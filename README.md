 Password Manager:

This is a simple password manager application created using Python's Tkinter library. It allows users to generate strong passwords, save them along with associated website and email information, and retrieve saved passwords when needed.

 Features:

1. Password Generator:** Automatically generates strong passwords consisting of letters (both lowercase and uppercase), numbers, and symbols.
2. Save Password:** Stores website, email, and password information in a JSON file (`data.json`).
3. Find Password:** Retrieves saved password information for a specific website.

How to Use:

1. Run the application.
2. Enter the website, email, and password information.
3. Use the "Generate Password" button to create a strong password.
4. Click "Add" to save the information.
5. To retrieve a password, enter the website and click "Search".

 Dependencies:

- tkinter (standard Python library)
- JSON (standard Python library)



Notes:

- The generated passwords are not stored anywhere but can be copied from the application interface.
- Ensure the `data.json` file is secure as it contains sensitive information.
- Customize the application further by modifying the UI or adding more features
