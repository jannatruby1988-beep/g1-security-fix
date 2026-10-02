# G1 Security Fix
Fixed G1 Robot File Theft & BLE Hack

## Problem
G1 robot allowed ../../ to steal /etc/passwd

## Fix
Blocked path traversal, secured /data folder, added BLE auth

## Result
5/5 Security Tests Passed
