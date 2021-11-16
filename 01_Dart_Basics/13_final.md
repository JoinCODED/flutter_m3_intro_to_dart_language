# final



![img](https://lh4.googleusercontent.com/pabB0FDVEHyLDAnMeEUsDc_1JJufwbszy2obEtOAPE8cKGioqZxg3Ln55X0V2SN_WdmO_4t01gN2H2Yn7Uc8HcRbnSsazob3BYgykb7mTNAGfhps19eG-Co7WqWy1DLMUHOoEBfK)

There is a special keyword called `final`. This is not a final exam yet!





### **Example**

Calculate the area of the circle. Knowing that the area is π * r2. Where π = 3.14. r = 4.



###  **Solution**

![img](https://lh3.googleusercontent.com/2gC3btzu8NeBp0ZSDHmdcMLldLG_YuNkYOZaPPSfupNXj_hhsd0ALB-ESs7NxXyPulywiq5YVXjZ14Pj0Zd2VnRAZE-ehqp1BpF7ByxOFEpB2SCbwIJaSaOuO0KPeDL5rwYaHueq)



But imagine at one time of your application, you change pi by mistake. 

![img](https://lh4.googleusercontent.com/7jXE-0ZmSlRtjnkx5dE5geLUxf3I0plm5eQ07e8Sn4LYDB2aOob1NorplDNrF7SzI9VUHQWoFPQXAC2PWCYkiMZJ6MUqgOAkLZZWMGWR3KpbIbUxH78m_2DF-HFEMyA45CTjU263)



This is not going to generate syntax error. But it should!! pi should always remain constant. That's why `final` was invented. You can lock a variable from getting modified after it gets its first initial value. So no one can ever change it in future. 

**![img](https://lh3.googleusercontent.com/OlzxSblWZbtUwTpT0bJ7YDQs9BFzdaoOdJS4SZC_a-FwDS2oKb2OchFMOrINevynW6_fgjmH2R0aOOzP8Z38HkNaAkgjdk3R15ZOvSWmYukZbJM879bxTEnRWEJssoivL_RIuPKC)**

> Note: how when we defined pi using `final` it threw an error when we tried to modify pi. Now we can know that we're doing something wrong with our application (we're changing pi!).





















