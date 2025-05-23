[![PyPI Downloads](https://static.pepy.tech/badge/splitexpense)](https://pepy.tech/projects/splitexpense)

# SplitExpense

**SplitExpense** is a lightweight, user-friendly desktop application built with Python's Tkinter library. It simplifies the process of splitting group expenses, making it ideal for roommates, travel groups, or any situation where shared expenses occur. The app allows users to add participants, record expenses, and instantly calculate who owes whom. Additionally, it offers the capability to export detailed and summary reports to Excel for easy sharing and record-keeping.

## ✨ Features

- **Add Participants and Expenses**: Easily input the names of individuals involved and the expenses incurred.
- **Assign Payments and Participants**: Specify who paid for what and who participated in each expense.
- **Calculate Balances**: Automatically compute the net balance for each person, indicating how much they owe or are owed.
- **Export to Excel**: Generate detailed and summary reports in Excel format for transparency and record-keeping.
- **Offline Functionality**: Operates entirely offline, ensuring privacy and accessibility without the need for an internet connection.

## 📦 Installation

Ensure you have Python 3.7 or higher installed. You can install SplitExpense using pip:

```bash
pip install splitexpense
```

Alternatively, to install the latest version directly from the source:

```bash
git clone https://github.com/MuddyHope/split_expense.git
cd split_expense
pip install .
```

## 🚀 Usage

After installation, you can launch the application using the following command:

```bash
python -m splitexpense.app
```

This will open the SplitExpense GUI, where you can start managing your group expenses.

## 📝 Example

Imagine you're on a trip with friends, and various expenses are paid by different individuals. With SplitExpense, you can:

1. Add all participants to the app.
2. Record each expense, specifying the amount, payer, and participants involved.
3. View the calculated balances to see who owes whom.
4. Export the report to Excel for sharing with the group.

## 📁 Project Structure

```
split_expense/
├── splitexpense/
│   ├── app.py           # Main application file with the Tkinter GUI
│   ├── __init__.py      # Package initializer
├── setup.py             # Setup script for packaging
├── pyproject.toml       # Project metadata and dependencies
├── README.md            # Project README
├── LICENSE              # License file
```

## 🤝 Contributing

Contributions are welcome! If you'd like to improve SplitExpense, please fork the repository and submit a pull request. For major changes, open an issue first to discuss what you'd like to change.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 📬 Contact

For questions or suggestions, feel free to open an issue on the [GitHub repository](https://github.com/MuddyHope/split_expense).
