Comment stuff out.  Then uncomment it later.  Relies on 'commentstring' to be
correctly set, or uses b:commentary_format if it is set.

Assign b:commentary_startofline to insert comment characters at column 1
regardless of indentation.

                                                *gc*
gc{motion}              Comment or uncomment lines that {motion} moves over.

                                                *gcc*
gcc                     Comment or uncomment [count] lines.

                                                *v_gc*
{Visual}gc              Comment or uncomment the highlighted lines.

                                                *o_gc*
gc                      Text object for a comment (operator pending mode
                        only.)

                                                *gcgc* *gcu*
gcgc                    Uncomment the current and adjacent commented lines.
gcu

                                                *:Commentary*
:[range]Commentary      Comment or uncomment [range] lines
