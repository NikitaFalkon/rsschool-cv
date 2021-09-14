# Nikita Sokolovsky

## **Junior Frontend-Backend Developer**

## Contact information:
* **Phone:** +375 29 1782359
* **E-mail:** mikita.falcon@gmail.com
* **Telegram:** @CodeOrange

## **Some words about myself**
Highly motivated junior developer with experience in creating web applications. I have a good soft skills and wishing to discover something new.
Also i have internship experience in IT (not so positive, but i don't give up). And i have a parrot, i don't know why i'm telling you about that but i think it's very important information.

## **Skils**
* Java, Spring(SpringMVC, SpringBoot, SpringSecurity...), Maven
* Html, CSS, Thymeleaf
* SQL, MySQL, H2, Hybernate
* JaxB, W3C, Jasper
* VS Code, IntelliJ IDEA

## **Code Example** 
 **Peak array index KATA from CODEWARS:** 
 *In this little assignment you are given a string of space separated numbers, and have to return the highest and lowest number.*
```function highAndLow(numbers) {
    let high = parseInt(numbers);
    let low = parseInt(numbers);
    let str = '';
    
    for(let i = 0; i < numbers.length; i++) {
        if(numbers[i] !== " ") {
            let h = numbers[i];
            str = str + h;
        }
        
        if(numbers[i] == " " || i+1 == numbers.length) {
            if(low > parseInt(str)) low = parseInt(str);

            if(high < parseInt(str)) high = parseInt(str);

            str = ''
        }
    }

    return high + " " + low;
}
```
## **Education**
Student, Yanka Kupala State University of Grodno (Faculty of Mathematics and Informatics)

## **English level**
B1-B2 (I attended English courses during this summer and have some practise in communication with native speakers)
