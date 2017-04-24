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

## Complete
<p align="center" >
  <img src="https://github.com/reiya/Bridging-Header/blob/1.0.0/Pod/Assets/complete.png" alt="Bridging-Header" title="Bridging-Header">
</p>

## License

Bridging-Header is released under the MIT license. See LICENSE for details.