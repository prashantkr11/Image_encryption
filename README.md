# Image_encryption
# Image Encrption using Chaotic Map

* We are using different chaotic Maps to generate key here
* We wil encrypt the image pixel-wise. For each pixel there will be a unique key and that key will be generated using the constants from chaotic map
* The chaotic map  we are using here is Logistic Map
* Here the key will depend on two variable those are the intial point where to start and the value of r(rate)

 $X_{n} = {r}*X_{n-1}*(1 - X_{n-1})$

 * For chaotic map  we have to take the value of r in certain range
 * the range will we usually between 3.54 to 4
 * But not for all value between the range because there are some value of r where the map will give periodic output and we can't get chaotic map
