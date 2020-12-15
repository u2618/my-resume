# my-resume
I discovered ![My Resume](https://github.com/GiantMolecularCloud/my-resume) and loved it instantly. I was playing around with ![AltaCV](https://github.com/liantze/AltaCV) before but the result was a little too unorganized for my taste. 

With the original layout proposed by @GiantMolecularCloud, I had problems fitting my really long employers name. So I decided to borrow the implementation from AltaCV and included these in my take on a resume cv.

Changes compared to @GiantMolecularCloud's CV:
- Upgraded from fontawesome to fontawesome5
- Added \cvevent from AltaCV
- Added \cvref from AltaCV
- Added \cvachievement from AltaCV
- Added \divider from AltaCV
- Harmonized colors, text sized and other small stuff

Note that my-resume runs on XeLaTeX or LuaLaTeX only.

I am working on an overleaf template so you can get going right away.

# Example PDF

Thre three pages below show most possibilities that are implemented in my-resume. There are different pagestyles available, colors, header and much more can be optimized to match your taste.

The default page style features a header and a highlight bar.

![Example PDF page 1](https://github.com/tinkerdudeno1/my-resume/raw/main/resume-1.png "Example PDF page 1")

For consecutive pages, a layout with the highlight bar but without the header might be needed.
Depending on the options for my-resume, the highlight bar can alternate between pages (option doublesided) or stay on the left side for all pages (option singlesided).
In this case, the highlight bar is left empty and appears as a grey block.

![Example PDF page 2](https://github.com/tinkerdudeno1/my-resume/raw/main/resume-2.png "Example PDF page 2")

Empty pages are possible as well.

![Example PDF page 3](https://github.com/tinkerdudeno1/my-resume/raw/main/resume-3.png "Example PDF page 3")
