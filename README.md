FAILED: out/target/product/beyondx/obj/ETC/sepolicy_intermediates/sepolicy
/bin/bash -c "(out/host/linux-x86/bin/secilc -m -M true -G -c 30  out/target/product/beyondx/obj/ETC/plat_sepolicy.cil_intermediates/plat_sepolicy.cil out/target/product/beyondx/system/etc/selinux/mappin
g/32.0.cil out/target/product/beyondx/obj/ETC/plat_pub_versioned.cil_intermediates/plat_pub_versioned.cil out/target/product/beyondx/obj/ETC/vendor_sepolicy.cil_intermediates/vendor_sepolicy.cil out/targ
et/product/beyondx/obj/ETC/system_ext_sepolicy.cil_intermediates/system_ext_sepolicy.cil out/target/product/beyondx/system/system_ext/etc/selinux/mapping/32.0.cil -o out/target/product/beyondx/obj/ETC/se
policy_intermediates/sepolicy.tmp -f /dev/null ) && (out/host/linux-x86/bin/sepolicy-analyze out/target/product/beyondx/obj/ETC/sepolicy_intermediates/sepolicy.tmp permissive > out/target/product/beyondx
/obj/ETC/sepolicy_intermediates/sepolicy.permissivedomains ) && (if [ \"userdebug\" = \"user\" -a -s out/target/product/beyondx/obj/ETC/sepolicy_intermediates/sepolicy.permissivedomains ]; then 		e
cho \"==========\" 1>&2; 		echo \"ERROR: permissive domains not allowed in user builds\" 1>&2; 		echo \"List of invalid domains:\" 1>&2; 		cat out/target/product/beyo
ndx/obj/ETC/sepolicy_intermediates/sepolicy.permissivedomains 1>&2; 		exit 1; 		fi ) && (mv out/target/product/beyondx/obj/ETC/sepolicy_intermediates/sepolicy.tmp out/target/produ
ct/beyondx/obj/ETC/sepolicy_intermediates/sepolicy )"
neverallow check failed at out/target/product/beyondx/obj/ETC/plat_pub_versioned.cil_intermediates/plat_pub_versioned.cil:9793
  (neverallow base_typeattr_219_32_0 default_prop_32_0 (file (ioctl read write create setattr lock relabelfrom append unlink link rename open watch watch_mount watch_sb watch_with_perm watch_reads)))
    <root>
    allow at out/target/product/beyondx/obj/ETC/vendor_sepolicy.cil_intermediates/vendor_sepolicy.cil:2074
      (allow hal_lineage_touch_default default_prop_32_0 (file (read)))

neverallow check failed at out/target/product/beyondx/obj/ETC/plat_sepolicy.cil_intermediates/plat_sepolicy.cil:22900 from system/sepolicy/private/property.te:47
  (neverallow base_typeattr_222 base_typeattr_747 (file (ioctl read write create setattr lock relabelfrom append unlink link rename open watch watch_mount watch_sb watch_with_perm watch_reads)))
    <root>
    allow at out/target/product/beyondx/obj/ETC/vendor_sepolicy.cil_intermediates/vendor_sepolicy.cil:2074
      (allow hal_lineage_touch_default default_prop_32_0 (file (read)))

neverallow check failed at out/target/product/beyondx/obj/ETC/plat_sepolicy.cil_intermediates/plat_sepolicy.cil:14293 from system/sepolicy/public/property.te:222
  (neverallow base_typeattr_222 default_prop (file (ioctl read write create setattr lock relabelfrom append unlink link rename open watch watch_mount watch_sb watch_with_perm watch_reads)))
    <root>
    allow at out/target/product/beyondx/obj/ETC/vendor_sepolicy.cil_intermediates/vendor_sepolicy.cil:2074
      (allow hal_lineage_touch_default default_prop_32_0 (file (read)))
