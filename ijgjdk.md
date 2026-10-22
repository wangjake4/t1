代发 wailian999

[U51] PHP：数组解构
来源：http://dali.cqqwz.cn/Article/details/gt2arpbmwwh.html

[$a, $b] = $arr;
来源：http://dali.smart0.xyz/Article/details/gt2hxxuycrm.html

[U52] PHP：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gt2yenueplk.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gt2drpuxxmr.html

[U53] PHP：空合并运算符
来源：http://dali.daxiang520.top/Article/details/gt2yfuwjngf.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxuanxn.top/Article/details/gt2kbptpfnf.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gt2boxbhrcr.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gt2tlvqkpcn.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2zynclwkp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gt2eivyjuqt.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2ltrgpnks.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2arehqdbu.html

[U57] PHP：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2mxhqpebe.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2zoaodtkb.html

[U58] PHP：数组三件套
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdmykyph.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gt2ewdohnqy.html

[U59] PHP：自定义排序
来源：http://dali.quarkkingdee.top/Article/details/gt2oyuqqmex.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2dcjtrbaq.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gt2vjoneoqv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gt2zkssyfnn.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gt2bglxkagw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gt2gemfgujy.html

[U62] PHP：日期对象
来源：http://dali.redwolf501.top/Article/details/gt2hwtczalm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gt2vvasjviq.html

[U63] PHP：文件读写
来源：http://dali.jqgfzy.top/Article/details/gt2bjbqffil.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gt2fpvffdlj.html

[U64] PHP：目录遍历
来源：http://dali.9152youxi.cn/Article/details/gt2hrpciudc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gt2lmqpmhjr.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gt2swinnpic.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iqaktate.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gt2xvpefzlu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2mnievfra.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhvlyool.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fzhhl.top/Article/details/gt2ctpziydt.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gt2qiuwkymq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gt2mhiedcqk.html

[U69] PHP：PDO 预处理
来源：http://dali.ehwqpu.com/Article/details/gt2avenviml.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gt2yivgsfpj.html

[U70] PHP：PDO 事务
来源：http://dali.smart0.xyz/Article/details/gt2ynvzebft.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gt2pqzzccfl.html

[U71] PHP：抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gt2atozgxpd.html

throw new RuntimeException("失败", 500);
来源：http://dali.shuidangran.top/Article/details/gt2mujrgshk.html

[U72] PHP：写错误日志
来源：http://dali.ivvv.top/Article/details/gt2stpsvwhu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhmxswxk.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhcrbzxp.html

parse_ini_file("config.ini", true)
来源：http://dali.wangdashe.top/Article/details/gt2yatgsrpk.html

[U74] PHP：读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2ncmwjnnk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjugpivd.html

[U75] PHP：依赖注入
来源：http://dali.hongshengwenyu.top/Article/details/gt2dutfduot.html

composer require psr/container
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywnhqbjo.html

[U76] PHP：简单路由
来源：http://dali.yueranfly.top/Article/details/gt2rrwbjwri.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gt2mzunxcid.html

[U77] PHP：模板渲染
来源：http://dali.dashuyun.cn/Article/details/gt2qkkdypcc.html

composer require twig/twig
来源：http://dali.9152youxi.cn/Article/details/gt2ftelgwti.html

[U78] PHP：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gt2taizffry.html

composer require --dev phpunit/phpunit
来源：http://dali.xziqi.cn/Article/details/gt2mssfjqid.html

[U79] PHP：静态分析
来源：http://dali.bjfxy.top/Article/details/gt2poorrvlg.html

composer require --dev phpstan/phpstan
来源：http://dali.aibaodan.cn/Article/details/gt2xbrxuaek.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gt2popsgeqk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxyqrpke.html

[U81] JS：初始化项目
来源：http://dali.jinqigufen.top/Article/details/gt2uxcfqjgs.html

npm init -y;  npm i express
来源：http://dali.yj20258.top/Article/details/gt2nyhbshmr.html

[U82] JS：package.json 脚本
来源：http://dali.yuxming.cn/Article/details/gt2uqvyxiry.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ayfmrxij.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gt2rmdqtvhw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwhkoadg.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gt2hwjeipew.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gt2awwhbiiy.html

[U85] JS：可选链
来源：http://dali.yvedp.cn/Article/details/gt2fotwuqwb.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gt2dxullzha.html

[U86] JS：空值合并
来源：http://dali.xylfe.cn/Article/details/gt2pmnngyax.html

a ?? b
来源：http://dali.sweek.top/Article/details/gt2ytgeqpmy.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gt2wloprdoi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gt2efzvsfzi.html

[U88] JS：对象展开合并
来源：http://dali.zhiwuduotai.top/Article/details/gt2ollxtpoo.html

{ ...a, ...b }
来源：http://dali.andypj.xyz/Article/details/gt2bqaeyjvt.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gt2vrjjlhds.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2typnkbvo.html

[U90] JS：数字数组排序
来源：http://dali.ydzc1.top/Article/details/gt2ursqjcjn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2lbnmopct.html

[U91] JS：对象键值遍历
来源：http://dali.fzhhl.top/Article/details/gt2xkopaquk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jlsjyb.cn/Article/details/gt2enuyybbe.html

[U92] JS：深拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjjssqvz.html

structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2rwwbibqk.html

[U93] JS：模板字符串
来源：http://dali.smart0.xyz/Article/details/gt2bpyxhiwi.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gt2aifgihqz.html

[U94] JS：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kywckdhb.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gt2uecuedmk.html

[U95] JS：Promise 包装
来源：http://dali.shuidangran.top/Article/details/gt2hdkkboky.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gt2jrjjmanp.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gt2oyytjgdv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gt2eufljwnc.html

[U97] JS：并发请求
来源：http://dali.sysykeji.top/Article/details/gt2hbkptehr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2czdynthi.html

[U98] JS：fetch 带 JSON
来源：http://dali.redwolf501.top/Article/details/gt2mhwamjjs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gt2vkoscuhq.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gt2fklypoit.html

el.addEventListener("click", e => {})
来源：http://dali.hysaishi.cn/Article/details/gt2ejmwclay.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfycoozi.html

document.querySelector(".item")
来源：http://dali.ivvv.top/Article/details/gt2struuxgj.html

[U101] JS：classList 操作
来源：http://dali.gaohongyu789.top/Article/details/gt2hkavzbxg.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gt2bbrszfmi.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gt2pjrvssxu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gt2erffknds.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2evapoqgo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgufenzy.top/Article/details/gt2yicqfqya.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gt2xcgvdcyd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gt2mdpydfav.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbaosxqt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gt2cvywaxui.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2czvouwpn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2ssojmggy.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gt2flwpeasb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2blslztjn.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmmkhyef.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gt2lmnftjrt.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gt2qlrxnfaq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2pixhyadi.html

[U110] JS：数组分块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2svstmfys.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.dashuyun.cn/Article/details/gt2iqqgpjje.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gt2tfhcygml.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufxfwciq.html

[U112] JS：字符串补位
来源：http://dali.hnqzz.top/Article/details/gt2byutdyph.html

"7".padStart(3, "0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgqcquvy.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gt2vwwakocq.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xpmorojs.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2eorqcouo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gt2urwyylms.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2xmgyrxrx.html

crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gt2nxrwkzbx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gt2yrdllcbu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj202588.top/Article/details/gt2duxuvdrx.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2hlrgubtr.html

npm i -D vitest;  npx vitest
来源：http://dali.haohaochexian.top/Article/details/gt2yjwvirdn.html

[U118] JS：开发服务器
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmvqksgi.html

npm i -D vite;  npx vite
来源：http://dali.jiagoushi.top/Article/details/gt2nvfpauzh.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gt2vosugaek.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmlqaobf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ogyupede.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gt2pbzzogvq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2zjpnozzx.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gt2kyspzvpm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfcrgrqh.html

按语言统计（条）：
来源：http://dali.shzxlz.cn/Article/details/gt2ucecvdan.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gt2pexbfhlx.html

PHP ............ 252
来源：http://dali.hammf.cn/Article/details/gt2gkashbwh.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2sirauqzo.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gt2ytfydkoc.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gt2lsobzrga.html

Go ............. 212
来源：http://dali.aibaodan.cn/Article/details/gt2txscktru.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2hoxhjvmm.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2qplonhux.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gt2zwfnblru.html

C++ ............ 30
来源：http://dali.aizwys.cn/Article/details/gt2enbgeiba.html

SQL ............ 90
来源：http://dali.cheryme.top/Article/details/gt2bkqxgtpq.html

Bash ........... 80
来源：http://dali.wangdashe.top/Article/details/gt2zanwphmb.html

Kotlin ......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2bvyhjjfr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ropigpji.html

Lua ............ 10
来源：http://dali.jyoumei.cn/Article/details/gt2cxujjwpg.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gt2blmceozk.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2xnkphppg.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2sydnthpd.html

合计 ........... 2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2dknwbzib.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gt2nxxqyijr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gt2xgbahqcp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2avgdulvg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkftlfbm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2xldexdjv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gt2sonxdzfr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gt2pmjrzxbu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gt2kcohbgoi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2aiazmivu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2wgnetafm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2cgiobxvh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gt2hsfaefqb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2ioqpfsbe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2mhdebtct.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gt2hnirgbnq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gt2wslggggu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2vzknoivp.html

Q SQL 专题                              90
来源：http://dali.316326.xyz/Article/details/gt2fxpyqqny.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gt2arsmwwai.html

S C / C++ 专题                          60
来源：http://dali.gotoacloud.top/Article/details/gt2xlrhnqfz.html

T 其他语言补充                          60
来源：http://dali.c1oappe.top/Article/details/gt2yopmdqot.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2quvvinvf.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2lxvfoxmm.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2chztprxu.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2wknvbulv.html

使用提醒
来源：http://dali.jianghu66.top/Article/details/gt2rwqirdzv.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gt2dxsjqamo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gt2zvwfanbg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2rmqigdwk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhixingplan.top/Article/details/gt2sqyrfpji.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gt2rgikelfp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.vqdsnc.cn/Article/details/gt2puuekmjk.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gt2dkjvmcqm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pquughbz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gt2rtrstvfo.html

Common Programming Examples Cheat Book
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzilrenw.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lglzktzb.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gt2cwoaxurx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gt2owulxgxr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gt2ibrvxerc.html

SQL · Bash · C · C++
来源：http://dali.shuidangran.top/Article/details/gt2atbhajcv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sweek.top/Article/details/gt2rgcqlyqh.html

【使用说明】
来源：http://dali.vqdsnc.cn/Article/details/gt2bovxyxsy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtkmlos.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gaohongyu789.top/Article/details/gt2iiscbmji.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuanzhike.top/Article/details/gt2lgoenzcg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gt2zernnlkc.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gt2gxpfhxbf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gt2uqowlfkh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pycfn.com/Article/details/gt2qahfzsny.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yangfankeji.com/Article/details/gt2qsxszpzp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jlsjyb.cn/Article/details/gt2nuwdpnuu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aibaodan.cn/Article/details/gt2imdiesun.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgufenzy.top/Article/details/gt2jcsyahva.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gt2joxqfque.html

【文件统计】
来源：http://dali.cucudq.cn/Article/details/gt2thmwhxtq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cashguo.top/Article/details/gt2uegxwzpf.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2ffvshkjh.html

目  录
来源：http://dali.tanke756.top/Article/details/gt2ryedqhyo.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2qewuuhgw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2yiiswgyh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gt2mtzvcqeg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhbqjbbd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gt2jnzxzoje.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tanke756.top/Article/details/gt2umlfamgp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nwbrower.top/Article/details/gt2kguoprww.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gt2jfnhhpuq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gt2sxsjxghr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2xtqjexoc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2cevroqzd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2qsallqub.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gt2cwapiabh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2svxyilsf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcqdldli.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2ylxqzqfr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2uxtublni.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gt2bjlaengz.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shzxlz.cn/Article/details/gt2meadptjw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2oirnbwgo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2myeiwjqz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2qlialojb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pdhcwujh.html

A. 基础语法与类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvrhviqr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tyawqbsi.html

[A01] Hello World
来源：http://dali.yj20258888.top/Article/details/gt2vfhcvtnc.html

Py:   print("Hello, World!")
来源：http://dali.yj20258888.top/Article/details/gt2gbwovabw.html

PHP:  echo "Hello, World!";
来源：http://dali.xuanzx.com/Article/details/gt2plewmiwe.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmkeejw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gt2klxtgvnj.html

Java: System.out.println("Hello, World!");
来源：http://dali.shuidangran.top/Article/details/gt2iogsjjwg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gt2xhewmkel.html

Ruby: puts "Hello, World!"
来源：http://dali.ybcxt.top/Article/details/gt2cbbaoooa.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2qkvqgzol.html

[A02] 变量声明与赋值
来源：http://dali.c1oappe.top/Article/details/gt2zgimuopx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gt2ifrmmtjd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2xfleegkv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iyingspi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujecwskx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2orrsedov.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gt2agglytae.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gt2glazvhau.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2pkiecxdv.html

[A03] 常量定义
来源：http://dali.birdmap.top/Article/details/gt2akzrisio.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cheryme.top/Article/details/gt2ytcgmpvt.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mubfvbfh.html

JS:   const PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gt2cwigitnb.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2qalvwzdd.html

Java: static final double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbkynoeb.html

Go:   const PI = 3.14159
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmjcgiej.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gt2vqeqojjj.html

C#:   const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2qnagqhja.html

[A04] 判断变量类型
来源：http://dali.aizwys.cn/Article/details/gt2dajbdunv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnxiangtu.top/Article/details/gt2ikwnulnw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.andypj.xyz/Article/details/gt2icjimppa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2mptqdcaf.html

TS:   typeof x; x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gt2xjzsbesm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258.top/Article/details/gt2pkbacted.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xziqi.cn/Article/details/gt2mwccxcda.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuanzhike.top/Article/details/gt2emhvkrse.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gt2zghvznow.html

[A05] 整数除法与取模
来源：http://dali.316326.xyz/Article/details/gt2nfhnzemc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gt2hlswfakg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2tenrowbz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2wucccfli.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmxkbwrd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvuiijr.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2wwigprsc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gt2sufjnvwq.html

C#:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2sofavipm.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2grojiyen.html

Py:   int("42"); float("3.14")
来源：http://dali.cqqwz.cn/Article/details/gt2arlzmiys.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yongpay.top/Article/details/gt2mxcicieg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fssfpzub.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jlsjyb.cn/Article/details/gt2kkobrgff.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2soqqafqk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pycfn.com/Article/details/gt2siescjfv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yanxiufei.cn/Article/details/gt2ujivzmxn.html


<!-- 参考信息 -->