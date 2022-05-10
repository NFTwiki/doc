# participate in contribution

> If the following content is too obscure to understand and difficult to implement, please register and log in to the [Issues](https://github.com/NFTwiki/doc/issues) page and click the green button [New issue](https://github.com/NFTwiki/doc/issues/new/choose) to submit the content directly.

The open source source of this tutorial is hosted on Github, welcome to participate in the maintenance: [NFTwiki/doc] (https://github.com/NFTwiki/doc).

First, `fork` as your own repository, such as `yourname/doc`, on GitHub. Then `clone` to your computer, and set the user information.

```sh
$ git clone git@github.com:NFTwiki/doc.git
$ cd Tutorial
$ git config user.name "yourname"
$ git config user.email "your email"
```

Commit the updated content and push it to your repository.

```sh
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```

Finally, submit the pull request on GitHub website.

In addition, it is recommended to update the contents of your own repository regularly with the contents of the project repository.

```sh
$ git remote add upstream https://github.com/NFTwiki/doc
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```