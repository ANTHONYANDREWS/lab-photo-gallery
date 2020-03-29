![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | Angular Introduction - Photo Gallery



## Learning Goals

After this lesson, you will be able to:

- Create a static Angular application with Angular CLI.
- Build an Angular application with one component.

## Requirements

- Fork this repo.
- Clone this repo.

## Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "done"
$ git push origin master
```

Navigate to your repo and create a pull request from your master branch to the original repository's master branch.

In the pull request name, add your Prograd id, name, and last name separated by a dash "-".

## Deliverables

You need to generate the starter code and fill it with the necessary code to satisfy the requirements described below.

## Introduction

In this lesson we are going to work with Angular for the first time. The goal here is to work on a small projects where you can practice the concepts we've learned thus far.

## Starter Code

To generate the starter code, follow the steps given below

- To create a new application,
    - Open your ubuntu or cmd terminal and execute the following command
      - ```ng new app-name```
      - for example, ng new super-wars
    - To create a new component, execute the command 
      - ``` ng generate component component-name```
      - example, ng generate component contacts
      
## How to run

- To run the project go to your ubuntu terminal or VScode editor
    - open the ubuntu or cmd terminal or inside the vscode editor
    - run the command following command
    - ```ng serve --open or ng serve -o```


## PROGRESSION #1: PHOTO GALLERY

In the first progression we are going to build a photo album. Imagine you have an album at home. On it, you can find a photo by yourself or you can use the images given inside the src/assets folder. This is what we are going to build.

We will build this album in the `AppComponent` component. The album will have mutilple photos, and **it's not necessary to have an array to store these values**.

Easy, right? Add some styles to the page to give your photo album a little flair!

## PROGRESSION #2: HEADER and FOOTER (Optional)
In the second progression we are going to generate two component header and footer. Have the page heading inside the header part and the 
'Made with by ❤️ ProGrads' in the footer part



Happy Coding ProGrad ❤️
