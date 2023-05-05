Download Link: https://assignmentchef.com/product/solved-cv1-assignment-4
<br>
<strong>Task 1: </strong>SIFT (pen &amp; paper)

Explain why0, with <em>α,β </em>being the eigenvalues of the Hessian matrix at a keypoint.

Using this result, prove that when <em>r &gt; </em>0, the function has a minimum at <em>r </em>= 1.

<strong>Task 2: </strong>ORB Feature Detectors (programming)

ORB is a fast and efficient alternative to SIFT. Download and read the image Elbphilharmonie.jpg on Moodle.

Figure 1: Hamburg Elbphilharmonie. Image source: Wikipedia

<ul>

 <li>Convert the image to grayscale image im.</li>

 <li>Using transform.AffineTransform, obtain a transformed image im2 with the following parameters: shrink the dimensions by half, 20 degree counter-clockwise rotation, 300 pixels to the right and 300 pixels to the bottom translation.</li>

 <li>Visualize the images im, im2.</li>

 <li>Using feature.ORB, extract 100 ORB key points and descriptors of the two images above. Visualize the matching results.</li>

</ul>

Note: Follow the example at <a href="http://scikit-image.org/docs/dev/auto_examples/features_detection/plot_orb.html">http://scikit-image.org/docs/dev/auto_examples/ </a><a href="http://scikit-image.org/docs/dev/auto_examples/features_detection/plot_orb.html">features_detection/plot_orb.html</a><a href="http://scikit-image.org/docs/dev/auto_examples/features_detection/plot_orb.html">.</a>

1

<strong>Task 3: </strong>SIFT (pen &amp; paper)

Consider Figure 2, which shows a normalized orientation histogram for a SIFT keypoint after weighting<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>.

Orientation <em>θ </em>(degrees)

Figure 2: A normalized orientation histogram of a SIFT keypoint.

<ul>

 <li>What is the dominant local direction of the keypoint?</li>

 <li>How many new keypoints will be created, and why? What are their orientations?</li>

</ul>

<a href="#_ftnref1" name="_ftn1">[1]</a> For simplicity, we consider an 8-bin orientation histogram. In the original SIFT algorithm, 36 bins are used.