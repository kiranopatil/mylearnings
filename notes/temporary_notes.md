# HTML 
* most of the editors come with tag autofilling..
    * Eg: type html and press tab .. you will get <html> </html> 
Tested in VSCode and Sublimetext
* In Browser to use Developer tool Press F12 or Ctrl + Shift + C (Windows)
* To generate dummy text one can use "lorem" tab to fill text.. most text editors supoort it.. Tested in VSCODE and sublime text.
  Eg: lorem <tab>
      lorem200 <tab>
* Block Vs Inline elements
    * Block : 
        * Start on a new line
        * Take full width available
        * `Eg: <div>, <h1>..<h6>, <p>, <form>`
    * Inline : 
        * Donot start on a new line 
        * Take only necessary width 
        * `Eg: <span>, <img>,<a> `

* Tag Attributes: <tagname attributename="attributevalue">content</tagname>
	`<h1 title="My Company">About Us</h1>`
	* All tags can have attributes
	* Provide information about an element
	* Placed within the start tag
	* key/value pairs (id="someid")
* Table syntax:
	```HTML
	<table>
    <thead>
        <tr>
            <th>

            </th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                
            </td>
        </tr>
    </tbody>
	</table>
	```
* Forms: <form> </form>
	* Following tags are allowed inside 
	* <label></label> -> to display text
	* <input></input> -> Diplay a input text box
		* Attributes:
		* type - type of text Eg: text, email, textarea, date
		* name - Description
		* textarea - 
		* select - 
			* Eg: ```<div>
				<select name="gender">
				<option value='male'>"Male"</option>
				<option value='female'>"Female"</option>
				<option value=other>"other"</option>

				</select>
				</div>
			     ```
		* date
		* placeholder
		* value
		* submit
* Buttons outside the form is possible
	* <button>text</button>
* Quotations:
	* Blockqote - similar as <p> which gives more padding and format to text
	* abbreviate - For abbrevation
	*Eg: <p>The <abbr title="Wold Wide Web">WWW</abbr> is awsome </p?
	* cite - is a semantic which gives italics test 
	
