---

layout: col-sidebar
title: OWASP Seraphimdroid
tags: example-tag
level: 0
type: tool

auto-migrated: 1
auto-migrated: 1

---

{front matter for this file}

## Mission:

To create, as a community, an open platform for education and protection of Android users against privacy and security threats.

## Project 

OWASP Seraphimdroid is a privacy and security protection app for Android devices. It enables users to protect their devices against malicious software (viruses, trojans, worms, etc.), phishing SMS, MMS messages, execution of dangerous USSD codes, theft and loosing. Also, it enables user to protect their privacy and to control the usage of applications and services via various kinds of locks.

OWASP Seraphimdroid has two aims:

* To protect user's privacy and secure the device against malicious features that may cost user money
* To educate user about threats and risks for their privacy, privacy of their data and security of their device.

<iframe src="https://www.youtube.com/embed/WccEBFaBXOw" allowfullscreen="true" width="640" height="360" frameborder="0"></iframe>

![OWASP SEraphimdroid screenshot](https://www.owasp.org/images/thumb/2/23/OWASPSeraphimdroid.png/200px-OWASPSeraphimdroid.png)

## Deeper introduction
Android users face many threats and risks. Since modern mobile devices are almost all the time exposed to the internet and other types of mobile networks, they are more exposed to the attacks. From the open WiFi networks that can be spoofed to the Trojan malware applications on the app stores, threats are everywhere around. Many of the attacks are successful because users are not aware of the risks and threats. They may act naive and expose themselves to the attacks even more. These attacks may lead to the identity theft, money theft, losing privacy or they devices may start acting as part of the botnet network.

In order to prevent attacks on the users, this project aims to develop a set of guidelines and application that will ensure that users are using their devices in a secure manner. Project is and always will remain open for everyone to participate and all project deliverables will be free and open source.


Project development is done on GitHub: https://github.com/nikolamilosevic86/owasp-seraphimdroid

Release of OWASP Seraphimdroid is available on Google Play: https://play.google.com/store/apps/details?id=org.owasp.seraphimdroid

## Description

The aim of this project is to research all threats and risks for users of Android operating system. We want to develop, as a community an free and open source security and privacy protection application and a set of security guideline for Android users. The project tend to be research oriented and we are willing to innovate in Android security field using machine learning, heuristics and other innovative techniques in order to protect our users, their privacy and money. The project is community driven and everyone is open to participate. The main aim of OWASP SeraphimDroid application should keep user data and money safe.

So far the main features include:

* Permission scanner. Permission scanner will show you the list of all installed application and the permission they are using. Also app will describe potential malicious use of certain permissions. Seraphimdroid is using machine learning in order to predict whether application might be malicious (be a virus, Trojan, worm, rootkit, etc) or not and will notify the user.
* Application and service locker. With OWASP Seraphimdroid, user may lock access to certain or to all of your applications and system services (WiFi, network, BlueTooth) with password
* Install lock. This feature can lock all installing and uninstalling action on your device. Great for parental control.
* Outgoing call and SMS blocker. This feature will allow user to perform normally outgoing calls and SMS, but it will block outgoing calls and inform about outgoing SMS performed by trojan applications.
* Geo-fencing. This feature allows user to set a location range where the device should be. If the device exits the range it may set up alarm or start sending messages to the defined number with its location.
* Remote location. If user lost your phone, he is able to send SMS with a defined secret code as a content and his phone and it will reply with the location coordinates of the device.
* Remote lock and lock
* Network and CPU monitoring

## Licencing

GNU GPL v3 License (allows commercial use, but requires that modifications to your code stay open source, thus prohibiting proprietary forks of your project)
