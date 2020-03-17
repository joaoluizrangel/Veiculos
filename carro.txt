package exe4;

public class Carro {
	protected String marca;
	protected String modelo;
	protected String combustivel;
	
	public Carro (String marca, String modelo, String combustivel){
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
	public void apresentarCarro(){
		System.out.println("Marca: " + this.getMarca());
		System.out.println("Modelo: " + this.getModelo());
		System.out.println("Combustivel: " + this.getCombustivel());
	}
}
