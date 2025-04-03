# Graph

This is GaugeChart or Half Guague view, handle as per your requirements.

class usage:


        LinearLayout clMainScroll = new LinearLayout(this);
        clMainScroll.setOrientation(LinearLayout.VERTICAL);
        clMainScroll.setLayoutParams(new ViewGroup.LayoutParams(ViewGroup.LayoutParams.MATCH_PARENT, ViewGroup.LayoutParams.WRAP_CONTENT));

        GaugeChart clGaugeChart = GaugeChart();
        clGaugeChart.setBulletColor(Color.GREEN);
        clGaugeChart.setActualValue(85);
        clGaugeChart.setTargetValue(160);
        clGaugeChart.setMinValue(0.0);
        clGaugeChart.setMaxValue(150.0);
        clGaugeChart.setLayoutParams(new LinearLayout.LayoutParams(CLViewUtil.dpToPx(280),CLViewUtil.dpToPx(200)));
        clGaugeChart.setBackgroundColor(Color.WHITE);
        
        clMainScroll.addView(clGaugeChart);
        
        setContentView(clMainScroll);


![GaugeChart.java Example](https://github.com/Rameshkumarpolavarapu/Graph/blob/main/GaugeChart.png)
