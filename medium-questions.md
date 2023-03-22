# Medium questions
## How would you communicate between two Fragments?
### Answer 
- All Fragment-to-Fragment communication is done either through a shared ViewModel or through the associated Activity. Two Fragments should never communicate directly.
- The recommended way to communicate between fragments is to create a shared ViewModel object. Both fragments can access the ViewModel through their containing Activity. The Fragments can update data within the ViewModel and if the data is exposed using LiveData the new state will be pushed to the other fragment as long as it is observing the LiveData from the ViewModel.
- Another way is to define an interface in your Fragment A, and let your Activity implement that Interface. Now you can call the interface method in your Fragment, and your Activity will receive the event. Now in your activity, you can call your second Fragment to update the textview with the received value.

## What are the permission protection levels in Android?
### Answer
- Normal — A lower-risk permission that gives requesting applications access to isolated application-level features, with minimal risk to other applications, the system, or the user. The system automatically grants this type of permission to a requesting application at installation, without asking for the user’s explicit approval.
- Dangerous — A higher-risk permission. Any dangerous permissions requested by an application may be displayed to the user and require confirmation before proceeding, or some other approach may be taken to avoid the user automatically allowing the use of such facilities.
- Signature — A permission that the system grants only if the requesting application is signed with the same certificate as the application that declared the permission. If the certificates match, the system automatically grants the permission without notifying the user or asking for the user’s explicit approval.
- SignatureOrSystem — A permission that the system grants only to applications that are in the Android system image or that are signed with the same certificate as the application that declared the permission.

## What is the ViewHolder pattern? Why should we use it?
### Answer

- Every time when the adapter calls getView() method, the findViewById() method is also called. This is a very intensive work for the mobile CPU and so affects the performance of the application and the battery consumption increases. ViewHolder is a design pattern which can be applied as a way around repeated use of findViewById().
- A ViewHolder holds the reference to the id of the view resource and calls to the resource will not be required after you "find" them: Thus performance of the application increases.
- View.setTag(Object) allows you to tell the View to hold an arbitrary object. If we use it to hold an instance of our ViewHolder after we do our findViewById(int) calls, then we can use View.getTag() on recycled views to avoid having to make the calls again and again.

## What is the difference between getContext(), getApplicationContext(), getBaseContext(), and this?
### Answer

- View.getContext(): Returns the context the view is currently running in. Usually the currently active Activity.
- Activity.getApplicationContext(): Returns the context for the entire application (the process all the Activities are running inside of). Use this instead of the current Activity context if you need a context tied to the lifecycle of the entire application, not just the current Activity.
- ContextWrapper.getBaseContext(): If you need access to a Context from within another context, you use a ContextWrapper. The Context referred to from inside that ContextWrapper is accessed via getBaseContext().
- this: is refer current class object always. this and getContext()are not always same e.g. in Activity class, you can use this because Activity inherits from Context but method getContext() is not in Activity class.

## What is a frament in Android?

- A fragment has its own layout and behavior with its own life cycle callbacks.
- Fragments can be added or removed in an activity while the activity is running and used in multiple activities.
- Multiple fragments can be combined in a single activity to build a multi-pane UI.
- The fragment life cycle is closely related to the life cycle of its host activity which means when the activity is paused, all the fragments available in the activity will also be stopped

## What is ANR in Android?
- ANR is an abbreviation for Application not responding that describes an unresponsive Android app. an "ANR" event is triggered, When an app is running on an Android device and stops responding.

## What are the Android application components?

There are four main components, which are:

- Activities: They show the UI and handle the interaction of the users in smartphone screen.
- Services: They take care of the processing associated with the application.
- Broadcast Receivers: They handle the communication process between Android OS and application.
- Content Providers: They handle issues with data and database management.

## What options do the users get to save data in Android?

Android provides some options to save or store the app data. Here the choice depends on the specific needs and requirement of space by the users.

- Internal file storage: stores the private file on the device file system.
- External file storage: stores the file on the shared external file system.
- Shared preferences: stores the private primitive data in key-value pairs.
- Databases: stores the structured data in a private database.


