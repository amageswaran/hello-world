# hello-world
Simple hello-world application

* worst jitter occurs at $$\Delta T=0.5 / injected frequency$$
* scan jitter vs time dealy for freq 10KHz to 100KHz
* at some injected freq, internal oscillator components resonate called **squelching**
* at some injected freq, oscillator becomes very sensitive to noise because of **insufficient filtering**

### 12.2.4 Power supply filtering for clock sources
* use RLC filtering - 20dB roll off after below freq,
$$F_{20dB} = \frac{3.2}{(LC)^{1/2}}$$

$$x_{1,2} = {-b\pm\sqrt{b^2 - 4ac} \over 2a}.$$
