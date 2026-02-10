# 📚 SATs Mathematics Question Bank

A comprehensive digital repository of UK Year 6 SATs mathematics questions from 2000-2025, containing over 1,400 questions with detailed answers and hierarchical topic organisation.

## 🚀 Live

Visit the live site: [https://Rbeadle21.github.io/Yr6-sats-question-bank/](https://Rbeadle21.github.io/Yr6-sats-question-bank/)

## 🌟 Features

- **1,400+ Questions**: Complete coverage of SATs papers from 2000-2025
- **Hierarchical Topics**: Organized by main categories (Number, Geometry, Statistics, etc.) and subcategories
- **Random Generation**: Generate truly random worksheets from selected topics
- **Customizable Filters**: Filter by difficulty, year range, and number of questions
- **Interactive Editing**: Remove unwanted questions and add new ones from the sidebar
- **Print Support**: Print worksheets and answer sheets
- **Embedded Images**: All question images stored in database - no external files needed
- **Fully Client-Side**: Runs entirely in browser using SQL.js - no server required

## 🎯 Use Cases

- **Teachers**: Create custom practice worksheets for students
- **Parents**: Generate homework and revision materials
- **Tutors**: Build targeted practice sets by topic
- **Students**: Self-study with randomized questions

## 📖 How to Use

1. **Select Topics**: Expand categories and check the topics you want to practice
2. **Set Filters**: Choose difficulty level, year range, and number of questions
3. **Generate**: Click "Generate Worksheet" to create a random set of questions
4. **Customize**: Remove questions you don't want, add more from the sidebar
5. **Print**: Print the worksheet (without answers) or answer sheet (with answers)

## 📊 Database Structure

The database contains:
- **9 main categories**: Number, Geometry, Statistics, Fractions/Decimals/Percentages, Ratio & Proportion, Algebra, Measurement, Probability, Problem Solving
- **67 subcategories**: Detailed topic breakdown for precise targeting
- **1,436 questions**: Complete verified answers
- **1,433 images**: Embedded as BLOBs (~27MB total)

### Categories & Subcategories

**Number:**
- Four operations, Addition, Subtraction, Multiplication, Division
- Doubling/halving, 10/100/1000, Inverse operations
- Order of operations and brackets, Number properties
- Factors, Multiples, Roots and powers, Prime numbers
- Place value, Number line, Roman numerals
- Number patterns/sequences, Negative numbers
- Rounding, Estimation/approximation, Money

**Geometry:**
- Angles, Co-ordinates
- 2-D shapes (Quadrilaterals, Triangles, Circle)
- 3-D shapes, Nets
- Symmetry, Transformation (Reflection, Translation)
- Construction

**Statistics:**
- Charts and graphs
- Interpreting data
- Representing data
- Averages

*Plus: Fractions/Decimals/Percentages, Ratio & Proportion, Algebra, Measurement, Probability, and Problem Solving*

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Database**: SQLite (via SQL.js)
- **Hosting**: GitHub Pages (static hosting)
- **No Dependencies**: Self-contained, runs offline after initial load

## 📥 Local Development

To run locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/sats-question-bank.git
   cd sats-question-bank
   ```

2. Serve the files using any local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js http-server
   npx http-server
   ```

3. Open browser to `http://localhost:8000`

**Note**: Must use a local server (not `file://`) due to CORS restrictions with SQL.js

## 🤝 Contributing

This is a private educational resource. If you'd like to contribute or report issues, please contact Script Work Studio.

## ⚠️ Important Notes

- **Read-Only**: The web interface does NOT save changes to the database for other users
- **Local Storage**: Any edits you make are temporary and only visible to you
- **No User Accounts**: No login system - completely anonymous usage
- **UK Curriculum**: Based on UK National Curriculum Key Stage 2 SATs

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Copyright & Usage
- SATs questions are © Crown Copyright and used for educational purposes
- Database structure and web interface © 2025 Script Work Studio
- Free for personal and educational use
- Not for commercial distribution without permission

## 👨‍💻 Credits

**Developed by Script Work Studio**

Built with ❤️ for teachers, parents, and students preparing for Year 6 SATs.

---

**Last Updated**: February 2025  
**Version**: 1.0.0  
**Questions**: 1,436  
**Years Covered**: 2000-2025
