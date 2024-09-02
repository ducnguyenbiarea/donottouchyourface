<div align="center">

  # DO NOT TOUCH YOUR FACE
   ![image](https://github.com/user-attachments/assets/295d142e-138a-4439-a5fe-45fa8fab3a73)

</div>

## Overview
We often touch our faces as a natural habit. This can spread many infectious pathogens, such as COVID-19, the flu, herpes simplex, or exacerbate pre-existing skin conditions like acne, impetigo, and boils.

Many infectious disease experts warn that the eyes, nose, and mouth are entry points for viruses such as COVID-19 and SARS.

Let's imagine a person infected with a disease using an elevator, sneezing or pressing the buttons both outside and inside. When that person leaves, tiny droplets containing the virus remain. The next person presses those buttons or touches the surfaces and carries the virus on their hands, then scratches their nose, rubs their eyes, or touches their mouth. Studies show that each time you touch your eyes, nose, or mouth, you give the virus 11 chances per hour to enter your body.

As the world faces the spread of the COVID-19 pandemic, avoiding touching your eyes, nose, and mouth is one of the key recommendations from the U.S. Centers for Disease Control and Prevention, the World Health Organization, and the Vietnamese Ministry of Health.

Not only does this habit increase the risk of infectious diseases, but it also worsens other skin conditions. Touching or popping pimples spreads the bacteria *Cutibacterium acnes*—the main culprit causing inflammatory pimples, pustules, nodules, and cysts. In cases where you are infected with the herpes simplex virus on the lips or genitals, accidentally touching your eyes can cause herpes keratitis, which, if not treated promptly, can lead to reduced vision or blindness.

Therefore, I have an idea about create a demo machine learning project that helps prevent touching our faces. It will make a "Hey, Tay (HAND)" voice every time you touch your face, to warn you, and the background around the app will turn red to help you be more aware of accidentally touching your face.
## Feature
I have built many features for the app, some of it can be listed here:
- Small screen (connected to your camera)
- Train 1 button
- Train 2 button
- Run button
To see more about the features, please read the How to use section.
## How to use
-	When you log in to the website, the home page will display like this:
  ![image]( https://github.com/user-attachments/assets/b2c91f90-b7e2-4ded-b3fc-b08c9b282cdb)
 	
- It will ask for camera access, then you must accept it. After that, camera will be in use, and it will ask for access to show notification (this is typically effect when you let the app running, do something else in another tab and touch your face, it will say "Hey, Tay (HAND)", and send notification to your current tab the message: "Bạn đang chạm vào mặt mình, Bỏ tay ra! (You are touching your face, get your hand off!)").

    ![image](https://github.com/user-attachments/assets/6c6f1fe8-4786-4145-85be-2431b6faea1b)

- Continue allow access. Now it will look like this:
  
  ![image](https://github.com/user-attachments/assets/99bfb1d8-f697-421d-9b50-eb1dc6726a24)
  
- Now, you have to be in the camera, and don't raise your hand or let it be in the camera. Then, you press the train 1 button. After about 5 seconds (it has done the process learning about your face data and analyse it), you let your hand in front of the camera but please don't touch your face, just do like this:
  
  ![image](https://github.com/user-attachments/assets/e3327a96-e493-475b-87fc-544805265996)
  
-	Following this, you press the train 2 button and gradually touch your face:
  
   ![image](https://github.com/user-attachments/assets/4231c82a-7f96-469f-8622-275eec71a603)

-	Finally, you press the run button, and see what happens when you touched or not touch your face:
- When you don't touch your face, it's still normal. But when you touched your face slow or fast, It will make a "Hey, Tay (HAND)" voice every time you touch your face, to warn you, and the background around the app will turn red to help you be more aware of accidentally touching your face.
   ![image](https://github.com/user-attachments/assets/295d142e-138a-4439-a5fe-45fa8fab3a73)
- Even when you are not in the app but still let the app running, do something else in another tab and touch your face, it will say "Hey, Tay (HAND)", and send notification to your current tab the message: "Bạn đang chạm vào mặt mình, Bỏ tay ra! (You are touching your face, get your hand off!)").
  ![image](https://github.com/user-attachments/assets/de6ee099-8535-460e-9ae3-bd1741871a3a)

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






## Contact
If you have any idea or find any mistake in the project, please tell me via:
- Email: nguyentriduc92004@gmail.com
- Facebook: https://www.facebook.com/ducbiarea3009?mibextid=LQQJ4d<div align="center">

  # ~~~ Thanks for visiting my repo ~~~
  
</div>


