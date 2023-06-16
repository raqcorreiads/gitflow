import org.junit.jupiter.api.Assertions;
import org.junit.jupiter.api.Test;

public class ComentarioTest {

    @Test
    public void testGettersAndSetters() {
        // Criação de um objeto Comentario para testar os getters e setters
        Comentario comentario = new Comentario();

        // Configuração dos valores usando os setters
        comentario.setId(1L);
        comentario.setEmail("test@example.com");
        comentario.setComentario("Este é um comentário de teste");
        comentario.setTopico("Teste");

        // Verificação dos valores usando os getters
        Assertions.assertEquals(1L, comentario.getId());
        Assertions.assertEquals("test@example.com", comentario.getEmail());
        Assertions.assertEquals("Este é um comentário de teste", comentario.getComentario());
        Assertions.assertEquals("Teste", comentario.getTopico());
    }

    @Test
    public void testConstrutor() {
        // Criação de um objeto Comentario usando o construtor
        Comentario comentario = new Comentario("test@example.com", "Este é um comentário de teste", "Teste");

        // Verificação dos valores usando os getters
        Assertions.assertNull(comentario.getId()); // O ID deve ser gerado automaticamente
        Assertions.assertEquals("test@example.com", comentario.getEmail());
        Assertions.assertEquals("Este é um comentário de teste", comentario.getComentario());
        Assertions.assertEquals("Teste", comentario.getTopico());
    }
}
