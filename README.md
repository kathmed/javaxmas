<js>
    //Reads number of rows to be printed
    var n = 8;
 
    for(i=1; i<=n; i++)
    { 
        //Prints trailing spaces
        for(j=i; j<n; j++)
        {
            document.write(" ");
        }
 
        //Prints the pyramid pattern
        for(j=1; j<=(2*i-1); j++)
        {
            document.write("*");
        }
 
        document.write("<br>");

        }

</js>
