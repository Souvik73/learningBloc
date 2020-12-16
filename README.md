# learningBloc
BLoC is an abbreviation for Business Logic Component, it is helpful to implement everything in the app as stream of events. It is generally Platform Independent and all about Input and Output(Sink and Stream). It is really helpful while handling APIs. 

To understand BLoC we need to Understand the following four things-

  1.State is the information that can be read synchronously when the widget is built and might change during the lifetime of the widget.
  1.Event is any action that is detected by the application. Typically, it is a user action like clicking on a button.
  1.Stream can be considered as a medium through which data travels. We can understand it with the idea of a Pipe through which data is taken as imput from one end and streamed       out through the other end(like water) as output with or without mmanipulations.
  1.Sink can be considered as the point where we input data to stream.
  
In the BLoC system there would be an input(Maybe using a button) which will act as Sink to the BLoC,  then the BLoC may Stream it to Output Widget like Text.

## Getting Started
You can build apps with Flutter using any text editor combined with Flutter's command-line tools. However, I recommend using one of Flutter's editor plugins for an even better experience. These plugins provide you with code completion, syntax highlighting, widget editing assists, run & debug support, and more.

## Prerequisites
Things you need to install:
1. Flutter sdk
2. Android Studio/VS Code (IDE)

For more info head towards https://flutter.dev/docs/get-started/install 

## Built With
1. Flutter - The sdk used
2. VS Code - IDE used
3. Android Studio - Android sdk

## Authors
Souvik Banerjee

### Acknowledgments
Thanks to all whose codes were used.
