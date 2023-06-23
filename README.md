# CalculateGrossSalary

The payroll system of an organization involves calculating the gross salary of each type of
employee and the tax applicable to each.
Create the following entity classes as described below.

Class Employee
Fields: id: int, name : String, basicSalary : double, HRAPer : double, DAPer : double
Public Method: calculateGrossSalary() - returns a double
Calculate the gross salary as : basicSalary +HRAPer +DAPer

Class Manager
Fields: id: int, name : String, basicSalary : double, HRAPer : double,DAPer : double,
projectAllowance: double
Public Method: calculateGrossSalary() - returns a double
Calculate the gross salary as : basicSalary +HRAPer +DAPer + projectAllowance

Class Trainer
Fields: id: int, name : String, basicSalary : double, HRAPer : double,DAPer : double,
batchCount: int, perkPerBatch: double
Public Method: calculateGrossSalary() - returns a double
Calculate the gross salary as : basicSalary +HRAPer +DAPer +(batchCount * perkPerBatch)

Class Sourcing
Fields: id: int, name : String, basicSalary : double, HRAPer : double,DAPer : double,
enrollmentTarget: int, enrollmentReached: int, perkPerEnrollment: double
Public Method: calculateGrossSalary() - returns a double.
