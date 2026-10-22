代发 wailian999

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtsozawitu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.dianchejie.cn/Article/details/gtgaukfwzg.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gtldiqwzmm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtelmyzrql.html

[U63] PHP：文件读写
来源：http://dali.jlsjyb.cn/Article/details/gttrlytmzm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.havefunace.top/Article/details/gthpukehwu.html

[U64] PHP：目录遍历
来源：http://dali.jqgufenzy.top/Article/details/gtqfmdtonw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gthnuorsgv.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtrnhgdtvo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtysatkrza.html

[U66] PHP：设置 Cookie
来源：http://dali.pengpengdd.cyou/Article/details/gthoxkbnwb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtzvmblrsv.html

[U67] PHP：处理文件上传
来源：http://dali.yuanzhike.top/Article/details/gtmxytatbj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtvxcpdvyo.html

[U68] PHP：PDO 连接
来源：http://dali.sysykeji.top/Article/details/gtqyjfrqnm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuanzhike.top/Article/details/gtqzcdxmzm.html

[U69] PHP：PDO 预处理
来源：http://dali.pengpengdd.cyou/Article/details/gtrfrvighu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gthquikxrj.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtcyvgzsqv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gtmcrvxkxn.html

[U71] PHP：抛出异常
来源：http://dali.ybcxt.top/Article/details/gtbxbuwuut.html

throw new RuntimeException("失败", 500);
来源：http://dali.guowangkeji.top/Article/details/gtwinyzmge.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gthslpwkbm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gtzktosdub.html

[U73] PHP：读取 ini 配置
来源：http://dali.cqqwz.cn/Article/details/gtcgtpuvkp.html

parse_ini_file("config.ini", true)
来源：http://dali.dianchejie.cn/Article/details/gtxnsxsjow.html

[U74] PHP：读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtoyavdyic.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nwbrower.top/Article/details/gtrotxxfzs.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtztnyzudu.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gtlyxgyisz.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtmewbizjn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gtijlulrpy.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlimbxodf.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gtqcaerbbe.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtidrcoyup.html

composer require --dev phpunit/phpunit
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvenyjuem.html

[U79] PHP：静态分析
来源：http://dali.gogol.net.cn/Article/details/gtqmqovyro.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gtxfmejdfi.html

[U80] PHP：代码规范修复
来源：http://dali.shangyingyoupin.top/Article/details/gtyjbptmby.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gtcdlyzfpt.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbxkfwic.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gtciwakjxa.html

[U82] JS：package.json 脚本
来源：http://dali.zhixingplan.top/Article/details/gtfkuugspu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gtqgxcmysk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtwytwdnti.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gttozijljw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtiwuyjkiy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gtxugywvzh.html

[U85] JS：可选链
来源：http://dali.dashuyun.cn/Article/details/gtmcfczyyd.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtfjdovtqo.html

[U86] JS：空值合并
来源：http://dali.hywenlv.cn/Article/details/gtqrfbwkcz.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gtnnmqgmjl.html

[U87] JS：解构默认值
来源：http://dali.quarkkingdee.top/Article/details/gtlcfamqop.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtyauptiqe.html

[U88] JS：对象展开合并
来源：http://dali.jqgufenzy.top/Article/details/gtzwjzhuen.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gtqfychhjp.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtvkbfkcbz.html

[...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtmwofgsaa.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gtcchzymrv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtcfeajhuk.html

[U91] JS：对象键值遍历
来源：http://dali.wangdashe.top/Article/details/gttkslierv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gtacdvnfyn.html

[U92] JS：深拷贝
来源：http://dali.ppjwa.cn/Article/details/gtxsdjuyeh.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtadellmtd.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtcrgrddgn.html

`共 ${n} 条`
来源：http://dali.iojbl.cn/Article/details/gtstbeiktp.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtuyohhkrs.html

const double = x => x * 2;
来源：http://dali.nwbrower.top/Article/details/gtwdsklxkp.html

[U95] JS：Promise 包装
来源：http://dali.chenzaomai.com/Article/details/gtwmjqtxki.html

new Promise((resolve, reject) => {})
来源：http://dali.316326.xyz/Article/details/gtkoykffbb.html

[U96] JS：async/await 与异常
来源：http://dali.yongpay.top/Article/details/gtakntdozu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtuqedtiyc.html

[U97] JS：并发请求
来源：http://dali.sysykeji.top/Article/details/gtcuonufvd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtnfwyvkxi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhengqikj.top/Article/details/gtioiambtk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shangyingyoupin.top/Article/details/gtipfminxt.html

[U99] JS：事件监听
来源：http://dali.yuxming.cn/Article/details/gtanbudkpe.html

el.addEventListener("click", e => {})
来源：http://dali.tian-w.cn/Article/details/gtknbprnaa.html

[U100] JS：DOM 查询
来源：http://dali.xuetiantiany.cn/Article/details/gtvrjngkhn.html

document.querySelector(".item")
来源：http://dali.daria6918.cn/Article/details/gtnyvbsfla.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtzrwucjpb.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gtomzisxmw.html

[U102] JS：本地存储
来源：http://dali.jinqigfzy.top/Article/details/gtmgjrkzxo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gtqhflpqvm.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtlwvlkxru.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtwzojkqfa.html

[U104] JS：防抖
来源：http://dali.xinyue.icu/Article/details/gtwhuphgrq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtokortdgj.html

[U105] JS：节流
来源：http://dali.haohaochexian.top/Article/details/gtlxecobfb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtudtovowu.html

[U106] JS：日期格式化
来源：http://dali.havefunace.top/Article/details/gtrxooevud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigfzy.top/Article/details/gtzzzkhnng.html

[U107] JS：数字千分位
来源：http://dali.zhongyouzk.top/Article/details/gtpakejukc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtwuhvcalb.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gthiocmdku.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gtsomzcsyy.html

[U109] JS：数组分组
来源：http://dali.yangfankeji.com/Article/details/gtnwyjwpsc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gtozgggplm.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtfknyfreh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtjecqbswb.html

[U111] JS：对象转 Map
来源：http://dali.haohaochexian.top/Article/details/gtlcwkgaqk.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gtlkcsrgxb.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gtwtrfcpug.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgpftegf.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gtzkxsgusz.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtvqikehxp.html

[U114] JS：JSON 深比较
来源：http://dali.jianghu66.top/Article/details/gtzvndldju.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtxorxjrng.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtblxthmph.html

crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gtwhtlrhtw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtfkmclbzr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cheryme.top/Article/details/gtbaehgtte.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtvtytgiru.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtbziwlfok.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtmjoydaoy.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtwjipfrnp.html

[U119] JS：生产构建
来源：http://dali.ivvv.top/Article/details/gtvmphosvt.html

npx vite build
来源：http://dali.jinqigufen.top/Article/details/gtjnautura.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtiwidftzw.html

import.meta.env.VITE_API_URL
来源：http://dali.yj202588.top/Article/details/gtqotcvbuk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdhtphatg.html

统计汇总
来源：http://dali.jlsjyb.cn/Article/details/gteijifkme.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtvepmgtax.html

按语言统计（条）：
来源：http://dali.hysaishi.cn/Article/details/gtahegowzz.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gtmzjzlcof.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtqftqwdxc.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gtnbgoasxo.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gtiyomafdy.html

Java ........... 212
来源：http://dali.sysykeji.top/Article/details/gttrtsbnvg.html

Go ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtnnfkbwcs.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gthniillwl.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtqbzkatoh.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gteyddtyyk.html

C++ ............ 30
来源：http://dali.sysykeji.top/Article/details/gtzjqvmuwm.html

SQL ............ 90
来源：http://dali.jinqigufen.top/Article/details/gtkfkftknu.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtsvqwsker.html

Kotlin ......... 15
来源：http://dali.cashguo.top/Article/details/gttfcpgsdh.html

Swift .......... 15
来源：http://dali.zhixingplan.top/Article/details/gtbtyztynq.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gteyoqeqek.html

Perl ........... 10
来源：http://dali.yj202588.top/Article/details/gtyudkespf.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gtjqshtiyp.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gteucvivbp.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtrpfezhel.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gtmsktmwof.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrfjzbyz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtjgkfxfng.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtzaawkfmy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxinkj.top/Article/details/gtjtvufkbt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefsguboo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtbbcwdbis.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtlsocicbr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtseciybjs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtizvtinon.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtoauazznu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtxkqbbunp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtjbixvpfy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtoompbicb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gtrvqjyrju.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.mhx1999.top/Article/details/gthohwhwya.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtxargnihi.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gtceiqrref.html

R Bash 专题                             80
来源：http://dali.xuetiantiany.cn/Article/details/gtcguystuw.html

S C / C++ 专题                          60
来源：http://dali.jqgfzy.top/Article/details/gtvpppomic.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gtqabrxoil.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gtltszdxgi.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtjkmkzawv.html

合计                                  2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtmtvxdvhb.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtxjjhtfyv.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gtreadbuyp.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gthrufchyp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gtrteuyvxu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtnitpjtnm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.svipenyu.cn/Article/details/gtqwckymud.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnqzz.top/Article/details/gtwqpgwkku.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.9152youxi.cn/Article/details/gttgirfyjv.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gtlgbdtolo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthxjpgzzo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gtvombhqqa.html

Common Programming Examples Cheat Book
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfozggrf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtyhnvxkpu.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqgnqsbe.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.tanke756.top/Article/details/gtqamdrnbt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ehwqpu.com/Article/details/gtkljqjbnv.html

SQL · Bash · C · C++
来源：http://dali.xylfe.cn/Article/details/gtxpefcppi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.haohaochexian.top/Article/details/gtosgkujil.html

【使用说明】
来源：http://dali.dianchejie.cn/Article/details/gtigbzxmfl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zycfv.cn/Article/details/gthonmstox.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gtqrbmjzgq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gtmkqyzqqa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gtjgolfbrb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuanzhike.top/Article/details/gthrgusydv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsxtmgic.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guowangkeji.top/Article/details/gtfbivsraj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.feifeiyinyue.top/Article/details/gtmxebvjjy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dashuyun.cn/Article/details/gtxoppsoec.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinqigufen.top/Article/details/gtppdnfwpy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gtksqwennj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.andypj.xyz/Article/details/gtyxuxnriw.html

【文件统计】
来源：http://dali.yj20258.top/Article/details/gtgfaqibzn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gtqmmahmpx.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtkghzuhiw.html

目  录
来源：http://dali.shanyushiyangtech.top/Article/details/gtntsjodsi.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtjamiajuf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtdxwhnmtp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrzrrmrj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gtqjpyihov.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tanke756.top/Article/details/gtnbnlqabt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.havefunace.top/Article/details/gtdrqlymty.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtigghwpyk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtjveoxhgm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtpseuugdn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtayowwzdv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gtohpvrsjg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtgnojwoud.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtltgvfbkc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtaizqjkof.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtkcbegnst.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gtfkrmrqpn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtasttxtsu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ybcxt.top/Article/details/gtarkmylce.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtdtxcqwah.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.316326.xyz/Article/details/gtwyqoogpl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtqqtmnlqy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtottkpcvb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmyhnxmub.html

A. 基础语法与类型
来源：http://dali.snrcjt.cn/Article/details/gtuyziorlw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdzsdcykr.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gtisreeysq.html

Py:   print("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gtmykinuyx.html

PHP:  echo "Hello, World!";
来源：http://dali.svipenyu.cn/Article/details/gtgsalnuwq.html

JS:   console.log("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtlkuqnoug.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuanzx.com/Article/details/gtbrprsivo.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtkmdenztx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gtbrdusknu.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gtzombjcts.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtwxtnjxpe.html

[A02] 变量声明与赋值
来源：http://dali.guowangkeji.top/Article/details/gtclkyklfl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tanke756.top/Article/details/gtrqyqxbkt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daxiang520.top/Article/details/gtbmzijxxu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtrvrchhex.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tian-w.cn/Article/details/gtzflosmgs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtsqpedqbj.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gtxxvtasyg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhoulong.xyz/Article/details/gtlvnzivwf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuxming.cn/Article/details/gtonkswncq.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gtliuqswpi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.guannengcc.top/Article/details/gtdkeyberk.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtuttjzorr.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtetvlsxlq.html

TS:   const PI: number = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxxpcacj.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtzqgfwvfi.html

Go:   const PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtyyfwaczd.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtdwlzjzpf.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtizjjfmhi.html

[A04] 判断变量类型
来源：http://dali.meibo888.top/Article/details/gtfsbdxtlv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gtbhavuccq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gtqfyoargb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gtwxndtfvw.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtlpkqfvca.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtckroaxdw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.feifeiyinyue.top/Article/details/gtwipstddn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtpwkjrfth.html

C#:   x.GetType().Name; x is int
来源：http://dali.redwolf501.top/Article/details/gtxpbihlwm.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gtnqemdcco.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzoelhqay.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gthmyvaajt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtlpujkthj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtmukaiwxy.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtpmmhisvm.html

Go:   7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtmooycaee.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtagedcpxc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtyoemdqsd.html

[A06] 字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtdblsqlvm.html

Py:   int("42"); float("3.14")
来源：http://dali.cqqwz.cn/Article/details/gtsiyepqtp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hongshengwenyu.top/Article/details/gtgfhevvge.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.316326.xyz/Article/details/gtudpatekh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtymstbvac.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtbjeewuep.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gtsjmfedbd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gtxqzsenmo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cqqwz.cn/Article/details/gthjiicqeu.html

[A07] 数字转字符串
来源：http://dali.hammf.cn/Article/details/gtisnbtoxc.html

Py:   str(42)
来源：http://dali.shzxlz.cn/Article/details/gtuyjotwhz.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gttuegkvvy.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gthumhvpin.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtxozjgkvd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jianghu66.top/Article/details/gtynsjtrdv.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtgrtgbnwz.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gtzhsckjkw.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gturqenfxd.html

[A08] 取整与四舍五入
来源：http://dali.feifeiyinyue.top/Article/details/gtjkdpvcvo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gttceslwza.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gtyiqlvmnz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtexiibzce.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.bjfxy.top/Article/details/gtmmfbdkmk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtetwjhbcg.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmcvwwza.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuanzx.com/Article/details/gtydpqhfhm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtjyfrpnzc.html

[A09] 绝对值与最大最小值
来源：http://dali.hnqzz.top/Article/details/gtxjgocxbz.html


<!-- 参考信息 -->