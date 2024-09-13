 $('.top.positioner').find('.bg').css("background", "none")
        $('.bottom.positioner').find('.bg').css("background", "none")
        $('.bottom.positioner').find('.bg-additional-widget-left').css("background", "none")
        $('.bottom.positioner').find('.bg-additional-widget-right').css("background", "none")
        $('.game-layer').css({"top":0, "bottom": 0})
        Engine.onResize()

        $('.widget-button').css({"background-image":"none", "background-color":"transparent"})
        $('.widget-button.green').css({"background-image":"none"})

        $('.bottom-panel-of-bottom-positioner.bottom-panel').css({"width":"227px", "height":"44px", "margin-left": "-227px", "background-position-y": "-111px"})
        //$('.glass').css({"background-image":"none"})

        let div1 = $('<div>').addClass("bottom-panel-of-bottom-positioner bottom-panel asdasd1")
        let div2 = $('<div>').addClass("bottom-panel-of-bottom-positioner bottom-panel asdasd2")

        $('.bottom.positioner').find('.content').append(div2)

        $('.bottom-panel-of-bottom-positioner.bottom-panel').find('.slots.right').css({    "right": "-164px"});
        $('.bottom-panel-of-bottom-positioner.bottom-panel').find('.slots.left').css({    "left": "63px"});

        $('.asdasd2').css({"left": "50%", "background-position-x": "-444px", "background-position-y": "-111px", "margin-left": "0px", "width":"231px", "height":"44px"})
        $('.hp-indicator-wrapper').css({"display":"none"})
        $('.bottom-panel-pointer-bg').css({"display":"none"})
        $('.exp-progress').css({"display":"none"})
        $('.interface-layer ').find('.main-column').css({"top": 0, "bottom": 0})
        $('.bottom-panel-of-bottom-positioner.bottom-panel').css('bottom', "50px")

        //$('.bottom-left.main-buttons-container').css('left', "260px")
        //$('.bottom-left-additional.main-buttons-container').css('left', "260px")

        //$('.bottom-right.main-buttons-container').css('right', "260px")
        //$('.bottom-right-additional.main-buttons-container').css('right', "260px")

        //$('.top-left.main-buttons-container').css('left', "260px")
        //$('.top-right.main-buttons-container').css('right', "260px")

        $('.comandBar').css('display', "none")

        $('.right-column.main-column').css({'background':"none", "background-color":"#202020"})

        $('.hud-container').css({'background':"none", "left": "inherit", "right":"-57px"})

        $('.equipment-wrapper').css({'top':"70px"})

        $('.stats-wrapper').css({'top':"70px"})

        $('.inventory_wrapper').css({'top':"265px"})

        $('.pvp-btn').css({'top':"178px"})

        $('.bottom-panel-of-bottom-positioner.bottom-panel').css({'background':"none"})

        //$('.bottom-left.main-buttons-container').css('left', "260px")
        //$('.bottom-left-additional.main-buttons-container').css('left', "260px")

        //let left = "260px";
        let leftUpMax = "260px";
        let leftMax = "310px";
        let leftAdditionalMax = "260px";

        let leftUpMin = "0px";
        let leftMin = "50px";
        let leftAdditionalMin = "0px";

        let rightUpMax = "260px";
        let rightMax = "-6px";
        let rightAdditionalMax = "44px";

        let rightUpMin = "0px";
        let rightMin = "-258px";
        let rightAdditionalMin = "-205px";

        let style =  `
        <style id="asdasd-style">

        /*.main-buttons-container.bottom-left {*/
            /*bottom: -43px;*/
        /*}*/

        .bottom-left.main-buttons-container,
        .bottom-left-additional.main-buttons-container,
        .bottom-right.main-buttons-container,
        .bottom-right-additional.main-buttons-container
         {
                transform: rotate(270deg);
                transform-origin: 0% 0%;
                bottom: -43px;

                .widget-button {
                    transform: rotate(90deg);
                }
        }

        .chat-size-0 {
            .bottom-left.main-buttons-container {
            left : ${leftMin};
            }
            .bottom-left-additional.main-buttons-container {
            left : ${leftAdditionalMin};
            }
            .top-left.main-buttons-container {
            left : ${leftUpMin};
            }
        }

        .chat-size-1 {
            .bottom-left.main-buttons-container {
            left : ${leftMax};
            }
            .bottom-left-additional.main-buttons-container {
            left : ${leftAdditionalMax};
            }
            .top-left.main-buttons-container {
            left : ${leftUpMax};
            }
        }

        .eq-column-size-1 {
            .bottom-right.main-buttons-container {
            right : ${rightMax};
            }
            .bottom-right-additional.main-buttons-container {
            right : ${rightAdditionalMax};
            }
            .top-right.main-buttons-container {
            right : ${rightUpMax};
            }
        }

        .eq-column-size-0 {
            .bottom-right.main-buttons-container {
            right : ${rightMin};
            }
            .bottom-right-additional.main-buttons-container {
            right : ${rightAdditionalMin};
            }
            .top-right.main-buttons-container {
            right : ${rightUpMin};
            }
            .hud-container {
            display: none
            }
        }

        </style>

        `;

        const styleEl = stringToHtml(style);
        document.head.appendChild(styleEl);
