$URLsources = "http://fooo/fooURL1:800","http://fooo/fooURL2:800","http://fooo/fooURL2:800"

#table definition
    $tabName = "Output table"

    #Create Table object
    $table = New-Object system.Data.DataTable “$tabName”

    #columns definition
    $col1URL = New-Object system.Data.DataColumn URL,([string])
    $col2Status = New-Object system.Data.DataColumn Status,([string])
    $col3Desc = New-Object system.Data.DataColumn Desc,([string])

    #add columns
    $table.Columns.Add($col1URL)
    $table.Columns.Add($col2Status)
    $table.Columns.Add($col3Desc)


foreach($url in $URLsources){
  $result = Invoke-WebRequest $url 
  
  #preparation of the row
      $row = $table.NewRow()
      $row.URL= $url
      $row.Status= $result.StatusCode
      $row.Desc= $result.StatusDescription

  #add row to the table  
  $table.Rows.Add($row)
    
}

#print out the table
$table | format-table -AutoSize 
 
