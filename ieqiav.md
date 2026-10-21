代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtzvhincfe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtcsaatnje.html

[U60] PHP：JSON 编解码
来源：http://dali.tian-w.cn/Article/details/gtxdfpaesl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtvysvhofv.html

[U61] PHP：正则
来源：http://dali.yanxiufei.cn/Article/details/gtdeirfzzu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtykdbzjic.html

[U62] PHP：日期对象
来源：http://dali.hysaishi.cn/Article/details/gtypsfbrep.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gtpzygvyrv.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gtugahhubu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtfxqqthba.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gtwyxedbpf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gtjlryqugm.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gtifhkxxcy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtxquimqub.html

[U66] PHP：设置 Cookie
来源：http://dali.snrcjt.cn/Article/details/gtrovejhlr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gtenrdxrie.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gtagoooall.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gtcappoivx.html

[U68] PHP：PDO 连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvbucnxi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gttindlecq.html

[U69] PHP：PDO 预处理
来源：http://dali.aizwys.cn/Article/details/gtlvqdymja.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhengqikj.top/Article/details/gtqemagisi.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gtpxewtjvb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cashguo.top/Article/details/gtqcfyuplj.html

[U71] PHP：抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtpmvpueho.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtlahuplzs.html

[U72] PHP：写错误日志
来源：http://dali.andypj.xyz/Article/details/gtuyixuypl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jiagoushi.top/Article/details/gthaxhslud.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gtsucijaim.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gtrrjygupq.html

[U74] PHP：读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtixnyduxj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtynlfxmig.html

[U75] PHP：依赖注入
来源：http://dali.vqdsnc.cn/Article/details/gtiiohsoch.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gtcjbgbikk.html

[U76] PHP：简单路由
来源：http://dali.hysaishi.cn/Article/details/gtxszoffeg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yangfankeji.com/Article/details/gtaccofylx.html

[U77] PHP：模板渲染
来源：http://dali.daria6918.cn/Article/details/gthkbjcmie.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gtnwvbibfv.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtcqklurcr.html

composer require --dev phpunit/phpunit
来源：http://dali.bjfxy.top/Article/details/gtqzexpibu.html

[U79] PHP：静态分析
来源：http://dali.jqgufenzy.top/Article/details/gtmbgyewjd.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gtrqoummcj.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gtyzvmidsc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hysaishi.cn/Article/details/gtqwugcdal.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gtbunwpuqh.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gtamasoneh.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gtjajpveos.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.redwolf501.top/Article/details/gtkgzgbsjh.html

[U83] JS：ES Module 导入导出
来源：http://dali.fzhhl.top/Article/details/gtjdouihsw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gtzrylmdmj.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtbbfaakpw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aizwys.cn/Article/details/gtgxozcyrz.html

[U85] JS：可选链
来源：http://dali.pengpengdd.cyou/Article/details/gtygwiifzl.html

a?.b?.c
来源：http://dali.yj20258.top/Article/details/gtfzqilsrf.html

[U86] JS：空值合并
来源：http://dali.jianghu66.top/Article/details/gtntrhvgqd.html

a ?? b
来源：http://dali.svipenyu.cn/Article/details/gteoikbypk.html

[U87] JS：解构默认值
来源：http://dali.316326.xyz/Article/details/gtzepakqrb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xziqi.cn/Article/details/gtgbjwmtuy.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gtgmftsyiq.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gtqygxrpgr.html

[U89] JS：数组去重
来源：http://dali.xuanzx.com/Article/details/gtpahfyejj.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtgkhfzmou.html

[U90] JS：数字数组排序
来源：http://dali.jlsjyb.cn/Article/details/gtkvvkiluf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxljsptm.html

[U91] JS：对象键值遍历
来源：http://dali.ydzc1.top/Article/details/gtnbyuarud.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gthijegveh.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkxzzvdz.html

structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtgbdnehhs.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gtovlyspdk.html

`共 ${n} 条`
来源：http://dali.cheryme.top/Article/details/gttcazuqyu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtnbpahels.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtgrgyqhlh.html

[U95] JS：Promise 包装
来源：http://dali.sufxvd.cn/Article/details/gtvtqvahkx.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtefepvxos.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gtstuvrngg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtuhrnveua.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtkbyyjrdo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gttskheikw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtpxzrkqcd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyqkopcq.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtfwqsewqt.html

el.addEventListener("click", e => {})
来源：http://dali.aibaodan.cn/Article/details/gtkvfjngtp.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaoawvmvb.html

document.querySelector(".item")
来源：http://dali.cucudq.cn/Article/details/gtgsweycmd.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gtgtkbaebv.html

el.classList.toggle("active")
来源：http://dali.9152youxi.cn/Article/details/gtepzcagzw.html

[U102] JS：本地存储
来源：http://dali.chenjidiqi.icu/Article/details/gtaesmtybm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gtbygsjvvt.html

[U103] JS：定时器
来源：http://dali.xinyue.icu/Article/details/gtjmwocjgr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gtripqjvev.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtivtfcctk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtvqwznmbx.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gttflyujii.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fengsongda.top/Article/details/gtraigyckp.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gthmoxcgke.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gttnziomqz.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtrryrkhla.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtqrunqbhv.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gtgfktrqln.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgxwxemk.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gtczbsrgcu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.havefunace.top/Article/details/gtotsmcgzr.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtebjendiq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gttgrtmluz.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtgubdmemp.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtwyybftnt.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtpmtesmkp.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtamzkqssf.html

[U113] JS：正则替换全部
来源：http://dali.nwbrower.top/Article/details/gtxruihzoy.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtocxmaczd.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtskrrupjm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtfxigohuo.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtrjqyzugh.html

crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gtaksjujzr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gtlyxqjxqn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtftnqltmh.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gttablbgnj.html

npm i -D vitest;  npx vitest
来源：http://dali.xinyue.icu/Article/details/gtpmsnhnwi.html

[U118] JS：开发服务器
来源：http://dali.ivvv.top/Article/details/gthyrawffn.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtsldulcts.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gttmztwrhw.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gthfitcway.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gtaqevmmae.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gtsgbcpori.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpjwuxqhf.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gtzxxkipuz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgngfznhy.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gtxqzfarag.html

Python ......... 252
来源：http://dali.xuetiantiany.cn/Article/details/gtmmwdmghs.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtlaitepda.html

JavaScript ..... 252
来源：http://dali.ivvv.top/Article/details/gtqyxlzdjv.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtsemqdion.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gtdbzszrls.html

Go ............. 212
来源：http://dali.yangfankeji.com/Article/details/gthnkkcxbq.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtizscihxc.html

C# ............. 212
来源：http://dali.sysykeji.top/Article/details/gttfznvifx.html

C .............. 30
来源：http://dali.nwbrower.top/Article/details/gttjadgymi.html

C++ ............ 30
来源：http://dali.havefunace.top/Article/details/gtkfxyogwy.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gttxwmztbt.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gtmhdbtdom.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtqvcxrawh.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtfkvurwix.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtdcmwjtmu.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtthvveuob.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gtztbesipx.html

------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtznctwviw.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtltnqntyi.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtzlwokaun.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtotulfpzu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtunzzwpmo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtaqgpxhly.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcympamw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.kuanghao11.cn/Article/details/gtrcgajzem.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtsvmkphpj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gtdygbdtcv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtzpoopyea.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtetutukwy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gthbbeazxy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtphuqcprc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtsmjopxyr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtslrrvreq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.haohaochexian.top/Article/details/gtqugrqyja.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cucudq.cn/Article/details/gtkmlivekl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtnbbkzhfk.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtwczcfhod.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gtayhbtuhp.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gtuecabivq.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gtxcvopeor.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gtulhbbxwf.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtqetxqhfe.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gtvzckiaoi.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujuiwrme.html

使用提醒
来源：http://dali.sxryk.cn/Article/details/gtdmansity.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtcnphpfog.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtqgjnxzop.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gtdshnlpgb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtpuoipkvo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtbqsprtzz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zycfv.cn/Article/details/gtoxisrxgm.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtbefhlfvo.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzwdvnutf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gtuyklthrq.html

Common Programming Examples Cheat Book
来源：http://dali.nanxuanxn.top/Article/details/gtefjhgabr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwuyimfzx.html

【收录内容】
来源：http://dali.birdmap.top/Article/details/gtjwebdnky.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yongpay.top/Article/details/gtqweruzdh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ivvv.top/Article/details/gtwagestxz.html

SQL · Bash · C · C++
来源：http://dali.yongpay.top/Article/details/gtbxtwgjrm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtxvesomrg.html

【使用说明】
来源：http://dali.shuidangran.top/Article/details/gthsrxhzgk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxgysjws.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.meibo888.top/Article/details/gtvsypzdgm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtpiikubcg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cheryme.top/Article/details/gtmevffscj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gtgnubelah.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.andypj.xyz/Article/details/gtxyhhipeo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gttdwlwcld.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hysaishi.cn/Article/details/gtapgyysli.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yonumen.top/Article/details/gtvlpewiuu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gotoacloud.top/Article/details/gtxmitdwzb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxpstwlz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gtwehoetcs.html

【文件统计】
来源：http://dali.yanxiufei.cn/Article/details/gtubvxatgv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.birdmap.top/Article/details/gtwyzqgsmq.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtrqyetqok.html

目  录
来源：http://dali.meibo888.top/Article/details/gtbpjrmfxf.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtdlwndhji.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtnnwnniwn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yanxiufei.cn/Article/details/gtkaimfjid.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtbaskugpk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aizwys.cn/Article/details/gtgbdszyxl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gttcftlyaa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtaxlukbcz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gttnmyyiro.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgssvebsv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkqimqis.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtkyxduskb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtgeawpudb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtexoslqqi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtuzsfprrf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinqigufen.top/Article/details/gtzqnfhhqg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cqqwz.cn/Article/details/gtbhpsnezh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtmkaezwlg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gtajhabgkf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtsyfxzkcd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cqqwz.cn/Article/details/gtdrloqgqx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtjaopcuvz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtowepehsr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtiihwdkwh.html

A. 基础语法与类型
来源：http://dali.jlsjyb.cn/Article/details/gtvsxlhspg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkmgoiisk.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtmwufqwdy.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarxaezwe.html

PHP:  echo "Hello, World!";
来源：http://dali.dashuyun.cn/Article/details/gtnozeswrv.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfikkzmp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hongshengwenyu.top/Article/details/gtnpbgspwe.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtsucykhww.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtherssvnl.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gtxbquplkv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.cdnleiting.top/Article/details/gtfvwttoak.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymtvcjrr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gttuygetgx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj202588.top/Article/details/gtagoqutdd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gtslzeefxd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtjqtufond.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daria6918.cn/Article/details/gtskodqfhd.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtxwqodzxi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cqqwz.cn/Article/details/gtmzrwnxpg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gthwtmdris.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gtarqulcvn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtyialwmar.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtntmbfzwo.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtevcteubz.html

TS:   const PI: number = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtftxylqap.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtzfyhstxw.html

Go:   const PI = 3.14159
来源：http://dali.fzhhl.top/Article/details/gtzshdrfce.html

Ruby: PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gtvaqxnaew.html

C#:   const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gttcpgdojr.html

[A04] 判断变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxvefuab.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gtmmckvthe.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gthrjwleyc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtwhpyufud.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvsugrfi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gtmtnehuae.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gtshnmdjwn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtuyhgrzmn.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj20258.top/Article/details/gtkxxzuvkq.html

[A05] 整数除法与取模
来源：http://dali.yongpay.top/Article/details/gtljiyurhg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtaujhmrii.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtgbrvaksc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtsjfwzjsj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtynlcdwxx.html

Java: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtexavaiok.html

Go:   7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtprzohpfo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtvonjqzry.html

C#:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtujdfutby.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gttxmzcthc.html

Py:   int("42"); float("3.14")
来源：http://dali.0kj1m.cn/Article/details/gthvtwdudd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gthkovdlwf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxmqvlkj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtmvdoolkm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtemqrfobx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdojqrmeo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ivvv.top/Article/details/gtpvfdtcqj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.smart0.xyz/Article/details/gtmcarjyrs.html

[A07] 数字转字符串
来源：http://dali.xinyue.icu/Article/details/gtizznmrsx.html

Py:   str(42)
来源：http://dali.bjfxy.top/Article/details/gtzopayvxc.html

PHP:  (string) 42; strval(42)
来源：http://dali.iojbl.cn/Article/details/gtzydarolv.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtdjsjgumg.html

TS:   String(42)
来源：http://dali.jinqigfzy.top/Article/details/gtjbbrbmit.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangdashe.top/Article/details/gtmflzuyye.html

Go:   strconv.Itoa(42)
来源：http://dali.jianghu66.top/Article/details/gtklmwudpu.html

Ruby: 42.to_s
来源：http://dali.yuxming.cn/Article/details/gtngtnmyrh.html

C#:   42.ToString()
来源：http://dali.redwolf501.top/Article/details/gthnbcxzpe.html

[A08] 取整与四舍五入
来源：http://dali.andypj.xyz/Article/details/gttewormym.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtbdivnxka.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.iojbl.cn/Article/details/gtfjorzksd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtzmlbumws.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuanzhike.top/Article/details/gtcjhubklo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gteklwcyke.html


<!-- 参考信息 -->