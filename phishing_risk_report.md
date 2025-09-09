# Mini Risk Assessment Report: Phishing Attacks on E-Commerce Company

## 1. Assets

-   **Customer Data:** Payment details, personal identifiable
    information (PII).
-   **Product Details:** Inventory, pricing, supplier information.
-   **Employee Accounts:** Credentials granting access to internal
    systems.

------------------------------------------------------------------------

## 2. Threats

-   **Phishing Attacks:** External attempts to trick employees into
    revealing login credentials or executing malicious actions.

------------------------------------------------------------------------

## 3. Vulnerabilities

-   Misconfigured access controls (potential for privilege escalation).
-   Lack of employee awareness/training on phishing.
-   Limited or absent use of multi-factor authentication (MFA).
-   Inadequate monitoring/logging of suspicious login attempts.

------------------------------------------------------------------------

## 4. Impacts

-   **Customer Data Breach:** Financial fraud, regulatory fines,
    reputational loss.
-   **Product Information Tampering:** Incorrect pricing, disrupted
    inventory, financial damage.
-   **Compromised Employee Accounts:** Extended unauthorized access,
    further exploitation of systems.

------------------------------------------------------------------------

## 5. Risk Matrix

  -------------------------------------------------------------------------------
  Risk Description                           Likelihood   Impact   Risk Level
  ------------------------------------------ ------------ -------- --------------
  Phishing attack leading to stolen          High         High     **Critical**
  credentials                                                      

  Privilege escalation through weak access   Medium       High     **High**
  control                                                          

  Data alteration (customer/product details) Medium       High     **High**

  Lack of phishing awareness among staff     High         Medium   **High**
  -------------------------------------------------------------------------------

------------------------------------------------------------------------

## 6. Mitigation Priorities

1.  **Access Control Improvements**
    -   Enforce least privilege access.
    -   Patch privilege escalation issues.
    -   Require multi-factor authentication (MFA).
2.  **Employee Training & Awareness**
    -   Conduct regular phishing awareness training.
    -   Run simulated phishing exercises.
    -   Create clear reporting procedures for suspicious emails.
3.  **Technical Defenses**
    -   Deploy advanced email filtering and URL scanning.
    -   Implement endpoint detection and response (EDR).
4.  **Monitoring and Response**
    -   Centralize logging and enable real-time alerts for unusual login
        activities.
    -   Maintain an updated incident response plan focused on phishing
        scenarios.

------------------------------------------------------------------------

## 7. Conclusion

Phishing poses a **critical risk** to the e-commerce company due to its
high likelihood and severe potential impact on sensitive customer data
and internal systems. Immediate focus should be on strengthening access
controls and employee awareness, supported by technical defenses and
monitoring.
