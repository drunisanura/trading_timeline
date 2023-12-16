# Total Timeline For Both Api and Frontend
```
1. Authentication Feature = 5 days
2. Point Feature = 10 days
3. Multiple Account Feature = 10 days
4. Promotion Features = 5 days
5. Trading Features = 30 days
6. Showing Fake ui Feature = 10 days
7. Other Feature may or may not be necessary for Future = 20 days
```

# Main topic to discuss with Client.

```
1. What is the main difference between each account eg. Normal account, and Trading account? 
2. What are the main features of trading?
3. What are the specific features of fake ui data?
4. What kind of promotion feature do we want to provide to users?
```

### Authentication API Features (5 days)

1. **User Account Creation:**
    
    - The admin can create new user accounts.
    - This involves providing necessary user details and generating authentication credentials.
2. **User Account Management:**
    
    - The admin possesses the authority to disable user accounts.
    - Disabling an account grants the admin full control over it, restricting user access.


###  Frontend Authentication Features (5 days)


1. **Create User Register Page for Admin:**
    
    - Develop a dedicated page where administrators can register new users.
    - Include form fields for necessary user details and a submission button to send the registration request.
2. **Create Sign-in Page for Both Admin and User:**
    
    - Design a unified sign-in page that accommodates both administrators and regular users.
    - Provide separate input fields for username/email and password.
    - Include a "Sign In" button to initiate the authentication process.
3. **Implement Navigation Condition Based on Sign-in:**
    
    - Upon successful sign-in, implement a condition to determine whether the user is an admin or a regular user.
    - Redirect the user to the appropriate dashboard or landing page based on their role.


### Point API Features (10 days)

1. **User Uploads Transaction Screenshots:**
    
    - Allow users to upload screenshots of their cryptocurrency transactions.
    - Include fields for entering the transaction amount and any additional notes.
2. **Admin Verification and Requirement Fulfillment:**
    
    - Admins should have the ability to review transaction details submitted by users.
    - Admins can manually fulfill the point requirements based on the verified transaction details.
3. **User Management of Withdrawal Addresses:**
    
    - Users can add multiple cryptocurrency addresses for receiving points when withdrawing.
    - Provide a user-friendly interface for users to manage and update their withdrawal addresses.
4. **Admin Transfer to User Crypto Addresses:**
    
    - Admins can transfer points to users by using third-party wallets.
    - The system should prompt admins to check and confirm the withdrawal address provided by the user before proceeding.
5. **Deposit History for Each User:**
    
    - Implement a deposit history feature for each user.
    - Users should be able to view a log of all their deposited points, including transaction details and timestamps.
6. **Withdrawal History for User:**
    
    - Create a withdrawal history section for users.
    - Users should be able to track the history of their point withdrawals, including transaction details and statuses.


###  Point  Frontend Features  (10 days)

1. **Admin Point Management Page:**
    
    - Develop a dedicated point management page for admins.
    - Focus on real-time notifications, and ensure the page refreshes automatically to reflect updates.
2. **User Deposit Page:**
    
    - Create a user-friendly deposit page where users can initiate point deposits.
    - Include fields for uploading transaction screenshots, entering transaction amounts, and providing additional notes.
3. **User to Admin Deposit Page:**
    
    - Implement a page where users can submit point deposits to admins.
    - Include relevant fields for transaction details and any necessary information.
4. **User Management of Withdrawal Addresses:**
    
    - Develop a page where users can manage multiple cryptocurrency withdrawal addresses.
    - Allow users to add, edit, or delete withdrawal addresses.
5. **User Withdrawal Page:**
    
    - Create a withdrawal page for users to request point withdrawals.
    - Include fields for withdrawal amount, transaction details, and any additional information.
6. **Admin Transfer to User Withdrawal Page:**
    
    - Implement a page where admins can process and transfer points to users.
    - Admins should verify withdrawal details before proceeding.
7. **User Deposit History Page:**
    
    - Design a page for users to view their deposit history.
    - Include a log of all deposited points with transaction details and timestamps.
8. **Admin Deposit History Page for Each User:**
    
    - Develop a page for admins to view deposit history for each user.
    - Provide detailed logs of deposited points with timestamps.
9. **User Withdrawal History Page:**
    
    - Create a page where users can track their withdrawal history.
    - Include details such as withdrawal amounts, transaction details, and withdrawal statuses.
10. **Admin Withdrawal History Page for Each User:**
    
    - Design a page for admins to view withdrawal history for each user.
    - Display comprehensive logs of user withdrawals with transaction details and timestamps.





### Multiple Account API Features (10 days)

1. **Create Stable Account Types:**
    
    - Introduce different types of accounts, such as "Spot" or "Trading," to serve distinct purposes.
2. **Top-Up Points for Specific Account:**
    
    - Enable users to add points to a specific account when opening it, ensuring a valid starting balance.
3. **Withdrawal Limits for Each Account:**
    
    - Set specific limits for how many points users can withdraw from each account, maintaining control and security.
4. **Point Transfers Between Accounts:**
    
    - Allow users to transfer points between their regular account and specialized accounts like "Spot," providing flexibility.


### Multiple Account  Frontend Features(10days)

**Days 1-5:**

- Design and implement the Multiple Account Page for Users.

**Days 6-8:**

- Integrate API calls to fetch and display user accounts.
- Develop the logic to calculate and display incentives for opening a spot account.

**Days 9-10:**

- Implement the user interface for top-up functionality, allowing users to fulfill the requested amount for opening a spot account.



### Promotion API features (5 days) 

Create promotion-related detail.
Create some event.

### Promotion Frontend features (5 days) 

- Create admin provided Promotion detail page For the user.
- Create a promotion detail page for admin.
- Create an event create page for Admin.

*(Will discuss more if the Client want to add more feature to this one)*

### Trading Features Both API and frontend (30 days)

- We don’t have enough data to calculate the specific timeline for this feature. 
- We need to have a meeting with the Client to discuss this specific feature.

### For Fake UI feature  Both API and frontend(10 days)

- Showing fake chart for specific Crypto.
- We need to make a meeting with the Client to discuss other specific fake UI feature that the client wants to add)
