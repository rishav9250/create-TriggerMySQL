CREATE TRIGGER trigger_name    
    [before | after]    
   {insert | update | delete}    
    ON table_name [FOR EACH ROW]    
    BEGIN    
        --variable declarations    
        --trigger code    
    END;  
