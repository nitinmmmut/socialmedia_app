# socialmedia_app

Task
Create a multi-page React app that fetches data from an API and displays it in different views, using React Router and Redux to manage state and routing.

Problem Statement
You have to use React Router to create multiple routes and views for your app. Your app should have the following views:
A home page that displays a list of items fetched from an API.
A detail page that displays information about a single item.
Your app should have two routes:
`/` - The home page.
`/item/:id` - The detail page for a specific item, where `:id` is the ID of the item.

Use Redux to manage the app's state. You should create at least one Redux store to hold the data you fetch from the API and use it to populate your views.

Fetch data from an API using Redux Thunk middleware. Use the `fetch` method to get the data from the following API endpoint: `https://jsonplaceholder.typicode.com/posts`.
The data returned from the API will be an array of objects. Each object will have the following properties:
`userId`: The ID of the user who created the post.
`id`: The ID of the post.
`title`: The title of the post.
`body`: The body of the post.
`imgSrc`: Since the image is not coming in the api result use this as your image src in the post component - https://picsum.photos/200?random=${post.id} where [post.i](http://post.id/)d is the id given in the object returned by api.
You should create a Redux action to fetch the data and update the Redux store with the fetched data.

Display the data in your views using React components. You should create separate components for each view, and use React Router to navigate between them.
The home page should display a list of items, with each item displaying the title of the post. Clicking on an item should take the user to the detail page for that item. Make sure that you don’t show the entire title and the entire description as it will not look nice. Slice it and show it. As shown in the UI. Add “Read More…” if the entire description doesn’t fit inside the card view.
The detail page should display the title and body of the post, as well as the ID of the user who created the post.

Add styling to the website as shown in the figma

Make sure your app is responsive and works well on both desktop and mobile devices. Also manage the loading state properly using redux as well.
Design Links
Figma Link:
https://www.figma.com/file/HywHp4NEMyXhcBNaaPC65a/F4---Module-Test---May?type=design&node-id=0-1&t=LUG462Sserb2mw7U-0
