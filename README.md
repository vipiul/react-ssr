Its project for react with ssr

guide-->>>

1.
ReactDOM.render(<App />, document.getElementById('root'));

 replace with 
 
ReactDOM.hydrate(<App />, document.getElementById('root'));

2.
npm install express

3.
npm install @babel/register @babel/preset-env @babel/preset-react ignore-styles

4.
copy and pest Server folder

5.
npm run build

6.
node server/index.js


regard (vipul)
