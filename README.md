# React To Do list

## How to start

Create your React project using: `npx create-react-app todo`.

Change to your app directory with `cd` and run your project with `npm start`

## 1. Setting up your ToDo app

You need to show:
  - An input where the user will be able to write his todo.
  - A button to submit this todo. Once pressed the todo will be stored in the component state

  > **HINT**: Check the `onChange` and `onSubmit` method to achieve that.

## 2. Showing your ToDo's

Once you are able to store as many todo's as you write in the input (think of the best datatype to store them) you should try to display all of them.

Every time you write a new todo, it should appear on the todo's section

## Bonus!

You could create some logic in order to show a text like: *You did not add any todo yet* if your todo's are empty. This text will disappear if you add a todo (this todo will be shown instead)

## 3. Delete a ToDo

Each todo that you display, should have a button right after it, if you click that button, that todo will be deleted.

## Extra Bonus 1: Add a category per todo

You should refactor you app in order to also show a selector that includes a category for that todo (feel free to add as many todo categories as you would like). It could like this:

![ToDo](https://i.imgur.com/ujXp6Qo.png)

  > **WARNING**: You will also need to rethink on how do you store you todo in the state, since it is not only a string anymore, it is the todo and the category associated to it.

## Extra Bonus 2: Filter ToDo's based on categories

You should see all your categories on a different panel.
Depending on which category you click, you will only see the todo's related to that category.

You should also add a `All` category to display all the todo's that you have (this could be the default category)


![Imgur](https://i.imgur.com/riTMe4G.png)
