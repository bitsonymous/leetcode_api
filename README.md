# Documentation

## Overview

This API provides endpoints to retrieve various statistics and data related to LeetCode users. The API uses LeetCode's GraphQL endpoint to fetch data.

## Base URL
https://leetcodeapi-v1.vercel.app/


## Endpoints

### 1. Get User Stats

**URL:** `/{username}`  
**Method:** `GET`  
**Description:** Retrieves detailed user statistics.  
**Path Parameter:** `username` (LeetCode username)  

**Example Request:**

```bash
curl -X GET "https://api.yourdomain.com/bitsonymous"


{
  "bitsonymous": {
    "submitStatsGlobal": {
      "acSubmissionNum": [
        {"difficulty": "easy", "count": 30},
        {"difficulty": "medium", "count": 50},
        {"difficulty": "hard", "count": 20}
      ]
    }
  }
}
2. Get Solved Questions by Difficulty
URL: /questions/{username}
Method: GET
Description: Retrieves the number of questions solved by difficulty.
Path Parameter: username (LeetCode username)

Example Request:

bash
Copy code
curl -X GET "https://api.yourdomain.com/questions/bitsonymous"
Example Response:

json
Copy code
{
  "easy": 30,
  "medium": 50,
  "hard": 20
}
3. Get User Contest Data
URL: /contest/{username}
Method: GET
Description: Retrieves user contest data.
Path Parameter: username (LeetCode username)

Example Request:

bash
Copy code
curl -X GET "https://api.yourdomain.com/contest/bitsonymous"
Example Response:

json
Copy code
{
  "userContestDetails": {
    "attendedContestsCount": 10,
    "rating": 1800,
    "globalRanking": 1234,
    "totalParticipants": 5000,
    "topPercentage": 5.0
  }
}
4. Get User Rating
URL: /rating/{username}
Method: GET
Description: Retrieves the user rating.
Path Parameter: username (LeetCode username)

Example Request:

bash
Copy code
curl -X GET "https://api.yourdomain.com/rating/bitsonymous"
Example Response:

json
Copy code
{
  "rating": 1800
}
Error Codes
404 Not Found: User or data not found.
500 Internal Server Error: Error processing the request.
Contact
For questions or issues, contact Himanshu Yadav at [your-email@example.com].

arduino
Copy code

You can save this text to a file named `README.md`.









