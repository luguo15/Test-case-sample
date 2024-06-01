# Test-case-sample
**Test cases for shopping carts**

QA: Lu Guo


**1. Function testing**

(1) Adding items:
Test adding a single item to the cart, the shopping cart displays the item correctly.
Test adding the same item multiple times on the produce display page, then check the number of items correct in the shopping cart.
Test adding multiple items to the chart, all the items are in the shopping cart.
Test adding the same item with different features (like size, color, etc.), all the items and features are correct in the shopping cart.
All the added items should display correctly in carts, and the number of Cart Total is right.

(2) Removing items:
Test removing a single item from the cart.
Test removing multiple items from the cart.
Test removing all the items from the cart.
The removed items will not show in the cart, and the number of the Cart Total will decrease the number of removed items.

(3) Updating quantities
Test adding the quantity of an item in the cart.
Test decreasing the quantity of an item in the cart.
Test decreasing the quantity to 0 of an item in the cart (remove the item).
The Cart Total number should change when updating quantities.

(4) Moving to the Wishlist or adding from the Wishlist
Test moving an item to the Wishlist, then the item should not display in the cart and should display in the Wishlist.
Test adding items from the Wishlist, then the item should display in the cart and should not display in the Wishlist.
The Cart Total number should change when moving items to the Wishlist or adding items from the Wishlist.

(5) Items in the cart
Test that the pictures and item names are correctly displayed.
Test the pictures and item names are clickable, users can click the picture or item name on the item introduction page.

(6) Order Summary
Test all the information is right in the order summary section

(7) Check out
Test the items can check out and pay from the cart.
After checking out, the bought items are removed from the cart.

(8) Persistence
Test adding items to the cart, then close the application, and reopen the application. The items in the cart are the same.

(9) Boundary value testing:
Test the maximum quantity of a single item that can be added to carts. When the quantity is equal to the total quantity in stock, the user can't add more, and the page should send a friendly notice.
When the total number of items in the cart is equal to the maximum limit, the user can't add any item to the cart, and the page should send a friendly notice.

**2. Abnormal testing**

When an item is out of stock, the user can't add this item to the cart, and the page should send a friendly notice.

Test adding items to the cart in a weak network environment, the item should be added to the cart with more time, or can't be added to the cart.
Test adding items to the cart in an offline environment. The item can't be added to the cart.

**3. API testing**

Test the logs are uploaded correctly when adding or removing items from the cart, or updating quantity.

**4. Load testing**

Test a large number of visits to the carts simultaneously for an extended period.

**5. Automation testing**

Write automation testing cases.

**6. Safety testing**

Test no illegal or discriminatory information is displayed on the cart page.

**7. Compatibility testing**

Test the cart can be displayed and used correctly across different versions of phones, systems, or browsers.

**8. Aging-friendly testing**

Testing the UI is correct when the cart is displayed on a phone that sets extra large font.

![image](https://github.com/luguo15/Test-case-sample/assets/112709254/f698aceb-cef8-485f-ae35-d69c4d453158)
