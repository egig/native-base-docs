#### Card Header and Footer

To add an optional header and/or footer within a card, include <code>header</code> prop with the <code>CardItem</code>.<br />
* **Card Header**: Include <code>header</code> prop with first instance of CardItem within Card.
* **Card Footer**: Include <code>header</code> prop with last instance of CardItem within Card.

![Preview ios Card_Header_and_Footer](https://github.com/GeekyAnts/NativeBase-KitchenSink/raw/master/screenshots/ios/cardHeader.png)
![Preview android Card_Header_and_Footer](https://github.com/GeekyAnts/NativeBase-KitchenSink/raw/master/screenshots/android/cardHeader.png)

*Syntax*

<pre class="line-numbers"><code class="language-jsx">import React, { Component } from 'react';
import { Container, Content, Card, CardItem, Text, Body } from 'native-base';
​
export default class CardHeaderFooterExample extends Component {
    render() {
        return (
            &lt;Container>
                &lt;Content>
                    &lt;Card>
                        &lt;CardItem header>
                            &lt;Text>NativeBase&lt;/Text>
                        &lt;/CardItem>
                        &lt;CardItem>
                            &lt;Body>
                                &lt;Text>
                                    //Your text here
                                &lt;/Text>
                            &lt;/Body>
                        &lt;/CardItem>
                        &lt;CardItem header>
                            &lt;Text>GeekyAnts&lt;/Text>
                        &lt;/CardItem>
                   &lt;/Card>
                &lt;/Content>
            &lt;/Container>
        );
    }
}</code></pre><br />
