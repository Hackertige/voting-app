# voting-app
Voting Application
This is a backend application for a voting system where users can vote for candidates. It provides functionalities for user authentication, candidate management, and voting.

# Features
1.User sign up and login with Aadhar Card Number and password
2.User can view the list of candidates
3.User can vote for a candidate (only once)
4.Admin can manage candidates (add, update, delete)
5.Admin cannot vote
# Technologies Used
1.Node.js
2.Express.js
3.MongoDB
4.JSON Web Tokens (JWT) for authentication
# Installation
Clone the repository:


# API Endpoints
Authentication
# Sign Up
1.POST /signup: Sign up a user
# Login
1.POST /login: Login a user
# Candidates
Get Candidates
1.GET /candidates: Get the list of candidates
Add Candidate
2.POST /candidates: Add a new candidate (Admin only)
Update Candidate
3.PUT /candidates/:id: Update a candidate by ID (Admin only)
Delete Candidate
4.DELETE /candidates/:id: Delete a candidate by ID (Admin only)
# Voting
Get Vote Count
1.GET /candidates/vote/count: Get the count of votes for each candidate
Vote for Candidate
2.POST /candidates/vote/:id: Vote for a candidate (User only)
# User Profile
Get Profile
1.GET /users/profile: Get user profile information
Change Password
2.PUT /users/profile/password: Change user password
