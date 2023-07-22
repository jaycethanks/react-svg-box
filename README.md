# PathBasedSvg

a simple react component to render svg based on path

## Usage

```bash
npm install react-svg-box
```

```tsx
import SvgBox from "react-svg-box";

const childStr = `
 <g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2">
        <rect width="20" height="20" x="2" y="2" rx="5" ry="5"/>
        <path d="M16 11.37A4 4 0 1 1 12.63 8A4 4 0 0 1 16 11.37zm1.5-4.87h.01"/>
</g>
`;

const SvgIcon = function () {
  return (
    <SvgBox height="32px" width="32px" style={{ color: "red" }}>
      {childStr}
    </SvgBox>
  );
};
```
