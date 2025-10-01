<script>
export default {
  name: "FormularioRegistro", // <- nombre de componente multi-word
  data() {
    return {
      nombre: "",
      edad: "",
      correo: "",
      enviado: false,
    };
  },
  methods: {
    enviarFormulario() {
      this.enviado = true;
    },
  },
};
</script>
