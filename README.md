# python_probelm
"""1"""
# word ="bhavana"
# vowel_count=0
# const_count =0
# for char in word:
#     if char=="a":
#         vowel_count+=1
#     else:
#         const_count+=1
# print(vowel_count,const_count)

# string =input()
# vowels ="aeiouAEIOU"
# count=0
# for char in string:
#     if char in vowels:
#         count+=1
# print(count)

"""2"""
# s = input("Enter a string: ")
# rev = ''.join(sorted(s, reverse=True))
# print("Reversed string:", rev)
# print(s[::-1])

"""3"""
#sent="my name is bhavana from atp"
#split method

# words =sent.split()
# print("no of:",len(words))

#without split

# sentence = input()
# count = 0
# in_word = False
# for ch in sentence:
#     if ch != " ":
#         if not in_word:
#             count += 1
#             in_word = True
#     else:
#         in_word = False

# print(count)

"4"
# string = input()
# # function:sciling

# # rev =string[::-1]
# # if string==rev:
# #     print("is palindrome")
# # else:
# #     print("is not palindrome")

# rev =""
# for ch in string:
#     rev =ch + rev
# if rev==string:
#     print("palidrome")
# else:
    # print("noy palidrome")

"5"
# str="bhavna"
# rev=str.upper()
# print(rev)
"6"
# list =[1,2,3,6]
# sum=0
# for i in list:
#     sum = i+ sum
# print(sum)

"7"
# listing = [1,2,3,4,5,50,6,0,9]
# listing.sort()
# print(listing)
# print(listing[-1])
# print(max(listing))

"8"
# listing = [1,2,3,4,5,50,6,0,9]
# count=0
# for ch in listing:
#     if ch%2==0:
#       count+=1
# print(count)

# nums = list(map(int, input("Enter numbers: ").split()))
# count = 0

# for n in nums:
#     if n % 2 == 0:
#         count += 1

# print(count)
""
"9"
# list =[1,2,3,4,4,5,5]
# list.reverse()
# print(list)

"10"
# lst = [1,2,3,4,5,6,6,7,8,9]
# num = int(input("Enter the value to check: "))

# found = False

# for ch in lst:
#     if num == ch:
#         found = True
#         break

# if found:
#     print("Exists")
# else:
#     print("Not Exists")



# lst = [1,2,3,4,5,6,6,7,8,9]
# num = int(input())

# if num in lst:
#     print("Exists")
# else:
#     print("Not Exists")
