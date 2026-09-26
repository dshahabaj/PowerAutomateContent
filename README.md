# Power Automate Content

This project contains a presentation deck on Connection References in Power Automate / Power Platform.

## Files
- [ConnectionReference-modern.html](ConnectionReference-modern.html) — interactive slide deck
- [ConnectionRefrence.html](ConnectionRefrence.html) — earlier/simple version of the presentation

## Presentation topic
Connection References are a design pattern used in Power Platform to separate automation logic from the underlying connector authentication. They help with environment portability, governance, safer deployments, and ALM.

## Slide overview
1. Connection References in Power Automate
2. Connector vs Connection vs Connection Reference
3. Why it matters in real projects
4. Architecture and flow of execution
5. Real-time example: leave request approval flow
6. Why teams and Power Platform use them
7. Deployment and ALM process
8. Security and governance
9. Best practices and common mistakes
10. Summary

## How to view the deck
Open the HTML file in a browser, or serve the folder locally:

```bash
cd /workspaces/PowerAutomateContent
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/ConnectionReference-modern.html
```

## Notes for future updates
- Add new slides here when the deck changes
- Keep the presentation content aligned with the HTML deck
- Add screenshots, diagrams, and business examples as needed
- Keep language concise and presentation-friendly for a 15–20 minute talk

## Speaker guidance
Focus on these key messages:
- Connection References decouple logic from credentials
- They prevent deployment failures across environments
- They support secure enterprise automation
- They improve ALM and governance