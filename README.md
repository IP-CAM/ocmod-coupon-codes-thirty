# ocmod-coupon-codes-thirty
30 character coupon codes (ocmod)

You'll also need to update the relevant database table:

```ALTER TABLE `oc_coupon` CHANGE `code` `code` VARCHAR(30) CHARACTER SET utf8 COLLATE utf8_general_ci NOT NULL;```