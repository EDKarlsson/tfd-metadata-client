# ArcheTuningBoardGroupResponseInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**arche_tuning_board_group_id** | **str** | Arche tuning board group identifier | [optional] 
**descendant_group_id** | **str** | Descendant group identifier (Refer to meta/descendant-group API) | [optional] 
**arche_tuning_board_id** | **str** | Arche board identifier (Refer to /meta/arche-tuning-board API) | [optional] 

## Example

```python
from tfd_metadata_client.models.arche_tuning_board_group_response_inner import ArcheTuningBoardGroupResponseInner

# TODO update the JSON string below
json = "{}"
# create an instance of ArcheTuningBoardGroupResponseInner from a JSON string
arche_tuning_board_group_response_inner_instance = ArcheTuningBoardGroupResponseInner.from_json(json)
# print the JSON string representation of the object
print(ArcheTuningBoardGroupResponseInner.to_json())

# convert the object into a dict
arche_tuning_board_group_response_inner_dict = arche_tuning_board_group_response_inner_instance.to_dict()
# create an instance of ArcheTuningBoardGroupResponseInner from a dict
arche_tuning_board_group_response_inner_from_dict = ArcheTuningBoardGroupResponseInner.from_dict(arche_tuning_board_group_response_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


