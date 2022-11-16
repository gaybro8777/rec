[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Sensor](../../../Sensor.md) > [Air_Quality_Sensor](../../Air_Quality_Sensor.md) > [Particulate_Matter_Sensor](../Particulate_Matter_Sensor.md) > [TVOC_Sensor](#)
# TVOC_Sensor

**Display name:** TVOC Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:TVOC_Sensor;1

---

## Child interfaces
* [TVOC_Level_Sensor](TVOC_Level_Sensor.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Air_Quality_Sensor](../../Air_Quality_Sensor.md):** lastKnownValue
* **[Point](../../../../Point.md):** aggregate, customTags, externalIds, hasQuantity, hasSubstance, name

---

## Target Of
### General
* [Point](../../../../Point.md).isPointOf
* [Agent](../../../../../Agent/Agent.md).owns
* [Space](../../../../../Space/Space.md).isLocationOf
* [Equipment](../../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../../Information/Document/Document.md).url
* [EquipmentCollection](../../../../../Collection/Equipment-.md).feeds
* [Lease](../../../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../../Asset/Asset.md).hasPoint
* [EquipmentCollection](../../../../../Collection/Equipment-.md).hasPoint
* [ExceptionEvent](../../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../Event/Point-/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).producedBy