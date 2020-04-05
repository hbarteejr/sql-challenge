CREATE Table "EmployeeDept"

("Emp_no" INTEGER NOT NULl, 
"Dept_no" INTEGER NOT NULL,
"From_date" INTEGER NOT NULL,
"To_date" INTEGER NOT NULL
CONSTRAINT "pk_EmployeeDept" PRIMARY KEY (
        "Emp_no"
     )
);
  
CREATE Table "Department"
("Dept_no" INTEGER
"Dept_name" VARCHAR
CONSTRAINT "pk_Department" PRIMARY KEY (
        "Dept_no"
     )
);
 
CREATE Table "ManagerDept"
("Dept_no" INTEGER
"Emp_no" INTEGER
"From_date" INTEGER 
"To_date" INTEGER
CONSTRAINT "pk_ManagerDept" PRIMARY KEY (
        "Dept_no"
     )
);

CREATE Table "Employees"
("Emp_no" VARCHAR
"Birth_date" INTEGER
"First_nam" VARCHAR
"Last_nam" VARCHAR
"Gender" VARCHAR
"Hire_date" INTEGER
CONSTRAINT "pk_Employees" PRIMARY KEY (
        "Emp_no"
     )
);

CREATE TABLE "Salaries"
("Emp_no" INTEGER
"Salary" INTEGER
"From_date" INTEGER
"To_date" INTEGER
CONSTRAINT "pk_Salaries" PRIMARY KEY (
        "Emp_no"
     )
);

CREATE TABLE "Titles"
("Emp_no" INTEGER
"Title" VARCHAR
"From_date" INTEGER
"To_date" INTEGER
 CONSTRAINT "pk_Titles" PRIMARY KEY (
        "Emp_no"
     )
);

 
 
 
 
