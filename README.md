# Graph


class usage:


        LinearLayout clMainScroll = new LinearLayout(this);
        clMainScroll.setOrientation(LinearLayout.VERTICAL);
        clMainScroll.setLayoutParams(new ViewGroup.LayoutParams(ViewGroup.LayoutParams.MATCH_PARENT, ViewGroup.LayoutParams.WRAP_CONTENT));

        CLHalfDialChartView clHalfDialChartView = CLHalfDialChartView();
        clHalfDialChartView.setBulletColor(Color.GREEN);
        clHalfDialChartView.setActualValue(85);
        clHalfDialChartView.setTargetValue(160);
        clHalfDialChartView.setMinValue(0.0);
        clHalfDialChartView.setMaxValue(150.0);

        clHalfDialChartView.setLayoutParams(new LinearLayout.LayoutParams(CLViewUtil.dpToPx(280),CLViewUtil.dpToPx(200)));
        clHalfDialChartView.setBackgroundColor(Color.WHITE);
        clMainScroll.addView(clHalfDialChartView);
        setContentView(clMainScroll);
