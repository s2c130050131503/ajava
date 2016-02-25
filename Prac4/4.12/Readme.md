
4.12 Time Updater in Servlet
----------------------------
In this program we are going to make one program on servlet which will keep on updating the time in every second and the result will be displayed to you.
To make this servlet firstly we need to make a class named TimeUpdater.  The name of the class should be such that it becomes easy to understand what the program is going to do. Call the method getWriter() method of the response object which will return a PrintWriter object. Use the method getHeader() of the response object to add a new header. We can also use setHeader() in place of getHeader(). The setHeader() method overrides the previous set header. Now by using the PrintWriter object display the result on the browser.


![1](https://cloud.githubusercontent.com/assets/16960997/13324019/f82ec5b2-dc01-11e5-97d9-5a7567d2d2f3.PNG)
![2](https://cloud.githubusercontent.com/assets/16960997/13324020/f82f147c-dc01-11e5-8aed-e799ef2c84e4.PNG)