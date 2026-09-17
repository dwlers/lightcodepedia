```csv
name,fee,campus
Scout,180,Milwauke
Biscuit,150,MKE
Nova,180,Downtown
```

{: .dataset #dogs save="../module_00/dogs.yaml" }

## 🦮 Dogs
```csv
```

{: .datagrid #wired source="src: str = self.chart.source" height="200" title="🏠 Our dogs, by campus" empty="" }

## 📊 Fees
```csv
```

{: .chart #fees type="bar" x="name" y="fee" source="adoptions" height="260" empty="Nothing arrives here yet — this chart is listening for a part that does not exist." }