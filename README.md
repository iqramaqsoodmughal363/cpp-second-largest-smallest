# 🥈 Find Second Largest & Second Smallest in Array

> A C++ program that finds the second largest and second smallest elements in a user-defined integer array using a descending sort approach with nested loops.

---

## 📋 Overview

This program sorts the array in descending order and then extracts:
- **Second Largest:** The element at index `1` (`A[1]`).
- **Second Smallest:** The element at index `n-2` (second last position).

**Note on Duplicates:** If the array contains duplicate values, the program will return the duplicate value as the "second" element. For strictly unique second largest/smallest, duplicate skipping logic is required.

---

## 🧮 Program Logic & Execution Flow

1. The user enters the size of the array and its elements.
2. Nested `for` loops implement a descending order bubble/selection sort:
   - If `A[i] < A[j]`, the elements are swapped.
3. After sorting, the array is in descending order.
4. The program outputs:
   - `A[1]` as the second largest element.
   - `A[n-2]` as the second smallest element.

---

## 💻 Sample Input / Output

**Input (No Duplicates):**
Enter size of array : 5
Enter elements of array : 10 25 3 18 7


**Output:**
Second largest number : 18
Second smallest number : 7


**Input (With Duplicates):**
Enter size of array : 4
Enter elements of array : 5 5 3 2


**Output:**
Second largest number : 5
Second smallest number : 3


---

## 🛠️ How to Compile and Run (Windows & Linux)

Follow the instructions below based on your operating system.

### 🪟 For Windows Users (Using MinGW/G++ or any C++ compiler)
| Step | Command |
| :---: | :--- |
| **1. Compile** | `g++ second_min_max.cpp -o second_min_max.exe` |
| **2. Run** | `second_min_max.exe` |

> **Note:** If `g++` is not recognized, make sure MinGW is installed and added to your System PATH.

---

### 🐧 For Linux / macOS Users (Terminal)
| Step | Command |
| :---: | :--- |
| **1. Compile** | `g++ second_min_max.cpp -o second_min_max` |
| **2. Run** | `./second_min_max` |

> **Prerequisite:** Ensure GCC/G++ is installed on your system. (On Linux: `sudo apt install g++` | On macOS: `xcode-select --install`)

---

## 📂 Project Structure
cpp-second-largest-smallest/
│
├── second_min_max.cpp # Main source code file
└── README.md # Project documentation (this file)


---

## 👩‍💻 Author

**Iqra Maqsood Mughal**  
*C++ Developer | Programming Enthusiast*

---

## 📅 Date

**August 2, 2026**

---

## 📄 License

This project is open-source and intended for educational purposes.
