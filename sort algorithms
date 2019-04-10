'''冒泡排序'''
def bubble_sort(number):
    for i in range(len(number)):
        for j in range(len(number)-1,i,-1):
            if(number[j] < number[j-1]):
                number[j],number[j-1] = number[j-1],number[j];
    return number;

'''选择排序'''
def select_sort(number):
    for i in range(len(number)):
        for j in range(i+1,len(number)):
            if (number[i] > number[j]):
                number[i],number[j] = number[j],number[i];
    return number;

'''插入排序'''
def insert_sort(number):
    for i in range(1,len(number)):
        for j in range(0,i):
            if (number[i] < number[j]):
                temp = number[i];
                for t in range(i,j,-1):
                   number[t] = number[t-1];
                number[j] = temp;
                break;
    return number;

number1 = [42,13,2,67,34,21,45,15,8,18,0];
print(bubble_sort(number1));
number2 = [42,13,2,67,34,21,45,15,8,18,0];
print(select_sort(number2));
number3 = [42,13,2,67,34,21,45,15,8,18,0];
print(insert_sort(number3));
