# Drug Orchestra Testing


When it comes to the complex prediction of how someone's genes affect drug targets, responses, and side effects, not many advancements have been made. Different models have individually been used on various datasets to test their accuracy, but no progress has been made in bridging the gap between these three areas. There is potential to transfer data between the types of predictive models to create more powerful algorithms through the cooperation and communication between these datasets.

Drug Orchestra is a proposed solution by Yuepeng Jiang1 that aims to combine several unique complex machine learning algorithms for drug testing, responses, and side effects into one powerful model. Their work is publicly available on GitHub and will serve as the foundation for my work to reaffirm the evidence of possible transferability between these drug-related tasks.

Specifically, three charts will be used to confirm the connections between these tasks. The first chart measures the performance of machine learning algorithms in comparison to Drug Orchestra, aiming to demonstrate that combining all tasks and datasets can enhance data transferability and benefit prediction accuracy. The next chart will illustrate the performance gains from training and testing different datasets on each other. The final chart will assess the performance gains between the different groups as a whole, aiming to establish a direct link between their transferability.

My results generally agree with those provided by Drug Orchestra. Some algorithms were found to be more effective than Drug Orchestra, although there were some biases that might have affected the results. The datasets and tasks also seem to support the original findings of a link between datasets and tasks, with transferability being a viable option.

Some challenges encountered included the large volumes of data that required extensive preprocessing. To manage this, we employed PCA and feature extraction techniques. A significant drawback of this approach was the loss of information due to dimensionality reduction, which was exacerbated when we changed the data type from 64-bit integers to 32-bit, saving substantial amounts of space and processing power but at the cost of reducing the fidelity of the original dataset.
