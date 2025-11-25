
The system is designed to demonstrate the application of supervised machine learning classification techniques in a real-world, scalable environment. By classifying reviews as Positive, Negative, or Neutral, it provides businesses with actionable insights to quickly respond to customer feedback and maintain product quality. The architecture is cloud-ready, emphasizing modularity and performance.

Features

1)Review Submission API: Secure endpoint to accept new product reviews for processing.

2)ML-Powered Sentiment Engine: Real-time prediction of review sentiment using a pre-trained or fine-tuned classification model.

3)Data Persistence: Storage of processed reviews and their associated sentiment scores.

4)Intuitive Dashboard: A single-page application (SPA) displaying:

     - Overall Sentiment Distribution (Pie Chart).

     - Trending Keywords in Negative Reviews (Basic Text Analysis).

     - Historical Sentiment Trend over time.

Technologies and Tools Used

| Category                   |                         Technology                        |                         Rationale & CO Alignment                  |
| ---------------------------|-----------------------------------------------------------|-------------------------------------------------------------------|                                                                                                                                                       
| Framework                  |              Python (Scikit-learn / TensorFlow)           |        Core implementation of Classification and Estimators.      |
|----------------------------|-----------------------------------------------------------|-------------------------------------------------------------------|                                                                                                                                                         
| Backend/API                |                   Flask (Python) / FastAPI                |               To build the functional Review Submission API.      |
|----------------------------|-----------------------------------------------------------|-------------------------------------------------------------------|
| Database                   |             SQLite (for development) / Cloud Firestore    |             Simple, persistent storage for Data Representations.  |
|----------------------------|-----------------------------------------------------------|-------------------------------------------------------------------|                             
| Frontend                   |                 HTML, Tailwind CSS, Vanilla JS            |               For building the responsive Analytics Dashboard.    |
|----------------------------|-----------------------------------------------------------|-------------------------------------------------------------------|                            
|Deployment Focus            |          Docker, Cloud Platform (e.g., AWS/GCP/Azure)     |   Essential for the Cloud Computing context and validating Non-   |                                  |                                                           |                  Functional Requirements (Scalability).

Installation and Setup                       

1)Prerequisites

2)Python 3.8+

3)pip (Python package installer)

4)Git

Step 1: Clone the Repository

             git clone (https://github.com/your-username/sentiment-analyzer-project
             cd sentiment-analyzer-project


Step 2: Setup Python Virtual Environment

It is highly recommended to use a virtual environment to manage dependencies.

                       python3 -m venv venv
                       source venv/bin/activate  # On Linux/macOS
                       # .\venv\Scripts\activate  # On Windows


Step 3: Install Dependencies

                         pip install -r requirements.txt


Step 4: Run the Application

                          python app.py

