# Vue Advanced Workshop

This is the companion repository to the Vue Advanced Workshop.

## Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/) version 6+

## 我的配置

我的前端学习笔记：
- [GitHub: PiperLiu/front-end-notes](https://github.com/PiperLiu/front-end-notes)

对于本 workshop 的笔记：
- [GitHub: PiperLiu/front-end-notes/vue2017/README.md](https://github.com/PiperLiu/front-end-notes/blob/master/notes/vue2017/README.md)

```bash
# fork
git clone https://github.com/d-levin/vue-advanced-workshop.git

cd vue-advanced-workshop

# 建立我的解决方案分支
git checkout -b piper

# 回滚到没有答案的版本
git reset --hard 49b3bb3a9

npm install
```

我看答案的话，去看 `49b3bb3a96fe5317` 这次 commit 删去了什么就行。

## Setup

1. Clone this repo:

  ``` bash
  git clone https://github.com/yyx990803/vue-advanced-workshop.git
  ```

2. Install dependencies (for automated tests):

  ``` bash
  cd vue-advanced-workshop
  npm install
  ```

## Usage

### Switching Between Work and Solution Branches

This repo contains two branches: the `master` branch is where you will be working on the exercises, and the `solutions` branch contains the full solutions to each exercise.

To jump to the `solutions` branch, use the following git command:

``` bash
git checkout solutions
```

To go back to the working branch:

``` bash
git checkout master
```

### Saving Your Work

As you work on the exercise, you will leave un-commited changes to the repo. Make sure to commit your changes before switching branches:

``` bash
git add -A
git commit -m 'working on exercise 1.1'
git checkout solutions
```

After viewing the hints from the `solutions` branch, you can then go back to the `master` branch to continue the exercise.

### Automated Tests

For each exercise there will be an automated test case to check if your implementation meets the requirements. To run the test for a given exercise (e.g. 1.1), run:

``` bash
npm test -- -t 1.1
```

You can also run the test in watch mode (which automatically re-runs the tests as you edit the files) with:

``` bash
npm run watch
```
