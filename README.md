# bpa2matpower
A data conversion from BPA-china dataform to MATPOWER dataform, may also work for EPRI-WSCC dataform(.dat),original author Cyren_BJTU @ csdn.net, original source https://download.csdn.net/download/cyren_bjtu/11008596, dubugged by Vurgit. Tested using ieee90.dat and 118bpa.dat, converted and powerflow calculated successfully.Run Untitled.m for conversion test.Still has some major problem when converting data from actual grid in China provinces,probably resulted from lack of data input standardization of employees,may also have problems converting actual data from other countries.Try writing dataform in BPA as close to the standard of IEEE dataform as possible.CANNOT DEAL WITH DC BUSES AND DC LINES!
