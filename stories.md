## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy
  - utter_goodbye

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* mood_affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* mood_deny
  - utter_goodbye

## say my name
* name{"name":"Gigi"}
  - utter_greet_with_name

## say goodbye
* goodbye
  - action_joke
  - utter_goodbye