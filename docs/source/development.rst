Developer Guide
===============

.. _backend:
Backend
-------

^^^^^^^^^^^^^
Prerequisites
^^^^^^^^^^^^^
- Python
- postgreSQL

^^^^^^^^^^^^^
Install Guide
^^^^^^^^^^^^^
TO BE DECIDED.

^^^^^^^^^^^^^
Usage Guide
^^^^^^^^^^^^^
Run the program please. Pretty please.

^^^^^^^^^^^^^
Components
^^^^^^^^^^^^^
- Database: PSQL Server that runs.
- Database Connector: Python script that connects the PSQL server to the rest of the backend.
- Location Manager: Python script that interfaces with the Location API to pull map data and push it to the frontend.
- User Manager: Python script that manages distributing and storing updates to users.
- Chatroom Manager: Python script that manages distributing and storing updates to chatrooms.
- User Validator: Python script that ensures users have permissions to access any particular resources (chatrooms, profiles, etc.)


.. _frontend:
Frontend
--------

App development, developed by **[WILL DECIDE LATER]**

Technologies are currently Dart and Flutter, as well as Android Studio Goes in ``/frontend/``

^^^^^^^^^^^^^
Prerequisites
^^^^^^^^^^^^^

- Flutter (2.1GB)
- Android Studio (1.4GB) + SDK (2.4GB) (And more.)

^^^^^^^^^^^^^
Install Guide
^^^^^^^^^^^^^

1. Install Flutter as described here: https://docs.flutter.dev/install/quick
2. Install Android Studio as described here: https://developer.android.com/studio/install
3. Set it up for use with Flutter as described here: https://docs.flutter.dev/platform-integration/android/setup

^^^^^^^^^^^^^
Test Instructions
^^^^^^^^^^^^^

1. Pull this repository and open it with your preferred Code Editor
2. Run ``cd frontend`` in the terminal.
3. Setup your device:

* Run ``flutter emulators --launch [Emulator_Name]`` to launch your Android Emulator
* Run ``???`` to connect to your actual phone.

4. Run ``flutter run`` in the terminal to open your Android Emulator/Device and run the app.

^^^^^^^^^^^^^
Build Instructions
^^^^^^^^^^^^^

1. Pull this repository and open it with your preferred Code Editor
2. Run ``cd frontend`` in the terminal.
3. Run ``flutter build`` in the terminal to compile app.


.. _goals:
Developer Goals
---------------
Scope of the project is to produce an application (and accompanying backend) that covers all possible User and System requirements as listed in Coursework Item 1.



