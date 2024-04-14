The notes app is a simple web application built using HTML, CSS, and JavaScript. It allows users to create, edit, and delete notes, with the ability to persist the notes across page refreshes using local storage.

When the page loads, the JavaScript code attaches an event listener to the DOMContentLoaded event to ensure that the code runs only after the HTML content is fully loaded. This event listener calls the showNotes() function, which retrieves the notes from local storage and displays them on the page.

Users can create new notes by clicking on a designated button. When the button is clicked, a new input box is dynamically created and appended to the notes container. Each input box is editable, allowing users to type their notes directly into the box.

Each input box also contains a delete button, represented by an image icon. When users click on the delete button, the corresponding note is removed from the page, and the updated list of notes is saved to local storage using the updateStorage() function.

Additionally, the app allows users to press the Enter key to create new lines within a note, enhancing the editing experience.

Overall, the notes app provides a simple and intuitive interface for users to manage their notes, with the added convenience of data persistence across page reloads.
