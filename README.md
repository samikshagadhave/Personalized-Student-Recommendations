# Personalized-Student-Recommendations
This script:

1.Analyzes student quiz performance.
2.Identifies weak topics and difficulty levels.
3.Generates personalized recommendations.
4.Uses a linear regression model to predict NEET rank.

1.Analyze Quiz Performance (analyze_quiz_performance
  1.Takes the latest quiz data and historical quiz performance (last 5 quizzes).
  2.Identifies weak topics and difficulty levels where the student struggles.
  3.Tracks accuracy trends over multiple quizzes.
  4.Provides personalized recommendations for improvement.

2.Predict NEET Rank (predict_neet_rank)
  1.Uses past NEET results and quiz scores to train a linear regression model.
  2.Predicts the student's NEET rank based on their average quiz scores.
  3. Ensures the predicted rank is always at least 1 (since ranks start from 1).

3.Example Usage
  1. Sample quiz data is analyzed to generate insights and recommendations.
  2. A student's NEET rank is predicted based on their recent quiz scores.

This approach helps students track their weak areas and estimate their NEET performance!
