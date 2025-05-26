# UK Exam Questions Repository

📚 **Daily updated questions for UK Exam Pro mobile app**

## 🎯 Purpose
This repository contains category-wise question banks for UKSSSC and UKPSC exam preparation. Questions are updated daily and automatically synced with the UK Exam Pro mobile app.

## 📁 File Structure
```
├── hindi_questions.json          # Hindi language questions
├── uttarakhand_questions.json    # Uttarakhand specific questions  
├── science_questions.json        # Science questions
├── geography_questions.json      # Geography questions
├── history_questions.json        # History questions
├── computer_questions.json       # Computer science questions
├── reasoning_questions.json      # Logical reasoning questions
└── math_questions.json          # Mathematics questions
```

## 📝 JSON Format
Each question file follows this structure:

```json
{
  "category": "Category Name",
  "lastUpdated": "2024-01-15T10:30:00Z",
  "version": "1.0",
  "totalQuestions": 5,
  "questions": [
    {
      "question": "Question text here?",
      "options": ["Option 1", "Option 2", "Option 3", "Option 4"],
      "correctIndex": 0,
      "explanation": "Detailed explanation of the answer",
      "subCategory": "Subcategory name",
      "difficulty": "Easy|Medium|Hard"
    }
  ]
}
```

## 🔄 Update Schedule
- **Daily**: New questions added to existing categories
- **Weekly**: Review and quality check of all questions
- **Monthly**: Major updates and new subcategories

## 📱 App Integration
The UK Exam Pro mobile app automatically:
- Checks for updates daily
- Downloads only new questions
- Prevents duplicate questions
- Works offline after download

## 🌐 Raw File URLs
For app integration, use these raw GitHub URLs:

```
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/hindi_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/uttarakhand_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/science_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/geography_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/history_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/computer_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/reasoning_questions.json
https://raw.githubusercontent.com/YOUR_USERNAME/uk-exam-questions/main/math_questions.json
```

## ✅ Quality Guidelines
- All questions must have 4 options
- Correct answer index must be valid (0-3)
- Explanation must be clear and educational
- Questions should be exam-relevant
- No duplicate questions within category

## 📊 Current Stats
- **Total Categories**: 8
- **Total Questions**: 40 (5 per category)
- **Last Updated**: January 15, 2024
- **App Version Compatibility**: 1.0+

## 🤝 Contributing
To add new questions:
1. Follow the JSON format exactly
2. Ensure questions are accurate and relevant
3. Add proper explanations
4. Test JSON validity before committing
5. Update the lastUpdated timestamp

## 📞 Contact
For questions or suggestions about the question bank, please create an issue in this repository.

---
**Made with ❤️ for UKSSSC & UKPSC aspirants**
