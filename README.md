# Oea.svg

SVG GUI and Graphics Library built after Java AWT. The Oea Framework provides three Javascript libraries, 1- Java.js, 2- Draw2D.svg and 3- Swing.svg to build SVG GUI applications.

## Java.js

This package container a number of core Java classes that was required to implement both, Draw2D.svg and Swing.svg. Two Java packages have been ported, AWT and Util. AWT classes included Event and Geom namespaces while Util package included generic classes such as Hastable, Vector, Enumeration and many other useful code.

## Draw2D.svg

The svgDraw2D package is written for SVG in JavaScript to decouple the manipulation of DOM/SVG interfaces from writing graphics applications. The package provides a higher level of abstraction to JavaScript developers to manipulate graphics independently from the DOM API. It also provides capabilities for drawing sophisticated two-dimensional shapes, working with fonts, text and text layout, controlling colours; and it features layering management, styled tool tips and desktop canvas. The work on the svgDraw2D package was inspired by the Java AWT package.

## Swing.svg

Swing was the unofficial code name of the project that developed Java Foundational Classes (JFC) for Java. This inspired the name Swing.svg for this package.

Swing.svg offers classes to help in developing GUI components. There are two main sets of components in Swing.svg: Top Level Containers (e.g. Panel and Window) and Basic Components (e.g. Button and ScrollBox).

Top Level Components inherit indirectly from the Component class through EventManager, hence they support direct AWT-like events. The Window class for instance may enable AWT-events and choose to listen to them through Mouse Motion Interface or Mouse Interface. The AWT-events received by the Window class have been generated by the EventManager and delivered by ListenerManager.

Button class handles AWT-like events generated from an indirect source; EContainer. EContainer is the root of a tree of Basic Components. AWT-like events received by EContainer are processed and then routed down the containment hierarchy to a target component (similar to DOM).

The Swing.svg Package has adapted a look-and-feel similar to that of MS-Windows. This is temporary. The package supports a pluggable look-and-feel model.

More details are [here](https://github.com/websemantics/Oea.svg/raw/master/pdf/svg_open_2005_mem.pdf)
