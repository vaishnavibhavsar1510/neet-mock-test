# Student Performance Analysis and Recommendations

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

### Test Interface
- Clean, intuitive UI
- Progress tracking
- Real-time timer
- Easy navigation

### Analysis Dashboard
- Interactive visualizations
- Subtopic performance breakdown
- Strength/weakness identification
- Progress tracking over time

### AI Recommendations
- Performance-based suggestions
- Specific study strategies
- Time management advice
- Resource recommendations



## Installation

1. Clone the repository:
   git clone [(https://github.com/vaishnavibhavsar1510/neet-mock-test.git)]
   cd student_recommendations

2. Create a virtual environment:
   bash
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate

3. Install dependencies:
   bash
   pip install -r requirements.txt

4. Run the application:
   bash
   streamlit run app.py

## Project Structure
    student_recommendations/
├── src/
│ ├── app.py # Main application
│ ├── analyzer.py # Performance analysis logic
│ ├── recommender.py # Recommendation system
│ └── data_loader.py # Data handling
├── tests/ # Test files
├── requirements.txt # Dependencies
└── README.md # Documentation


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
