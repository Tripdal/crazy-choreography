# Choreografie

A tool for designing choreography for a dance group. It is a single HTML file that runs offline in the browser with nothing to install.

**Open `choreografie.html` in Google Chrome or Microsoft Edge.** Video export to MP4 needs a recent Chrome or Edge.

## Tabs

1. **Lidičky** (Kids): groups and the dancers' names. To add several names at once, separate them with commas.
2. **Prvky** (Sets): a top-down view of the dance floor.
   - **Start**: the starting positions of the dancers.
   - **+** adds a frame. Drag the balls along the path they should follow, then click **Použít** (Apply). Everyone you dragged moves at the same time.
   - Shift+click, or dragging a box around balls, selects several dancers so you can drag them together.
   - Sets can be copied (⧉) and played back.
3. **Tanec** (Dance): put sets in order and insert **+ přechod** (transition) between them.
   - In a transition you see the previous set's positions solid and the next set's positions semi-transparent. Dancers you don't drag go in a straight line.
   - **🎵 Hudba** (Music) loads a track. The timeline shows its waveform below.
   - Drag the end of a block to change its length. Double-click a block to type an exact length. Ctrl+wheel zooms. Space plays and pauses.
   - **Export videa** records the video with the music, with the set names in large letters at the top.

## Saving

Your work is saved automatically in the browser. To back it up or move it to another computer, use **💾 Uložit projekt** (Save project) and **📂 Otevřít projekt** (Open project), which write and read a `.json` file. Music is not stored inside the project. After opening a project, select the music file again with **🎵 Hudba**. It's easiest to keep it in the same folder as the HTML file.
