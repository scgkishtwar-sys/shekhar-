# shekhar-
​🧮 Multi-Tool: Calculator & Converter App
​A robust, cross-platform utility application built with Flutter. This app features a standard arithmetic calculator with a history tape and a real-time unit converter, all wrapped in a modern, dark-themed UI.
​🚀 Features
​1. Standard Calculator
​Grid Layout: Clean, circular button design similar to iOS.
​Math Logic: Handles complex expressions using the math_expressions parser (PEMDAS supported).
​History Drawer: A slide-out side menu that records past calculations. Tapping a history item recalls the result.
​Error Handling: gracefully handles division by zero and invalid formats.
​2. Unit Converter
​Real-time Conversion: Results update instantly as you type or change units.
​Scalable Architecture: Built on a "Base Unit" logic system, making it easy to add new categories (Weight, Temperature, Currency) without breaking the code.
​User-Friendly: distinct "From" and "To" dropdown menus.
​3. Navigation
​Tabbed Interface: Swipe left/right to switch between tools instantly.
​State Preservation: Inputs are saved when switching between tabs.
​🛠️ Tech Stack
​Framework: Flutter (Dart)
​State Management: setState (Lightweight and efficient for this scale)
​Navigation: DefaultTabController & TabBarView
​Math Engine: math_expressions
