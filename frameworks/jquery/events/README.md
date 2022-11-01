# JQuery
## Events
- JQuery
    - jQuery.ready
- Event on DOM
    - .on(), .off()??
    - .bind()
    - .click(), .dblclick()
    - .focus(), .blur()
    - .focusin(), .focusout()
    - .input(), .change()
    - ~~.live(), .die()~~
    - .hover()
    - Keyboard
        - .keydown()
        - .keyup()
        - .keypress()
- Event Object
    - Methods
        - event.preventDefault()
            - event.isDefaultPrevented()
        - event.stopPropagation()
            - event.isPropagationStopped()
        - event.stopImmediatePropagation()
            - event.isImmediatePropagationStopped()
    - Attributes
        - Target
            - event.target
            - event.relatedTarget
            - event.currentTarget
            - event.delegateTarget
        - Position
            - event.pageX
            - event.pageY
        - Other
            - event.result
            - event.data
            - event.metaKey
            - event.timeStamp
            - event.type
            - event.which