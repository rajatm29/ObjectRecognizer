# Real Time Object Recognition Using Swift, iOS 11.2, and CoreML


Download Resnet50 or SqueezeNet [Here](https://developer.apple.com/machine-learning/)

Resnet50 - larger model and more accurate results

SqueezeNet - smaller model, less accurate results, serves as proof of concept

Accessing the model:
```Swift

guard let model = try? VNCoreMLModel(for: Resnet50().model) else { return }

```

You can update between Resnet50 and SqueezeNet
