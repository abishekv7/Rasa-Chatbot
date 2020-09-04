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

## ms dhoni
* ms_dhoni
    -utter_msdhoni
	
## play songs
*play_music
	-utter_music
	
## call phone
*call_phone
  -action_call_phone
  
## mobile
* mobile
  -action_phone
 
## landline
* landline
  -action_landline
	
## number
* number
  -action_number