# webLab3
Web programming lab work made at ITMO University by Artem Bakin and Dmitry Kupershtein.

| Start page | Main page |
| ---------- | --------- |
|![Start page](https://user-images.githubusercontent.com/38016689/105333342-ab54d000-5be6-11eb-863d-9e104f823198.png)| ![Main page](https://user-images.githubusercontent.com/38016689/105333413-c0316380-5be6-11eb-93fd-02086f32c0d7.png)|

## Task
Develop a web application based on servlets and JSFs that determines whether a point on a coordinate plane falls into a
given area. The application should contain a start page with a client datetime and a main page. User can enter point's coordinates by using form input fields or by
clicking with a mouse on the graph. The radius of the figure can be set by drop-down list.

This area has a variable radius R.

| Var | Type | Valid values      | Input         |
| --- | ---- | ----------------- | ------------- |
| X   |int   |[-3,5]             | commandButton |
| Y   |float |(-5,5)             | inputText     |
| R   |float |{1, 1.5, 2, 2.5, 3}| selectOneMenu |

## Harmonograph
You can see strange blinking figures on the start page. They are generated by harmonograph [js version](https://github.com/Afomin01/webLab3/blob/master/src/main/webapp/resources/js/Harmonograph.js). If you are interested in what is this, welcome to our [Java](https://github.com/Afomin01/Digital_Harmonograph) and [C++](https://github.com/Afomin01/Harmonograph) harmonograph implementations.

## Server time
To fill the start page, we added server time, which is requested once by the HEAD http method.

## Denial of responsibility
Some of our technical solutions were dictated by the task, so we had no opportunity to improve them.
