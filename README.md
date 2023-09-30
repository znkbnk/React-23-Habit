Step 1: Identify where to add the textarea

Determine where in your project you want 
to add the textarea. In this case, add it
in the HabitForm component, possibly
under the existing form fields.

Step 2: Update the State

Modify the state of your component to
include a notes field. This field will
hold the text entered by the user
in the textarea.

Step 3: Create a Textarea Element

Add a textarea element to your component's JSX.
You can use the HTML <textarea> tag and bind
its value attribute to the notes field in
your component's state.

Step 4: Style the Textarea

Apply CSS styles to the textarea to control
its appearance, such as setting a maximum
width and height, preventing resizing,
and centering it within its container.

Step 5: Handle Textarea Value Changes

Implement a function to handle changes to
the textarea's value. You can use the 
onChange event to capture user input and
update the notes field in your component's state.

Step 6: Include Notes in Form Submission

Ensure that the notes field is included in the
data you send when the form is submitted.
Modify your addHabit function or form submission
logic to include the notes field in the habit data.

Step 7: Display Notes in Habit List

Modify the HabitList component to display
the notes for each habit. You can include
a paragraph element below the goal achievement
message to display the notes if they
exist for a habit.

