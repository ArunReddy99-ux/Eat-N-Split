# Split The Bill App 🧾💸
This is a React-based bill-splitting application that allows you to manage shared expenses with friends. You can add friends, select a friend, and split bills seamlessly with a user-friendly interface.

# Features 🚀
# Add Friends:

Add new friends to the list with their name and image URL.
Friends are displayed with their balance status (who owes whom).
# Split Bills:

Select a friend and split the bill based on how much each person paid.
Automatically updates the balance based on the input.
# Balance Tracking:

See whether you owe a friend, they owe you, or if the balance is even.
# Dynamic Friend List:

Friends are displayed in an organized list.
Selecting a friend opens the split-bill form.
# Technologies Used 🛠️
React: Core library for building the UI.
JavaScript (ES6): For handling state and logic.
CSS: Basic styling for components.
Crypto API: Generates unique IDs for new friends.
# Components 🧩
App: Parent component managing the entire app state.
Button: Reusable button component.
FriendsList: Displays a list of friends.
Friend: Represents a single friend's details.
FormAddFriend: Form to add a new friend with name and image.
FormSplitBill: Form to split the bill between you and a friend.
# How to Use 📋
# Add a Friend:

Click the "Add Friend" button.
Enter the friend's name and an optional image URL.
# Split a Bill:

Click "Select" next to a friend's name.
Enter the bill amount, your expense, and choose who paid the bill.
Submit to update the balance.
# Track Balances:
The app displays messages like:
"You owe Sarah 20$" (when you owe a friend).
"Sarah owes you 10$" (when the friend owes you).
"You and Anthony are even".

# Enjoy splitting bills effortlessly! 😊
