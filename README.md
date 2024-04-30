# azure-face-api

## overall flow
* detect face with image url -- first input an image and detect the face
* compare face with person -- verify the face is a given person and output confidence

## Issues
* Azure Face API image input structure
  * is looking for image of structure: https://raw.githubusercontent.com/van-william/azure-face-api/main/test_images/william_test.jpeg
  * How is this achievable with connector functions?

* Azure Stream API Image input is looking for octet-stream (https://learn.microsoft.com/en-us/rest/api/faceapi/face/detect-with-stream?view=rest-faceapi-v1.0&tabs=HTTP)
  * Is it possible to convert images to this structure within a custom widget?
