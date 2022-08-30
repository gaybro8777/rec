[Index](../../../../Index.md) > [Point](../../../Point.md) > [Parameter](../../Parameter.md) > [PID_Parameter](../PID_Parameter.md) > [Proportional_Band_Parameter](Proportional_Band_Parameter.md) > [Entering_Water_Temperature_Proportional_Band_Parameter](#)
# Entering_Water_Temperature_Proportional_Band_Parameter

**Display name:** Entering Water Temperature Proportional Band Parameter<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Entering_Water_Temperature_Proportional_Band_Parameter;1

---

## Relationships

### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|array (string)|False|
### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, lastKnownValue, name

---

## Target Of
### Inherited
* [Asset](../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../Collection/EquipmentCollection.md).hasPoint
* [ActuationEvent](../../../../Event/PointEvent/ActuationEvent.md).targetPoint
* [ExceptionEvent](../../../../Event/PointEvent/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/PointEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint