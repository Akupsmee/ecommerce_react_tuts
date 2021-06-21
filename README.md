## Notes

#### Older React Version

```
"react": "^16.13.1",
"react-dom": "^16.13.1",
"react-scripts": "3.4.3",
```

#### Current React Version

```
"react": "^17.0.1",
"react-dom": "^17.0.1",
"react-scripts": "4.0.0",
```

#### Alternative fix

.env file in the root
FAST_REFRESH=FALSE


{/* manual approach for star rendering */}

  {/* star */}
    {/* <span>
      {stars >= 1 ? <BsStarFill /> : stars >= 0.5 ? <BsStarHalf />:<BsStar /> }
    </span>
    {/* end of star */}

  {/* star */}
    {/* <span>
      {stars >= 2 ? <BsStarFill /> : stars >= 1.5 ? <BsStarHalf />:<BsStar /> }
    </span> */}
    {/* end of star */}

  {/* star */}
    {/* <span>
      {stars >= 3 ? <BsStarFill /> : stars >= 2.5 ? <BsStarHalf />:<BsStar /> }
    </span> */}
    {/* end of star */}
  {/* star */}
    {/* <span>
      {stars >= 4 ? <BsStarFill /> : stars >= 3.5 ? <BsStarHalf />:<BsStar /> }
    </span> */}
    {/* end of star */}
  {/* star */}
    {/* <span>
      {stars === 5 ? <BsStarFill /> : stars >= 4.5 ? <BsStarHalf />:<BsStar /> }
    </span> */} */
    {/* end of star */}

    {/* programatic approach */}