代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtsdkritie.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtoumnayft.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gtxyqusmbn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jianghu66.top/Article/details/gtuelyfqqd.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gtwlvhgvkm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtkcqicgpr.html

[U62] PHP：日期对象
来源：http://dali.cucudq.cn/Article/details/gtqopytnwa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gtptetatex.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gtiqincipv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guowangkeji.top/Article/details/gtykqduqge.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gtsgtlofbj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj20258.top/Article/details/gtervlqvvr.html

[U65] PHP：会话
来源：http://dali.zhixingplan.top/Article/details/gtxuzeibtu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gtpweurvwq.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gtirbxadvz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gtpidqvzio.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gttjgbyyyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gtafrezoql.html

[U68] PHP：PDO 连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdupymizi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtdxknujbw.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gtloacsfbf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gtqgretewa.html

[U70] PHP：PDO 事务
来源：http://dali.nanxuanxn.top/Article/details/gtqdyijoho.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.aibaodan.cn/Article/details/gteclmgumr.html

[U71] PHP：抛出异常
来源：http://dali.iojbl.cn/Article/details/gtcfihvlya.html

throw new RuntimeException("失败", 500);
来源：http://dali.haohaochexian.top/Article/details/gtplzdqukd.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gtipghlrll.html

error_log("失败: " . $e->getMessage());
来源：http://dali.birdmap.top/Article/details/gtuymevpuv.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gttimfedys.html

parse_ini_file("config.ini", true)
来源：http://dali.havefunace.top/Article/details/gtimmnxzqg.html

[U74] PHP：读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtwlbyhiqe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tanke756.top/Article/details/gtbahkhysg.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gtipxefiff.html

composer require psr/container
来源：http://dali.aizwys.cn/Article/details/gtpfjkqwmw.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtjtmaqrvf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtvvpicaog.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkltpjea.html

composer require twig/twig
来源：http://dali.c1oappe.top/Article/details/gtpjyyoyja.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gtmrvbwrej.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtxcciooyp.html

[U79] PHP：静态分析
来源：http://dali.jqgufenzy.top/Article/details/gtggmnroam.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtstvmnwva.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gtuebmvpfk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.0kj1m.cn/Article/details/gthlfosxzv.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gtdpontbey.html

npm init -y;  npm i express
来源：http://dali.cqqwz.cn/Article/details/gtfoxlklca.html

[U82] JS：package.json 脚本
来源：http://dali.316326.xyz/Article/details/gtbzbzjyie.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gtsjcoqlbu.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gttopgzhnb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtyfopqakz.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtffjymwxv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaeixpoff.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gthvkhteof.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gtnavawdnw.html

[U86] JS：空值合并
来源：http://dali.yvedp.cn/Article/details/gtmjgawymc.html

a ?? b
来源：http://dali.xuetiantiany.cn/Article/details/gtxxjyuloy.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gtesgadmqv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnqzz.top/Article/details/gtjkxiligb.html

[U88] JS：对象展开合并
来源：http://dali.hongshengwenyu.top/Article/details/gtuufhbdxq.html

{ ...a, ...b }
来源：http://dali.jqgfzy.top/Article/details/gtiigorgor.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gtgnsvxeml.html

[...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtyzfjzmfc.html

[U90] JS：数字数组排序
来源：http://dali.chenjidiqi.icu/Article/details/gtyhcbwsed.html

[...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gthrlhepsy.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtwawrqojl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtndpdlwof.html

[U92] JS：深拷贝
来源：http://dali.smart0.xyz/Article/details/gtrztexpwc.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtmsuruftb.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gtpienhnbc.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gtflehlbma.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtmddflouh.html

const double = x => x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkillejh.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gtfbbmpyqr.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gtzhhnlphu.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gtwzavznzn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gtejyzxvow.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtrzpwupvg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtaxwzcnqc.html

[U98] JS：fetch 带 JSON
来源：http://dali.sufxvd.cn/Article/details/gtsebmrdmg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zycfv.cn/Article/details/gtywjmcoxd.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gthjxauoqa.html

el.addEventListener("click", e => {})
来源：http://dali.guannengcc.top/Article/details/gttamjqiju.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gtmlbievbz.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gtilrvyybs.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gtmloibcdj.html

el.classList.toggle("active")
来源：http://dali.jinqigfzy.top/Article/details/gtpqulkkez.html

[U102] JS：本地存储
来源：http://dali.gaohongyu789.top/Article/details/gtzmjfhome.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtbfizljij.html

[U103] JS：定时器
来源：http://dali.chenlongwang.top/Article/details/gttojxyzci.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwavyamlt.html

[U104] JS：防抖
来源：http://dali.gotoacloud.top/Article/details/gtqrthoxjo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtryodfagi.html

[U105] JS：节流
来源：http://dali.dashuyun.cn/Article/details/gtszhtewij.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtqujxxkkg.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtydwqqwys.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtbbodgokq.html

[U107] JS：数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gtpmawszuh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yonumen.top/Article/details/gtudzezxkt.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtvgodvtqw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gtvqadubwc.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtlqmsnpty.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gthwikqlto.html

[U110] JS：数组分块
来源：http://dali.sweek.top/Article/details/gtzzckdnzg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gtxnduiymo.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtxtfokhov.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtgqifngtw.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtutyyswxw.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtvrfczusk.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gtbtesijip.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtimijwnll.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gtmajxbjvo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtwgvphgjv.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtghurhxrz.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtwuxqnsel.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.mhx1999.top/Article/details/gtmdqwzlvj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtjgjsyrzi.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtybahuykn.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtnorxbtqu.html

[U118] JS：开发服务器
来源：http://dali.fengsongda.top/Article/details/gtvkxziopj.html

npm i -D vite;  npx vite
来源：http://dali.aizwys.cn/Article/details/gtcjgjejst.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtwswjvevv.html

npx vite build
来源：http://dali.zdqjudy.top/Article/details/gtdmcypjqp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdtvnvgj.html

import.meta.env.VITE_API_URL
来源：http://dali.birdmap.top/Article/details/gtznbztcvz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqwkensax.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gtiegrcsoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsywcemeu.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gtdsqbwyyz.html

Python ......... 252
来源：http://dali.tanke756.top/Article/details/gtcdrkvtid.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtcnoygemp.html

JavaScript ..... 252
来源：http://dali.chenjidiqi.icu/Article/details/gttnwqyvha.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gtxrqdrsiq.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gtvzfcseju.html

Go ............. 212
来源：http://dali.zycfv.cn/Article/details/gtdjdmhbvy.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gtiufscsze.html

C# ............. 212
来源：http://dali.yongpay.top/Article/details/gtvbkwrurj.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjnbjflo.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gteamxszet.html

SQL ............ 90
来源：http://dali.gotoacloud.top/Article/details/gtqblmhnlt.html

Bash ........... 80
来源：http://dali.shzxlz.cn/Article/details/gtirwtunfr.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gthftjiirw.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gtpdehybqd.html

Lua ............ 10
来源：http://dali.feifeiyinyue.top/Article/details/gtjircojwd.html

Perl ........... 10
来源：http://dali.tianlin.xyz/Article/details/gtunnwxnfl.html

Scala .......... 10
来源：http://dali.yj20258888.top/Article/details/gtiexwahhg.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtdtbljefe.html

合计 ........... 2106 条
来源：http://dali.ivvv.top/Article/details/gtdtfoypry.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtxwlaqgyg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvnwwohm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtgrpgoqdn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtadahywxx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtbycuyqoh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gtjsaahnex.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtflzssgzb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtwttddcfi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gttomytadn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtvuhsjcab.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtakanhafm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxflaaey.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtvjiakgqf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtkcrkadmd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtlqowaiwm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhengqikj.top/Article/details/gtkljpqpas.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtejrppfvw.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gttbmfpuqk.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtwiaxvqgn.html

S C / C++ 专题                          60
来源：http://dali.ppjwa.cn/Article/details/gtbijeyath.html

T 其他语言补充                          60
来源：http://dali.jiagoushi.top/Article/details/gtebkmknkn.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gthfbyprng.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtnjuhounr.html

合计                                  2106 条
来源：http://dali.hammf.cn/Article/details/gtucfqapcb.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtujohzgfe.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtrzvtbhcl.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtkjjjbolh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.316326.xyz/Article/details/gtcticqsjz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.iojbl.cn/Article/details/gtbqutwebl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.redwolf501.top/Article/details/gtqunknflx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxtypwfs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gtjokbbfcc.html

—— 文件结束 ——
来源：http://dali.shanyushiyangtech.top/Article/details/gtynpfiaja.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkminzqid.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.andypj.xyz/Article/details/gtcqnhjgqj.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtmybporcr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfzerbjgn.html

【收录内容】
来源：http://dali.dashuyun.cn/Article/details/gtvrroispw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gtrwqaxckk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gtwfqamnyj.html

SQL · Bash · C · C++
来源：http://dali.guowangkeji.top/Article/details/gtzomcnjsb.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenzaomai.com/Article/details/gtbxbmyyaw.html

【使用说明】
来源：http://dali.tianlin.xyz/Article/details/gtieswsvkl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guowangkeji.top/Article/details/gtksjhetek.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daxiang520.top/Article/details/gtayhockns.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhengqikj.top/Article/details/gtnesvnxkn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cashguo.top/Article/details/gtylrzsign.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhixingplan.top/Article/details/gthixnrovy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.quarkkingdee.top/Article/details/gthzefufgj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhongyouzk.top/Article/details/gtwflqoucp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangshuangyany.cn/Article/details/gtqcqpihrq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.nanxuanxn.top/Article/details/gtmvdsyzuk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtoncrrizb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gtvotxhxbw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.andypj.xyz/Article/details/gtufhzdujf.html

【文件统计】
来源：http://dali.jlsjyb.cn/Article/details/gtslisrhvv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gotoacloud.top/Article/details/gtabcuyfbg.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtxuxykdms.html

目  录
来源：http://dali.fzhhl.top/Article/details/gtolahnopw.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtreuzygwy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtgftyyyxs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtpzrlqocx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhengqikj.top/Article/details/gtycfzhibt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gtwwhcaipo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sweek.top/Article/details/gtgaodgiak.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gttponssvj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nwbrower.top/Article/details/gtyoyubexo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gthgcnpnfn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gtmmaamlua.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtsyfeoqvi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gttwykgsff.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtbnjeiivx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtfbgmlo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gtcyxnpjxa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shuidangran.top/Article/details/gtkyvwaofv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gteqoizvcq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yueranfly.top/Article/details/gtjzqtxfzq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtvcmorrnh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtyuxdfbir.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtqptklaoz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtfbleqfno.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqykylpjk.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtxnxvhfnw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtecucqxug.html

[A01] Hello World
来源：http://dali.sweek.top/Article/details/gtnmcmkyhr.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gtconnzsmf.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gtcyzzsttr.html

JS:   console.log("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gteklaejri.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gturrieqyw.html

Java: System.out.println("Hello, World!");
来源：http://dali.jlsjyb.cn/Article/details/gtojkqqnoz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtjxfegrnf.html

Ruby: puts "Hello, World!"
来源：http://dali.nwbrower.top/Article/details/gtimwlnnmn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gttfsibarc.html

[A02] 变量声明与赋值
来源：http://dali.zhengqikj.top/Article/details/gtdlpwtibo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtjdctozel.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gttnhumsyk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtxflqlypa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtajlqqmxs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtnmlbuthm.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpywabayw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gtwcyoeqgy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gtqskflgti.html

[A03] 常量定义
来源：http://dali.gogol.net.cn/Article/details/gtauvsgfva.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhixingplan.top/Article/details/gtbodsytku.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtklatygbc.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtvbtbtqph.html

TS:   const PI: number = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtohgrumrt.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtzypsoixi.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtizxwtjzu.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtabhifooe.html

C#:   const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtkynckuoh.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gtleqaqafe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhhcanwy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.bjfxy.top/Article/details/gtqownmkwu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tianlin.xyz/Article/details/gtzuqfgtha.html

TS:   typeof x; x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gtpultkduy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cashguo.top/Article/details/gtfdeqotve.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.birdmap.top/Article/details/gtmpveghbq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ydzc1.top/Article/details/gtnmfphjod.html

C#:   x.GetType().Name; x is int
来源：http://dali.svipenyu.cn/Article/details/gtyzhllvud.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gthkhrrgja.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aibaodan.cn/Article/details/gtbuumcicj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtvksqblkw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtzkypqbgx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtyiuauyxu.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtytzgzdrl.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtfjfsabkc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fengsongda.top/Article/details/gtbpzfqhpk.html

C#:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gteshvdubk.html

[A06] 字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtrdjvrtxr.html

Py:   int("42"); float("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtpzfhznuz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daria6918.cn/Article/details/gtvymuwnoh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtxfigeifq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtmvqvhxwg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xinyue.icu/Article/details/gtejsjncrn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gtunkmvzsd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gtoqnyitli.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtambessmy.html

[A07] 数字转字符串
来源：http://dali.xylfe.cn/Article/details/gtrxakssga.html

Py:   str(42)
来源：http://dali.bjfxy.top/Article/details/gtevjbunoa.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtachngihy.html

JS:   String(42); (42).toString()
来源：http://dali.jyoumei.cn/Article/details/gtbzkblwht.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gtlkqsjvgw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hfpthk.cn/Article/details/gttebkesga.html

Go:   strconv.Itoa(42)
来源：http://dali.guowangkeji.top/Article/details/gtnbixzzut.html

Ruby: 42.to_s
来源：http://dali.jyoumei.cn/Article/details/gtwvjekqbh.html

C#:   42.ToString()
来源：http://dali.jinqigufen.top/Article/details/gtejlufrpe.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gtgsngjyxu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtdqukybpd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ybcxt.top/Article/details/gtkskrqwfv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnoxfvmm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gotoacloud.top/Article/details/gtkohgxerm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtolmhyyct.html


<!-- 参考信息 -->