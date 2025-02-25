# Thumber

Create thumbnails. Specify dimensions or aspect ratio. If the aspect ratio from the inout image is altered, fills the background with the same image, but blurred.

Install using pip:

```
pip install thumber
```

## Usage

```
thumber <mode> <input_image> [<final_width> <final_height> | <aspect_ratio>] [blur_radius]
```

Examples:

To produce a 1920x1080 image:

```
thumber dimensions square.jpg 1920 1080 --blur=30
```

To produce an image whose width is 1.778x the height:

```
thumber aspect square.jpg 1.778 --blur=30
```

The closer to 0, the lower is the blur effect


## Gallery Examples


| `babel.webp` (1024x1024)| `babel-dimensions-1920x1080.webp` | `babel-aspect-0.5.webp` | `babel-aspect-2.webp`
|:----:|:----:|:-----:|:----:| 
| ![](assets/babel.webp)| ![](assets/babel-dimensions-1920x1080.webp) | ![](assets/babel-aspect-0.5.webp) | ![](assets/babel-aspect-2.webp)


## License 

This project is licensed under the MIT License.
