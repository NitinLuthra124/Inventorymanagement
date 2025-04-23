# Inventorymanagement
# Practice question
def show_menu():
    print("\n--- Inventory Menu ---")
    print("1. Add Item")
    print("2. Remove Item")
    print("3. Update Item")
    print("4. View Inventory")
    print("5. Exit")

def main():
    inventory = {}

    while True:
        show_menu()
        choice = input("Enter your choice: ")

        if choice == "1":
            # Add item
            pass
        elif choice == "2":
            # Remove item
            pass
        elif choice == "3":
            # Update item
            pass
        elif choice == "4":
            # View inventory
            pass
        elif choice == "5":
            print("Exiting program...")
            break
        else:
            print("Invalid choice. Please try again.")

if __name__ == "__main__":
    main()
