# homework3
  
**電腦視覺特效-第六組**  
  
## Generate images with GANPaint

### origin
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/original_pic.jpg" width="250" height="250"/>

### result
object | first draw &nbsp;&nbsp;&nbsp;&nbsp;| after draw &nbsp;&nbsp;&nbsp;&nbsp;| second draw &nbsp;&nbsp;| after draw &nbsp;&nbsp;&nbsp;&nbsp;| first remove &nbsp;&nbsp;&nbsp;| after remove |second remove|after remove 
<br/><br/>
brick&nbsp;&nbsp;
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_add1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_add2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_add3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_add4.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_re1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_re2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_re3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/brick_re4.jpg" width="100" height="100"/>
<br/>
由上表格第一個row測試的結果，我們可以發現原圖在塗上brick的效果後，不僅是建築物，包含部分的樹木的顏色也會偏向磚塊的顏色。而在對原圖remove brick的過程中，則可以發現當建築物remove brick效果後，整個建築物的顏色就變淺了。
<br/>
door&nbsp;&nbsp;
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_add1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_add2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_add3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_add4.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_re1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_re2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_re3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/door_re4.jpg" width="100" height="100"/>
<br/>
<br/>
由上表格第二個row測試的結果，我們可以發現原圖在塗上door的效果後，原本是窗戶的建築物外觀被整個塗改成門的外觀。然而在對原圖進行remove door的操作後，其效果反而不顯著。
<br/>
<br/>
grass&nbsp;&nbsp;
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_add1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_add2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_add3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_add4.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_re1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_re2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_re3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/grass_re4.jpg" width="100" height="100"/>
<br/>
由上表格第三個row測試的結果，我們可以發現原圖再塗上grass的效果後，圖片內的建築物以及其他景觀皆有了綠意盎然的效果。而在對原圖進行remove grass的操作後，整張圖片中原本含有綠地以及其他偏綠的景色大多轉變為非草地的顏色。
<br/>
<br/>
tree&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_add1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_add2.png" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_add3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_add4.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_re1.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_re2.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_re3.jpg" width="100" height="100"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/GANpaint/tree_re4.jpg" width="100" height="100"/>
由上表格第四個row測試的結果，我們可以發現原圖再塗上tree的效果後，圖片內原本建築物的部分則會被樹的效果所覆蓋。而在對原圖進行remove tree的操作後，整張圖片中原本為tree的部分則轉變為建築物了。


## Dissect GAN model and analyze



## Compare with other method
