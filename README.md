package sample.model;

public class Livro {
   //atributos
   private String titulo;
   private String autor;
   private String editora;
   private int ano;

   public String getTitulo() {
       return titulo;
   }

   public void setTitulo(String titulo) {
       this.titulo = titulo;
   }

   public String getAutor() {
       return autor;
   }

   public void setAutor(String autor) {
       this.autor = autor;
   }

   public String getEditora() {
       return editora;
   }

   public void setEditora(String editora) {
       this.editora = editora;
   }

   public int getAno() {
       return ano;
   }

   public void setAno(int ano) {
       this.ano = ano;
   }
}


package sample;

import sample.model.Livro;

public class Main {

   public static void main(String[] args){

   Livro livro = new Livro();
   livro.setTitulo("Senhor dos anéis");
   livro.setAutor("J. R. R. Tolkien");
   livro.setEditora("HarperCollins Brasil");
   livro.setAno("2019");


   System.out.println("Livro:" + livro.getTitulo());
   livro.setTitulo("Senhor dos Anéis: duas torres");
   System.out.println("Autor:" + livro.getAutor());
   System.out.println("Editora:" + livro.getEditora());
   System.out.println("Ano:" + livro.getAno());

   }
}


























Endereço 

package sample;

import sample.model.Endereco;

public class Main {

   public static void main(String[] args) {

       Endereco Endereco = new Endereco();
       Endereco.setBairro("Ingleses");
       Endereco.setCidade("Florianópolis");
       Endereco.setNumero(218);
       Endereco.setRua("Rua Recanto do Sol");

       System.out.println("Bairro:" + Endereco.getBairro());
       System.out.println("Cidade:" + Endereco.getCidade());
       System.out.println("Numero:" + Endereco.getNumero());
       System.out.println("Rua:" + Endereco.getRua());

   }
}























Endereço: 

package sample.model;

public class Endereco {
   //atributos
   private String rua;
   private int numero;
   private String bairro;
   private String cidade;

   public String getRua(){
       return rua;
   }

   public void setRua(String rua) {
       this.rua = rua;
   }

   public int getNumero(){
       return numero;
   }

   public void setNumero(int numero) {
       this.numero = numero;
   }

   public String getBairro(){
       return bairro;
   }

   public void setBairro(String bairro) {
       this.bairro = bairro;
   }

   public String getCidade() {
       return cidade;
   }

   public void setCidade(String cidade) {
       this.cidade = cidade;
   }

}




Pessoa:

package sample;

import sample.model.Pessoa;

public class Main  {

   public static void main(String[] args) {

       Pessoa pessoa = new Pessoa();
       pessoa.setNome("Pedro Antônio");
       pessoa.setData("05/12/2003");

       System.out.println("Nome: " + pessoa.getNome());
       System.out.println("Data de nascimento: " + pessoa.getData());

   }
}




























package sample.model;

public class Pessoa {
   //atributos
   private String nome;
   private String data;

   public String getNome() {
       return nome;
   }

   public void setNome(String nome) {
       this.nome = nome;
   }

   public String getData() {
       return data;
   }

   public void setData(String data) {
       this.data = data;
   }
}
