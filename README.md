# dotnet

<code>
@Html.DropDownList("Departments", new List<SelectListItem>
{ 
      new SelectListItem { Text = "IT", Value = "1", Selected=true},
      new SelectListItem { Text = "HR", Value = "2"},
      new SelectListItem { Text = "Payroll", Value = "3"}
}, "Select Department") 
</code>
