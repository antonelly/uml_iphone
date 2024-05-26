classDiagram
    iPhone : +funcionalidade1()
    iPhone : +funcionalidad2()
    iPhone <|-- ReprodutorMusical
    iPhone <|-- AparelhoTelefonico
    iPhone <|-- NavegadorInternet
    class ReprodutorMusical{
      +tocar()
      +pausar()
      +SelecionarMusica()
    }
    class AparelhoTelefonico{
      -ligar(String numero)
      -atender()
      -iniciarCorreioVoz()
    }
    class NavegadorInternet{
      +abrirAba()
      +fecharAba()
      +carregarPaginaWeb(String url)
    }