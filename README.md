Dependencies:
Node 9.4.0 [https://nodejs.org/en/download/]
Imagemagick [https://www.imagemagick.org/script/download.php]

Running the test app

```
$ npm start
=> http://localhost:3000
```

Running test suite

```
$ npm test
```

Run tests in watch mode

```
$ npm test -- -w
```

After running test suite, you can review generated images in the `__images__/output` folder.

To accept new images, you must manually copy and rename the image file into the `__images__/baseline` folder. You can also run the following convenience script, and then re-run the tests

```
$ ./update-baseline.sh
```

To reset the baseline test images, you can run the following convenience script

```
$ ./reset-baseline.sh
```
