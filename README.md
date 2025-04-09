:root{
    --color-white: #fff;
    --color-blue: rgb(201, 22, 171);
    --color-blue2: rgb(212, 83, 173);
    --color-gray: rgb(238, 238, 238);
}

body{
    all: unset;
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: var(--color-blue);
}

.content{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    background-color: rgba(0,0,0,0.6);
    color: var(--color-white);
    padding: 3rem 4rem;
    border-radius: 1rem;
}

.content input{
    background-color: transparent;
    border: none;
    border-bottom: 1px solid var(--color-gray);
    color: var(--color-white);
    outline: none;
    padding: .4rem;
    width: 50%;
    font-size: 1rem;
}

.content input::placeholder{
    color: var(--color-white);
}

.content input:focus{
    border-bottom: 1px solid var(--color-blue);
}

.content button{
    padding: .8rem;
    width: 80%;
    font-size: 1rem;
    background-color: var(--color-blue2);
    border: none;
    border-radius: 1rem;
    color: var(--color-white);
    margin-top: 2rem;
    cursor: pointer;
    transition: .4s;
}

.content button:hover{
    background-color: var(--color-blue);
}
