CREATE TABLE PERSONS (  
    name VARCHAR(50) NOT NULL,  
    surname VARCHAR(50) NOT NULL,  
    age INT NOT NULL,  
    phone_number VARCHAR(15),  
    city_of_living VARCHAR(50),  
    PRIMARY KEY (name, surname, age)  
);  

SELECT name, surname  
FROM PERSONS  
WHERE city_of_living = 'MOSCOW';  

SELECT *  
FROM PERSONS  
WHERE age > 27  
ORDER BY age DESC;  