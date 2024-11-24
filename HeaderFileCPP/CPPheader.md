# Standard C++ Header Files

## **Input and Output**
- `<iostream>` – For input/output streams (e.g., `std::cin`, `std::cout`, `std::cerr`).
- `<fstream>` – For file stream input/output (e.g., `std::ifstream`, `std::ofstream`).
- `<sstream>` – For string stream input/output (e.g., `std::stringstream`).
- `<cstdio>` – C-style input/output (e.g., `printf`, `scanf`, `fopen`).

## **Containers**
- `<vector>` – For `std::vector`, a dynamic array.
- `<list>` – For `std::list`, a doubly linked list.
- `<deque>` – For `std::deque`, a double-ended queue.
- `<array>` – For `std::array`, a fixed-size array.
- `<stack>` – For `std::stack`, a stack container.
- `<queue>` – For `std::queue`, a queue container.
- `<set>` – For `std::set`, a collection of unique elements.
- `<map>` – For `std::map`, a collection of key-value pairs.
- `<unordered_set>` – For `std::unordered_set`, an unordered collection of unique elements.
- `<unordered_map>` – For `std::unordered_map`, an unordered collection of key-value pairs.

## **Algorithms**
- `<algorithm>` – For algorithms like `sort`, `find`, `reverse`, `binary_search`, etc.
- `<functional>` – For function objects, function pointers, and higher-order functions (e.g., `std::function`, `std::bind`).
- `<numeric>` – For numeric algorithms (e.g., `std::accumulate`, `std::iota`).

## **Utility**
- `<utility>` – For utility functions and classes (e.g., `std::pair`, `std::move`, `std::swap`).
- `<tuple>` – For the `std::tuple` class template.
- `<type_traits>` – For compile-time type checks (e.g., `std::is_integral`, `std::is_same`).
- `<chrono>` – For time utilities and duration types (e.g., `std::chrono::system_clock`, `std::chrono::duration`).
- `<initializer_list>` – For working with initializer lists.
- `<bitset>` – For `std::bitset`, a container for representing a fixed-size sequence of bits.

## **Memory Management**
- `<memory>` – For smart pointers and memory management (e.g., `std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`).
- `<new>` – For dynamic memory allocation (e.g., `new`, `delete`, `std::nothrow`).

## **Concurrency and Multithreading**
- `<thread>` – For managing threads (e.g., `std::thread`).
- `<mutex>` – For synchronization primitives (e.g., `std::mutex`, `std::lock_guard`).
- `<condition_variable>` – For condition variables.
- `<future>` – For asynchronous tasks (e.g., `std::future`, `std::promise`).
- `<atomic>` – For atomic operations (e.g., `std::atomic`).

## **Exception Handling**
- `<stdexcept>` – For standard exception classes (e.g., `std::exception`, `std::out_of_range`, `std::logic_error`).
- `<exception>` – For base exception classes and `std::terminate`.

## **Type Information**
- `<typeinfo>` – For type identification and runtime type information (e.g., `typeid`, `std::type_info`).

## **String Handling**
- `<string>` – For the `std::string` class and string manipulation.
- `<cstring>` – C-style string functions (e.g., `strlen`, `strcmp`, `strcpy`).
- `<cwchar>` – C-style wide character string functions (e.g., `wcslen`, `wcscpy`).
- `<codecvt>` – For handling character conversions (e.g., `std::wstring_convert`).

## **Math**
- `<cmath>` – For mathematical functions (e.g., `sin`, `cos`, `sqrt`, `pow`).
- `<cctype>` – For character classification and manipulation functions (e.g., `isalpha`, `isdigit`).
- `<limits>` – For numerical limits (e.g., `std::numeric_limits`).
- `<random>` – For random number generation.
- `<complex>` – For complex number operations.

## **Time and Date**
- `<ctime>` – For C-style time functions (e.g., `time`, `localtime`, `strftime`).
- `<chrono>` – C++11 library for time and duration (e.g., `std::chrono::system_clock`).

## **C++ Standard Library Extensions**
- `<regex>` – For regular expression matching and manipulation.
- `<filesystem>` – For file system manipulation (e.g., `std::filesystem::path`, `std::filesystem::directory_iterator`).
- `<locale>` – For locale-specific behavior (e.g., `std::locale`, `std::toupper`).

## **Compiler-Specific/Additional Headers**
- `<cassert>` – For diagnostic/assertion macros (e.g., `assert`).
- `<cstdarg>` – For handling variable arguments (e.g., `va_list`, `va_start`, `va_end`).
- `<cstdlib>` – For C-style utility functions (e.g., `malloc`, `free`, `exit`).
- `<cstdio>` – For C-style file handling functions (e.g., `fopen`, `fclose`).
