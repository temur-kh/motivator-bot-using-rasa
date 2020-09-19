## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## say goodbye
* goodbye
  - utter_motivational_quote
  - utter_goodbye

## path 0
* greet
  - utter_greet
* mood_unhappy
  - utter_what_did_happen
* have_to_do_activity
  - utter_when_is_deadline
* deadline_soon
  - utter_hurry_up
  - utter_need_some_inspiration
* deny
  - utter_motivational_quote
  - utter_goodbye

## path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_what_did_happen
* have_to_do_activity
  - utter_when_is_deadline
* deadline_soon
  - utter_hurry_up
  - utter_need_some_inspiration
* affirm
  - utter_motivational_quote
  - utter_motivational_video
  - utter_did_that_help
* affirm
  - utter_good_luck

## path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_what_did_happen
* have_to_do_activity
  - utter_when_is_deadline
* deadline_soon
  - utter_hurry_up
  - utter_need_some_inspiration
* affirm
  - utter_motivational_quote
  - utter_motivational_video
  - utter_did_that_help
* deny
  - utter_good_advice_to_start
  - utter_goodbye

## path 3
* greet
  - utter_greet
* mood_unhappy
  - utter_what_did_happen
* i_need_some_inspiration
  - utter_motivational_movie

## path 4
* thank_you_bot
  - utter_you_are_welcome
  - utter_goodbye

## path 5
* i_need_some_inspiration
  - utter_motivational_movie

## path 6
* create_a_notification
  - utter_notification_created
