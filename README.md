# ToDoList App
This is a simple ToDoList Android app that allows users to create and manage a list of tasks they want to complete.
## Features
* Add items to the ToDo list
* Strike through completed items

## Screenshot
![test 1](https://user-images.githubusercontent.com/104861566/216049972-77bc258b-5c0c-4522-a5f8-ad774903e2e6.PNG)

## Technologies Used
* Java
* Android Studio
* XML for the layout

## Usage
1. Clone or download the repository
2. Open the project in Android Studio
3. Run the app on an emulator or physical device
4. Type in the task you want to add to the list in the edit text field
5. Click the "Add" button to add the task to the list
6. Tap on a task in the list to strike it through, indicating that it has been completed

## Code Highlight
The App uses onSaveInstanceState and onCreate method to save and restore the state of the timer <br/>
```java
listView.setOnItemClickListener(new AdapterView.OnItemClickListener() {
        @Override
        public void onItemClick(AdapterView<?> adapterView, View view, int i, long l) {
            TextView textView = (TextView) view;
            textView.setPaintFlags(textView.getPaintFlags() | Paint.STRIKE_THRU_TEXT_FLAG);

        }
    });
   ```
This code sets the onItemClickListener for the listView, which allows the user to  <br/>
strike through a task in the list by tapping on it.

## Contribute
If you want to contribute to the project, you can fork the repository, make changes <br/>
and then submit a pull request. I would be happy to review and merge it.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgements
* Hat tip to anyone whose code was used
* Inspiration
* etc

Please let me know if there is anything else you would like me to include.
    
    

