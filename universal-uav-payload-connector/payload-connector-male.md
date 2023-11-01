# Payload Connector (Male)



<figure><img src="../.gitbook/assets/20231030_235255.jpg" alt=""><figcaption></figcaption></figure>



## IO Pinouts

### UART

**Connector Type:** JST GH 6-pin

<figure><img src="../.gitbook/assets/UART IO Schematic.png" alt=""><figcaption></figcaption></figure>

### USB

**Connector Type:** JST GH 4-Pin



<figure><img src="../.gitbook/assets/USB IO Schematic.png" alt=""><figcaption></figcaption></figure>

### CAN BUS

**Connector Type:** JST GH 4-Pin

<figure><img src="../.gitbook/assets/CAN BUS IO Schematic.png" alt=""><figcaption></figcaption></figure>



### PWM (1-4)

**Connector Type:** JST GH 3-Pin

<figure><img src="../.gitbook/assets/PWM IO Schematic.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
There are 4 PWM Outputs on the connector board (Numbered 1 through 4).
{% endhint %}

## Flight Batt

**Connector Type:** XT-30 Female

{% hint style="warning" %}
This is unregulated power directly from the flight battery! Do not pull exceed 5 amps continuously or 8 amps burst currents.
{% endhint %}

## Files

### PCB Fab Specifications

| Specification     | Dimension/setting |
| ----------------- | ----------------- |
| **PCB Layers**    | 2                 |
| **PCB Thickness** | 1.2 mm            |

### Gerber File

{% embed url="https://drive.google.com/file/d/15yGzmYnBwSNRk8nLHRvMF4qbwZ0yDygx/view?usp=sharing" %}

## Bills of Material



<table><thead><tr><th>Component Name</th><th data-type="number">Quantity</th><th>Link</th></tr></thead><tbody><tr><td>JST-GH 6-Pin</td><td>1</td><td><a href="https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM06B-GHS-TBT/807804">https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM06B-GHS-TBT/807804</a></td></tr><tr><td>JST-GH 4-Pin</td><td>3</td><td><a href="https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM04B-GHS-TBT/807802">https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM04B-GHS-TBT/807802</a></td></tr><tr><td>JST-GH 2-Pin</td><td>4</td><td><a href="https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM02B-GHS-TBT/807800">https://www.digikey.com/en/products/detail/jst-sales-america-inc/BM02B-GHS-TBT/807800</a></td></tr><tr><td>XT-30 Female</td><td>1</td><td><a href="https://www.digikey.com/en/products/detail/dfrobot/FIT0586/9559255">https://www.digikey.com/en/products/detail/dfrobot/FIT0586/9559255</a></td></tr><tr><td>Pogo Pin</td><td>24</td><td><a href="https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/0906-4-15-20-75-14-11-0/1147052">https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/0906-4-15-20-75-14-11-0/1147052</a></td></tr></tbody></table>
