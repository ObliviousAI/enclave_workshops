<img align="right" height="28" src="https://oblv.io/badge" alt="OBLV: Made for Enclaves">

# The Enclave Workshop Series 📺

This repository is composed of a series of workshops on the theory and practice of using secure enclaves as a privacy enhancing technology (PET). If you have never come accross the concept of a secure enclave, not to worry as we will eneavour to start right from the beginning.

Enclaves, also known as trusted execution environments (TEEs) or confidential compute (CC), can be motivated by multiple drivers, including:
  
![](https://img.shields.io/badge/-Algorithmic%20Transparency-%23FFF3B5) <sup>Proving how data was processed</sup>

![](https://img.shields.io/badge/-Enhanced%20Security%20Transparency-%23FFC17A) <sup>Minimizing the attack surface of data throughout its life cycle</sup>

![](https://img.shields.io/badge/-Multiparty%20Computation-%231191AB) <sup>Brokering trusted computation between multiple parties who each input either data or algorithms</sup>

![](https://img.shields.io/badge/-Secure%20SaaS-%23515991) <sup>Gaurenteeing to SaaS consumers their queries and data will never be seen by or logged by the SaaS providers</sup>

In the workshops below, we will tage each workshop with the above tags so you can easily navigate towards topics most relivent to you. We will also use one more tag which will be used for generic fundamental topics in enclaves:

![](https://img.shields.io/badge/-Core%20Concept-%23C270A9) <sup>A fundamental or core concept to enclaves</sup>

## Workshops

### Workshop 1: Enclave Fundamentals 

![](https://img.shields.io/badge/-Core%20Concept-%23C270A9) ![](https://img.shields.io/badge/-Multiparty%20Computation-%231191AB)

<sup>_Workshop Length Estimate:_ 30 minutes.<sup>

A special thank you to the collaboration with Sebastián Ramírez Montaño of:

[![](https://img.shields.io/badge/-FastAPI-1D9385?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAABVlBMVEUAAAAAkpIGmIwFmYoFmYsFmYsFmYsFmIsGmosAnYkHmo0FmYwFmYsFmosHmIoAjo4FmYoFmYsGmYsAn4AFmYsFmIoAmY8Fl40EmYsGm4sAlYoFmYsFmYsGmIoFmYsFmYsFmYsGmIoFmYoFmYsFmYsFmYsFmYsFmYsGmYoAlZUIlo8GmYwFmYsAkpIFmYsEmYsJl44GmY4AnoYFmYsGmIsFmYsFmooGmosFmYsGmYtOt60Vn5Kz4NyN0cqy39skppr3%2FPuc19Go29f%2F%2F%2F%2BHzsc6r6T%2B%2F%2F9zxr6%2B5eFevbRTua9KtasJm43W7uw0rKFtw7t9ysJpwrkcopUSnpHo9vXX7%2ByIz8hMtqwfpJf1%2B%2Fqk2tX9%2Fv42raJnwbjy%2Bvmh2dP6%2Ff32%2B%2FshpZgXoJOEzcYrqZ3p9vUTn5FBsadrw7pVurDY7%2B1qwrpQt66Ay8TB5uKS0804rqOQZtRSAAAAOHRSTlMADlmbyur6mlgNJp31nCUJjPuKCNPHGTHjLhjQzIHzlvRXmevp%2BfiYVQwih8YH4uUbLRXBhsiXVsnIqF0AAAFRSURBVHjaVdLTop1BDAXgdWyb27bXrtvUtm3j%2FS%2Fanh%2FJzHc7CGFGRsfGJyYnJ8anpmeg1OzcPNX8wiJ8S8sr9EyursGxuM7YkJGNTaitCapjjG3v6PsJquMnqLZ3EVjbozl5imZ%2FCUeWaU6fOUvHQVDfCs05OU%2FH4S6AOZoLF%2BUSXQlgZJ7mssgVupIzGKW5KiLX6ElhjOr6DRG5SU8a41S35L%2FbdwJ3GdpAhrF790U9uM5QFjnGHop5xEjeLjx%2BIuoy9YKFeCrq2XPGsprk9Rd3Ai9F5BXVBqboGb4WefOWqoBpet6JyHuaIkpJuj6IfPxElSwBC3R9FvlCMwVgcZKOr%2FLtOlWujP9W6fguP2gqOLK2QfPzF021hsBuner3H6pGE5GdbWfrVb0F1e5oo%2Bz%2FXThqB0l6ct0afLuJJFUyXYZSpVShl83lsr3%2BoAT1D8WptzmcHWvkAAAAAElFTkSuQmCC)](https://fastapi.tiangolo.com/)

In this workshop, we'll cover:

1. What are secure enclaves?
2. What types of enclaves are there? ( and a brief history of the domain)
3. How do we write software to deploy to an enclave?
  * How to manage access control.
  * How to allowlist outbound connections.
  * How to make enclaves configureable.
4. How do we configure and deploy a secure enclave?
5. How can we securely connect to an enclave?

[Click here to start the workshop.](./workshops/1_Enclave_Fundamentals/README.md)


### Workshop 2: Synthetic Data from Multiple Private Data Sources

![](https://img.shields.io/badge/-Multiparty%20Computation-%231191AB)

<sup>_Workshop Length Estimate:_ 30 minutes.<sup>

A special thank you to the collaboration with team from:

[![](https://img.shields.io/badge/-OpenDP_SmartNoise-blue?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACMAAAAjCAYAAAAe2bNZAAAHlklEQVR42p1YA7CkzQ69Wtu2bdu2bdu2bdu2bdu2bQ7yclI3r1Lfr91N1ZnP6dNRp8fn34SIfBl%2B9l7Dhg1bNWrUaM2bN29mEtF%2BxhXGecYlxknGCkZ7RkFGeKPLD%2Fp8%2FkQMCZyH%2FvnzZ3sMvnnz5s%2B49fLlS%2FoFucAYyohrdPn%2FLhF%2Fc16bcVu1P3v2jNauXev5%2FPmzm4g8DC8Exy9fvninTJni2bdvn4tv4bnKG0Y%2FRrjfIkREAYHHqIyVRiEGdmHQBw8eCClwUEAeP35MESNGJLYeQQIJASpwZc5fIaQv4JiWcZ0BEQtgQI%2FHQ5CRI0dSly5d6OvXrwRRMuxKunLlCr17944cghcwEch3RgUz8X8lkonxlAFx2cGUzJIlS6h69er0%2Fv17JSNg1wkhvWefGX16LG%2FHdQYrjtE0PliByxKwA7x69Ypu375N9pnL5aJx48bRhg0b8N6%2FEXIbtxezhCR9DakNgR%2F%2F1EHbt29Pp0%2BftspFNm7cSBcvXiSVt2%2FfElQsXrzYWpE%2BfvxIkydPprNnz6oOS%2BgRI5by%2BL9V3G53I2WugyImunfvTunSpaM7d%2B6QCr9LGTJkoKFDh9KPHz8I8vz5c2rVqhVduHCBrMyYMUNInjt3Tsk4XbbUaZ3QjHtqPv1IU7lIkSJUp04dshm0evVqpLgQw7VaAeT0euvWrSCC7HK6G%2FDqJbs4t4%2FK9%2B%2FfO3%2F48IG%2BffvmURMDGAiC2SJgr169SqqMa4qksloGWXT%2F%2Fn18h%2BfQRc2bN6dJkyZp1ukznKo11Tor1SohX7x4cRSpOnHiRJd%2BqAIFCE5UXF4CiN8lyOvXr6lx48ZifhArWbIkBrYWADnJOFsW9NvZs2dT4sSJvVwgpSqwZAaZXGwB7%2B7du71btmzxIjVv3LhBJ0%2BepE%2BfPpF12alTpyhp0qR0%2Fvx5IZY8eXJatGgRXb58mfz8%2FGjv3r1CbMWKFXTr1i1njIglQQpWrFy5MuJJrYP7XUCmvaayumXlypXia8wcA6B%2BQFDMmjZtSunTp6d79%2B7R2LFjqV%2B%2FfogJvC%2BTmDt3rpzDtWqRu3fv0oQJEyhz5sy4D%2FcjU7Umqcn2gsyaQDIenQVmd%2BLECercubMo1kCFPH36lHLlykVDhgyRmVWqVIl69OhBLVq0oOXLl8v7bGEMJO5dsGCB3MuTJw8tW7bMVmen5d6BzFm97%2FQt3HTs2DHCWoRYGTFihAy0Z88eybCyZctKisePH58qVqxIKVOmpGnTptHhw4cl7Q8dOkQ7d%2B4Ukg8fPhRyGocKKyDzUsnQvwisheKVJEkSatCgAVWrVk1mHBAQQP7%2B%2FnKeM2dOyaAsWbJQzZo1JTZ%2BQ7w%2BNmvgR1gBswBwjozA8dGjRxITO3bsoGbNmsngESJEABFBiBAhKGjQoJQpUyaaOXOmZJl%2Bp3pUr%2BqGy%2BFOFR9dgxCkWm3z5csncaHInTs3Zc2aFRCroABGihRJCPn6%2BgpgIVwXKlRIrFOqVCkhliNHDrGY1Zc3b16xXoUKFejmzZsaI%2BImXMGfXqwfmPmuXbsUcg2%2Fc%2BpLLGBNUsuECRMGKS1kQoUKJfeQMXDngQMHaP%2F%2B%2FVaHU6%2FEFIqtJbPDLgPOSLcxA0Jt2rTBzDBzGRyAizRmihYtCiDTdD37ZQGZsXaB1GUAwDlW4%2B3bt1Pp0qVlwMGDB9O2bdvkGkUPAQ3rwJXBggWjWbNmIYVBTN4fNWqUxBovOZic1Y1rmzhXQKaCXUWtoMpWrVpVSUjlRZ1AoUPcDB8%2BXKxQr149atu2raR%2B9OjRpXo%2FefKEVq1aRSVKlMD3SG8hYURTW29OAJkEqNTykAVrEMr5tWvXJKg3bdokJOAmyMKFC6Fclobp06dLv4POD4F66dIlateuHfXq1UuzRDJmzZo1qOTQjx4I7%2BkCa8kU8YEw40VEhMh2RY4cWQY7cuSIM3ak2OEZ2ge4r1atWnALLIH7qNoojij%2FmIhaQl0PPVhM8S6qNr5TImfZC2GFDGdSHrgJDdL69eu98LFWS1WI9kHdhVmht8E1CMKaBQsWpPnz5%2BsqjwCGFTVW1CVwsyQCbwYJdoDVWbo6G%2FF5ztixSpCGvXv3FhIQtKL4DCs2hGsLMk0XVUwKzxHsGqyAbVM9XEpQFK%2FrzlN7YBzjMB6ZzLINNayBJknvIUART1on0IgjhmAJbVnRoGt8qR6F12RRGTWK0zqVjFVgEskCLP%2Fo3JzbFhUdHFZD4Oo7yEZUdbSfSsTsoeDOUc6ttHO70oEBQRB7cAvZooPoaj5v3jy6fv06qeA54ungwYOWNLJQJ2KJQDaqV%2FSo4nRZR1RPPkXf4sbg1hpITTxDHKlgwGLFiuF9bcoFKrovN0RCWyP8ExlxGVfY%2Fkg%2FpDCUsLhwVPNj3XHuKM%2BcOaMdno03xJ%2F16YRf%2FUfCmiwEN1b5ObX3OPbMbm3EVMw%2BCwUSGYUbHkdVv8uo6AyLXxHnTrMBsvufFlF1H%2FricOHCadyoXEUdYYRTvcA%2FDswFKggjpAWnbUhuzEMDeIeX%2FXA842KcupM5WG%2BgsBmAHAqalxt2BPdTfmcxv1%2BPYy8uvuc1KhhvS0KzXjOOnGOcoAz%2F%2FwHhJgAbxX1etQAAAABJRU5ErkJggg%3D%3D)](https://smartnoise.org/)

In this workshop, we'll cover:

1. A brief recap of enclave fundamentals.
2. An introduction to (differentially private) synthetic data.
3. Why connect sensitive data sources in an enclave? 
4. A walk-through of building and interacting with a (differentially private) synthetic data enclave service.
5. Comparing the utility of enclave-generated joint synthetic data with synthetic data generated.

[Click here to start the workshop.](./workshops/2_Synthetic_Data_from_Multiple_Private_Data_Sources/README.md)


### Workshop 3: Offering SaaS Services via Enclaves

![](https://img.shields.io/badge/-Secure%20SaaS-%23515991)

<sup>_Workshop Length Estimate:_ 30 minutes.<sup>

In this workshop, we'll cover:

1. A brief recap of enclave fundamentals.
2. Why deploy a SaaS via enclaves?
3. Example application: Inference-as-a-service
4. Example application: Privacy-ensured surveys

This workshop is coming soon. **Star / watch this repo to be notified when the next update will be live.**


