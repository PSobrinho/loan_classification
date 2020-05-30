# Classificador de empréstimo (loanKNN)

Usando o PyData Stack e o SKLearn será treinado e avaliado um modelo preditivo de classificação com objetivo de ajudar na tomada de decisão para concessão de empréstimos. O DataSample vem do dataset [Loan Data](https://www.kaggle.com/zhijinzhai/loandata) disponível no Kaggle, está estruturado da seguinte forma:

* Loan_id: Valor unico que identifica cada cliente de empréstimo;

* Loan_status: Se o empréstimo foi pago (PAIDOFF) ou está em cobrança (COLLECTION) ou se foi pago após cobrança (COLLECTION_PAIDOFF);

* Principal: Valor principal do empréstimo;

* terms: pode ter agenda de pagamentos semanal (7) bisemanal (15) ou mensal (30);

* Effective_date: quando o empréstimo foi originado;

* Due_date: data de vencimento;

* Paidoff_time: tempo levado pelo cliente para pagar o empréstimo;

* Pastdue_days: dias passados do vencimento;

* Age, education, gender: dados demográficos dos clientes