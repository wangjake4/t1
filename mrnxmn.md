代发 wailian999

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gt2ptqxydic.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxvnorce.html

[U52] PHP：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gt2qpdgkspz.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gt2ebwxfzzk.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gt2lznvmuul.html

$v = $a ?? $b ?? "default";
来源：http://dali.jianghu66.top/Article/details/gt2zbwtcale.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gt2squoxdjn.html

$obj?->method()
来源：http://dali.yanxiufei.cn/Article/details/gt2ejsdfshq.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gt2aaufdrix.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2nirkebnt.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2jednqsbh.html

f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2axzvcadk.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2eodvgeap.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gt2nhsttkzn.html

[U58] PHP：数组三件套
来源：http://dali.zhoulong.xyz/Article/details/gt2xlwreyhv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shuidangran.top/Article/details/gt2dckrntlw.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gt2pekhdpfl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gt2ntgyqbey.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gt2trdofssa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.9152youxi.cn/Article/details/gt2qsejpiil.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gt2gmsxmysu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gt2roxbeetx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpnntqt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gt2sknhmvxk.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amkkolen.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hysaishi.cn/Article/details/gt2adfemmhn.html

[U64] PHP：目录遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2nsdtfdow.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gt2wwocvxcy.html

[U65] PHP：会话
来源：http://dali.chenlongwang.top/Article/details/gt2mvqxaedn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wznmbkft.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gt2zbnctqhi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gt2nuazbtnz.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gt2uqdkfqis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gt2rqfstdie.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gt2vvruktmy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxinkj.top/Article/details/gt2tjlphmuu.html

[U69] PHP：PDO 预处理
来源：http://dali.yj20258.top/Article/details/gt2ikscbndf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2oadqftku.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gt2sjxryymd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gt2iddjtqtf.html

[U71] PHP：抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2cgdnjalu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2jihgpueh.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2xuwewahv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.haohaochexian.top/Article/details/gt2ycbxkuhn.html

[U73] PHP：读取 ini 配置
来源：http://dali.daxiang520.top/Article/details/gt2exaifazg.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uibnyizh.html

[U74] PHP：读取环境变量
来源：http://dali.yueranfly.top/Article/details/gt2wulrppwf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gogol.net.cn/Article/details/gt2cnoemdjl.html

[U75] PHP：依赖注入
来源：http://dali.chenjidiqi.icu/Article/details/gt2txdofrjt.html

composer require psr/container
来源：http://dali.hysaishi.cn/Article/details/gt2fuqdaqtq.html

[U76] PHP：简单路由
来源：http://dali.sweek.top/Article/details/gt2ssdjkmgg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2hprmpaqm.html

[U77] PHP：模板渲染
来源：http://dali.guowangkeji.top/Article/details/gt2qpliqodj.html

composer require twig/twig
来源：http://dali.hammf.cn/Article/details/gt2lwwglvib.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gt2cekplduw.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gt2xqqjivod.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gt2lnpilqcp.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gt2zsqkxvga.html

[U80] PHP：代码规范修复
来源：http://dali.yonumen.top/Article/details/gt2hcynkdrm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gt2odawcnms.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gt2fxjldhru.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gt2checnfmg.html

[U82] JS：package.json 脚本
来源：http://dali.ehwqpu.com/Article/details/gt2tvkweacd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gt2ijhyogbi.html

[U83] JS：ES Module 导入导出
来源：http://dali.xylfe.cn/Article/details/gt2nhgmrpvi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2hokpmaty.html

[U84] JS：CommonJS 写法
来源：http://dali.feifeiyinyue.top/Article/details/gt2avrvzrwd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouxqepit.html

[U85] JS：可选链
来源：http://dali.sweek.top/Article/details/gt2upjnswux.html

a?.b?.c
来源：http://dali.jqgufenzy.top/Article/details/gt2zndbqedc.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gt2flyqlweh.html

a ?? b
来源：http://dali.shangyingyoupin.top/Article/details/gt2tnabvjfq.html

[U87] JS：解构默认值
来源：http://dali.smart0.xyz/Article/details/gt2kcfuwfqm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gt2embwlyog.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gt2snegxemf.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gt2pbjkhcat.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gt2pvsqqrte.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2jpfuwyfh.html

[U90] JS：数字数组排序
来源：http://dali.haohaochexian.top/Article/details/gt2zibmyfvc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gt2caaqrtbm.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gt2zylmyyjt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.chenjidiqi.icu/Article/details/gt2sftmgycd.html

[U92] JS：深拷贝
来源：http://dali.redwolf501.top/Article/details/gt2kfncxwhb.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2cyckzcmy.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gt2vunzxxzy.html

`共 ${n} 条`
来源：http://dali.hywenlv.cn/Article/details/gt2zltyueod.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gt2lgvudbes.html

const double = x => x * 2;
来源：http://dali.yongpay.top/Article/details/gt2nkrajiey.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gt2wonqlanp.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gt2owllqcbe.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gt2wyswerrr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2cpbzcohx.html

[U97] JS：并发请求
来源：http://dali.jyoumei.cn/Article/details/gt2eqbcixyi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2kifovqpj.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj202588.top/Article/details/gt2sawkwoev.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvtsnlox.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gt2qlbcugnc.html

el.addEventListener("click", e => {})
来源：http://dali.yonumen.top/Article/details/gt2iyrxfcmx.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gt2eddzsovt.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gt2peuumjsf.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gt2cwjzxppk.html

el.classList.toggle("active")
来源：http://dali.c1oappe.top/Article/details/gt2kagzbqes.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gt2jpweludy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.birdmap.top/Article/details/gt2lilkohga.html

[U103] JS：定时器
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdrsdexu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yanxiufei.cn/Article/details/gt2mhxmgtpl.html

[U104] JS：防抖
来源：http://dali.aizwys.cn/Article/details/gt2eyrjalnk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gt2bpntaqoh.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gt2pfrqquif.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jianghu66.top/Article/details/gt2wjkxcbdr.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2wlzsherf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gt2jfylduku.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gt2cidfgtbe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.tian-w.cn/Article/details/gt2adeuzuua.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gt2qstkwhxh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gt2semwatkq.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gt2bxhnwsxl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gt2hfdadjmw.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gt2aamynjok.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gt2wsrvdsud.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gt2nimmfrkk.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2jdtjhcrc.html

[U112] JS：字符串补位
来源：http://dali.sysykeji.top/Article/details/gt2fempzkjm.html

"7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gt2rzpbjpgw.html

[U113] JS：正则替换全部
来源：http://dali.chenzaomai.com/Article/details/gt2naubuttf.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2dazilgcj.html

[U114] JS：JSON 深比较
来源：http://dali.ybcxt.top/Article/details/gt2qxywtomk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2wibejxmi.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gt2hoifnwgo.html

crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gt2qrqwgubt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gt2bzsmkqfh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnlisxr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmytgki.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gt2hdqdtyen.html

[U118] JS：开发服务器
来源：http://dali.jianghu66.top/Article/details/gt2ntftkkit.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2miwdrecq.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gt2oqnovdbm.html

npx vite build
来源：http://dali.birdmap.top/Article/details/gt2xcadibgt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gt2tuohgtkc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gt2krczelka.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2gxatqlvh.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gt2alhzfylw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cyqioljp.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbfehtau.html

Python ......... 252
来源：http://dali.hammf.cn/Article/details/gt2rlinskla.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwxccdxc.html

JavaScript ..... 252
来源：http://dali.ivvv.top/Article/details/gt2ejfmdaqz.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gt2plyepakn.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gt2mbqmgalo.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2lmxokwld.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gt2jyzotoop.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gt2hvsdkuvh.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gt2rlbksthh.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gt2hagvnyxs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvxazpc.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gt2gyrqogxw.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gt2tqenmplp.html

Swift .......... 15
来源：http://dali.kuanghao11.cn/Article/details/gt2agognsbe.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gt2vphvpqak.html

Perl ........... 10
来源：http://dali.tanke756.top/Article/details/gt2xdyawjun.html

Scala .......... 10
来源：http://dali.daxiang520.top/Article/details/gt2cushtcbs.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2zowkpadh.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gt2dmeebfgf.html

按章节统计：
来源：http://dali.sysykeji.top/Article/details/gt2objkqnsh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2yzqfmwfu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2zesaqltl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.snrcjt.cn/Article/details/gt2medlxyzf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zdqjudy.top/Article/details/gt2yhfgbuji.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xziqi.cn/Article/details/gt2piqvddvi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gt2moykmvlb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gt2vxgqkrrt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2lfxyaojq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2fdxyrvgw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2vbirjdmg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2oyofuvfo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2zihprgpq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2gohdjstq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrtimaht.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vywvmapd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2ngaedumg.html

Q SQL 专题                              90
来源：http://dali.haohaochexian.top/Article/details/gt2zaxtqzeq.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gt2dfnygmsb.html

S C / C++ 专题                          60
来源：http://dali.gogol.net.cn/Article/details/gt2otiaumyi.html

T 其他语言补充                          60
来源：http://dali.dashuyun.cn/Article/details/gt2uthvwevp.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gt2dlhgfgfe.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2uzubyuus.html

合计                                  2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdbldxbw.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzlkbyus.html

使用提醒
来源：http://dali.yj20258.top/Article/details/gt2vkfarhhz.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2stoawmbt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gt2krmtlghu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenlongwang.top/Article/details/gt2udgngrhq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gt2swkvrcrp.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gt2auvugwkk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gt2bwhwuish.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gt2iojuhsgd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hsnvxdyp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqewzslw.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gt2umhdgpjf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2wbwmqehv.html

【收录内容】
来源：http://dali.hnqzz.top/Article/details/gt2hjblbasj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gotoacloud.top/Article/details/gt2yqxtruht.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.kuanghao11.cn/Article/details/gt2gvkdkrwb.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gt2nyhgndux.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.kuanghao11.cn/Article/details/gt2dpqbztli.html

【使用说明】
来源：http://dali.gotoacloud.top/Article/details/gt2wttozacv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gt2zqyixnhg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.bjfxy.top/Article/details/gt2zdopbjwj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gt2vopbflty.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.vqdsnc.cn/Article/details/gt2immtwggs.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gt2bvhuzcxd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258888.top/Article/details/gt2uflkjmtm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenjidiqi.icu/Article/details/gt2ugysmccl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfdlvlhg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqsedjcp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.svipenyu.cn/Article/details/gt2qeepslnx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujhjuinx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zycfv.cn/Article/details/gt2vzqkjpcj.html

【文件统计】
来源：http://dali.tianlin.xyz/Article/details/gt2cyxvzbod.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcyztcsq.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gt2mmzqupdj.html

目  录
来源：http://dali.jianghu66.top/Article/details/gt2lthtcjwe.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2tdpdrlyt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gt2xgoztqef.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2cjxzhosc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gt2czyxojzy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2jinxyari.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gt2klmfoswo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hywenlv.cn/Article/details/gt2tvsfcgsz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2hmqmbbgl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.0kj1m.cn/Article/details/gt2yhxbjacl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2oeorrspz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxinkj.top/Article/details/gt2kxgfmepw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2jjiqawzs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2ctfcnbpc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctkzkdjz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gt2drqmlhie.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2gzebhved.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2zcxzckmg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gt2nfxpalrs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ydzc1.top/Article/details/gt2eeulewxu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ipogooei.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2slhzxgky.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2fylejnrk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2azwrhzkm.html

A. 基础语法与类型
来源：http://dali.ydzc1.top/Article/details/gt2mnsmnxwx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2heyrleno.html

[A01] Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2dpbtcknm.html

Py:   print("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gt2mswqfaax.html

PHP:  echo "Hello, World!";
来源：http://dali.yongpay.top/Article/details/gt2yiouppqf.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gt2aspnvtnb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gotoacloud.top/Article/details/gt2rmdrmdua.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyhmoviz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gt2dvtbeekr.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2uojyanyj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gt2jlyaozrj.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gt2daavncxc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qontxfhp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2bqfoeyod.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2qqbbwaih.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2wjyspinv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gt2srdpuivw.html

Go:   name := "Alex"; age := 20
来源：http://dali.yvedp.cn/Article/details/gt2haoedkui.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gt2qtwcgrck.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2irtyydcm.html

[A03] 常量定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2yazmagtj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gt2khawoyeq.html

PHP:  const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2qxuunrzc.html

JS:   const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2uilywgvx.html

TS:   const PI: number = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2tybsftuv.html

Java: static final double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2fbaeijko.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gt2inoqmqnh.html

Ruby: PI = 3.14159
来源：http://dali.zycfv.cn/Article/details/gt2mpontkus.html

C#:   const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2htsqmwcg.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gt2tdtpkmvj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.c1oappe.top/Article/details/gt2fkmuwryf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdcenerd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gt2rkpzwupc.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gt2hyhfxwex.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gt2avzmdunb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.svipenyu.cn/Article/details/gt2rrikbuwy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnxiangtu.top/Article/details/gt2aqriucsp.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gt2dxdtoeak.html

[A05] 整数除法与取模
来源：http://dali.hywenlv.cn/Article/details/gt2kkthotdo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ivvv.top/Article/details/gt2lixuprvh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gt2rqdkvdip.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2brrmaehv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gt2unkvtqqu.html

Java: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nviqjfxi.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gt2sqznrqxr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkfmcjtj.html

C#:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2euqbjydn.html

[A06] 字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gt2quafvsec.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gt2yczrnlmf.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ehwqpu.com/Article/details/gt2rfettdke.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.xziqi.cn/Article/details/gt2ekhxarcp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.quarkkingdee.top/Article/details/gt2drcukizn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2wbqylokt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gt2nittrmph.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cheryme.top/Article/details/gt2hwypnrvk.html


<!-- 参考信息 -->