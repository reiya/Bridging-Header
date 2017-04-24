Bridging-Header
============

## Installation with CocoaPods

```bash
$ gem install cocoapods
```
#### Podfile

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'

target 'TargetName' do
 pod "Bridging-Header"
end
```

## Usage

```objective-c
   override func viewDidLoad() {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
        BHOCallSwift.callSwift()
    }
```

## License

Bridging-Header is released under the MIT license. See LICENSE for details.