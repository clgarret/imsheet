<template>
  <div class="container">
    <div class="row">
      <div class="column">
        <div>
          <img class="logo" src="https://cubicle7games.com/media/wysiwyg/IM-Logo-Banner.png"/>
        </div>
        <div class="inputitem">
            <input class="textinput" type="text" id="character_name" name="attr_character_name">
            <label class="textinput_label" for="character_name">Character Name</label>
          </div> 
      </div>

      <div class="column margintop">
        <div class="row">
          <div class="inputitem">
            <input class="textinput" type="text" id="origin" name="attr_origin">
            <label class="textinput_label" for="origin">Origin</label>
          </div>
          <div class="inputitem">
            <input class="textinput" type="text" id="faction" name="attr_faction">
            <label class="textinput_label" for="faction">Faction</label>
          </div>
          <div class="inputitem">
            <input class="textinput" type="text" id="role" name="attr_role">
            <label class="textinput_label" for="role">Role</label>
          </div>
          <div class="inputitem">
            <input class="textinput" type="text" id="patron" name="attr_patron">
            <label class="textinput_label" for="patron">Patron</label>
          </div>
        </div>
        
        <div class="row">
          <div class="inputitem">
            <input class="textinput" type="text" id="age" name="attr_age">
            <label class="textinput_label" for="age">Age</label>
          </div>

          <div class="inputitem">
            <input class="textinput" type="text" id="eyes" name="attr_eyes">
            <label class="textinput_label" for="eyes">Eyes</label>
          </div>

          <div class="inputitem">
            <input class="textinput" type="text" id="hair" name="attr_hair">
            <label class="textinput_label" for="hair">Hair</label>
          </div>
          
          <div class="inputitem">
            <input class="textinput" type="text" id="height" name="attr_height">
            <label class="textinput_label" for="height">Height</label>
          </div>

          <div class="inputitem">
            <input class="textinput" type="text" id="weight" name="attr_weight">
            <label class="textinput_label" for="weight">Weight</label>
          </div>

          <div class="inputitem">
            <input class="textinput" type="text" id="handedness" name="attr_handedness">
            <label class="textinput_label" for="handedness">Handedness</label>
          </div>
        </div>

        <div class="row">
          <div class="inputitem">
            <input class="textinput" type="text" id="distinguishing_features" name="attr_distinguishing_features">
            <label class="textinput_label" for="distinguishing_features">Distinguishing Features</label>
          </div>
          <div class="inputitem">
            <input class="textinput smallinput" type="text" id="xp_current" name="attr_xp_current">
            <label class="textinput_label" for="xp_current">Current</label>
          </div>
          / XP
          <div class="inputitem">
            <input class="textinput smallinput" type="text" id="xp_spent" name="attr_xp_spent">
            <label class="textinput_label" for="xp_spent">Spent</label>
          </div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="row margintop fullwidth">
        <div class="column">
          <div class="sectionheader">
            ------ CHARACTERISTICS ------
          </div>
          <div class="row">
            <div class="characteristicstable">
              <div>&nbsp;</div>
              <div>WS</div>
              <div>BS</div>
              <div>STR</div>
              <div>TGH</div>
              <div>AG</div>
              <div>INT</div>
              <div>PER</div>
              <div>WIL</div>
              <div>FEL</div>

              <div>Starting</div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_ws" name="attr_starting_ws">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_bs" name="attr_starting_bs">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_str" name="attr_starting_str">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_tgh" name="attr_starting_tgh">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_ag" name="attr_starting_ag">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_int" name="attr_starting_int">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_per" name="attr_starting_per">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_wil" name="attr_starting_wil">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="starting_fel" name="attr_starting_fel">
              </div>

              <div>Advances</div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_ws" name="attr_advances_ws">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_bs" name="attr_advances_bs">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_str" name="attr_advances_str">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_tgh" name="attr_advances_tgh">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_ag" name="attr_advances_ag">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_int" name="attr_advances_int">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_per" name="attr_advances_per">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_wil" name="attr_advances_wil">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="advances_fel" name="attr_advances_fel">
              </div>

              <div>Current</div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_ws" name="attr_current_ws">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_bs" name="attr_current_bs">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_str" name="attr_current_str">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_tgh" name="attr_current_tgh">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_ag" name="attr_current_ag">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_int" name="attr_current_int">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_per" name="attr_current_per">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_wil" name="attr_current_wil">
              </div>
              <div class="inputitem">
                <input class="textinput smallinput" type="text" id="current_fel" name="attr_current_fel">
              </div>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="smallsectionheader">
            ------ FATE ------
          </div>
          <div class="row">
            <div class="inputitem">
              <input class="textinput smallinput" type="text" id="fate_current" name="attr_fate_current">
              <label class="textinput_label" for="fate_current">Current</label>
            </div>
            <div class="inputitem">
              <input class="textinput smallinput" type="text" id="fate_spent" name="attr_fate_spent">
              <label class="textinput_label" for="fate_spent">Spent</label>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="smallsectionheader">
            ------ CORRUPTION ------
          </div>
          <div class="row">
            <div class="inputitem">
              <input class="textinput smallinput" type="text" id="corruption_total" name="attr_corruption_total">
              <label class="textinput_label" for="corruption_total">Total</label>
            </div>
            <div class="inputitem">
              <textarea class="textinput smallinput" id="corruption_mutations" name="attr_corruption_mutations"></textarea>
              <label class="textinput_label" for="corruption_mutations">Mutations</label>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="row sectionheader margintop fullwidth">
      ------ SKILLS & SPECIALISATIONS ------
    </div>

    <div class="row">
      <div class="row fullwidth">
        <div class="column">
          <div class="row">
            <div class="skillstable">
              <div>Skill</div>
              <div>Characteristic</div>
              <div>Adv (+5 each)</div>
              <div>Total</div>

              <div>ATHLETICS</div>
              <div>STR</div>
              <div><input class="textinput" type="text" id="skill_adv_athletics" name="attr_skill_adv_athletics"></div>
              <div><input class="textinput" type="text" id="skill_athletics" name="attr_skill_athletics"></div>

              <div>AWARENESS</div>
              <div>PER</div>
              <div><input class="textinput" type="text" id="skill_adv_awareness" name="attr_skill_adv_awareness"></div>
              <div><input class="textinput" type="text" id="skill_awareness" name="attr_skill_awareness"></div>

              <div>DEXTERITY</div>
              <div>AG</div>
              <div><input class="textinput" type="text" id="skill_adv_dexterity" name="attr_skill_adv_dexterity"></div>
              <div><input class="textinput" type="text" id="skill_dexterity" name="attr_skill_dexterity"></div>

              <div>DISCIPLINE</div>
              <div>WIL</div>
              <div><input class="textinput" type="text" id="skill_adv_discipline" name="attr_skill_adv_discipline"></div>
              <div><input class="textinput" type="text" id="skill_discipline" name="attr_skill_discipline"></div>

              <div>FORTITUDE</div>
              <div>TGH</div>
              <div><input class="textinput" type="text" id="skill_adv_fortitude" name="attr_skill_adv_fortitude"></div>
              <div><input class="textinput" type="text" id="skill_fortitude" name="attr_skill_fortitude"></div>

              <div>INTUITION</div>
              <div>PER</div>
              <div><input class="textinput" type="text" id="skill_adv_intuition" name="attr_skill_adv_intuition"></div>
              <div><input class="textinput" type="text" id="skill_intuition" name="attr_skill_intuition"></div>

              <div>LINGUISTICS</div>
              <div>INT</div>
              <div><input class="textinput" type="text" id="skill_adv_linguistics" name="attr_skill_adv_linguistics"></div>
              <div><input class="textinput" type="text" id="skill_linguistics" name="attr_skill_linguistics"></div>

              <div>LOGIC</div>
              <div>INT</div>
              <div><input class="textinput" type="text" id="skill_adv_logic" name="attr_skill_adv_logic"></div>
              <div><input class="textinput" type="text" id="skill_logic" name="attr_skill_logic"></div>

              <div>LORE</div>
              <div>INT</div>
              <div><input class="textinput" type="text" id="skill_adv_lore" name="attr_skill_adv_lore"></div>
              <div><input class="textinput" type="text" id="skill_lore" name="attr_skill_lore"></div>

              <div>MEDICAE</div>
              <div>INT</div>
              <div><input class="textinput" type="text" id="skill_adv_medicae" name="attr_skill_adv_medicae"></div>
              <div><input class="textinput" type="text" id="skill_medicae" name="attr_skill_medicae"></div>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="row">
            <div class="skillstable">
              <div>Skill</div>
              <div>Characteristic</div>
              <div>Adv (+5 each)</div>
              <div>Total</div>

              <div>MELEE</div>
              <div>WS</div>
              <div><input class="textinput" type="text" id="skill_adv_melee" name="attr_skill_adv_melee"></div>
              <div><input class="textinput" type="text" id="skill_melee" name="attr_skill_melee"></div>

              <div>NAVIGATION</div>
              <div>INT</div>
              <div><input class="textinput" type="text" id="skill_adv_navigation" name="attr_skill_adv_navigation"></div>
              <div><input class="textinput" type="text" id="skill_navigation" name="attr_skill_navigation"></div>

              <div>PRESENCE</div>
              <div>WIL</div>
              <div><input class="textinput" type="text" id="skill_adv_presence" name="attr_skill_adv_presence"></div>
              <div><input class="textinput" type="text" id="skill_presence" name="attr_skill_presence"></div>

              <div>PILOTING</div>
              <div>AG</div>
              <div><input class="textinput" type="text" id="skill_adv_piloting" name="attr_skill_adv_piloting"></div>
              <div><input class="textinput" type="text" id="skill_piloting" name="attr_skill_piloting"></div>

              <div>PSYCHIC MASTERY</div>
              <div>RANGED</div>
              <div><input class="textinput" type="text" id="skill_adv_psychic_mastery" name="attr_skill_adv_psychic_mastery"></div>
              <div><input class="textinput" type="text" id="skill_psychic_mastery" name="attr_skill_psychic_mastery"></div>

              <div>INTUITION</div>
              <div>PER</div>
              <div><input class="textinput" type="text" id="skill_adv_ranged" name="attr_skill_adv_ranged"></div>
              <div><input class="textinput" type="text" id="skill_ranged" name="attr_skill_ranged"></div>

              <div>RAPPORT</div>
              <div>FEL</div>
              <div><input class="textinput" type="text" id="skill_adv_rapport" name="attr_skill_adv_rapport"></div>
              <div><input class="textinput" type="text" id="skill_rapport" name="attr_skill_rapport"></div>

              <div>REFLEXES</div>
              <div>AG</div>
              <div><input class="textinput" type="text" id="skill_adv_reflexes" name="attr_skill_adv_reflexes"></div>
              <div><input class="textinput" type="text" id="skill_reflexes" name="attr_skill_reflexes"></div>

              <div>STEALTH</div>
              <div>AG</div>
              <div><input class="textinput" type="text" id="skill_adv_stealth" name="attr_skill_adv_stealth"></div>
              <div><input class="textinput" type="text" id="skill_stealth" name="attr_skill_stealth"></div>

              <div>TECH</div>
              <div>INT</div>
              <div><input class="textinput" type="text" id="skill_adv_tech" name="attr_skill_adv_tech"></div>
              <div><input class="textinput" type="text" id="skill_tech" name="attr_skill_tech"></div>
            </div>
          </div>
        </div>

        <div class="column">
          <div class="row">
            <div class="skillstable">
              <div>Specialisation</div>
              <div>Skill</div>
              <div>Adv (+5 each)</div>
              <div>Total</div>

              <div><input class="textinput" type="text" id="specialization_1" name="attr_specialization_1"></div>
              <div><input class="textinput" type="text" id="specialization_1_skill" name="attr_specialization_1_skill"></div>
              <div><input class="textinput" type="text" id="specialization_1_adv" name="attr_specialization_1_adv"></div>
              <div><input class="textinput" type="text" id="specialization_1_total" name="attr_specialization_1_total"></div>


              <div><input class="textinput" type="text" id="specialization_2" name="attr_specialization_2"></div>
              <div><input class="textinput" type="text" id="specialization_2_skill" name="attr_specialization_2_skill"></div>
              <div><input class="textinput" type="text" id="specialization_2_adv" name="attr_specialization_2_adv"></div>
              <div><input class="textinput" type="text" id="specialization_2_total" name="attr_specialization_2_total"></div>

              <div><input class="textinput" type="text" id="specialization_3" name="attr_specialization_3"></div>
              <div><input class="textinput" type="text" id="specialization_3_skill" name="attr_specialization_3_skill"></div>
              <div><input class="textinput" type="text" id="specialization_3_adv" name="attr_specialization_3_adv"></div>
              <div><input class="textinput" type="text" id="specialization_3_total" name="attr_specialization_3_total"></div>

              <div><input class="textinput" type="text" id="specialization_4" name="attr_specialization_4"></div>
              <div><input class="textinput" type="text" id="specialization_4_skill" name="attr_specialization_4_skill"></div>
              <div><input class="textinput" type="text" id="specialization_4_adv" name="attr_specialization_4_adv"></div>
              <div><input class="textinput" type="text" id="specialization_4_total" name="attr_specialization_4_total"></div>

              <div><input class="textinput" type="text" id="specialization_5" name="attr_specialization_5"></div>
              <div><input class="textinput" type="text" id="specialization_5_skill" name="attr_specialization_5_skill"></div>
              <div><input class="textinput" type="text" id="specialization_5_adv" name="attr_specialization_5_adv"></div>
              <div><input class="textinput" type="text" id="specialization_5_total" name="attr_specialization_5_total"></div>

              <div><input class="textinput" type="text" id="specialization_6" name="attr_specialization_6"></div>
              <div><input class="textinput" type="text" id="specialization_6_skill" name="attr_specialization_6_skill"></div>
              <div><input class="textinput" type="text" id="specialization_6_adv" name="attr_specialization_6_adv"></div>
              <div><input class="textinput" type="text" id="specialization_6_total" name="attr_specialization_6_total"></div>

              <div><input class="textinput" type="text" id="specialization_7" name="attr_specialization_7"></div>
              <div><input class="textinput" type="text" id="specialization_7_skill" name="attr_specialization_7_skill"></div>
              <div><input class="textinput" type="text" id="specialization_7_adv" name="attr_specialization_7_adv"></div>
              <div><input class="textinput" type="text" id="specialization_7_total" name="attr_specialization_7_total"></div>

              <div><input class="textinput" type="text" id="specialization_8" name="attr_specialization_8"></div>
              <div><input class="textinput" type="text" id="specialization_8_skill" name="attr_specialization_8_skill"></div>
              <div><input class="textinput" type="text" id="specialization_8_adv" name="attr_specialization_8_adv"></div>
              <div><input class="textinput" type="text" id="specialization_8_total" name="attr_specialization_8_total"></div>

              <div><input class="textinput" type="text" id="specialization_9" name="attr_specialization_9"></div>
              <div><input class="textinput" type="text" id="specialization_9_skill" name="attr_specialization_9_skill"></div>
              <div><input class="textinput" type="text" id="specialization_9_adv" name="attr_specialization_9_adv"></div>
              <div><input class="textinput" type="text" id="specialization_9_total" name="attr_specialization_9_total"></div>

              <div><input class="textinput" type="text" id="specialization_10" name="attr_specialization_10"></div>
              <div><input class="textinput" type="text" id="specialization_10_skill" name="attr_specialization_10_skill"></div>
              <div><input class="textinput" type="text" id="specialization_10_adv" name="attr_specialization_10_adv"></div>
              <div><input class="textinput" type="text" id="specialization_10_total" name="attr_specialization_10_total"></div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="row">
      <div class="side">
        <div class="column">
          <div class="sectionheader">
            ------ GOALS ------
          </div>
          <div class="inputitem">
            <textarea class="textinput smallinput" id="goals" name="attr_goals" rows="5"></textarea>
          </div>
          <div class="sectionheader">
            ------ CONNECTIONS ------
          </div>
          <div class="inputitem">
            <textarea class="textinput smallinput" id="connections" name="attr_connections" rows="5"></textarea>
          </div>
          <div class="sectionheader">
            ------ NOTES ------
          </div>
          <div class="inputitem">
            <textarea class="textinput smallinput" id="notes" name="attr_notes" rows="19"></textarea>
          </div>
          <div class="sectionheader">
            ------ DIVINATION ------
          </div>
          <div class="inputitem">
            <textarea class="textinput smallinput" id="divination" name="attr_divination" rows="5"></textarea>
          </div>
        </div>
      </div>

      <div class="main">
        <div class="column">
          <div class="sectionheader">
            ------ INFLUENCE ------
          </div>
          <div class="row">
            <div class="influencetable">
              <div>FACTION</div>
              <div>INFL</div>
              <div>CONTACTS</div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

              <div><input class="textinput" type="text" id="faction1" name="attr_faction1"></div>
              <div><input class="textinput" type="text" id="infl1" name="attr_infl1"></div>
              <div><input class="textinput" type="text" id="contacts1" name="attr_contacts1"></div>

            </div>
          </div>

          <div class="sectionheader">
            ------ TALENTS ------
          </div>
          <div class="row">
            <div class="talenttable">
              <div>NAME</div>
              <div>EFFECT</div>

              <div><input class="textinput" type="text" id="attr_talent1" name="attr_talent1"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect1" name="attr_talent_effect1"></div>

              <div><input class="textinput" type="text" id="attr_talent2" name="attr_talent2"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect2" name="attr_talent_effect2"></div>

              <div><input class="textinput" type="text" id="attr_talent3" name="attr_talent3"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect3" name="attr_talent_effect3"></div>

              <div><input class="textinput" type="text" id="attr_talent4" name="attr_talent4"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect4" name="attr_talent_effect4"></div>

              <div><input class="textinput" type="text" id="attr_talent5" name="attr_talent5"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect5" name="attr_talent_effect5"></div>

              <div><input class="textinput" type="text" id="attr_talent6" name="attr_talent6"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect6" name="attr_talent_effect6"></div>

              <div><input class="textinput" type="text" id="attr_talent7" name="attr_talent7"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect7" name="attr_talent_effect7"></div>

              <div><input class="textinput" type="text" id="attr_talent8" name="attr_talent8"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect8" name="attr_talent_effect8"></div>

              <div><input class="textinput" type="text" id="attr_talent9" name="attr_talent9"></div>
              <div><input class="textinput" type="text" id="attr_talent_effect9" name="attr_talent_effect9"></div>
            </div>
          </div>
        </div>
      </div>
    </div>


    <div class="row fullwidth">
      <div class="side">
        <div class="column">
          <div class="sectionheader">
              ------ INITIATIVE ------
          </div>
          <div class="inputitem">
              <textarea class="textinput" id="initiative" name="attr_initiative" rows="5"></textarea>
            </div>
        </div>
      </div>
      <div class="column">
        <div class="sectionheader">
            ------ WOUNDS ------
        </div>
        <div class="row">
          <div class="inputitem">
            <input class="textinput smallinput" type="text" id="wounds_current" name="attr_wounds_current">
            <label class="textinput_label" for="wounds_maximum">Current</label>
          </div>
          /
          <div class="inputitem">
            <input class="textinput smallinput" type="text" id="wounds_maximum" name="attr_wounds_maximum">
            <label class="textinput_label" for="wounds_maximum">Maximum</label>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="sectionheader">
            ------ CRITICAL WOUNDS ------
        </div>
        <div class="row">
          <div class="criticalwoundstable">
            <div>LOCATION</div>
            <div>EFFECT</div>

            <div><input class="textinput" type="text" id="wound_location1" name="attr_wound_location1"></div>
            <div><input class="textinput" type="text" id="wound_effect1" name="attr_wound_effect1"></div>

            <div><input class="textinput" type="text" id="wound_location2" name="attr_wound_location2"></div>
            <div><input class="textinput" type="text" id="wound_effect2" name="attr_wound_effect2"></div>

            <div><input class="textinput" type="text" id="wound_location3" name="attr_wound_location3"></div>
            <div><input class="textinput" type="text" id="wound_effect3" name="attr_wound_effect3"></div>

            <div><input class="textinput" type="text" id="wound_location4" name="attr_wound_location4"></div>
            <div><input class="textinput" type="text" id="wound_effect4" name="attr_wound_effect4"></div>

            <div><input class="textinput" type="text" id="wound_location5" name="attr_wound_location5"></div>
            <div><input class="textinput" type="text" id="wound_effect5" name="attr_wound_effect5"></div>
          </div>
        </div>
      </div>
    </div>
  </div>
    
</template>

<script>
export default {
  name: 'App',
  components: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container {
  display: flex;
  flex-wrap: nowrap;
  flex-direction: column;
}
.fullwidth {
  justify-content: space-between;
}
.width20 {
  width: 20%;
}
.width30 {
  width: 30%;
}
.width50 {
  width: 50%;
}
.row {
  display: flex;
  flex-direction : row;
  gap: 10px;
}
.column {
  display: flex;
  flex-direction: column;
  flex-wrap: nowrap;
  gap: 20px;
  margin-right: 10px;
}
.inputitem {
  display: flex;
  flex-direction: column;
  flex-grow: 1;
}
.textinput {
  width: 90%;
}
.smallinput {
  flex-shrink: 2;
}
.margintop {
  margin-top: 55px;
}

label {
  text-transform: uppercase;
}
.characteristicstable {
    display: grid;
    grid-template-columns: repeat(11, 50px);
}
.characteristicstable > div {
  margin: 2px;
  padding: 2px;
  border: 1px solid #000000;
}
.characteristicstable > div:nth-child(10n+1) {
  grid-column: span 2;
  border-left: 0;
}
.skillstable {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    min-height: 30vh;
}
.skillstable > div {
  margin: 2px;
  padding: 2px;
  border: 1px solid #000000;
}
.influencetable {
  display: grid;
    grid-template-columns: 2fr 1fr 4fr;
    min-height: 30vh;
}
.influencetable > div {
  margin: 2px;
  padding: 2px;
  border: 1px solid #000000;
}

.talenttable {
  display: grid;
    grid-template-columns: 2fr 5fr;
    min-height: 30vh;
    width: 100%;
}
.criticalwoundstable > div {
  margin: 2px;
  padding: 2px;
  border: 1px solid #000000;
}
.criticalwoundstable {
  display: grid;
    grid-template-columns: 2fr 5fr;
    width: 100%;
}
.talenttable > div {
  margin: 2px;
  padding: 2px;
  border: 1px solid #000000;
}
.side {
  padding-top: 1rem;
	width: 25rem;
}
.main {
	flex: 1 0 0;
	padding: 1rem;
}

.logo {
  max-width: 406px;
}
</style>
