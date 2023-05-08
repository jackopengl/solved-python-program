Download Link: https://assignmentchef.com/product/solved-python-program
<br>
<ol>

 <li>Modify your first program to print a table of the words of an input file in alphabetical order with the count of each word. Case should be ignored. A sample run of the program might look like this:</li>

</ol>




<table width="576">

 <tbody>

  <tr>

   <td width="576">Please enter a file: data.txta 8about 1after 1all 2always 1and 9are 1asked 1balance 1bank 1be 2because 3began 1better 1between 1by 1can 2cannot 1change 3…</td>

  </tr>

 </tbody>

</table>







data.txt

<table width="576">

 <tbody>

  <tr>

   <td width="576">My mentor Earl Shoaff taught me that it’s not what happens that determines the major part of our future, because what happens, happens to us all. Instead, he taught me that the key is what we do about it. If we start the process of change by developing a plan, doing something different the next year than we did the previous year, it won’t matter how small those efforts start. Start doing different things with the same set of circumstances — the ones we’ve always had and cannot change — and see what miracles occur. If we start the miracle process and change ourselves, then everything changes. And here’s what is interesting: The difference between failure and success is subtle.…Remember that your plan is the roadmap for how you are going to get to your goals, so you have to have them. Of all the things that changed my life for the better (and most quickly), it was learning how to set goals. Mastering this unique process can have a powerful effect on your life, too. I remember shortly after I met Mr. Shoaff, he asked me if I had a list of my goals, and of course I didn’t. He suggested to me that because I lacked a set of clearly defined goals that he could guess my bank balance within a few hundred dollars… and he did! Well, Mr. Shoaff immediately began helping me define my view of the future, my dreams. He taught me to set goals because it is the greatest influence on a person’s future and the greatest force that will pull a person in the direction that they want to go. The future must be planned, well designed to exert a force that pulls you toward the promise of what can be.<a href="https://www.success.com/article/rohn-it-only-takes-6-steps-to-plan-your-success">https://www.success.com/article/rohn-it-only-takes-6-steps-to-plan-your-success</a> </td>

  </tr>

 </tbody>

</table>




<ol start="2">

 <li>Write a program that has three functions: sepia(), remove_all_red(), and gray_scale().</li>

</ol>




Sepia Tone images are those brownish colored images that may remind you of times past. The formula for creating a sepia tone is as follows:




newR = (R × 0.393 + G × 0.769 + B × 0.189)

newG = (R × 0.349 + G × 0.686 + B × 0.168)

newB = (R × 0.272 + G × 0.534 + B × 0.131)




Red removal from an image:




Simply set the R component to 0.




Gray scale conversion:




newR = (R × 0.289 + G × 0.587 + B × 0.114)

newG = (R × 0.289 + G × 0.587 + B × 0.114)

newB = (R × 0.289 + G × 0.587 + B × 0.114)







<em> </em>

<em>Hint:</em> Remember that rgb values must be integers between 0 and 255.

You can get each pixel by using p = img.getPixel(col, row)

Components of each pixel can be retrieved by p.getRed(), p.getGreen(), p.getBlue()




<table width="576">

 <tbody>

  <tr>

   <td width="576">#Starter code<strong>import</strong> imageimg = image.Image(“sample.jpg”)newimg = image.EmptyImage(img.getWidth(), img.getHeight())win = image.ImageWin()img.draw(win)win.exitonclick() </td>

  </tr>

 </tbody>

</table>








