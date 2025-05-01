# 📱 Android Fragment Transactions Demo – Experiment 7 (Part 2)

This Android app demonstrates how to **dynamically manage fragments** at runtime using various fragment operations such as `add`, `remove`, `attach`, `detach`, and `replace`.

## 🔍 Description

In this experiment, the user can interact with buttons in the main activity to:

- Add two fragments (`FirstFragment` and `SecondFragment`)
- Remove them individually
- Attach and detach the first fragment
- Replace one fragment with the other

This showcases the flexibility and control developers have over fragment lifecycle and management using `FragmentTransaction`.

## 🛠 Features Demonstrated

- `add()` – Add a fragment to the UI
- `remove()` – Remove a fragment from the UI
- `attach()` – Reattach a previously detached fragment
- `detach()` – Temporarily remove a fragment without destroying its state
- `replace()` – Replace one fragment with another in the same container

## 🧩 Project Structure

```
com.example.exp7_2/
│
├── MainActivity.java         # Hosts all fragment-related logic and button listeners
├── FirstFragment.java        # Displays a green background with a label
├── SecondFragment.java       # Displays a blue background with a label
│
res/layout/
├── activity_main.xml         # Contains UI with 8 buttons for fragment operations
├── fragment_first.xml        # Layout for FirstFragment (green background)
├── fragment_second.xml       # Layout for SecondFragment (blue background)
```

## 📱 UI Overview

- Buttons in the `MainActivity` allow the user to:
  - Add/remove fragments
  - Attach/detach `FirstFragment`
  - Replace `FirstFragment` with `SecondFragment` and vice versa

Each action is applied using the Android `FragmentTransaction` APIs.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SajaAsfour/Android-Fragment-Transactions-Demo-Experiment-7-Part-2-Lab-Android.git
   ```
2. Open the project in **Android Studio**.
3. Run the app on an emulator or physical device.
