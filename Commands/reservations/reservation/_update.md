# [Command] _reservations reservation update_

Update the applied scopes, renewal, name, instance-flexibility of the `Reservation`.

## Versions

### [2022-03-01](/Resources/mgmt-plane/L3Byb3ZpZGVycy9taWNyb3NvZnQuY2FwYWNpdHkvcmVzZXJ2YXRpb25vcmRlcnMve30vcmVzZXJ2YXRpb25zL3t9/2022-03-01.xml) **Stable**

<!-- mgmt-plane /providers/microsoft.capacity/reservationorders/{}/reservations/{} 2022-03-01 -->

#### examples

- Update applied scope type
    ```bash
        reservations reservation update --applied-scope-type Shared --reservation-id 10000000-aaaa-bbbb-cccc-200000000001 --reservation-order-id 50000000-aaaa-bbbb-cccc-200000000005
    ```