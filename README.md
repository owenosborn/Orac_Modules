# Orac_Modules

orac modules... should get installed at 

media/orac/usermodules

PRESETS for:

data/orac

DEPLOY: staging for creating .zop

-----

to fix old presets:

  705  find . -name "*.json" 
  706  grep an_ohn `find . -name "*.json" `
  707  history | grep sed
  708  grep an_ohn `find . -name "*.json" `
  709  grep sequencer_bmp `find . -name "*.json" `
  710  ls ../../../media/orac/usermodules/
  711  grep sequence_bmp `find . -name "*.json" `
  712  find . -name "*.json" -exec sed -i "s/an_ohn/sequence_bpm/g" {} \;
  713  grep sequence_bmp `find . -name "*.json" `
  714  grep an_ohn `find . -name "*.json" `
  715  grep sequence_bpm `find . -name "*.json" `

