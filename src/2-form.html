const formEl = document.querySelector('.feedback-form');
const STORAGE_KEY = 'feedback-form-state';

let formData = {
  email: '',
  message: '',
};

const savedState = localStorage.getItem(STORAGE_KEY);
if (savedState) {
  formData = JSON.parse(savedState);
  formEl.elements.email.value = formData.email;
  formEl.elements.message.value = formData.message;
}

formEl.addEventListener('input', event => {
  const { name, value } = event.target;

  if (name) {
    formData[name] = value.trim();
    localStorage.setItem(STORAGE_KEY, JSON.stringify(formData));
  }
});

formEl.addEventListener('submit', event => {
  event.preventDefault();

  const { email, message } = formData;

  if (!email || !message) {
    alert('Fill please all fields');
    return;
  }

  console.log(formData);

  localStorage.removeItem(STORAGE_KEY);
  formEl.reset();
  formData = { email: '', message: '' };
});
