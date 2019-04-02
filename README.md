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
### layer 4
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4.png" /><br/>
#### ceiling
unit: 306,340,469<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_ceiling_unit306.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_ceiling_unit340.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_ceiling_unit469.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_ceiling_unit306.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_ceiling_unit340.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_ceiling_unit469.png" /><br/>
#### window
unit: 88,404,405<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_window_unit88.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_window_unit404.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_window_unit405.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_window_unit88.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_window_unit404.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_window_unit405.png" /><br/>
#### sofa
unit 25,37,383<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_sofa_unit25.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_sofa_unit37.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/layer4_sofa_unit383.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_sofa_unit25.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_sofa_unit37.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer4/ablation_sofa_unit383.png" /><br/>

### layer 7
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7.png" /><br/>
#### ceiling
unit: 59,133,172<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_ceiling_unit59.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_ceiling_unit133.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_ceiling_unit172.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_ceiling_unit59.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_ceiling_unit133.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_ceiling_unit172.png" /><br/>
#### window
unit: 88,171,190<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_window_unit88.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_window_unit171.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_window_unit190.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_window_unit88.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_window_unit171.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_window_unit190.png" /><br/>
#### sofa
unit 42,159,249<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_sofa_unit42.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_sofa_unit159.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/layer7_sofa_unit249.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_sofa_unit42.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_sofa_unit159.png" /><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/dissect/layer7/ablation_sofa_unit249.png" /><br/>


## Compare with other method
在此部分吾組所使用的other method為助教於課堂中所提及的Inpainting，而Inpainting這個方法的架構可從下圖可以得知：

<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/mode_inpainting.png" width="650" height="250"/>
<br/><br/>
從Inpainting的論文可以得知，該model是由三個networks所組成，分別為completion network、global context discriminator以及local context discriminator。而completion network的輸入為一張完整的圖片以及該圖片對應的Mask，並經過fully convolutional，最後則輸出一張完整的圖片。至於
global context discriminator以及local context discriminator則是負責判斷completion network輸出的圖片是否有completed consistently。

origin | mask | result
<br/><br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/1.jpg" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/mask1.png" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/out1.png" width="200" height="200"/>
<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/2.jpg" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/mask2.png" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/out2.png" width="200" height="200"/>
<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/3.jpg" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/mask3.png" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/out3.png" width="200" height="200"/>
<br/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/4.jpg" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/mask4.png" width="200" height="200"/>
<img src="https://github.com/TingWeiHuang22/homework3/blob/master/pictures/inpainting/out4.png" width="200" height="200"/>
<br>
<br>
GANPaint和Inpainting主要的差異為， GANPaint針對的是特定物體的移除或加入，像是brick, door, tree等等；而Inpainting移除的方式則是透過mask，然而這個mask其實並不需要完全貼齊要移除的物體，只要該物體為mask主要的部分即可。移除效果的部分，兩者方法皆可以將想要移除的部分移除，而補上的部分也幾乎都和背景相近，只是在GANPaint中，補上的背景不是和背景融為一體，就是顯得非常突兀，前者如移除樹木的那幾張圖，特別是移除樹木的第一張，而且可以完美的補上建築物，後者則是像移除草的那幾張，加入的建築物不知道是從哪邊冒出來的；而Inpainting的都帶有一些模糊，在大部分的情形中，帶有一些模糊更能和背景融為一體，像是第一張和第二張，但若是背景過於繽紛，則像是第三張圖，感覺就像畫面被刮壞了，比較特別的"是你的名字"那張，同樣是色彩繽紛，但是不僅成功將女主角移除，也將女主角身後的建築物給補上了。
