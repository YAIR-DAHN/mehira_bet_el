<template>
  <footer class="bg-gradient-to-b from-white to-gray-100 py-10 mt-auto border-t border-gray-100">
    <div class="container-custom">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
        <!-- קישורים מהירים -->
        <div class="text-center">
          <h3 class="text-lg font-bold text-primary-700 mb-4">קישורים מהירים</h3>
          <ul class="space-y-2 flex flex-col items-center">
            <li>
              <router-link to="/" class="text-gray-600 hover:text-primary-600 transition-colors">
                דף הבית
              </router-link>
            </li>
            <li>
              <router-link to="/form" class="text-gray-600 hover:text-primary-600 transition-colors">
                מכירת חמץ
              </router-link>
            </li>
            <li>
              <router-link to="/kimcha" class="text-gray-600 hover:text-primary-600 transition-colors">
                קמחא דפסחא
              </router-link>
            </li>
            <!-- <li>
              <a href="https://63863ecdd7031.site123.me/" target="_blank" class="text-gray-600 hover:text-primary-600 transition-colors">
                אתר הארגון
              </a>
            </li> -->
          </ul>
        </div>
        
        <!-- מידע נוסף -->
        <div class="text-center">
          <div class="flex flex-col items-center">
            <img src="../assets/images/logo.png" alt="לוגו הכולל" class="h-16 mb-4" />
            <p class="text-gray-600 text-sm mt-2">
              בית הכנסת בית אל הרצליה            </p>
            <div class="flex justify-center gap-5 mt-4">
              <!-- <a href="https://wa.me/972504191508" class="text-primary-500 hover:text-primary-700 transition-colors" target="_blank">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
                  <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
                </svg>
              </a> -->
              <a href="mailto:y0548473336@gmail.com" class="text-primary-500 hover:text-primary-700 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
                </svg>
              </a>
              <!-- <a href="https://63863ecdd7031.site123.me/" target="_blank" class="text-primary-500 hover:text-primary-700 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </a> -->
            </div>
          </div>
        </div>
        
        <!-- צור קשר -->
        <div class="text-center">
          <h3 class="text-lg font-bold text-primary-700 mb-4">צור קשר</h3>
          <div class="space-y-2 flex flex-col items-center">
            <div class="flex items-center gap-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-primary-600 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
              <span class="text-gray-600">054-8473336</span>
            </div>
            <div class="flex items-center gap-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-primary-600 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              <span class="text-gray-600">y0548473336@gmail.com</span>
            </div>
            <div class="flex items-center gap-2">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-primary-600 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
              </svg>
              <span class="text-gray-600">העירית 6 הרצליה</span>
            </div>
          </div>
        </div>
      </div>

      <hr class="border-gray-200 mb-8" />
      
      <div class="text-center flex flex-col items-center space-y-4">
        <p class="text-gray-500 text-sm">© 2025 כל הזכויות שמורות לבית הכנסת בית אל הרצליה</p>
        <button 
          @click="showContact = true" 
          class="text-gray-500 hover:text-primary-600 transition-colors text-sm inline-flex items-center"
        >
          <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 ml-1" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
          </svg>
          נבנה ע"י y.d. systems
        </button>
      </div>

      <!-- מודל פרטי יצירת קשר -->
      <div v-if="showContact" class="fixed inset-0 bg-black bg-opacity-50 z-50 flex items-center justify-center p-4" @click="showContact = false">
        <div class="bg-white rounded-lg max-w-md w-full p-6 shadow-xl transform transition-all" @click.stop>
          <div class="flex justify-between items-center mb-6">
            <h3 class="text-2xl font-bold text-gray-800">פרטי יצירת קשר</h3>
            <button @click="showContact = false" class="text-gray-500 hover:text-gray-700 focus:outline-none">
              <span class="text-2xl">&times;</span>
            </button>
          </div>

          <div class="space-y-4">
            <div class="flex items-center gap-3 p-3 bg-primary-50 rounded-lg transition-all hover:scale-105 hover:bg-primary-100">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
              <a href="tel:0583730000" class="text-primary-600 hover:text-primary-700 font-medium">058-373-0000</a>
            </div>

            <div class="flex items-center gap-3 p-3 bg-primary-50 rounded-lg transition-all hover:scale-105 hover:bg-primary-100">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
              </svg>
              <a href="mailto:yairdahn@gmail.com" class="text-primary-600 hover:text-primary-700 font-medium">yairdahn@gmail.com</a>
            </div>

            <div class="flex items-center gap-3 p-3 bg-primary-50 rounded-lg transition-all hover:scale-105 hover:bg-primary-100">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-primary-600" fill="currentColor" viewBox="0 0 24 24">
                <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.626.712.226 1.36.194 1.872.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
              </svg>
              <a href="https://wa.me/972583730000" target="_blank" class="text-primary-600 hover:text-primary-700 font-medium">058-373-0000</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter',
  data() {
    return {
      showContact: false
    }
  }
}
</script>

<style scoped>
a, button {
  transition: all 0.3s ease;
}

.container-custom {
  max-width: 1200px;
  margin-left: auto;
  margin-right: auto;
  padding-left: 1rem;
  padding-right: 1rem;
}
</style> 