## Questions:
- [ ] What catchy name should we give this system / product?
- [ ] What browsers to support (Think we can drop IE10)
- [ ] Separate css files for pub specific colors?
- [ ] Should we create a 'common' css file wh/ will include all the pub colors + more features (e.g. for more highly designed pages)?
- [ ] What breakpoints should we use? (Maybe look at GA to determine common screen sizes)
- [ ] Container width?
- [ ] Do we want to build an icon library or use a public one? [Like IBM's](https://www.carbondesignsystem.com/guidelines/iconography/library)
- [ ] What are the max-min text sizes for h1-h6, p? [See rucksack dynamic font-size](https://www.rucksackcss.org/docs/#responsive-type)
- [ ] Any update on the report / research Megan and her team is doing on LF's client base?
- [ ] How are we going to test our updates and what metrics will determine a winner
- [ ] Will all these items be the same across each pub? (Primary, secondary text color), (Container width), (h1-h6, p font size)


## TO DO:

List of items for each team to try to accomplished (broken down by '*General*', '*Devs*', '*Designers*', '*Backlog*')


### GENERAL
- [ ] What is each pub's Primary color, Secondary color, Pub link Hover color
- [ ] Container width (Does new #10 look kind of wide for desktop reading?)
- [ ] For h1-h6, p font size (so that styles match let's consider current ja.com site for font-sizes, etc)


### DEV TEAM
- [ ] Research best css library to copy from
- [ ] Look at GA to determine common screen sizes (so we can figure out breakpoints)
- [ ] Look into what's obligatory on OPIUM's forms (e.g. remove field_wrapper, etc)
- [ ] Set up w/ Parcel or Gulp if we are not using already? (add purgeCSS, autoprefix, cssnano, `npm run build` to `--public-url ./` `--no-minify`, etc)


### DESIGN TEAM
- [ ] What are each pub's font-family(ies)
- [ ] What are each pub's primary colors [Emma has posted most here](https://3.basecamp.com/3487677/buckets/9637308/messages/1384234231)
- [ ] What are each pub's secondary colors
- [ ] What are each pub's hover colors
- [ ] What are LF's general success, error, warning, info colors
- [ ] What are LF's general primary/secondary text colors


### BACKLOG ITEMS:
- [ ] < hr > styles (h-(1-4) (for height on HRs))
- [ ] Checkboxes styles
- [ ] Radios styles
- [ ] Dark theme (for after hours)
- [ ] Consider using '.text-tiny, .text-sm, .text-md, .text-lg, .text-xl...'
- [ ] Create a mockup of promo / OF with comments about what we (w/in LF) call each section (eyebrow, hero, form, subhead, Y/NO call to actions)
- [ ] Get naming conventions down. (ie. eyebrow, hero, form, subhead, Y/NO call to actions, primary/secondary-color/text). All this being organized will make on boarding/talking amongst the team easier.
- [ ] Click to copy code on style guide (See: any public styleguide a lot have them)
- [ ] Slack integration
- [ ] Make components trigger by flags/booleans in JS object

```
<script>
let LFCoolAppName.config = {
  popUp: true,
  twoStep: true,
  ImageZoom: false
}
</script>
```

### Important Links

[LF Production - Should we post things here?](https://3.basecamp.com/3487677/projects/9637308)<br>
[New #10 Checklist](https://3.basecamp.com/3487677/buckets/9427561/messages/1350327868)<br>
[Updates to #10](https://3.basecamp.com/3487677/buckets/9427561/messages/1504639018)<br>
[LF Pub Icons](https://3.basecamp.com/3487677/buckets/9637308/messages/1384234231)<br>
[LF Meta data](https://3.basecamp.com/3487677/buckets/9637308/messages/1462233508)<br>
