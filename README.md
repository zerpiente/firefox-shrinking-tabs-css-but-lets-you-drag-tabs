# Firefox: Chrome-like Shrinking Tabs

> A `userChrome.css` style to make Firefox tabs shrink down to a single, centered icon instead of scrolling.

*(Recommendation: Record a short GIF of the feature in action and replace the link below to show users how it works.)*

![A GIF demonstrating the tabs shrinking and centering the favicon](https://user-images.githubusercontent.com/example/shrinking-tabs-demo.gif)

---

## ✨ Features

* 🚫 **No More Scrolling:** The tab bar never activates the scroll arrows, allowing you to see all your open tabs at once.
* 🤏 **Extreme Compacting:** Tabs shrink down to a tiny size, showing only the centered favicon to save valuable screen space.
* 🐛 **Bug-Free:** Handles closing tabs smoothly with a quick animation that prevents the common "blank space" glitch.
* ✅ **Cross-Platform:** The CSS is platform-agnostic and should work on macOS, Windows, and Linux.

---

## 🖥️ Compatibility

This style has been tested and confirmed working on:

* **Firefox Version:** `140.0.4`
* **Operating System:** `macOS`

*(It is expected to work on other versions and operating systems, but not guaranteed.)*

---

## 🛠️ Installation

#### Step 1: Enable `userChrome.css` Customization

First, you need to tell Firefox to allow UI modifications.

1.  Type `about:config` into the Firefox address bar and press **Enter**.
2.  Accept the "Proceed with Caution" warning.
3.  Search for the preference: `toolkit.legacyUserProfileCustomizations.stylesheets`
4.  Click the toggle button on the right to set its value to **`true`**.

#### Step 2: Find Your Firefox Profile Folder

1.  Type `about:support` into the Firefox address bar and press **Enter**.
2.  Look for the **Profile Directory** entry.
3.  Click the **Open Directory** (or **Show in Finder** / **Open Folder**) button. This will open your personal Firefox profile folder.

#### Step 3: Create the `userChrome.css` File

1.  Inside the profile folder you just opened, create a new folder and name it **`chrome`** (all lowercase).
2.  Open the new `chrome` folder.
3.  Inside this folder, create a new text file and name it exactly **`userChrome.css`**.

#### Step 4: Add the Code

1.  Copy the code from the `userChrome.css` file in this repository.
2.  Paste it into the `userChrome.css` file you just created.
3.  Save and close the file.

#### Step 5: Restart Firefox

For the changes to take effect, you must **completely close and reopen Firefox**.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
