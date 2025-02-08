# 📚 Personal Library Manager

A simple Python program that helps users manage their personal book collection by adding owned books, maintaining a wishlist, tracking acquired books, and handling donations.

# 🚀 Features

Add books to your personal library.

Maintain a wishlist of books you want to own in the future.

Move books from your wishlist to your library when acquired.

Remove donated books from your library.


# 🛠 Installation

1. Ensure you have Python 3.x installed on your system.


2. Clone the repository or download the script:

git clone https://github.com/MohamedGamal1773/Personal-Library-Manager.git
cd Personal-Library-Man


3. Run the script:

python library_manager.py


# 📌 Usage

1. Enter the names of books you currently own.


2. Add books you wish to own in the future.


3. Move acquired books from your wishlist to your library.


4. Remove books from your library when donating them.

# 📷 Demo

Enter the name of book you own:
> The Alchemist  
Enter the name of another book you own (or press 'Enter' to skip)  
> Atomic Habits  

Your Library: ['The Alchemist', 'Atomic Habits']  

Enter the name of a book you wish to have in the future:  
> Deep Work  
Enter the name of another book you wish to have (or press 'Enter' to skip)  
> The Power of Habit  

Your Wishlist: ['Deep Work', 'The Power of Habit']  

Enter the name of a book from your wishlist that you’ve already acquired (or press 'Enter' to skip)  
> Deep Work  

Updated Library: ['The Alchemist', 'Atomic Habits', 'Deep Work']  
Updated Wishlist: ['The Power of Habit']  

Enter the name of a book from your Library you wish to donate (or press 'Enter' to skip)  
> The Alchemist  

Final Library after donation: ['Atomic Habits', 'Deep Work']
# 🔥 Future Enhancements

Allow users to save and load their library/wishlist from a file.

Implement a graphical user interface (GUI).

Add search functionality.


🏆 Author

Mohamed Gamal - https://github.com/MohamedGamal1773
