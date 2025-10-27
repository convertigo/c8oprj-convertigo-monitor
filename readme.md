


# ConvertigoMonitor

Convertigo NGX builder Project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page](#page)
        - [ThreadDetails](#threaddetails)
        - [Threads](#threads)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     ConvertigoMonitor=/Users/nicolas/dev/convertigo/runtime-ConvertigoStudio/ConvertigoMonitor/.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     ConvertigoMonitor=/Users/nicolas/dev/convertigo/runtime-ConvertigoStudio/ConvertigoMonitor//archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __ConvertigoMonitor__ project


## Mobile Application

Describes the mobile application global properties

### Pages

#### Page

My First Page as root page

#### ThreadDetails

Detailed view of a single JVM thread

#### Threads

Threads snapshot view



