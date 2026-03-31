# Selenium Learning Project 🚀

A beginner-level test automation project built with **Selenium WebDriver**, **TestNG**, and **Maven** in Java.

## 📁 Project Structure
```
SeleniumLearning/
├── src/
│   ├── main/
│   │  
│   └── test/
│       └── java/
│           ├── ButtonExample.java
│           ├── LinkExample.java
│           └── TextBoxExample.java
├── pom.xml
└── .gitignore
```

## 🛠️ Technologies Used

- Java 25
- Selenium WebDriver 4.18.1
- TestNG 7.12.0
- Maven
- IntelliJ IDEA

## 🧪 Test Cases

### ButtonExample.java
- Click a button and verify page title
- Find the position (X, Y) of a button
- Get the background color of a button
- Get the height and width of a button

### LinkExample.java
- Click a link and navigate to dashboard
- Find destination URL without clicking
- Check if a link is broken (404)
- Count all links on the page
- Count links within a specific layout section

### TextBoxExample.java
- Type text into a text box
- Append text to an existing field
- Verify if a text box is disabled
- Clear typed text
- Retrieve typed text value
- Type email and use TAB key to move focus

## ▶️ How to Run

1. Clone the repository:
```
   git clone https://github.com/AAKDIVYANGANA/SeleniumLearning.git
```

2. Open in IntelliJ IDEA

3. Run Maven install:
```
   mvn clean install -U
```

4. Run individual test classes using TestNG

## 📌 Notes

- Chrome browser is required
- Selenium Manager automatically handles ChromeDriver setup
- Test site used: [leafground.com](https://www.leafground.com)

## 👩‍💻 Author

**Ahinsa Divyangana**
