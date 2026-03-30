#include <iostream>
using namespace std;

int main() {
    int choice;

    // واجهة ترحيبية مرتبة
    cout << "============================================" << endl;
    cout << "   BUSINESS MANAGEMENT INFORMATION SYSTEM   " << endl;
    cout << "============================================" << endl;
    
    cout << "Select an option to view details:" << endl;
    cout << "1. Definition of Management" << endl;
    cout << "2. Management Departments" << endl;
    cout << "3. Management Functions" << endl;
    cout << "4. Exit" << endl;
    cout << "--------------------------------------------" << endl;
    cout << "Enter your choice (1-4): ";
    cin >> choice;

    cout << "\n--- Result ---" << endl;

    // استخدام Switch Case يجعل الكود احترافياً جداً
    switch(choice) {
        case 1:
            cout << "Definition: Organizing and planning company work to achieve success." << endl;
            break;
        case 2:
            cout << "Departments:\n\t- Financial Management\n\t- Human Resources (HR)\n\t- Marketing" << endl;
            break;
        case 3:
            cout << "Functions:\n\tPlanning - Organizing - Directing - Controlling" << endl;
            break;
        case 4:
            cout << "Exiting program... Goodbye!" << endl;
            break;
        default:
            cout << "Invalid choice! Please run the program again." << endl;
    }

    cout << "--------------------------------------------" << endl;
    return 0;
}
