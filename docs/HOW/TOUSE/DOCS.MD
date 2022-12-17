# How to use it?

First, you need to know what Android versions are supported.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | :x:                |
| 4.0.x   | :x: |
| < 4.0   | :x:                |

Also, you need to know where you install GitConnect24.


Like in a GitConnect24 folder.
![](https://firebasestorage.googleapis.com/v0/b/plus-6aaf1.appspot.com/o/20221211_112520.jpg?alt=media&token=4e74894d-0d2c-4c7a-bd85-c896a0aed9ca)

After that, download the first and third packages.

Place it in your GitConnect24 folder.

![](https://firebasestorage.googleapis.com/v0/b/plus-6aaf1.appspot.com/o/20221211_113449.jpg?alt=media&token=a1d30f24-8b10-4f4d-9e84-68dae56fbf4c)

And why not download the second package?

Beacause the second package is for installing the service with ADB (Android Debug Bridge)

Now create a new file (named LIT.MANIFEST)

![](https://firebasestorage.googleapis.com/v0/b/plus-6aaf1.appspot.com/o/20221211_114032.jpg?alt=media&token=b41fe988-de53-4591-9f05-2f5b599a66b0)

Make sure that the file is in the root of the folder.

![](https://firebasestorage.googleapis.com/v0/b/plus-6aaf1.appspot.com/o/20221211_115041.jpg?alt=media&token=b9f8cbc2-fe9e-4959-afdd-20bdd10cacd5)

Now, open the file, then, write the following text:

![](https://firebasestorage.googleapis.com/v0/b/plus-6aaf1.appspot.com/o/20221216_171837.jpg?alt=media&token=8836a4d9-827f-4fed-b681-8943d37d82af)

Just to say, the "Hello World!" text is only for testing that it's works, if it work for you, skip to part 4.

## Part 2

You need to test your app, so, install Carrier Services, then, install Terminal Emulator.

In Terminal Emulator, execute:

```bash
git install app_ABC123
git run app_ABC123
```
If "Hello World!" text appears, skip part 3, if it's dosen't appears, skip nothing.

## Part 3

If your app dosen't work, verify your Terminal version.

For help you, here is the table with supported versions.

| Version | Supported          |
| ------- | ------------------ |
| 5.1.x   | :white_check_mark: |
| 5.0.x   | Depracted                |
| 4.0.x   | :x: |
| < 4.0   | :x:                |
| 3.6.x   | Depracted                |
| < 3.2   | Depracted                |
| 2.6.x   | :white_check_mark: |
| < 2.4   | :x:                |
| 1.6.x   | Depracted                |
| < 1.5   | :x:                |
| 1.2.x   | :x:                |
| < 1.1   | :x:                |
| 0.6.x   | Depracted                |
| < 0.5   | :x:                |

Now, verify your Terminal version.

If it's not that, verify [this](https://github.com/AmixemHello/gitconnect24/wiki/What-versions-of-Git-are-supported%3F).

## Part 4
