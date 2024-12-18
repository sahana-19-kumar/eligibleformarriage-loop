# eligibleformarriage-loop
information=[ {"name":"santhosh kumar","age":21,"gender":"male"},
{"name":"vijay","age":23, "gender":"male"},
{"name":"suriya","age":24,"gender":"male"},
{"name":"vishwa","age":21,"gender":"male"},
{"name":"tamil","age":23,"gender":"female"}]

for i in range(len(information)):
    if(information[i]["gender"]=="male"):
        if(information[i]["age"]>21):
            print(information[i]["name"]," eligible for marriage")
        else:
            print(information[i]["name"]," not eligible for marriage")

    elif(information[i]["gender"]=="female"):
        if(information[i]["age"]>18):
            print(information[i]["name"]," eligible for marriage")
        else:
            print(information[i]["name"],"eligible for marriage") 
            else:
   print("  enter valid gender ")
