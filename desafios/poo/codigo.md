##### prévia do código do Desafio - 


````java
public class iPhone implements iPlayer, iCall, iSafari {

}

````

````java
public interface iPlayer {

	private String artista;

	private String album;
	
	void tocar();

	void pausar();

	String selecionarMusica(String musica);

	String selecionarArtista(String artistaa);

	String selecionarAlbum(String album);

}


````

````java
public interface iCall {

    void ligar(String numero);
    void atender();
    void iniciarCorreioVoz();

}



````


````java
public interface Safari {

	void exibirPagina(String url);

	void adicionarNovaAba();

	void atualizarPagina();

}

````

