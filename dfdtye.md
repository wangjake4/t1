代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gthgonfcou.html

"值: {$a}"
来源：http://dali.xuanzx.com/Article/details/gtliszwvgz.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtnpcdiwrx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gtsbnkpzfc.html

[U59] PHP：自定义排序
来源：http://dali.andypj.xyz/Article/details/gtyswbcjju.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtfoctzxad.html

[U60] PHP：JSON 编解码
来源：http://dali.birdmap.top/Article/details/gtmsmmtntb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ydzc1.top/Article/details/gtddygyxvh.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gtlfsqcchl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvmbmnzz.html

[U62] PHP：日期对象
来源：http://dali.snrcjt.cn/Article/details/gtsdpxagxe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cucudq.cn/Article/details/gtcruthjzb.html

[U63] PHP：文件读写
来源：http://dali.ydzc1.top/Article/details/gtawegefjv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtukwyevvx.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gtkdzrjiuh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtdtkipuwe.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gtiblsmxdb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtqovgfetm.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtploreghr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jlsjyb.cn/Article/details/gtpaszixzg.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gtbwzttmlf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtkqmlxpsd.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gtcuozdyru.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtjofleuvu.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtdtxkofyr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gtgotmllfr.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gtpxwuwbzm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gtdlgftrvi.html

[U71] PHP：抛出异常
来源：http://dali.iojbl.cn/Article/details/gtuugcefxt.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtxkcolmfs.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gtwzaqokie.html

error_log("失败: " . $e->getMessage());
来源：http://dali.0kj1m.cn/Article/details/gtvfrpjurx.html

[U73] PHP：读取 ini 配置
来源：http://dali.mhx1999.top/Article/details/gtlzjxtayj.html

parse_ini_file("config.ini", true)
来源：http://dali.c1oappe.top/Article/details/gtoljgngws.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtogwalfgx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fengsongda.top/Article/details/gtkuntwdme.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtipvopmfd.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gtxdfpqqpt.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtrnjdcewi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gtxzlcywbd.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gtjgtapqqg.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gtuojrvpfh.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtvitrozah.html

composer require --dev phpunit/phpunit
来源：http://dali.cdnleiting.top/Article/details/gtxlfsrzop.html

[U79] PHP：静态分析
来源：http://dali.xuetiantiany.cn/Article/details/gtjosbzvzu.html

composer require --dev phpstan/phpstan
来源：http://dali.redwolf501.top/Article/details/gtjvzekzvz.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtutfwhxcr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hammf.cn/Article/details/gtykpowrkt.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtklozbiba.html

npm init -y;  npm i express
来源：http://dali.wangdashe.top/Article/details/gtkcraeejp.html

[U82] JS：package.json 脚本
来源：http://dali.xziqi.cn/Article/details/gtgdwfpdfk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gtpqbjxeed.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gtflmjvars.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtvoorwesa.html

[U84] JS：CommonJS 写法
来源：http://dali.dashuyun.cn/Article/details/gtttxudvmp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gtftjvlrwf.html

[U85] JS：可选链
来源：http://dali.pycfn.com/Article/details/gtptbwmvgi.html

a?.b?.c
来源：http://dali.zhoulong.xyz/Article/details/gtbeakboiq.html

[U86] JS：空值合并
来源：http://dali.xuanzx.com/Article/details/gtmekpvefm.html

a ?? b
来源：http://dali.chenjidiqi.icu/Article/details/gtayljfiwy.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gtiidawohg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gtogovpuip.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gtpnpbydnq.html

{ ...a, ...b }
来源：http://dali.yuxming.cn/Article/details/gtulpsgpip.html

[U89] JS：数组去重
来源：http://dali.vqdsnc.cn/Article/details/gthfakpfnb.html

[...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtyaollxan.html

[U90] JS：数字数组排序
来源：http://dali.nwbrower.top/Article/details/gthouokfxa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtcagmwdqn.html

[U91] JS：对象键值遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtygojbqjb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ppjwa.cn/Article/details/gtejfbltmi.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gtnwsmxqhx.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtuawpnggn.html

[U93] JS：模板字符串
来源：http://dali.tianlin.xyz/Article/details/gtztbcmnmu.html

`共 ${n} 条`
来源：http://dali.tian-w.cn/Article/details/gtbnnolrnv.html

[U94] JS：箭头函数
来源：http://dali.cashguo.top/Article/details/gtdcclgkta.html

const double = x => x * 2;
来源：http://dali.ivvv.top/Article/details/gtlxdowjpz.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtbfudeuoi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhoulong.xyz/Article/details/gtexxahprj.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnoimtdo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtfveqewgy.html

[U97] JS：并发请求
来源：http://dali.ehwqpu.com/Article/details/gttqnixxcn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuhlvyad.html

[U98] JS：fetch 带 JSON
来源：http://dali.dianchejie.cn/Article/details/gtrltnhbwe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yueranfly.top/Article/details/gtbycnncgq.html

[U99] JS：事件监听
来源：http://dali.jianghu66.top/Article/details/gtqvivchdz.html

el.addEventListener("click", e => {})
来源：http://dali.sxryk.cn/Article/details/gtpcolqmuj.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gticxwpqrq.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gtuhninhlk.html

[U101] JS：classList 操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gteppvctrw.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gtktbrabmi.html

[U102] JS：本地存储
来源：http://dali.gogol.net.cn/Article/details/gtdmbpvhhn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.wangdashe.top/Article/details/gtzilloqce.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gtaollobfb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtqkusudsm.html

[U104] JS：防抖
来源：http://dali.yj20258.top/Article/details/gtydbwebuf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtzvppfxvs.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtkuvszlpm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gtfrxnbjui.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gtxqrvuama.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gttbicvlae.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gtgkzybhta.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtlkwsqshq.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtfrlpfdav.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xziqi.cn/Article/details/gtomxbnlmy.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gtbikotqip.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtzlwnrirp.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gttfuhozey.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gtakkonttd.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjibiymmw.html

new Map(Object.entries(obj))
来源：http://dali.yueranfly.top/Article/details/gtjqvignqj.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gttldiolfu.html

"7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gtilhwrwwk.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gtcemnhnrv.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtgsxfgrmq.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gthvvbkwhf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ppjwa.cn/Article/details/gtvyqmncys.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtowflctde.html

crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtxhiudbnf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gtrgjdzyqf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gtujpegavu.html

[U117] JS：单元测试
来源：http://dali.xylfe.cn/Article/details/gtxkvjtmsx.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gtzasgxneq.html

[U118] JS：开发服务器
来源：http://dali.haohaochexian.top/Article/details/gtyfrwcxyf.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gtczwhwytg.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtehawtvex.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtrvwjrelk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gtiiytgicb.html

import.meta.env.VITE_API_URL
来源：http://dali.jlsjyb.cn/Article/details/gtwlhymtgw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzvvjnqjn.html

统计汇总
来源：http://dali.zycfv.cn/Article/details/gthbyoahuk.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbutqwsfm.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwdnydcy.html

Python ......... 252
来源：http://dali.dashuyun.cn/Article/details/gtzbbddtbp.html

PHP ............ 252
来源：http://dali.kuanghao11.cn/Article/details/gtxluttlew.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtkbbvvfrw.html

TypeScript ..... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtdhbclnef.html

Java ........... 212
来源：http://dali.xinyue.icu/Article/details/gtdujfzfti.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtzzohmcyq.html

Ruby ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtixncolhi.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gtmvspegxc.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gthgkdymyp.html

C++ ............ 30
来源：http://dali.gzhubu.top/Article/details/gtcebepltd.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gtjtkmnepi.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtkpfhyehs.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtwjaswdlb.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtjjafwwjn.html

Lua ............ 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiaaypuz.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtiluwxxke.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gtcioykjea.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtmgxagqya.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gthmkluufv.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gtqrixkaxy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtmswprewo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhixingplan.top/Article/details/gtkdfvxeaw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjnvdvhf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtyxotkqfs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gtzmdkwwpz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtgtwvmwaj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtibmnnqxa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtpidykntb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtdcgqmgmg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtbnepbyvp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtjmqxckbu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrtxcnck.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtuiupjbfe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtumyjfsxp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.bjfxy.top/Article/details/gtjprftilc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtebtzokxz.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsraqyvdm.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gtoszymnrb.html

S C / C++ 专题                          60
来源：http://dali.ydzc1.top/Article/details/gtqlvijrkk.html

T 其他语言补充                          60
来源：http://dali.ppjwa.cn/Article/details/gthhblkibh.html

U 高频实用片段                         120
来源：http://dali.gotoacloud.top/Article/details/gttiuvsdxr.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtxhnekjcy.html

合计                                  2106 条
来源：http://dali.cheryme.top/Article/details/gtbtqfzzeh.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtznpstwsa.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gtmudlkdpg.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtufpfkrdn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtzhlrsszp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagbbqzzb.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.daria6918.cn/Article/details/gtgftiatya.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gtzzlgxflu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cheryme.top/Article/details/gtiksrbkqk.html

—— 文件结束 ——
来源：http://dali.chenzaomai.com/Article/details/gtshainxbr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthggppgeg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sufxvd.cn/Article/details/gtfhftwcom.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetcihpto.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfljgtwgl.html

【收录内容】
来源：http://dali.pengpengdd.cyou/Article/details/gtqvuoutze.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gtgyvxjjpl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zycfv.cn/Article/details/gtrphscmar.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtoednprei.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gtemifjaoy.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gtjialkgnp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yuxming.cn/Article/details/gtguhkquak.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.haohaochexian.top/Article/details/gthmhvlusm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gtzihsrkop.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.meibo888.top/Article/details/gtsvuajfaz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.andypj.xyz/Article/details/gtexivwvib.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cqqwz.cn/Article/details/gtzezaedfu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.birdmap.top/Article/details/gtxbvckthq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guowangkeji.top/Article/details/gtxyasminr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuetiantiany.cn/Article/details/gtnzlqwmtn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.pengpengdd.cyou/Article/details/gtbtcxyavr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtwcikhzhd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gtqjlnzujk.html

【文件统计】
来源：http://dali.316326.xyz/Article/details/gtejkplaua.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tianlin.xyz/Article/details/gtczlsvogc.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtfrlfkszx.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgxgdlhm.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtialbdklr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gtfjudsofq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ppjwa.cn/Article/details/gtzdroupyo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtjqdtifjz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtroffwmtq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258.top/Article/details/gtxykxgvna.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhoulong.xyz/Article/details/gtafccrevm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtbyeduwho.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gthxzjekvs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtzbyyzeed.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jianghu66.top/Article/details/gtsppfhgqj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtllgjqxyu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtuzziftaf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtbrlpvazu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtsmusxotc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gtdwlqohty.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtrszqfjmp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.snrcjt.cn/Article/details/gtoiplznsx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangdashe.top/Article/details/gtlgpwprma.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gtnaukbqvr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtfrjvjdju.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtzkfxuqub.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtfxhyisyd.html

A. 基础语法与类型
来源：http://dali.smart0.xyz/Article/details/gtmvzzchrf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtoalxhuip.html

[A01] Hello World
来源：http://dali.sxryk.cn/Article/details/gttquoiikv.html

Py:   print("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtgllhwnia.html

PHP:  echo "Hello, World!";
来源：http://dali.nwbrower.top/Article/details/gtxnouunug.html

JS:   console.log("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gthbmdsibd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gtrbbxmyjj.html

Java: System.out.println("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtbxxhlpwu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtenurlqve.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gtfrlhehpa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtdtrrnwco.html

[A02] 变量声明与赋值
来源：http://dali.jqgufenzy.top/Article/details/gtmrimnlmg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenlongwang.top/Article/details/gthsivulyp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sysykeji.top/Article/details/gtxabpweqp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ydzc1.top/Article/details/gtogfaabqk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gtkqtcxifs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtstrqmrmt.html

Go:   name := "Alex"; age := 20
来源：http://dali.andypj.xyz/Article/details/gtvlhnqxxm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gtplwlbtqg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtrouweddu.html

[A03] 常量定义
来源：http://dali.gaohongyu789.top/Article/details/gtoluffimw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhongyouzk.top/Article/details/gtydidxyot.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqsvjpvj.html

JS:   const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gthtcnqyvb.html

TS:   const PI: number = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gthkvznzhv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtickbvedk.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtbalfwemt.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtocjgrqsc.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtrpadzflk.html

[A04] 判断变量类型
来源：http://dali.iojbl.cn/Article/details/gtozujnizc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gtsvhenfnq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gttllwuuib.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinghuilouyu.cn/Article/details/gthxdppepu.html

TS:   typeof x; x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gtzfaxfcvl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwkgzcng.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.9152youxi.cn/Article/details/gtwekwatxe.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.daxiang520.top/Article/details/gtwsmjzgfy.html

C#:   x.GetType().Name; x is int
来源：http://dali.ehwqpu.com/Article/details/gtqpbfijnx.html

[A05] 整数除法与取模
来源：http://dali.zhengqikj.top/Article/details/gtxiadqbyf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ybcxt.top/Article/details/gtmgkagvrw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtvbaqytei.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtqiwofbhm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtxldbhejn.html

Java: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gttyygwylg.html

Go:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtfbrcfdqy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtztzfbdai.html

C#:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtgyrqiuvw.html

[A06] 字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtohtufsyp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdbnlixw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxuanxn.top/Article/details/gtaodyahze.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gtydbjwdpf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yuanzhike.top/Article/details/gtcswhukbr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gthicigygf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.andypj.xyz/Article/details/gtbmginvtp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jyoumei.cn/Article/details/gtwovcvfup.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daria6918.cn/Article/details/gtdgbjsrqz.html

[A07] 数字转字符串
来源：http://dali.daria6918.cn/Article/details/gtwzwflntu.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gtcarllbze.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigufen.top/Article/details/gtwdyuaidy.html

JS:   String(42); (42).toString()
来源：http://dali.svipenyu.cn/Article/details/gtblhyarqg.html

TS:   String(42)
来源：http://dali.tian-w.cn/Article/details/gtuskjfxoo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkrvhzqw.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gtuopzlwdi.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gtjoewbnul.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gthvwpabqq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gtkxlrduch.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtbgzzuciq.html


<!-- 参考信息 -->