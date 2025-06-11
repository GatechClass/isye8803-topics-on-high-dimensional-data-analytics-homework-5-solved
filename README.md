# isye8803-topics-on-high-dimensional-data-analytics-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [ISyE8803: Topics on High Dimensional Data Analytics Homework 5 Solved](https://mantutor.com/product/isye8803-topics-on-high-dimensional-data-analytics-homework-5-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;55517&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISyE8803: Topics on High Dimensional Data Analytics  Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>Question 1. Robust PCA (25 points)</h1>
Recently, robust PCA has become popular for many modern problems, including video surveillance (where the background objects appear in low rank matrix and foreground objects appear in sparse matrix), face recognition (eigenfaces are in low rank matrix and shadows, occlusions, etc. are in sparse matrix). In this problem, we want to use robust PCA on the Extended Yale Face Database to decompose some of its images to the low-rank component and occluded regions.

The Extended Yale Face Database consists of cropped and aligned images of 38 individuals (28 from the extended database, and 10 from the original database) under 9 poses and 64 lighting conditions. Each image is 192 pixels tall and 168 pixels wide. Each of the facial images in this data set have been reshaped into a large column vector with 192 * 168 = 32256 elements.

For this problem, consider the first 64 columns of the data set (corresponding to the first 64 images), then apply robust PCA method on that. Your response should include image numbers:&nbsp; 3, 4, 14, 15, 17, 18, 19, 20, 21, 32, and 43. Show each image along with its low rank image and sparse image. Comment on how effective RPCA is to fill in occluded regions of the image corresponding to the shadows.

&nbsp;

<h1>Question 2. Matrix Recovery (25 points)</h1>
‘ratings.mat’ 𝑀<sub>#</sub> contains ratings on a 1 to 10 scale by 200 viewers for 100 movies. 50% of the ratings were randomly removed (i.e. replaced with 0) and stored in ‘ratings_missing.mat’ 𝑀<sub>$</sub>. Recover the original matrix from ‘ratings_missing.mat’ by using the two methods below:

<ul>
<li><u>Method 1</u>: By directly solving the following optimization problem:</li>
</ul>
<h2>min( ‖𝑀‖<sub>∗</sub> subject to 𝑀 {𝑜𝑏𝑠𝑒𝑟𝑣𝑒𝑑&nbsp;&nbsp;&nbsp; 𝑠𝑒𝑡}</h2>
<ul>
<li><u>Method 2</u>: By using the completion algorithm (i.e. using singular value thresholding to solve the above optimization problem)</li>
</ul>
Include the following results and commentary in your report:

<ul>
<li>For Method 1, report the optimal objective function value and the relative reconstruction error. The relative reconstruction error is defined by:</li>
</ul>
‖𝑀 − 𝑀<sub>#</sub>‖<sub>?</sub>

‖𝑀#‖?

&nbsp;

<ul>
<li>For Method 2, report the relative reconstruction error for the following values of 𝛿 and 𝜏 after (i) 1000 iterations and (ii) 2000 iterations. Comment on the results.</li>
</ul>
<table width="344">
<tbody>
<tr>
<td width="172">𝜹</td>
<td width="66"></td>
<td width="16"></td>
<td width="90">𝝉</td>
</tr>
<tr>
<td width="172">0.1</td>
<td width="66">50</td>
<td width="16"></td>
<td width="90"></td>
</tr>
<tr>
<td width="172">2</td>
<td width="66">50</td>
<td width="16"></td>
<td width="90"></td>
</tr>
<tr>
<td width="172">0.1</td>
<td width="66">500</td>
<td width="16"></td>
<td width="90"></td>
</tr>
<tr>
<td width="172">2</td>
<td width="66">500</td>
<td width="16"></td>
<td width="90"></td>
</tr>
</tbody>
</table>
&nbsp;

<ul>
<li>Comment on the performance (i.e. execution time etc.) of Method 1 and Method 2. Conclude by providing your recommendation on which is a better method.</li>
</ul>
<strong>&nbsp;</strong>

<h1>Question 3. Compressive Sensing for Color Images (25 points)</h1>
Color images are acquired in three channels – Red (R), Green (G) and Blue (B). The data (image) acquired by each of the channels is sparse in DCT or wavelet domain. i.e.,

𝐶 = 𝛷<sup>F</sup>𝒳<sub>H</sub>, 𝐶 ∈ {𝑅, 𝐺, 𝐵}.

𝒳<sub>H </sub>= 𝛷𝐶

Where C represent each of the three-color channels, 𝛷 is the (sparsifying) transform matrix and 𝒳<sub>H</sub> is the sparse transform coefficient for each color channel.

(1). In this problem, you are required to compress the color image (Lenna.png) to 70% of its original size by using compressive sensing matrix 𝐴<sub>H</sub> (random sampling). The sensing matrix can be the same for all channels. Define your own sensing matrix 𝐴<sub>H</sub> and plot the compressed color image.

(2). In this problem, use the provided code DWT.m to generate the transform matrix 𝛷 and recover the color image. Compare the original color image with recovered color image. Compute the reconstruction error in terms of MSE.

Hint: in compact matrix-vector notation, 𝑦<sub>O </sub>= 𝐴<sub>H</sub>𝐶 =&nbsp;&nbsp;&nbsp; 𝐴<sub>H</sub>𝛷<sup>F</sup>𝒳<sub>H</sub>,&nbsp; 𝐶 ∈ {𝑅, 𝐺, 𝐵} can be expressed as

𝑦Q&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝐴Q𝛷F&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝒳Q

P𝑦<sub>R</sub>T = U&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝐴<sub>R</sub>𝛷<sup>F&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>0&nbsp;&nbsp; W P𝒳<sub>R</sub>T

𝑦S&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝐴S𝛷F 𝒳S

In short,

𝑦 = 𝐴𝒳

Where 𝑦 = [𝑦<sub>Q</sub><sup>F</sup>𝑦<sub>R</sub><sup>F</sup>𝑦<sub>S</sub><sup>F</sup>]<sup>F</sup>, 𝐴 = BlockDiag(𝐴<sub>Q</sub>𝛷<sup>F</sup>,&nbsp;&nbsp; 𝐴<sub>R</sub>𝛷<sup>F</sup>, 𝐴<sub>S</sub>𝛷<sup>F</sup>) and 𝒳 = [𝒳<sub>Q</sub><sup>F</sup>𝒳<sub>R</sub><sup>F</sup>𝒳<sub>S</sub><sup>F</sup>]<sup>F</sup>

&nbsp;

&nbsp;

<h1>Question 4. Sparse Smooth Decomposition (25 points)</h1>
In this problem, we’re going to use Sparse Smooth Decomposition to extract features rather than detect anomalies. Provided are two images of heatmaps of a GPU lid. One is at idle, and the other one is under load (training a CNN in to classify tensors of birds and cats.) We want to programmatically detect where heat spreads on the lid under load so engineers can design appropriate heatsinks and place thermal sensors on the die.

Unfortunately, the temperature sensor we have is very noisy when the GPU is idle due to the temperature differentials being quite small. Therefore, we can’t solely rely on image processing techniques from Module 2, such as simply subtracting the at-idle image from the at-load image and doing edge detection.

A: 10%) Read in both images and convert to grayscale. To demonstrate why this would be an ugly problem with simple techniques, show a simple subtraction of the idle image from the load image as the deliverable for this part.

B: 40%) Implement 2-D SSD. For purposes of this part, use the default parameters, as in the example code. (Eg., delta = 0.2, x and y knots = 6, anomaly knots = length/4.) As deliverables, include in your report the same output as from the example code. That is, the:

<ul>
<li>combined image used</li>
<li>decomposed mean</li>
<li>decomposed features – we are interested in heat generated under load, so set values &lt;0 to 0!</li>
</ul>
C: 50%) The default parameters do quite well, but we can do better! Play with all available parameters to generate the best separation you can. Remember, your goal is to capture the load heat as sparse “anomaly” in the decomposition. In other words, you (probably) don’t want the spots that are only hot under load to show up in the mean. For this part, include in your report your:

<ul>
<li>combined image used (the “delta” used when combining the images is fair game)</li>
<li>decomposed mean</li>
<li>decomposed features – again, set values &lt;0 to 0!</li>
<li>a brief discussion of your methodology; say what you tried, what did (or didn’t) work, and why you chose what you finally chose.</li>
</ul>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
