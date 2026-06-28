# Face Recognition Using ESP32

This project implements a real-time face recognition based access control system using Python, OpenCV, face_recognition, and an ESP32 DevKitC. The system identifies authorized users through facial recognition and wirelessly sends the result to an ESP32 over WiFi.

## Features

Real-time face recognition using a webcam.

Automatic handling of visually similar individuals (including twins) using Linear Discriminant Analysis (LDA).

WiFi communication between PC and ESP32 via HTTP.

Access Granted: Green LED + DC motor activation.

Access Denied: Red LED + buzzer alert.

Modular architecture with separate training, recognition, and hardware response modules.

## Tech Stack

Python

OpenCV

face_recognition (dlib)

scikit-learn

ESP32 (Arduino Framework)

HTTP & WiFi Communication

## Project Goal

To build a low-cost, intelligent biometric access control system capable of reliable face recognition and physical actuation using affordable embedded hardware.
