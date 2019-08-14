# Webblock
A Python 3 website blocker that works by editing the hosts file in Windows.

## Prerequisites
Create a copy of your hosts file (in the same directory) with the name `hosts_ban`. This file should contain the websites that intend to be blocked.

## Notes
This program is intended to provide a wall between the user and directly editing the hosts file to ensure that blocked websites can not be unblocked within a short amount of time, rendering the blocking useless. This is achieved by requiring the user to guess a randomly-generated integer "password" between the numbers 1 - 99. By editing the source code, a user can change the range of the password, consequently changing the average time needed to edit the hosts file.
