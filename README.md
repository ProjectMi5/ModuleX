# ModuleX

Example implementation of our module behavior in TwinCAT.

Behavior:
* Set SkillInput0.Execute to true
* Skill 1337 will be active for a few seconds
 * SkillOutput0.Ready will go to false
 * SkillOutput0.Busy will go to true
 *  ..Skill is active..
 * SkillOutput0.Busy will go to false
 * SkillOutput0.Done will go to true
* SkillInput0.Execute must be set to true
