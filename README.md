# InsightScribe
InsightScribe is an AI-powered tool that transforms raw data into interactive visualizations paired with engaging narratives. It analyzes datasets to generate dynamic charts and clear insights, empowering users to uncover trends, identify outliers, and make data-driven decisions.



## Features

- **Data Ingestion:** Upload datasets in CSV, Excel, or JSON format.
- **Interactive Visualizations:** Automatically generate dynamic charts using Plotly/D3.js.
- **Narrative Generation:** Leverage AI models (T5 or GPT-2) to produce plain-language summaries and insights.
- **Customization:** Adjust narrative tone and detail levels to suit your needs.
- **Export & Share:** Save visualizations and narratives as images, PDFs, or reports.
- **Responsive Dashboard:** Seamlessly explore data through an intuitive web interface.

## Tech Stack

- **Backend:** Python with FastAPI or Flask for API development and data processing.
- **Data Processing:** Pandas and NumPy for data manipulation.
- **NLP Models:** T5 or GPT-2 (via Hugging Face Transformers) for generating narratives.
- **Visualization:** Plotly and/or D3.js for interactive charts.
- **Frontend:** React or Vue.js for building the user dashboard.
- **Deployment:** Docker for containerization; free-tier cloud services (Heroku, Vercel, GitHub Pages) for hosting.

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AryanVarmora/insightscribe.git
   cd insightscribe
