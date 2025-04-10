# Student Score Grading Project

A Python-based application designed to manage and evaluate student academic performance. This system allows users to input scores for different subjects and automatically assigns grades based on predefined score ranges. The goal is to provide a simple, accurate, and efficient solution for grading students.

## Features

- Add and manage student information
- Input subject-wise scores
- Automatically calculate letter grades (A-F)
- Display student average scores and grade summaries
- Optional export of reports in text or CSV formats
- Modular, easy-to-extend Python structure

## Grading Criteria

| Score Range | Grade |
|-------------|-------|
| 90-100      | A     |
| 80-89       | B     |
| 70-79       | C     |
| 60-69       | D     |
| Below 60    | F     |

## Technologies Used

- **Language:** Python 3.x
- **Database:** SQLite (optional for persistence)
- **CLI / GUI / API:** Customize as needed
- **Optional Web Framework:** Flask / Django

## Getting Started

### Prerequisites

- Python 3.8 or higher
- `pip` for package management

### Installation

1. Clone the repository:

   ```
   score = int(input("Whats your score \n"))
   if 90 <= score <= 100:
   print("Your possition is excellent")
   elif 80 <= score < 89:
   print("very good")
   elif 70 <= score < 79:
   print ("good")
   elif 60 <= score < 69:
   print ("satisfactory")
   elif 50 <= score < 59:
   print ("needs improvement")
   elif 0 <= score < 49:
   print("fail")
   else:
   print ("invalid score, input a number between 0 to 100")
   ```
2. (Optional) Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate


3. Install dependencies (if any):

pip install -r requirements.txt


4. Run the application:

python main.py



Future Improvements

Add persistent database support

Build a web interface using Flask or Django

Implement user authentication for teachers


License

This project is licensed under the MIT License.

Author

Chizydon
