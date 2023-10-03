using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace dikdörtgen_alan_çevre
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnHesapla_Click(object sender, EventArgs e)
        {
            int kenar1, kenar2, alan, cevre;

            kenar1 = Convert.ToInt32(txtUkenar.Text);
            kenar2 = Convert.ToInt32(txtKkenar.Text);

            alan = kenar1 * kenar2;
            cevre = kenar1 * 2 + kenar2 * 2; 

            lblAlan.Text = "Alan: " + alan.ToString();
            lblCevre.Text = "Çevre :" + cevre.ToString();

        }

    }
}
