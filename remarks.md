* In the file `_config.yml`, after putting course_name: MO and course_semester: "20",
all the pages on MOTP, when browsed, shows Algebra - MO / 20, Geometry - MO / 20 etc.
* Fine! But from do we get the slash in MO / 20?
  * In the file `_layouts/home.html`, removed a space before <span style, and removed a slash-space (/ ) after 6;">.
  * After building the page, one observes that the above process does remove the slash from Algebra - MO / 20, Geometry - MO / 20.
    But it removed the slash from MO/20 as shown below.
    
<p float="left">
<img src="https://raw.githubusercontent.com/jpsaha/MOTP/_images/screenshots/LearningSyntax/FrmTopOfHome-SlashRemoved.png" width="300">
</p>
