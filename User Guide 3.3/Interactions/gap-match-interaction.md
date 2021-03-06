# Gap Match Interaction

>The Gap Match [Interaction](../appendix/glossary.md#interaction) gives [Test-takers](../appendix/glossary.md#test-taker) the opportunity to demonstrate their knowledge in a manner similar to Match Interactions. A Gap Match, however, provides a set of match words, some of which will fit into gaps within a selected text passage. In essence, this is a combination of a match interaction and a "fill the gap" question. 

![Gap Match Interaction](../resources/delivery/interactions/qti/gap-match.png)

Once you have generated a new [Item](../appendix/glossary.md#item), and clicked on *Authoring* in the [Action Bar](../appendix/glossary.md#action-bar), follow the steps below to create a new gap match interaction:

**1.** From the [Common Interactions Library](../appendix/glossary.md#common-interactions-library) on the left, drag the *Gap Match* ![Gap Match](../resources/_icons/gap-match.png) icon onto the blank Item and drop it onto the [Canvas](../appendix/glossary.md#canvas).

This opens a new Gap Match Interaction window. There is a question field at the top, a middle field for the words which are to be matched, and a lower field for the gapped text, which contains a sample text.

**2.** Fill in the question field, where it says _define prompt_. 

Typically this will be some variation of "Fill in the gaps from the following word set." 

*Note: See the section on [Interaction Authoring Tools](../interactions/interaction-authoring-tools.md) for details on text editing options such as using italics or bold text in your item, and inserting features such as shared stimuli or media, tables or formulae.*

**3.** Insert the text which will contain the gaps into the text field at the bottom. 

The Gap Match elements will be extracted from this text.

**4.** Select the words or phrases you want to make into Gap Match elements within the text.

Click on the word or phrase in the text to highlight it. This will create a *magic wand* button.

Click on the *magic wand* to confirm your selected location for a Gap Match element. This creates a gap in the text, and places the word/phrase into the match words field.

Repeat as many times as is needed to adequately assess the test-taker's knowledge of the passage.

*Note: Drag-and-drop is enabled for this type of interaction.*

**5.** If desired, add extra options into the match words field by clicking the *add choice* button.

Placing additional words into the match word field may prevent test-takers from successfully using "process of elimination" as a strategy.

*Note: The _choice #1_ option will not automatically bee filled and can be used as an extra option or should be deleted y clicking the trash can ![delete](../resources/_icons/bin.png) icon.* 

<aside class="optional-extras">
    
## Optional Extras when Creating a Task

The following options are available in the [Interaction Properties Panel](../appendix/glossary.md#interaction-properties-panel) on the right.

### Shuffling the choices 

Check the *Shuffle choices* box. The sequence of the match word options will then be randomized. This is recommended if the order of presentation of the match words is not important.

If needed, you can also *pin* a response to that location in the order be clicking on the pin ![pin](../resources/_icons/pin.png) icon to the right of that choice.

### Limiting the use of a choice

If you want to limit the number of times a particular element is used, click on it. It will then appear in the *Identifier* box in the right-hand panel, which gives you the option to set the *Allowed number of uses*. Setting this to a maximum of 1, for example, will mean that the test-taker can only use that element in one match. 

### Obliging the test-taker to give an answer

If you want to prevent test-takers from continuing to the next question without providing an answer, check the *required* box for that gap match. This box appears after you have inserted the gaps in the text. 

</aside>

**7.** Click *Response* on the right of blue interaction header to define the correct answer(s).

To define the correct answers, drag and drop the correct match words from the match word field onto the corresponding gaps in your text. 

<aside class="optional-extras">

## Optional Extras when Processing a Response

The following options are available in the [Response Properties Panel](../appendix/glossary.md#response-properties-panel) on the right.

### Modifying the scoring method

By default, a test-taker receives one point per completely correct interaction, so in the case of Gap Match interactions, the test-taker has to select all the correct matches in order for the answer to be considered correct.

You may want to modify the scoring method if, for example, you want the test-taker to receive partial credit for selecting some, but not all, of the correct matches. Or you may wish to give a higher weight to some of the matches than to others. 

You can do this using the *map response* option of *Response processing*, in the Response Properties panel on the right. When you choose this option, there are several settings you need to enter. 

First, assign a weight for each correct match in the *Pair Scoring* box below the text. To do this, click on an appropriate match word and then on the space in which it should be placed. Now click the *Add* button, and it will appear in the list of matches at the bottom of the window. Check the *Correct* box, and assign the desired weight for matching this correctly in the *Score* box. Fill all the gaps with their appropriate matches. 

[Click here](../items/item-scoring-rules.md#item-scoring-rules) for more details on how to use this scoring method, and how to set the values of the associated properties.


### Inserting modal feedback

If you wish, you can insert [Modal Feedback](../appendix/glossary.md#modal-feedback) into this Interaction. For more details on how to do this, see the [section on Modal Feedback](../items/modal-feedback.md).

</aside>


**8.** Click the blue *Done* button. Your gap match interaction is now complete.

After this step, you can preview your interaction using the steps given in the [Preview Instructions](../items/preview.md).

