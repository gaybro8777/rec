[Index](../../../index.md) > [Point](../../Point.md) > [Sensor](../Sensor.md) > [Duration_Sensor](Duration_Sensor.md) > [Run_Time_Sensor](#)
# Run_Time_Sensor

Measures the duration for which a device was in an active or "on" state


**Display name:** Run Time Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Run_Time_Sensor;1

---

## Relationships

### Inherited Relationships
* **[Point](../../Point.md):** isPointOf

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|map (string->boolean)|False|
### Inherited Properties
* **[Duration_Sensor](Duration_Sensor.md):** lastKnownValue
* **[Point](../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, name

---

## Target Of
### General
* [Point](../../Point.md).isPointOf
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../../Space/Space.md).isLocationOf
* [Equipment](../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [EquipmentCollection](../../../Collection/Equipment-.md).feeds
* [Lease](../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../Collection/Equipment-.md).hasPoint
* [ExceptionEvent](../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/Point-/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy