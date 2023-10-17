https://friendly-mooncake-09e5ee.netlify.app



Function for display string base 64


function displayImageFromBase64(base64String) {
  // Create balise img
  const imgElement = document.createElement("img");
  // Assign Base64 string to image source
  imgElement.src = base64String;
  // Do whatever you want with the image, for example, add it to the DOM
  document.body.appendChild(imgElement);
}
