    id1 = "300833B2DDD901400000000D"
    id2 = "300833B2DDD9014000000012"
    id3 = "300833B2DDD9014000000009"
    id4 = "300833B2DDD9014000000007"
    id5 = "300833B2DDD9014000000013"
    global lap
    lap1 = 0
    lap2 = 0
    lap3 = 0
    lap4 = 0
    lap5 = 0
    name1 = raw_input("ID1: What is your name? ")
    name2 = raw_input("ID2: What is your name? ")
    name3 = raw_input("ID3: What is your name? ")
    name4 = raw_input("ID4: What is your name? ")
    name5 = raw_input("ID5: What is your name? ")
    
    
    Start = raw_input("Do you want to start? ")
    
    if Start == "yes":
        print "3"
        time.sleep(1)
        print "2"
        time.sleep(1)
        print "1"
        time.sleep(1)
        print "go!"
        starttime = time.time()
    
    elif Start == "no":
        print "Bye!"
    
    while True:
        RFID = raw_input("Enter ID Here ")
        if RFID == id1:
            end = round((time.time() - starttime),2)
            lap1 += 1
            print str(name1) + " : " + str(lap1) + " laps : " + str(end)
            if lap1 == 4:
                print "\033[1;31;0mCongratulations!"
                print "\033[1;31;0m" + str(name1) + "'s " + "time is " + str(end) + "\033[0;30;0m"
    
    
        if RFID == id2:
            end = round((time.time() - starttime),2)
            lap2 += 1
            print str(name2) + " : " + str(lap2) + " laps : " + str(end)
            if lap2 == 4:
                print "\033[1;31;0mCongratulations!"
                print "\033[1;31;0m" + str(name2) + "'s " + "time is " + str(end) + "\033[0;30;0m"
    
    
        if RFID == id3:
            end = round((time.time() - starttime),2)
            lap3 += 1
            print str(name3) + " : " + str(lap3) + " laps : " + str(end)
            if lap3 == 4:
                print "\033[1;31;0mCongratulations!"
                print "\033[1;31;0m" + str(name3) + "'s " + "time is " + str(end) + "\033[0;30;0m"
    
    
        if RFID == id4:
            end = round((time.time() - starttime),2)
            lap4 += 1
            print str(name4) + " : " + str(lap4) + " laps : " + str(end)
            if lap4 == 4:
                print "\033[1;31;0mCongratulations!"
                print "\033[1;31;0m" + str(name4) + "'s " + "time is " + str(end) + "\033[0;30;0m"
    
    
        if RFID == id5:
            end = round((time.time() - starttime),2)
            lap5 += 1
            print str(name5) + " : " + str(lap5) + " laps : " + str(end)
            if lap5 == 4:
                print "\033[1;31;0mCongratulations!"
                print "\033[1;31;0m" + str(name5) + "'s " + "time is " + str(end) + "\033[0;30;0m"
    
    #http://ozzmaker.com/add-colour-to-text-in-python/
    #Color
    
