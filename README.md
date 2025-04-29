# 🚀 iOS Interview Questions and Answers  
**Your Ultimate Cheat Sheet for iOS Developer Interviews**

---

### 👨‍💻 Prepared and Maintained by Keshu Rai a.k.a [RaiTech Labs](https://www.youtube.com/@RaiTechLabs)
**iOS & Android Expert | Educator | Mentor | Creator @ RaiTech Labs**

---

### 📌 About Me

Hi, I’m **Keshu Rai**, a passionate mobile developer. With over **8 years of industry experience** and a growing presence as a mentor and educator, I’ve helped countless developers transition into successful iOS careers.  

I’m also the creator of **[RaiTech Labs](https://www.youtube.com/@RaiTechLabs)** — a YouTube channel where I publish **high-quality tutorials**, **course content**, and **interview prep guides** focused on **Swift**, **SwiftUI**, and **Android** development. My goal is to **simplify complex concepts** and make learning accessible for everyone, whether you're a beginner or looking to land your next senior iOS role.

---

### 📺 Free SwiftUI Crash Course Playlist

Learn SwiftUI from scratch and build real-world apps.  
Click the thumbnail below to start the **free crash course** on YouTube:

[![SwiftUI Crash Course](https://img.youtube.com/vi/UmE5gtlwMc4/0.jpg)](https://www.youtube.com/watch?v=UmE5gtlwMc4&list=PL9TY7jc64Gd4OU7LqA7N_r3O4c79QbR8w)

---

### 🎯 Connect with Me

- 📺 [YouTube: RaiTech Labs](https://www.youtube.com/@RaiTechLabs)
- 💼 [LinkedIn](https://www.linkedin.com/in/keshurai)

> ✨ Don’t forget to **subscribe to RaiTech Labs** on YouTube for in-depth mobile dev content, interview preparation series, and career advice!

## 📘 Swift Language – iOS Interview Questions (Structured)

- What are the key features of the Swift language?
- What is a type-safe language and how does Swift enforce it?
- What is type inference in Swift?
- What is null safety in Swift and how are Optionals used to achieve it?
- What are Optionals in Swift and why are they important?
- What is the difference between Optional Binding and Optional Chaining?
- What makes Enumerations powerful in Swift?
- What is the difference between `let` and `var` in Swift?
- Can a `let` constant reference a mutable object?
- What happens when you declare a reference type using `let`?
- How do you create read-only properties in Swift?
- What is the difference between using `let` and a computed property with only a `get`?
- How do you make a property read-only outside the class but writable inside it?
- How does Swift support both value and reference types?
- What is the difference between a value type and a reference type?
- What is the difference between a class and a struct in Swift?
- What are the practical use cases where a struct is preferred over a class?
- Why does SwiftUI use structs for defining views?
- How is memory management handled in Swift?
- How is memory management different for classes and structs?
- What is Copy-on-Write in Swift?
- How do Array, Dictionary, and String implement Copy-on-Write in Swift?
- What is protocol-oriented programming and how is it different from object-oriented programming?
- How do Generics work in Swift and why are they useful?
- What are collection types in Swift?
- What are the types of access control modifiers available in Swift?
- Which access modifier is the default in Swift?
- What is the difference between `open` and `public` access modifiers?
- What is the difference between `private` and `fileprivate` in Swift?
- How does the `private(set)` access modifier help in encapsulating data while allowing read-only access?
- What are the key differences between stored properties and computed properties in Swift?
- What is the purpose of the `lazy` keyword in Swift, and in which scenarios is it best used?
- How does the `inout` keyword enable pass-by-reference behavior in Swift functions?
- What is the role of the `defer` keyword in Swift, and how is it typically used for resource management?
- How is operator overloading implemented in Swift, and how does it contribute to expressive code?
- What is the process to create a custom operator in Swift, and how do operator types like infix, prefix, and postfix affect its usage?
- How do extensions enhance the functionality of existing types in Swift, and what limitations exist when using them?
- Why are stored properties not allowed inside Swift extensions?
- Why can’t you override methods inside an extension even if the class is subclassed?
- How does Swift promote protocol-oriented programming and what benefits does it offer over traditional object-oriented programming?
- What makes protocol extensions in Swift a powerful tool for writing reusable and modular code?
- How do associated types enable protocols to remain generic while being strongly typed in Swift?
- How does conditional conformance allow Swift types to adopt a protocol only under specific conditions?
- How do generics in Swift contribute to type-safe and reusable code across different data types?
- What are some real-world scenarios where using generics in Swift significantly improves code reusability and maintainability?
- What is a subscript in Swift and how can you create a custom subscript in your type?
- What is `Codable` in Swift and how does it relate to `Encodable` and `Decodable`?
- Is `Codable` a class, struct, or protocol? How is it used in practice?
- How do enumerations work in Swift, and what are associated values in enums?
- How can you use associated values in enums to represent complex state?
- What is the `Result` type in Swift, and how does it use associated values to represent success or failure?
- What are the different types of initializers in Swift?
- What is a convenience initializer, and what conditions must be met to use one?
- What is a failable initializer in Swift, and when should you use it?
- What are higher-order functions in Swift and how do they enable functional programming?
- How does the `map` function work in Swift collections?
- What is the purpose of `compactMap`, and how does it differ from `map`?
- How is `flatMap` used in Swift, and what makes it different from `map` and `compactMap`?
- What is the difference between `map`, `compactMap`, and `flatMap` in Swift?
- How does the `sort` function work in Swift, and how can you use custom sorting logic?
- What is the `reduce` function in Swift and how can it be used to combine elements of a collection?
- What are the main collection types in Swift, and how do they differ?
- How is an `Array` different from a `Set` in Swift?
- Why does `Set` in Swift only store unique values?
- What are the key features and use-cases for `Dictionary` in Swift?
- What is the role of the `Hashable` protocol in Swift, and when should a type conform to it?
- How does `Equatable` enable comparison of values in Swift?
- What is the `Comparable` protocol and how does it help in sorting custom types?
- What are the differences between closures and delegates in Swift, and when should each be used?
- What are Property Wrappers in Swift?
- What are Opaque Types in Swift?
- What are some common keywords in Swift?

- ## 🧩 Design Patterns in Swift


- What is Singleton pattern in Swift?
- Why should Singleton be avoided?
- When should Singleton be used?
- What is Observer pattern in Swift?
- What is Delegate pattern in Swift?
- What is Façade pattern in Swift?
- What is Decorator pattern in Swift?
- What is Adapter pattern in Swift?
- What is Memento pattern in Swift?
- What is Strategy pattern in Swift?
- What is Factory Method pattern in Swift?
- What is Abstract Factory pattern in Swift?
- What is Builder pattern in Swift?
- What is Proxy pattern in Swift?

---

## 🧱 SOLID Principles in Swift

- What is the Single Responsibility Principle?
- What is the Open/Closed Principle?
- What is the Liskov Substitution Principle?
- What is the Interface Segregation Principle?
- What is the Dependency Inversion Principle?

---

## 💉 Dependency Injection in Swift

- What is Dependency Injection?
- What are the types of Dependency Injection?
- Why use Dependency Injection?
- What is Resolver?
- What is SwiftInject?

---

## 🧬 Core Swift Concepts

- What is Composition over Inheritance?
- What is a Pure Function?

---

## 🗃️ Local Data Storage

- What is Core Data?
- What is Realm?
- What is SQLite?
- What are migrations in Core Data?
- How to insert data using background queue in Core Data?
- What is the difference between Core Data and SQLite?
- Is Core Data encrypted?
- What are the delete rules in Core Data?
- What is No Action delete rule?
- What is Nullify delete rule?
- What is Cascade delete rule?
- What is Deny delete rule?
- What are the types of persistent store in Core Data?
- What is XML store type?
- What is Binary store type?
- What is SQLite store type?
- What is In-Memory store type?
- What are the concurrency types in Core Data?
- What is `NSMainQueueConcurrencyType`?
- What is `NSPrivateQueueConcurrencyType`?
- How to pass Managed Object between contexts on different queues?
- What are performance guidelines for Core Data?

---

## 🧬 App Lifecycle

- What is the lifecycle of AppDelegate and SceneDelegate?
- What is the lifecycle of UIViewController?
- What is the lifecycle of UIView?

---

## 🌐 REST API Integration

- What is URLSession in Swift?
- What is URLRequest in Swift?
- What is URLComponents in Swift?
- What are the different HTTP methods?
- What are HTTP response status codes?
- What is OAuth protocol?
- What is caching in iOS apps?
- What is Result type in Swift?
- How do you handle retry calls in API requests?
- How do you check for internet availability in iOS?

---

## ⚙️ GCD and OperationQueue

- What is the difference between GCD and OperationQueue?
- What are the different types of queues in GCD?
- What is the difference between Serial and Concurrent queues?
- What is Quality of Service (QoS) in GCD?
- What is DispatchWorkItem in GCD?
- What is DispatchGroup in GCD?
- What is BlockOperation in OperationQueue?

---

## 🏗️ Architecture Patterns

- What is the MVC architecture pattern in iOS?
- What is the MVVM architecture pattern in iOS?
- What is MVVM-C architecture pattern in iOS?
- What is VIPER/VIP architecture pattern in iOS?
- Which architecture pattern is the best for iOS and why?
- How do you choose an architecture for a project?
- What is Modular Architecture in iOS?
- What is TCA architecture in iOS?
- What is VIPER/VIP and its components?
- How can architecture patterns be used with SOLID principles and dependency injection?

---
## 🧠 Memory Management

- What are Strong, Weak, and Unowned references in Swift?
- When should you use Weak and Unowned references in Swift?
- What are the common ways to prevent memory leaks during development?
- How is the `deinit` method used in Swift?
- How can you find memory leaks, memory allocations, and retain cycles?

---

## 🧑‍💻 Git

- What Git flow have you used in past projects?
- What is the difference between `merge` and `rebase` in Git?
- How do you reset the last commit in Git? How can you change the last commit message?
- What is the `cherry-pick` command in Git used for?
- What is the difference between a hard reset and a soft reset in Git?
- What is Git stash, and how is it used?

---

## 🏃‍♂️ Agile Process

- What Agile process do you follow in your projects?
- How do you plan sprints in Agile?
- How do you estimate stories in Agile?
- What is backlog refinement in Agile?
- What is a Sprint retrospective, and why is it important?
- What is a Sprint review or showcase, and how is it conducted?

---

## 📈 Code Quality Practices

- What code quality checks do you use during the PR process? (e.g., SonarQube, quality gate, unit test coverage, peer code review)
- What are the code review practices or guidelines followed to maintain code quality?

---

## 🔐 Security Mechanisms

- What are the security mechanisms used to make an app secure?
- What is SSL pinning? What is the difference between certificate pinning and public key pinning?
- How can you ensure that SSL pinning is perfectly integrated in an app?
- How do you securely store data in an app? What is the Keychain storage used for?
- How do you implement encryption on the database in an app?
- What are the different encryption algorithms used in app security (e.g., AES, RSA, SHA)?
- How do you check for jailbroken devices?
- What is App Transport Security (ATS), and how does it contribute to app security?
- How can you prevent screenshot capturing within an app?
- How can you avoid exposing confidential information, such as API keys, in a code repository?
- What are the best practices for managing debug logs in production apps?

---

## 🛠️ Managing Different Environments

- How do you manage different environments such as DEV, SIT, UAT, and Production?
- What is the `.xcconfig` file, and how is it used to manage different environments in an app?
- What is the difference between a Scheme and a Target in Xcode?

---

## ⚙️ Dispatch and Swift Performance

- What is dynamic dispatch, and how does it differ from static dispatch?
- What is the `final` keyword in Swift? How does it help improve Swift code performance?
- What are the best practices for writing high-performance Swift code?
- What is the difference between `setNeedsLayout()`, `layoutIfNeeded()`, and `layoutSubviews()` in Auto Layout?

---

## 📐 Auto Layout

- What is Content Hugging Priority and Compression Resistance Priority in Auto Layout?

---

## 🚀 Package Managers

- What are CocoaPods, Swift Package Manager (SPM), and Carthage? What are the differences between them?

---

## 🔔 Push Notifications

- What is the difference between Apple Push Notification Authentication Key (.p8) and Apple Push Notification service SSL certificate (.p12)?

---

## 📱 App Store Mechanism

- What are the different types of provisioning profiles used in iOS development?
- What are the different certificate types used in iOS development?
- How does TestFlight beta testing work, and what is the difference between internal and external testing?



---

## 🧪 Unit Testing with XCTest

- How do you use the XCTest framework for Unit Testing in Swift?
- How do you manage real and mock implementations in API testing?
- What are the different types of assertions used in Unit Testing?
- What is `XCTSkipUnless` used for in Unit Testing?
- How does Dependency Injection help with Unit Testing?
- How do you test asynchronous tasks or real API integration in Swift?
- What is the use case of `tearDown()` and `setup()` methods in testing?
- What is behavior-driven testing, and how do you write behavior-driven tests in iOS?
- What is the Quick and Nimble framework, and how is it used for Unit Testing?
- Is `setUpWithError()` called before each test or only before the first test?
- Is `tearDownWithError()` called after each test?
- What is SnapshotTesting, and which framework is used for it?
- What is code coverage in testing?

---

## 🌀 Functional Reactive Programming – Combine

- What are Publishers and Subscribers in Combine?
- What are the subjects in Combine? How do `PassThroughSubject` and `CurrentValueSubject` work?
- What are transforming operators in Combine, and how do they work?
  - How does `collect` work in Combine?
  - How does `map` work in Combine?
  - How does `flatMap` work in Combine?
  - How does `scan` work in Combine?
- What are filtering operators in Combine, and how do they work?
  - How does `filter` work in Combine?
  - How does `removeDuplicates` work in Combine?
  - How does `compactMap` work in Combine?
  - How does `ignoreOutput` work in Combine?
  - How do `first` and `last` work in Combine?
  - How do `dropFirst` and `drop` work in Combine?
  - How does `prefix` work in Combine?
- What are combining operators in Combine, and how do they work?
  - How does `prepend` work in Combine?
  - How does `append` work in Combine?
  - How does `switchToLatest` work in Combine?
  - How does `merge` work in Combine?
  - How does `combineLatest` work in Combine?
  - How does `zip` work in Combine?
- What are time manipulation operators in Combine, and how do they work?
  - How does `debounce` work in Combine?
  - How does `throttle` work in Combine?
  - How does `timeout` work in Combine?
- How do you debug Combine pipelines?
- How do `share` and `multicast` operators work in Combine?
- What is `Future` in Combine, and how is it used?
- What is backpressure in Combine, and how can it be achieved?
- What is `AnyCancellable` in Combine, and how is it used?

---

## 🖥️ SwiftUI

- What is the difference between `@State` and `@StateObject` in SwiftUI?
- What is `@ObservedObject` and when should it be used in SwiftUI?
- What is `@Published` and how does it work in SwiftUI?
- What is `@Environment` in SwiftUI, and when should it be used?
- What is `@EnvironmentObject` in SwiftUI, and how does it work?
- What is `@AppStorage` in SwiftUI, and how is it useful?
- What is `@Binding` in SwiftUI, and when should it be used?
- If a struct contains a `@Binding` property, how do you create a custom initializer for that struct?
- What is `@FocusedBinding` in SwiftUI, and how is it different from `@Binding`?
- What is `@GestureState` in SwiftUI, and how does it work?
- What is `@UIApplicationDelegateAdaptor` in SwiftUI, and how is it used?
- What are view modifiers in SwiftUI, and how are they applied to views?
- What is the purpose of the `some` keyword in SwiftUI?
- How do you create custom view modifiers in SwiftUI?
- How do you navigate between views in SwiftUI?
- How do you interact with UIKit components in SwiftUI using `UIViewControllerRepresentable` and `UIViewRepresentable`?
- What is `AnyView` in SwiftUI, and when should it be used?
- How can you avoid using `AnyView` in SwiftUI, and what is the benefit of using `@ViewBuilder`?
- What is `@ViewBuilder`, and how is it used to build views in SwiftUI?

---

## 🛠️ Fastlane

- What are the different methods available for authenticating with Apple services using Fastlane?
- What are the roles of `AppFile` and `FastFile` in Fastlane configuration?
- What is Fastlane match, and how is it useful for managing certificates and provisioning profiles?
- What are the different types of lanes available in Fastlane?

---

## 🚀 New Features in Swift

- What is structured concurrency in Swift, and how does it improve async tasks?
- What are async/await, and how do they simplify asynchronous programming in Swift?
- What is `AsyncSequence`, and how is it used in Swift for handling sequences of asynchronous events?
- What are effectful read-only properties, asynchronous properties, and throwing properties in Swift?
- What are `Task` and `TaskGroup` in Swift, and how are they used for concurrent programming?
- What are `Actor` and `GlobalActor`, and how do they help manage concurrency and data safety in Swift?
- What is the purpose of the `@Sendable` attribute, and how does it relate to the `Sendable` protocol in Swift?


---

    MIT License

    Copyright (c) 2025 Raitech Labs
    
    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

