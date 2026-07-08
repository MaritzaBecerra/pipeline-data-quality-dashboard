# Data Model

## Feature Classes

### Pipelines (Line)

- PipelineID
- Asset Type
- Name
- Status
- Product
- Diameter
- InstallYear
- Material
- LengthMiles
- PressurePSI

---

### Valves (Point)

- ValveID
- PipelineID
- Status
- ValveType

---

### Stations (Point)

- StationID
- Name
- StationType

---

### Counties (Polygon)

- CountyName
- State

---

## Tables

### Inspections

- InspectionID
- PipelineID
- Date
- Inspector
- Result

### Repairs

- RepairID
- PipelineID
- RepairDate
- Cost