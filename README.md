export default () =>
    <div>
        Hello world
        <p>scoped!</p>
        <style jsx>{`
      p {
        color: blue;
      }
      div {
        background: red;
      }
      @media (max-width: 600px) {
        div {
          background: blue;
        }
      }
    `}</style>
        <style global jsx>{`
      body {
        background: black;
      }
    `}</style>
    </div>
    
    
    import "../styles.scss";
    
    export default () => <div className="example">
        <img src="/static/img/xiaodu.png" alt="我的logo" />
        Hello World!</div>;