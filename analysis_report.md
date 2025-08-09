#include <algorithm>
#include <array>
#include <iostream>

int main() {
    std::array<int, 4> arr{5, 2, 9, 1};

    std::sort(arr.begin(), arr.end());

    for (int x : arr) std::cout << x << ' ';
    std::cout << '\n';
}