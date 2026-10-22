代发 wailian999

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gtyiylrdfz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtqcuxkokn.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gtdbljtyqa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ydzc1.top/Article/details/gtxckrboew.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gtcdkllrgg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gtiwjrpfmr.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtrrgbrlin.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhoulong.xyz/Article/details/gtbpervzet.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gtcqjufaej.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtzqovssmw.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gtitjoupjt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gtgpmezkmf.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtcsdwtvbe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcssgjadx.html

[U68] PHP：PDO 连接
来源：http://dali.ehwqpu.com/Article/details/gtfizalksz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gtkuyjxyap.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gtwcpojqoi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.vqdsnc.cn/Article/details/gtumvwqcuo.html

[U70] PHP：PDO 事务
来源：http://dali.xziqi.cn/Article/details/gtefppzfmf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shangyingyoupin.top/Article/details/gtwvecklwv.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gtoffnzlsw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtstcvfglr.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gtqxjanrfw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gtfcdjxgyj.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gtnevewinp.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gtzrpwenyk.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gtssgoejmc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtoqjaamaq.html

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtyyirwqdn.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gtbtqxmafa.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gtqhoymtpj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cucudq.cn/Article/details/gtaayfmhuo.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gtnpkofshg.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gtdjlbzeys.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtaugxuunj.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtnivvmqkq.html

[U79] PHP：静态分析
来源：http://dali.shzxlz.cn/Article/details/gtdacmzfoi.html

composer require --dev phpstan/phpstan
来源：http://dali.jiagoushi.top/Article/details/gtugxprvxk.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqxsozqq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xziqi.cn/Article/details/gtvlksbscp.html

[U81] JS：初始化项目
来源：http://dali.cqqwz.cn/Article/details/gtunlaxorb.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gtmyqbroxw.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gtansauncc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtnlthewdc.html

[U83] JS：ES Module 导入导出
来源：http://dali.pengpengdd.cyou/Article/details/gttztqduck.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtofbhltue.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtvnrmcths.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hfpthk.cn/Article/details/gtvrnfkruy.html

[U85] JS：可选链
来源：http://dali.nanxuanxn.top/Article/details/gtzzpbexba.html

a?.b?.c
来源：http://dali.vqdsnc.cn/Article/details/gtrfvncngl.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gtdbstvajj.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gtuacbsbtb.html

[U87] JS：解构默认值
来源：http://dali.quarkkingdee.top/Article/details/gtrvawswos.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guannengcc.top/Article/details/gttwrgcbwl.html

[U88] JS：对象展开合并
来源：http://dali.redwolf501.top/Article/details/gtjrpucjfd.html

{ ...a, ...b }
来源：http://dali.shuidangran.top/Article/details/gtqkkendrh.html

[U89] JS：数组去重
来源：http://dali.dashuyun.cn/Article/details/gtqpjkspqa.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmzmtyodx.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyojwavzc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtttkjweik.html

[U91] JS：对象键值遍历
来源：http://dali.jianghu66.top/Article/details/gtvbxhgndj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangtech.top/Article/details/gtlisvulft.html

[U92] JS：深拷贝
来源：http://dali.cheryme.top/Article/details/gtgzupholn.html

structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtlifgadgp.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gtqxowdgdc.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtxjoasqhs.html

[U94] JS：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtrftgpkzl.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtiimxousb.html

[U95] JS：Promise 包装
来源：http://dali.zycfv.cn/Article/details/gtbsbrhlwe.html

new Promise((resolve, reject) => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtybyxkvwa.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gtsoapruar.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtgtsdwsnq.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gtolitavgt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtetsjgjmp.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gtfheaasrs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.9152youxi.cn/Article/details/gtykdowlkr.html

[U99] JS：事件监听
来源：http://dali.jianghu66.top/Article/details/gtrkvxxjsz.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtsefsepyu.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gttlcizata.html

document.querySelector(".item")
来源：http://dali.daxiang520.top/Article/details/gtrileqrdj.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtmpsnivur.html

el.classList.toggle("active")
来源：http://dali.vqdsnc.cn/Article/details/gtqwowvsjc.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtgovulezo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteejusrju.html

[U103] JS：定时器
来源：http://dali.wangdashe.top/Article/details/gtvbuofrkg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangdashe.top/Article/details/gtlxwmuiat.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtyoogghdz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtqrugjkym.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gthbglsjec.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtytqatpcv.html

[U106] JS：日期格式化
来源：http://dali.c1oappe.top/Article/details/gtrxtvmgze.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gtspqylsxq.html

[U107] JS：数字千分位
来源：http://dali.yj20258888.top/Article/details/gtdeljmohy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtqtooruve.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtmfmaiclu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gtoszutmdg.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowhxhkca.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gtkqzodfon.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gtfsnpdgwz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuetiantiany.cn/Article/details/gtkuicbmlv.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqeiuxan.html

new Map(Object.entries(obj))
来源：http://dali.gogol.net.cn/Article/details/gtyghgoxen.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtxlrbdzxz.html

"7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtobfyvlmt.html

[U113] JS：正则替换全部
来源：http://dali.jinqigufen.top/Article/details/gttvousctz.html

s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtjyaedgvq.html

[U114] JS：JSON 深比较
来源：http://dali.xylfe.cn/Article/details/gtgxhwkiem.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtqensowbv.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gthsmabmhm.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtjpyvwvcj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangshuangyany.cn/Article/details/gtcpnztoro.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpalddttj.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtdsgabnaw.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtcbirmqcf.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gtblkbnjdu.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtqvychaat.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gtniqzeorj.html

npx vite build
来源：http://dali.kuanghao11.cn/Article/details/gtnqgqgnjm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gtglppnhjn.html

import.meta.env.VITE_API_URL
来源：http://dali.cheryme.top/Article/details/gtblbznnfl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtegmtyqms.html

统计汇总
来源：http://dali.tian-w.cn/Article/details/gtxwejqrdi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtvtzfcxzf.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtujthjkev.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtgybdppcx.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gtamkvteow.html

JavaScript ..... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsfhntkm.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtgpzxfjhn.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gtsqyzjutm.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gtlscgvomp.html

Ruby ........... 212
来源：http://dali.shzxlz.cn/Article/details/gtuciokzpw.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtbtnkrsts.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtldjgbpnz.html

C++ ............ 30
来源：http://dali.yueranfly.top/Article/details/gtmnpdgcvy.html

SQL ............ 90
来源：http://dali.guannengcc.top/Article/details/gtiojprvkt.html

Bash ........... 80
来源：http://dali.cdnleiting.top/Article/details/gtxddfwxbs.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gtrkmrmcbb.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtpghyqwdh.html

Lua ............ 10
来源：http://dali.hammf.cn/Article/details/gtlajgnekq.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtusazuxem.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gtwuublknl.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtgmbnagwn.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtujuszrfm.html

按章节统计：
来源：http://dali.zhoulong.xyz/Article/details/gtpeprnvcw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtzidjnxyp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtgatsthyb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtihknzayk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gttlsvcyrv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gtweyzknrb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gtrnbbxvqu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtsqjvobgn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuxming.cn/Article/details/gtrlramipi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtmffbvsnk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtcnfcerxw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtnuxiyqkj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtqbvmuazl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gteudmzpdh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtvhykiksu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtvznrgdtm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtwbxcizoh.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gtgwitzimg.html

R Bash 专题                             80
来源：http://dali.feifeiyinyue.top/Article/details/gtjeuojmym.html

S C / C++ 专题                          60
来源：http://dali.fengsongda.top/Article/details/gtvqkwbvim.html

T 其他语言补充                          60
来源：http://dali.9152youxi.cn/Article/details/gtstgeioik.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gtteesredc.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtbsotpzoh.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gtdrydhdfd.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gttrtcrqcg.html

使用提醒
来源：http://dali.zhongyouzk.top/Article/details/gtgiokubqn.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtlxwhzjvn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.havefunace.top/Article/details/gtenktsvyl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuetiantiany.cn/Article/details/gtrncearpu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.chenjidiqi.icu/Article/details/gtdeswagtc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.snrcjt.cn/Article/details/gtyeejadho.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yongpay.top/Article/details/gtoalgacmm.html

—— 文件结束 ——
来源：http://dali.kuanghao11.cn/Article/details/gtxfhqcziu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtxhsktarc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtqutuwskj.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtvsfcsfoo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiflnzwcf.html

【收录内容】
来源：http://dali.gzhubu.top/Article/details/gtmftmgkuk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzzfpcbz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gttpwvfrvh.html

SQL · Bash · C · C++
来源：http://dali.yj202588.top/Article/details/gtbtxmwyue.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gtlocorxdu.html

【使用说明】
来源：http://dali.yuanzhike.top/Article/details/gtfmhxsgrm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinqigufen.top/Article/details/gtpycmeupr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ivvv.top/Article/details/gtsasxkiuq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuanzhike.top/Article/details/gtrudzwyfo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xziqi.cn/Article/details/gtsxyraizo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sweek.top/Article/details/gtihfsmxtk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtijmadklk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtqiwiynuq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gtogtijlxn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.mhx1999.top/Article/details/gtdwolsqai.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ehwqpu.com/Article/details/gtmxrgshfc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daxiang520.top/Article/details/gtszyijlzt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangdashe.top/Article/details/gtlwuxuucx.html

【文件统计】
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkluugqm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuetiantiany.cn/Article/details/gtfjfictwx.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtpdpomuls.html

目  录
来源：http://dali.yj20258.top/Article/details/gtaoxbenag.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtdoypffcl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtvpjjmycm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtryardkei.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtiivvupwi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtljdrrqaf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yonumen.top/Article/details/gtmdwpdagq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcczcplle.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtvdbzywcp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gtnnrhilip.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtxzhmsbse.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.9152youxi.cn/Article/details/gtczmgdeoy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtemtkljkg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gthmjkftoy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtlrzoltvc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yj20258888.top/Article/details/gtwczednlv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yanxiufei.cn/Article/details/gtmmhqwqfl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtqcytwwiz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yonumen.top/Article/details/gtlahcvtot.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtzxoeofxn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhengqikj.top/Article/details/gtvorqmavm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinghuilouyu.cn/Article/details/gteowmcvyt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtcwcdoxwf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqhmruyxd.html

A. 基础语法与类型
来源：http://dali.hysaishi.cn/Article/details/gtduiyrvct.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwzrfkvqu.html

[A01] Hello World
来源：http://dali.hfpthk.cn/Article/details/gtoavynpmm.html

Py:   print("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gtvjgsnlnk.html

PHP:  echo "Hello, World!";
来源：http://dali.andypj.xyz/Article/details/gtmurgxtfs.html

JS:   console.log("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtsczsaaqm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnqzz.top/Article/details/gtvlazenct.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtmicogzjc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gtsbhnvejh.html

Ruby: puts "Hello, World!"
来源：http://dali.cashguo.top/Article/details/gtmbuvxqxi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtxlxrmdhs.html

[A02] 变量声明与赋值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtjzhwum.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhzwejqo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsqokxpn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtbpxduubf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yangfankeji.com/Article/details/gtopiugoyc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtfmrhjybv.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gtlrfyxdju.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxuanxn.top/Article/details/gtdliiihfc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtdxcpeful.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gtgjznmyqs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.quarkkingdee.top/Article/details/gtosscnnxa.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtogvxdpdm.html

JS:   const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtgovuvurf.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtzxtuuhrn.html

Java: static final double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtzdgmupam.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtbvvwacpi.html

Ruby: PI = 3.14159
来源：http://dali.zhongyouzk.top/Article/details/gtmdgbefex.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtybkojtqy.html

[A04] 判断变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtbbwvcaxv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtmnfqzmjt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jiagoushi.top/Article/details/gtudsilasi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtwglpczvs.html

TS:   typeof x; x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gtfiabvmrm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sysykeji.top/Article/details/gtbianywhg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gttivbftkp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.c1oappe.top/Article/details/gtlaanxjst.html

C#:   x.GetType().Name; x is int
来源：http://dali.mhx1999.top/Article/details/gtqtggkwnl.html

[A05] 整数除法与取模
来源：http://dali.dashuyun.cn/Article/details/gtqejfxndj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gzhubu.top/Article/details/gtruzzxlxw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtvuftmqeg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtbecwmwvl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtidugbpty.html

Java: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtostmzcet.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtjjddkpux.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtfincphvo.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtcmtibubt.html

[A06] 字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtuldlhyme.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtcrbdsusk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gtoyzkwomz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtpcrzykgr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtdixqfhco.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtyxcnojsn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gtcyvinjnc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxuanxn.top/Article/details/gtciilwspb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fzhhl.top/Article/details/gtagzmzuhh.html

[A07] 数字转字符串
来源：http://dali.sweek.top/Article/details/gtlxvkvihw.html

Py:   str(42)
来源：http://dali.haohaochexian.top/Article/details/gtgtcajeif.html

PHP:  (string) 42; strval(42)
来源：http://dali.c1oappe.top/Article/details/gtuqugzujc.html

JS:   String(42); (42).toString()
来源：http://dali.yvedp.cn/Article/details/gtnmsikdiq.html

TS:   String(42)
来源：http://dali.havefunace.top/Article/details/gtzyoklcsc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnqzz.top/Article/details/gtapaljdvt.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gtvcphztxi.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gtrsmoxava.html

C#:   42.ToString()
来源：http://dali.nwbrower.top/Article/details/gtccqxprlr.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gtbnbvxppk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gthnwyigpp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnxiangtu.top/Article/details/gttrvhgxfg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gttpghyvzp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258888.top/Article/details/gtdqraumce.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtysldaezv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtsrnwyrjn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqwpympq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gttowovtoh.html

[A09] 绝对值与最大最小值
来源：http://dali.snrcjt.cn/Article/details/gttnfrvcgs.html


<!-- 参考信息 -->