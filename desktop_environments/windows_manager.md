# Windows Manager
## Summary
### Commands list[# Commands list]

# Commands list

NB: # marks the limits of the screen

When opening application, default behavior
  - full screen
  - split view
  - floating windows

  
Tilling windows
  Commands
    Create new window
      With vertical split
      With horizontal split
      As tab
      As stack
    Change tab or stack position and direction
      Horizontal / Vertical
      Top / Bottom / Right / Left
    Adjust split length
      Resize
        On one side
        On two side
      Set to middle between two splits
      ############       ############
      #1234|5|678#       #1234|56|78#
      #    | |   #  -->  #    |  |  #
      #    | |   #       #    |  |  #
      ############       ############
      Set to equidistant between (selected|all) splits
      ##########       ##########
      #123|4|56#       #12|34|56#
      #   | |  #  -->  #  |  |  #
      #   | |  #       #  |  |  #
      ##########       ##########
      Link / Unlink splits
        - Linked
      #######       #######
      #  |  #       #  |  #
      #  |  #       #--+--#
      #--+--#  -->  #  |  #
      #  |  #       #  |  #
      #  |  #       #  |  #
      #######       #######
        - Unlinked
      #######       #######
      #  |  #       #  |  #
      #  |  #       #--|  #
      #--+--#  -->  #  +--#
      #  |  #       #  |  #
      #  |  #       #  |  #
      #######       #######
        NB: When unlinked on one axis, can't unlink on the other
      
    Switch windows tile
      #####       #####
      #a| #       #c| #
      #-+c#  -->  #-+b#
      #b| #       #b| #
      #####       #####
    Turn windows around split
      #####       #####
      #a| #       # |a#
      #-+c#  -->  #c+-#
      #b| #       # |b#
      #####       #####
      
    Attach to current tilling
      How to choose where to attach ? (vertical split, horizontal split, tab, stack)
    Detach from current tilling (set floating)
    Bring current tile / window fullscreen (and when unfocus, get back to normal)
    Display / hide title bar
    
Other
-----

Ability for applications to override the title bar ? (like firefox)

Windows snapping (bring floating window to an edge/corner to resize)
  Snap assist (display thumbnail of opened windows)

When stacking, either only highlight current window, or move windows title bar to the bottom/top or right/left
