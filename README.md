# Gaussian Blur

```sh
gray = cv2.cvtColor(image_copy, cv2.COLOR_RGB2GRAY)
blur_img = cv2.GaussianBlur(gray, (5,5), 0)

f, (ax1, ax2) = plt.subplots(1, 2, figsize=(20,10))

ax1.imshow(gray, cmap="gray")
ax1.set_title("Original")

ax2.imshow(blur_img, cmap="gray")
ax2.set_title("Blured Image")
```

![ss1](https://user-images.githubusercontent.com/47830409/63856516-78cf8500-c9aa-11e9-8ad9-5f7482eec644.PNG)
