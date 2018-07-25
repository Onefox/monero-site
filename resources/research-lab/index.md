---
layout: custom
title: titles.researchlab
permalink: /resources/research-lab/index.html
---
<div class="container description">
    <p>{% t research-lab.intro %}</p>
</div>
<section class="container">
    <div class="row">
        <!-- left two-thirds block-->
        <div class="left two-thirds col-lg-8 col-md-8 col-sm-12 col-xs-12">
            <div class="info-block research-paper">
                <div class="row center-xs">
                    <div class="col"><h2>{% t research-lab.mrl_papers %}</h2></div>
                </div>
                <div class="tab">
                    <input id="tab-one" type="checkbox" name="tabs" class="accordion" checked="checked">
                    <label for="tab-one" class="accordion">MRL-0001: {% t research-lab.mrl1 %}</label>
                    <div class="tab-content">
                        <p><strong>{% t research-lab.abstract %}:</strong> {% t research-lab.mrl1_abstract %}
                            <br>
                            <br>
                            <a target="_blank" rel="noreferrer noopener" href="https://lab.getmonero.org/pubs/MRL-0001.pdf">{% t research-lab.read-paper %}</a>
                        </p>
                    </div>
                </div>
                <div class="tab">
                    <input id="tab-two" type="checkbox" name="tabs" class="accordion">
                    <label for="tab-two" class="accordion">MRL-0002: {% t research-lab.mrl2 %}</label>
                    <div class="tab-content">
                        <p><strong>{% t research-lab.abstract %}:</strong> {% t research-lab.mrl2_abstract %}
                            <br>
                            <br>
                            <a target="_blank" rel="noreferrer noopener" href="https://lab.getmonero.org/pubs/MRL-0002.pdf">{% t research-lab.read-paper %}</a>
                        </p>            
                    </div>
                </div>
                <div class="tab">
                    <input id="tab-three" type="checkbox" name="tabs" class="accordion">
                    <label for="tab-three" class="accordion">MRL-0003: {% t research-lab.mrl3 %}</label>
                    <div class="tab-content">
                        <p><strong>{% t research-lab.introduction %}:</strong> {% t research-lab.mrl3_abstract %}
                            <br>
                            <br>
                            <a target="_blank" rel="noreferrer noopener" href="https://lab.getmonero.org/pubs/MRL-0003.pdf">{% t research-lab.read-paper %}</a>
                        </p>
                    </div>
                </div>
                <div class="tab">
                    <input id="tab-four" type="checkbox" name="tabs" class="accordion">
                    <label for="tab-four" class="accordion">MRL-0004: {% t research-lab.mrl4 %}</label>
                    <div class="tab-content">
                        <p><strong>{% t research-lab.abstract %}:</strong>{% t research-lab.mrl4_abstract %}
                            <br>
                            <br>
                            <a target="_blank" rel="noreferrer noopener" href="https://lab.getmonero.org/pubs/MRL-0004.pdf">{% t research-lab.read-paper %}</a></p>
                    </div>
                </div>
                <div class="tab">
                    <input id="tab-five" type="checkbox" name="tabs" class="accordion">
                    <label for="tab-five" class="accordion">MRL-0005: {% t research-lab.mrl5 %}</label>
                    <div class="tab-content">
                        <p><strong>{% t research-lab.abstract %}:</strong>{% t research-lab.mrl5_abstract %}
                            <br>
                            <br>
                            <a href="https://lab.getmonero.org/pubs/MRL-0005.pdf" target="_blank" rel="noreferrer noopener">{% t research-lab.mrl5_abstract %}</a></p>
                    </div>
                </div>
            </div>
        </div>
        <!-- end left two-thirds block-->
        <!-- right one-third block-->
        <div class="right one-third col-lg-4 col-md-4 col-sm-12 col-xs-12">
            <div class="info-block">
                <div class="row center-xs">
                    <div class="col">
                        <h2>{% t research-lab.cryptonote %}</h2>
                    </div>
                </div>
                <div>
                    <a href="https://cryptonote.org/whitepaper.pdf">{% t research-lab.cryptonote-whitepaper %}</a>
                    <p>{% t research-lab.cryptonote-whitepaper_para %}</p>
                    <a href="https://downloads.getmonero.org/whitepaper_annotated.pdf">{% t research-lab.annotated %}</a>
                    <p>{% t research-lab.annotated_para %}</p>
                    <a href="https://downloads.getmonero.org/whitepaper_review.pdf">{% t research-lab.brandon %}</a>
                    <p>{% t research-lab.brandon_para %}</p>
                </div>
            </div>
        </div>
        <!-- end right one-third block-->
    </div>
</section>

<div class="untranslated {% t research-lab.translated %}">
    <p>{% t global.untranslated %} <a class="untranslated-link" href="https://github.com/monero-project/monero-site/blob/master/README.md">README</a>.</p>
</div>