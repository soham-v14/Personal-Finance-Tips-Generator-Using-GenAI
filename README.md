# Personal-Finance-Tips-Generator-Using-GenAI


A **Generative AI-based tool** that provides personalized budgeting advice and money-saving suggestions.
It takes in basic financial information (income, spending habits, and savings goals) and uses both hard-coded financial logic and GPT-3.5 to generate actionable, friendly advice.

---

## Features

- Accepts user input:
  - Monthly Income
  - Spending Habits
  - Savings Goal

- Performs financial analysis:
  - Estimates fixed & discretionary expenses
  - Assesses feasibility of savings goal
  - Highlights potential problem areas in spending

- Uses GPT-3.5 to:
  - Craft human-friendly advice and encouragement
  - Suggest specific actions to improve financial habits

---

## Tools & Technologies

- Python 3.8+
- OpenAI GPT-3.5 API
- Libraries: openai, python-docx (optional for reports)

---

## Project Structure

personal_finance_tip_generator.py   # Main script
README.txt                           # This file
requirements.txt                     # Required Python packages

---

## Setup Instructions

1. Clone the repository

```bash
git clone "https://github.com/soham-v14/Personal-Finance-Tips-Generator-Using-GenAI.git"
cd personal-finance-tip-generator
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

Contents of requirements.txt:
openai
python-docx


---

## Usage

Run the script:

python personal_finance_tip_generator.py

You’ll be prompted to provide:
- Your monthly income
- A description of your spending habits
- Your savings goal

The tool will output friendly and actionable financial advice tailored to your situation.

---

## Example Output

✅ Your goal of saving $500 per month is realistic given your income — great job setting that goal!

Here are some tips to help you reach it:
1. Track your expenses with a simple app or spreadsheet.
2. Limit dining out and plan more meals at home.
3. Set a monthly shopping budget and stick to it.
4. Automate your savings transfer right after payday.

You’re already on the right track — keep it up!

---

## Future Enhancements

- Web-based interface using Streamlit or Flask
- Historical tracking of user inputs & progress
- Multi-language support
- Advanced budgeting strategies & calculators
- User feedback loop to improve suggestions

---

## Contributing

Pull requests are welcome! If you’d like to contribute, please fork the repo and submit a PR.

---

## License

This project is licensed under the MIT License.

---

## Contact

College Name, Student Name, Email to be added here
GitHub: https://github.com/your-username
