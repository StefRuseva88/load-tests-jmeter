# Exercise: JMeter

## Overview
Assignments for the "Back-End Test Automation" course @ SoftUni. This guide introduces JMeter basics, installation, and scripting for performance testing.

---

## 1. Prerequisites
- Ensure the latest Java (JVM) is installed.

## 2. Installing JMeter
1. Download `apache-jmeter-{version}.zip` from [Apache JMeter Official Website](https://jmeter.apache.org/).
2. Unzip and run `jmeter.bat` in the `bin` folder.

## 3. Test Plan Elements
- **Threads (Users):** Simulate virtual users.
- **Samplers:** Define requests (e.g., HTTP).
- **Timers:** Add delays between requests.
- **Listeners:** Visualize test results.
- **Assertions:** Validate responses.

## 4. Writing Test Scripts
1. **Home Page Test:**
   - Add a Thread Group, HTTP Request, Timer, and Listener.
   - Example: Test `https://blazedemo.com` with 5 users.

2. **Reservations Test:**
   - Simulate flight search using parameters like `fromPort` and `toPort`.

3. **Recording Scenarios:**
   - Use BlazeMeter Chrome Extension to record and export `.jmx` scripts.

## 5. Dynamic Data Testing
- Use `CSV Data Set Config` for variable inputs (e.g., departure cities).


