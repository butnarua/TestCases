# Test Case Samples

Below are some Test Case samples that I wrote while working on previous projects.

-----------------------------

**Description:**
Check if the login works when a user enters the correct credentials.

**Steps to Reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add correct email
3. Click "Continue" button
4. Add correct password
5. Click "Login" button

**Expected result:**
User should be able to login and is redirected to his profile page.

**Test Data:**
email: andrei@gmail.com
password: 123456

---------------------------

**Description:**
Check if the "Reset password" link works when a user forgets his password.

**Steps to Reproduce:**
1. Open https://auth.emag.ro/user/login
2. Add correct email
3. Click "Continue" button
4. Click "Forgot password" link
5. Click "Reset password" button in the received email
6. Add new password
7. Add new password confirmation
8. Click "Continue" button

**Expected result:**
User should be able to reset his password and is redirected to his profile page.

**Test Data:**
email: andrei@gmail.com
New password: 123456
New password confirmation: 123456

**Note:**
Please check the login again after running this test case.

-----------------------------

**Description:**
Check if the login works when a user wants to login via social media account.

**Pre-conditions:**
User should have a valid social media account (Facebook, Google, Apple) and be logged into it.

**Steps to Reproduce:**
1. Open https://auth.emag.ro/user/login
2. Click "Google" social media button
3. Click "Continue as" button

**Expected result:**
User should be able to login and is redirected to his profile page.

------------------------------

**Description:**
Check if the search works when a user enters the data.

**Steps to Reproduce:**
1. Open https://www.emag.ro/#opensearch
2. Write "earpods" in the input
3. Click "Search" button

**Expected result:**
User should be able to search for the desired product and see all available earpods products.

-------------------------------

**Description:**
Enter an empty search query and ensure it provides an appropriate error message or doesn't initiate a search.

**Steps to Reproduce:**
1. Open https://www.emag.ro/#opensearch
2. Let search box input empty
3. Click "Search" button

**Expected result:**
A list of popular searches will be shown to the user and the search button doesn't initiate a search.
