const Button = () => {
 const [count, setCount] = useState(0);

 const increment = () => {
    setCount(count + 1);
 };

 return (
    <div>
      <button onClick={increment}>Aumentar Contagem</button>
      <Contador count={count} />
    </div>
 );
};# codigo-3-
