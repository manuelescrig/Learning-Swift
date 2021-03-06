# Swift Snippets 
Swift Snippets - A collection of Swift language snippets.

## Introduction
The purpose of this repository is to collect the most typical Swift code snippets for learning purposes.

## Code Snippets

#### Logging

```swift
func log(message: String,
    function: String = #function,
    file: String = #file,
    line: Int = #line) {
        
    print("Message \"\(message)\" (File: \(file), Function: \(function), Line: \(line))")
}
    
log("Some message")
```

#### Literals

###### String

###### Array

###### Dictionary


#### Collection Types

###### Sum a list of numbers
```swift
(1...1024).reduce(0,combine: +)
```

###### Verify if Exists in a String
```swift
let words = ["Swift","iOS","cocoa","OSX","tvOS"]
let tweet = "This is an example tweet larking about Swift"
let valid = words.contains(tweet.containsString)
valid //true
```

#### Device
###### Mdoel
```swift
let version = UIDevice.currentDevice().model
```

###### System Name
```swift
let version = UIDevice.currentDevice().systemName
```

###### iOS Version
```swift
let version = UIDevice.currentDevice().systemVersion
```

## Collaborating
Please open an issue if you seen any errors, mistakes or ideas for improvements.

Pull requests are always welcome.

## License

(The MIT License)

Copyright (c) 2016 Manuel Escrig Ventura [@manuelescrig](https://www.twitter.com/manuelescrig)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
