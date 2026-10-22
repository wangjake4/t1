代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtxrezceae.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtiwgklcbo.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gtqtfmrios.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gtanoxxyyd.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gtyppnvpas.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtjrayswdx.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwajiev.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gtiappzxro.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gtpmvocute.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gtwbzucvvs.html

[U64] PHP：目录遍历
来源：http://dali.sufxvd.cn/Article/details/gtqjxrtkmk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cheryme.top/Article/details/gtparwnqcm.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtfenanyhc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtbvizsulo.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtktpsnmrz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gtgpiqrrxv.html

[U67] PHP：处理文件上传
来源：http://dali.zhixingplan.top/Article/details/gtokwpllpr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gtjfbclumo.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gttowoustt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xylfe.cn/Article/details/gtmjgpbfcs.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gtpaevyglm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.havefunace.top/Article/details/gtlmnstopm.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gtuikdnzdx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gtiwnfuoof.html

[U71] PHP：抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdfumlcg.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnqzz.top/Article/details/gtotldmqea.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gtaxiwmmmk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gtdvwhpxio.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gthqhykcij.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtxoctvwfr.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtgnbmswir.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gtrqmqzobo.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gttpykftmx.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtfgkzcyci.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gtcqcizpbv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yongpay.top/Article/details/gtzuifjxow.html

[U77] PHP：模板渲染
来源：http://dali.hongshengwenyu.top/Article/details/gtwvvqrqzs.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gtbhqowyei.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzmzzxrm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gtaupmjxnf.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuagdhff.html

composer require --dev phpstan/phpstan
来源：http://dali.ppjwa.cn/Article/details/gtkgnmxlsq.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gtdzftabrn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daria6918.cn/Article/details/gtdhfrwlqh.html

[U81] JS：初始化项目
来源：http://dali.xuetiantiany.cn/Article/details/gtaotfescv.html

npm init -y;  npm i express
来源：http://dali.daxiang520.top/Article/details/gtgvonxvoa.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gtccemxagy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jiagoushi.top/Article/details/gtrofemppu.html

[U83] JS：ES Module 导入导出
来源：http://dali.sweek.top/Article/details/gtdfqhnuje.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtqfyaksyb.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gtuzzvjmfa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtewkpwpdr.html

[U85] JS：可选链
来源：http://dali.0kj1m.cn/Article/details/gtrfcltnsz.html

a?.b?.c
来源：http://dali.yj20258.top/Article/details/gtqkofadhi.html

[U86] JS：空值合并
来源：http://dali.andypj.xyz/Article/details/gtsypocknt.html

a ?? b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiwzldds.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtulxggxky.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gtxgzdsdiu.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjmybedm.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gtioctfhkc.html

[U89] JS：数组去重
来源：http://dali.cdnleiting.top/Article/details/gtoghrspka.html

[...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtqkfpawbb.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtjfonyhjq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftdtoqeg.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtcrdephfq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gtekazwrej.html

[U92] JS：深拷贝
来源：http://dali.xylfe.cn/Article/details/gthwflqcnw.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtsfxzhvcb.html

[U93] JS：模板字符串
来源：http://dali.zhoulong.xyz/Article/details/gtndoppaby.html

`共 ${n} 条`
来源：http://dali.jiagoushi.top/Article/details/gtkrzkitlv.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtiiazsvfx.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtswupqfss.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gtcfhggmyo.html

new Promise((resolve, reject) => {})
来源：http://dali.ydzc1.top/Article/details/gtvgcqgsav.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtywfqoacd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gthyvwkewl.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtdhdypbaf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtxyzmxdon.html

[U98] JS：fetch 带 JSON
来源：http://dali.zdqjudy.top/Article/details/gthqfzchmn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhongyouzk.top/Article/details/gtiorfwekk.html

[U99] JS：事件监听
来源：http://dali.xinyue.icu/Article/details/gtlizhaxyt.html

el.addEventListener("click", e => {})
来源：http://dali.hysaishi.cn/Article/details/gtfgkkamim.html

[U100] JS：DOM 查询
来源：http://dali.daxiang520.top/Article/details/gtrobgigxn.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gtvchvaplc.html

[U101] JS：classList 操作
来源：http://dali.fzhhl.top/Article/details/gtsnywvmnk.html

el.classList.toggle("active")
来源：http://dali.dashuyun.cn/Article/details/gtuqbgdban.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtabkerxfh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gtcuibdvga.html

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gtmpronabc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gttnvprtdr.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gtrulmjlqj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtfoqepepa.html

[U105] JS：节流
来源：http://dali.hnqzz.top/Article/details/gttnkgsuej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtawfsoxpk.html

[U106] JS：日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtldglmzpo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gtyspkssuj.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gtyyespvve.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtfvayrxca.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwikbhdqn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtxyvxakyp.html

[U109] JS：数组分组
来源：http://dali.shangyingyoupin.top/Article/details/gtfplrbnhu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gtlikrzxwf.html

[U110] JS：数组分块
来源：http://dali.zhongyouzk.top/Article/details/gtfywowqta.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cdnleiting.top/Article/details/gtawbbqaxc.html

[U111] JS：对象转 Map
来源：http://dali.hywenlv.cn/Article/details/gtkiccmqkf.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gtiwjculiv.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gtigpyuwga.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtncidswek.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtddlfdkzy.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtlzvvmyzi.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtdkadegqf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtksvycyve.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtmfjrgzou.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtcygjzzgo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuanzhike.top/Article/details/gtxppdtgas.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtskguvdcj.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtzpzjnque.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtfeqtwxpv.html

[U118] JS：开发服务器
来源：http://dali.yanxiufei.cn/Article/details/gtjoferqbt.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gtwbbxuiia.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gtanmuphwj.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtssqvsand.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gtgkbyukut.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gtwjlrzgyo.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtoxuuqkgn.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gtjjisrbmn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqhxpkjeu.html

按语言统计（条）：
来源：http://dali.feifeiyinyue.top/Article/details/gtagrvsbhu.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtovrqiofh.html

PHP ............ 252
来源：http://dali.yongpay.top/Article/details/gtxgakbeqh.html

JavaScript ..... 252
来源：http://dali.hongshengwenyu.top/Article/details/gteokawotl.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtndnedmyv.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gteclljtja.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtinwqgxjj.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gtjfdwvgns.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtkppdseoi.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtldzbmfjp.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gtgphiprok.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtbzhcmmis.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gthnxavtyx.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtkyfqwpgx.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gtpltshwww.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtqqfzmcst.html

Perl ........... 10
来源：http://dali.sufxvd.cn/Article/details/gtfuomtget.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gtrdwxsbvq.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtujqjrscg.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gtqhysxzch.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtmmrlgvgg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gtrldbewei.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dashuyun.cn/Article/details/gtcqlqpcfs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cashguo.top/Article/details/gtjysbdakt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtznxbykxq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gtlbsjhemd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqktcgcd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtvvbxpshz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtrxsstmfk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtsjelzdhv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtmelapffw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtcygxulrt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtgvytyliu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtngyhycme.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtgrjgkdhq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamcsswye.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtyeobhsou.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtuvaiflfb.html

R Bash 专题                             80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetcwbpmw.html

S C / C++ 专题                          60
来源：http://dali.shanyushiyangtech.top/Article/details/gtpylpfcpf.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gtzkhaytgd.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gtwsuhtgdt.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtaopfnfai.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gtkkzexwrm.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtbtjwxmeb.html

使用提醒
来源：http://dali.birdmap.top/Article/details/gtgqaxpxlo.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtftmqutha.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnycvqmrm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenlongwang.top/Article/details/gtijgyernu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gtkjnpgzns.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gtyzfqnodf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj202588.top/Article/details/gtrgiiexrm.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gtwaejxtuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtddnnygbt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnqzz.top/Article/details/gtsbputukw.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbutywdoe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrpnzdbqf.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gtnmdwdbtz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ehwqpu.com/Article/details/gtsmzokymp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gtwquhsrry.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gthrnlujmh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gtbywshxzt.html

【使用说明】
来源：http://dali.sweek.top/Article/details/gtzmwzffyy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.smart0.xyz/Article/details/gthynwpecd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigfzy.top/Article/details/gttpaqwmok.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ppjwa.cn/Article/details/gtfitcykhl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj202588.top/Article/details/gtasrwatvg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gtnmbvsarf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklsxtqyv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gtmrrlltdr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyyyhbqr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbvkbaxx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gtczmvxmxv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.svipenyu.cn/Article/details/gtghtojhvg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dianchejie.cn/Article/details/gtvatvleqf.html

【文件统计】
来源：http://dali.yuxming.cn/Article/details/gthhujeejh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.9152youxi.cn/Article/details/gtsklhesov.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtcgzavsfk.html

目  录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajxtnlms.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gttgxbgqbn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtrlopecgt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtthjnwghs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtyqysdqrr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtbpovvoui.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyupjdqup.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtsijtyxcc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jqgufenzy.top/Article/details/gtiomvijvf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtabuchefo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhixingplan.top/Article/details/gtynwfwtlu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gttqrttbhl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtzpihejjt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gtlibgosdw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtnlntkzzv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtsiokxrma.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhixingplan.top/Article/details/gtrjhmqgux.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtpsitqhbs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhongyouzk.top/Article/details/gtpgnrdgig.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtytcqgtti.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.iojbl.cn/Article/details/gtnkddbcjq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtafmqymgh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrgszbdo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtriswwvfc.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gtpneahryc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gteceemthv.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gtccblfzse.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtmvngnuzd.html

PHP:  echo "Hello, World!";
来源：http://dali.hysaishi.cn/Article/details/gtvmcwokih.html

JS:   console.log("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gtnqdahntq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gtayonrjuw.html

Java: System.out.println("Hello, World!");
来源：http://dali.aibaodan.cn/Article/details/gtbldjsvev.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gtlazmjchi.html

Ruby: puts "Hello, World!"
来源：http://dali.sweek.top/Article/details/gtkoclaizb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtfrkqvkki.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gtgowzggih.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yonumen.top/Article/details/gtzqjikcff.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtbgcdgoaw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkircfact.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuanzhike.top/Article/details/gtmyylnmqy.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jianghu66.top/Article/details/gttohiwczh.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gtxpdidqjo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guannengcc.top/Article/details/gthbhlfgtx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtlhwnesnk.html

[A03] 常量定义
来源：http://dali.xuanzx.com/Article/details/gtbdfbuxys.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtszxlctjj.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtbmeafixy.html

JS:   const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtilywwyfr.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqesomxb.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtdwvyvsnt.html

Go:   const PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gtdrfuyfgd.html

Ruby: PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gtjynwqafd.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtjrocgeew.html

[A04] 判断变量类型
来源：http://dali.yuxming.cn/Article/details/gtrtgewneu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gteenkdoyp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gtwitvhvnl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenlongwang.top/Article/details/gtpihlvnxw.html

TS:   typeof x; x instanceof Date
来源：http://dali.hammf.cn/Article/details/gtnhtrqnuc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yonumen.top/Article/details/gtrucujgkb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gtkwkgrkrf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenjidiqi.icu/Article/details/gtcywrivgj.html

C#:   x.GetType().Name; x is int
来源：http://dali.daria6918.cn/Article/details/gtjqraahgj.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gtyfznyrac.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gtzukgsiod.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtspadpkfg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtrvyacwuw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtpaalvpry.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtfgtzrvpl.html

Go:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtptzkuduh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtqnenpcyj.html

C#:   7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtzdzqhzfs.html

[A06] 字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtsxcniimj.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtgfgsirlr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.andypj.xyz/Article/details/gtewnxnuvb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.smart0.xyz/Article/details/gthiknhugs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhixingplan.top/Article/details/gtdvazeddw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtrrihpmdb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nwbrower.top/Article/details/gtfatcrhrm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.andypj.xyz/Article/details/gtxfwyzjgb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenlongwang.top/Article/details/gtsujsvwzl.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gtabdxkpie.html

Py:   str(42)
来源：http://dali.redwolf501.top/Article/details/gtvyolrnmm.html

PHP:  (string) 42; strval(42)
来源：http://dali.tianlin.xyz/Article/details/gtvmjtwnwm.html

JS:   String(42); (42).toString()
来源：http://dali.ppjwa.cn/Article/details/gtmadusixk.html

TS:   String(42)
来源：http://dali.quarkkingdee.top/Article/details/gtazplpxhs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigfzy.top/Article/details/gtcujoxdcm.html

Go:   strconv.Itoa(42)
来源：http://dali.9152youxi.cn/Article/details/gtupwkmdte.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtkguynweo.html

C#:   42.ToString()
来源：http://dali.zycfv.cn/Article/details/gtdpbipwxm.html

[A08] 取整与四舍五入
来源：http://dali.jiagoushi.top/Article/details/gthsxcaomk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtogvsncsh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbstbiobq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtktlcwlmv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.nanxinkj.top/Article/details/gtenlpusxc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtglzxiljy.html


<!-- 参考信息 -->