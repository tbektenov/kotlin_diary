**Digital Diary Mobile Application**

**Project Goal:**
The Digital Diary mobile application allows users to create and store personalized entries that can include text notes, photos, and voice recordings.

**Functional Requirements:**

- **Creating Entries:** Users can create entries that include text notes with a location marker based on GPS, automatically adding the town name where the note was made. Each note can also include a photo and a voice recording made at the time of the note's creation.
  
- **Editing Entries:** Users can edit any entry after its creation.

- **Data Storage:** All entries are stored locally in an SQLite database on the user's device.

- **Adding Captions to Photos:** Users can add a textual description directly on the photo before saving it in the entry.

- **Browsing Entries:** Users can view all entries within the application.

- **Securing the Diary:** To access the diary's content, users must enter a password or PIN when launching the application.

**Technical Requirements:**

- **Design Pattern:** The project should implement the MVVM or MVI design pattern.
  
- **Resource Management:** All literals should be placed in resource files (res/values) to support easy translation into other languages.

- **Sample Data:** A set of sample data should be loaded each time the application is launched to demonstrate all functionalities. This sample data should be embedded directly in the application code.
