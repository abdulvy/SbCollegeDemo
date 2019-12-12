# SpringBoot Project


**Step 1:**<br/>

   We Need to Create SpringBoot Project Template, <br/>
   Follow below steps <br/>
   Go to link : https://start.spring.io/ <br/>
   Fill out : <br/>
   Group : <br/>
   Artifact : <br/>
   
   Like bellow <br/>
   
   Group : com.tcdc <br/>
   Artifact : Name of the project <br/>
   
**Step 2:** <br/>

<ul>
   <li>Add Dependency to our SpringBoot project Template</li>
<li>WEB Dependency is Enough for Basic Hello World app</li>
<li>Then Click on <b >Generate Button</b> to download our project template</li>
</ul>

<b>Step 3:</b> <br/>
<ul>
<li>Unzip the project Template and copy to your desired location</li>
 <li>Now Click on FILE->IMPORT->EXISTING MAVEN PROJECT</li>
 <li>Click On Browse and Select the Project Location</li>
  <li>Click on Finish Button</li>
</ul>

<b>Step 4:</b> <br/> 
<ul>
<li>Now open the eclipse and import the project to eclipse</li>
 <li>Run the Project</li>
</ul>

<b>Step 5:</b> <br/>
<ul>
<li>Add Jasper Dependency to support JSP pages in springboot</li>
 <li>Create folder under mail folder Ex:- webapp->WEB-INF->view </li>
 <li>Inside view folder create a JSP page</li>
 <li>Now add prefix and suffix to property file</li>
</ul>

      	<dependency>
			<groupId>org.apache.tomcat.embed</groupId>
			<artifactId>tomcat-embed-jasper</artifactId>
		</dependency>
      
 <b>Prefix and Sufix for properties file</b>
      
      spring.mvc.view.prefix:/WEB-INF/view/
      spring.mvc.view.suffix:.jsp
      
      

