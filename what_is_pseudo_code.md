# What is Pseudo-code?

For this technical exercise, we'd like you to write **pseudo-code** rather than fully functional code. This allows you to focus on your analytical thinking and approach without spending time on implementation details.

## What is pseudo-code?

Pseudo-code is a way to outline your programming logic using a mixture of natural language and code-like structure. It captures the **what** and **how** of your approach without worrying about perfect syntax or working implementations.

## What we're looking for:

- **Function definitions** with clear input/output specifications
- **Docstrings** explaining what each function does
- **High-level logic flow** showing your thought process
- **Key steps** in your analysis, feature engineering, and modeling approach
- **Comments** explaining your reasoning and assumptions

## Example of good pseudo-code:

```python
def explore_missing_values(df):
    """
    Analyze missing value patterns in the dataset
    
    Args:
        df (DataFrame): Raw dataset
        
    Returns:
        dict: Summary of missing value patterns and recommendations
    """
    # Calculate missing value percentages by column
    missing_summary = {}
    
    # Identify columns with >50% missing values
    high_missing_cols = [col for col in df.columns if missing_pct > 0.5]
    
    # Check for patterns in missing values
    # Use visualisation to understand missingness patterns
    
    # Return recommendations for handling each type
    return {
        'drop_columns': high_missing_cols,
        'imputation_strategy': imputation_recommendations,
        'missing_patterns': pattern_analysis
    }
```

## Don't worry about:
- Perfect Python syntax
- Import statements
- Error handling
- Making the code actually run

## Do focus on:
- Clear logic and reasoning
- Appropriate method choices
- Structured approach to the problem
- Demonstrating your data science knowledge