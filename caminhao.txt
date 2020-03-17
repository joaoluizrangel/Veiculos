package exe4;

public class Caminhao {
	private String marca;
	private String modelo;
	private String combustivel;
	
	public Caminhao (String marca, String modelo, String combustivel){
		this.marca = marca;
		this.modelo = modelo;
		this.combustivel = combustivel;
	}
	public String getMarca(){
		return marca;
	}
	public void setMarca(String marca) {
		this.marca = marca;
	}
	public String getModelo(){
		return modelo;
	}
	public void setModelo(String modelo) {
		this.modelo = modelo;
	}
	public String getCombustivel() {
		return combustivel;
	}
	public void setCombustivel() {
		this.combustivel = combustivel;
	}	
	public void apresentarCaminhao(){
		System.out.println("Marca: " + this.getMarca());
		System.out.println("Modelo: " + this.getModelo());
		System.out.println("Combustivel: " + this.getCombustivel());
	}
}
