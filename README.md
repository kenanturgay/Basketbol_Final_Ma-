# Basketbol_Final_Match


Arrow Func. &amp;  Backtick

In this project, we need an application that gives a summary of a simulated match in sentences. The previous team started this work but did not finish it. Now, you need to complete the macOzeti function following these rules:
    
    Create a function named macOzeti.
    This function should take two parameters: homeTeam and awayTeam.
    In every period of the match, generate random scores for homeTeam and awayTeam. (In final matches, teams usually score between 12 and 26 points per period).
    Add the period scores to an array like this: "1st Period: {homeTeam} 10 - {awayTeam} 21".
    Add the final score for homeTeam as:
    "Final Score: {homeTeam} 61 - 54 won" or
    "Final Score: {homeTeam} 61 - 68 lost".
    If the match ends in a tie, write "The match ended 61 - 61 and went to overtime".
    Example Usage:
    
    javascript
    Copy code
    macOzeti("Real Madrid", "Barcelona");
    Example Output 1:
    
    javascript
    Copy code
    [
    	"1st Period: Real Madrid 10 - Barcelona 21",
    	"2nd Period: Real Madrid 30 - Barcelona 34",
    	"3rd Period: Real Madrid 43 - Barcelona 43",
    	"4th Period: Real Madrid 61 - Barcelona 54",
    	"Final Score: Real Madrid 61 - 54 won"
    ]
    Example Output 2:
    
    javascript
    Copy code
    [
    	"1st Period: Real Madrid 10 - Barcelona 21",
    	"2nd Period: Real Madrid 30 - Barcelona 34",
    	"3rd Period: Real Madrid 43 - Barcelona 43",
    	"4th Period: Real Madrid 61 - Barcelona 68",
    	"Final Score: Real Madrid 61 - 68 lost"
    ]
    Example Output 3:
    
    javascript
    Copy code
    [
    	"1st Period: Real Madrid 10 - Barcelona 21",
    	"2nd Period: Real Madrid 30 - Barcelona 34",
    	"3rd Period: Real Madrid 43 - Barcelona 43",
    	"4th Period: Real Madrid 61 - Barcelona 61",
    	"The match ended 61 - 61 and went to overtime"
    ]






