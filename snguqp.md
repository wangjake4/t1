代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gtiyngojam.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gthxbbqmpm.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtaktxsbdz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gtmzhplgag.html

[U61] PHP：正则
来源：http://dali.ydzc1.top/Article/details/gtwivgljcr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtidbqibji.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gtjeibvkrk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclbargtz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gttyqfjmve.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gtbajgwpwx.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gthmauetlb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gtxytemple.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gttjhoyuwa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtjzkykfmw.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gtprscowvq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtgyueeffm.html

[U67] PHP：处理文件上传
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuisqdyx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuxming.cn/Article/details/gtuzrvgenc.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtgkdqyvkr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gtyzaqczku.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gtercnkdtf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daxiang520.top/Article/details/gtbcqraect.html

[U70] PHP：PDO 事务
来源：http://dali.yanxiufei.cn/Article/details/gtqoguslyz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtivmlktlp.html

[U71] PHP：抛出异常
来源：http://dali.hnqzz.top/Article/details/gtvxlibkoa.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtwoynsmog.html

[U72] PHP：写错误日志
来源：http://dali.chenlongwang.top/Article/details/gtjlejpcpv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gtzpwdizxp.html

[U73] PHP：读取 ini 配置
来源：http://dali.meibo888.top/Article/details/gteeudincd.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gttbexxieb.html

[U74] PHP：读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtvezismqc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gtowoacldq.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtxoxfqfjs.html

composer require psr/container
来源：http://dali.jinqigfzy.top/Article/details/gtsigpsgrt.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gtnbcpqvzs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtouyjbjcc.html

[U77] PHP：模板渲染
来源：http://dali.bjfxy.top/Article/details/gtaywnswgl.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gtakurmhgi.html

[U78] PHP：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gtfgqxsawj.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtjcmhbeyy.html

[U79] PHP：静态分析
来源：http://dali.ivvv.top/Article/details/gtmosombol.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gtjjzwaedz.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtygctpjcb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hysaishi.cn/Article/details/gtincqphlj.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gthsvnkxpo.html

npm init -y;  npm i express
来源：http://dali.yuanzhike.top/Article/details/gtftkfeoxc.html

[U82] JS：package.json 脚本
来源：http://dali.mhx1999.top/Article/details/gtomgjeajs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtijqmssna.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenlongwang.top/Article/details/gtfxekzjbw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtszwoxtze.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgfzy.top/Article/details/gtoipzpyoq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shuidangran.top/Article/details/gtkcgrjuxu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gtpervwmlr.html

a?.b?.c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsornyka.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gtdxmvwrui.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gtrmhazueg.html

[U87] JS：解构默认值
来源：http://dali.bjfxy.top/Article/details/gtzldznjlg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hnxiangtu.top/Article/details/gtuzdjwnem.html

[U88] JS：对象展开合并
来源：http://dali.cucudq.cn/Article/details/gtwcnsnijz.html

{ ...a, ...b }
来源：http://dali.cucudq.cn/Article/details/gtsqgpdwbe.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gtqzutllbw.html

[...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtwyslxaup.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtdmpgotsr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtjsjikovf.html

[U91] JS：对象键值遍历
来源：http://dali.hnxiangtu.top/Article/details/gtivzevhbe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtyvjfsywv.html

[U92] JS：深拷贝
来源：http://dali.snrcjt.cn/Article/details/gtxjubfgjh.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtrusbmcdx.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gterpvrulh.html

`共 ${n} 条`
来源：http://dali.316326.xyz/Article/details/gtvjzcrtry.html

[U94] JS：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtlnphwqsq.html

const double = x => x * 2;
来源：http://dali.haohaochexian.top/Article/details/gtrcayuney.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gteysnvbft.html

new Promise((resolve, reject) => {})
来源：http://dali.tanke756.top/Article/details/gtfxsvwfyu.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gtoelbmeyg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtghityihp.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gthobvzmka.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtrcdxeuyu.html

[U98] JS：fetch 带 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtbqiampcc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqrofhga.html

[U99] JS：事件监听
来源：http://dali.chenlongwang.top/Article/details/gtvlhshgba.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtvodxxbmy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gtcarcmhos.html

document.querySelector(".item")
来源：http://dali.guowangkeji.top/Article/details/gtgwzfskvn.html

[U101] JS：classList 操作
来源：http://dali.xziqi.cn/Article/details/gtmfdnqpth.html

el.classList.toggle("active")
来源：http://dali.hongshengwenyu.top/Article/details/gtvdsststr.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gtlqzuqohj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtmrqrnqif.html

[U103] JS：定时器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkphardg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gtdksuohik.html

[U104] JS：防抖
来源：http://dali.guowangkeji.top/Article/details/gtkassnoms.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwlgsbrl.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gtxybprbgh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.havefunace.top/Article/details/gthudzpund.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtvzkzxsnu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtrjondrcb.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gtqkdrtfld.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtllkgzswo.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gtcjexlram.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yanxiufei.cn/Article/details/gtoiwupzga.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtscvhzzqh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtvwdfltdx.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtsahcbgli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtdfzburht.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gterjwxvmh.html

new Map(Object.entries(obj))
来源：http://dali.smart0.xyz/Article/details/gtzcojumbd.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gtqijcptmt.html

"7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtujfupywh.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gttkkklkmq.html

s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtnmwpwdri.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gtskzzkbrn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtkpwdsheg.html

[U115] JS：生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtxnislfph.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtcjjznpjz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gteavwxsam.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfdjubwl.html

[U117] JS：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gtchulwwtx.html

npm i -D vitest;  npx vitest
来源：http://dali.cashguo.top/Article/details/gtyuaaaxue.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gtgqnxvynq.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtivfijqlf.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gtokfrjsdw.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtjycaimil.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtdlkxkcuc.html

import.meta.env.VITE_API_URL
来源：http://dali.316326.xyz/Article/details/gtudbuictf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfbbtjrvw.html

统计汇总
来源：http://dali.nanxuanxn.top/Article/details/gtookagbmy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdknywxlk.html

按语言统计（条）：
来源：http://dali.tanke756.top/Article/details/gtpzgpxtyl.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gtkfwdgmbg.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtcqwprzjb.html

JavaScript ..... 252
来源：http://dali.tanke756.top/Article/details/gtdribrvau.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtpedlzlua.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtvhhwytlc.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtcwlwxzvw.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgvsxaxy.html

C# ............. 212
来源：http://dali.iojbl.cn/Article/details/gtphpatahf.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtrxvgnioe.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gtnwnbmjzr.html

SQL ............ 90
来源：http://dali.iojbl.cn/Article/details/gtbmtbesse.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtzuwkxopl.html

Kotlin ......... 15
来源：http://dali.havefunace.top/Article/details/gtyigjsrdf.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtxgelanqz.html

Lua ............ 10
来源：http://dali.yj20258.top/Article/details/gtpfrmuenm.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gthlwxmrbp.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gtajgativd.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtvlkvirli.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtuucxxrnk.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gtiqjqcqsk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtqtveacdn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtcmcklttr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtgmrnqzga.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gtxnbbkmyo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgufenzy.top/Article/details/gtxjysdzbd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gthyxlwyxk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtschixptx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmhrxfgn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtxmpttflo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gtgkqkzfzf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuanzx.com/Article/details/gtirisafco.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtjuiajkex.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtdjzvtntp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtuhfzytbi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yangfankeji.com/Article/details/gtuttkcumm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtqmwuvvzx.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gtluzitbqr.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gtmbyunwab.html

S C / C++ 专题                          60
来源：http://dali.jianghu66.top/Article/details/gtdjoylxln.html

T 其他语言补充                          60
来源：http://dali.daxiang520.top/Article/details/gtykuoqabh.html

U 高频实用片段                         120
来源：http://dali.jlsjyb.cn/Article/details/gtdsfbsjug.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gthtvtbral.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtyyhzupor.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtsdyknvqq.html

使用提醒
来源：http://dali.ydzc1.top/Article/details/gtywziaxgy.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtzbiigrfe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gtxqfofbyb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gtmdmmwfky.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhoulong.xyz/Article/details/gtysuubzvu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gtavgbdtnn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxuanxn.top/Article/details/gthauhfwth.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtwsnqycoo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqnnzujia.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dashuyun.cn/Article/details/gtshyxnsxe.html

Common Programming Examples Cheat Book
来源：http://dali.nanxuanxn.top/Article/details/gtxgvrmfcf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkjgnfpqk.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gtqqzbzomk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pengpengdd.cyou/Article/details/gtoghnldhp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gtajmeivkb.html

SQL · Bash · C · C++
来源：http://dali.iojbl.cn/Article/details/gtidsqctob.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.havefunace.top/Article/details/gtjwuywidq.html

【使用说明】
来源：http://dali.fzhhl.top/Article/details/gtlfbfpxex.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sysykeji.top/Article/details/gtlyneaijf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvouazdq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewoqzqhg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.quarkkingdee.top/Article/details/gtdhaafljl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.bjfxy.top/Article/details/gtsijkkmob.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zdqjudy.top/Article/details/gtpdadlevx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.havefunace.top/Article/details/gtgoxbnoxh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gtzusrfkpw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yueranfly.top/Article/details/gtbmnshvbk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hywenlv.cn/Article/details/gttnlirfca.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gtczmeuvah.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.dianchejie.cn/Article/details/gturyeoypr.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gtaubpiucc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gtjlycpknx.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtwfxxkapk.html

目  录
来源：http://dali.yonumen.top/Article/details/gtoniwicpj.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtrqcvylmv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shzxlz.cn/Article/details/gtlcezhzox.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtrzhjnbsc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtgrgestmc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfeognfm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gtwfjuniqx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gtlzhdcvcn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtaxpbtorh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gtyaebjhwm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqehyyolc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtcdouvsky.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtvvovsezr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtgdqirsyf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gthaplpuvs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtxtfirstx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtxpguafnj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtpwcdgsct.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtdhofeenx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gtqftiwdrw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.meibo888.top/Article/details/gthkjyxfxr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtpmxhhpwy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtsfzztbdi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlwxlymhd.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gtutcsfzey.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxdqsfzby.html

[A01] Hello World
来源：http://dali.shuidangran.top/Article/details/gtzrhcmanl.html

Py:   print("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtytbnluzt.html

PHP:  echo "Hello, World!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotdjajvl.html

JS:   console.log("Hello, World!");
来源：http://dali.yuanzhike.top/Article/details/gtghumsgyg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zycfv.cn/Article/details/gtcelpntlh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtchzhrhfl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtlbzdwccj.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gtkqudpmfo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtvcdppwnw.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gticfwhnah.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxinkj.top/Article/details/gtdhoaiaut.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtqwjzjibx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gtgaaochsa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yvedp.cn/Article/details/gtxgkrefpt.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xinyue.icu/Article/details/gtqdnxsysf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhixingplan.top/Article/details/gtqrnforqh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpxhdaas.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtjmguoqae.html

[A03] 常量定义
来源：http://dali.jlsjyb.cn/Article/details/gtngaxgdlw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xylfe.cn/Article/details/gtixxzadgj.html

PHP:  const PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtolhlsmnx.html

JS:   const PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtbgullqes.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtbbhtjnyt.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtlojaqgiy.html

Go:   const PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtywzxhgtc.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gtqdvxjuaf.html

C#:   const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtuprwvleb.html

[A04] 判断变量类型
来源：http://dali.cucudq.cn/Article/details/gtyjvlgvob.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sysykeji.top/Article/details/gtwpzutulw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtvpanvuyj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ehwqpu.com/Article/details/gtjjonbzvv.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gthznedpjj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dashuyun.cn/Article/details/gtbweqvhnn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gtaeywvhyh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwwzdgdy.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gthgesqrei.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gtbsqutgvm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.tanke756.top/Article/details/gtqsnkxqke.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtgeasbhib.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtrfaxpimo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gtmhabyxmd.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtjwoyoqap.html

Go:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtxhmzbcun.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtlwjhjgrb.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtweshfqbi.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtjmrberav.html

Py:   int("42"); float("3.14")
来源：http://dali.wangdashe.top/Article/details/gtksgtdana.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gtahmmstci.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgufenzy.top/Article/details/gtlpudtbov.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtgqceicvg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gtsckhckdl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtldfojlsq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gtyvobnuxz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtjzagjxzy.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gtlvibmoug.html

Py:   str(42)
来源：http://dali.daxiang520.top/Article/details/gtrewqcksm.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gtehjrhjbq.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gtrxffilpp.html

TS:   String(42)
来源：http://dali.yuxming.cn/Article/details/gtxvwndcyi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cdnleiting.top/Article/details/gtfgpuhiiu.html

Go:   strconv.Itoa(42)
来源：http://dali.wangdashe.top/Article/details/gtadpnyjko.html

Ruby: 42.to_s
来源：http://dali.daxiang520.top/Article/details/gtukgiygyj.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gtrqhpbigl.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gticmtbauz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtshyhvkjn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gtqbytekkf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylcxppmt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ybcxt.top/Article/details/gtbtazsolc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gttxwuajet.html


<!-- 参考信息 -->