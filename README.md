class User {
    constructor(props){
        this.nombre = props.nombre;
        this.apellido = props.apellido;
        this.localidad = props.localidad;
        this.conocimientos = props.conocimientos;
    };
    
    get conocimientos(){
        return this.conocimientos;
    };
};

const conocimientos =[
    {
        type: 'Frontend',
        Items: ['HTML5', 'CSS3', 'Javascript','Bootsrap', 'Vite', 'React JS']
    },
    {
        type: 'Backend',
        Items: ['NodeJs', 'MongoDB', 'MySQL', 'SQL Server', 'SQLite'],
    },
    {
        type: 'Idiomas',
        Items: ['Ingles', 'Español']
    },
    {
        type: 'Adicionales',
        Items: ['Git', 'JSON', 'Ajax']
    },
    ];


const Esteban = new User({
    nombre: 'Esteban',
    apellido: 'Soraire',
    localidad: 'San Martin, Buenos Aires, Argentina',
})
