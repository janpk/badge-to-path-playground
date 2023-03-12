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

<table>
<tr>
 <th>Color</th>
 <th>Badge</th>
 <th>Action</th>
</tr>
<tr>
<td>brightgreen</td>
<td><img src="badges/color-brightgreen.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : brightgreen'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: brightgreen
          messageColor: brightgreen
          path: badges/color-brightgreen.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>green</td>
<td><img src="badges/color-green.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : green'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: green
          messageColor: green
          path: badges/color-green.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>yellow</td>
<td><img src="badges/color-yellow.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : yellow'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: yellow
          messageColor: yellow
          path: badges/color-yellow.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>yellowgreen</td>
<td><img src="badges/color-yellowgreen.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : yellowgreen'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: yellowgreen
          messageColor: yellowgreen
          path: badges/color-yellowgreen.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>orange</td>
<td><img src="badges/color-orange.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : orange'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: orange
          messageColor: orange
          path: badges/color-orange.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>red</td>
<td><img src="badges/color-red.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : red'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: red
          messageColor: red
          path: badges/color-red.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>blue</td>
<td><img src="badges/color-blue.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : blue'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: blue
          messageColor: blue
          path: badges/color-blue.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>grey</td>
<td><img src="badges/color-grey.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : grey'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: grey
          messageColor: grey
          path: badges/color-grey.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>lightgrey</td>
<td><img src="badges/color-lightgrey.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : lightgrey'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: lightgrey
          messageColor: lightgrey
          path: badges/color-lightgrey.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>gray</td>
<td><img src="badges/color-gray.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : gray'
        uses: janpk/badge-to-path@main
        with:
          label: gray
          message: gray
          messageColor: gray
          path: badges/color-gray.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>lightgray</td>
<td><img src="badges/color-lightgray.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : lightgray'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: lightgray
          messageColor: lightgray
          path: badges/color-lightgray.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>critical</td>
<td><img src="badges/color-critical.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : critical'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: critical
          messageColor: critical
          path: badges/color-critical.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>important</td>
<td><img src="badges/color-important.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : important'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: important
          messageColor: important
          path: badges/color-important.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>success</td>
<td><img src="badges/color-success.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : success'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: success
          messageColor: success
          path: badges/color-success.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>informational</td>
<td><img src="badges/color-informational.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : informational'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: informational
          messageColor: informational
          path: badges/color-informational.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>inactive</td>
<td><img src="badges/color-inactive.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : inactive'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: inactive
          messageColor: inactive
          path: badges/color-inactive.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
</table>

### Example Hexadecimal Colors

<table>
<tr>
 <th>Hex Color</th>
 <th>Badge</th>
 <th>Action</th>
</tr>
<tr>
<td>ff69b4</td>
<td><img src="badges/color-ff69b4.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : ff69b4'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: ff69b4
          messageColor: ff69b4
          path: badges/color-ff69b4.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>9cf</td>
<td><img src="badges/color-9cf.svg" alt=""></td>
<td>

```yaml
      - name: 'Color : 9cf'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: 9cf
          messageColor: 9cf
          path: badges/color-9cf.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
</table>


## Example Link & Logo

<table>
<tr>
 <th>Type</th>
 <th>Badge</th>
 <th>Action</th>
</tr>
<tr>
<td>link</td>
<td><img src="badges/githublink.svg" alt=""></td>
<td>

```yaml
      - name: 'Link'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: GitHub
          link: https://github.com
          path: badges/githublink.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>logo</td>
<td><img src="badges/githublogo.svg" alt=""></td>
<td>

```yaml
      - name: 'Logo'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: GitHub
          logo: github
          path: badges/githublogo.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>logo,logowidth</td>
<td><img src="badges/githublogowidth.svg" alt=""></td>
<td>

```yaml
      - name: 'LogoWidth'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: GitHub
          logo: github
          logoWidth: 200
          path: badges/githublogowidth.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
<tr>
<td>logo,link</td>
<td><img src="badges/githublogolink.svg" alt=""></td>
<td>

```yaml
      - name: 'Logo with Link'
        uses: janpk/badge-to-path@main
        with:
          label: Hello
          message: GitHub
          link: https://github.com
          logo: github
          path: badges/githublogolink.svg
          github-token: ${{ secrets.GITHUB_TOKEN }}
```
</td>
</tr>
</table>
