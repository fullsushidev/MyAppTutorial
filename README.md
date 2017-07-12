# Introduction
**Welcome,**
In this first book you will find Android related tutorials that will help you to explore the basics functionalities of Back4app.com

> #### warning::Disclaimer
> To avoid compatibility issues in every tutorial you will find a box like these to inform you about what program versions were used in the tutorial.




\[Summary of\]
What is?
What is it for?
What will you learn here?








# If you're doing the tutorial at home

If you're doing the tutorial at home, not at one of the [Django Girls events](https://djangogirls.org/events/), you can completely skip this chapter now and go straight to the [How the Internet works](../how_the_internet_works/README.md) chapter.

---

{% label %}test.java{% endlabel %}
```java
//Imports are listed in full to show what's being used
//could just import javax.swing.* and java.awt.* etc..
import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.JComboBox;
import javax.swing.JButton;
import javax.swing.JLabel;
import javax.swing.JList;
import java.awt.BorderLayout;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;

public class GuiApp1 {
    
    //Note: Typically the main method will be in a
    //separate class. As this is a simple one class
    //example it's all in the one class.
    public static void main(String[] args) {
        
        new GuiApp1();
    }
```

---
.
> #### Title
> Content

.
> #### primary::Title
> Content

.
> #### success::Title
> Content

.
> #### danger::Title
> Content

.
> #### warning::Title
> Content

.
> #### info::Title
> Content

___


gitbook-plugin-sectionx
===

<!--sec data-title="Introduction" data-id="intro" data-nopdf="true" ces-->
This page is implemented using the two plugins developed by me: ```gitbook-plugin-sectionx```, please check the [Github repo](https://github.com/ymcatar/gitbook-plugin-sectionx) for the plugin.

The source code for this page is available [here](https://raw.githubusercontent.com/ymcatar/gitbook-test/master/testing_sectionx.md).
<!--endsec-->

<!--sec data-title="Example 1" data-id="section1" ces-->
This is a section that is by default visible. You can toggle this with the button in the title. The next section is hidden by default, you can add a custom button to toggle it (see GitHub for the syntax).

<button class="section" target="section3" show="Show the next section" hide="Hide the next section"></button>
<!--endsec-->

<!--sec data-title="Example 2" data-id="section2" data-collapse=true ces-->
This is a section that is by default closed but visible (with ```data-collapse=true```)
<!--endsec-->

<!--sec data-title="Hidden 3" data-id="section3" data-show=false ces-->
This section can only be opened with that button.
<!--endsec-->