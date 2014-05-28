<!---
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
-->

# org.apache.cordova.vibration

Ten plugin umożliwia wibracje urządzenia.

## Instalacji

    cordova plugin add org.apache.cordova.vibration
    

## Obsługiwane platformy

*   Amazon ogień OS
*   Android
*   Jeżyna 10
*   Firefox OS
*   iOS
*   Windows Phone 7 i 8

## Notification.vibrate

Wibruje urządzenie na określoną ilość czasu.

    navigator.notification.vibrate(time)
    

*   **czas**: milisekund wibracje urządzenia. *(Liczba)*

## Przykład

    // Vibrate for 2.5 seconds
    navigator.notification.vibrate(2500);
    

## iOS dziwactwa

*   **czas**: ignoruje określony czas i wibruje na wstępnie określoną ilość czasu.
    
        navigator.notification.vibrate();
        navigator.notification.vibrate(2500);   // 2500 is ignored