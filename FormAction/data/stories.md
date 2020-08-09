## slots Book
* greet
  - utter_greet
* search_provider{"facility_type": "hospital"}
  - slot_book  
  - form{"name": "slot_book"}
  - form{"name": null}
  - utter_slots_values
  - utter_ask_feedback
* thanks
  - utter_goodbye







## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

  
## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

  
  
  
## What is corona
* corona_intro
  - utter_corona_intro

## how does corona spread
* corona_spread
  - utter_corona_spread
 
## corona food spread
* corona_food_spread
  - utter_corona_food_spread
  
## corona warm weather
* warm_weather
  - utter_warm_weather

  
 
  
  
  
  
  
  
  
  