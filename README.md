# Employee_data_Analysis
CREATE TABLE employees (
    employee_id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    department VARCHAR(50),
    salary DECIMAL(10,2),
    hire_date DATE,
    city VARCHAR(50),
    performance_rating INT
);

INSERT INTO employees ("employee_id", "first_name", "last_name", "department", "salary", "hire_date", "city", "performance_rating") 
VALUES 
('1', 'John', 'Smith', 'Engineering', '75000.00', '2020-03-15', 'New York', '8'),
('2', 'Sarah', 'Johnson', 'Marketing', '65000.00', '2019-07-22', 'Chicago', '9'),
('3', 'Michael', 'Brown', 'Engineering', '82000.00', '2018-11-05', 'New York', '7'),
('4', 'Emily', 'Davis', 'HR', '55000.00', '2021-01-30', 'Boston', '6'),
('5', 'David', 'Wilson', 'Sales', '70000.00', '2020-09-12', 'Chicago', '8'),
('6', 'Lisa', 'Anderson', 'Engineering', '90000.00', '2017-05-10', 'Boston', '9'),
('7', 'James', 'Miller', 'Marketing', '60000.00', '2022-02-28', 'New York', '7');
