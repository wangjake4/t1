代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2lrvyqdzs.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gt2qmwavhqk.html

[U58] PHP：数组三件套
来源：http://dali.shzxlz.cn/Article/details/gt2mdkmdapc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2ypaledab.html

[U59] PHP：自定义排序
来源：http://dali.ydzc1.top/Article/details/gt2qxnyjlqy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2gdhadexv.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gt2qkfpunrd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gt2kbwvppqc.html

[U61] PHP：正则
来源：http://dali.ydzc1.top/Article/details/gt2tkqvgrux.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kckdjsoq.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gt2ulfkugls.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gt2ctweylej.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gt2cwavfwdk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gt2sjidwabw.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gt2bwrswcgq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gt2yypbtvku.html

[U65] PHP：会话
来源：http://dali.shangyingyoupin.top/Article/details/gt2flzxxvua.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ncnwbfej.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gt2dsdfmudd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gt2wasahvgs.html

[U67] PHP：处理文件上传
来源：http://dali.jiagoushi.top/Article/details/gt2munftwwf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.iojbl.cn/Article/details/gt2czuqihwv.html

[U68] PHP：PDO 连接
来源：http://dali.yj202588.top/Article/details/gt2buvkzucs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gt2phamrkdg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mtiprgis.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqydmcil.html

[U70] PHP：PDO 事务
来源：http://dali.jianghu66.top/Article/details/gt2yyydyfch.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cqqwz.cn/Article/details/gt2tkupeuao.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gt2tswiegug.html

throw new RuntimeException("失败", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vofttqlm.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrvvfknl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aizwys.cn/Article/details/gt2fxitzjre.html

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gt2rykdewvy.html

parse_ini_file("config.ini", true)
来源：http://dali.sxryk.cn/Article/details/gt2tztcfxma.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2aaegmbli.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gt2gmoazydh.html

[U75] PHP：依赖注入
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbfctpiq.html

composer require psr/container
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuxuajfm.html

[U76] PHP：简单路由
来源：http://dali.guannengcc.top/Article/details/gt2ppvgstlx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gt2ruglwhmp.html

[U77] PHP：模板渲染
来源：http://dali.xinyue.icu/Article/details/gt2rmzewitg.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gt2wpalunlf.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ditzpnzx.html

composer require --dev phpunit/phpunit
来源：http://dali.dashuyun.cn/Article/details/gt2yvemvsjr.html

[U79] PHP：静态分析
来源：http://dali.tanke756.top/Article/details/gt2heavgczf.html

composer require --dev phpstan/phpstan
来源：http://dali.hongshengwenyu.top/Article/details/gt2ovixwtia.html

[U80] PHP：代码规范修复
来源：http://dali.xuanzx.com/Article/details/gt2ujkgoxzi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gt2vsduvswf.html

[U81] JS：初始化项目
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuerrwli.html

npm init -y;  npm i express
来源：http://dali.havefunace.top/Article/details/gt2kqqkjfyh.html

[U82] JS：package.json 脚本
来源：http://dali.smart0.xyz/Article/details/gt2itbvatnd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guowangkeji.top/Article/details/gt2gqaouwna.html

[U83] JS：ES Module 导入导出
来源：http://dali.cdnleiting.top/Article/details/gt2honuxujl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2obttsaww.html

[U84] JS：CommonJS 写法
来源：http://dali.sweek.top/Article/details/gt2kmzyaude.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rfnsmtmg.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gt2nrxcygvk.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gt2vfswiwjd.html

[U86] JS：空值合并
来源：http://dali.xinyue.icu/Article/details/gt2qlmyehxh.html

a ?? b
来源：http://dali.zdqjudy.top/Article/details/gt2salehafn.html

[U87] JS：解构默认值
来源：http://dali.xziqi.cn/Article/details/gt2pdeeistq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tianlin.xyz/Article/details/gt2pcwsdnvj.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gt2ehzqigrv.html

{ ...a, ...b }
来源：http://dali.jlsjyb.cn/Article/details/gt2nibdmzdk.html

[U89] JS：数组去重
来源：http://dali.hnxiangtu.top/Article/details/gt2jvdlvmaf.html

[...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gt2saffhysb.html

[U90] JS：数字数组排序
来源：http://dali.ppjwa.cn/Article/details/gt2kywgwmyi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gt2ssdmlztl.html

[U91] JS：对象键值遍历
来源：http://dali.fengsongda.top/Article/details/gt2dlfwsyhz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gt2nvvizsjo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaarzbs.html

structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mgmmthlp.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gt2vdkbvufy.html

`共 ${n} 条`
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcktcgvv.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gt2omshcycd.html

const double = x => x * 2;
来源：http://dali.guannengcc.top/Article/details/gt2tjeuamfn.html

[U95] JS：Promise 包装
来源：http://dali.zhoulong.xyz/Article/details/gt2ppsgdaep.html

new Promise((resolve, reject) => {})
来源：http://dali.shangyingyoupin.top/Article/details/gt2bysxmbbl.html

[U96] JS：async/await 与异常
来源：http://dali.meibo888.top/Article/details/gt2ejkfofxe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2scaudcpd.html

[U97] JS：并发请求
来源：http://dali.snrcjt.cn/Article/details/gt2axridahg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2ofepzzbc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkwbljb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvipsisq.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gt2eveyfvlr.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gt2ysbjprns.html

[U100] JS：DOM 查询
来源：http://dali.zhoulong.xyz/Article/details/gt2ijqssssz.html

document.querySelector(".item")
来源：http://dali.gogol.net.cn/Article/details/gt2bhaukoon.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gt2mxuzezbv.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gt2wfhoxail.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gt2obydpezf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ppjwa.cn/Article/details/gt2nbrwrott.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gt2slddpgyw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258.top/Article/details/gt2caowpdxa.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gt2gbiuunap.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2zmkmokqx.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gt2toukkqtl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gt2egrggqia.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2mmjvtrsn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jianghu66.top/Article/details/gt2nhyafdtq.html

[U107] JS：数字千分位
来源：http://dali.redwolf501.top/Article/details/gt2bfqnzqgh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gt2adodnxsg.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gt2tshxzxsb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gt2veuxwutj.html

[U109] JS：数组分组
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqvowsxm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2wpnqgyeu.html

[U110] JS：数组分块
来源：http://dali.ehwqpu.com/Article/details/gt2huwijmsn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gt2ztuyhswn.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gt2lglcggbc.html

new Map(Object.entries(obj))
来源：http://dali.sufxvd.cn/Article/details/gt2lhzqswlg.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gt2wermtwbh.html

"7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2mcaflemh.html

[U113] JS：正则替换全部
来源：http://dali.pycfn.com/Article/details/gt2dlwcswfm.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gt2ywjgtmmt.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gt2lunjvbeu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shzxlz.cn/Article/details/gt2znyayhap.html

[U115] JS：生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2ajekuhcj.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2lcgssmla.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gt2jdvcpoye.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ckgmqkob.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2umawsqoc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctpqxaob.html

[U118] JS：开发服务器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owsnrkgy.html

npm i -D vite;  npx vite
来源：http://dali.xziqi.cn/Article/details/gt2meancxmb.html

[U119] JS：生产构建
来源：http://dali.jianghu66.top/Article/details/gt2vzjskkwr.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gt2tecoevhz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gt2lucwmryc.html

import.meta.env.VITE_API_URL
来源：http://dali.shangyingyoupin.top/Article/details/gt2aejggsxo.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qmbnzaok.html

统计汇总
来源：http://dali.cdnleiting.top/Article/details/gt2ydxjoawv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2zwjfehxw.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvnkxlqb.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gt2ywdnynkh.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gt2hcjdlhkv.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gt2awmvactr.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gt2euviewcj.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmdcashl.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2yqsaayok.html

Ruby ........... 212
来源：http://dali.hnqzz.top/Article/details/gt2rzguhfid.html

C# ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gt2spgesyxx.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gt2gngvnipn.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gt2qdniqzcv.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2qgqywmdv.html

Bash ........... 80
来源：http://dali.cucudq.cn/Article/details/gt2pvwyfizw.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gt2qhhtwbzr.html

Swift .......... 15
来源：http://dali.fzhhl.top/Article/details/gt2fhvqewfd.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gt2umfgwfao.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2knswhuhj.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gt2kjgdlmfy.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2pxjfpegj.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gt2dmnkoreq.html

按章节统计：
来源：http://dali.guannengcc.top/Article/details/gt2wjykseen.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gt2dhioqkoe.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2ncpxmjko.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2kvcwsuuo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gt2vedrbkop.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnfukpih.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpazhftq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2idshjfjm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2arkudlyz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gt2imqtdzgf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.316326.xyz/Article/details/gt2lvxegkii.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2nuwagfuk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2euyryijy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2jkhvozyk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2eylbnyfu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gt2xtkycccp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2qqkgrkqo.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gt2ovqxhzjc.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gt2ktbedajk.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gt2yaeuykss.html

T 其他语言补充                          60
来源：http://dali.gaohongyu789.top/Article/details/gt2rpalqpnh.html

U 高频实用片段                         120
来源：http://dali.cashguo.top/Article/details/gt2uvnffito.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gt2ksgmjixg.html

合计                                  2106 条
来源：http://dali.yongpay.top/Article/details/gt2hjbtdwyw.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2rmumaxew.html

使用提醒
来源：http://dali.zdqjudy.top/Article/details/gt2emcjwwgg.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2kbjettwt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gt2yghgrevc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hoewprpt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hfpthk.cn/Article/details/gt2ehtahxuq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gt2qnbfdsvr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gotoacloud.top/Article/details/gt2xivvpsiv.html

—— 文件结束 ——
来源：http://dali.jinqigfzy.top/Article/details/gt2erytkvax.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2bhjnehgu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.fengsongda.top/Article/details/gt2gqlwkjfq.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gt2qfzaxplh.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wtwfscrq.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gt2rqdojkdt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gt2loxghstv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gt2mecnsuot.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gt2maahrpoz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.iojbl.cn/Article/details/gt2iqgnxvbp.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gt2agispnru.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shuidangran.top/Article/details/gt2nlfluqeg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zycfv.cn/Article/details/gt2mxcsswxg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gt2tjgmdblo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqnicfbo.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tanke756.top/Article/details/gt2mebfpjvm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.iojbl.cn/Article/details/gt2hhzwxpcv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jqgufenzy.top/Article/details/gt2cnbrrrje.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gt2zszkhlbn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jyoumei.cn/Article/details/gt2cssayvtb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sxryk.cn/Article/details/gt2prsdgkbj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.9152youxi.cn/Article/details/gt2bugxgrhv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenjidiqi.icu/Article/details/gt2omfwdbhe.html

【文件统计】
来源：http://dali.svipenyu.cn/Article/details/gt2gevcarnx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gt2upojsasm.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2yyakzwae.html

目  录
来源：http://dali.jlsjyb.cn/Article/details/gt2clwglpvq.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfpxghgj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2csvjhbge.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2kffkpxzn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gt2ifralhvb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gt2iiexxabh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2yxdrmbnp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yuxming.cn/Article/details/gt2xyeidnqb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gt2tobunbnu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2ipggkoki.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qufzisav.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gt2trzssbtt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2xabzlrcq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2abvuswfu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gt2adkueife.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gt2ythxddqa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gt2lmxzchsg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gt2bqjdjanq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgfzy.top/Article/details/gt2sprvtqal.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hammf.cn/Article/details/gt2zsrgeeyk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.316326.xyz/Article/details/gt2mxjlagig.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lkyohyvv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2chkhurvd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvcxbbkx.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gt2zhilnjnm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kqntdakz.html

[A01] Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2mhmniwwt.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2sxwnuhpu.html

PHP:  echo "Hello, World!";
来源：http://dali.haohaochexian.top/Article/details/gt2fvquckkj.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gt2kdariwug.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.redwolf501.top/Article/details/gt2mamtappa.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyxupbs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gt2ikxjgndd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gt2iqdkyobo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gt2mfcmmaah.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gt2nygqbakw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guannengcc.top/Article/details/gt2ajeuzgju.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gt2imukxocr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2khgjjxzb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.redwolf501.top/Article/details/gt2hmqfsqjr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2jbmlxgac.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gt2imocvbrb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnumdcji.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgrmwkn.html

[A03] 常量定义
来源：http://dali.cucudq.cn/Article/details/gt2ujljhorz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrqchznc.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2bdyidywh.html

JS:   const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldhaapgx.html

TS:   const PI: number = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2vwhaeevx.html

Java: static final double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2uvdbfouj.html

Go:   const PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gt2qmtkxhky.html

Ruby: PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gt2grlvrztz.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2siommeju.html

[A04] 判断变量类型
来源：http://dali.gzhubu.top/Article/details/gt2uavmeyvj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.c1oappe.top/Article/details/gt2rcqwgoeq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zdqjudy.top/Article/details/gt2xqjrqezn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2qtpufejj.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gt2nxkcgjsn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.meibo888.top/Article/details/gt2jctgtoaa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pycfn.com/Article/details/gt2quscljdv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxbtcjag.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gt2aapdvgiu.html

[A05] 整数除法与取模
来源：http://dali.cucudq.cn/Article/details/gt2jomwzqzc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gt2aiwjgsfv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2evjcpuqr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwuxhjft.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2uemytdau.html

Java: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2rnnfiezu.html

Go:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2hizdkivx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2gnfspvqf.html

C#:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2itmfmbzh.html

[A06] 字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2qlycldtb.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gt2avofgdmv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2twcxgduj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gt2znbsxekc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gt2qadqxrlc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gt2bvauewib.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigufen.top/Article/details/gt2yjiovfzb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zdqjudy.top/Article/details/gt2qjayvgrk.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.0kj1m.cn/Article/details/gt2mrmaphwp.html

[A07] 数字转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hgfncfgl.html

Py:   str(42)
来源：http://dali.guannengcc.top/Article/details/gt2rauczfiu.html

PHP:  (string) 42; strval(42)
来源：http://dali.hammf.cn/Article/details/gt2tbimoaxc.html

JS:   String(42); (42).toString()
来源：http://dali.hfpthk.cn/Article/details/gt2gwxqpgkt.html

TS:   String(42)
来源：http://dali.cashguo.top/Article/details/gt2acykjgus.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gt2vyqkfofx.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gt2ljyljzdl.html

Ruby: 42.to_s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okfgvsyq.html

C#:   42.ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqjeccna.html

[A08] 取整与四舍五入
来源：http://dali.pengpengdd.cyou/Article/details/gt2dugvkzmm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gt2dxtbahur.html


<!-- 参考信息 -->