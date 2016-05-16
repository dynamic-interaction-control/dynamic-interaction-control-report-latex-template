cmake_minimum_required(VERSION 2.6)

project(UseLATEX_DOC NONE)

include(cmake/UseLATEX.cmake)

add_latex_document(DIC_report.tex
                    INPUTS header.tex
                           newrap.tex
                           save.tex
                           RR.sty
                    IMAGE_DIRS images/template
)
