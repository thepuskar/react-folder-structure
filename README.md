# ⚛ ReactJS folders structure boilerplate .

ReactJS application with intermediate folder structure.
Here is a full article where i explain all folders and their roles. [" Here "](https://yacouri.medium.com/reactjs-folder-structure-boilerplate-92d5dace5b7d)

<img src="https://cdn-images-1.medium.com/max/800/1*HJFGolt5ACH9eChLaN_JbQ.png" alt="ReactJS folders structure boilerplate">


- Structure: 
```
src/
├─ assets/
│  ├─ fonts/
│  ├─ images/
│  ├─ videos/
├─ components/
├─ config/
├─ containers/
├─ context/
├─ hooks/
├─ helpers/
├─ i18n/
│  ├─ en/
│  ├─ fr/
│  ├─ ar/
├─ layouts/
├─ pages/
├─ services/
├─ validations/
```


## Explaining each folder’s role 📁
Our focus will be in the src folder where we’re going to structure our folders.

### Folders structure
### 📁 Assets
- Here we group all of our media files. I personally prefer to create subfolders such as Images, Icons, Videos, Audios etc.... 
- You might want to put all of the components in one place, but you better break it into 2 folders. (Components & Containers).

### 📁 Components
- This folder contains all of our application presentational components (Stateless Components).
### 📁 Containers
- In this folder we have the Stateful components (Smart component) where we keep tracking the state.
### 📁 Constants
- In this file we group all constants like regex.
### 📁 Helpers
- Here we create and export functions that will be re-used in different places in our application.
### 📁 Hooks
- A folder made for customized hooks.
### 📁 Layouts
- It contains layout files such as Navbar, Footer, Sidebar .
Layouts are used to wrap a specific components.
### 📁 Pages
- This folder contains pages components like Home, Contact etc...
- Each page wrapped with a specific Layout
### 📁 Validations
- Here we write our form validation and rules using a library like Formik .
### 📁 Services
- In this folder we manage all of the API requests by creating files for each service.
### 📁 Context
- This folder contains all the context files where we manage and globalize the state in our application such as theming styles.
### 📁 Config
- All of our application configuration will be here in this folder.
### 📁 i18n
- This folder is made for multi-language support.
- You can create subfolders with a JSON file for each language you want to translate.
- Take a look to their Step by Step guide [HERE](https://react.i18next.com/latest/using-with-hooks). 

### ✨ Keep consistency in your code
- By adding Eslint & Prettier to your project it will give you :
  - A nice linting environment.
  - Correct bad coding practices.
  - Make your code clean and consistent.
