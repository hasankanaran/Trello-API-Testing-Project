# Trello API Testing Project

This project is designed to test the Trello API using automated tests and Postman. It includes test cases for creating boards, lists, and cards, as well as updating and deleting them.

---

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Running the Tests](#running-the-tests)
- [Postman Collection](#postman-collection)
- [Test Cases](#test-cases)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

---

## Prerequisites

Before you begin, ensure you have the following installed:

- **Postman**: Download and install it from [postman.com](https://www.postman.com/downloads/).
- **Trello API Key and Token**: You already have these:
  - **API Key**: `Enter Your API KEY`
  - **API Token**: `Enter Your Api Token`

---

## Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hasankanaran/Trello-API-Testing-Project.git
   cd Trello-API-Testing-Project
   
##Folder Strucher
   
├── tests/                  # Contains all test files
│   ├── board.test.js       # Tests for board-related endpoints
│   ├── list.test.js        # Tests for list-related endpoints
│   └── card.test.js        # Tests for card-related endpoints
├── utils/                  # Utility functions or helpers
│   └── apiClient.js        # Axios client for making API requests
├── postman/                # Postman collection and environment files
│   ├── Trello-API-Testing-Project.postman_collection.json
│   └── Trello-API-Testing-Project.postman_environment.json
├── .env                    # Environment variables (not uploaded to GitHub)
├── .gitignore              # Specifies files to ignore in Git
├── package.json            # Node.js dependencies and scripts
├── README.md               # Project documentation
└── LICENSE                 # License file (optional)


