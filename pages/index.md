```sql orders_by_month
select
    date_trunc('month', order_datetime) as month,
    count(*) as orders
from
    orders
group by all
```

<LineChart
  data={orders_by_month}
  x=month
  y=orders
/>

<MySpecialLineChart
  data={orders_by_month}
  x=month
  y=orders
/>



