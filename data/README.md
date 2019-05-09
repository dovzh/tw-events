# Dataset

### Files
- test.1k.txt - test tweets (from https://github.com/aritter/twitter_nlp)
- chunk.txt, ner.txt, pos.txt - annotation (from https://github.com/aritter/twitter_nlp)
- events.txt - events annotation

### Events annotation format

Annotation example:

    Cant ep
    wait ep
    for o
    the en
    ravens en
    game en
    tomorrow o
    .... o
    go ep1
    ray en1
    rice en1
    !!!!!!! o


<table>
<tr>
<td>Word</td>
<td>Annotation</td>
<td></td>
</tr>
<tr>
<td>Cant</td>
<td>ep</td>
<td>Event phrase</td>
</tr>
<tr>
<td>go</td>
<td>ep1</td>
<td>Event phrase * </td>
</tr>
<tr>
<td>the</td>
<td>en</td>
<td>Entity</td>
</tr>
<tr>
<td>for</td>
<td>o</td>
<td>Not part of an entity or an event phrase</td>
</tr>
</table>
* First tweet event hasn't index
