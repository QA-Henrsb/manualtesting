# 🧪 Manual Testing with uTest  
### 25 Scenarios – Functional / Visual / Content / Performance / Crash  
**Page Tested:** [https://academybugs.com/find-bugs/#](https://academybugs.com/find-bugs/#)

---

## Functional Test Scenarios

**#1** Product quantity resets when updating cart  

**Severity:** High  
**Issue Type:** Functional  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click the **Find Bugs** link on the navigation bar  
3. Add one or more products to the cart  
4. Click the **“View cart”** link on top of the page  
5. Set the products quantity to 3 or more  
6. Click **Update** below  

**Expected Result:**  
The product quantity can be increased past 2.  

**Actual Result:**  
When clicking on the update button, the product quantity becomes 2 again.  

---

**#2** Price range filter does not update results  

**Severity:** Medium  
**Issue Type:** Functional  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click the **Find Bugs** link  
3. Open a product  
4. In the right menu, find the **Filter by Price** section  
5. Select any of the price ranges  
6. Also open any item from the **Store Menu** and repeat  

**Expected Result:**  
A list of products in the selected price range is shown.  

**Actual Result:**  
The same page reloads with no filtering applied.  

---

**#3** Manufacturer link opens error page  

**Severity:** Medium  
**Issue Type:** Functional  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click **Find Bugs**  
3. Open any product  
4. Click the **manufacturer link** under the quantity  

**Expected Result:**  
The manufacturer link shows an appropriate page.  

**Actual Result:**  
The manufacturer link opens an error page.  

---

**#4** Twitter share link broken  

**Severity:** Medium  
**Issue Type:** Functional  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product  
4. Click the **Twitter share button**  

**Expected Result:**  
The Twitter share button should open a valid share page.  

**Actual Result:**  
The Twitter share button opens an error page.  

---

**#5** Grand total incorrectly calculated  

**Severity:** Critical  
**Issue Type:** Functional  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Add one or more products to the cart  
4. Click **“View Cart”** or **“Continue to Shipping”**  

**Expected Result:**  
The grand total equals the sum of all products in the cart.  

**Actual Result:**  
The grand total is **$100 higher** than the sum of all products.  

---

## Visual Test Scenarios

**#6** Product image not filling container  

**Severity:** Medium  
**Issue Type:** Visual  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click **Find Bugs**  
3. Click on **Dark Grey Jeans**  

**Expected Result:**  
The product image fills the box entirely.  

**Actual Result:**  
The image has white space on the right.  

---

**#7** Sign In button overlaps footer  

**Severity:** Low  
**Issue Type:** Visual  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product with no color options  
4. Scroll to the bottom of the right side menu  

**Expected Result:**  
The **Sign In** button is above the footer.  

**Actual Result:**  
The **Sign In** button overlaps the footer.  

---

**#8** Sign In button text misaligned  

**Severity:** Low  
**Issue Type:** Visual  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click **Find Bugs**  
3. Open a product  
4. Scroll to the sign-in form  
5. Enter invalid credentials and click **Sign In**  

**Expected Result:**  
The caption on the Sign In button is vertically centered.  

**Actual Result:**  
The caption is misaligned vertically.  

---

**#9** Unnecessary space under product images  

**Severity:** Low  
**Issue Type:** Visual  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click **Find Bugs**  
3. Find **Store Menu → All Items**  

**Expected Result:**  
Item images have no space underneath.  

**Actual Result:**  
Images have unnecessary space below.  

---

**#10** Password field misaligned  

**Severity:** Low  
**Issue Type:** Visual  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click **Find Bugs**  
3. Open any product  
4. Scroll to bottom → **Sign In** (without filling the form)  

**Expected Result:**  
The password title aligns with the field above.  

**Actual Result:**  
The title is misaligned.  

---

## Content Test Scenarios

**#11** Extra space in “Return to Store” button  

**Severity:** Low  
**Issue Type:** Content  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product  
4. Open the cart and clear all items  

**Expected Result:**  
“Return to Store” text spacing is even.  

**Actual Result:**  
Too much space before the last letter.  

---

**#12** Product description not in English  

**Severity:** Medium  
**Issue Type:** Content  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Click **Find Bugs**  
3. Open a product  

**Expected Result:**  
The short and long descriptions are in English.  

**Actual Result:**  
They appear in another language.  

---

**#13** Symbols in shopping cart popup  

**Severity:** Low  
**Issue Type:** Content  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Add items to the cart  
4. Hover over the **Shopping Cart** caption  

**Expected Result:**  
All characters are readable.  

**Actual Result:**  
Unreadable symbols appear.  

---

**#14** “New User” section not in English  

**Severity:** Low  
**Issue Type:** Content  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Scroll to bottom → **Sign In**  
3. Check **New User** section  

**Expected Result:**  
Text is in English.  

**Actual Result:**  
Text appears in another language.  

---

**#15** Color names misspelled  

**Severity:** Low  
**Issue Type:** Content  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product with color options  
4. Choose **Yellow** and **Orange**  

**Expected Result:**  
Colors spelled correctly.  

**Actual Result:**  
“Yellow” appears as **Yelow** and “Orange” as **Orang**.  

---

## Performance Test Scenarios

**#16** MySpace share page loads infinitely  

**Severity:** Low  
**Issue Type:** Performance  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product  
4. Click **MySpace share link**  

**Expected Result:**  
MySpace page loads correctly.  

**Actual Result:**  
The page loads infinitely.  

---

**#17** Hot Item product never loads  

**Severity:** High  
**Issue Type:** Performance  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product  
4. Click a product in **Hot Item** section  

**Expected Result:**  
Hot Item product displays normally.  

**Actual Result:**  
Page loads infinitely.  

---

**#18** Billing Address section loads infinitely  

**Severity:** Medium  
**Issue Type:** Performance  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Log in  
4. Select **Dashboard → Billing Address**  

**Expected Result:**  
Appropriate info is displayed.  

**Actual Result:**  
Billing Address loads infinitely.  

---

**#19** Billing Information never updates  

**Severity:** High  
**Issue Type:** Performance  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Sign up or log in  
4. Go to **Billing Information**  
5. Fill out form → click **Update**  

**Expected Result:**  
Billing info updates correctly.  

**Actual Result:**  
Page loads infinitely after clicking update.  

---

**#20** Order History never loads  

**Severity:** High  
**Issue Type:** Performance  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Log in  
4. Open **Order History**  

**Expected Result:**  
Order history displays correctly.  

**Actual Result:**  
Order history loads infinitely.  

---

## Crash Test Scenarios

**#21** Page freezes when changing currency  

**Severity:** High  
**Issue Type:** Crash  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product  
4. Change **currency** on right side menu  

**Expected Result:**  
Currency changes as expected.  

**Actual Result:**  
Page freezes when changing currency.  

---

**#22** Page freezes when selecting number of results  

**Severity:** High  
**Issue Type:** Crash  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Click buttons to change results count  

**Expected Result:**  
Correct number of results displayed.  

**Actual Result:**  
Page freezes when clicking result numbers.  

---

**#23** Page unresponsive when posting comment  

**Severity:** High  
**Issue Type:** Crash  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product  
4. Fill comment form → click **Post Comment**  

**Expected Result:**  
Comment posts normally.  

**Actual Result:**  
Page becomes unresponsive after clicking.  

---

**#24** Page unresponsive on “Forgot Password”  

**Severity:** High  
**Issue Type:** Crash  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs → Sign Up**  
3. Click **Forgot Your Password?**  
4. Enter email → click **Retrieve Password**  

**Expected Result:**  
Password is sent to email.  

**Actual Result:**  
Page becomes unresponsive and no email sent.  

---

**#25** Crash when increasing quantity with pink/green color  

**Severity:** High  
**Issue Type:** Crash  
**Frequency:** Every Time  
**Environment:** All Browsers  

---

**Steps to Reproduce:**  
1. Open [https://academybugs.com](https://academybugs.com)  
2. Go to **Find Bugs**  
3. Open a product with color options  
4. Choose **pink** or **green** color  
5. Increase quantity  

**Expected Result:**  
Quantity increases as expected.  

**Actual Result:**  
Page becomes unresponsive when quantity is increased.  

---
