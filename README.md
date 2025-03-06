# Resume Analyzer & Career Advisor

A cutting-edge solution that transforms resumes into actionable career insights. This project extracts key skills from resumes using KeyBERT, then employs a GPT-4o Mini model to generate dynamic quiz questions and MCQs. Based on the candidate's performance, it provides a detailed score and tailored recommendations for career paths and courses.

## Features
- **Automated Resume Parsing:** Extracts relevant skills and keywords seamlessly.
- **Dynamic Quiz Generation:** Creates interactive, real-time assessments to gauge candidate expertise.
- **Personalized Career Guidance:** Scores performance and suggests optimal career paths and learning opportunities.

## How It Works
1. **Resume Upload:** Users submit their resume for processing.
2. **Skill Extraction:** Key skills are identified using KeyBERT.
3. **Interactive Assessment:** The system generates customized quiz questions using a fine-tuned GPT-4o Mini model.
4. **Results & Recommendations:** Candidates receive a score along with personalized career and course recommendations.

## Technologies
- **Backend:** Python, FastAPI
- **NLP & AI:** KeyBERT, OpenAI (GPT-4o Mini)
- **Deployment:** Heroku, ngrok for local testing

## License
This project is licensed under the MIT License.
