# (PART\*) Student Activity {-}

# Explore the Epigenome

## Launch the Genome Browser Gateway

Go to [`https://genome.ucsc.edu/cgi-bin/hgGateway`](https://genome.ucsc.edu/cgi-bin/hgGateway). Ensure "Human" is selected under "Browse/Select Species".  


```
## Warning: replacing previous import 'ellipsis::check_dots_unnamed' by
## 'rlang::check_dots_unnamed' when loading 'tibble'
```

```
## Warning: replacing previous import 'ellipsis::check_dots_used' by
## 'rlang::check_dots_used' when loading 'tibble'
```

```
## Warning: replacing previous import 'ellipsis::check_dots_empty' by
## 'rlang::check_dots_empty' when loading 'tibble'
```

```
## Warning: replacing previous import 'ellipsis::check_dots_unnamed' by
## 'rlang::check_dots_unnamed' when loading 'pillar'
```

```
## Warning: replacing previous import 'ellipsis::check_dots_used' by
## 'rlang::check_dots_used' when loading 'pillar'
```

```
## Warning: replacing previous import 'ellipsis::check_dots_empty' by
## 'rlang::check_dots_empty' when loading 'pillar'
```

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_2.png" title="Landing page for the UCSC Genome browser Gateway." alt="Landing page for the UCSC Genome browser Gateway." width="100%" style="display: block; margin: auto;" />

You will be working from the Human Assembly **March 2006 (NCBI/hg18)**. Make sure this is selected under the "Find Position" dropdown menu. Enter **HOXA7** in Position/Search Term and select GO. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_7.png" title="March 2006 assembly is highlighted on the Find Position dropdown menu." alt="March 2006 assembly is highlighted on the Find Position dropdown menu." width="100%" style="display: block; margin: auto;" />

Your Genome Browser should now look like this:

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_22.png" title="March 2006 assembly results for the HOXA7 locus." alt="March 2006 assembly results for the HOXA7 locus." width="100%" style="display: block; margin: auto;" />

## Clean up Visual Settings

You’ll now use the following directions to remove the default visual settings.

Scroll below to different menu options shown. 

* Under the "Mapping and Sequence" tab, Base Position should be set to **dense**. 
* Under the "Genes and Gene Predictions" tab,  RefSeq Genes should be set to **pack**.  
* All other features should be marked as **hide**. You will need to go through each of the menu options to make sure features are marked as “hide”. Please note you will need to open each menu option by select the  “+” to ensure all tracks are turned off (marked as hide). 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_29.png" title="The Base Position menu has been set to 'dense'." alt="The Base Position menu has been set to 'dense'." width="100%" style="display: block; margin: auto;" />
<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_33.png" title="The RefSeq Genes menu has been set to 'pack'." alt="The RefSeq Genes menu has been set to 'pack'." width="100%" style="display: block; margin: auto;" />

At the end of the browser page, select "refresh". 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_41.png" title="The refresh button at the bottom of the page is highlighted." alt="The refresh button at the bottom of the page is highlighted." width="100%" style="display: block; margin: auto;" />

Your browser should look like the image below, where only HOXA7 is shown. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_48.png" title="The genome is zoomed in to the HOXA7 gene." alt="The genome is zoomed in to the HOXA7 gene." width="100%" style="display: block; margin: auto;" />

## Zooming Out

Zoom out your display by 10x, 3x or 1.5x to see HOXA1-HOXA13 genes on your browser. The zoom out value you’ll select will be dependent on your computer display screen. You may need to use the zoom in option if you’ve zoomed out the display beyond the HOXA1-HOXA13 genes. Zoom buttons can be clicked more than once.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_54.png" title="The zoom in and out buttons are highlighted" alt="The zoom in and out buttons are highlighted" width="100%" style="display: block; margin: auto;" />

Ideally your browser should like the image below. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_59.png" title="HOXA1 through HOXA3 loci are now visible on the genome." alt="HOXA1 through HOXA3 loci are now visible on the genome." width="100%" style="display: block; margin: auto;" />

Instead of zooming in and out, you can always manually enter your chromosome region of choice. For this exercise, try entering the following region: **chr7:27,087,367-27,235,317**. Click "go". 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g15625333d53_0_65.png" title="The specific chromosome locus has been typed into the search bar." alt="The specific chromosome locus has been typed into the search bar." width="100%" style="display: block; margin: auto;" />

<div class = "notice">
You could also enter **chr7:27,087,367-27,235,317** in the search bar at the start of this exercise instead of HOXA7. 
</div>

## Selecting Histone Marks

Now we’ll visualize histone marks to show that the same chromosome locus can have drastically different histone patterns.

Scroll down to the "Regulation" menu and click the **Broad Histone** track hyperlink.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_0_0.png" title="The Broad Histone track hyperlink is highlighted." alt="The Broad Histone track hyperlink is highlighted." width="100%" style="display: block; margin: auto;" />

Scroll down and deselect all boxes.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_1_8.png" title="Cell line and antibody combinations have been deselected." alt="Cell line and antibody combinations have been deselected." width="100%" style="display: block; margin: auto;" />

Select **H3K4me3** and **H3K27me3** marks for **H1-hESC** and **NHLF**. To learn more about these options you can click on their blue hyperlinks for more information. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_0_9.png" title="Selected cell line and antibody combinations have been highlighted." alt="Selected cell line and antibody combinations have been highlighted." width="100%" style="display: block; margin: auto;" />

<div class = "notice">
**H3K4me3** is a known histone mark on Histone 3 (H3). It occurs on lysine 4 (K4) and has three methyl groups (me3) that indicate active gene expression. In other words, the DNA is open and ready to be accessed.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_1_18.png" title="Histone H3 (tri methyl K4). Marks promoters that are active or poised to be activated." alt="Histone H3 (tri methyl K4). Marks promoters that are active or poised to be activated." width="100%" style="display: block; margin: auto;" />

**H3K27me3** is a known histone mark on on Histone 3 (H3). It occurs on lysine 27 (K27) and has three methyl groups (me3) that indicate inactive gene expression. In other words, the DNA is closed off and cannot be accessed.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_1_22.png" title="Histone H3 (tri-methyl K27). Marks promoters that are silenced by Polycomb proteins in a given lineage; large domains are found at inactive developmental loci." alt="Histone H3 (tri-methyl K27). Marks promoters that are silenced by Polycomb proteins in a given lineage; large domains are found at inactive developmental loci." width="100%" style="display: block; margin: auto;" />

The **H1-hESC** cell line consists of embryonic stem cells.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_53_0.png" title="The table of statistics on H1-hESC cell line." alt="The table of statistics on H1-hESC cell line." width="100%" style="display: block; margin: auto;" />

The **NHLF** cell line consists of lung fibroblasts. Fibroblasts are important for building the connective structures around cells and healing wounds.

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_1.png" title="The table of statistics on NHLF cell line." alt="The table of statistics on NHLF cell line." width="100%" style="display: block; margin: auto;" />
</div>

Scroll below and deselect the Peak views. You will only need Signal views. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_5.png" title="Peak check boxes are highlighted." alt="Peak check boxes are highlighted." width="100%" style="display: block; margin: auto;" />

Your selected subtracks should only display Signal views as shown below. Click "Submit".

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_13.png" title="Only Signal views are visible among subtracks. The Submit button is highlighted" alt="Only Signal views are visible among subtracks. The Submit button is highlighted" width="100%" style="display: block; margin: auto;" />

Scroll down, and your browser should look like the image below. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_18.png" title="Histone marks are shown below the HOXA loci in the genome browser." alt="Histone marks are shown below the HOXA loci in the genome browser." width="100%" style="display: block; margin: auto;" />

## Comparing Histone Marks

Let's first examine the **H1-hESC** cell line (embryonic stem cells).

Signals are high for the H3K27me3 histone mark. You’ll also notice that H3K4me3 signals are minimal. This signal pattern demonstrates that embryonic stem cells are in the repressed chromatin configuration at the HOXA locus and indicates that HOXA genes in blue are not expressed in this cell line. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_22.png" title="High signals for the H3K27me3 histone mark in the H1-hESC cell line indicate these genes are not expressed in these cells." alt="High signals for the H3K27me3 histone mark in the H1-hESC cell line indicate these genes are not expressed in these cells." width="100%" style="display: block; margin: auto;" />

Now, let's examine the **NHLF** cell line (lung fibroblasts).

The pattern is different for NHLF. H3K4me3 signals are high for the first half of the HOXA locus, but low for the second half of the locus. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_30.png" title="H3K4me3 signals are high then low in the genome browser." alt="H3K4me3 signals are high then low in the genome browser." width="100%" style="display: block; margin: auto;" />

H3K27me3 signals are low and then high for the same locus. 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_35.png" title="H3K27me3 signals are low then high in the genome browser." alt="H3K27me3 signals are low then high in the genome browser." width="100%" style="display: block; margin: auto;" />

This signal pattern demonstrates that for lung fibroblasts only half of the HOXA locus is expressed while the other half is not expressed. Specifically, we can use the full image to see that HOXA1-7 are expressed (turned on).

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_40.png" title="HOXA1 through 7 are highlighted to indicate expression is turned on." alt="HOXA1 through 7 are highlighted to indicate expression is turned on." width="100%" style="display: block; margin: auto;" />

We can also see that HOXA9-13 is not expressed (turned off). 

<img src="05-explore_the_epigenome_files/figure-html//1B7y_jm8GuHZMUvTU1TFdW4nqQQV6nOT9XuFwgSflXz4_g152864d54a7_70_46.png" title="HOXA9 through 13 are highlighted to indicate expression is turned off." alt="HOXA9 through 13 are highlighted to indicate expression is turned off." width="100%" style="display: block; margin: auto;" />
