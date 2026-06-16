# Grade 11 Mathematics Question Bank

A comprehensive, interactive question bank for Grade 11 Mathematics covering all units from St. Joseph Catholic School Adama (2018 E.C.).

## Features

### 📚 Content Coverage
- **8 Complete Units** with 200+ questions:
  - **Unit 1**: Relations & Functions
  - **Unit 2**: Rational Expressions
  - **Unit 3**: Matrices
  - **Unit 4**: Determinants
  - **Unit 5**: Vectors
  - **Unit 6**: Transformation of the Plane
  - **Unit 7**: Statistics
  - **Unit 8**: Probability & Counting

### 🎯 Question Difficulty Levels
- **Easy** - Foundational concepts
- **Medium** - Application and problem-solving
- **Hard** - Advanced analysis and synthesis

### 🔧 Interactive Features
- **Search functionality** - Find questions by keyword or concept
- **Unit filtering** - Browse questions by specific units
- **Difficulty filtering** - Filter by easy, medium, or hard questions
- **Expandable cards** - Click to reveal detailed solutions
- **Multiple-choice interaction** - Select answers and get immediate feedback
- **Answer explanations** - Detailed explanations for every question

### 🎨 User Experience
- **Dark mode support** - Automatic detection of system preferences
- **Responsive design** - Works seamlessly on desktop, tablet, and mobile
- **Clean interface** - Intuitive navigation and organized layout
- **Real-time filtering** - Instant results as you search and filter
- **Statistics display** - See how many questions match your filters

## How to Use

### Opening the Question Bank
1. Open `index.html` in any modern web browser
2. The page loads with all questions displayed by default

### Searching for Questions
- Use the search bar at the top to find questions by:
  - Keywords from the question text
  - Mathematical concepts
  - Explanations
- Results update in real-time as you type

### Filtering by Unit
- Click any unit button (U1–U8) to show only questions from that unit
- Click "All Units" to reset and view all questions

### Filtering by Difficulty
- Click "Easy", "Medium", or "Hard" to filter by difficulty level
- Combine with unit filters for specific learning paths
- Click again to deselect

### Viewing Questions
- Click on any question card to expand it
- The question unfolds to show:
  - Multiple-choice options (A, B, C, D)
  - A button to reveal the answer
  - Detailed explanations
- Click again to collapse

### Answering Questions
1. **Option 1**: Click "Show answer & explanation" to view the correct answer
2. **Option 2**: Click one of the multiple-choice options to attempt the question
   - Selected answers are highlighted
   - Correct answers are shown in green
   - Incorrect selections are highlighted in red
   - Full explanation appears below

## Question Statistics

The question bank includes:
- **Total Questions**: 200+
- **Units**: 8
- **Easy Questions**: ~80
- **Medium Questions**: ~80
- **Hard Questions**: ~40+

### Distribution by Unit
- Unit 1 (Relations): 16 questions
- Unit 2 (Rational): 9 questions
- Unit 3 (Matrices): 10 questions
- Unit 4 (Determinants): 10 questions
- Unit 5 (Vectors): 14 questions
- Unit 6 (Transformations): 13 questions
- Unit 7 (Statistics): 18 questions
- Unit 8 (Probability): 60+ questions

## Technical Details

### Built With
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables
- **Vanilla JavaScript** - No external dependencies required

### Browser Compatibility
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

### Features
- **Offline ready** - All content embedded, works without internet connection
- **Lightweight** - Single HTML file, fast loading
- **No external dependencies** - Runs entirely in the browser

## File Structure

```
maths/
├── index.html    # Main question bank application
└── README.md     # This file
```

## Color Scheme

### Light Mode
- Background: Light cream (#f8f7f4)
- Surface: White
- Text: Dark gray

### Dark Mode
- Background: Dark gray (#1a1a18)
- Surface: Dark tone (#26261f)
- Text: Light cream

### Difficulty Badges
- **Easy**: Green (#639922)
- **Medium**: Orange (#BA7517)
- **Hard**: Red (#E24B4A)

## Tips for Effective Study

1. **Start with Easy questions** to build foundational understanding
2. **Progress to Medium questions** to apply concepts
3. **Challenge yourself with Hard questions** for deeper mastery
4. **Use search** to find questions related to specific topics you're struggling with
5. **Filter by unit** to focus on one topic at a time
6. **Review explanations** even for questions you answer correctly

## Contributing

To add or modify questions:
1. Edit the `QUESTIONS` array in the `<script>` section of `index.html`
2. Follow the format:
```javascript
{ 
  unit: 1,                                    // Unit number (1-8)
  id: '1-1',                                 // Unique identifier
  num: 1,                                    // Question number within unit
  text: 'Question text here...',             // The question
  opts: ['Option A', 'Option B', '...'],     // Multiple choice options
  answer: 0,                                 // Index of correct answer (0-3)
  diff: 'easy',                              // Difficulty: 'easy', 'medium', 'hard'
  explain: 'Explanation of the answer...'    // Detailed explanation
}
```

## Future Enhancements

Potential features to add:
- Progress tracking and statistics
- Bookmarking favorite questions
- Printable worksheets
- Mixed difficulty practice sets
- Timer for timed practice sessions
- Solution videos or external resources
- Export answers as PDF

## Support & Contact

For questions about the content or to report issues, please visit the repository or contact the maintainers.

## License

These materials are provided for educational purposes at St. Joseph Catholic School Adama.

---

**Last Updated**: 2018 E.C.  
**Repository**: [Sinbo-lab/maths](https://github.com/Sinbo-lab/maths)
