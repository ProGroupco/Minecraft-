library(miner)
# Connect to the server
conn <- mc_connect()

# Get player position
pos <- mc_player_pos(conn)

# Place a diamond block at the player's position
mc_setBlock(conn, pos$x + 1, pos$y, pos$z, id = 57)
