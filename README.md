void STATEValueChanged(object sender, ValueChangedEventArgs e)
{
    Int16 Status = (Int16)this.STATE.Value;
    UInt16 Mode = (UInt16)this.MODE.Value;

    /* ================= 0 ================= */
    if(Status == 0){
        rectangle27.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state0.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state0a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle27.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state0.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state0a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 100 ================= */
    if(Status == 100){
        rectangle28.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state100.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state100a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle28.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state100.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state100a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 101 ================= */
    if(Status == 101 && Mode == 1){
        rectangle29.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state101.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state101a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state101a.Text = "Open No. 01 Tank";
    } else if(Status == 101 && Mode == 2){
        rectangle29.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state101.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state101a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state101a.Text = "Open No. 01 Tank & No. 02 Tank";
    } else {
        rectangle29.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state101.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state101a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 102 CLOSE ================= */
    if(Status == 102){
        rectangle30.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state102.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state102a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle30.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state102.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state102a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 103 ================= */
    if(Status == 103){
        rectangle31.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state103.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state103a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle31.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state103.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state103a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 104 CLOSE ================= */
    if(Status == 104){
        rectangle32.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state104.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state104a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle32.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state104.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state104a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 105 ================= */
    if(Status == 105 && Mode == 1){
        rectangle33.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state105.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state105a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state105a.Text = "Open No. 03 Tank";
    } else if(Status == 105 && Mode == 2){
        rectangle33.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state105.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state105a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state105a.Text = "Open No. 03 Tank & No. 04 Tank";
    } else {
        rectangle33.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state105.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state105a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 106 CLOSE ================= */
    if(Status == 106){
        rectangle34.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state106.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state106a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle34.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state106.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state106a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 107 ================= */
    if(Status == 107){
        rectangle35.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state107.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state107a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle35.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state107.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state107a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }

    /* ================= 108 CLOSE ================= */
    if(Status == 108){
        rectangle36.BrushColor = new NxtControl.Drawing.Color(255,255,0);
        state108.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
        state108a.TextColor = new NxtControl.Drawing.BlinkColor("BlackWhite");
    } else {
        rectangle36.BrushColor = new NxtControl.Drawing.Color(255,255,255);
        state108.TextColor = new NxtControl.Drawing.Color(0,0,0);
        state108a.TextColor = new NxtControl.Drawing.Color(0,0,0);
    }
}
