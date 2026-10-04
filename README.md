## Evaluating NBA Talent Production by College

A data analytics project exploring which collegea consistently produce the best NBA players.

Using Python, SQL, and data visualization, I analyzed over 1,500 NBA players drafted between 1989 and 2021 to answer questions such as:

- Which colleges produce the highest-scoring NBA players?
- Which schools develop players with the longest careers?
- Which programs create the most impactful NBA talent?
- Which colleges have the highest draft "hit rate"?

This project focuses on turning raw NBA draft data into meaningful basketball insights through statistical analysis and visual storytelling.

---

### Technologies

- ```Python```
- `SQL (SQLite)`
- `pandas`
- `Matplotlib`
- `NumPy`
- `Jupyter Notebook`

---

### Analyses

Here's what you can discover from this project:

- **Points Per Game (PPG):** Compare which colleges produce the highest-scoring NBA players by analyzing the average career points per game of their top alumni.

- **Assists Per Game (APG):** Evaluate which programs consistently develop elite playmakers based on average career assists.

- **Career Longevity:** Measure how long players from each college remain in the NBA by comparing average seasons played.

- **Win Shares per 48 Minutes (WS/48):** Compare player efficiency and overall contributions using one of basketball's most widely used advanced metrics.

- **Box Plus/Minus (BPM):** Evaluate each college based on the overall on-court impact of its NBA alumni.

- **Draft Success Rate:** Calculate the percentage of drafted players from each college who reached a defined level of NBA success.

- **Overall College Rating:** Combine multiple statistical categories into a custom ranking system that compares the overall quality of NBA talent produced by each school.

---

### The Process

The project began by importing and cleaning the NBA Draft dataset before storing it in a SQLite database for analysis.

Each research question was translated into SQL queries that filtered, grouped, and summarized the data using joins, aggregate functions, CASE statements, Common Table Expressions (CTEs), and window functions where appropriate.

After validating the query results, the data was loaded into pandas for additional processing before creating publication-quality visualizations using Matplotlib.

Each visualization was accompanied by a written interpretation explaining the results, notable players, and why certain schools performed well according to the selected metric.

Rather than simply displaying charts, the goal was to communicate the story behind the data and explain what the statistics actually mean in a basketball context.

---

### What I Learned

During this project I strengthened several data analysis skills while learning how to communicate analytical findings more effectively.

### SQL

- Writing analytical SQL queries
- Aggregate functions
- GROUP BY & HAVING
- CASE statements
- Window functions
- Common Table Expressions (CTEs)

### Python

- Data cleaning with pandas
- Working with relational databases
- Automating analysis workflows

### Data Visualization

- Designing readable visualizations
- Comparing distributions
- Presenting statistical findings clearly

### Sports Analytics

- Understanding advanced NBA metrics
- Creating objective evaluation criteria
- Comparing player development across colleges

### Project Highlights

- Analyzed 1,500+ NBA players
- Combined SQL and Python within one workflow
- Built multiple statistical visualizations
- Wrote technical interpretations for every analysis
- Created a reusable workflow for future sports analytics projects

---

### Future Improvements

- Expand the analysis beyond Top-10 draft selections
- Build an interactive dashboard for exploring results
- Add additional advanced metrics such as VORP and PER
- Compare conference-level performance (ACC, SEC, Big Ten, etc.)
- Incorporate machine learning models for draft outcome prediction

---

### Dataset

[NBA Draft Basketball Player Data (1989–2021)](https://www.kaggle.com/datasets/mattop/nba-draft-basketball-player-data-19892021/data)

Source: Kaggle

---

## Connect

If you're interested in basketball analytics, data science, or sports analytics, feel free to connect or explore the project.
