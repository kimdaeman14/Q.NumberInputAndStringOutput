# Q.NumberInputAndStringOutput



## *특정한 달을 숫자로 입력 받아 문자로 반환해주는 함수 (1 = "Jan" , 2 = "Feb")*

````
func inputNumberMonthReturn(number:Int) {
    switch number {
    case 1:
        print("1월")
        return
    case 2:
        print("2월")
        return
    case 3:
        print("3월")
        return
    case 4:
        print("4월")
        return
    case 5:
        print("5월")
        return
    case 6:
        print("6월")
        return
    case 7:
        print("7월")
        return
    case 8:
        print("8월")
        return
    case 9:
        print("9월")
        return
    case 10:
        print("10월")
        return
    case 11:
        print("11월")
        return
    case 12:
        print("12월")
        return
    default:
        print("잘못된 입력입니다.")
    }
}

inputNumberMonthReturn(number: 1)
inputNumberMonthReturn(number: 3)
inputNumberMonthReturn(number: 5)
inputNumberMonthReturn(number: 10)
inputNumberMonthReturn(number: 11)
````


````
func Calender(_ num: Int) -> String{
    let calList = [1:"jan", 2:"feb",3:"mar",4:"apr",5:"may",6:"june",7:"july",8:"aug",9:"sep",10:"oct",11:"nov",12:"dec"]

    guard num > 0 , num < 13 else {return "잘못된 값 입니다"}

    return (calList[num]!)
}
print(Calender(8))
````

