Student Placement Project Conclusion
A simple summary of the analysis and its results
What the data shows
Across 10,000 student records, 8,356 students are marked as placed (83.6%), and the average exam score is 86.7 out of 100. Students with more study hours, more completed assignments, and stronger attendance generally have higher exam scores and placement rates. These patterns show a relationship in this dataset; they do not prove that any one factor caused placement.
Model results
The machine-learning notebook reports 99.8% accuracy, but its model uses exam score as an input. The dataset itself marks students as placed when their exam score is 70 or higher. The model is therefore given the rule that defines its answer, so this score should not be treated as proof of real-world prediction ability.
The dashboard also reports a model that leaves exam score out. It reached 90.6% accuracy and a 0.94 ROC-AUC on a 2,000-student test sample. It identified 64% of students who were not placed; class weighting raised that figure to 90%. This result is more useful, but it still needs testing on a separate group of students.
Conclusion
The project gives a clear summary of student performance and shows which groups may need more academic support. Before using a model to make placement decisions, test it with information available before the exam and evaluate it on new student data. For now, use these results to guide support, not to decide a student’s future.
