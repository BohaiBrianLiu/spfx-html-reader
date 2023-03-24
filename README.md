# SPFX HTML Reader

This web part allows users to inject HTML DOM to SharePoint pages.

![screen shot of input field](screen-shot-1.png)
![screen shot of result](screen-shot-2.png)

## Safety

- Codes will be [purified](https://github.com/cure53/DOMPurify) to aviod potential XSS attacks.
- ./config/serve.json file is excluded to aviod exposure of server entry point.
