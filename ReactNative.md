React Native is an open-source framework developed by Facebook that allows developers to build mobile applications using JavaScript and React. It enables the creation of native mobile apps for both iOS and Android platforms using a single codebase, which can significantly reduce development time and effort.

Key features of React Native include:

1. **Cross-Platform Development**: Developers can write most of the code once and deploy it on both iOS and Android, which increases efficiency and consistency across platforms.

2. **Native Components**: React Native provides a set of pre-built native components like buttons, text, and images, which can be used to build the app's user interface. It also allows integration with existing native code, so developers can include platform-specific features when needed.

3. **Hot Reloading**: This feature allows developers to see the changes they make in the code immediately, without recompiling the entire app. It speeds up the development process and makes it easier to experiment with different UI designs.

4. **Performance**: While React Native apps are not purely native, they often provide performance close to native apps. This is because React Native components are backed by native views, and the JavaScript code runs in a separate thread.

5. **Large Community and Ecosystem**: Being open-source and widely adopted, React Native has a large community that contributes to its ecosystem, including libraries, tools, and plugins that extend its functionality.

React Native is a popular choice for many companies and developers looking to build mobile apps because it offers a balance of performance, ease of use, and efficiency.

The main difference between React and React Native lies in their purpose and the platforms they target:

1. **Purpose and Platform**:
   - **React**: React, also known as React.js or ReactJS, is a JavaScript library primarily used for building user interfaces for web applications. It focuses on the view layer of web applications, allowing developers to create reusable UI components. React is used in conjunction with other libraries or frameworks for state management, routing, and other aspects of web development.
   - **React Native**: React Native is a framework for building native mobile applications for iOS and Android using JavaScript and React. It enables developers to write most of their code once and run it on both platforms, leveraging native components for performance and a native look and feel.

2. **Rendering**:
   - **React**: React renders HTML for web applications. It uses a virtual DOM to optimize rendering and updates the actual DOM based on changes in the application's state or props.
   - **React Native**: React Native does not render HTML; instead, it renders native components specific to the platform (iOS or Android). This means that the UI components in React Native translate to native components like `UIView` in iOS or `View` in Android.

3. **Components and APIs**:
   - **React**: React uses web-specific components and APIs, such as `<div>`, `<span>`, `<input>`, and the DOM.
   - **React Native**: React Native provides a different set of components and APIs that correspond to mobile UI elements, such as `<View>`, `<Text>`, `<TextInput>`, and `<ScrollView>`. It also includes platform-specific APIs and modules, allowing developers to access native device functionalities like the camera, GPS, or sensors.

4. **Styling**:
   - **React**: Styling in React is typically done using CSS or CSS-in-JS libraries. The styles are applied to HTML elements.
   - **React Native**: React Native uses a style system similar to CSS but tailored for mobile development. Styles are written in JavaScript and applied to components using a subset of CSS properties, with some differences due to the mobile context.

5. **Deployment**:
   - **React**: React applications are deployed on web servers and accessed via web browsers.
   - **React Native**: React Native applications are compiled into native code and deployed through app stores (such as the Apple App Store and Google Play Store) as standalone mobile apps.