# ANSI SQL Using MySQL – 25 SQL Practice Questions

This repository contains solutions for 25 ANSI SQL practice questions based on an Event Management Database schema consisting of:

- Users
- Events
- Sessions
- Registrations
- Feedback
- Resources

The exercises cover SQL concepts such as:

- Joins
- Aggregation
- GROUP BY
- HAVING
- Subqueries
- CTEs
- Date Functions
- Window Analysis
- Data Validation
- Reporting Queries

---

# Database Schema

## ER Diagram / Schema

![Database Schema](images/schema.png)

---

# Sample Dataset

## Users Table

![Users Dataset](images/users.png)

## Events Table

![Events Dataset](images/events.png)

## Sessions Table

![Sessions Dataset](images/sessions.png)

## Registrations Table

![Registrations Dataset](images/registrations.png)

## Feedback Table

![Feedback Dataset](images/feedback.png)

## Resources Table

![Resources Dataset](images/resources.png)

---

# SQL Exercises

## 1. User Upcoming Events

**Problem Statement**

Show a list of all upcoming events a user is registered for in their city, sorted by date.

### Output

![Question 1 Output](images/q1.png)

---

## 2. Top Rated Events

**Problem Statement**

Identify events with the highest average rating, considering only those that have received at least 10 feedback submissions.

### Output

![Question 2 Output](images/q2.png)

---

## 3. Inactive Users

**Problem Statement**

Retrieve users who have not registered for any events in the last 90 days.

### Output

![Question 3 Output](images/q3.png)

---

## 4. Peak Session Hours

**Problem Statement**

Count how many sessions are scheduled between 10 AM and 12 PM for each event.

### Output

![Question 4 Output](images/q4.png)

---

## 5. Most Active Cities

**Problem Statement**

List the top 5 cities with the highest number of distinct user registrations.

### Output

![Question 5 Output](images/q5.png)

---

## 6. Event Resource Summary

**Problem Statement**

Generate a report showing the number of resources (PDFs, Images, Links) uploaded for each event.

### Output

![Question 6 Output](images/q6.png)

---

## 7. Low Feedback Alerts

**Problem Statement**

List all users who gave feedback with a rating less than 3, along with their comments and associated event names.

### Output

![Question 7 Output](images/q7.png)

---

## 8. Sessions per Upcoming Event

**Problem Statement**

Display all upcoming events with the count of sessions scheduled for them.

### Output

![Question 8 Output](images/q8.png)

---

## 9. Organizer Event Summary

**Problem Statement**

For each event organizer, show the number of events created and their current status.

### Output

![Question 9 Output](images/q9.png)

---

## 10. Feedback Gap

**Problem Statement**

Identify events that had registrations but received no feedback at all.

### Output

![Question 10 Output](images/q10.png)

---

## 11. Daily New User Count

**Problem Statement**

Find the number of users who registered each day in the last 7 days.

### Output

![Question 11 Output](images/q11.png)

---

## 12. Event with Maximum Sessions

**Problem Statement**

List the event(s) with the highest number of sessions.

### Output

![Question 12 Output](images/q12.png)

---

## 13. Average Rating per City

**Problem Statement**

Calculate the average feedback rating of events conducted in each city.

### Output

![Question 13 Output](images/q13.png)

---

## 14. Most Registered Events

**Problem Statement**

List the top 3 events based on the total number of user registrations.

### Output

![Question 14 Output](images/q14.png)

---

## 15. Event Session Time Conflict

**Problem Statement**

Identify overlapping sessions within the same event.

### Output

![Question 15 Output](images/q15.png)

---

## 16. Unregistered Active Users

**Problem Statement**

Find users who created an account in the last 30 days but haven’t registered for any events.

### Output

![Question 16 Output](images/q16.png)

---

## 17. Multi-Session Speakers

**Problem Statement**

Identify speakers who are handling more than one session across all events.

### Output

![Question 17 Output](images/q17.png)

---

## 18. Resource Availability Check

**Problem Statement**

List all events that do not have any resources uploaded.

### Output

![Question 18 Output](images/q18.png)

---

## 19. Completed Events with Feedback Summary

**Problem Statement**

For completed events, show total registrations and average feedback rating.

### Output

![Question 19 Output](images/q19.png)

---

## 20. User Engagement Index

**Problem Statement**

For each user, calculate how many events they attended and how many feedbacks they submitted.

### Output

![Question 20 Output](images/q20.png)

---

## 21. Top Feedback Providers

**Problem Statement**

List the top 5 users who have submitted the most feedback entries.

### Output

![Question 21 Output](images/q21.png)

---

## 22. Duplicate Registrations Check

**Problem Statement**

Detect if a user has been registered more than once for the same event.

### Output

![Question 22 Output](images/q22.png)

---

## 23. Registration Trends

**Problem Statement**

Show a month-wise registration count trend over the past 12 months.

### Output

![Question 23 Output](images/q23.png)

---

## 24. Average Session Duration per Event

**Problem Statement**

Compute the average duration (in minutes) of sessions in each event.

### Output

![Question 24 Output](images/q24.png)

---

## 25. Events Without Sessions

**Problem Statement**

List all events that currently have no sessions scheduled under them.

### Output

![Question 25 Output](images/q25.png)

---

# Technologies Used

- SQL
- ANSI SQL
- SQLite
- MySQL
- GitHub

---

# Author

**Vishal S**

B.Tech CSE (IoT)  
Saveetha Engineering College
