
{
  settings: {
    theme: {
      categoryAxis: {
        axisLine: { show: false },
        axisTick: { show: false },
        splitLine: { show: false }
      },
      valueAxis: { axisLine: { show: false } }
    }
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
