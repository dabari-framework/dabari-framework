# dabari-framework
dabari is a framework raging from gui library to network for building crossplatform application.


Platforms supported by now : windows , android 

simple usage :
           
	   // create the application that will start the event loop and hold all windows
	   App myapp;

	   // create one window with default params
	   Window* win = Window::New() ;

	   // add it to the application
	   myapp.AddWindow(win);

	   // build a widget from xml file
	   Widget* widget = win->GetBuilder()->BuildFile("assets/main.xml");

	   // add it to the root widget of the window
	   win->GetRootWidget()->AddWidget(widget);

   	   // start event loop 
   	   myapp.Run();



Demo :

  Simple texteditor :
  
  Load Image from the web and show it :


How to build and advanced usage : https://github.com/dabari-framework/dabari-framework/wiki for documentation. 

