# Notes from reading Cures Rules

## ONC -- Real World Testing

* Vendors publish public, annual plans
* Vendors publish public, annnual results --> ACB --> CHPL

## Compliance for Existing Certified API Technology

* I'm unclear on what it means for existing technology developers to "revise their existing API Documentation" -- what specifically needs to change about the docs?

## App Registration

* All systems must be able to *demonstrate* the ability to register a patient-facing app.

But is vetting allowed?

> The practices by all parties (including implementers of Health IT Modules) other than developers of certified Health IT Modules are not in scope for this certification criterion nor the associated Condition and Maintenance of Certification requirements. All other practices associated with third-party application review or “vetting” by implementers must not violate the information blocking provision described in section VIII of this preamble and applicable laws and regulations

Huh. Clarification below that vendors are 

* allowed to review third-party applications the implementer intends to use for its own business use
* are not permitted to review or “vet” third-party applications intended for patient access and use


## App Capabilities

* Appears that support for *all* SMART Core Capabilities is required?
* Unclear why there would be a requirement for things like `need-patient-banner`
* "We have finalized requirements for authentication and authorization for patient and user scopes in § 170.315(g)(10)(v)(A)" -- this should explain requirements for refresh tokens
* Apparently "public clients" aren't guaranteed to get refresh tokens :-((

## TODO
* Review detailed rules on responsibilites for API Users vs API Technology Provider
* "Authenticity verification and registration" -- states rules for verification must be the same "permitted to institute a process to verify the authenticity of API Users so long as such process is objective and the same for all API Users". Presumably this does *not* apply to Patients, even though they may be "API Users"
