# badge-to-path-playground

## Styles


<table>
<tr>
 <th>Style</th>
 <th>Badge</th>
 <th>Action</th>
</tr>
<tr>
<td>flat</td>
<td><img alt="" src="badges/flat.svg"></td>
<td>

```yaml
      - name: 'Style : flat'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: World
          path: badges/flat.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>flat-square</td>
<td><img alt=""  src="badges/flat-square.svg"></td>
<td>

````yaml
      - name: 'Style : flat-square'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: World
          style: flat-square
          path: badges/flat-square.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
````
</td>
</tr>
<tr>
<td>for-the-badge</td>
<td><img alt=""  src="badges/forthebadge.svg"></td>
<td>

````yaml
      - name: 'Style : for-the-badge'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: World
          style: for-the-badge
          path: badges/forthebadge.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
````
</td>
</tr>
<tr>
<td>plastic</td>
<td><img alt=""  src="badges/plastic.svg"></td>
<td>

````yaml
      - name: 'Style : plastic'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: World
          style: plastic
          path: badges/plastic.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}

````
</td>
</tr>
<tr>
<td>social</td>
<td><img alt=""  src="badges/social.svg"></td>
<td>

`````yaml
      - name: 'Style : social'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: World
          style: social
          path: badges/social.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
`````
</td>
</tr>
</table>

## Colors

### Example Named Colors

| Color         | Badge                               |
|---------------|-------------------------------------|
| brightgreen   | ![](badges/color-brightgreen.svg)   |
| green         | ![](badges/color-green.svg)         |
| yellow        | ![](badges/color-yellow.svg)        |
| yellowgreen   | ![](badges/color-yellowgreen.svg)   |
| orange        | ![](badges/color-orange.svg)        |
| red           | ![](badges/color-red.svg)           |
| blue          | ![](badges/color-blue.svg)          |
| grey          | ![](badges/color-grey.svg)          |
| lightgrey     | ![](badges/color-lightgrey.svg)     |
| gray          | ![](badges/color-gray.svg)          |
| lightgray     | ![](badges/color-lightgray.svg)     |
| critical      | ![](badges/color-critical.svg)      |
| important     | ![](badges/color-important.svg)     |
| success       | ![](badges/color-success.svg)       |
| informational | ![](badges/color-informational.svg) |
| inactive      | ![](badges/color-inactive.svg)      |

### Example Hexadecimal Colors

| Color  | Badge                        |
|--------|------------------------------|
| ff69b4 | ![](badges/color-ff69b4.svg) |
| 9cf    | ![](badges/color-9cf.svg)    |
