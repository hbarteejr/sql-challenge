CREATE TABLE public.department
(
    dept_no character varying(100) COLLATE pg_catalog."default" NOT NULL,
    dept_name character varying COLLATE pg_catalog."default" NOT NULL
)

CREATE TABLE public.employeedept
(
    emp_no character varying(100) COLLATE pg_catalog."default" NOT NULL,
    dept_no character varying COLLATE pg_catalog."default" NOT NULL,
    from_date character varying COLLATE pg_catalog."default" NOT NULL,
    to_date character varying COLLATE pg_catalog."default" NOT NULL
)

CREATE TABLE public.employees
(
    emp_no character varying COLLATE pg_catalog."default" NOT NULL,
    birth_date character varying COLLATE pg_catalog."default" NOT NULL,
    first_nam character varying COLLATE pg_catalog."default" NOT NULL,
    last_nam character varying COLLATE pg_catalog."default" NOT NULL,
    gender character varying COLLATE pg_catalog."default" NOT NULL,
    hire_date character varying COLLATE pg_catalog."default" NOT NULL
)

CREATE TABLE public.salaries
(
    emp_no character varying COLLATE pg_catalog."default" NOT NULL,
    salary character varying COLLATE pg_catalog."default" NOT NULL,
    from_date character varying COLLATE pg_catalog."default" NOT NULL,
    to_date character varying COLLATE pg_catalog."default" NOT NULL
)

CREATE TABLE public.titles
(
    emp_no character varying(100) COLLATE pg_catalog."default" NOT NULL,
    title character varying(100) COLLATE pg_catalog."default" NOT NULL,
    from_date character varying(100) COLLATE pg_catalog."default" NOT NULL,
    to_date character varying(100) COLLATE pg_catalog."default" NOT NULL
)
 
 CREATE TABLE public.managerdept
(
    dept_no character varying COLLATE pg_catalog."default" NOT NULL,
    emp_no character varying(100) COLLATE pg_catalog."default" NOT NULL,
    from_date character varying(100) COLLATE pg_catalog."default" NOT NULL,
    to_date character varying(100) COLLATE pg_catalog."default" NOT NULL
)

 
 
