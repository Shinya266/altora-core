
Public API Example

This is a conceptual example.

The private implementation is not included.

Request

POST /v1/altora

{
"message": "A signal was detected. Is this permission to act?",
"trace": true
}

Response

{
"output": ["F13", "F14"],
"bridge": "I=nrm;T=T06;P=1;F=F13,F14;A=A02;R=R01;S=none;X=0;G=0;O=0",
"meta": {
"router": {
"requested_useCore": true,
"final_useCore": false,
"reason": "local_only_fallback",
"fallback_class": "local_only"
},
"guardrails": {
"execution_permission": false,
"gate_permission": false,
"oracle_permission": false,
"human_review_required": true
}
}
}
