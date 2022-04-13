## Habit-tracking- Libits

## Contributors 
- Anwar
- Jaxson
- Sami
- Sidar
- Melissa

## Installation
- Clone or download the repo
- Open terminal and navigate to api folder
- Run npm install to install dependencies

## Usage
- Run docker compose up to get the containers up
- Run the following for tests
docker-compose.test.yaml up -d
docker exec -it debug_test_api bash -c "npm install && npm test"

## Design


## Test
- Test coverage 88%
Sceenshot

## Wins
- After registering the page automatically login 
- Add habit form pops down when clicked on 
- Each habit can be deleted using the X button on the right 
- + button on the left increase the count by one for each habit
- Once the counter reached the goal, the habit will be crossed out 

## Challenges
- Streak 
