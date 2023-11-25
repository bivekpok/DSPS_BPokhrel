This is the visualization assignment

<img width="978" alt="Screenshot 2023-11-21 at 3 48 31 PM" src="https://github.com/bivekpok/DSPS_BPokhrel/assets/144483051/0d61b67e-e758-4548-b704-ddd072aee81a">

 In the above picture, the change is sort of hidden as the every bar is plotted form y  = 0 therefore to see the changes writer couyld have started the y axis from somewhere in the middle of the y axis. So thhis is distorted plot and misleading so meaning the changes are not represented as it should be. It voilates the effect size factor.
Concerns with Y-Axis Origin:
The decision to initiate the y-axis from zero, coupled with the logarithmic transformation, might lead to a visual distortion. When changes in the data are subtle, starting the y-axis from zero can exaggerate the perceived differences, making them appear more substantial than they actually are. This can violate the principle of effect size, which emphasizes the importance of accurately representing the magnitude of changes.
Effect Size Factor:
Effect size is a critical statistical concept that measures the magnitude of a phenomenon or the strength of an observed effect. In graphical representations, it is crucial to ensure that the scale and origin of the axes do not mislead the viewer regarding the size of the observed changes. Violating the effect size principle can lead to misinterpretations and an inaccurate understanding of the significance of the observed variations.
 
<img width="653" alt="Screenshot 2023-11-21 at 3 48 46 PM" src="https://github.com/bivekpok/DSPS_BPokhrel/assets/144483051/804be837-ea19-451a-afe7-b4ae6ad95c2b">

This is the picture which is very good, the efect size, data/ink ratio, no chart junk is there in this picture.


<img width="510" alt="Screenshot 2023-11-21 at 3 52 30 PM" src="https://github.com/bivekpok/DSPS_BPokhrel/assets/144483051/8428645e-86d0-4c6d-a5b7-3edd03c9e513">

This is another bad picture where the information is lost in the sense that the lower valued bars in the right most is under-represented, it would be better if the plot had log axis in y axis.



  These are my own plots:
  

  
![before](https://github.com/bivekpok/DSPS_BPokhrel/assets/144483051/77b3f623-dc33-445d-a260-d4099f5bfa77)

In this plot there are few points with very less frequency that are hard to read.The generated plot serves as a comprehensive visualization, providing a clear depiction of the distribution of maximum logits or probabilities across the dataset. Each point on the plot corresponds to a specific value of the maximum logits or probabilities, and the y-axis represents the frequency of occurrence for each of these values.
The plot effectively highlights the frequency distribution of maximum logits or probabilities. Notably, certain points on the plot exhibit lower frequencies, making them challenging to discern. These infrequent occurrences may represent instances where the model faces challenges or uncertainties in predicting the correct class. The analysis of these points with lower frequency becomes particularly important as they may indicate areas where the model requires further refinement or additional training data.

Significance:
Understanding the frequency distribution of maximum logits or probabilities provides valuable insights into the robustness and reliability of the GNN model. Points with lower frequency may correspond to scenarios where the model is less confident or encounters complexities in the input data. Identifying and addressing these instances can contribute to improving the overall performance and generalization capabilities of the GNN.

![after](https://github.com/bivekpok/DSPS_BPokhrel/assets/144483051/7b5ce1f4-2ec2-4c74-b93c-b06fc664bf44)

Afterward, I log plotted the y axis and it looked much better interms of readability and use of the space.
Improvement Made:
After generating the initial frequency plot, it was observed that there were points with very low frequency, making them difficult to discern on the linear y-axis. To address this, a logarithmic transformation was applied to the y-axis. This transformation compresses the scale of the y-axis, enhancing the visibility of points with lower frequencies and allowing for a more detailed examination of less frequent occurrences.

The decision to log plot the y-axis significantly improved the visualization of the frequency distribution of maximum logits or probabilities in the GNN model. This enhancement not only enhanced the graph's aesthetics but also facilitated a more insightful analysis of infrequent occurrences, contributing to a more comprehensive understanding of the model's performance
