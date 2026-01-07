// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyAkk8Ox0DCTYsUNMd7qCCC9EBMvgLlDZaY",
  authDomain: "perpus-sman5-garut.firebaseapp.com",
  projectId: "perpus-sman5-garut",
  storageBucket: "perpus-sman5-garut.firebasestorage.app",
  messagingSenderId: "329349356070",
  appId: "1:329349356070:web:fa1b8c9d3bfe422be3a4e7",
  measurementId: "G-PY98W20GNN"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);# perpus-sman5-garut
