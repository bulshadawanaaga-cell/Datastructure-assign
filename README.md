
using System;

abstract class Lecturer
{
    private string lecturerId;
    private string name;

    public Lecturer(string lecturerId, string name)
    {
        this.lecturerId = lecturerId;
        this.name = name;
    }

    public string GetLecturerId()
    {
        return lecturerId;
    }

    public string GetName()
    {
        return name;
    }

    public void SetName(string name)
    {
        this.name = name;
    }

    public abstract double CalculateSalary();

    public abstract void DisplayInformation();
}
