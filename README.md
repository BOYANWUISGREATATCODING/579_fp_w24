Overview: 
Our team developed a memes search engine application designed to provide users with a fast and efficient tool for discovering and interacting with a wide array of memes. The application, developed as a React web application, integrates various features such as meme searching, rating, and sorting functionalities. The primary objective was to blend entertainment with functionality, offering a user-friendly interface for meme enthusiasts.

Achievements:
Our search engine for memes has a user-friendly interface that was created with the user's convenience in mind. The first achievement is the sidebar menu. This UI feature offers quick access to various functions. Users can easily navigate to the Funny Gallery to view a collection of funny memes or go to the Favorite Memes section to revisit their personal favorites. (see files in the directory /src/components/sidebar.js).
In terms of personalization, our application stands out by allowing users to customize their meme discovery process. The application includes a dropdown menu that offers 2 APIs for users to choose from, and allows them to fetch and display memes that match their individual preferences(see files in the directory /src/components/SearchEngine.js and constants.js). This feature is important as it not only caters to personal tastes but also integrates a variety of meme sources.
Additionally, the application's dynamic nature is demonstrated through its rating and sorting system, giving users the freedom to evaluate memes based on humor, aesthetics, and personal preference. The use of state management techniques allows the front end to update instantly to ensure a seamless and uninterrupted user experience. (see files in the directory /src/components/Gallery.js,FavoritesGallery.js, DeleteMeme.js,Grading.js,)
Another achievement is the CSS hover effects that added to this interactivity. It provides a tactile response as users select and navigate through different components. To further engage users, we carefully designed the typography and layout, strategically placing headers at the top of each page to guide their journey through the content. Each meme is presented within a distinct frame and footer so as to create a gallery-like effect and organized appearance. (see each CSS file specific in component /src/components, SearchEngine.js)
With the application's color scheme, consistency in design was achieved by employing a dark blue color scheme across all selectable options, with a balanced contrast of white and black background color against the blue theme( see files in the directory /src/components/App.css)


Challenges:
Custom API Integration: One of our objectives was to allow users to add their own list of APIs for a more personalized experience. However, we encountered difficulties in implementing a secure and efficient way to integrate various APIs externally. While users are free to select and choose the API of their choice, they need to be aware of their API scalability and readability. Thus, this application is intended to target mid-experienced users who have a little bit of skilled knowledge of API setup.
The large image size piles up the local storage within only a few images. Resolved by downsizing the images that were originally 1MB to only around 100Kb and thus enlarging the local storage saving load. 

Future Enhancements:
In the design spectrum, we managed to set up the parameters where users can freely control and add their memes on the left sidebar in a limited range. However, the app was still yet unmanageable on various devices such as mobile phones. Thus, our team would consider enhancing this responsive design to ensure the application is accessible on various devices and adjustable to different screen sizes.
Another aspect we could focus on is to make the process of adding a different rating aspect more generic. The implementation of the rating system is basically controlled by Grading.js and Gallery.js, which are already generic to some point. However, the current version still needs to modify other javascript files to add another rating aspect. The ideal process I want to accomplish is to smoothly complete the process by making minimum modifications to other files. 
One last thing we would like to improve is that currently, our website cannot deal with CORS-related images. Since these images have proxies that are forbidden to be saved to local storage. One potential solution we could come up with is to save the URL of the image rather than the image itself to the local storage and render the image every time when necessary. The “Feeling Lucky” button means that the fetched API and images are chosen randomly, thus more clarity should be given when users select.




Conclusion:
	This meme search application represents a progressive step toward creating an engaging and dynamic platform for meme discovery. While there are some challenges and undesirable outcomes, our teams wish this application to provide basic functionality that reflects the learning materials and facilitates user engagement and entertainment. 



Reference:
SI 579 Project
Github Deploy Link and Source Code: linus-xzx.github.io/579_fp_w24

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
