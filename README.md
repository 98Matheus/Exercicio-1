# Exercicio-1

         static void Main (string [] args)
        {
            para (int i = 0; i <7; i ++)
            {

            int Ds = 0;
            Console.WriteLine ("Informe um número correspondente aos dias da semana:");
            Ds = int.Parse (Console.ReadLine ());



                interruptor (Ds)
                {
                    caso 1:
                        Console.WriteLine ("Hoje é Domingo:");
                        Console.WriteLine ("O primeiro dia da semana, cuidado... amanhã é segunda:");
                        quebrar;

                    caso 2:
                        Console.WriteLine ("Hoje é Segunda-Feira:");
                        Console.WriteLine ("O dia mais arrastado da semana...");
                        quebrar;

                    caso 3:
                        Console.WriteLine ("Hoje é Terça-Feira:");
                        Console.WriteLine ("Ainda hoje é terça:");

                        quebrar;

                    caso 4:
                        Console.WriteLine ("Hoje é Quarta-Feira:");
                        Console.WriteLine ("Opa, tá no meio da semana:");
                        quebrar;

                    caso 5:
                        Console.WriteLine ("Hoje é Quinta-Feira:");
                        Console.WriteLine ("Um dia antes de SEXTA! Mas dê uma segurada... ainda tem um chãozinho:");
                        quebrar;

                    caso 6:
                        Console.WriteLine ("Hoje é Sexta-Feira:");
                        Console.WriteLine ("OPAHHH! Sextou, fihhh:");
                        quebrar;

                    caso 7:
                        Console.WriteLine ("Hoje é Sábado:");
                        Console.WriteLine ("S de sabadou:");
                        quebrar;

                    padrão:
                        Console.WriteLine ("Número não definido:");
                        quebrar;
                }
}
            Console.ReadLine ();

        }

    }
