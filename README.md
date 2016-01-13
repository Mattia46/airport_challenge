Airport Challenge
=================

User stories
-----

We have a request from a client to write the software to control the flow of
planes at an airport. The planes can land and take off provided that the weather
is sunny. Occasionally it may be stormy, in which case no planes can land or
take off.  Here are the user stories that we worked out in collaboration with
the client.

```
As a pilot
So that I can arrive at my specified destination
I would like to land my plane at the appropriate airport

As a pilot
So that I can set off for my specified destination
I would like to be able to take off from the appropriate airport

As an air traffic controller
So that I can avoid collisions
I want to be able to prevent airplanes landing when the airport if full

As an air traffic controller
So that I can avoid accidents
I want to be able to prevent airplanes landing when the weather is stormy
```

How to run
----------

Clone this repo and run bundle:
```
$ git clone https://github.com/Mattia46/airport_challenge
$ gem install bundle
$ bundle
```
Type `rake` in the application's root folder.

Application Code:
-----------------

- `./lib/airport`
- `./lib/plane`
