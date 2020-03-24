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

## out of scope
* out_of_scope
  - utter_out_of_scope

## academic advising
* academic_advising
  - utter_academic_advising

## graduation
* graduation
  - utter_graduation
* graduation_advising
  - utter_graduation_advising

## inform person_name
* inform{"person_name": "John"}
    - slot{"person_name": "John"}
    - utter_greet
* inform{"person_name": "Jane"}
    - slot{"person_name": "Jane"}
    - utter_greet
* inform{"person_name": "mark"}
    - slot{"person_name": "mark"}
    - utter_greet
* inform{"person_name": "sarah"}
    - slot{"person_name": "sarah"}
    - utter_greet
* inform{"person_name": "Steven"}
    - slot{"person_name": "Steven"}
    - utter_greet
* inform{"person_name": "Joshua"}
    - slot{"person_name": "Joshua"}
    - utter_greet
* inform{"person_name": "Emily"}
    - slot{"person_name": "Emily"}
    - utter_greet
* inform{"person_name": "James"}
    - slot{"person_name": "James"}
    - utter_greet
* inform{"person_name": "george"}
    - slot{"person_name": "george"}
    - utter_greet
* inform{"person_name": "laura"}
    - slot{"person_name": "laura"}
    - utter_greet
