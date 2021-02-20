wiki
====

shameless repository created so I can have a free personal wiki

  ```mermaid
graph BT

  subgraph todo
    fix_dlc_light_account
    learn_mermaid
  end

  subgraph ideas
    decide_on_retraining_proxy-->develop_retraining
    develop_retraining-->prove_live_retraining_works

    mix_in_qc_algorithm_tuning
    buisness_plan_for_predictor_app
  end

  subgraph skeletor                   
    email_skelator_about_ymca-->email_skelator_about_summer
    research_summer_childcare-->email_skelator_about_summer                
  end     

  subgraph financials               
    retirement_autopilot{retirement autopilot}
    intrum_alloc{interum_alloc}

    subgraph taxes
      should_i_rollover_max_to_roth_each_year-->backdoor_roth_conversion
      prepare_tax_docs
      autotransfer_est_payments_to_money_market_and_back

    end %% taxes

    subgraph long_term_tilt_strategy
      await_new_fundadvice-->implement_advice
      update_review_materials-->await_new_fundadvice
    end %% long_term_tilt_strategy

    subgraph budget
      setup_budget_for_tracking-->update_budget
    end %% budget

    intrum_alloc-->long_term_tilt_strategy
    long_term_tilt_strategy-->retirement_autopilot
    long_term_tilt_strategy-->should_i_rollover_max_to_roth_each_year
    long_term_tilt_strategy-->backdoor_roth_conversion
        
    prepare_tax_docs-->update_budget                                 
  
            

  end %% financials

```

