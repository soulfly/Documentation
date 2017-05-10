This sample shows you how to work with Users API, **Custom Objects API** and **Content API** by Quickblox JavaScript SDK.
It allows you to create any server side data structure, authorize and work with files as uploading.

Below is the sample you'll create using this tutorial, sources files you can found in [Github](https://github.com/QuickBlox/quickblox-javascript-sdk/tree/gh-pages/samples) or inspect detailed on [Github Pages](https://quickblox.github.io/quickblox-javascript-sdk/samples/data).

<!--- TODO: change to src DATA sample insted of chat --->
<!--<iframe src="https://samples.quickblox.com/web/data" width="100%" height="550px" frameborder="1" scrolling="no">-->

# Try it yourself
Before all, adding a Custom Data structure to your application.

<div class="panel panel-warning">
  <div class="panel-body">
     Note: This guide based on <a href="https://quickblox.com/developers/Custom_Objects" target="_blank">Custom Objects REST API documentation</a>. It is very helpful, describes the full list of QuickBlox Custom Objects API features and need to be read in addition to reading this guide.
  </div>
</div>

To start using the Custom Objects module you should create your data scheme. Go to [admin.quickblox.com](https://admin.quickblox.com/), find the Custom Objects module page and press the Add new class button. The 'add new class' popup will then appear.

![Create a new class](./resources/create_class_popup.png)

Enter Class name, add fields any you want. Allow 7 types of fields:
* Integer;
* Float;
* Boolean;
* String;
* File;
* Location;
* Array (of Integers, Floats, Booleans, Strings);

<div class="panel panel-info">
  <div class="panel-body">
     Important:
     There are some predefined fields, that are described in this <a href="http://quickblox.com/developers/Custom_Objects#Module_description" target="_blank">Custom Objects REST API Module description</a> documentation.
  </div>
</div>


