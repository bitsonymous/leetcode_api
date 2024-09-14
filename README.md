# Documentation

## Overview

This API provides endpoints to retrieve various statistics and data related to LeetCode users. The API uses LeetCode's GraphQL endpoint to fetch data.

## Base URL
https://leetcodeapi-v1.vercel.app/


## Endpoints

### 1. Get User Stats

**URL:** `/{username}`

**Method:** `GET`

**Description:** Get detailed user statistics for a given LeetCode username.

**Path Parameters:**
- `username` (required): LeetCode username.

**Responses:**

- **200 OK**: Returns detailed user stats for the given username.
- **404 Not Found**: User not found on LeetCode.
- **500 Internal Server Error**: An error occurred while processing the request.

**Example Request:**

```bash
curl -X GET "https://api.yourdomain.com/bitsonymous"


