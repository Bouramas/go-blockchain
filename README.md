# Golang - Blockchain

This is a sample blockchain written in Go.

## Sample Commands

### Create a new blockchain
    go run main.go createblockchain --address "John"

### See the current chain
    go run main.go printchain

### Get the balance of an address
    go run main.go getbalance -address "John"

### Exchange tokens between two addresses
    go run main.go send -from "John" -to "fred" -amount 50

### Delete the existing database / Cleanup
    rm tmp/blocks/*