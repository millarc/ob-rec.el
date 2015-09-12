# ob-rec.el
create org mode tables from a recutils file

GENERAL

Jose Marchesi created and maintains GNU Recutils which "is a set of tools and libraries to access human-editable, plain text databases called recfiles."  https://www.gnu.org/software/recutils/

DOWNLOAD

git clone git://git.sv.gnu.org/recutils.git

The GNU Recutils package includes a command-line interface, an emacs rec-mode for creating and editing recfiles and ob-rec.el by which those recfiles are read into a table in org-mode.

ob-rec.el DESCRIPTION AND DISCUSSION 

See Jose's and Eric Shulte's thread at Emacs-orgmode https://lists.gnu.org/archive/html/emacs-orgmode/2011-02/msg00814.html
or at gmane  http://thread.gmane.org/gmane.emacs.orgmode/37697/focus=37750 

A recfile can contain different types of records and each record type has field lables and corresponding values.   ob-rec.el then can used to create a table which may be exported to a LaTeXpdf document for instance. A document template in org-mode format can be used to generates separate reports from corresponding recfiles. 

EXAMPLE

(to follow)
