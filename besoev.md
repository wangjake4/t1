代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtpgecliyk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gttcuibnjh.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gthaqbejxt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtlmydptpk.html

[U61] PHP：正则
来源：http://dali.jiagoushi.top/Article/details/gtgvmtyvfz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtgdlxktoo.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gteturlizp.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhiwuduotai.top/Article/details/gtmuibbhsr.html

[U63] PHP：文件读写
来源：http://dali.hnqzz.top/Article/details/gtsvkaszmi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexvfdsti.html

[U64] PHP：目录遍历
来源：http://dali.yueranfly.top/Article/details/gtcqumkxow.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gtotumepin.html

[U65] PHP：会话
来源：http://dali.tian-w.cn/Article/details/gttbytvsva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtmpxeviue.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gtmrcvqhzo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtilwnpzlk.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjawvhdbr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gtjkypuqmy.html

[U68] PHP：PDO 连接
来源：http://dali.yonumen.top/Article/details/gtcymrvdcv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yuxming.cn/Article/details/gtuurzydce.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtbvvxnhgz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gtdjnzjucv.html

[U70] PHP：PDO 事务
来源：http://dali.kuanghao11.cn/Article/details/gtyanguoob.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xinyue.icu/Article/details/gtpqjsihsa.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtlszosban.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcewenncd.html

[U72] PHP：写错误日志
来源：http://dali.jianghu66.top/Article/details/gtcgmyuvpr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gtidbpaajf.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtsclcmkwa.html

parse_ini_file("config.ini", true)
来源：http://dali.cdnleiting.top/Article/details/gtgiaugtca.html

[U74] PHP：读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtiookepxm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yueranfly.top/Article/details/gtleboiupj.html

[U75] PHP：依赖注入
来源：http://dali.bjfxy.top/Article/details/gtoyusrxlx.html

composer require psr/container
来源：http://dali.andypj.xyz/Article/details/gtyivbnwwd.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gtuwoijlgi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gtrwkkhwur.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtckwxbpjr.html

composer require twig/twig
来源：http://dali.cashguo.top/Article/details/gthasgtcjw.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gtynbaqrbd.html

composer require --dev phpunit/phpunit
来源：http://dali.tanke756.top/Article/details/gtlpltcxfn.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gteubpsyai.html

composer require --dev phpstan/phpstan
来源：http://dali.gzhubu.top/Article/details/gtpqyedjgs.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gtygrotubr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gtmzvenkwm.html

[U81] JS：初始化项目
来源：http://dali.zhengqikj.top/Article/details/gtpjslgkrr.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtblafkxpj.html

[U82] JS：package.json 脚本
来源：http://dali.zhengqikj.top/Article/details/gtkovhfsqs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gtlxkrurcu.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenjidiqi.icu/Article/details/gtdltpndpn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtansgking.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvvdwvrx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtrdqbynak.html

[U85] JS：可选链
来源：http://dali.yj20258888.top/Article/details/gtnprllwxr.html

a?.b?.c
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlhoojre.html

[U86] JS：空值合并
来源：http://dali.hnqzz.top/Article/details/gtzgvqmiee.html

a ?? b
来源：http://dali.jqgfzy.top/Article/details/gtncfobgaj.html

[U87] JS：解构默认值
来源：http://dali.birdmap.top/Article/details/gtxvtxyhhx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gtcbigouxg.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gtlgifqzmn.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gtxuvvzskt.html

[U89] JS：数组去重
来源：http://dali.yuxming.cn/Article/details/gtprpsucqq.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtwbunbhqt.html

[U90] JS：数字数组排序
来源：http://dali.316326.xyz/Article/details/gtwvkdgeka.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtgvwbkjpi.html

[U91] JS：对象键值遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdbvfbzu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.bjfxy.top/Article/details/gtdrihgnxc.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gtazdjlyru.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtnuvcumko.html

[U93] JS：模板字符串
来源：http://dali.sufxvd.cn/Article/details/gtgcuvloxa.html

`共 ${n} 条`
来源：http://dali.hfpthk.cn/Article/details/gtibplehwq.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtfrwxiktt.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gtkwiligys.html

[U95] JS：Promise 包装
来源：http://dali.shangyingyoupin.top/Article/details/gtnxlajvua.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqffnljh.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gtsiasaahp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtpuusleju.html

[U97] JS：并发请求
来源：http://dali.redwolf501.top/Article/details/gtikxdcctg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtchhjfwvq.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtynyaqhwm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cucudq.cn/Article/details/gtvfaeddod.html

[U99] JS：事件监听
来源：http://dali.yangfankeji.com/Article/details/gtnqgnbxnd.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtcxsjdysf.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gtxbrubnmr.html

document.querySelector(".item")
来源：http://dali.guowangkeji.top/Article/details/gtqrkhuuqx.html

[U101] JS：classList 操作
来源：http://dali.hongshengwenyu.top/Article/details/gtvpabhdjk.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gtnvthxojd.html

[U102] JS：本地存储
来源：http://dali.cucudq.cn/Article/details/gtklwtiisi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gtdhmjupbr.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gtqxreewrg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhiwuduotai.top/Article/details/gtxvxjeryg.html

[U104] JS：防抖
来源：http://dali.zhengqikj.top/Article/details/gtaigfcpyn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtwykdxpsj.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtbvbnhgpa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtlkqvzbyn.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtxcbkinzh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtfdvamkjv.html

[U107] JS：数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtqckwaepv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aibaodan.cn/Article/details/gtssdicuom.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtsfitvkgu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.c1oappe.top/Article/details/gtinfhxibw.html

[U109] JS：数组分组
来源：http://dali.guowangkeji.top/Article/details/gtggqnsxss.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtbdcydure.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtazrlhwrk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gtidvyjdlw.html

[U111] JS：对象转 Map
来源：http://dali.daria6918.cn/Article/details/gtzqgzxsym.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtivqoauvv.html

[U112] JS：字符串补位
来源：http://dali.yj202588.top/Article/details/gtahqqhcnm.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtwsglomrj.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gtmkekdvgk.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtuxpnplfl.html

[U114] JS：JSON 深比较
来源：http://dali.andypj.xyz/Article/details/gtryoaqiry.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqpgpsgs.html

[U115] JS：生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtxwhymleu.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gtugiemimd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gtakaysxcp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gtthrgkkom.html

[U117] JS：单元测试
来源：http://dali.gotoacloud.top/Article/details/gtogugrygb.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gtayvjqcpd.html

[U118] JS：开发服务器
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzprsgqd.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gthdolfimx.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gtxeqwimgu.html

npx vite build
来源：http://dali.yueranfly.top/Article/details/gtyhwknabf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtbqgjhkgn.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gtglacxoxj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtjljhlcjo.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtyxzkuvye.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthfyjshgt.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtrosaygwq.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gtskjxvghr.html

PHP ............ 252
来源：http://dali.jiagoushi.top/Article/details/gtswvxdjcx.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gtqjcfmhos.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtlrzljpji.html

Java ........... 212
来源：http://dali.yvedp.cn/Article/details/gtqqlfvuff.html

Go ............. 212
来源：http://dali.cheryme.top/Article/details/gtconllkmu.html

Ruby ........... 212
来源：http://dali.pycfn.com/Article/details/gtkwbhelyd.html

C# ............. 212
来源：http://dali.jianghu66.top/Article/details/gtuwlntnbv.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gtvvhfldhl.html

C++ ............ 30
来源：http://dali.cashguo.top/Article/details/gtektdirhi.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtzovylxxf.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopfjotqo.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtxklvxzoa.html

Swift .......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiffdhbbp.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtvxxmbyqh.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gtxmjfnsfn.html

Scala .......... 10
来源：http://dali.0kj1m.cn/Article/details/gtivkpmykp.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtttpnigcs.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtrwwdgxll.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtqgexbszf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvitcrwo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtiqtrmuxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtripfdzsu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.dashuyun.cn/Article/details/gtdrxkwsmh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtulrlxdur.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtxgndudsq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtxzzzyvoz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gtlmqhrrls.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtqizzvyrs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtzetzmrvw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtvfzpgcfo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtwsdkvxaj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtrjzayfkl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gtiwxicrac.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gtrhkdhseh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtwqosqdvp.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gtvvmgsggs.html

R Bash 专题                             80
来源：http://dali.chenzaomai.com/Article/details/gtegnhmobn.html

S C / C++ 专题                          60
来源：http://dali.shuidangran.top/Article/details/gthugmkmop.html

T 其他语言补充                          60
来源：http://dali.cucudq.cn/Article/details/gtmvwxthil.html

U 高频实用片段                         120
来源：http://dali.mhx1999.top/Article/details/gtpzhzcygt.html

------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtjrogkqtr.html

合计                                  2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gticjqvrss.html

--------------------------------------------------------------------------------
来源：http://dali.svipenyu.cn/Article/details/gtdhiwnkun.html

使用提醒
来源：http://dali.chenlongwang.top/Article/details/gtqrtquyey.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtgdpxschc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gtszipliwk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yueranfly.top/Article/details/gtagbjjzmw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gtijevgoje.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.iojbl.cn/Article/details/gtllldyhch.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtnkrznwdu.html

—— 文件结束 ——
来源：http://dali.snrcjt.cn/Article/details/gtdmkufwcz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtsdotqakz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gtpajivvtr.html

Common Programming Examples Cheat Book
来源：http://dali.fzhhl.top/Article/details/gtfnbraqyy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrilgzhfy.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtricecwwk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gtjqjgufvt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gtqaiczqrh.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gtxwqtxrft.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtkfrgqsmq.html

【使用说明】
来源：http://dali.zhengqikj.top/Article/details/gtjtdzcluh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aibaodan.cn/Article/details/gtvammxvme.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gtkgbbbkug.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.iojbl.cn/Article/details/gthxcretjw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ehwqpu.com/Article/details/gtjqunfskg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sxryk.cn/Article/details/gtbhhvzxhp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnqzz.top/Article/details/gtqoktpxqy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gtznvpcuxr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jlsjyb.cn/Article/details/gtfsgnwxhj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gtkasoroeq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nwbrower.top/Article/details/gtkktnrvro.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gtjjixmvvu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gtmjdplkuv.html

【文件统计】
来源：http://dali.yueranfly.top/Article/details/gtwxqrfgrw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gtdkfnluod.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtrjfcqgar.html

目  录
来源：http://dali.ivvv.top/Article/details/gtlxllchda.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gteffcdfqa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtfpkbktrb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtlaakqcld.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtfvwpfztf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtlfngmzxt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jyoumei.cn/Article/details/gtxgnbnpkz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxuanxn.top/Article/details/gtzbzqgmdt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtxvxkhezk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtvbhaewas.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtwvjxtndz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtkshukbpk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtgblyxpwl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtglxqfeps.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtttheulgw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwbngzex.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gtubmmkofs.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtdxtzgdjl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.haohaochexian.top/Article/details/gtxcipxgde.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtpxiyyhyc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtiebqjeoq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zycfv.cn/Article/details/gtykiibbzo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gthzvwmuqp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtyvizhwts.html

A. 基础语法与类型
来源：http://dali.zhixingplan.top/Article/details/gteanmhuje.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuzjkdytv.html

[A01] Hello World
来源：http://dali.bjfxy.top/Article/details/gtffocmpdo.html

Py:   print("Hello, World!")
来源：http://dali.smart0.xyz/Article/details/gthfviuskk.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gtwzmegpvt.html

JS:   console.log("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtzerztlox.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.meibo888.top/Article/details/gtsiwohbhr.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gttzyyhbdz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxinkj.top/Article/details/gtavdskybp.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gtzlpmwucf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtihleijeb.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gtzskcfayx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.tianlin.xyz/Article/details/gtsbymllqr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtxdwqvtxd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtjkxvpbpj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenzaomai.com/Article/details/gtkxvyqoeb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtvggnlzhc.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtnvbizudg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gtjpdulmsm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtsrabgvxt.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtxrvzgcho.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jiagoushi.top/Article/details/gtazjktwgz.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtheltalpd.html

JS:   const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtlvtnetut.html

TS:   const PI: number = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtnmmqsina.html

Java: static final double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtufimyaug.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gtesuntwfy.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtrymlvjhk.html

C#:   const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtubllmcir.html

[A04] 判断变量类型
来源：http://dali.yangfankeji.com/Article/details/gtxznlddfb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenzaomai.com/Article/details/gtqclaqmoi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtnrmsswzv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.tanke756.top/Article/details/gtktnyiqhv.html

TS:   typeof x; x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtzxytfhrz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhengqikj.top/Article/details/gthupnlakq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtpnuwztyo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.meibo888.top/Article/details/gtswaukycs.html

C#:   x.GetType().Name; x is int
来源：http://dali.gaohongyu789.top/Article/details/gtcfanjnzd.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gtdidhsqco.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yonumen.top/Article/details/gtluybjnho.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtjgkybogm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtqmgnlgov.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtkhdhxmdr.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtqritauwf.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtectgtpqe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtruzliigu.html

C#:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtibiprmvb.html

[A06] 字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtejvgkzzx.html

Py:   int("42"); float("3.14")
来源：http://dali.iojbl.cn/Article/details/gthdaapadq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xziqi.cn/Article/details/gtoycyyrid.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gtlwdcemvp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xziqi.cn/Article/details/gtmjzguwwq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pycfn.com/Article/details/gthwkdvrbq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gtexgfradl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtgwatvzfy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daria6918.cn/Article/details/gttxzgyxue.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtpkjlefjz.html

Py:   str(42)
来源：http://dali.hnxiangtu.top/Article/details/gtbztmylur.html

PHP:  (string) 42; strval(42)
来源：http://dali.iojbl.cn/Article/details/gteddwvzvd.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gthbvillkk.html

TS:   String(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjnfifil.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daxiang520.top/Article/details/gtvosspodu.html

Go:   strconv.Itoa(42)
来源：http://dali.cheryme.top/Article/details/gtffnzfhhi.html

Ruby: 42.to_s
来源：http://dali.smart0.xyz/Article/details/gtuayaplfa.html

C#:   42.ToString()
来源：http://dali.dashuyun.cn/Article/details/gtnzmtmeen.html

[A08] 取整与四舍五入
来源：http://dali.zycfv.cn/Article/details/gtxztbyiit.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtjqmurgnx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttnfqgzho.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shuidangran.top/Article/details/gttaytcnxg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.mhx1999.top/Article/details/gtvnllkspr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gteccphvdp.html


<!-- 参考信息 -->