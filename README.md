# Professional Self-Assessment

## Introduction

Throughout my journey in the Computer Science program, I have gained a comprehensive understanding of the technical, analytical, and collaborative skills necessary to thrive in the field. Completing my coursework and developing this ePortfolio has allowed me to reflect on my growth as a student and professional, and it has provided a platform to showcase my strengths and accomplishments. The program has been instrumental in shaping my professional goals and values, preparing me for a successful career in software engineering, and enhancing my employability in the tech industry.

## Strengths and Skills

### Collaborating in a Team Environment

One of the key strengths I have developed is the ability to work effectively within a team. Collaboration is essential in computer science, where large projects often require input from multiple disciplines. Through group assignments, I have learned to contribute to discussions, share ideas, and resolve conflicts in a constructive manner. In particular, during my work on projects, I worked with teammates to solve complex problems and ensure our deliverables met the required standards.

### Communicating with Stakeholders

Clear communication with stakeholders, whether they are clients, team members, or project managers, has been a fundamental aspect of my development. I have refined my ability to translate technical concepts into understandable terms for non-technical audiences, a skill that is invaluable in both academic and professional settings. For instance, in my Weight Tracker Pro project where I developed an interactive dashboard, I had to present the system’s functionality and explain its value proposition to a group of stakeholders with varying levels of technical expertise.

### Data Structures and Algorithms

My understanding of data structures and algorithms has grown significantly over the course of the program. I have developed the ability to analyze problems and implement efficient solutions using a range of data structures, such as arrays, linked lists, trees, and graphs. A standout example of this is my work on the Weight Tracker Pro project, where I optimized an algorithm for data retrieval, reducing the time complexity from O(n^2) to O(n log n). This project helped me appreciate the importance of selecting the right data structures and algorithms to ensure scalability and performance.

### Software Engineering and Database Management

The program has equipped me with a solid foundation in software engineering practices and database management. I have gained hands-on experience with developing applications using modern tools and methodologies, such as version control systems like Git, Agile frameworks, and SQL databases. My work on projects like Weight Tracker Pro allowed me to design, implement, and test robust software solutions that meet real-world requirements. I have also worked with relational and non-relational databases, optimizing queries for performance and ensuring data integrity.

### Security

Security has become an increasingly important aspect of my education. Throughout the program, I have learned to design and implement secure applications, paying careful attention to user authentication, data encryption, and vulnerability prevention. In my Weight Tracker Pro, I implemented multi-factor authentication and ensured secure data storage, which not only enhanced the application's security but also provided peace of mind to users and stakeholders.

## 📌 Code Review

Below is a direct link to my YouTube channel, where I’ve uploaded my **Code Review** video. In this review, I cover the following key areas:

- ✅ **Overview of Existing Functionality** – A step-by-step walkthrough explaining what the code does, how it operates, and its purpose.

- ✅ **Code Evaluation** – Analyzing the structure, efficiency, and readability of the code, while also checking for comments and documentation. I share insights on areas of improvement.

- ✅ **Potential Enhancements** – Reviewing planned improvements and discussing ways to optimize or expand the current functionality.

[📺 Watch the full Code Review here](https://www.youtube.com/watch?v=74-eLiDFAng)

## Artifacts Overview

This ePortfolio reflects my growth and achievements in the Computer Science program through various artifacts that demonstrate my technical skills and knowledge. The **Weight Tracker Pro** project represents a significant portion of my work, highlighting my ability to design and implement a full-stack application with a focus on user experience, functionality, and continuous improvement. The recent enhancements to this project include:

1. **Graphing Weight Trend**: I added a feature that displays users' weight trends over time using a graph. This enhancement demonstrates my skills in data visualization and my ability to implement the Model-View-Controller (MVC) design pattern to improve modularity.

   Pseudocode for Graph Implementation:

   ```python
   # Fetch weight entries from database
   weights = fetch_weights_from_database()

   # Process data for graph
   dates = [entry.date for entry in weights]
   values = [entry.weight for entry in weights]

   # Generate graph
   plot_graph(dates, values, title="Weight Trend Over Time")

   ```

2. **Optimized Search Algorithm**: I implemented an optimized search algorithm to filter weight entries by date range or keywords, showcasing my ability to improve algorithm efficiency and enhance user experience.

   Pseudocode for Optimized Search:

   ```python
   def search_entries(start_date, end_date):
   # Query database for entries within the date range
   query = "SELECT * FROM weights WHERE date BETWEEN ? AND ?"
   results = execute_query(query, (start_date, end_date))
   return results

   ```

3. **SQLite Data Backup**: I introduced a data export feature that allows users to back up their weight entries by exporting the SQLite database to a CSV file. This enhancement improves user data portability and provides additional functionality for managing data.

   Pseudocode for Export Feature:

   ```python
   def export_to_csv(database_path, csv_path):
   # Connect to SQLite database
   conn = sqlite3.connect(database_path)
   cursor = conn.cursor()

   # Fetch all data
   cursor.execute("SELECT * FROM weights")
   data = cursor.fetchall()

   # Write data to CSV
   with open(csv_path, 'w', newline='') as file:
       writer = csv.writer(file)
       writer.writerow(["Date", "Weight"])
       writer.writerows(data)
   conn.close()
   ```

**Weight Tracker Pro (CS-360, CS-499)** - This project showcases my ability to design and implement a full-stack application with a focus on user experience and functionality.

[Link to Enhanced Weight Tracker Pro](./Weight-TrackerPro-3.0.zip)

[Link to Original Weight Tracker Pro](./WeightTrackerPro-OldVersion.zip)

This artifact enhancements come together to provide a comprehensive picture of my abilities in software development, data management, security, and collaboration. The variety of projects reflects my versatility and readiness to tackle challenges in the computer science field.

## Conclusion

In conclusion, my time in the Computer Science program has not only equipped me with technical expertise but also helped me develop the skills necessary to excel in a professional environment. From collaboration and communication to software engineering and security, I am confident in my ability to contribute to and lead complex projects. This professional self-assessment and the artifacts within my ePortfolio demonstrate the range of my skills and capabilities, preparing me to enter the workforce as a skilled and employable software engineer.
