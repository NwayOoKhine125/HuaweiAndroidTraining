# Material Design
An android app demo that showcases the material design components such as buttons and dialog box. There are three activities, `MainActivity.java`, `MaterialButtons.java` and `MaterialDialog.java`. 

## Introduction:
This app includes the following callbacks: `onCreate()`, `onClick()` and some methods of AlertDialogBuilder, [`setTitle()`, `show()`, `setIcon()`, `setMessage()`, `setNeutralButton()`, `setNegativeButton()`, `setPositiveButton()` and `setItems()`].

First of all, you have to add material design library into "build.gradle(:app)" file. </br>
![Insert Library](https://user-images.githubusercontent.com/67506554/103675118-f26b8000-4fad-11eb-8b78-95c7d8c5d307.png) </br></br>
Then, to display the material design components, you have to add material components theme into AndroidManifest.xml</br>
If not, it will only display the android components effect.
![Add Material Themes](https://user-images.githubusercontent.com/67506554/103675021-d7990b80-4fad-11eb-9952-b07fb219477f.png) 

## onClick(View v) 
Called when a view has been clicked.

## show()
Creates an AlertDialog with the arguments supplied to this builder and immediately displays the dialog.

## setTitle()
Set the title displayed in the Dialog.

## setIcon()
Set the resource id of the Drawable to be used in the title.

## setMessage()
Set the message to display.

## setNeutralButton()
Set a listener to be invoked when the neutral button of the dialog is pressed.

## setNegativeButton()
Set a listener to be invoked when the negative button of the dialog is pressed

## setPositiveButton()
Set a listener to be invoked when the positive button of the dialog is pressed.

## setItems()
Set a list of items to be displayed in the dialog as the content, you will be notified of the selected item via the supplied listener.

## DialogInterface.OnClickListener()
Interface used to allow the creator of a dialog to run some code when an item on the dialog is clicked.

About this repo
===

Run this app in Android Studio.

When you look at the actual phone screen, you can see that there are two buttons (Material Buttons,and Material Dialogs).

If you click the "Material Buttons" button, you will see 4 material design buttons and 2 normal buttons. You can switch on/off by clicking the "NORMAL TOGGLEBUTTON OFF".

If you click the "Material Dialogs" button, you will see another 3 buttons which will display the dialog boxes. After you choose and click some buttons from those dialog boxes, the toasts will display what you chose.

You can learn more about material design [here](https://material.io/components)!
