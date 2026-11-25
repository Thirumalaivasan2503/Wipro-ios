import SwiftUI

struct ContentView: View {
    @State private var name = ""

    var body: some View {
        VStack(spacing: 20) {
            TextField("Enter your name", text: $name)
                .textFieldStyle(.roundedBorder)
                .padding()

            Text("Welcome \(name)")
                .font(.title)
        }
        .padding()
    }
}
