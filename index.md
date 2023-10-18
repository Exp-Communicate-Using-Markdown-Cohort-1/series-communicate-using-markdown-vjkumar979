# I'm making a header
I made these changes to the index.md file

![Image of Change](https://online.up.ac.za/wp-content/uploads/2021/11/UP-Change-Job-1500x630.jpg)

```
struct ContentView: View {
    @State private var name = ""

    var body: some View {
        TextField("Enter your name:", text: $name)
            .textFieldStyle(.roundedBorder)
            .onChange(of: name) { newValue in
                print("Name changed to \(name)!")
            }
    }
}
```



- [x] Add headers
- [x] Add an image
- [x] Add a code example
- [x] Make a task list
- [ ] Merge your pull request
- [ ] Finish
