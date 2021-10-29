---
In PencilCode, every program is a web page. PencilCode allows programmers to seamlessly switch between “block” and “text” modes. The underlying text language is: CoffeeScript, JavaScript or HTML. You can switch between languages by selecting the gear icon in the blue bar at the top of the PencilCode coding environment.

<iframe src="https://giphy.com/embed/DrZ0bl2LCt0noFFV1L" width="480" height="350" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/DrZ0bl2LCt0noFFV1L"></a></p>

### PencilCode Syntax
---
Try the following basic commands in your PencilCode window. Press **run/play** to see the graphical output. Decide if you would rather work with text, blocks or both. 

**Sample Code #1:** Try this simple command below in the PencilCode window. 

![Sample Code](.guides/img/sampcode.png)

**Sample Code #2:** Try the following code but enter it into the text-based editor. Play around with changing the value of `n`, the `speed` and the color of the `pen`.
```
n = 6
speed 5 
pen purple
for [1..n]
  fd 100
  rt (360/n)
fill purple
```

Run your program by clicking the **Play** button in your PencilCode environment. 

![Play Button](.guides/img/playbutton.png)

### PencilCode Commands
---
Explore the different categories and blocks in the block-based editor! Having the ability to work with blocks allows for more exploration and experimentation. Here is a list of the most basic commands:

|Command|Parameter|
|:-----:|:-------:|
|`fd n`| The turtle moves forward `n` pixels. | 
|`rt n`| The turtle rotates to the right `n` degrees.  | 
|`lt n`| The turtle rotates to the left `n` degrees. |
|`speed n`| The turtle moves at a speed of `n`. |
|`bk n`| The turtle moves backward `n` pixels. |
|`pen c, n`| The turtle's movements are traced by `pen`, in color `c`, in width `n`. |
