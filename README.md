# Complex Form

This repository contains an HTML form with various input fields to capture personal and other information. The form is designed to be comprehensive and user-friendly, covering essential personal details, contact information, address, and additional comments.

## Table of Contents

- [Personal Information](#personal-information)
- [Address Information](#address-information)
- [Other Information](#other-information)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Personal Information

The first section of the form collects personal details, including:

- **Name**
- **Email**
- **Phone Number**
- **Date of Birth**
- **Gender**
- **Country**

## Address Information

The address section is designed to capture detailed location information:

- **Street Address**
- **City**
- **State**
- **Zip Code**

## Other Information

This section includes a text area for additional comments and a checkbox to agree to the terms of service.

## Usage

To use this form, simply include the provided HTML code in your project. You can customize the fields and styling as needed.

### Example Usage

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Complex Form</title>
    </head>
    <body>
        <form>
            <fieldset>
                <legend style="background-color: black; color: aliceblue;"><b>Complex Form</b></legend>
                <fieldset>
                    <legend>Personal Information</legend>
                    <label for="name">Name</label>
                    <input type="text" id="name" name="nm">
                    <label for="mail">Email</label>
                    <input type="text" id="mail" name="mail">
                    <label for="no.">Phone</label>
                    <input type="tel" id="no." name="phn">
                    <label for="date1">Date of Birth</label>
                    <input type="date" id="date1" name="dt">
                    <label for="gndr">Gender:</label>
                    <label for="male">Male</label>
                    <input type="radio" id="male" name="gender">
                    <label for="female">Female</label>
                    <input type="radio" id="female" name="gender">
                    <label for="other">Other</label>
                    <input type="radio" id="other" name="gender">
                    <br>
                    <label for="desh">Country</label>
                    <select name="CNTRY" id="desh">
                        <option value=""></option>
                        <option value="Afghanistan">Afghanistan</option>
                        <option value="Belgium">Belgium</option>
                        <option value="India">India</option>
                        <option value="United States">United States</option>
                        <option value="UK">UK</option>
                    </select>
                    <br>
                </fieldset>
                <fieldset>
                    <legend>
                        <label for="adrs">Street Address</label>
                        <input type="text" id="adrs" name="address">
                        <label for="sahar">City</label>
                        <input type="text" id="sahar" name="address">
                        <label for="state">State</label>
                        <input type="text" id="state" name="address">
                        <label for="zip">Zip Code</label>
                        <input type="text" id="zip" name="address">
                    </legend>
                </fieldset>
                <fieldset>
                    <legend>Other Information</legend>
                    <label for="cmnt">Comments</label>
                    <textarea name="cmnt" id="cmnt" cols="50" rows="10" placeholder="Type here...."></textarea>
                    <label for="agree">I agree to the terms of service</label>
                    <input type="checkbox" id="agree" name="accept">
                </fieldset>
                <input type="submit" id="sbmt">
            </fieldset>
        </form>
    </body>
</html>
