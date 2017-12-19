# dabari-framework
dabari is a framework raging from gui library to network for building crossplatform application.


Platform supported by now : windows , android 

simple usage :
           
	   // create application which will start event loop and hold all windows
	   App myapp;

	   // create on window with default params
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




