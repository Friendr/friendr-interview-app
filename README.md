# Friendr iOS interview

Following are a two part test.
Part one consists of a set questions.

Part two is a coding challenge where you are supposed to solve a given problem.

## Part one

1) Explain some differences between a modal and push navigation.
2) When is it preferred to use `Keychain Services`, `UserDefaults` or `Core Data`? Please explain some different scenarios or use cases.
3) Given the following function inside a `UIViewController`, what can go wrong here?:
```swift
func fetchData() {
    service.fetchFromAPI { result in
        self.data = result
    }
}
```
4) Give a brief explanation of protocol oriented programming.

## Part two

Please create a iOS application that presents the number of times the word `banana` is mentioned in this Wikipedia article: https://en.wikipedia.org/wiki/Banana.

* The search should be **case sensitive**.
* It should not count HTML, such as class names, id's and so on. Only user facing text.
* You can target which ever iOS version you want. Use `UIKit` or `SwiftUI`.
* Its positive if you can display understanding in some chosen architecture. Ie. `MVVM`, `VIP` or `MVC`.
* Do **not use** any third party dependency, like a networking library. Stick to Apple's libraries.
* Display usage of `git` and clean commits.

## Deliveries

Both part one and part two should be submitted in a single Github repo.
Part one can be in a `.md` file.

If you like, the repo can be private with read access to Github user `tskippervold`.
