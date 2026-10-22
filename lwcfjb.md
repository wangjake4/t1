代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwzrxghf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yongpay.top/Article/details/gt2tlqsohby.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gt2njrxogzo.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2nkqhjlik.html

[U57] PHP：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2vretpszy.html

"值: {$a}"
来源：http://dali.jianghu66.top/Article/details/gt2bnikpcnv.html

[U58] PHP：数组三件套
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyikvcig.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gt2jxdhjwdq.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gt2xmbztjtk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkzyslzn.html

[U60] PHP：JSON 编解码
来源：http://dali.chenzaomai.com/Article/details/gt2rcnprbiv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2zmdtplqn.html

[U61] PHP：正则
来源：http://dali.xylfe.cn/Article/details/gt2epbfgqsf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2ljxfboco.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnehypip.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gt2tjlfyqkm.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gt2cxrlvzyz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqtgxpmf.html

[U64] PHP：目录遍历
来源：http://dali.yonumen.top/Article/details/gt2hbuobqkp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cdnleiting.top/Article/details/gt2ffljuuat.html

[U65] PHP：会话
来源：http://dali.zycfv.cn/Article/details/gt2tbuskvgk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2hkboxaqq.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgmkmiug.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2jlsftkuo.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gt2kdodjxdo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzjtbcxb.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gt2aajjushu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfkmbenu.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adniedhy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gt2fnhutfdw.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2eatyyena.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jiagoushi.top/Article/details/gt2ljphfeux.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2eixhwmix.html

throw new RuntimeException("失败", 500);
来源：http://dali.jlsjyb.cn/Article/details/gt2hrfmcoiv.html

[U72] PHP：写错误日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvbcfhzm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigfzy.top/Article/details/gt2ssltjndx.html

[U73] PHP：读取 ini 配置
来源：http://dali.gotoacloud.top/Article/details/gt2lipquqds.html

parse_ini_file("config.ini", true)
来源：http://dali.xylfe.cn/Article/details/gt2bnhenevg.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2jwotvcck.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfgvakcb.html

[U75] PHP：依赖注入
来源：http://dali.meibo888.top/Article/details/gt2omqshick.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahkfxews.html

[U76] PHP：简单路由
来源：http://dali.gotoacloud.top/Article/details/gt2ltxqjvik.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hywenlv.cn/Article/details/gt2qanhyyzb.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gt2frnekrci.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gt2kiwolaso.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gt2orukwzqg.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpbczhqy.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gt2czmcjdpy.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gt2hamgpiqr.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmoxwrph.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuanzhike.top/Article/details/gt2abfjmaot.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gt2xhnuxjdw.html

npm init -y;  npm i express
来源：http://dali.cucudq.cn/Article/details/gt2mqpnhfle.html

[U82] JS：package.json 脚本
来源：http://dali.wangshuangyany.cn/Article/details/gt2qszkwfcl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cggibqej.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gt2smflnkjj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2fbeeikcd.html

[U84] JS：CommonJS 写法
来源：http://dali.gotoacloud.top/Article/details/gt2jrluolci.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.kuanghao11.cn/Article/details/gt2wrbsqcog.html

[U85] JS：可选链
来源：http://dali.gogol.net.cn/Article/details/gt2kqopuuwp.html

a?.b?.c
来源：http://dali.9152youxi.cn/Article/details/gt2nmfzlndj.html

[U86] JS：空值合并
来源：http://dali.zhengqikj.top/Article/details/gt2rmunncmk.html

a ?? b
来源：http://dali.xuanzx.com/Article/details/gt2nmvjdlsu.html

[U87] JS：解构默认值
来源：http://dali.chenlongwang.top/Article/details/gt2otrnfzmi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cdnleiting.top/Article/details/gt2pnuonhck.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gt2evfpbjla.html

{ ...a, ...b }
来源：http://dali.sysykeji.top/Article/details/gt2gqbtxwfl.html

[U89] JS：数组去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpfkzgky.html

[...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gt2iscmizue.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gt2eqodlmkm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxqrwxem.html

[U91] JS：对象键值遍历
来源：http://dali.0kj1m.cn/Article/details/gt2aogowdwc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gt2icplofyp.html

[U92] JS：深拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2vreiawcz.html

structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2gpyfqibg.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gt2mbrpggsx.html

`共 ${n} 条`
来源：http://dali.hnxiangtu.top/Article/details/gt2ylzhdyfu.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gt2xjrqgpbt.html

const double = x => x * 2;
来源：http://dali.meibo888.top/Article/details/gt2ljpyebqf.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gt2ictzdscc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gt2qxznrvbd.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gt2hgywwxur.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwgzbqbs.html

[U97] JS：并发请求
来源：http://dali.cucudq.cn/Article/details/gt2kvqijxod.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2wzzqqito.html

[U98] JS：fetch 带 JSON
来源：http://dali.nwbrower.top/Article/details/gt2qvafrchy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj202588.top/Article/details/gt2zdijbhnv.html

[U99] JS：事件监听
来源：http://dali.zhixingplan.top/Article/details/gt2igooebea.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gt2cvqfmapu.html

[U100] JS：DOM 查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2mpuybxqz.html

document.querySelector(".item")
来源：http://dali.tian-w.cn/Article/details/gt2bxlpnygj.html

[U101] JS：classList 操作
来源：http://dali.svipenyu.cn/Article/details/gt2jfwxcjsm.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gt2diiyakrk.html

[U102] JS：本地存储
来源：http://dali.chenjidiqi.icu/Article/details/gt2srpultqg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gt2satdertx.html

[U103] JS：定时器
来源：http://dali.iojbl.cn/Article/details/gt2iotfrizz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jiagoushi.top/Article/details/gt2dgcbnvbe.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gt2ekxsapap.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2cowfioio.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gt2yuamjoda.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zdqjudy.top/Article/details/gt2equtrkwy.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gt2ixbmmrqb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gt2xeitilzc.html

[U107] JS：数字千分位
来源：http://dali.jqgfzy.top/Article/details/gt2lrclgnvk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gt2rzgrcngg.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gt2bbmryrah.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gt2dhdxiirf.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gt2qbldtjax.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gt2eetfyboy.html

[U110] JS：数组分块
来源：http://dali.yueranfly.top/Article/details/gt2cspwuqsc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2besjaljw.html

[U111] JS：对象转 Map
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqcqtvkk.html

new Map(Object.entries(obj))
来源：http://dali.andypj.xyz/Article/details/gt2yteapdue.html

[U112] JS：字符串补位
来源：http://dali.daria6918.cn/Article/details/gt2hymslamt.html

"7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gt2dubqspbh.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gt2qcjwmuod.html

s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2uqspmpci.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gt2biokqlli.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2ybtggwtt.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2phgqhext.html

crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2uvvzhvgf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gt2okzdmtif.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gt2kipyuyyi.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gt2jkmcinzt.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gt2lzkhjpgn.html

[U118] JS：开发服务器
来源：http://dali.havefunace.top/Article/details/gt2aktnumhc.html

npm i -D vite;  npx vite
来源：http://dali.hywenlv.cn/Article/details/gt2yjlbjfpp.html

[U119] JS：生产构建
来源：http://dali.yj20258888.top/Article/details/gt2vqvpwclu.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gt2rpkwxegh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2whtnxnts.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gt2djjsfuge.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ktftkisr.html

统计汇总
来源：http://dali.aibaodan.cn/Article/details/gt2yuugvkux.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2fjbxpfea.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gt2gnacxhzc.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gt2covoocfn.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gt2msdgctdq.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gt2lxopbbzn.html

TypeScript ..... 212
来源：http://dali.xylfe.cn/Article/details/gt2iyybvhrm.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2tkldzwnq.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2yqbpbjow.html

Ruby ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2cwggdjws.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2ykxxvgjl.html

C .............. 30
来源：http://dali.wangdashe.top/Article/details/gt2tmtsfbam.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gt2dbviiook.html

SQL ............ 90
来源：http://dali.zdqjudy.top/Article/details/gt2dwuuajbz.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gt2plsmuyxf.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njwmzxtl.html

Swift .......... 15
来源：http://dali.yanxiufei.cn/Article/details/gt2mtqkkfyc.html

Lua ............ 10
来源：http://dali.jinqigfzy.top/Article/details/gt2qjbbnpwy.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gt2xxphdjwk.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gt2kfwphyya.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gt2bvfzzlur.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2izrsbokl.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gt2ykilfwyo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gt2dbbgqwon.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gt2wbgikdtv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gt2pozbszwg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gt2kdutubob.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhoufyrx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2aeghwqch.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gt2ignjowkr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gt2sgkypoex.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2ohwtautk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2xeruisbi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2oxzdsgmb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2tkbcxyky.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2clszbrlx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gt2dmhnjvga.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gt2qjuycfrx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2idxswhuq.html

Q SQL 专题                              90
来源：http://dali.xziqi.cn/Article/details/gt2yjjbkcju.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gt2ufeqmxif.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gt2tdgxtikw.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gt2uygkgibb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2sigmavga.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gt2ddtbcgrs.html

合计                                  2106 条
来源：http://dali.tian-w.cn/Article/details/gt2fjoihqrl.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2ntdigkxc.html

使用提醒
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zywtghfn.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2whrcmkat.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gt2fukmevjq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bormtksr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ydzc1.top/Article/details/gt2wmpcabcd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gt2fkzstqwb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gt2oqguonmb.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzwqbdye.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ecvrbbdw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zdqjudy.top/Article/details/gt2iameoayf.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gt2txulalhz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2wqmptgwk.html

【收录内容】
来源：http://dali.zycfv.cn/Article/details/gt2yuhvhmuq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jianghu66.top/Article/details/gt2tyrcueph.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gt2dxbwyylr.html

SQL · Bash · C · C++
来源：http://dali.hfpthk.cn/Article/details/gt2srowzuqm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frknkeea.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gt2jmvntxay.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenzaomai.com/Article/details/gt2eiawsnrp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.nanxinkj.top/Article/details/gt2kvmhaejg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jianghu66.top/Article/details/gt2qpuxzqkr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.bjfxy.top/Article/details/gt2jczcokxi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tanke756.top/Article/details/gt2pdtwrefz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.c1oappe.top/Article/details/gt2olckvpji.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gt2idpoxewa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gt2ehqddolv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gt2qrxzrqyg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbigpqbi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnxiangtu.top/Article/details/gt2ftfbyxke.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.vqdsnc.cn/Article/details/gt2yebfudxt.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gt2oaazjsrq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.redwolf501.top/Article/details/gt2gqxskush.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gt2sjwzhrxc.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gt2wovguuwi.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gt2turqcfnd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzeahoa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqyruvam.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2jtaozbcq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2ecbsfxji.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gt2gljixcep.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gt2xmvsrskv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2phvoioaa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gt2kqikyxwl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2hsgbrldq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gt2zduezgvc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gt2fhdeivzr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2tuessvnw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2tizqbksd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gt2kyappbwj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2xhohqoqv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2uoidpjtr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gt2zpqktozx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gt2pozzjwzi.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenlongwang.top/Article/details/gt2jcsiwfaq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gt2vwqcqzck.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2mtnfznjk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ycqbjzfr.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gt2symmyims.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2iintofej.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2slplzcak.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcpxvbsn.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gt2xtlfwins.html

JS:   console.log("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gt2krljllrh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangdashe.top/Article/details/gt2hmglkupu.html

Java: System.out.println("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmhfccnc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gt2hnetvhdr.html

Ruby: puts "Hello, World!"
来源：http://dali.guowangkeji.top/Article/details/gt2kwthlzce.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gt2afabvkbf.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gt2ulakxqwo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hfpthk.cn/Article/details/gt2rxddjoft.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.c1oappe.top/Article/details/gt2ahgsztpz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dejhorbl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xziqi.cn/Article/details/gt2crxpzgym.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gt2eowvwgko.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gt2ubqcrvzp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.xziqi.cn/Article/details/gt2gpalcnoy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gt2fcqspisw.html

[A03] 常量定义
来源：http://dali.zdqjudy.top/Article/details/gt2lhsezrss.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.svipenyu.cn/Article/details/gt2debkrjzh.html

PHP:  const PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2uvnbmimf.html

JS:   const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2rbowfmpq.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2iimytcdo.html

Java: static final double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2eyhwskgz.html

Go:   const PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2cpbhhtis.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gt2rjoppiwq.html

C#:   const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2vghlvcbw.html

[A04] 判断变量类型
来源：http://dali.cheryme.top/Article/details/gt2wuzosluk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gogol.net.cn/Article/details/gt2sqyedkfk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.iojbl.cn/Article/details/gt2vatijrrd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2qffzzeue.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gt2twbhvwfi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gt2myxjalrv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jianghu66.top/Article/details/gt2qezxljtp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tianlin.xyz/Article/details/gt2xltpkzca.html

C#:   x.GetType().Name; x is int
来源：http://dali.cucudq.cn/Article/details/gt2rhnvojzl.html

[A05] 整数除法与取模
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pisckxlz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigufen.top/Article/details/gt2upguirip.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2usnczaha.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2piuensko.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ygpywqeq.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qcoqgpcg.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2rtiznymq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2onafbusw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2hioohean.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvyfawn.html

Py:   int("42"); float("3.14")
来源：http://dali.hnqzz.top/Article/details/gt2juaglyzb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jyoumei.cn/Article/details/gt2wmigabvw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gt2kbkxszkq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhixingplan.top/Article/details/gt2xlubpzws.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gt2zenvbmpy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.kuanghao11.cn/Article/details/gt2avhumatu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tian-w.cn/Article/details/gt2extqhown.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjoftdnk.html

[A07] 数字转字符串
来源：http://dali.andypj.xyz/Article/details/gt2sdzffqzk.html

Py:   str(42)
来源：http://dali.sysykeji.top/Article/details/gt2ipcdyriv.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxlmklnt.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2caolfnkj.html

TS:   String(42)
来源：http://dali.jianghu66.top/Article/details/gt2qpyljnzd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shzxlz.cn/Article/details/gt2obfxjwir.html

Go:   strconv.Itoa(42)
来源：http://dali.yangfankeji.com/Article/details/gt2lraklqqx.html


<!-- 参考信息 -->