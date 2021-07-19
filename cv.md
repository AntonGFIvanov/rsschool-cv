# Anton Ivanov

- <anton.gf.ivanov@outlook.com>
- +375 29 5489762
- Mogilev, Belarus

Junior Full-Stack Developer.I want to develop as a software engineer. I try to learn and master new knowledge and skills, as well as gain experience. I would be grateful for advice or assistance in development.

## Experience

### **Senior Software Engineer** , **Dec 2020 -- to the present**

Plant "Mogilevtransmash" OJSC "MAZ", Mogilev

- Development of software products for main production and assembly line
- Work with electronic accounting and planning systems

### **Head of IT department** , **Dec 2018 -- Dec 2020**

Plant "Mogilevtransmash" OJSC "MAZ", Mogilev

- Department management.
- Development and implementation of software for the plant.
- Local network development. 

### **Software engineer** , **Jan 2017 -- Dec 2018**

Plant "Mogilevtransmash" OJSC "MAZ", Mogilev

- Development of software products for main production and assembly line
- Work with electronic accounting and planning systems 

### **Operator-adjuster of CNC and semi-automatic machines** , **Nov 2011 -- Jan 2017**

Plant "Mogilevtransmash" OJSC "MAZ", Mogilev

- Ensuring uninterrupted operation of machines and automatic lines
- Development and modernization of programs for CNC machines
- Maintenance and testing of machine tools and automatic lines 

## Projects

``` C#
public partial class FormViewSM : Form
    {
        public static string conString = @"Provider=Microsoft.Jet.OLEDB.4.0;Data Source=c:\TehnoSearch\Base\;Extended Properties=dBASE IV;User ID=Admin;Password=";

        public FormViewSM()
        {
            InitializeComponent();
        }

        // Metods

        #region Метод поиска изделий

        private void SearchIZD()
        {
            comboBoxKodIZD.DataSource = null;

            string stringSQL = $"SELECT IZD FROM NRASV000 GROUP BY IZD";

            comboBoxKodIZD.DataSource = DTselect(stringSQL, conString);

            comboBoxKodIZD.DisplayMember = "IZD";
            comboBoxKodIZD.ValueMember = "IZD";
            comboBoxKodIZD.SelectedIndex = -1;
        }
        #endregion
 ```
 
## Education

### **Belarusian-Russian University, BA Automated Data Processing Systems** **2012 -- 2018**

  - **A1QA** Test Engineer (functional testing) **06.2013 -- 08.2013**
  - **SoftLine** Junior Oracle SQL Developer **06.2017**
