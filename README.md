# java-lab-5-solved
**TO GET THIS SOLUTION VISIT:** [Java Lab 5 Solved](https://www.ankitcodinghub.com/product/java-lab-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95420&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Java Lab 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
<ul>
<li>Pay attention to exception handling (otherwise: -0.5 points)</li>
<li>Create your own types of exceptions to report abnormal events related to
application execution.
</li>
<li>Organize your classes and interfaces in packages.
Media Catalog

Write an application that can manage a catalog of multimedia items. An entry in this catalog might be a song, a movie, a book, an image or any item that has at least a name and a path in the local file system. (We may also consider specifying a release year, a rating and other additional data, for example the author of the book, etc.)

The main specifications of the application are: Compulsory (1p)
</li>
</ul>
<ul>
<li>Create an object-oriented model of the problem. You should have at least the following classes: Catalog and two item classes at your choice. Consider using an interface or an abstract class in order to describe the items in a catalog.</li>
<li>Implement the following methods representing commands that will manage the content of the catalog:</li>
</ul>
o add: adds a new entry into the catalog;

o list: prints the content of the catalog on the screen;

o play: playback using the native operating system application (see

the Desktop class);

o save: saves the catalog to an external file (either as a text or binary,

using object serialization);

o load: loads the catalog from an external file.

• The application will signal invalid data (year, path, etc.) using a custom exception.

Optional (2p)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>Create a shell that allows reading commands from the keyboard, together with their arguments.</li>
<li>Represent the commands using classes instead of methods. Use an interface or an abstract class in order to desribe a generic command.

Implement the commands add, list, save, load, play (create the

classes AddCommand, ListCommand, etc.).</li>
<li>Implement the command report: create (and open) an HTML report representing the content of the catalog.

Use a template engine such as FreeMarker or Velocity, in order to create the HTML report.</li>
<li>The application will signal the commands that are not valid using a custom exception.</li>
<li>The final form of the application will be an executable JAR archive. Identify the generated archive and launch the application from the console, using the JAR.
Bonus (2p)
</li>
</ul>
<ul>
<li>Use Apache Tika in order to extract metadata from your catalog items and implement the command info in order to display them.</li>
<li>Create a graph G in which the catalog items represent the nodes, two nodes being connected if they share some common feature (for example, two songs that have the same artist, etc).</li>
<li>Suppose that you want to play all the items in the catalog in as fe w days as possible, so that in one day you will not play two items that are connected in G. Create an algorithm that generates the playlists for each day.</li>
<li>Create large graphs and test your algorithm. Resources</li>
</ul>
<ul>
<li>Basic I/O</li>
<li>Exceptions</li>
<li>Regular Expressions</li>
<li>Setting the class path</li>
<li>Creating, Importing, and Configuring Java Projects in Netbeans</li>
<li>Packaging Programs in JAR Files
Objectives
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>Use basic I/O streams.</li>
<li>Understand the difference between byte and character streams, primitive and
decorator streams.
</li>
<li>Use File I/O to works with files and directories.</li>
<li>Handle exceptions using try-catch-finally blocks.</li>
<li>Handle resources using try-with-resources statements.</li>
<li>Create custom exceptions and chained exceptions.</li>
<li>Use regular expressions and glob patterns</li>
<li>Understand the notion of CLASSPATH.</li>
<li>Use external JAR libraries.</li>
<li>Package all project classes as an executable JAR file.</li>
</ul>
</div>
</div>
</div>
