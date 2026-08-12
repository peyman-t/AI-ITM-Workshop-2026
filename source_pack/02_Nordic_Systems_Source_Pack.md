# Nordic Systems AS — 48-Hour Operations Brief

## Student source pack

**Case status:** Synthetic teaching case. All names, events, numbers, and document identifiers are fictional.  
**Permitted use:** You may paste this material into Sikt KI-Chat, USN Copilot, or another tool you choose. Do not add real personal, employer, research, or confidential information.

## Your task

Prepare a one-page brief for the Operations Director:

> What appears to have happened, what is known and unknown, what should management do in the next 48 hours, and what requires further investigation?

Use only this source pack. Cite a document ID after each factual claim. If the pack does not establish something, write **not established**. Name the human role responsible for each proposed action.

---

## Document NS-01 — Customer escalation

**From:** Operations Manager, Fjord Process Solutions  
**To:** Nordic Systems Customer Service  
**Date:** 7 August 2026, 08:14  
**Subject:** Urgent: repeated E17 shutdown, unit NX-420-B / serial NSX-47A-203

Our NX-420-B unit shut down with alarm E17 on 2 August and again on 5 August. The two interruptions caused about nine hours of lost production in total. The unit was delivered on 18 June and commissioned on 4 July.

Your technician restarted the unit after the first event. After the second event, the technician replaced the inlet filter. The unit is running, but we do not regard two hours of operation as proof that the issue is resolved.

Please provide a written explanation of the cause, the risk of recurrence, and your proposed corrective action by 8 August. We have not quantified our financial loss. We need to know whether continued operation is safe and whether other units at our site may be affected.

---

## Document NS-02 — Field-service report

**Document ID:** FSR-260806-19  
**Technician:** Field Service Engineer A. Lind  
**Site visit:** 6 August 2026, 09:40–13:20  
**Equipment:** NX-420-B / NSX-47A-203

### Observations

- Alarm log showed E17 at 14:32 on 2 August and 05:18 on 5 August.
- Inlet filter appeared dark and partially obstructed. Pressure drop was not measured before removal.
- Filter was replaced with a service-stock filter; removed filter was bagged and left at the customer's maintenance desk.
- Unit restarted and ran for two hours under a reduced production load without a further E17 alarm.
- Ambient temperature at the time of the visit was 27 °C. Ambient temperature during the two shutdowns was not recorded.
- Firmware version and filter production lot were not captured in the service form.
- No physical damage or smoke was observed. The protective shutdown operated as designed.

### Technician assessment

“Restricted inlet airflow is a likely cause, but the observation is not sufficient for a confirmed root cause. Firmware and environmental conditions should also be checked.”

---

## Document NS-03 — Quality dashboard extract

**Prepared by:** Quality Analytics  
**Extract date:** 7 August 2026  
**Population:** 240 active units in the NX-400 product family. Models and configurations are not separated in this extract.

| Month 2026 | Recorded E17 events | Units with an E17 event | “Airflow restriction noted” in field text | Other information |
|---|---:|---:|---:|---|
| April | 2 | 2 | 2 | Firmware not recorded |
| May | 1 | 1 | 0 | Firmware 3.8 confirmed |
| June | 3 | 2 | 3 | Two events were on the same unit; component lots incomplete |
| July | 2 | 2 | 1 | High ambient temperature noted in one case; firmware not recorded |
| **Total** | **8** | **7** | **6** | Categories are not mutually exclusive and do not establish cause |

Quality note: Free-text observations have not been independently validated. “Airflow restriction” may refer to a dirty filter, blocked duct, installation condition, or another restriction. The dashboard counts events, not confirmed failures or root causes. The customer event from August is not included.

---

## Document NS-04 — Engineering bulletin EB-26-14

**Issue date:** 15 July 2026  
**Applies to:** Selected NX-400 control units using firmware 3.8

Engineering reproduced an E17 false trigger on firmware 3.8 when inlet-sensor readings changed rapidly at ambient temperatures above 34 °C. Firmware 3.9 changes the filtering of the sensor signal. It does not disable the protective shutdown.

Production targeted firmware 3.9 for units commissioned from 1 July onward. This was a production target, not a confirmation that every commissioned unit received the update. Field retrofits are not automatic. Verify the installed version before attributing an event to this mechanism.

Engineering has not established whether firmware 3.8 alone can explain all reported E17 events. Airflow restrictions may create a real temperature condition that also activates E17.

---

## Document NS-05 — Supplier quality email

**From:** Quality Manager, NordFilter Components  
**To:** Nordic Systems Supplier Quality  
**Date:** 5 August 2026  
**Subject:** Preliminary response — filter media batch F-221

We tested 30 retained samples from batch F-221 after your question about pressure drop. Four samples were at the upper edge of the contractual tolerance under high-humidity laboratory conditions. All 30 were within the current contractual specification.

This variation could reduce margin in an installation that already has restricted inlet flow. It does not demonstrate that F-221 caused a field shutdown. We are repeating the test and can provide results by 12 August.

We cannot determine whether NSX-47A-203 contains material from batch F-221 because Nordic Systems has not supplied the installed filter lot number.

---

## Document NS-06 — Incident communication procedure OPS-7.2

**Owner:** Director of Operations  
**Effective:** 1 March 2026

1. The Service Manager owns the customer response until an incident owner is formally appointed.
2. Engineering must approve any external statement that names a technical root cause.
3. Supplier fault, fleet-wide corrective action, recall, and financial liability must not be stated before the relevant owners have reviewed the evidence.
4. A protective shutdown is not automatically a safety incident. Safety Engineering must determine the classification when safe continued operation is uncertain.
5. Preserve logs, removed components, configuration records, test conditions, decisions, and customer communications.
6. Within 24 hours of escalation, tell the customer what is verified, what remains under investigation, who owns each action, and when the next update will be provided.

---

## End of source pack

Do not search for Nordic Systems AS: it is fictional. Your result will be judged on traceability, calibrated language, useful action, and explicit human accountability—not on confidence or length.
