- 👋 Hi, I’m @salvotoshi77-creator![Exponentiation_as_monoid_homomorphism_svg](https://github.com/salvotoshi77-creator/salvotoshi77-creator/assets/132113671/29f259f4-1d82-48ea-85a8-2176c3f0ff04)

- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---HTMLInputElement
The HTMLInputElement interface provides special properties and methods for manipulating the options, layout, and presentation of <input> elements.

EventTarget
Node
Element
HTMLElement
HTMLInputElement
Instance properties
Some properties only apply to input element types that support the corresponding attributes.

align Deprecated
string: Represents the alignment of the element. Use CSS instead.

autocapitalize Experimental
string: Defines the capitalization behavior for user input. Valid values are none, off, characters, words or sentences.

defaultValue
string: Returns / Sets the default value as originally specified in the HTML that created this object.

dirName
string: Returns / Sets the directionality of the element.

inputmode
Provides a hint to browsers as to the type of virtual keyboard configuration to use when editing this element or its contents.

labels Read only
NodeList array: Returns a list of <label> elements that are labels for this element.

list Read only
HTMLElement: Returns the element pointed to by the list attribute. The property may be null if no HTML element is found in the same tree.

multiple
boolean: Returns / Sets the element's multiple attribute, indicating whether more than one value is possible (e.g., multiple files).

name
string: Returns / Sets the element's name attribute, containing a name that identifies the element when submitting the form.

popoverTargetAction Experimental
Gets and sets the action to be performed ("hide", "show", or "toggle") on a popover element being controlled by an <input> element of type="button". It reflects the value of the popovertargetaction HTML attribute.

popoverTargetElement Experimental
Gets and sets the popover element to control via an <input> element of type="button". The JavaScript equivalent of the popovertarget HTML attribute.

step
string: Returns / Sets the element's step attribute, which works with min and max to limit the increments at which a numeric or date-time value can be set. It can be the string any or a positive floating point number. If this is not set to any, the control accepts only values at multiples of the step value greater than the minimum.

type
string: Returns / Sets the element's type attribute, indicating the type of control to display. For possible values, see the documentation for the type attribute.

useMap Deprecated
string: Represents a client-side image map.

value
string: Returns / Sets the current value of the control. If the user enters a value different from the value expected, this may return an empty string.

valueAsDate
Date: Returns / Sets the value of the element, interpreted as a date, or null if conversion is not possible.

valueAsNumber
double: Returns the value of the element, interpreted as one of the following, in order: A time value, a number or NaN if conversion is impossible

Instance properties related to the parent form
form Read only
HTMLFormElement: Returns a reference to the parent <form> element.

formAction
string: Returns / Sets the element's formaction attribute, containing the URL of a program that processes information submitted by the element. This overrides the action attribute of the parent form.

formEnctype
string: Returns / Sets the element's formenctype attribute, containing the type of content that is used to submit the form to the server. This overrides the enctype attribute of the parent form.

formMethod
string: Returns / Sets the element's formmethod attribute, containing the HTTP method that the browser uses to submit the form. This overrides the method attribute of the parent form.

formNoValidate
boolean: Returns / Sets the element's formnovalidate attribute, indicating that the form is not to be validated when it is submitted. This overrides the novalidate attribute of the parent form.

formTarget
string: Returns / Sets the element's formtarget attribute, containing a name or keyword indicating where to display the response that is received after submitting the form. This overrides the target attribute of the parent form.

Instance properties that apply to any type of input element that is not hidden
autofocus
boolean: Returns / Sets the element's autofocus attribute, which specifies that a form control should have input focus when the page loads, unless the user overrides it, for example by typing in a different control. Only one form element in a document can have the autofocus attribute.

disabled
boolean: Returns / Sets the element's disabled attribute, indicating that the control is not available for interaction. The input values will not be submitted with the form. See also readonly.

required
boolean: Returns / Sets the element's required attribute, indicating that the user must fill in a value before submitting a form.

validationMessage Read only
string: Returns a localized message that describes the validation constraints that the control does not satisfy (if any). This is the empty string if the control is not a candidate for constraint validation (willValidate is false), or it satisfies its constraints. This value can be set by the setCustomValidity() method.

validity Read only
ValidityState: Returns the element's current validity state.

willValidate Read only
boolean: Returns whether the element is a candidate for constraint validation. It is false if any conditions bar it from constraint validation, including: its type is one of hidden, reset or button, it has a <datalist> ancestor or its disabled property is true.

Instance properties that apply only to elements of type checkbox or radio
checked
boolean: Returns / Sets the current state of the element.

defaultChecked
boolean: Returns / Sets the default state of a radio button or checkbox as originally specified in HTML that created this object.

indeterminate
boolean: Returns whether the checkbox or radio button is in indeterminate state. For checkboxes, the effect is that the appearance of the checkbox is obscured/greyed in some way as to indicate its state is indeterminate (not checked but not unchecked). Does not affect the value of the checked attribute, and clicking the checkbox will set the value to false.

Instance properties that apply only to elements of type image
alt
string: Returns / Sets the element's alt attribute, containing alternative text to use.

height
string: Returns / Sets the element's height attribute, which defines the height of the image displayed for the button.

src
string: Returns / Sets the element's src attribute, which specifies a URI for the location of an image to display on the graphical submit button.

width
string: Returns / Sets the element's width attribute, which defines the width of the image displayed for the button.

Instance properties that apply only to elements of type file
accept
string: Returns / Sets the element's accept attribute, containing comma-separated list of file types that can be selected.

allowdirs Non-standard
boolean: Part of the non-standard Directory Upload API. Indicates whether or not to allow directories and files both to be selected in the file list. Implemented only in Firefox and is hidden behind a preference.

files
FileList: Returns / Sets a list of File objects representing the files selected for upload.

webkitdirectory
boolean: Returns the webkitdirectory attribute. If true, the file-system-picker interface only accepts directories instead of files.

webkitEntries
FileSystemEntry array: Describes the currently selected files or directories.

Instance properties that apply only to visible elements containing text or numbers
autocomplete
string: Returns / Sets the element's autocomplete attribute, indicating whether the value of the control can be automatically completed by the browser.

max
string: Returns / Sets the element's max attribute, containing the maximum (numeric or date-time) value for this item, which must not be less than its minimum (min attribute) value.

maxLength
unsigned long: Returns / Sets the element's maxlength attribute, containing the maximum number of characters (in Unicode code points) that the value can have.

min
string: Returns / Sets the element's min attribute, containing the minimum (numeric or date-time) value for this item, which must not be greater than its maximum (max attribute) value.

minLength
unsigned long: Returns / Sets the element's minlength attribute, containing the minimum number of characters (in Unicode code points) that the value can have.

pattern
string: Returns / Sets the element's pattern attribute, containing a regular expression that the control's value is checked against. Use the title attribute to describe the pattern to help the user. This attribute only applies when the value of the type attribute is text, search, tel, url or email.

placeholder
string: Returns / Sets the element's placeholder attribute, containing a hint to the user of what can be entered in the control. The placeholder text must not contain carriage returns or line-feeds. This attribute only applies when the value of the type attribute is text, search, tel, url or email.

readOnly
boolean: Returns / Sets the element's readonly attribute, indicating that the user cannot modify the value of the control. This is ignored if the type is hidden, range, color, checkbox, radio, file, or a button type.

selectionEnd
unsigned long: Returns / Sets the end index of the selected text. When there's no selection, this returns the offset of the character immediately following the current text input cursor position.

selectionStart
unsigned long: Returns / Sets the beginning index of the selected text. When nothing is selected, this returns the position of the text input cursor (caret) inside of the <input> element.

selectionDirection
string: Returns / Sets the direction in which selection occurred. Possible values are: forward (the selection was performed in the start-to-end direction of the current locale), backward (the opposite direction) or none (the direction is unknown).

size
unsigned long: Returns / Sets the element's size attribute, containing visual size of the control. This value is in pixels unless the value of type is text or password, in which case, it is an integer number of characters. Applies only when type is set to text, search, tel, url, email, or password.

Instance methods
blur()
Removes focus from the input element; keystrokes will subsequently go nowhere.

click()
Simulates a click on the input element.

focus()
Focuses on the input element; keystrokes will subsequently go to this element.

select()
Selects all the text in the input element, and focuses it so the user can subsequently replace all of its content.

setSelectionRange()
Selects a range of text in the input element (but does not focus it).

setRangeText()
Replaces a range of text in the input element with new text.

setCustomValidity()
Sets a custom validity message for the element. If this message is not the empty string, then the element is suffering from a custom validity error, and does not validate.

showPicker()
Shows a browser picker for date, time, color, and files.

checkValidity()
Returns a boolean value that is false if the element is a candidate for constraint validation, and it does not satisfy its constraints. In this case, it also fires an invalid event at the element. It returns true if the element is not a candidate for constraint validation, or if it satisfies its constraints.

reportValidity()
Runs the checkValidity() method, and if it returns false (for an invalid input or no pattern attribute provided), then it reports to the user that the input is invalid in the same manner as if you submitted a form.

stepDown()
Decrements the value by (step * n), where n defaults to 1 if not specified. Throws an InvalidStateError exception:

if the method is not applicable to for the current type value,
if the element has no step value,
if the value cannot be converted to a number,
if the resulting value is above the max or below the min.
stepUp()
Increments the value by (step * n), where n defaults to 1 if not specified. Throws an InvalidStateError exception:

if the method is not applicable to for the current type value.,
if the element has no step value,
if the value cannot be converted to a number,
if the resulting value is above the max or below the min.
Events
Listen to these events using addEventListener() or by assigning an event listener to the oneventname property of this interface:

input
Fires when the value of an <input>, <select>, or <textarea> element has been changed. Note that this is actually fired on the HTMLElement interface and also applies to contenteditable elements, but we've listed it here because it is most commonly used with form input elements.

invalid
Fired when an element does not satisfy its constraints during constraint validation.

search Non-standard
Fired when a search is initiated on an <input> of type="search".

selectionchange event Experimental
Fires when the text selection in a <input> element has been changed.

Specifications
Specification
HTML Standard
# htmlinputelement
Browser compatibility
Report problems with this compatibility data on GitHub
desktop	mobile
Chrome
Edge
Firefox
Opera
Safari
Chrome Android
Firefox for Android
Opera Android
Safari on iOS
Samsung Internet
WebView Android
HTMLInputElement

1
Toggle history	
12
Toggle history	
1
Toggle history	
8
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
10.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
37
Toggle history
accept

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
align
Deprecated

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
alt

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
autocomplete

14
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
6
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
6
Toggle history	
1.0
Toggle history	
4.4
Toggle history
cancel event
Experimental

No
footnote
Toggle history	
No
footnote
Toggle history	
91
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
91
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history
capture

No
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
25
Toggle history	
79
Toggle history	
14
Toggle history	
10
Toggle history	
1.5
Toggle history	
4.4
Toggle history
checkValidity

4
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
checked

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
defaultChecked

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
defaultValue

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
dirName

17
Toggle history	
79
Toggle history	
No
Toggle history	
12.1
Toggle history	
6
Toggle history	
18
Toggle history	
No
Toggle history	
12.1
Toggle history	
6
Toggle history	
1.0
Toggle history	
4.4
Toggle history
disabled

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
files

2
Toggle history	
12
Toggle history	
3
Toggle history	
12.1
Toggle history	
4
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
3
Toggle history	
1.0
Toggle history	
37
Toggle history
form

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
formAction

9
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4.2
Toggle history	
1.0
Toggle history	
3
Toggle history
formEnctype

9
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4.2
Toggle history	
1.0
Toggle history	
3
Toggle history
formMethod

9
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4.2
Toggle history	
1.0
Toggle history	
3
Toggle history
formNoValidate

4
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
formTarget

9
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4.2
Toggle history	
1.0
Toggle history	
3
Toggle history
height

21
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
7
Toggle history	
25
Toggle history	
16
Toggle history	
12.1
Toggle history	
7
Toggle history	
1.5
Toggle history	
4.4
Toggle history
incremental

10
Toggle history	
79
Toggle history	
No
Toggle history	
15
Toggle history	
5
Toggle history	
18
Toggle history	
No
Toggle history	
14
Toggle history	
4.2
Toggle history	
1.0
Toggle history	
37
Toggle history
indeterminate

1
Toggle history	
12
Toggle history	
3.6
Toggle history	
12.1
Toggle history	
3
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
invalid event

10
Toggle history	
12
Toggle history	
4
Toggle history	
10
Toggle history	
5
Toggle history	
18
Toggle history	
64
Toggle history	
12
Toggle history	
5
Toggle history	
4.0
Toggle history	
4
Toggle history
labels

6
Toggle history	
18
Toggle history	
56
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
56
Toggle history	
12.1
Toggle history	
4.2
Toggle history	
1.0
Toggle history	
3
Toggle history
list

20
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
12.1
Toggle history	
25
Toggle history	
4
Toggle history	
12.1
Toggle history	
12.2
Toggle history	
1.5
Toggle history	
4.4.3
Toggle history
max

4
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
16
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
maxLength

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
min

4
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
16
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
minLength

40
Toggle history	
17
Toggle history	
51
Toggle history	
27
Toggle history	
10.1
Toggle history	
40
Toggle history	
51
Toggle history	
27
Toggle history	
10.3
Toggle history	
4.0
Toggle history	
40
Toggle history
multiple

2
Toggle history	
12
Toggle history	
3.6
Toggle history	
12.1
Toggle history	
4
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
3.2
Toggle history	
1.0
Toggle history	
37
Toggle history
name

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
pattern

4
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
placeholder

3
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
3.2
Toggle history	
1.0
Toggle history	
37
Toggle history
popoverTargetAction
Experimental

114
Toggle history	
114
Toggle history	
No
Toggle history	
No
Toggle history	
TP
Toggle history	
114
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
114
Toggle history
popoverTargetElement
Experimental

114
Toggle history	
114
Toggle history	
No
Toggle history	
No
Toggle history	
TP
Toggle history	
114
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
114
Toggle history
readOnly

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
reportValidity

40
Toggle history	
17
Toggle history	
49
Toggle history	
27
Toggle history	
10.1
Toggle history	
40
Toggle history	
64
Toggle history	
27
Toggle history	
10.3
Toggle history	
4.0
Toggle history	
40
Toggle history
required

4
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
search event
Non-standard

1
Toggle history	
79
Toggle history	
No
Toggle history	
15
Toggle history	
2
Toggle history	
18
Toggle history	
No
Toggle history	
14
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
select

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
select event

1
Toggle history	
12
Toggle history	
6
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
6
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
selectionDirection

15
Toggle history	
13
Toggle history	
8
Toggle history	
12.1
Toggle history	
6
Toggle history	
18
Toggle history	
8
Toggle history	
12.1
Toggle history	
6
Toggle history	
1.0
Toggle history	
4.4
Toggle history
selectionEnd

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1.3
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
selectionStart

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1.3
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
selectionchange event
Experimental

No
footnote
Toggle history	
No
footnote
Toggle history	
92
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
92
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history	
No
footnote
Toggle history
setCustomValidity

4
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
setRangeText

24
Toggle history	
79
Toggle history	
27
Toggle history	
15
Toggle history	
7
Toggle history	
25
Toggle history	
27
Toggle history	
14
Toggle history	
7
Toggle history	
1.5
Toggle history	
4.4
Toggle history
setSelectionRange

1
Toggle history	
12
Toggle history	
1
Toggle history	
8
Toggle history	
3
Toggle history	
18
Toggle history	
4
Toggle history	
10.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
showPicker

99
Toggle history	
99
Toggle history	
101
Toggle history	
85
Toggle history	
16
Toggle history	
99
Toggle history	
101
Toggle history	
68
Toggle history	
16
Toggle history	
18.0
Toggle history	
99
Toggle history
autocomplete input

99
Toggle history	
99
Toggle history	
No
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
No
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
color input

99
Toggle history	
99
Toggle history	
101
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
101
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
datalist input

99
Toggle history	
99
Toggle history	
No
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
No
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
date input

99
Toggle history	
99
Toggle history	
101
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
101
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
datetime-local input

99
Toggle history	
99
Toggle history	
101
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
101
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
file input

99
Toggle history	
99
Toggle history	
101
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
101
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
month input

99
Toggle history	
99
Toggle history	
No
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
No
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
time input

99
Toggle history	
99
Toggle history	
No
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
No
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
week input

99
Toggle history	
99
Toggle history	
No
Toggle history	
85
Toggle history	
No
footnote
Toggle history	
99
Toggle history	
No
Toggle history	
68
Toggle history	
No
footnote
Toggle history	
18.0
Toggle history	
99
Toggle history
size

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
src

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
step

5
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
16
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
stepDown

5
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
16
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
stepUp

5
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
16
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
type

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
useMap
Deprecated

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
validationMessage

5
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
validity

4
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
value

1
Toggle history	
12
Toggle history	
1
Toggle history	
12.1
Toggle history	
1
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
1
Toggle history	
1.0
Toggle history	
4.4
Toggle history
valueAsDate

5
Toggle history	
12
Toggle history	
57
more
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
57
more
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
valueAsNumber

5
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
5
Toggle history	
18
Toggle history	
16
Toggle history	
12.1
Toggle history	
4
Toggle history	
1.0
Toggle history	
37
Toggle history
webkitEntries

22
Toggle history	
79
Toggle history	
50
Toggle history	
15
Toggle history	
11.1
Toggle history	
25
Toggle history	
No
Toggle history	
14
Toggle history	
11.3
Toggle history	
1.5
Toggle history	
No
Toggle history
webkitdirectory

7
Toggle history	
13
Toggle history	
50
Toggle history	
15
Toggle history	
11.1
Toggle history	
18
Toggle history	
No
Toggle history	
14
Toggle history	
11.3
Toggle history	
1.0
Toggle history	
4.4
Toggle history
width

21
Toggle history	
12
Toggle history	
16
Toggle history	
12.1
Toggle history	
7
Toggle history	
25
Toggle history	
16
Toggle history	
12.1
Toggle history	
7
Toggle history	
1.5
Toggle history	
4.4
Toggle history
willValidate

2
Toggle history	
12
Toggle history	
4
Toggle history	
12.1
Toggle history	
4
Toggle history	
18
Toggle history	
4
Toggle history	
12.1
Toggle history	
3
Toggle history	
1.0
Toggle history	
37
Toggle history
Legend
Tip: you can click/tap on a cell for more information.

Full support
Full support
Partial support
Partial support
In development. Supported in a pre-release version.
In development. Supported in a pre-release version.
No support
No support
Experimental. Expect behavior to change in the future.
Non-standard. Check cross-browser support before using.
Deprecated. Not for use in new websites.
See implementation notes.
Has more compatibility info.
See also
HTML element implementing this interface: <input>
Found a content problem with this page?
Edit the page on GitHub.
Report the content issue.
View the source on GitHub.
Want to get more involved? Learn how to contribute.
This page was last modified on May 3, 2023 by MDN contributors.
salvotoshi77-creator/salvotoshi77-creator is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
