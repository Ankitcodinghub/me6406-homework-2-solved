# me6406-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [ME6406 Homework 2 Solved](https://www.ankitcodinghub.com/product/me6406-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121256&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ME6406 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1. Hough Transform y

a. Show that the foot-of-normal parameters   xyoo =   ggxy x

 

xgx +ygy

where = gx2 +gy2 . Fig. 1 HW2.jpg

b. With the equation derived in Part 1a to solve the parameters (xo, yo), write a MATLAB program to perform the Hough transform based on the foot-of-normal parameterization on the image ‘HW2.jpg’ to find the edge lines:

1) Convert the RGB image to a gray-level image followed by obtaining the binary edge image (edge pixel: 1, others: 0) and by applying the Sobel operation to get the gradient, so that the image can be characterized by a set of edge points with known gradient components (xi, yi; gx, gy).

Suggested Matlab functions: rgb2gray.m, edge.m, bwboundaries.m, imfliter.m.

3) From the peaks in H, determine the equations that characterize the straight edges in ‘HW2.jpg’.

Note: The Matlab commands hough.m, houghlines.m are not allowed.

c. Use Hough Transform to detect the circle in ‘HW2.jpg’. Compare your results with MATLAB function imfindcircle.m.

2. Feature Points Detection

a. Use the rho-theta signature method discussed in class and implement MATLAB to locate all the corners of the object in ‘HW2.jpg’ (Fig. 1). Plot the  signature to locate the corners. Show the coordinates of the corners with respect to the given coordinate system.

b. Repeat Part 2a with the median length method. Pick an appropriate N (length of the neighbor). Plot the median length as a function of the path. Show the coordinates of the corners with respect to the given coordinate system.

c. Repeat Part 2a with the curvature method, which is to locate the ‘peaks’ of the curvature along the boundary. Plot the graph that you use to locate the corners. Show the coordinates of the corners with respect to the given coordinate system.

3. Template Matching

a. Forward transformation: Write a MATLAB function to perform the transformation for three template points with the parameters as shown in Table 1. Show and plot three points before and after transformation. The transformed points are accurate to three decimal places.

Template

Features 1 2 3

X 0 6 2

Y 0 3 7

Table 1 Parameters

(xd, yd) = (8, 5) θ = 30° k = 1.2

b. Pseudo inverse method: Write a MATLAB function to perform the pseudo-inverse method on the template and transformation points in Part 3a to find parameters (k, θ, xd, and yd). Check these values in Table 1.

c. Polygon matching: Write a MATLAB program to perform template matching on the template and target as shown in Table 2 and Fig. 2 to identify the match points, and determine the transformation parameters; namely scale k, orientation θ, and displacement (xd, yd).

Note 1: Given n points, there are   n3 = (n−n3 !3!!) unique triangles. Use Matlab function

 

nchoosek( ) to compute all possible combinations of vertices to form unique triangles.

Note 3: As there are many triangles to be matched, your program must automate the matching process to avoid tedious manual matching.

Note 4: Determine the ‘best’ match by finding the one that yields the smallest ‘matching error’ defined by Eq. (11) in [Lee, et al., 1992]:

k

E= (X Xti − i )2 + −(Y Yti i )2

i=1

Reference:
