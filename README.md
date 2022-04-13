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
<img width="290" alt="Screenshot 2022-04-13 at 17 49 08" src="https://user-images.githubusercontent.com/58670404/163230701-7736b3d2-84da-47f4-bc0c-a1161e4e2c5d.png">

### Register
<img width="290" alt="Screenshot 2022-04-13 at 17 49 29" src="https://user-images.githubusercontent.com/58670404/163230829-b6372cb5-ffa3-4e5e-bd58-a5d87b1692f5.png">

### Login
<img width="290" alt="Screenshot 2022-04-13 at 17 49 19" src="https://user-images.githubusercontent.com/58670404/163230791-9abdd48d-a23a-44e0-b437-d59997ded62d.png">

### Habits
<img width="345" alt="Screenshot 2022-04-13 at 12 29 30" src="https://user-images.githubusercontent.com/58670404/163203977-4793ff8d-ac74-4b5c-aedc-119d90b8d8ba.png">

### Add Habits
<img width="345" alt="Screenshot 2022-04-13 at 12 29 38" src="https://user-images.githubusercontent.com/58670404/163203916-de231e8e-eac0-498f-8bb5-9eb6a8a1e161.png">

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
