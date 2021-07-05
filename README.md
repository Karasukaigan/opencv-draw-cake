# Draw Cake
Use **OpenCV** to draw a cake. Can be used to celebrate birthdays for friends.<br>
Written in **Python**, you can use **Colab** to run this program.<br>
<br>
<img src="https://github.com/Karasukaigan/opencv-draw-cake/blob/main/execution_result.png"  alt="Execution Result" />
<br>
## How to use?
**1.Generate a background.**<br>
*background = make_background(`width`, `height`, `R`, `G`, `B`)*<br>
<br>
**2.Draw a cake. `offset_x` and `offset_y` are the offsets of the coordinates. You can adjust the position of the cake through these two variables.**<br>
*img = draw_cake(background, `offset_x`, `offset_y`)*<br>
<br>
**3.Write your blessings.**<br>
*str = 'Happy Birthday!!!'*<br>
*img = print_blessings(img, str, `x`, `y`, `size`)*<br>
<br>
**4.Show the image.**<br>
*show_img(img)*<br>
