<h1 align="center">
Работа с git и bash
</h1>


<h2 align="left">
<details>
 
  <summary>Задача 1</summary>

1. cd ~

2. pwd

3. mkdir test1

4. cd test1

5. touch 1 2 3

6. ls

7. cd ~

8. mkdir test2

9. rm -r test2

10. rm test1/2

11. mkdir ~/test3 

    touch ~/test3/1 ~/test3/2

12. rm -r ~/test3

13. mkdir ~/test4

14. mv test1/1 test1/3 ~/test4

15. echo "line" >> test4/1

    echo "line" >> test4/1

    echo "line" >> test4/1

16. cat test4/1

17. echo "line" >> test4/3

    echo "line" >> test4/3

    echo "line" >> test4/3

18. cat test4/1 test4/3

19. nano ~/test4/1 

</details>
</h2>

<h2 align="left">
<details>
 
  <summary>Задача 2</summary>

1. cd ~

2. mkdir test3 

3. echo -e "row1\nrow2\nrow3\nrow4" > test3/4

   echo -e "row1\nrow2\nrow3\nrow4" > test3/5

   echo -e "row1\nrow2\nrow3\nrow4" > test3/6

4. grep "row2" test3/5

5. grep -r "row" test3

6. grep -c "row" test3/6

7. find test3 -name "5"

8. find test3 -name "5" -exec rm {} \;

9. echo "test" >> test3/4

10. sed -i 's/test/fail/g' test3/4

11. echo "test" >> test3/4

12. ps aux

13. kill 1974

14. ping artsiomrusau.com

15. ping -c 5 artsiomrusau.com

16. curl -X GET "https://petstore.swagger.io/v2/pet/findByStatus?status=available"

17. curl -X POST "https://petstore.swagger.io/v2/user" -H "Content-Type: application/json" -d '{"id": 0, "username": "newcat", "firstName": "Test", "lastName": "Testovich", "email": "test_testovich@example.com", "password": "1password2", "phone": "1234567899", "userStatus": 0}'


</details>
</h2>
