# Web site test


## Prerequisites

1.  [Nodejs version 14.17.6 (latest LTS) and NPM](https://nodejs.org/en/)

2.  [Git](https://git-scm.com/​)

## Steps to run locally

 
1. Clone the project [website-design](https://github.com/lizandro94/website-design)
```bash

git clone https://github.com/lizandro94/website-design

```
  2. Open repo folder
```bash

cd website-design/

```

3. Install dependencies
```bash

npm install

```
4. Cancel boilerplate wizard: After running `npm install` the setup wizard will run automatically, please cancel this by typing:
```bash

ctrl + c

```
 
5. Run the development server
```bash

npm run start

```

**Note:** If wizard is not cancelled (step 4), some files may be overwritten. In this case, just discard all changes before running `npm run start`

 ## Build for production
To build a production-ready version, run the following command in the project’s root directory:
```bash

npm run build:dist

```
An optimized version of the site will be generated in `dist/` folder