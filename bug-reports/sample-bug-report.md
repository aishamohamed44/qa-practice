# Sample Bug Report (Practice)

⚠️ **Practice exercise** - this is a sample bug report I wrote to learn the format. The bug is a known behavior of the demo site [saucedemo.com](https://www.saucedemo.com) when logging in as the `problem_user`.

---

**Bug ID:** BR-01

**Title:** Product images do not load for problem_user on the Products page

**Environment:** Chrome browser, Windows 11, saucedemo.com (demo site)

**Severity:** Medium - the shop still works, but customers cannot see the products

**Steps to reproduce:**
1. Open saucedemo.com
2. Login with username `problem_user` and password `secret_sauce`
3. Look at the products on the Products page

**Actual result:**
All product images show the same wrong placeholder image (a broken/backpack image repeated).

**Expected result:**
Each product shows its own correct image.

**Notes:**
This is a known test bug inside the demo site. I wrote this report only to practice writing clear bug reports: a short title, environment, severity, steps, actual result, and expected result.
