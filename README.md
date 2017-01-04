# widget_Plus

This collection is a set of widget which give more controls on the standard widget.


InputPlus : 
	* Real Max Length : you can decide for the max character. After this number, it is not possible to give more character
	* Style CSS : directly set some additional CSS style to the input
	* Title : add an info bullet to your widget
	
TextArea plus
	* Real Max Length : you can decide for the max character. After this number, it is not possible to give more character
	* Style CSS : directely set some additional CSS style to the input
	* Title : add an info bullet to your widget
	
Title Plus
	* Style CSS : directly set some additional CSS style to the input
		
CheckList :
	The standard checkList REMOVE the attribut in the result JSON when nothing is selected.
	So, if you use a CheckList, map to a contract, the submit will be rejected, or you have to do that in your formOutput
		'color' : $data.formInput.color || null
	To avoid this behavior and to not worry of the usage of the widget in the formOutput, use this CheckList.
	Plus : 	
	* Style CSS : directly set some additional CSS style to the input

Select
	Same behavior as the CheckList : if not value is selected, the widget REMOVE the attribut.
	Plus : 	
	* Style CSS : directly set some additional CSS style to the input
		
RadioButton
	Same behavior as the CheckList : if not value is selected, the widget REMOVE the attribut.
	Plus : 	
	* Style CSS : directly set some additional CSS style to the input
	
<img src="ScreenShot.jpeg"/>	