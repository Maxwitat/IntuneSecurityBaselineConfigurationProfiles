# IntuneSecurityBaselineConfigurationProfiles
W11 23H2 Security Baselines for Intune as Configuration Profile

Intune includes Security Baselines under Endpoint Security. While this is convenient, it has its disadvantages:

- Since it's not modular, it is challenging to implement exceptions. You will have to duplicate the whole baseline. If you have to deal with a larger number of exceptions, this becomes extremely complicating. Therefore, the implementation as Configuration Profiles splits the baselines up by topic by following the documentation on https://learn.microsoft.com/en-us/mem/intune/protect/security-baseline-settings-mdm-all?pivots=mdm-23h2
- The second advantage of the modular approach is that it allows you to implement the baseline on a step by step approach.

Part 1 of the implementation covers the Windows baseline. The baseline for Defender, Edge, W365 and W365 Apps will follow. I also intend to provide and automated setup.

