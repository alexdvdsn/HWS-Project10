#  Project 10

Here we are using UICollectionViewController, UIImagePicker, Data and UUID to make a simple app to store people's names and faces. 

### Day 1
Today we built out the UICollectionView with a custom cell. We defined a custom Class called PersonCell and tied the elements from interface builder to it. We then called the class from the main ViewController using the Apple provided CollectionView API calls


### Day 2
Today we configured UIImagePicker to select an image from the camera roll and created a custom NSObject to handle the name and photo URL of the people.

### Challenge
For the challenge I added another UIAlert Controllerler to ask the user to rename or delete a person

changed the picker source type to camera to see what happens (hint, it crashed). To soleve this, I put the sourceType line inside an if statement to check if the UIImagePickerController.isSourceeTypeAvaliable() is true
