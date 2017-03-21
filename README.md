# NAME

hashToGff

# SYNOPSIS

Converts a multidimensional hash, as produced by gffToHash.pm, into an array containing one GFF line (with endline "\\n" included) per element.

**Usage**: `@outGff = hashToGff(<gff_hashref>)`
