# Student Performance Analysis and Recommendations for NEET Test

An AI-driven solution to analyze quiz performance and provide personalized recommendations for NEET Testline students.

## Features

- Analyzes current and historical quiz performance
- Identifies topic-wise strengths and weaknesses
- Generates personalized study recommendations
- Determines student learning persona
- Provides actionable improvement strategies


## Technologies Used
- Python 3.8+
- Streamlit
- OpenAI GPT-3.5
- Plotly
- Pandas

## Features in Detail

### 🎯 Test Taking
- Real-time mock tests with timer
- Subject-wise question organization
- Auto-submission on time completion
- Multiple test attempts available

### 📊 Performance Analysis
- Overall score calculation
- Subject-wise performance metrics
- Detailed subtopic analysis
  - Physics: Mechanics, Optics, Nuclear Physics, Thermodynamics, Electromagnetism
  - Chemistry: Physical, Inorganic, Organic, Solutions, Chemical Bonding
  - Biology: Molecular Biology, Plant Physiology, Human Anatomy, Genetics, Ecology

### ⏱️ Time Management
- Question-wise time tracking
- Average time per question analysis
- Time management recommendations

### 🤖 AI-Powered Recommendations
- Personalized study strategies
- Data-driven improvement suggestions

###  Screenshots of Execution (Prototype)


![Screenshot 2025-01-27 100537](https://github.com/user-attachments/assets/90c66678-e9d9-4803-a52e-8590a2e2ab4f)
![Screenshot 2025-01-27 100514](https://github.com/user-attachments/assets/ad1145f0-fee2-4dba-8513-a1c0f1baaf60)

![Screenshot 2025-01-26 225207](https://github.com/user-attachments/assets/48a40c32-7e1a-4d2f-aa2c-d434eb906cd8)

## Installation

1. Clone the repository:   <br>
   git clone [(https://github.com/vaishnavibhavsar1510/neet-mock-test.git)]   <br>
   cd student_recommendations     <br>

2. Create a virtual environment:    <br>
   bash      <br>
   python -m venv venv    <br>
   source venv/bin/activate # On Windows: venv\Scripts\activate    <br>

3. Install dependencies:     <br>
   bash    <br>
   pip install -r requirements.txt   <br>

4. Run the application:    <br>
   bash    <br>
   streamlit run app.py   <br>

## Project Structure  
student_recommendations/    <br>
├── src/    <br>
│ ├── app.py # Main application    <br>
│ ├── analyzer.py # Performance analysis logic    <br>
│ ├── recommender.py # Recommendation system     <br>
│ └── data_loader.py # Data handling     <br>
├── tests/ # Test files   <br>
├── requirements.txt # Dependencies    <br>
└── README.md # Documentation    <br>


## Contributing
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- OpenAI for GPT-3.5 API
- Streamlit for the web framework
- NEET exam guidelines for test structure

## Contact
For any queries or suggestions, please open an issue in the repository.
