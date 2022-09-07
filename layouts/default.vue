<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;300;400;500;700;800&display=swap');

:root {
    /* Color styles */
  --primary: #040BFB;
  --secondary: #C02C0C;
  --primary-hover: #3136FF;
  --secondary-hover: #FF441B;
  --transparent: rgba(217, 217, 217, 0.0);
  --black: #000000;
  --white: #FFFFFF;
  --gray--50: #F9FAFB;
  --gray--100: #F3F4F6;
  --gray--200: #E5E7EB;
  --gray--300: #D1D5DB;
  --gray--400: #9CA3AF;
  --gray--500: #6B7280;
  --gray--600: #4B5563;
  --gray--700: #374151;
  --gray--800: #1F2937;
  --gray--900: #111827;
  --gray--50: #F9FAFB;
  --gray--100: #F3F4F6;
  --gray--200: #E5E7EB;
  --gray--300: #D1D5DB;
  --gray--400: #9CA3AF;
  --gray--500: #6B7280;
  --gray--600: #4B5563;
  --gray--700: #374151;
  --gray--800: #1F2937;
  --gray--900: #111827;
  --red--50: #FEF2F2;
  --red--100: #FEE2E2;
  --red--200: #FECACA;
  --red--300: #FCA5A5;
  --red--400: #F87171;
  --red--500: #EF4444;
  --red--600: #DC2626;
  --red--700: #B91C1C;
  --red--800: #991B1B;
  --red--900: #7F1D1D;
  --red--50: #FEF2F2;
  --red--100: #FEE2E2;
  --red--200: #FECACA;
  --red--300: #FCA5A5;
  --red--400: #F87171;
  --red--500: #EF4444;
  --red--600: #DC2626;
  --red--700: #B91C1C;
  --red--800: #991B1B;
  --red--900: #7F1D1D;
  --yellow--50: #FFFBEB;
  --yellow--100: #FEF3C7;
  --yellow--200: #FDE68A;
  --yellow--300: #FCD34D;
  --yellow--400: #FBBF24;
  --yellow--500: #F59E0B;
  --yellow--600: #D97706;
  --yellow--700: #B45309;
  --yellow--800: #92400E;
  --yellow--900: #78350F;
  --yellow--50: #FFFBEB;
  --yellow--100: #FEF3C7;
  --yellow--200: #FDE68A;
  --yellow--300: #FCD34D;
  --yellow--400: #FBBF24;
  --yellow--500: #F59E0B;
  --yellow--600: #D97706;
  --yellow--700: #B45309;
  --yellow--800: #92400E;
  --yellow--900: #78350F;
  --green--50: #ECFDF5;
  --green--100: #D1FAE5;
  --green--200: #A7F3D0;
  --green--300: #6EE7B7;
  --green--400: #34D399;
  --green--500: #10B981;
  --green--600: #059669;
  --green--700: #047857;
  --green--800: #065F46;
  --green--900: #064E3B;
  --green--50: #ECFDF5;
  --green--100: #D1FAE5;
  --green--200: #A7F3D0;
  --green--300: #6EE7B7;
  --green--400: #34D399;
  --green--500: #10B981;
  --green--600: #059669;
  --green--700: #047857;
  --green--800: #065F46;
  --green--900: #064E3B;
  --blue--50: #EFF6FF;
  --blue--100: #DBEAFE;
  --blue--200: #BFDBFE;
  --blue--300: #93C5FD;
  --blue--400: #60A5FA;
  --blue--500: #3B82F6;
  --blue--600: #2563EB;
  --blue--700: #1D4ED8;
  --blue--800: #1E40AF;
  --blue--900: #1E3A8A;
  --blue--50: #EFF6FF;
  --blue--100: #DBEAFE;
  --blue--200: #BFDBFE;
  --blue--300: #93C5FD;
  --blue--400: #60A5FA;
  --blue--500: #3B82F6;
  --blue--600: #2563EB;
  --blue--700: #1D4ED8;
  --blue--800: #1E40AF;
  --blue--900: #1E3A8A;
  --indigo--50: #EEF2FF;
  --indigo--100: #E0E7FF;
  --indigo--200: #C7D2FE;
  --indigo--300: #A5B4FC;
  --indigo--400: #818CF8;
  --indigo--500: #6366F1;
  --indigo--600: #4F46E5;
  --indigo--700: #4338CA;
  --indigo--800: #3730A3;
  --indigo--900: #312E81;
  --indigo--50: #EEF2FF;
  --indigo--100: #E0E7FF;
  --indigo--200: #C7D2FE;
  --indigo--300: #A5B4FC;
  --indigo--400: #818CF8;
  --indigo--500: #6366F1;
  --indigo--600: #4F46E5;
  --indigo--700: #4338CA;
  --indigo--800: #3730A3;
  --indigo--900: #312E81;
  --purple--50: #F5F3FF;
  --purple--100: #EDE9FE;
  --purple--200: #DDD6FE;
  --purple--300: #C4B5FD;
  --purple--400: #A78BFA;
  --purple--500: #8B5CF6;
  --purple--600: #7C3AED;
  --purple--700: #6D28D9;
  --purple--800: #5B21B6;
  --purple--900: #4C1D95;
  --purple--50: #F5F3FF;
  --purple--100: #EDE9FE;
  --purple--200: #DDD6FE;
  --purple--300: #C4B5FD;
  --purple--400: #A78BFA;
  --purple--500: #8B5CF6;
  --purple--600: #7C3AED;
  --purple--700: #6D28D9;
  --purple--800: #5B21B6;
  --purple--900: #4C1D95;
  --pink--50: #FDF2F8;
  --pink--100: #FCE7F3;
  --pink--200: #FBCFE8;
  --pink--300: #F9A8D4;
  --pink--400: #F472B6;
  --pink--500: #EC4899;
  --pink--600: #DB2777;
  --pink--700: #BE185D;
  --pink--800: #9D174D;
  --pink--900: #831843;
  --pink--50: #FDF2F8;
  --pink--100: #FCE7F3;
  --pink--200: #FBCFE8;
  --pink--300: #F9A8D4;
  --pink--400: #F472B6;
  --pink--500: #EC4899;
  --pink--600: #DB2777;
  --pink--700: #BE185D;
  --pink--800: #9D174D;
  --pink--900: #831843;

  /* Text-size styles */
  /* base size: body (16px) */
  --text: 0.75rem;
  --section: 2.5rem;
  --heading: 2.25rem;
  --subheading: 1.5rem;
  --caption: 0.88rem;
  --body: 1rem;

  /* Effect styles */
  --elevation-01:  2px 5px 8px rgba(0, 0, 0, 0.83);
  --elevation-02:  2px 12px 18px rgba(0, 0, 0, 0.57);
  --elevation-03:  2px 16px 22px rgba(0, 0, 0, 1);
  --elevation-04:  2px 23px 30px rgba(0, 0, 0, 0.96);

}
.btn {
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 25px;
  padding-right: 25px;
  text-decoration: none;
  color: var(--white);
  border-radius: 5px;
}
.primary {
  background: var(--primary);
}
.secondary {
  background: var(--secondary)
}
body {
  background: var(--gray--300);
}
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}
.row {
  display: flex;
  flex-dirextion: row;
}
.col {
  display: flex;
  flex-dirextion: column;
}

.primary:hover {
  background: var(--primary-hover);
}
.spacer-01 {
  height: 10px;
  width: 1px;
  display: flex;
  position: relative;
}
.spacer-02 {
  height: 20px;
  width: 1px;
  display: flex;
  position: relative;
}
.spacer-03 {
  height: 30px;
  width: 1px;
  display: flex;
  position: relative;
}
.spacer-04 {
  height: 40px;
  width: 1px;
  display: flex;
  position: relative;
}
input {
  border: 2px solid var(--gray--500);
  padding-left: 5px;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-right: 5px;
  border-radius: 5px;
  min-width: 300px;
}
.btn-outline-primary {
  border: 2px solid var(--primary);
  color: var(--primary);
  background: var(--transparent);
  text-decoration: none;
  padding-left: 25px;
  padding-right: 25px;
  padding-top: 10px;
  padding-bottom: 10px;
  transition: all .3s ease-out;
  min-width: 140px;
  font-weight: 600;
  border-radius: 5px;
}
.btn-outline-secondary {
  border: 2px solid var(--secondary);
  color: var(--secondary);
  background: var(--transparent);
  text-decoration: none;
  padding-left: 25px;
  padding-right: 25px;
  padding-top: 10px;
  padding-bottom: 10px;
  transition: all .3s ease-out;
  min-width: 140px;
  font-weight: 600;
  border-radius: 5px;
}
.spacer-wide-02 {
  width: 20px;
  height: 1px;
  position: relative;
}
.justify-center {
  justify-content: center;
}
.align-center {
  align-items: center;
}
.btn-outline-secondary:hover {
  background: var(--secondary);
  color: var(--white);
}
.btn-outline-primary:hover {
  background: var(--primary);
  color: var(--white);
}
</style>
