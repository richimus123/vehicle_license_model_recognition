# vehicle_license_model_recognition
Automatic recognition of license plates, determine if expired, look for hits in police database, recognize vehicle make and model.

# General Idea:
Python based ML to locate license plates and make/model of vehicles from pictures and/or video and perform a series of related tasks.  In short, make it so that Police officers don't need to manually enter license plate numbers while driving; and automate the task so that all vehicles in a "dash cam" can automatically be scanned.  This would be very useful esp in situations like Amber Alerts; the same algorithm/idea can be deployed to as many cameras as possible and try to find the vehicle in question.

# Tasks:
1) Get license plate state and unique numbers/letters combination.
2) Read if the registration is expired/current.
3) Check if there are any hits for the license plate/state combo in a simulated database of Police records.
4) Get the make/model of the vehicle based upon rear decals/logo/etc.
5) Validate make/model based upon overall shape and features of the vehicle.
6) Validate that the license plate matches the vehicle's make/model.
7) Auto-scan for infractions or hits and have an easy notification system.
8) Auto-scan for make/model of near by issues when the license plate is unknown or partial.
