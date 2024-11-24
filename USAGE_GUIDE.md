# Usage Guide for Role-Based Access Control (RBAC) UI

This guide provides step-by-step instructions on how to use the Role-Based Access Control (RBAC) User Interface effectively. Follow these steps to log in, add roles, and assign permissions.

## Step 1: Logging In

1. **Access the Application:**
   - Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) (or the appropriate URL if deployed).

2. **Log In as Admin:**
   - Click the **Login as Admin** button on the main page.
   - This will grant you access to the admin dashboard where you can manage users, roles, and permissions.

## Step 2: Adding Roles

1. **Navigate to the Role Management Page:**
   - Click on the **Role Management** link in the sidebar of the admin dashboard.

2. **Add a New Role:**
   - In the Role Management section, you will see a form to add a new role.
   - Fill in the **Role Name** and **Description** fields.
   - Specify the **Permissions** for the role (comma-separated if multiple).
   - Click the **Add Role** button to save the new role.

3. **Edit Existing Roles:**
   - To edit an existing role, click the **Edit** button next to the role you want to modify.
   - Update the role details and click the **Update Role** button to save changes.

4. **Delete a Role:**
   - To delete a role, click the **Delete** button next to the role. Confirm the deletion in the modal that appears.

## Step 3: Assigning Permissions to Roles

1. **Navigate to the Role Management Page:**
   - Ensure you are still in the Role Management section.

2. **Assign Permissions:**
   - When adding or editing a role, you can specify permissions in the **Permissions** field.
   - Enter the permissions you want to assign to the role, separated by commas (e.g., `Read, Write, Delete`).

3. **Save Changes:**
   - After adding or editing the role with the desired permissions, click the **Add Role** or **Update Role** button to save your changes.

## Step 4: Assigning Roles to Users

1. **Navigate to the User Management Page:**
   - Click on the **User Management** link in the sidebar.

2. **Add a New User:**
   - In the User Management section, fill in the user details, including **Name**, **Email**, and **Status**.
   - Select the role you want to assign to the user from the **Role** dropdown menu.
   - Click the **Add User** button to save the new user.

3. **Edit Existing Users:**
   - To edit an existing user, click the **Edit** button next to the user you want to modify.
   - Update the user details and select a new role if necessary.
   - Click the **Update User** button to save changes.

4. **Delete a User:**
   - To delete a user, click the **Delete** button next to the user. Confirm the deletion in the modal that appears.

## Conclusion

By following these steps, you can effectively manage roles and permissions within the RBAC UI. Ensure that roles are created before assigning them to users, and always validate the permissions assigned to each role for proper access control.

If you have any questions or need further assistance, please refer to the main README file or contact the project maintainer.