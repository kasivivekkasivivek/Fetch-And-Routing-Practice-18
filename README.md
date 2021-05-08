In this assignment let's practice a **Fetch and Routing** 

### Refer to image below:
** https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-output.gif **
<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-output.gif" alt="routing-practice-blog-list-desktop-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>
#### Data Fetch URLs

- `https://apis.ccbp.in/blogs`
- `https://apis.ccbp.in/blogs/[id]`


### Design Files

- [Extra Small (Size < 576px) and Small (Size >= 576px) - Blog List](https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-sm-blog-list-output.png)
- [Extra Small (Size < 576px) and Small (Size >= 576px) - Blog Item](https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-sm-blog-item-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Blog List](https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-lg-blog-list-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px) - Blog Item](https://assets.ccbp.in/frontend/content/react-js/fetch-and-routing-practice-lg-blog-item-output.png)

### Project Set Up Instructions

- Download dependencies by running `npm install`
- Start up the app using `npm start`

### Project Completion Instructions

#### Add Functionality

The app must have the following functionalities

- In the `HomeRoute` blog list should be displayed by fetching data (HTTP GET
  request).
- Should navigate to the respective blog post when clicked on a blog in the blog
  list.
- In the `BlogItemRoute` blog item details should be displayed by fetching data
  (HTTP GET request).
- A Loader should be displayed while fetching blog list and blog item data.
- Your task is to complete the implementation of

  - `src/App.js`
  - `src/components/Home/index.js`
  - `src/components/BlogList/index.js`
  - `src/components/BlogList/index.css`
  - `src/components/BlogItem/index.js`
  - `src/components/BlogItem/index.css`
  - `src/components/BlogItemDetails/index.js`
  - `src/components/BlogItemDetails/index.css`

> #### Important Note
>
> - `HomeRoute` should consist of "/" in URL path
> - `AboutRoute` should consist of "/about" in URL path
> - `ContactRoute` should consist of "/contact" in URL path
> - `BlogItemDetails` should consist of "/blogs/:id" in URL path
> - No need to use the `BrowserRouter` in `App.js` as we have already included
>   in `index.js` file
> - Wrap the Loader component with an HTML container element and add the
>   `testid` attribute value as `loader` to it as shown below
>
> ```
> <div testid="loader">
>      <Loader type="TailSpin" color="#00BFFF" height={50} width={50} />
> </div>
>
> ```





#### Colors

<div style="background-color: #8e8e8e; width: 150px; padding: 10px; color: white">Hex: #8e8e8e</div>
<div style="background-color: #000000; width: 150px; padding: 10px; color: white">Hex: #000000</div>
<div style="background-color: #d3d3d3; width: 150px; padding: 10px; color: white">Hex: #d3d3d3</div>
<div style="background-color: #2f4f4f; width: 150px; padding: 10px; color: white">Hex: #2f4f4f</div>

#### Font-families

- Roboto


