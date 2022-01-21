# Desktop Aurora

This project projects XAML and BAML files to Windows wallpaper. 

## Roadmap:

  * Proof of Concept ✔️
  * Post the source code
  * Implement BAML reader
  * Support Windows versions older than Windows 10

## How it works?
It makes use of C++/CLI to get "Desktop Walpaper HWND".
Than it creates child HwndSource and loads XAML with XamlReader.
It should be easy to implement BAML through the Baml2006Reader.

## Current state
I've made a Proof of Concept application. It has really loaded Aurora XAML onto the wallpaper.
It is tested on Windows 10, but I want to support older versions (maybe also Windows Longhorn). 

## Ideas
  * Compile XAML to BAML for better performance
