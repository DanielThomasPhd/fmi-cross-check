Model:
      Modelica Standard library model
      BooleanNetwork1
      
      FMI Type:
      ModelExchange
      
      Generation Tool:
      Dymola 2015 FD01
      
      Available Platforms:
      win32, win64
      
      Known Errors:
      
      Additional Information:
      
      
        
      FMUChecker:
      FMUChecker Version 2.0.1 
      
      run command:
      set FMUName=BooleanNetwork1
      fmuCheck.win64.exe -k me -e %FMUName%_cc.log -o %FMUName%_cc.csv -i %FMUName%_in.csv -h 1e-2 -s 10 %FMUName%.fmu
      
      Contact info: karl.wernersson@3ds.com
