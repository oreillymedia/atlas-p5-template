# Using p5 with Atlas

This is an simple template for using [p5](http://p5js.org) with Atlas.  It will turn code listings you mark as "executable" into editable,runnable examples in the HTML build.  For example, this:

```html
<pre data-executable="true" data-language="p5">
   ... Add your P5 code here ...
</pre>
```

Here's [an example site of that uses the P5 plugin](http://sites.oreilly.com/oreillymedia/oreilly-p5-template/ch01.html).


To use this template:

* Create a new project in Atlas
* Click the  the "Advanced" link
* Paste "https://github.com/oreillymedia/atlas-p5-template.git" into the Custom field
* Click "Create Project"

Atlas will churn away for a while, and then you can edit your project.  There are example files for both Markdown and HTMLBook.  Once you're ready to publish:

* Configure your build by adding the files in the order you want them to appear.  (We've already added the P5 plugin by default.)
* Do an HTML Build
* If you want to publish it on an O'Reilly domain:
  * Go to the [Atlas web publisher](http://web-publisher.atlas.oreilly.com/)
  * Enter your atlas API key and your project ("username/project name" format)
  * Click build
* You can also just download the zip file and deploy the static site wherever your want.  We won't mind.  

If you have questions, post them in the [Atlas support form](http://forum.atlas.oreilly.com).
