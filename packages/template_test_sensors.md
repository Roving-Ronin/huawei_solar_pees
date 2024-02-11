```yaml
{{ states('input_boolean.inverter_1_1phase') }}
{{ states('input_boolean.inverter_1_3phase') }}
{{ states('input_boolean.inverter_2_1phase') }}
{{ states('input_boolean.inverter_2_3phase') }}
{{ states('input_number.inverter_1_operating_voltage_l1') }}
{{ states('input_number.inverter_1_operating_voltage_m1') }}
{{ states('input_number.inverter_1_overall_factor') }}
{{ states('input_number.inverter_2_operating_voltage_l1') }}
{{ states('input_number.inverter_2_operating_voltage_m1') }}
{{ states('input_number.inverter_2_overall_factor') }}
{{ states('input_number.inverter_1_rated_power') }}
{{ states('input_number.inverter_2_rated_power') }}
{{ states('input_select.inverter_1_1phase_models') }}
{{ states('input_select.inverter_1_3phase_models') }}
{{ states('input_select.inverter_2_1phase_models') }}
{{ states('input_select.inverter_2_3phase_models') }}
{{ states('sensor.inverter_1_rated_power') }}
{{ states('sensor.inverter_2_rated_power') }}
{{ states('input_number.inverter_1_rated_power') }}
{{ states('input_number.inverter_1_rated_power') }}
```