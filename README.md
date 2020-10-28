# Ex Libris Primo Speed Tracker

This project was presented on October 28, 2020 at the [2020 ELUNA Learns - Primo Developer Presentations](https://el-una.org/eluna-learns/eluna-learns-primo-developer-presentations/) session.  Here is the description of that presentation:

In order to collect information about user perceptions regarding Primo load time, I developed a javascript widget to embed into the Primo interface that allows users to report whether or not they felt the Primo results page loaded fast enough. This presentation will discuss how I developed the widget using the custom.js and custom1.css files that are loaded into the Manage Customization Package in Alma, and will share the various reports and features that are a part of the data collection website I developed to collect user reported information using URL parameters. This presentation will also show how I identified specific Primo time variables to collect, and demonstrate to the audience how they can select their own variables to collect for their own reporting purposes.

This GitHub Repository holds the [Javascript](https://github.com/Hypolymer/primo_speed_tracker/blob/main/custom.js) file and [CSS](https://github.com/Hypolymer/primo_speed_tracker/blob/main/custom1.css) file used in this project.  These files will need to be included in the .zip folder that is uploaded in Alma under the [Manage Customization Package](https://knowledge.exlibrisgroup.com/Alma/Product_Documentation/010Alma_Online_Help_(English)/070Alma-Summon_Integration/050Display_Configuration/020Branding_the_Services_Page).  There was an additional PHP page that was created to handle the data that is passed in the URL when the user clicks the speed reporting button.  That PHP page accepts each of the variables passed in the URL and enters them in a MySQL database.

This project relied on the Ex Libris GitHub page for [Primo Explore Package](https://github.com/ExLibrisGroup/primo-explore-package) to learn how to drill down into the available Primo data through Google Chrome.
