# exam
namespace exam.project
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string student_Name, student_Surname, depart, lesson;
            float s1, s2, s3, average;

            student_Name = "Göktuğ";
            student_Surname = "Akpınar";
            depart = "Elektronik Haberleşme";
            lesson = "Dijital Elektronik";
            s1 = 85;
            s2 = 90;
            s3 = 100;
            average = (s1 + s2 + s3) / 3;

            Console.WriteLine("Öğrenci adı: " + student_Name);
            Console.WriteLine("Öğrenci soyadı: " + student_Surname);
            Console.WriteLine("Bölüm: " + depart);
            Console.WriteLine("Ders: " + lesson);
            Console.WriteLine("Ders Notu: " + average);

            Console.Read();
        }           
    }   

}
