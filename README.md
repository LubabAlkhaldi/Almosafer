# Almosafer Website Test Automation 🚀

This project is a **Selenium-based** test automation framework for the **Almosafer** website. It contains various tests to verify the website’s functionality and ensure a smooth user experience. The tests cover key aspects such as language selection, contact information, currency, hotel search, and more. 🌍

## Features 🔍

* **Language Validation**: Checks if the default language is set to English. 🇬🇧
* **Contact Information**: Verifies that the contact number displayed is correct. 📞
* **Currency Check**: Ensures that the currency is set to **SAR** (Saudi Riyal). 💰
* **Hotel Tab State**: Verifies that the "Hotels" tab is not selected by default. 🏨
* **Flight Dates**: Validates the departure and return dates for flights. ✈️
* **Random Language Switching**: Tests random switching between **English** and **Arabic**. 🔄
* **Hotel Search Functionality**: Checks if the hotel search tab accepts city input and performs search correctly. 🏙️
* **Room Selection**: Verifies the random selection of room options for hotel search. 🛏️
* **Search Results**: Ensures that the hotel search results are displayed properly after searching. 🔎

## Technologies Used 🛠️

* **Selenium WebDriver**: For automating browser interactions. 🌐
* **TestNG**: For running and organizing test cases. 🧪
* **Java**: For writing the test scripts. ☕️

## Test Cases Overview 📑

### 1. **English Default Language** 🇬🇧

* **Test**: Verifies that the default language on the website is English.
* **Expected Outcome**: The `lang` attribute in the `<html>` tag should be "en".

### 2. **Check Contact Number** 📞

* **Test**: Verifies that the displayed contact number is correct.
* **Expected Outcome**: The displayed contact number should match the expected value `+966554400000`.

### 3. **Check Currency (SAR)** 💰

* **Test**: Verifies that the currency displayed is Saudi Riyal (SAR).
* **Expected Outcome**: The currency displayed should be `SAR`.

### 4. **Hotel Tab Unselected** 🏨

* **Test**: Verifies that the "Hotels" tab is not selected by default when the page loads.
* **Expected Outcome**: The `aria-selected` attribute of the "Hotels" tab should be `false`.

### 5. **Flight Dates (Departure & Return)** ✈️

* **Test**: Verifies that the departure and return dates are set correctly (tomorrow and the day after tomorrow).
* **Expected Outcome**: The departure and return dates should match the expected values.

### 6. **Random Language Switch** 🔄

* **Test**: Randomly switches the website’s language between **English** and **Arabic**.
* **Expected Outcome**: The page should load in either English or Arabic based on the random selection.

### 7. **Hotel Search Tab (City Input)** 🏙️

* **Test**: Tests the hotel search input field by entering a random city name, either in English or Arabic.
* **Expected Outcome**: The city input field should accept the city name and trigger the search functionality.

### 8. **Random Room Selection** 🛏️

* **Test**: Verifies random selection of room options from the available list.
* **Expected Outcome**: A valid room option should be selected randomly from the list.

### 9. **Search Hotels Button** 🔍

* **Test**: Verifies that clicking the "Search Hotels" button triggers the search functionality.
* **Expected Outcome**: The button should be clickable and initiate the hotel search.

### 10. **Search Results Validation** ✔️

* **Test**: Verifies that the search results contain the word "found" or "مكان" (Arabic).
* **Expected Outcome**: The search result should contain the word "found" or its Arabic equivalent.  
