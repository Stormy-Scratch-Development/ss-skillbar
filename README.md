# ss-skillbar
skillbar for QBCore Framework

# creating a new skillbar
use this 2 lines on client side to create a new skillbar

                local skillbarSuccess = exports["ss-skillbar"]:CreateSkillbar(hasItem and 5 or 10, "medium")
                if (not skillbarSuccess) then return end
ss
