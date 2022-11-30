# lqual
Lower a image's quality.

<img src="https://user-images.githubusercontent.com/60672615/204927137-25b47847-8395-48af-ada9-330d433c942d.png" width=10% height=10%> <img src="https://user-images.githubusercontent.com/60672615/204928105-cae26a84-1193-4890-82e5-c286ee11619d.jpg" width=10% height=10%>

<img src="https://user-images.githubusercontent.com/60672615/204928631-4b10c7b2-38b8-43d7-b8e2-9e9f4228fe44.jpg" width=10% height=10%> <img src="https://user-images.githubusercontent.com/60672615/204928919-6ab3f45c-43e6-427d-b302-85346c21cde0.jpg" width=10% height=10%>

<img src="https://user-images.githubusercontent.com/60672615/204931234-baa67acd-19ec-4b09-9187-488447c8ac37.png" width=10% height=10%> <img src="https://user-images.githubusercontent.com/60672615/204931317-492f34b7-e0b3-4dfe-9f71-f50ceee45f13.jpg" width=10% height=10%>

#### Dependencies:

* [Pillow](https://pypi.org/project/Pillow/)

### Installation:
### Linux
Clone the project's repository and give the script execution permissions.
```
$ git clone https://github.com/VictorXPDE/lqual
$ cd lqual
$ chmod +x lqual
```
Now copy the script to `/usr/local/bin` or any other directory in your `$PATH`
```
$ sudo cp lqual /usr/local/bin
```

#### Usage:
```
lqual [-h] -m MULTIPLIER -q QUALITY [-l] input [output]

-h, --help            show this help message and exit
-m MULTIPLIER, --multiplier MULTIPLIER
                      the number that is going to be multiplied with the original resolution. (higher = lower resolution)
-q QUALITY, --quality QUALITY
                      the image's jpeg quality value. (lower = lower quality)
-l, --low-res         use this if you don't want the image to be resized back to its original size.
```
