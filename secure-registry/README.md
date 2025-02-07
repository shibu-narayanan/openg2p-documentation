# 📋 Registration

## Introduction

In the OpenG2P platform, registration is a series of three processes - intake, recording, and verification. Intake is the process of gathering information from applicants while recording and verification are the processes to add the authenticated information to the [Registry](registry.md). The platform verifies the applicant's details in the background by confirming the identity and demographic details of the applicant digitally.

Registration aims to provide detailed records for [Eligibility Assessment](../beneficiary-management/eligibility.md) in the [Registry](registry.md). It must be noted that at this stage, the people are referred to as applicants or registrants. Once the applicants/registrants pass the eligibility criterion set by the program manager, they become eligible to enrol in the program and are referred to as beneficiaries.&#x20;

This is a pictorial representation of the OpenG2P registration process.

<figure><img src="https://github.com/OpenG2P/openg2p-documentation/raw/10c5eb7b0884c079607f48b07d63088f0a8523c7/.gitbook/assets/registration-process.png" alt=""><figcaption></figcaption></figure>

## Registration approaches

Registration can be carried out via multiple channels such as digital service windows/kiosks, social workers, local registration offices, door-to-door visits, referrals from other programs, etc. The registration approach can be either on-demand or administrative-driven. Three key features distinguish between these two approaches:

#### **Applicant-initiated vs program-initiated**

Whether the registration process was initiated by the applicant (on-demand) or by the program administrator (administrator-driven)

#### **Individual vs group registration**

Whether applicants registered themselves individually (on-demand) or registered as a group/family/household (administrator-driven)

#### **Continuous vs time-bound**

Whether applicants could register at the time of their choosing (on-demand) or had to apply in a specific time window (administrator-driven)

## Registration interfaces

While on-demand and administrative-driven approaches are two distinct models, the registration process operates in a spectrum between these two models. For example, a program may allow the applicants to register individually (on-demand) but may allow them to apply only in a certain time window (administrative-driven). OpenG2P platform has a flexible implementation and through its various [Registration Interfaces](registration-methods/) aims to cater to a combination of approaches across different registration modalities and programs.&#x20;

## Registration features

OpenG2P registration interfaces are key client-facing interfaces. The clients here could be the applicants, social workers, program administrators, program managers, etc. There are the main features offered by these interfaces:

#### **Authentic**&#x20;

The clients log into the system using their MOSIP ID/National ID allowing the information to be verified while it is being recorded. Additionally, logging in using National ID can pre-fill the information fields in an authentic manner.

#### **Always available**

OpenG2P's [Mobile Registration App](registration-methods/offline-registration.md) allows social workers and field registration officers to record the applicant's information without any internet connectivity.&#x20;

#### **Secure**

The applicant's information is encrypted at rest and during transit allowing the information to be secure against malicious attacks.

#### **Privacy-preserving**

The platform allows for consent forms to be filled out and recorded before starting the intake. The recorded information is not used for any purpose other than the explicitly stated purpose in the consent form.&#x20;

#### Customizable intake

The applicant information is filled in using general intake sheets. These intake sheets can be customized per the assessment information required by the program.

#### Notifications

The platform can be configured to send [Notifications](../notifications.md) to the applicants via multiple channels such as email, sms, etc.&#x20;

## Developer References

[**API**](../api.md)

[**Code**](../guides/developer-guides/)

## Guides

## FAQs



<details>

<summary></summary>



</details>





