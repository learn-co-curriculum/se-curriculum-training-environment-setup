# Environment Setup

There are a few tools you'll need in order to work on the curriculum. We'll also
introduce more tools throughout this course to help you solve specific problems.

## Git

We'll assume that you have Git and a GitHub account already set up, but now's a
good time to check a few configuration settings. Run this:

```console
$ git config --list
```

Verify that you've set your `user.name` and `user.email` correctly (they should
match your full name and the email you use for your GitHub account). If not, set
them:

```console
$ git config --global user.email "email@example.com"
$ git config --global user.name "Full Name"
```

You should also check that `init.defaultbranch` is set to `main` (we use `main`
as the default branch for newly created lessons). If not, set it:

```console
$ git config --global init.defaultBranch main
```

## GitHub

You'll need to be a member of the learn-co-curriculum GitHub organization in
order to maintain our curriculum repositories. You can check if you're a member
here:

- [https://github.com/orgs/learn-co-curriculum/people](https://github.com/orgs/learn-co-curriculum/people)

If you're not, ask someone on the curriculum team to give you access.

We'll also use the GitHub CLI to interact with GitHub when authoring and
maintaining curriculum. Follow the installation and configuration steps here:

- [gh cli install instructions](https://cli.github.com/manual/)

## Node

We use [nvm](https://github.com/nvm-sh/nvm) to manage Node versions. If you
don't have it installed already, install it:

- [nvm install instructions](https://github.com/nvm-sh/nvm#installing-and-updating)

And use it to download the latest LTS version of Node:

```console
$ nvm install --lts
```

## Ruby

We use [rvm](https://rvm.io/) to manage Ruby versions. Even if you're not
maintaining Ruby curriculum, you'll need Ruby since several of our internal
tools are Ruby gems. If you don't have rvm installed already, install it:

- [rvm install instructions](https://rvm.io/rvm/install)

And use it to download the most recent Ruby 2.7 version:

```console
$ rvm install 2.7.4
```

## Conclusion

Congrats! You've now got a good baseline setup to continue on with the course.
We'll be adding more tools along the way to help with specific tasks as well.
