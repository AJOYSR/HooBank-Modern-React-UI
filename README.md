
# HooBank-Modern-React-UI
HooBank is a modern React UI designed for a fictional online banking application. The UI features a clean, minimalist design with a focus on usability and accessibility. The project uses Vite as the build tool and Tailwind CSS for styling, making it easy to customize and extend.

## Visiting Link
https://hoobank-ajoy.netlify.app/

## Introduction

HooBank is a modern React UI designed for a fictional online banking application. The UI features a clean, minimalist design with a focus on usability and accessibility. The project uses Vite as the build tool and Tailwind CSS for styling, making it easy to customize and extend.

* TailwindCSS 
* React 
* MaterialUI 
* React Icons



## Screenshots

![App Screenshot](https://i.ibb.co/nw8yYjZ/hoobank.png)


# Clone the project

```javascript
git@github.com:AJOYSR/HooBank-Modern-React-UI.git
```


## Prerequisites
Before starting with the application, the following technologies need to be installed on your system:

* Node.js (v14 or above)

# Installation
Clone the repository using the following command:

#### 1. Create a new React project with Vite by running the following command in your terminal:

```bash
  npx create-react-app hoo-bank --template vite

```
#### 2. Install all dependencies using node_modules:

```bash
  npm install 

```

This will create a new React app with Vite as the build tool.

#### 3. Install Tailwind CSS and its dependencies by running the following command in your terminal
```bash
  npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

```
This will install the latest version of Tailwind CSS, PostCSS, and Autoprefixer as development dependencies in your project.


#### 4. Create a Tailwind CSS configuration file by running the following command in your terminal
```bash
npx tailwindcss init -p
```
This will create a new __tailwind.config.js__ file in the root of your project, which you can use to customize Tailwind's default configuration.

#### 5. Import Tailwind's base, components, and utilities styles into your project by creating a new __index.css__ file in your __src__ directory with the following content:
```bash
@tailwind base;
@tailwind components;
@tailwind utilities;

```
This will import all of Tailwind's pre-defined styles into your project, which you can use to style your UI components.


#### 6. Import the __index.css__ file into your __index.js__ file by adding the following line at the top of the file:
```bash
import './index.css';

```
This will ensure that Tailwind's styles are applied to your React components.


#### 7. Start the development server by running the following command in your terminal
```bash
  npm run dev

```

This will start the Vite development server, which will automatically compile your React app and reload the browser whenever you make changes to your code.

#### 8.Build the production-ready version of your app by running the following command in your terminal
```bash
  npm run build

```
This will create a new build directory in your project's root directory, which contains the optimized and minified version of your React app that you can deploy to a web server
