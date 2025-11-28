<template>
  <div class="min-h-screen bg-white text-gray-800 font-sans">
    <!-- Navigation Bar -->
    <nav class="fixed top-0 left-0 w-full bg-gray-100 py-4 px-6 flex justify-between items-center z-50 shadow-sm">
      <div class="flex items-center space-x-2">
        <div class="w-10 h-10 rounded-full bg-blue-500"></div>
        <span class="text-xl font-semibold text-gray-700">张伟</span>
      </div>
      <div class="hidden md:flex space-x-6">
        <a href="#home" class="text-gray-600 hover:text-blue-500 transition-colors">首页</a>
        <a href="#about" class="text-gray-600 hover:text-blue-500 transition-colors">关于我</a>
        <a href="#portfolio" class="text-gray-600 hover:text-blue-500 transition-colors">作品集</a>
        <a href="#contact" class="text-gray-600 hover:text-blue-500 transition-colors">联系</a>
      </div>
      <button class="md:hidden text-gray-600">
        <i class="fas fa-bars text-xl"></i>
      </button>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-24 pb-16 px-6 bg-gradient-to-r from-blue-50 to-indigo-50">
      <div class="max-w-6xl mx-auto grid md:grid-cols-2 gap-12 items-center">
        <div>
          <h1 class="text-4xl md:text-5xl font-bold mb-4 text-gray-800">你好，我是 张伟</h1>
          <p class="text-xl text-gray-600 mb-6">资深 UI/UX 设计师 & 前端开发者</p>
          <p class="text-gray-600 mb-8 leading-relaxed">
            拥有 8 年以上互联网产品设计经验，专注于创造优雅且用户友好的数字体验。擅长将复杂问题简化为直观的界面解决方案，致力于通过设计驱动业务增长。
          </p>
          <div class="flex space-x-4">
            <button
              class="!rounded-button whitespace-nowrap bg-blue-500 hover:bg-blue-600 text-white px-6 py-3 transition-colors">
              查看作品集
            </button>
            <button
              class="!rounded-button whitespace-nowrap border border-blue-500 text-blue-500 hover:bg-blue-50 px-6 py-3 transition-colors">
              联系我
            </button>
          </div>
        </div>
        <div class="relative">
          <div class="w-full h-96 bg-gray-200 rounded-2xl overflow-hidden">
            <img src="https://ai-public.mastergo.com/ai/img_res/7bd4d15b67f7fbe5c825be808dae508b.jpg"
              alt="Designer workspace" class="w-full h-full object-cover">
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-6 bg-white">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-16 text-gray-800">关于我</h2>
        <div class="grid md:grid-cols-2 gap-12 items-center">
          <div class="flex justify-center">
            <div class="w-64 h-64 rounded-full overflow-hidden border-4 border-white shadow-lg">
              <img src="https://ai-public.mastergo.com/ai/img_res/8ff98dcd2c3e3156cae5e5acdeea8186.jpg" alt="张伟 头像"
                class="w-full h-full object-cover">
            </div>
          </div>
          <div>
            <h3 class="text-2xl font-semibold mb-4 text-gray-800">张伟 · Senior Product Designer</h3>
            <p class="text-gray-600 mb-6 leading-relaxed">
              我毕业于 清华大学 工业设计专业，拥有超过 8 年的用户体验设计经验。曾在阿里巴巴、腾讯等知名互联网公司担任高级设计师职位，主导过多个千万级用户产品的设计工作。
            </p>
            <p class="text-gray-600 mb-6 leading-relaxed">
              我的设计理念是"以用户为中心，用设计解决问题"。擅长用户研究、交互设计和视觉设计，熟练掌握 Figma、Sketch、Adobe Creative Suite
              等设计工具，同时具备前端开发基础，能够更好地与开发团队协作。
            </p>
            <div class="grid grid-cols-2 gap-4">
              <div class="flex items-center">
                <i class="fas fa-check-circle text-green-500 mr-2"></i>
                <span>UI/UX 设计</span>
              </div>
              <div class="flex items-center">
                <i class="fas fa-check-circle text-green-500 mr-2"></i>
                <span>用户研究</span>
              </div>
              <div class="flex items-center">
                <i class="fas fa-check-circle text-green-500 mr-2"></i>
                <span>原型设计</span>
              </div>
              <div class="flex items-center">
                <i class="fas fa-check-circle text-green-500 mr-2"></i>
                <span>前端开发</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-20 px-6 bg-gray-50">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-4 text-gray-800">我的作品</h2>
        <p class="text-gray-600 text-center mb-16 max-w-2xl mx-auto">
          精选近年来主导和参与的重要项目，涵盖电商、金融、教育等多个领域
        </p>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Project 1 -->
          <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow duration-300">
            <div class="h-48 overflow-hidden">
              <img src="https://ai-public.mastergo.com/ai/img_res/c72c8d88e6275da186cdfd0715b3eea9.jpg" alt="电商平台设计"
                class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2 text-gray-800">智能电商平台</h3>
              <p class="text-gray-600 mb-4">
                为某知名电商企业设计的下一代购物平台，优化用户购物流程，提升转化率 32%
              </p>
              <div class="flex flex-wrap gap-2">
                <span class="px-3 py-1 bg-blue-100 text-blue-600 rounded-full text-sm">UI Design</span>
                <span class="px-3 py-1 bg-green-100 text-green-600 rounded-full text-sm">UX Research</span>
              </div>
            </div>
          </div>

          <!-- Project 2 -->
          <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow duration-300">
            <div class="h-48 overflow-hidden">
              <img src="https://ai-public.mastergo.com/ai/img_res/657f38c9ad60fffeec6804852d4f604f.jpg" alt="金融科技应用"
                class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2 text-gray-800">财富管理应用</h3>
              <p class="text-gray-600 mb-4">
                面向年轻用户的理财助手应用，通过数据可视化帮助用户更好管理资产
              </p>
              <div class="flex flex-wrap gap-2">
                <span class="px-3 py-1 bg-blue-100 text-blue-600 rounded-full text-sm">Mobile Design</span>
                <span class="px-3 py-1 bg-purple-100 text-purple-600 rounded-full text-sm">Data Viz</span>
              </div>
            </div>
          </div>

          <!-- Project 3 -->
          <div class="bg-white rounded-xl overflow-hidden shadow-md hover:shadow-xl transition-shadow duration-300">
            <div class="h-48 overflow-hidden">
              <img src="https://ai-public.mastergo.com/ai/img_res/361c8148740483c6c2fb05e6ec8124a1.jpg" alt="在线教育平台"
                class="w-full h-full object-cover">
            </div>
            <div class="p-6">
              <h3 class="text-xl font-semibold mb-2 text-gray-800">在线教育平台</h3>
              <p class="text-gray-600 mb-4">
                一站式学习管理系统，支持课程创建、学生管理和学习数据分析
              </p>
              <div class="flex flex-wrap gap-2">
                <span class="px-3 py-1 bg-blue-100 text-blue-600 rounded-full text-sm">Web App</span>
                <span class="px-3 py-1 bg-yellow-100 text-yellow-600 rounded-full text-sm">Dashboard</span>
              </div>
            </div>
          </div>
        </div>

        <div class="text-center mt-12">
          <button
            class="!rounded-button whitespace-nowrap border border-blue-500 text-blue-500 hover:bg-blue-50 px-8 py-3 transition-colors">
            查看全部作品
          </button>
        </div>
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-6 bg-white">
      <div class="max-w-6xl mx-auto">
        <h2 class="text-3xl font-bold text-center mb-4 text-gray-800">联系我</h2>
        <p class="text-gray-600 text-center mb-16 max-w-2xl mx-auto">
          如果您有任何项目合作意向或想了解更多信息，请随时与我联系
        </p>

        <div class="grid md:grid-cols-2 gap-12">
          <div>
            <form class="space-y-6">
              <div>
                <label for="name" class="block text-gray-700 mb-2">姓名</label>
                <input type="text" id="name"
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                  placeholder="请输入您的姓名">
              </div>
              <div>
                <label for="email" class="block text-gray-700 mb-2">邮箱</label>
                <input type="email" id="email"
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                  placeholder="请输入您的邮箱">
              </div>
              <div>
                <label for="subject" class="block text-gray-700 mb-2">主题</label>
                <input type="text" id="subject"
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                  placeholder="请输入邮件主题">
              </div>
              <div>
                <label for="message" class="block text-gray-700 mb-2">消息内容</label>
                <textarea id="message" rows="5"
                  class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                  placeholder="请输入您的消息内容"></textarea>
              </div>
              <button type="submit"
                class="!rounded-button whitespace-nowrap w-full bg-blue-500 hover:bg-blue-600 text-white px-6 py-3 transition-colors">
                发送消息
              </button>
            </form>
          </div>

          <div>
            <div class="bg-gray-50 rounded-xl p-8 h-full">
              <h3 class="text-xl font-semibold mb-6 text-gray-800">联系信息</h3>

              <div class="space-y-6 mb-10">
                <div class="flex items-start">
                  <div class="mt-1 mr-4 text-blue-500">
                    <i class="fas fa-envelope text-xl"></i>
                  </div>
                  <div>
                    <h4 class="font-medium text-gray-700 mb-1">邮箱</h4>
                    <p class="text-gray-600">zhangwei@example.com</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="mt-1 mr-4 text-blue-500">
                    <i class="fas fa-phone-alt text-xl"></i>
                  </div>
                  <div>
                    <h4 class="font-medium text-gray-700 mb-1">电话</h4>
                    <p class="text-gray-600">+86 138 0013 8000</p>
                  </div>
                </div>

                <div class="flex items-start">
                  <div class="mt-1 mr-4 text-blue-500">
                    <i class="fas fa-map-marker-alt text-xl"></i>
                  </div>
                  <div>
                    <h4 class="font-medium text-gray-700 mb-1">地址</h4>
                    <p class="text-gray-600">北京市朝阳区建国路 88 号现代城 A 座 1501 室</p>
                  </div>
                </div>
              </div>

              <h3 class="text-xl font-semibold mb-6 text-gray-800">社交媒体</h3>
              <div class="flex space-x-4">
                <a href="#"
                  class="w-12 h-12 rounded-full bg-blue-500 flex items-center justify-center text-white hover:bg-blue-600 transition-colors">
                  <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="#"
                  class="w-12 h-12 rounded-full bg-gray-800 flex items-center justify-center text-white hover:bg-gray-900 transition-colors">
                  <i class="fab fa-github"></i>
                </a>
                <a href="#"
                  class="w-12 h-12 rounded-full bg-blue-400 flex items-center justify-center text-white hover:bg-blue-500 transition-colors">
                  <i class="fab fa-twitter"></i>
                </a>
                <a href="#"
                  class="w-12 h-12 rounded-full bg-pink-500 flex items-center justify-center text-white hover:bg-pink-600 transition-colors">
                  <i class="fab fa-dribbble"></i>
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="py-10 px-6 bg-gray-100 border-t border-gray-200">
      <div class="max-w-6xl mx-auto">
        <div class="flex flex-col md:flex-row justify-between items-center">
          <div class="mb-6 md:mb-0">
            <div class="flex items-center space-x-2">
              <div class="w-8 h-8 rounded-full bg-blue-500"></div>
              <span class="text-lg font-semibold text-gray-700">张伟</span>
            </div>
            <p class="mt-2 text-gray-600 text-sm">© 2023 张伟个人网站. 保留所有权利.</p>
          </div>
          <div class="flex space-x-6">
            <a href="#home" class="text-gray-600 hover:text-blue-500 transition-colors">首页</a>
            <a href="#about" class="text-gray-600 hover:text-blue-500 transition-colors">关于我</a>
            <a href="#portfolio" class="text-gray-600 hover:text-blue-500 transition-colors">作品集</a>
            <a href="#contact" class="text-gray-600 hover:text-blue-500 transition-colors">联系</a>
          </div>
        </div>
        <div class="mt-8 pt-8 border-t border-gray-200 text-center text-gray-500 text-sm">
          <p>Designed and built with ❤️ using Vue.js and Tailwind CSS</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

// Mobile menu state
const mobileMenuOpen = ref(false)

// Toggle mobile menu
const toggleMobileMenu = () => {
  mobileMenuOpen.value = !mobileMenuOpen.value
}
</script>

<style scoped>
/* Custom styles if needed */
</style>
