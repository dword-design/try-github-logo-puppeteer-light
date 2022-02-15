# try-github-logo-puppeteer-light

Minimal example of GitPod manipulating an external image.

`file.png` contains the file downloaded from https://github.blog/wp-content/uploads/2019/01/cropped-github-favicon-512.png?fit=32%2C32 locally.

Open the project in GitPod. It will automatically run `yarn start`, which will download the file from above via `wget`. Now you have Git changes although `file.png` should stay the same.

You can also run `yarn start` manually again.

In case you want to make sure that `file.png` is really the file from the GitHub server, you can download it locally and drag it into GitPod.
