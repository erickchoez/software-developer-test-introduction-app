# The Musical Lake 🎶

This project solves the **Software Developer Basic Test: "The Musical Lake"**.  
It simulates three animals (frog, dragonfly, cricket) singing together and returns the remaining sounds in a song sequence given an input sound.

---

## Requirements
- [Docker](https://docs.docker.com/get-docker/) 
- [docker-compose](https://docs.docker.com/compose/install/) 

---

## Setup & Run

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd the-musical-lake
```

### 2. Create a new branch
```bash
git checkout -b feature/{first-name}-{last-name}-task-list
```

### 3. Build and start the app with Docker Compose
```bash
docker-compose up 
```

### 4. Example Output
When running the container, you will see results like:
```
Input: brr
Output: fiu, cric-cric, brrah
----
Input: birip
Output: trri-trri, croac
----
Input: plop
Output: cric-cric, brrah
----
Input: croac
Output: (silence)
----
```

---

## Development
To run locally without Docker:
```bash
npm install
npm start
```
