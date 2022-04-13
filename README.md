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
### Homepage
<img width="383" alt="Screenshot 2022-04-13 at 11 20 16" src="https://user-images.githubusercontent.com/58670404/163163053-8f8bda46-dd80-486f-aa7b-5b850d85144a.png">

### Register
<img width="384" alt="Screenshot 2022-04-13 at 11 20 30" src="https://user-images.githubusercontent.com/58670404/163163622-7cc36463-53c2-4c14-b545-746c0185199a.png"> 

### Login
<img width="384" alt="Screenshot 2022-04-13 at 11 20 25" src="https://user-images.githubusercontent.com/58670404/163163589-7970052d-c04d-430d-882c-2b8157f27fad.png">
 

### Habits
<img width="383" alt="Screenshot 2022-04-13 at 11 20 34" src="https://user-images.githubusercontent.com/58670404/163164072-c9ff44ac-b607-4c76-9393-de157b69f205.png">

### Add Habits
<img width="382" alt="Screenshot 2022-04-13 at 11 20 40" src="https://user-images.githubusercontent.com/58670404/163164197-10d7945c-b053-40c8-8a85-6f1b11e7f737.png">

## Test
- Test coverage 88%
<img width="557" alt="Screenshot 2022-04-13 at 14 59 46" src="https://user-images.githubusercontent.com/58670404/163197566-600b60ad-dac1-4e28-ac37-87fd8aa82357.png">


## Wins
- After registering the page automatically login 
- Add habit form pops down when clicked on 
- Each habit can be deleted using the `X` button on the right 
- `+` button on the left increase the count by one for each habit
- Once the counter reached the goal, the habit will be crossed out 

## Challenges
- Streak 
