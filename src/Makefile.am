YAML_FILES = \
	entities/bat.yaml \
	entities/blaze.yaml \
	entities/cavespider.yaml \
	entities/chicken.yaml \
	entities/creeper.yaml \
	entities/cow.yaml \
	entities/donkey.yaml \
	entities/enderman.yaml \
	entities/ghast.yaml \
	entities/horse.yaml \
	entities/mule.yaml \
	entities/pig.yaml \
	entities/rabbit.yaml \
	entities/silverfish.yaml \
	entities/skeleton_horse.yaml \
	entities/spider.yaml \
	entities/stray.yaml \
	entities/wither.yaml \
	entities/wolf.yaml \
	entities/zombie.yaml \
	entities/zombie_husk.yaml \
	entities/zombie_villager.yaml \
	pack_manifest.yaml

# THINKME: For some reason guardians start to act strangely when
# "minecraft:behavior.hurt_by_target" is applied. They start to charge
# the laser but never fire it. They also loses their ability to
# "minecraft:behavior.avoid_mob_type".
#
#YAML_FILES += entities/guardian.yaml
#YAML_FILES += entities/guardian_elder.yaml

MCPACK_FILES = \
	$(YAML_FILES) \
	pack_icon.png

EXTRA_DIST=
CLEANFILES=
noinst_DATA=
include $(top_srcdir)/am/mcpack.am
include $(top_srcdir)/am/yaml.am
