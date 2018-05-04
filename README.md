# orthoMCLtoVennDiagramm

It takes the output from OrthoMCL, gives you the orthologous Venn Diagramm of species listed by you.


# input files

groups.txt - this is the output from orthoMCL

singletons.txt - this file is produced by running orthoMCL's orthomclSingletons and contains all genes that are contained in no groups

families.txt - this file details which species are in which groups, first the name of the group, then the short handles that appear in groups.txt. Example:

# Running it

python OrthoMCLtoVennDiagramm.py -h

usage: OrthoMCLtoVennDiagramm.py groups singletons families 

# positional arguments:
    groups      -Path to groups.txt
    
    singletons  -Path to singletons file (use orthomclSingletons, part of
    orthomcl)
    
    families    -Path to list file detailing groups of species/families
   
 Install cpanm to make installing other modules easier (you'll thank us later). You need to type these commands into a Terminal emulator (Mac OS X, Win32, Linux)

cpan App::cpanminus

Now install any module you can find.

cpanm Module::Statistics::R module
