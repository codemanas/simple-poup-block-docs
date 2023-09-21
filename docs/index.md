<!-- # Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->


# Simple Popup Block

## Overview
<p> The Simple Popup Block Plugin is a versatile and intuitive tool that extends the functionality of WordPress Block Editor by introducing a seamless popup feature. With its easy-to-use interface and robust customization options, this plugin empowers users to effortlessly create engaging popups tailored to their specific needs. </p>

<h5> Feature Listing </h5>
<p> These are the features that are included with the popup block plugin. </p>
<ol>
    <li>
        <p>Popup Trigger</p>
        <p>The trigger are used to set the prerequisites for the popup's display. Trigger conditions on: </p>
        <ul type="square">
            <li>
                <p>Time</p>
                <p>By default, the pop-up appears as soon as the page finishes loading. However, you can delay triggering your pop-up by setting the delay time in seconds. </p>
            </li>
            <li>
                <p>Scroll<p>
                <p>By selecting the scroll behaviour the popup can be triggered on page scroll. Options are availabel to set on what type of page scroll.
                <ul type="disc">
                <li>Scroll Percentage
                <p>Provides the option to input a percentage, and when the desired scroll percentage is achieved, a popup is displayed.</p>
                </li>
                <li>Scroll to element</li>
                <p>Provides a choice to add elements, such as by class or ids, and displays the popup once that element is reached.</p>
                </ul>
                </p>
            </li>
            <li>
                <p>Click</p>
                <p>Provides a choice to add elements, such as by class or ids, and displays the popup once that element is clicked.</p>
            </li>
        </ul>    
    </li>
    <li>
        <p>Popup Behaviour<p>
        <p>Describe the popup behaviour.</p>
        <ol type="a">
            <li>
                <p>Show Popup Once</p>
                <p>Enabling this option will only show popup once.</p>
            </li>
            <li>
                <p>Auto Close Popup</p>
                <p>This will automatically close your pop-up after specified time. Provides the option to input the time delay to close popup. </p>
                <p><i>Note: This behaviour is availabe only to the "Time" and "Scroll" trigger .</i></p>
            </li>
        </ol>   
    </li> 
    <li>
        <p>Popup Conditions</p>
        <p>Control poup condition on the current user's status or specific roles. Condtions provided:</p>
         <ul type="square">
            <li>
                <p>All</p>
                <p>By default, the pop-up appears for all the users or roles.</p>
            </li>
            <li>
                <p>Logged In Users</p>
                <p>Shows popup to only the logged-in users.</p>
            </li>
            <li>
                <p>Logged Out Users</p>
                <p>Shows popup to only the logged-out users.</p>
            </li>
            <li>
                <p>Specific User Roles</p>
                <p>Show the popup for users with at least one of the selected roles.</p>
                <p>Based on the created user-roles in wordpress</p>
                <p>For example: administrator, editor and so on.</p>
            </li>
        </ul>    
    </li>
</ol>

<h5>Styling Options</h5>

<p>Popup blocks provide a variety of style options. </p>
<ol>
<li>
    <p>Dimensions</p>
    <p>Include options to modify the height, width and border of the popup.</p>
    <ul type="square">
        <li>
            <p>Width</p>
            <p>Select the width of the popup.</p>
        </li>
        <li>
            <p>Height</p>
            <p>Select the height of the popup.</p>
        </li>
        <li>
            <p>Border</p>
            <p>Select the border for the popup.</p>
        </li>
    </ul>
</li>
<li>
    <p>Close Button</p>
    <p>Enables to customize the close button.</p>
    <ol type="square">
        <li>
            <p>Position</p>
            <p>Allow to hide the close button or display it inside/outside the popup.</p>
            <ol type="disc">
                <li>Outside</li>
                <li>Inside</li>
                <li>Hidden</li>
            </ol>
        </li>
        <li>
            <p>Size</p>
             <p>Select the size of the popup.</p>
        </li>
        <li>
            <p>Color</p>
            <p>Select the color using the color palatte for the close icon.</p>
        </li>
        <li>
            <p>Close Icon Options</p>
            <p>Choose an option for the close icon style. For Example : Default, Circular, Rectangle.</p>
        </li>
    </ol>
</li>

</ol>

## Installation

<h2> Minimum Requirements </h2>
<ul>
   <li> PHP 7.4 required or greater </li>
   <li> MySQL 5.6 or greater is recommended </li>
</ul>

<h2> Automatic Installation </h2>
<ol>
<li> Go to WordPress Plugins > Add New Search for "Simple Popup Block" </li>
<li> Click Install and then activate Plugin </li>
</ol>

<h2> Manual Installation </h2>
<p> If for some reason automatic installation is not possible, go to [path/to/simple-popup-block-plugin] and you will see the download button. Clicking download button will provide you with a zip file of the plugin then.</p>
<ol>
<li> Go to WordPress Plugins > Add New and click upload plugin. </li>
<li> Click upload plugin and then add the zip file. </li>
<li> The plugin will then be installed, then activate the plugin. </li>
</ol>

