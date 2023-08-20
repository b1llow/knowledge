# nginxWebUI runCmd远程命令执行

## 漏洞描述
nginxWebUI是一款图形化管理nginx配置得工具, 可以使用网页来快速配置nginx的各项功能。nginxWebUI runCmd 接口存在远程命令执行漏洞，攻击者通过漏洞可以获取到服务器权限，执行任意命令。

## <radar-chart-outlined /> 影响范围
nginxWebUI <= 3.5.0

## <eye-outlined /> 资产测绘
<a-typography-paragraph :copyable="{ tooltip: false }" style="font-size: 16px">
  app="nginxWebUI"
</a-typography-paragraph>

## 漏洞复现


## POC&EXP

<script lang="ts" setup>
  import { RadarChartOutlined, EyeOutlined } from '@ant-design/icons-vue';
</script>
