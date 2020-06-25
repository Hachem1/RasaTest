## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* open
    - utter_open_times

## New Story

* open
    - utter_open_times

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* are_you_bot
    - utter_iamabot

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* open
    - utter_open_times

## New Story

* open
    - utter_open_times

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* open
    - utter_open_times

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* open
    - utter_open_times
* are_you_bot
    - utter_iamabot

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* HelloWorldRequest
    - action_hello_world

## New Story

* HelloWorldRequest
    - action_hello_world

## New Story

* time
    - action_get_time

## New Story

* time
    - action_get_time

## New Story

* open
    - utter_open_times

## New Story

* time
    - action_get_time
* open
    - utter_open_times
* open
    - utter_open_times
* time
    - utter_open_times

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* time
    - action_get_time

## New Story

* time
    - action_get_time

## Story from conversation with 153d09d3b0a3448a9f1752841bbae776 on June 20th 2020

* greet
    - utter_greet
    - utter_how_can_i_help
* time
    - action_get_time
* open
    - utter_open_times
* greet
    - utter_goodbye

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* greet
    - utter_greet
    - utter_how_can_i_help
* greet
    - utter_greet
    - utter_how_can_i_help
* greet
    - utter_greet
    - utter_how_can_i_help
* goodbye
    - utter_goodbye

## New Story

* goodbye
    - utter_goodbye

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* open
    - utter_open_times
* goodbye
    - utter_goodbye

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* open
    - utter_open_times
* goodbye
    - utter_goodbye

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* open
    - utter_open_times
* open
    - utter_open_times

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* 21st_Century_Skills
    - utter_about_21st
    - utter_21st_what_can_i_do

## New Story

* what_bot_does
    - utter_what_does_bot_do

## New Story

* what_bot_does
    - utter_what_does_bot_do

## registraion Story
* greet
    - utter_greet
    - utter_how_can_i_help
* 21st_Century_Skills
    - utter_about_21st
    - utter_21st_what_can_i_do
* registration
    - registration_form
    - form{"name": "registration_form"}
    - form{"name": null}

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* 21st_Century_Skills
    - utter_about_21st
    - utter_21st_what_can_i_do
* registration
    - registration_form
    - form{"name":"registration_form"}
    - slot{"requested_slot":"full_name"}
* registration{"full_name":"firstname lastname"}
    - registration_form
    - slot{"full_name":"firstname lastname"}
    - slot{"requested_slot":"email_address"}
    - utter_ask_email
* registration{"email_address":"example@example.com"}
    - registration_form
    - slot{"email_address":"example@example.com"}
    - slot{"requested_slot":"phone_number"}
* registration{"phone_number":"07777738283"}
    - registration_form
    - slot{"phone_number":"07777738283"}
    - slot{"requested_slot":"status"}
    - utter_ask_work_status
    - registration_form
    - slot{"requested_slot":"status"}

## New Story

* greet
    - utter_greet
    - utter_how_can_i_help
* 21st_Century_Skills
    - utter_about_21st
    - utter_21st_what_can_i_do
* registration
    - registration_form
    - form{"name":"registration_form"}
    - slot{"requested_slot":"full_name"}
* registration{"full_name":"firstname lastname"}
    - registration_form
    - slot{"full_name":"firstname lastname"}
    - slot{"requested_slot":"email_address"}
    - utter_ask_email
* registration{"email_address":"example@example.com"}
    - registration_form
    - slot{"email_address":"example@example.com"}
    - slot{"requested_slot":"phone_number"}
    - utter_ask_phone_number
* registration{"phone_number":"07777738283"}
    - registration_form
    - slot{"phone_number":"07777738283"}
    - slot{"requested_slot":"status"}
    - utter_ask_work_status
* registration{"status":"working"}
    - registration_form
    - slot{"status":"working"}
    - slot{"requested_slot":"find_out"}
* registration{"find_out":"internet"}
    - registration_form
    - slot{"find_out":"internet"}
    - form{"name":null}
    - slot{"requested_slot":null}
