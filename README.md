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
<img width="345" alt="Screenshot 2022-04-13 at 12 29 05" src="https://user-images.githubusercontent.com/58670404/163204210-cdc2743b-8ba2-4479-b72d-7708e34bddff.png">

### Register
<img width="345" alt="Screenshot 2022-04-13 at 12 29 20" src="https://user-images.githubusercontent.com/58670404/163204164-80369f38-0a7f-4458-8da4-1df97a3b9f0d.png">

### Login
<img width="345" alt="Screenshot 2022-04-13 at 12 29 12" src="https://user-images.githubusercontent.com/58670404/163204071-e29536c1-1116-4a41-a3b1-d270b6ec2f90.png">
 
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
