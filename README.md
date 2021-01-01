# Pre-work - To Do App

**To Do App** is an android app that allows building a todo list and basic todo items management functionality including adding new items, editing and deleting an existing item.

Submitted by: **Liulan Zheng**

Time spent: **10** hours spent in total

## User Stories

The following **required** functionality is completed:

* [x] User can **successfully add and remove items** from the todo list
* [x] User can **tap a todo item in the list and bring up an edit screen for the todo item** and then have any changes to the text reflected in the todo list.
* [x] User can **persist todo items** and retrieve them properly on app restart

The following **optional** features are implemented:

* [ ] Persist the todo items [into SQLite](http://guides.codepath.com/android/Persisting-Data-to-the-Device#sqlite) instead of a text file
* [ ] Improve style of the todo items in the list [using a custom adapter](http://guides.codepath.com/android/Using-an-ArrayAdapter-with-ListView)
* [ ] Add support for completion due dates for todo items (and display within listview item)
* [ ] Use a [DialogFragment](http://guides.codepath.com/android/Using-DialogFragment) instead of new Activity for editing items
* [ ] Add support for selecting the priority of each todo item (and display in listview item)
* [ ] Tweak the style improving the UI / UX, play with colors, images or backgrounds

The following **additional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1:** "What are your reactions to the Android app development platform so far? Compare and contrast Android's approach to layouts and user interfaces in past platforms you've used."

**Answer:** 

This is the first Android app development platform that I've used so far. I struggled a lot in the beginning on where to each thing locates. After a couple of hours, I do get somehow familiar with the platform. I like the part we can code and see the design of each activity at the same time.


**Question 2:** "Take a moment to reflect on the `ArrayAdapter` used in your pre-work. How would you describe an adapter in this context and what is its function in Android? Why do you think the adapter is important? Explain the purpose of the `convertView` in the `getView` method of the `ArrayAdapter`." 
**Answer:** 

I think the ArrayAdapter collects all the elements from an array and prepares the data for the usages in user interface widgets such as the ``ListView``. It's important on updating the list in user interface widgets and changing the data object. `getView` method will get the data from `ArrayAdapter`. The`ArrayAdapter` uses the `convertView` as a way of recycling old View objects that are no longer being used. Instead of creating new view each time, it can re-use the old, so it doesn't waste too much memory with many invisible views. Android Studio also have a new data type called `recyclerview`.


## Notes

Describe any challenges encountered while building the app.

- Unable to run emulator with Genymotion because I forgot to disable Windows Subsystem for Linux (WSL)
- Unable to run the app because I used the wrong template for the project
- Had issues with widget layouts
- Spent hours on adding new feature on the to do app 


## License

    Copyright [2021] [Liulan Zheng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
