# Draw Cake
Use OpenCV to draw a cake. Can be used to celebrate birthdays for friends.<br>
Written in Python, you can use Colab to run this program.<br>
<br>
<img src=""  alt="Execution Result" />
<br>
<h2>How to use?</h2>
1.Generate a background.<br>
    background = make_background(`width`, `height`, `R`, `G`, `B`)
<br>
2.Draw a cake. <strong>offset_x</strong> and <strong>offset_y</strong> are the offsets of the coordinates. You can adjust the position of the cake through these two variables.<br>
    img = draw_cake(background, `offset_x`, `offset_y`)
<br>
3.Write your blessings.<br>
    str = 'Happy Birthday!!!'<br>
    img = print_blessings(img, str, `x`, `y`, `size`)
<br>
4.Show the image.<br>
    show_img(img)
