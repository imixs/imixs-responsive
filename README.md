# Imixs-Responsive


Imixs-Responsive provides an easy to use CSS and java Script framework for responsive websites and web apps.

Imixs-Responsive is basically a responsive layout concept. This means that a website based on it will fit into any screen size. The way the website's elements are displayed will depend on the device choosen by the user. 


Imixs-Responsive is licensed under a Creative Commons Share Alike 4.0 International license.
http://creativecommons.org/licenses/by-sa/4.0/



## Form Layout

Imixs-Responsive provides layout classes for a generic form layout. Input elements in this layout are put into form-sections which provide a multi-column layout based on DL Definitonens. 


### imixs-form-section

One column layout example:


	<div class="imixs-form-section">
		<dl>
			<dt>Subject</dt>
			<dd>
				<h:inputText value="#{workitem.item['_subject']}"  />
			</dd>
			<dt>Customer:	</dt>
			<dd>
				<h:inputText value="#{workitem.item['_customer']}" />
			</dd>
		</dl>
	</div>

For Multi column layout, the input elements must be put into separated DL sections

2-column layout example:

	<div class="imixs-form-section-2">
		<dl>
			<dt>Project:</dt>
			<dd>
				<h:inputText value="#{workitem.item['_project']}" />
			</dd>
		</dl>
		<dl>
			<dt>Contact:</dt>
			<dd>
				<h:inputText value="#{workitem.item['_contact']}" />
			</dd>
		</dl>
	</div>