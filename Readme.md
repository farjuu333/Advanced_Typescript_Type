setting up ts module:
mkdir dist
mkdir src
type nul >index.html
cd src
type nul >script.ts
cd ..
cls
tsc --init
tsc
in index.html under body tag write <script src="./dist/script.js"></script>
go live check console

tsc --watch

  "moduleDetection": "force",
v2-type union------
  different union
  1.literal type
  2.Basic Union
  3.literal Union
  4.object Union

  v3-type alias vs interface
  