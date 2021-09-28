# Project_ImageRecommendation
Image recommendation
There are many times when we find it difficult to recall the exact name of a product or cannot describe it clearly for search or would love to 
reorder what we saw someone else wearing. In all these cases and many more, “visual product search” is what comes to the rescue. Instead of describing, 
we could just take a picture of the product and search for it. This work is about developing a model which would find most similar images
to a particular product image. An article on mycustomer.com explains how Google has revolutionized the way we search. Consumers now demand image-based search 
functionalities when shopping online (not just text-based search). In a survey of 1,000 consumers, it was found that three quarters of consumers (74%) said 
traditional text-based keyword queries are inefficient in helping them find the right items online. Another 40% would like their online shopping experience 
to be more visual, image-based and intuitive. Potential customers are window shopping “by image” on search engines like Google. 
Retailers whose search engine optimize their product images and listings can gain a competitive advantage with consumers who prefer to shop this way.
# Result
The ANN has Adam (learning rate=0.01) optimizer and Sparse categorical Entropy loss with Accuracy as metric of evaluation and was trained for
250 epochs with a batch size of 128 and validation split of 20%. After training, the model achieved 97.2 % accuracy, 0.0845 loss for category prediction 
and 90.4% accuracy, 0.2700 loss for shape prediction. Below are the plots for training accuracy and training loss. The evaluation of final results i.e., 
if the recommended eye frames are similar to the eye frame image uploaded, displayed depends on user evaluation.
After this, a flask API was developed for improving the user interface for model testing.
