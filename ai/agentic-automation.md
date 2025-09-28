# Agentic Automation & Verification
*Automation without guardrails is chaos.*

## 🚩 The Problem
Most companies rush automation → security gaps, compliance issues, or angry customers. If your AI can cancel subscriptions without verification, you’ve already lost.

## 🔧 Framework
- **Session-Based Verification** – Verification tied to session (`call_id` in my Synthflow design).  
- **Multi-Factor Checks** – Email or phone + passphrase. Always two pieces of data.  
- **Scoped Access** – Verification applies only to current session, never persists.  
- **Guardrail Prompts** – Every API response reinforces what AI can/can’t say.  
- **Fail Secure** – If verification fails, automation stops. Period.  

## 📈 Example
At Nulids (Shopify + Recurpay integration), I built a verification flow that:
- Scoped verification to `call_id` only.  
- Required passphrase enforcement before any subscription/order access.  
- Rejected all requests if verification was false.  

Yes, it meant 30+ API calls per convo, but compliance > convenience.

## 💡 Lessons
- Automation without boundaries creates liability.  
- Guardrails must be technical, not just policy.  
- Security and adoption can coexist if you keep flows simple and human-friendly.
