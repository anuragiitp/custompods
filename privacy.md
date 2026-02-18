# Custom Pods Privacy Policy

This Privacy Policy ("Policy") explains how data is handled when you use any Custom Pod ("Pod") within an Adobe Connect meeting ("Meeting"). Your privacy is important, and the Pods are designed to minimize data collection.

## Overview

The Custom Pod itself does not receive, collect, store, or process personal data when used for its intended purpose inside a meeting, except when you explicitly use optional features that connect to external services (such as the AI Assistant).

No tracking, analytics, profiling, or behavioral monitoring is performed by the Pod.

Data handling may occur only in limited cases where you explicitly initiate an external action, as described in this Policy.

## Platform and SDK Data Flow

Custom Pods use the Adobe Connect HTML SDK to communicate with the Adobe Connect server and meeting participants.

When you interact with a Pod in a Meeting:

- Content entered into the Pod
- Actions taken within the Pod
- Messages or files shared through the Pod

may be transmitted to the Adobe Connect server and other meeting clients as part of normal meeting functionality.

This data flow is controlled by the Adobe Connect platform, not by the Pod provider.

## Meeting Data That May Be Used by the Pod

To function correctly within a meeting, the Pod may access or use:

- Meeting-specific user identifiers
- Adobe Connect user identifiers
- Display names used in the meeting
- Content entered into the Pod interface

This data is used only to enable Pod features and real-time collaboration behavior within the meeting environment.

The Pod does not export this data outside the meeting platform, except when you explicitly use the optional AI Assistant feature described below.

## Optional AI Assistant Feature

Some Pods include an optional AI Writing or Diagram Assistant that connects to third-party Large Language Model (LLM) services. This feature is disabled by default and only activates when a user explicitly configures it.

**When you use the AI Assistant:**

- Document content, selected text, or diagram data from the Pod may be sent to the configured AI service endpoint for processing.
- The AI service provider receives and processes this content according to their own privacy policy and terms of service.
- Conversation context (recent prompts and summaries) may be included in requests to provide continuity.

**Supported AI providers include:**

- Azure OpenAI
- OpenAI
- Anthropic (Claude)
- Custom user-specified endpoints

**Configuration and credentials:**

- AI provider settings (endpoint URL, model name, API key) are stored only in the browser's session storage.
- Settings are not transmitted to Adobe Connect servers or to the Pod provider.
- Settings are cleared when the browser session ends.

**Important:**

- The Pod provider does not operate, control, or have access to any AI service.
- The Pod provider does not receive, store, or have visibility into content sent to AI services.
- Users are responsible for ensuring their use of AI services complies with their organization's data policies.
- Data sent to AI providers is governed by those providers' respective privacy policies.

## Third-Party Content Delivery (CDN)

The Pods load open-source JavaScript libraries from third-party content delivery networks (CDNs) each time the Pod is opened. These CDN servers may include:

- `cdn.jsdelivr.net`
- `esm.sh`
- `app.diagrams.net`

When these resources are loaded, the CDN servers may automatically receive standard technical information such as:

- IP address
- Browser type and version
- Referrer URL
- Date and time of request

This is standard web behavior for loading external resources and is not controlled by the Pod provider.

## Situations Where Additional Data May Be Transmitted

Limited technical data may be transmitted only when you explicitly choose to:

- Check for updates through an update feature
- Visit an external website linked from the Pod
- Contact support or send a direct inquiry

These actions are user-initiated and optional.

## Automatically Collected Technical Data (External Services Only)

If you choose to visit an external website or use an update-check feature, standard technical information may be logged by those servers, such as:

- IP address
- Browser type and version
- Device and operating system information
- Date and time of access
- Pages visited

This is standard web server logging and applies only to those external services.

## Voluntarily Provided Information

If you contact support or send inquiries, any information you provide (such as your email address or message content) will be used only to respond to your request.

You may request that such communications not continue at any time.

## Data Removal

Data transmitted within meetings through the Pod is stored and managed by the Adobe Connect platform. Removal of such data should be performed using the tools and procedures provided by Adobe Connect for clearing Pod or meeting data.

Data sent to AI service providers is subject to the data retention and deletion policies of those providers. The Pod provider has no ability to delete data from third-party AI services.

## Third-Party Platforms and SDKs

The Pod relies on third-party platforms and SDKs (including the Adobe Connect HTML SDK) that are not operated or controlled by the Pod provider.

Their data practices and privacy controls are governed by their own policies. The Pod provider is not responsible for third-party privacy practices.

## Changes to This Policy

This Privacy Policy may be updated from time to time to reflect technical, legal, or operational changes. Updated versions will be posted at the same location where this Policy is made available.

Continued use of the Pod after updates are posted indicates acceptance of the revised Policy.

## Contact

For privacy-related questions or concerns, please contact the Pod provider or the organization that supplied the Pod to you through their official support channel.
