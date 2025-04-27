## About Me:

I completed my PhD in Electrical Engineering, during which I undertook courseworks in Machine Learning and Statistics for Data Science. Alongside my coursework, I conducted research focused on Exploratory Data Analysis (EDA) and Machine Learning algorithms. This combination of academic training and hands-on research sparked my interest in transitioning from academia to the data science industry. I found the process of working with raw data, uncovering patterns, and transforming numbers into meaningful insights and actionable business recommendations fascinating. I began relentlessly working on Python, SQL, Excel, Tableau and this journey naturally shifted my career trajectory toward becoming a data scientist, where I could utilize my skills in data analysis, machine learning, and statistical modeling to solve real-world problems.

## Skills & Tools

- **Programming:** Python, MySQL,ProtgreSQL, Excel, Matlab
- **ML & Deep Learning Frameworks:** Keras, Scikit-Learn,TensorFlow, PyTorch
- **Data Analytics & Visualization:** Pandas, NumPy, SciPy, Statsmodel, Matplotlib, Seaborn, Plotly
- **Development Tools:** VS Code, PyCharm, MATLAB & Simulink
- **Version Control:** Proficient in Git & GitHub

  
## Technical Expertise

- Data Cleaning: handling missing values, converting data to required datatype, removing outliers, introducing new features, grouping data 
  based on features. Generation of box plots & histograms, outlier treatment with (Interquartile Range)IQR capping, correlation heatmap
- ML Model Deployment using Flask
- Writing SQL Queries for Real world Problems
- Hands-on experience working on large-scale datasets with machine learning algorithms(regression, classification, clustering), feature engineering and model deployment.
- Knowledge of statistical metrics and experience using statistical packages for analyzing large datasets.
- Hands-on experience working on large-scale datasets with machine learning algorithms(regression, classification, clustering), feature engineering and model deployment.
- Knowledge of statistical metrics and experience using statistical packages for analyzing large datasets.
- Strong expertise in time series forecasting, Data Analytics, Anomaly detection, and Deep learning architectures (TCN, CNN, RNN, LSTM)
- Developed [hybrid modeling](https://www.sciencedirect.com/science/article/pii/S0019057824005366?via%3Dihub) involving DL-based models for analyzing and predicting complex system dynamics, Time series Analysis using ARIMA, SARIMAX and NARX methods.
  - Extensive research in [Nonlinear System Identification](https://link.springer.com/article/10.1007/s11071-023-09258-0) & Control, Predictive (Data-Driven) Modeling, and Deep Learning
- Actively working as an independent contractor /subject expert to train AI in Electrical Engineering at Outlier.ai

 
### Notable Research in Data Science (With high impact factor Research Publications):

Time series forecasting of a Real Time  pH Neutralization Process: 

Collected around 10705 samples of real-time dataset(pH base flow rate, acid flow rate) of a complex nonlinear pH neutralization process. The nonlinear dynamics of the  pH titration curve is predicted using deep learning algorithms: [Temporal Convolutional Networks (TCN) and LSTM networks](https://pubs.acs.org/doi/abs/10.1021/acs.iecr.3c01212) 

**Key Highlights:** 
-  Data partitioned to (train/test) and model development, Identified the trends, seasonality and irregular values of pH, acid and base flow rate data for time- series forecasting.
- Developed TCN and LSTM based pH prediction models with TCN outperforming LSTM with RMSE = 0.023 and R² = 97.6%, ensuring 18% less downtime in process operations.
-	Tuned hyperparameters (kernel size, dilation, dropout) using grid search, improving model accuracy by +8% and cutting validation loss by > 30%, while preventing overfitting through dropout (0.3) and weight normalization.
-	Reduced calibration/setup time by 40% through accurate modeling of nonlinear titration curves, increasing production throughput and reducing batch delays.
-	Delivered $50K/year in savings through improved pH balance, reducing chemical wastage by 30% and extending equipment lifespan in pilot-scale systems.
-	Designed models for cloud and edge deployment, supporting real-time pH control supporting smarter scheduling, procurement, and logistics planning.
- Predicted the nonlinear dynamics of the multislope pH titration curve using [Nonlinear ARX,ARIMA, RNN and CNN-LSTM Networks](https://www.sciencedirect.com/science/article/pii/S0019057824005366?via%3Dihub).
- Executed sequence modeling: used dilated causal convolutions and a residual learning framework for parallel processing and to handle very long sequences. 
- Implemented hyperparameter tuning (dropout, learning rates, filter size, hidden-state size) and grid search optimizer to enhance generalization
- Validated the prediction accuracy through standard statistical metrics(Descriptive and Inferential).

[Regression Analysis using kSINDYc - A ML Approach](https://link.springer.com/article/10.1007/s11071-023-09258-0):
- Conducted time series analysis on process control data sets including Continuous Strirred Tank Reactors, Heat Exchanger and Bioreactor using a novel machine learning algorithm called key term based Sparse Regression of Nonlinear Dynamics and Control (kSINDYc) and validated their training and testing accuracy using statistical metrics.
- Formulated nonlinear objective functions, involved regularization methods like (Ridge, Lasso, Droppot) to overcome overfitting

### Featured DS Project Works (Github):

a. [Bit-Coin Price prediction using Time-series Forecasting](https://github.com/joan-xavier/ML_projects_2024/tree/main/P3_Bitcoin_prediction_Time_series_ARIMA_LSTM)
ToolsUsed: NumPy, Pandas, datetime, Matplotlib, Seaborn, Statsmodels and SciPy
The primary objective of this project is to compare the accuracy of bitcoin price in USD prediction from time-series data based on two different models, Long Short term Memory (LSTM) network and ARIMA model. Collected the recent dataset (Sep 2014 - March 2025) from yahoo financing. Here are the questions I was interested in answering:
  - How exactly did detecting trends 12–24 hours earlier help the business?
  - What smoothing techniques did you use, and why were they chosen over others?
  - Were there any false positives in trend detection? How did you handle them?
  - How reliable was the ADF test in real-world (live) data compared to historical data?

**Key Highlights:**  
-	Detected early price trends by transforming and stabilizing Bitcoin data using ADF tests and smoothing techniques, helping teams react 12–24 hours sooner during trend and seasonality shifts.
-	Improved price prediction forecast accuracy by comparing ARIMA and LSTM models, showing LSTM reduced errors by 18% -helping guide future model choices.
-	Saved analyst monitoring time by automating steps like differencing and correlation checks (ACF, PACF) with statistical tools, reducing manual work by around 10 hours per week, making insights easy to understand for non-
-	Built trust in predictions by validating models with clear performance metrics (MAE, RMSE, and R²) and visuals, making insights easy to understand for non-technical teams.
-	Recommended weekly model updates to keep forecasts accurate during market swings, helping reduce prediction delays and improve response times during high-noise events like news-driven price fluctuations.

b. [EDA and Hypothesis Testing on Margeting Campaign Dataset](https://github.com/joan-xavier/ML_projects_2024/tree/main/P5_Marketing_data_Hypothesis_testing_EDA)

  - Performed exploratory data analysis and hypothesis testing on a marketing dataset integrating the five Ps (People, Product, Price, Place, and Promotion). Demonstrated the US market’s performance relative to other countries through comparative statistical analysis. Here are the questions I was interested in answering.
 - How does the US market's performance specifically differ from other countries? Are there particular products, prices, or promotions driving this?
 - Which of the five Ps (People, Product, Price, Place, Promotion) had the biggest impact on campaign success?
 - Based on your hypothesis testing, what immediate actions would you recommend for marketing strategy in the US versus globally?
   
  **Key Highlights:** 
    
- Ordinal Encoding and mapping based on Education level as (for category:Basic: 0,2Nd Cycle: 1, Graduation: 2,Master: 3,Phd: 4)
-	Encoded categorical variables using ordinal and one-hot encoding with Pandas, ensuring compatibility with statistical models and boosting hypothesis test accuracy.
-	Conducted hypothesis testing with SciPy t-tests to validate age-channel preferences, child-based online behavior, channel cannibalization, and U.S. purchasing dominance - guiding campaign focus and regional resource allocation.
-	Identified high/low-performing products through Pandas groupby analysis, recommending promotion reallocation toward top-selling categories to maximize Return On Investment (ROI).Forecasted $250K increase in quarterly revenue based on improved conversion rates and reduced churn
Recommended reallocation of 30% more budget toward Segment B(ages 25–34) and shift email content strategy to focus on personalized offers.

c. [SQL Project using Paintings & Museum Dataset](https://github.com/joan-xavier/Data_Analysis_Python_2024/blob/main/SQL_music_store_project1.pdf):

Analyzed museum inventory data with SQL to identify unexhibited paintings and underutilized museum spaces. Discovered 15% of artworks not displayed, highlighting opportunities to improve visitor engagement and provided insights to optimize art rotations and enhance museum profitability.

 **Key Highlights:** 
 
- Optimized museum inventory insights by querying and identifying 15% of paintings not currently exhibited and uncovering underutilized museum spaces.
- Improved collection management by detecting museums with no associated paintings, enabling better artwork distribution planning and enhancing visitor experience.
- Enhanced data-driven decision-making by cleaning inconsistencies (e.g., mismatched artist IDs, missing gallery assignments) to support accurate reporting on artwork visibility and artist representation

  
### Project/Course Certifications:

- Received a passing grade and verified certificate in [‘Machine Learning with Python – From Linear Models to Deep Learning’ offered by MITx, MA](https://courses.edx.org/certificates/996fa1a66b8243fd8cc2dddc1da867b2) in association with edX. (2024) 
- Received a passing grade and verified certificate in [‘Deep learning fundamentals with Keras’ offered by IBM](https://courses.edx.org/certificates/9937b0ec7eca42428ac0e45925984ac8) in association with edX. (2024) 
- Received a passing grade and verified certificate in the course [‘Deep learning with TensorFlow’ offered by IBM](https://courses.edx.org/certificates/a950c6cff0e54b5a9fd2c44e8928263f) in association with edX. (2024) 
- Verified Certificate on completing the six months course on [‘Artificial Intelligence and Deep learning’ conducted by IIT Roorkee](https://iitr.ac.in/cec/CEC-1003-2021-22/165.jpg), India (2023) 


### Honors & Awards

- [Anna Centenary Research Fellowship](https://cfr.annauniv.edu/research/announcements/Acrf-2019.pdf) (2019-2021) during the PhD study at [Anna University, India](https://www.annauniv.edu/)
- [Elsevier Reviewer Recognition](https://elsevier-reviewer-recognition-joan.tiiny.site) (Reviewed 20+ manuscripts)
- [Certificate of Recognition](https://drive.google.com/drive/folders/0Bw7TrMeBmo3Va0JKb3ByV194SE0?dmr=1) from [Centre for Research](https://cfr.annauniv.edu/research/academics/index.php), Anna University (2024) for publishing research articles in Q1 Journals as per [Scimago Ranking](https://www.scimagojr.com/journalrank.php?category=1710&wos=true).
- [Best Paper Presenter](https://publuu.com/flip-book/796176/1758624) at [IFAC 2022 Conference](http://acods2022.nits.ac.in/) ('International Fedaration of Automatic Control'), NIT Silchar, India 
- Designed [Front Cover Art](https://pubs.acs.org/toc/iecred/62/33) for 'Industrial & Engineering Chemistry Research' (ACS Journal)  The Cover art was based on my  article featuring Deep learning based Temporal Convolution Networks for a complex pH Process (2023)
    
## Ph.D. in Electrical Engineering | ML & Deep Learning | Data Science  Research

In my PhD research at [Anna University, (2018-2023)](https://www.annauniv.edu/), I worked on a challenging multi-disciplinary topic – ‘Nonlinear system Identification, nonlinearity quantification and control of Nonlinear Systems’, where I integrated the concepts of Nonlinear system identification from Electrical Engineering, time series  forecasting (ARIMA  Models) and analysis using Machine learning/deep learning algorithms and applied it to control engineering problems. This experience shaped my skills in analysing large raw datasets, applying rigorous optimization solvers,hyperparameter tuning and developing new approaches to complex real-world problems.This experience also stimulated my deep interest in diving in-depth in Machine learning/Deep learning algorithms and exploring Data Science to transition into this field.

### Research Publications

I have published around 10 peer-reviewed articles in science citation indexed journals. Among these, three research articles were focused on Machine learning based system identification as a first author in journals with high impact factor. My publications have over 60 total citations and a h-index of 5. 
You can view my publications in the [my Google Scholar page](https://scholar.google.co.in/citations?user=4O4FHQMAAAAJ&hl=en)

### Collaborative Projects and Scientific Writing

As a Full-time researcher at Anna University, I designed and executed multiple projects, collaborated with faculty at Central Research labs, and mentored Masters students on advanced topics in control systems, Machine learning and Deep learning which resulted in good publications in high impact factor Journals.

- Collaborated with Faculty and students of [Anna University](https://www.annauniv.edu/) in the field of [Sparse regression (ML)](https://www.sciencedirect.com/science/article/pii/S240589632200146X), [Deep learning (MLP,TCN, LSTM)](https://pubs.acs.org/doi/abs/10.1021/acs.iecr.3c01212), Hybrid modelling for System Identification and [economic optimization](https://www.sciencedirect.com/science/article/abs/pii/S0009250923000866?via%3Dihub) of Data Driven Nonlinear Real-time systems.
- Published multiple peer-reviewed Q1 journal articles on ML-based system identification [(Google Scholar h-index: 5)](https://scholar.google.co.in/citations?user=4O4FHQMAAAAJ&hl=en)
- Reviewer for Elsevier & IMechE Journals (Reviewed 20+ manuscripts)
- Co-author of the Humanity’s Last Exam a multimodal benchmark featuring original questions from many subject areas to test the limits of top state-of-art LLM Models (GPT- 
  4o, o1, Sonnet 3.5, Gemini 1.5 and Deep-Seek R1)[HLE research paper](https://arxiv.org/abs/2501.14249), organized by [Centre for AI Safety](https://agi.safe.ai/) & [Scale AI](https://scale.com/research/humanitys-last-exam)  2025.

     
### Github Projects:

[Data Science Projects](https://github.com/joan-xavier/Data_Analysis_Python_2024)
[ML Projects](https://github.com/joan-xavier/ML_projects_2024)
[For Python Projects](https://github.com/joan-xavier/Python_Projects_2024)
