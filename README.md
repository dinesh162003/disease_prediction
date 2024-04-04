# disease_prediction
Diabetes is a fast-growing disease among people, even among youngsters. In understanding diabetes and how it develops, we need to understand what happens in the body without diabetes. Sugar (glucose) comes from the foods that we eat, specifically carbohydrate foods. Carbohydrate foods provide our body with its main energy source. Everybody, even those people with diabetes, needs carbohydrates. Carbohydrate foods include bread, cereal, pasta, rice, fruit, dairy products and vegetables (especially starchy vegetables). When we eat these foods, the body breaks them down into glucose. The glucose moves around the body in the bloodstream. Some of the glucose is taken to our brain to help us think clearly and function. The remainder of the glucose is taken to the cells of our body for energy and to our liver, where it is stored as energy that is used later by the body. For the body to use glucose for energy, insulin is required. Insulin is a hormone that is produced by the beta cells in the pancreas. Insulin works like a key to a door. Insulin attaches itself to doors on the cell, opening the door to allow glucose to move from the bloodstream, through the door, and into the cell. If the pancreas is not able to produce enough insulin (insulin deficiency) or if the body cannot use the insulin it produces (insulin resistance), glucose builds up in the bloodstream (hyperglycemia) and diabetes develops. Diabetes Mellitus means high levels of sugar (glucose) in the bloodstream and in the urine.

# Features
Data Acquisition: Collecting both historical and real-time intraday stock price data along with relevant technical indicators from reliable financial data sources and APIs. Feature Engineering: Enhancing data quality and relevance through meticulous preprocessing techniques, ensuring consistency, and accuracy in the dataset. Model Development: Designing and training Long Short-Term Memory (LSTM) neural network models to learn intricate temporal patterns and relationships in the preprocessed data for accurate stock price prediction. Evaluation and Validation: Assessing the performance of developed models using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), etc., and validating predictions against actual stock prices to ensure reliability. Real-time Prediction: Implementing mechanisms to facilitate real-time prediction of intraday stock prices, enabling timely decision-making for traders and investors.

# Requirements
Operating System Compatibility: The system should be compatible with Windows, Linux, and macOS environments to ensure accessibility across different platforms.
Programming Language: Development should be conducted using Python 3.6 or later versions to leverage its extensive libraries and ecosystem.
Libraries: Required libraries include Pandas, NumPy, Scikit-learn, TensorFlow for deep learning, NLTK and TextBlob for natural language processing, as well as API libraries for accessing market data.
Integrated Development Environment (IDE): Used Colab Notebook for efficient development and experimentation.
Methodology
Data Collection: Gather intraday stock price data from reliable sources, ensuring completeness and consistency for subsequent analysis and modeling.
Preprocessing: Handle missing values, outliers, and inconsistencies, and perform data normalization to prepare the dataset for further analysis.
EDA: Explore the dataset to gain insights, identify patterns, and understand the relationships between variables using statistical and visual techniques.
Model Development: Design an appropriate model architecture, such as LSTM, for intraday stock price prediction, considering features and target variable.
Training and Evaluation: Train the model using the prepared dataset, validate its performance using suitable metrics, and fine-tune parameters for optimal results.
System Architecture
Screenshot 2024-04-01 234627

# Flow Diagram
Screenshot 2024-04-03 084346

Output
Screenshot 2024-04-02 223446

Screenshot 2024-04-02 223415

Results and Impact
Improved Prediction Accuracy: The LSTM model significantly enhances intraday stock price predictions, providing traders with more reliable insights.
Enhanced Trading Strategies: Accurate forecasts enable the development of more effective trading strategies, potentially increasing profitability.
Decision-Making: Real-time insights streamline decision-making, allowing traders to capitalize on opportunities and mitigate risks promptly.
Articles Published / References
[1] Shen, J., Shafiq, M.O. Short-term stock market price trend prediction using a comprehensive deep learning system. J Big Data 7, 66 (2020).

[2] Weng B, Lu L, Wang X, Megahed FM, Martinez W. Predicting short-term stock prices using ensemble methods and online data sources. Expert Syst Appl. 2018;112:258–73.

[3] Pang X, Zhou Y, Wang P, Lin W, Chang V. An innovative neural network approach for stock market prediction. J Supercomput. 2018. https://doi.org/10.1007/s11227-017-2228-y.

[4] Wang X, Lin W. Stock market prediction using neural networks: does trading volume help in short-term prediction.

[5] Mokhtari, Sohrab & Yen, Kang & Liu, Jin. (2021). Effectiveness of Artificial Intelligence in Stock Market Prediction based on Machine Learning. International Journal of Computer Applications. 183. 1-8.

[6] Mehar Vijh, Deeksha Chandola, Vinay Anand Tikkiwal, Arun Kumar, Stock Closing Price Prediction using Machine Learning Techniques, Procedia Computer Science, Volume 167, 2020, Pages 599-606, ISSN 1877-0509.

[7] Murkute, Amod, and Tanuja Sarode. "Forecasting market price of stock using artificial neural network." International Journal of Computer Applications 124.12 (2015): 11-15.

[8] Khan, Zabir & Alin, Tasnim & Hussain, Md. Akter. (2011). Price Prediction of Share Market Using Artificial Neural Network 'ANN'. International Journal of Computer Applications. 22. 42–47. 10.5120/2552-3497.
