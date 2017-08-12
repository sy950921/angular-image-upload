# angular-image-upload
An angular image uploader directive for cropping and upload base64 by zooming in, zooming out and draging the image.

Demo
=======
![](https://github.com/licaomeng/angular-image-upload/blob/master/Angular-img-uploader.gif)

How to demo
=======
STEP 1: Install npm on your device first;

STEP 2: Command `npm start` on root path;

STEP 3: Access `localhost:9000` with your browser, then you can see the same scene as demo.

Usage
=======
STEP 1: Add `imgZoomCanvas.js` which realize critical function such as zooming and dragging to your module.

STEP 2: You can copy the whole folder `/imgUploader` to your project, imgUploader is a directive which realize angular-image-upload business logic including add, delete, zoom, upload image file. you can also customize them by yourself.

STEP 3: Add this directive to the page, like below:

```
<img-uploader on-upload="upload(image, isDelete, isHasAvatar)" image="image" is-editable="isEditable"></img-uploader>
```


License
=======

    Copyright 2017 Caomeng Li

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
