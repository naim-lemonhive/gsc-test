# 🛑 Broken Test Site

This project is an **intentionally broken website** built for testing tools like  
Google PageSpeed Insights, Lighthouse, and custom site performance/SEO checkers.  

It contains a mix of **bad pages** (full of issues) and at least one **valid page**  
(for comparison).

---

## ⚡ Issues This Site Will Trigger

- ❌ **No responsiveness**  
  - Missing `<meta viewport>`  
  - Fixed-width tables & images  

- ❌ **Render-blocking CSS/JS**  
  - CSS loads in `<head>` without optimization  
  - Heavy, blocking JavaScript (infinite loops, alerts)  

- ❌ **AMP validation errors**  
  - Fake AMP page missing required scripts  
  - Invalid `<amp-img>` usage  

- ❌ **Bad SEO**  
  - Missing or duplicate `<title>`  
  - Missing meta descriptions  
  - Keyword stuffing  
  - Duplicate content  

- ❌ **Accessibility failures**  
  - Missing form labels  
  - Tiny/unreadable text  
  - Low-contrast buttons  
  - Images without `alt` text  
  - Deprecated `<marquee>` tag  

- ❌ **Broken links (404)**  
  - Internal links pointing to missing pages  

- ❌ **Deprecated HTML tags**  
  - `<marquee>`, `<font>`, `<center>`  

---

## 📂 Structure

