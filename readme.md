<table>
  <tr>
    <td>     
<img src="https://raw.githubusercontent.com/ncudemo/web-test-20230923/main/hw1.png">
</td>
<td style="width:300px">

```swift
  import SwiftUI
  struct ContentView: View {
      var body: some View {
          Text("Hello, SwiftUI")
              .fontWeight(.bold)
              .font(.title)
              .padding()
          Image(systemName: "beach.umbrella.fill")
              .font(.system(size:100))
              .foregroundColor(.green)
              .shadow(color: .red, radius: 5, x: 10, y: 10)
          // SF Symbol
          Image("mobiledevtw")
              .resizable()
              .scaledToFit()
      }
  }

```
</td></tr>
</table>




