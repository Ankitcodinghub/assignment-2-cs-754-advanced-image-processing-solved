# assignment-2-cs-754-advanced-image-processing-solved
**TO GET THIS SOLUTION VISIT:** [Assignment 2: CS 754, Advanced Image Processing Solved](https://www.ankitcodinghub.com/product/assignment-2-cs-754-advanced-image-processing-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110525&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Assignment 2: CS 754, Advanced Image Processing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
1. Refer to a copy of the paper ‘The restricted isometry property and its implications for compressed sensing’in the homework folder. Your task is to open the paper and answer the question posed in each and every green-colored highlight. The task is the complete proof of Theorem 3 done in class. [24 points = 1.5 points for each of the 16 questions]

2. Your task here is to implement the ISTA algorithm for the following three cases:

(a) Consider the image from the homework folder. Add iid Gaussian noise of mean 0 and variance 4 (on a[0,255] scale) to it, using the ‘randn’ function in MATLAB. Thus y = x + η where η ∼ N(0,4). You should obtain x from y using the fact that patches from x have a sparse or near-sparse representation in the 2D-DCT basis.

(b) Divide the image shared in the homework folder into patches of size 8 × 8. Let xi be the vectorized version of the ith patch. Consider the measurement yi = Φxi where Φ is a 32×64 matrix with entries drawn iid from N(0,1). Note that xi has a near-sparse representation in the 2D-DCT basis U which is computed in MATLAB as ‘kron(dctmtx(8)’,dctmtx(8)’)’. In other words, xi = Uθi where θi is a near-sparse vector. Your job is to reconstruct each xi given yi and Φ using ISTA. Then you should reconstruct the image by averaging the overlapping patches. You should choose the α parameter in the ISTA algorithm judiciously. Choose λ = 1 (for a [0,255] image). Display the reconstructed image in your report. State the RMSE given as kX(:)−Xˆ(:)k2/kX(:)k2 where Xˆ is the reconstructed image and X is the true image. [16 points]

(c) Repeat the reconstruction task using the Haar wavelet basis via the MATLAB command ‘dwt2’ withthe option ‘db1’. Display the reconstructed image in your report. State the RMSE. Use MATLAB function handles carefully. [8 points]

(d) Consider a 100-dimensional sparse signal x containing 10 non-zero elements. Let this signal be convolved with a kernel h = [1,2,3,4,3,2,1]/16 followed by addition of Gaussian noise of standard deviation equal to 5% of the magnitude of x to yield signal y, i.e. y = h ∗ x + η. Your job is to reconstruct x from y given h. Be careful of how you create the matrix A in the ISTA algorithm. [8 points]

3. One of the questions that came up in a live session was the notion of an oracle. Consider compressivemeasurements y = Φx + η of a purely sparse signal x, where . When we studied Theorem 3 in class, I had made a statement that the solution provided by the basis pursuit problem for a purely sparse

1

signal comes very close (i.e. has an error that is only a constant factor worse than) an oracular solution. An oracular solution is defined as the solution that we could obtain if we knew in advance the indices (set S) the non-zero elements of the signal x. This homework problem is to understand my statement better. For this, do as follows. In the following, we will assume that the inverse of ΦTSΦS exists, where ΦS is a submatrix of Φ with columns belonging to indices in S.

(a) Express the oracular solution x˜ using a pseudo-inverse of the sub-matrix ΦS. [5 points]

† ,T is standard notation for

(b) Now, show that. Here ΦSS

the pseudo-inverse of ΦS. The largest singular value of matrix X is denoted as kXk2. [3 points]

†

(c) Argue that the largest singular value of ΦS lies betweenandwhere k = |S| and δ2k

is the RIC of Φ of order 2k. [4 points]

(d) This yields . Argue that the solution given by Theorem 3 is only a

constant factor worse than this solution. [3 points]

4. If s &lt; t where s and t are positive integers, prove that δs ≤ δt where δs,δt stand for the restricted isometry constant (of any sensing matrix) of order s and t respectively. [8 points]

5. Here is our obligatory Google search question :-). Your task is to find out any one paper from within the last

6. Consider the problem P1: minxkxk1 s. t. . Also consider the LASSO problem which seeks to minimize the cost function . If x is a minimizer of J(.) for some value of λ &gt; 0, then show that there exists some value of for which x is also the minimizer of the problem P1. [6 points] (Hint: Consider . Now use the fact that x is a minimizer of J(.) to show that it is also a

minimizer of P1 subject to an appropriate constraint involving

2
