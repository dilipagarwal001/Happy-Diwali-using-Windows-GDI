using System.Drawing; using System.Drawing.Drawing2D; using System.Windows.Forms; 
 
namespace WindowsFormsApp1 
{ 
    public partial class Form1 : Form 
    { 
        private object color; 
 
        public Pen White { get; private set; } 
        public object Color { get => color; set => color = value; } 
 
        public Form1() 
        { 
            InitializeComponent(); 
        }  
        private void Form1_Load(object sender, EventArgs e)         { 
         } 
        protected override void OnPaint(PaintEventArgs e)         { 
            Graphics dc = e.Graphics; 
 	     dc.Clear(System.Drawing.Color.White); 
Rectangle RectangleArea = new Rectangle(550, 250, 300, 35); 
 
//All Brush and pens 
Pen BlackPen = new Pen(System.Drawing.Color.Black, 2); 
Pen RedPen = new Pen(System.Drawing.Color.RosyBrown, 2); 
Pen BrownPen = new Pen(System.Drawing.Color.Brown, 2); 
Brush BrownBrush = Brushes.SandyBrown; 
Brush BlackBrush = Brushes.Black; 
Brush circleBrush = Brushes.Yellow; 
Brush battiBrush = Brushes.LightGoldenrodYellow; 
Brush battinicheBrush = Brushes.PaleGoldenrod; 
Brush gmlaBrush = Brushes.DarkGoldenrod; 
Brush gmlauperBrush = Brushes.Goldenrod;             Brush grBrush = Brushes.LightGreen; 
            Brush windowBrush = Brushes.LightGray; 
            Brush OrangeBrush = Brushes.Orange; 
            Brush oBrush = Brushes.Orange; 
            Brush bBrush = Brushes.CornflowerBlue; 
            Brush bbBrush = Brushes.SandyBrown; 
            Brush faceBrush = Brushes.LightGoldenrodYellow; 
            Brush eyeBrush = Brushes.AliceBlue; 
            Brush blueBrush = Brushes.LightSkyBlue; 
            Brush greenBrush = Brushes.LightGreen; 
            Brush steelBrush = Brushes.LightSeaGreen; 
            Brush yellowBrush = Brushes.LightYellow; 
            Brush pinkBrush = Brushes.DeepPink; 
 
            dc.FillEllipse(windowBrush, 580, 400, 250, 40); 
 	 	 
            GraphicsPath hj = new GraphicsPath();             hj.AddArc(548, 80, 303, 340, 0, 180); 
            dc.DrawPath(BlackPen, hj);             Region ji = new Region(hj);             dc.FillRegion(BrownBrush, ji);             dc.DrawEllipse(BlackPen, 548, 235, 303, 25);             dc.FillEllipse(battinicheBrush, 548, 235, 303, 25);             dc.DrawArc(RedPen, 515, 185, 100, 145, 0, 90);             dc.DrawArc(RedPen, 615, 187, 150, 140, 0, 180);             dc.DrawArc(RedPen, 765, 187, 136, 140, -270, 90); 
            //circles in diya 
            dc.FillEllipse(circleBrush, 610, 335, 25, 25);             dc.FillEllipse(circleBrush, 687, 335, 25, 25);             dc.FillEllipse(circleBrush, 760, 335, 25, 25);             dc.DrawEllipse(BlackPen, 610, 335, 25, 25);             dc.DrawEllipse(BlackPen, 687, 335, 25, 25);             dc.DrawEllipse(BlackPen, 760, 335, 25, 25);             dc.DrawLine(BlackPen, 613, 390, 787, 390); 
            //batti 
            dc.DrawEllipse(BlackPen, 680, 100, 22, 150); 
            dc.FillEllipse(new SolidBrush(System.Drawing.Color.PaleGoldenrod), 680, 100, 
22, 150); 
            dc.FillEllipse(gmlaBrush, 450, 518, 50, 10);             dc.DrawEllipse(BlackPen, 450, 518, 50, 10);             dc.DrawEllipse(BlackPen, 470, 399, 13, 65);             dc.FillEllipse(grBrush, 470, 399, 13, 65);   
 	     dc.FillEllipse(windowBrush, 400, 500, 150, 40); GraphicsPath hp = new GraphicsPath(); hp.AddLine(440, 459, 450, 521); hp.AddLine(450, 521, 500, 521); hp.AddLine(500, 521, 510, 459); 
dc.DrawPath(BlackPen, hp); Region jo = new Region(hp); dc.FillRegion(BrownBrush, jo); dc.DrawEllipse(BlackPen, 439, 457, 72, 10); dc.FillEllipse(grBrush, 439, 457, 72, 10); dc.FillEllipse(gmlaBrush, 890, 518, 50, 10); dc.DrawEllipse(BlackPen, 890, 518, 50, 10); dc.DrawEllipse(BlackPen, 910, 399, 13, 65); dc.FillEllipse(grBrush, 910, 399, 13, 65); 
 	 
 	     dc.FillEllipse(windowBrush, 840, 500, 150, 40);             GraphicsPath hy = new GraphicsPath();             hy.AddLine(880, 459, 890, 521);             hy.AddLine(890, 521, 940, 521);             hy.AddLine(940, 521, 950, 459);             dc.DrawPath(BlackPen, hy);             Region joo = new Region(hy);             dc.FillRegion(BrownBrush, joo);             dc.DrawEllipse(BlackPen, 879, 457, 72, 10);             dc.FillEllipse(grBrush, 879, 457, 72, 10);             dc.DrawRectangle(BlackPen, 1095, 575, 210, 80);             dc.FillRectangle(windowBrush, 1095, 575, 210, 80); 
 
            //Boy code 
 
            GraphicsPath hs = new GraphicsPath();             hs.AddLine(470, 161, 470, 201);             hs.AddLine(470, 201, 512, 201);             hs.AddLine(512, 201, 512, 161);             dc.DrawPath(BlackPen, hs);             Region j = new Region(hs);             dc.FillRegion(OrangeBrush, j); 
 
            //face 
            dc.DrawEllipse(BlackPen, 460, 105, 60, 65);             dc.FillEllipse(faceBrush, 460, 105, 60, 65);             dc.DrawEllipse(BlackPen, 502, 123, 5, 2);             dc.DrawEllipse(BlackPen, 475, 123, 5, 2);             dc.DrawEllipse(BlackPen, 488, 136, 8, 8);             dc.DrawArc(BlackPen, 482, 140, 20, 20, 0, 180); 
 
            dc.DrawRectangle(BlackPen, 470, 201, 42, 30);             dc.FillRectangle(bBrush, 470, 201, 42, 30);             dc.DrawLine(BlackPen, 491, 201, 491, 231);             dc.DrawLine(BlackPen, 480, 230, 483, 256);             dc.DrawLine(BlackPen, 502, 230, 499, 256); 
            //legs 
            dc.DrawEllipse(BlackPen, 460, 255, 25, 10);             dc.DrawEllipse(BlackPen, 499, 255, 25, 10);             dc.FillEllipse(bbBrush, 460, 255, 25, 10);             dc.FillEllipse(bbBrush, 499, 255, 25, 10); 
            //hand 
            dc.DrawLine(BlackPen, 512, 160, 540, 205);             dc.DrawLine(BlackPen, 512, 175, 530, 205); dc.DrawEllipse(BlackPen, 530, 200, 10, 10); dc.DrawLine(BlackPen, 470, 160, 442, 205); dc.DrawLine(BlackPen, 470, 175, 452, 205); dc.DrawEllipse(BlackPen, 442, 200, 10, 10); dc.FillEllipse(bbBrush, 442, 200, 10, 10); dc.FillEllipse(bbBrush, 530, 200, 10, 10); 
//hair dc.DrawLine(BlackPen, 467, 100, 470, 115); dc.DrawLine(BlackPen, 475, 100, 478, 108); dc.DrawLine(BlackPen, 482, 97, 485, 107); dc.DrawLine(BlackPen, 493, 97, 490, 106); dc.DrawLine(BlackPen, 493, 97, 490, 106); dc.DrawLine(BlackPen, 500, 97, 500, 107);             dc.DrawLine(BlackPen, 510, 97, 507, 109);             dc.DrawLine(BlackPen, 520, 100, 513, 115); 
 
            //Boy returns 
             dc.DrawRectangle(BlackPen, 900, 201, 42, 30);             dc.FillRectangle(bBrush, 900, 201, 42, 30);             dc.DrawLine(BlackPen, 921, 201, 921, 231);             dc.DrawLine(BlackPen, 910, 230, 913, 256);             dc.DrawLine(BlackPen, 932, 230, 929, 256); 
 
            GraphicsPath h = new GraphicsPath(); 
            h.AddLine(900, 161, 900, 201); 
            h.AddLine(900, 201, 942, 201); 
            h.AddLine(942, 201, 942, 161);             dc.DrawPath(BlackPen, h);             Region w = new Region(h);             dc.FillRegion(OrangeBrush, w); 
 
            //face 
            dc.DrawEllipse(BlackPen, 890, 105, 60, 65);             dc.FillEllipse(faceBrush, 890, 105, 60, 65);             dc.DrawEllipse(BlackPen, 932, 123, 5, 2);             dc.DrawEllipse(BlackPen, 905, 123, 5, 2);             dc.DrawEllipse(BlackPen, 918, 136, 8, 8);             dc.DrawArc(BlackPen, 912, 140, 20, 20, 0, 180); 
            //legs 
            dc.DrawEllipse(BlackPen, 890, 255, 25, 10);             dc.DrawEllipse(BlackPen, 929, 255, 25, 10);             dc.FillEllipse(bbBrush, 890, 255, 25, 10);             dc.FillEllipse(bbBrush, 929, 255, 25, 10); 
            //hand 
            dc.DrawLine(BlackPen, 942, 160, 970, 205);             dc.DrawLine(BlackPen, 942, 175, 960, 205);             dc.DrawEllipse(BlackPen, 960, 200, 10, 10);             dc.DrawLine(BlackPen, 900, 160, 872, 205);             dc.DrawLine(BlackPen, 900, 175, 882, 205);             dc.DrawEllipse(BlackPen, 872, 200, 10, 10);             dc.FillEllipse(bbBrush, 872, 200, 10, 10);             dc.FillEllipse(bbBrush, 960, 200, 10, 10); 
            //hair 
            dc.DrawLine(BlackPen, 897, 100, 900, 115);             dc.DrawLine(BlackPen, 905, 100, 908, 108);             dc.DrawLine(BlackPen, 912, 97, 915, 107);             dc.DrawLine(BlackPen, 923, 97, 920, 106); dc.DrawLine(BlackPen, 930, 97, 930, 107); dc.DrawLine(BlackPen, 940, 97, 937, 109); dc.DrawLine(BlackPen, 950, 100, 943, 115);  
//house 
Point[] points = new Point[] { new Point(1000, 200), new Point(1150, 90), new 
Point(1300, 200) }; 
            Point[] points8 = new Point[] { new Point(1030, 190), new Point(1150, 105), new Point(1270, 190) }; 
             dc.DrawPolygon(BlackPen, points);             dc.FillPolygon(pinkBrush, points);             dc.FillPolygon(yellowBrush, points8);             dc.DrawRectangle(BlackPen, 1050, 201, 200, 200);             dc.FillRectangle(blueBrush, 1050, 201, 200, 200);             dc.DrawRectangle(BlackPen, 1115, 250, 70, 151);             dc.FillRectangle(steelBrush, 1115, 250, 70, 151); 
 
            //window 
            dc.DrawRectangle(BlackPen, 1060, 250, 40, 40);             dc.FillRectangle(windowBrush, 1060, 250, 40, 40);             dc.DrawRectangle(BlackPen, 1070, 260, 20, 20);             dc.DrawRectangle(BlackPen, 1200, 250, 40, 40);             dc.FillRectangle(windowBrush, 1200, 250, 40, 40);             dc.DrawRectangle(BlackPen, 1210, 260, 20, 20);             dc.FillEllipse(BlackBrush, 1120, 320, 6, 6);  
            //Tree 
            dc.FillEllipse(greenBrush, 15, 320, 450, 45); 
            Point[] points1 = new Point[] { new Point(75, 340), new Point(85, 340), new Point(70, 120) }; 
            Point[] points2 = new Point[] { new Point(135, 340), new Point(145, 340), new 
Point(130, 50) }; 
            Point[] points3 = new Point[] { new Point(195, 340), new Point(205, 340), new Point(190, 120) }; 
            Point[] points4 = new Point[] { new Point(255, 340), new Point(265, 340), new 
Point(250, 70) }; 
            Point[] points5 = new Point[] { new Point(325, 340), new Point(335, 340), new Point(320, 120) }; 
            dc.FillPolygon(BrownBrush, points1);             dc.FillPolygon(BrownBrush, points2);             dc.FillPolygon(BrownBrush, points3);             dc.FillPolygon(BrownBrush, points4);             dc.FillPolygon(BrownBrush, points5); 
 
            //quotes 
            dc.DrawString("-- Save Trees, They will save you", new Font("Arail", 17), new SolidBrush(System.Drawing.Color.DarkGoldenrod), new Point(80, 410)); 
            dc.DrawString("-- Don't Act mean, Go Green", new Font("Arail", 17), new SolidBrush(System.Drawing.Color.DarkGoldenrod), new Point(80, 450)); 
            dc.DrawString("Celebrate An Eco Friendly Diwali This Year", new Font("Arial", 
20), new SolidBrush(System.Drawing.Color.LightSteelBlue), new Point(432, 540));             dc.DrawString("-- Happy Diwali --", new Font("Arial", 20), new SolidBrush(System.Drawing.Color.LightSteelBlue), new Point(582, 580));             dc.DrawString("HAPPY DIWALI", new Font("Comic Sans MS", 40), new SolidBrush(System.Drawing.Color.DarkBlue), new Point(512, 10)); 
            dc.DrawString("--- Say No To Crackers ---", new Font("Goblin One", 17), new SolidBrush(System.Drawing.Color.DarkGoldenrod), new Point(560, 455));             dc.DrawString("--- Dilip Agarwal ---", new Font("Arail", 17), new SolidBrush(System.Drawing.Color.DarkGoldenrod), new Point(1100, 580));             dc.DrawString("-- 15BIT0309 --", new Font("Arail", 17), new 
SolidBrush(System.Drawing.Color.DarkGoldenrod), new Point(1120, 610)); 
 
        } 
    } 
} 
