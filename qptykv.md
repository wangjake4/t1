代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifwtcfvg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gt2bcaioxhi.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gt2wfnexmgi.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2shvnistm.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2rslviptt.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gt2rrzgakwy.html

[U58] PHP：数组三件套
来源：http://dali.birdmap.top/Article/details/gt2bxfxgaau.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2amqfgdce.html

[U59] PHP：自定义排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwchehtl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2cjrgdzwl.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gt2qbzustup.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gt2ypfkmwsm.html

[U61] PHP：正则
来源：http://dali.yuxming.cn/Article/details/gt2hqvpgicl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2dfdeipay.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gt2wijfqkxe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gt2kwaifqmw.html

[U63] PHP：文件读写
来源：http://dali.nwbrower.top/Article/details/gt2nhjtlzfd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gt2zeoqsakw.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gt2mojlpdeh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sxryk.cn/Article/details/gt2noncyzpc.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gt2kgzfakoq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2tawqtexy.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gt2ipqtfcsc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwvsfsje.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gt2gtjpgzfj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnxiangtu.top/Article/details/gt2bodzpxlc.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcgrpsxq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhoulong.xyz/Article/details/gt2atotfslg.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gt2xxjgxxkc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zdqjudy.top/Article/details/gt2nlvykkvg.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kctzwofx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gt2ettuvkzc.html

[U71] PHP：抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2yuitqxbr.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gt2itnbwqvk.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gt2kmgfqjoy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.svipenyu.cn/Article/details/gt2sovsgddy.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gt2lrejvtap.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gt2isphpeha.html

[U74] PHP：读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2ljidajew.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gt2gfxhkqry.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gt2lwqtfzfn.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gt2pywqejmr.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gt2epluqtan.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gt2cmutqadz.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gt2rbxarirl.html

composer require twig/twig
来源：http://dali.sufxvd.cn/Article/details/gt2vrhfznol.html

[U78] PHP：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2kodzwhnt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xalxpzpj.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gt2jfxdbldz.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gt2qhikgwbx.html

[U80] PHP：代码规范修复
来源：http://dali.ehwqpu.com/Article/details/gt2ubxhmuzx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gzhubu.top/Article/details/gt2irohfyvj.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gt2ztzpjtvn.html

npm init -y;  npm i express
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzoxztzz.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gt2vzfkdlpa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gt2fsqegsnq.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avdhratr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gt2lktxgmpw.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gt2lsqqbqml.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gt2vifvzaox.html

[U85] JS：可选链
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iebgsidv.html

a?.b?.c
来源：http://dali.sysykeji.top/Article/details/gt2arstsbtd.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gt2mnfgcxvb.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gt2ykmpswbx.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbkrihvb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nachyqrb.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gt2nalkokdr.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gt2qomcklko.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2xcplnejt.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2smbltkht.html

[U90] JS：数字数组排序
来源：http://dali.sxryk.cn/Article/details/gt2qalwmpnt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ptkqgzlr.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2picwyhhw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hammf.cn/Article/details/gt2ueklphxu.html

[U92] JS：深拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2fhklpecb.html

structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2pvzzqgdq.html

[U93] JS：模板字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2chbwwflg.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gt2ptfguvir.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfdpjpx.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gt2nemvolyp.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2boydbnld.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gt2zypqtftl.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clwyhgqk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2zhgryxec.html

[U97] JS：并发请求
来源：http://dali.hnxiangtu.top/Article/details/gt2lunrpplc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2wojudlfi.html

[U98] JS：fetch 带 JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2xsgkpiis.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxuanxn.top/Article/details/gt2utcbzrgb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzfkrot.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gt2kwjjgfdy.html

[U100] JS：DOM 查询
来源：http://dali.meibo888.top/Article/details/gt2wstctuwq.html

document.querySelector(".item")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hhivukns.html

[U101] JS：classList 操作
来源：http://dali.jiagoushi.top/Article/details/gt2vitvgzpz.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aimrcuyt.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrdzemot.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aorjuitg.html

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gt2bndivjsl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gt2pmtqzojo.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrpqzbva.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2usvewjjn.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqxsuoof.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258.top/Article/details/gt2ieefflcf.html

[U106] JS：日期格式化
来源：http://dali.cucudq.cn/Article/details/gt2jrcyvdei.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gt2ohsnecws.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gt2roeepwhv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gt2rahfvxfr.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gt2ixxdkvaw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gt2mhsfhrqp.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gt2kpktsdzv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gt2cfzbpntl.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gt2astzjsdb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gt2qvyopgtp.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmwrlvuz.html

new Map(Object.entries(obj))
来源：http://dali.cucudq.cn/Article/details/gt2leceigbl.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gt2fiykbgqw.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gt2ebazbgtg.html

[U113] JS：正则替换全部
来源：http://dali.nanxinkj.top/Article/details/gt2abnrycez.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coslggqk.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gt2wywhcbnf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2awmstiek.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2mrlkajqj.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2kvnqfvhe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gt2rbyvxaxr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gt2wnzdgmod.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gt2cowvubzn.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gt2brhuqzsv.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gt2lslrilnc.html

npm i -D vite;  npx vite
来源：http://dali.smart0.xyz/Article/details/gt2nkgogkkf.html

[U119] JS：生产构建
来源：http://dali.zhiwuduotai.top/Article/details/gt2kugezaut.html

npx vite build
来源：http://dali.daria6918.cn/Article/details/gt2jczqicnb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gt2qhpvtbkk.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gt2xeiqxnsk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2qayydqxc.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gt2netoirwe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ayuwxuim.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gt2mmgejdll.html

Python ......... 252
来源：http://dali.havefunace.top/Article/details/gt2selfssab.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gt2bclbgwfi.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knvwvbvi.html

TypeScript ..... 212
来源：http://dali.sysykeji.top/Article/details/gt2gymfevmp.html

Java ........... 212
来源：http://dali.yueranfly.top/Article/details/gt2zirrwauc.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2rmskjvcb.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gt2tkidmqxb.html

C# ............. 212
来源：http://dali.fengsongda.top/Article/details/gt2iaxfizvz.html

C .............. 30
来源：http://dali.jinqigfzy.top/Article/details/gt2qxdqrgag.html

C++ ............ 30
来源：http://dali.sxryk.cn/Article/details/gt2pxcwuzfi.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gt2brlebigr.html

Bash ........... 80
来源：http://dali.quarkkingdee.top/Article/details/gt2sdutbmlt.html

Kotlin ......... 15
来源：http://dali.cdnleiting.top/Article/details/gt2praciavo.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2pusksqrq.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gt2heimjhux.html

Perl ........... 10
来源：http://dali.jinqigfzy.top/Article/details/gt2cxrewtdc.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gt2ofyadzfa.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gt2mjktkilj.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gt2stkidugd.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gt2tkfepybx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gt2cydfitai.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xwugagoa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gt2sbchesko.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuanzhike.top/Article/details/gt2tjohbefh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gt2xasrrkmc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2ruqxmntb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2aaippcfm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gt2nfxvyopq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2tzrjouli.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2namqhrug.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2axzhpfxw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2ckvotwzw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2iciwuuzm.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gt2wzzcfwdk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gt2jdfksext.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2ivvssuyq.html

Q SQL 专题                              90
来源：http://dali.chenlongwang.top/Article/details/gt2mmxzzala.html

R Bash 专题                             80
来源：http://dali.yonumen.top/Article/details/gt2atjrtkou.html

S C / C++ 专题                          60
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvdxizoh.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtxdqtmr.html

U 高频实用片段                         120
来源：http://dali.yuxming.cn/Article/details/gt2iybcqzlt.html

------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2ntbziswh.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gt2xyggoxdn.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2dnxtypod.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gt2attpmctp.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2dpzqrhxg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dianchejie.cn/Article/details/gt2gdnkzfaw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dianchejie.cn/Article/details/gt2hobvpfmr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aibaodan.cn/Article/details/gt2drdzjnem.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenjidiqi.icu/Article/details/gt2suoqgpqg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.9152youxi.cn/Article/details/gt2aqsoeucs.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gt2peidaryo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhrfgvwt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xqivkqci.html

Common Programming Examples Cheat Book
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyqvzlvv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsrrtajs.html

【收录内容】
来源：http://dali.ehwqpu.com/Article/details/gt2bfiabanq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.pycfn.com/Article/details/gt2bsdwvpos.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2brefzeej.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gt2hxozirtm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zdqjudy.top/Article/details/gt2kvpwqjxa.html

【使用说明】
来源：http://dali.aizwys.cn/Article/details/gt2qlwfipdk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.redwolf501.top/Article/details/gt2supidoac.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gt2razelvnj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gt2pjzkxsdm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdtzcuxa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cheryme.top/Article/details/gt2kykbxxsq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukwftmyl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzqknwda.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gt2bvcqztgx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hywenlv.cn/Article/details/gt2xwlbpqoa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cdnleiting.top/Article/details/gt2lziekkau.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pycfn.com/Article/details/gt2kwgkjzft.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zdqjudy.top/Article/details/gt2uxwmuloi.html

【文件统计】
来源：http://dali.nwbrower.top/Article/details/gt2fplzgjfk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gt2vvzrstfe.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2ieboejsp.html

目  录
来源：http://dali.kuanghao11.cn/Article/details/gt2occzuhpx.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2wmwzsokt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gt2jptxakkw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2iqarqigs.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2goocsxsr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guowangkeji.top/Article/details/gt2jfqhbzcb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.c1oappe.top/Article/details/gt2xfchaggh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqkcfdcw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2vqyefdwz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2ninfzlqz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gt2olhfvtjn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2cejpfnit.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ilgpbpft.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2kvksimlg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2emswwzom.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2bfrvnqmk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gt2nxycocys.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwrxhtjl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ovjkgoaq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hammf.cn/Article/details/gt2yqzvfvou.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zjreckdr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gt2qvujtwlc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gt2pjlogdqc.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bbrjgwje.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gt2qqgnmeek.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pbvcnqkq.html

[A01] Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2rzjyzcpv.html

Py:   print("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gt2ofyqbmji.html

PHP:  echo "Hello, World!";
来源：http://dali.hywenlv.cn/Article/details/gt2wmsceybr.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2folgubvi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hywenlv.cn/Article/details/gt2gfqtkgzn.html

Java: System.out.println("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gt2kabxhbdv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gt2tmkieezu.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gt2hcydwkmi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2plqssebt.html

[A02] 变量声明与赋值
来源：http://dali.redwolf501.top/Article/details/gt2omejsjsl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gt2wgzaeqeu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2rbbyqrbb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2arhomgpe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.havefunace.top/Article/details/gt2ltvbbutc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gt2rbbrofdu.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigufen.top/Article/details/gt2cehazkhc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.wangdashe.top/Article/details/gt2sijvtzay.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2hhhvunnx.html

[A03] 常量定义
来源：http://dali.aibaodan.cn/Article/details/gt2hhcftrgi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.aibaodan.cn/Article/details/gt2orfaiziu.html

PHP:  const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vxworzxv.html

JS:   const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2hvqpmuxq.html

TS:   const PI: number = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2hapxbnke.html

Java: static final double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2yscrrrmq.html

Go:   const PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gt2pxlllqhd.html

Ruby: PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2kvfdickd.html

C#:   const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcvhbcyl.html

[A04] 判断变量类型
来源：http://dali.svipenyu.cn/Article/details/gt2ttqplwaq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gt2sqfvfrai.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gt2jcnfsijc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgufenzy.top/Article/details/gt2zbtqwjqs.html

TS:   typeof x; x instanceof Date
来源：http://dali.sysykeji.top/Article/details/gt2wfvwtmjf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shuidangran.top/Article/details/gt2bfnvpige.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ehwqpu.com/Article/details/gt2utptokgi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sysykeji.top/Article/details/gt2yvswahhu.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangdashe.top/Article/details/gt2dypispup.html

[A05] 整数除法与取模
来源：http://dali.hnqzz.top/Article/details/gt2gmgtvkrg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinqigufen.top/Article/details/gt2vxelumya.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2uihkvkaz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwobanqd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlwzarlk.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2utgyzbjp.html

Go:   7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2sgvsyner.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2hrqvzftw.html

C#:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gt2fxmiykyp.html

[A06] 字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2iryhksul.html

Py:   int("42"); float("3.14")
来源：http://dali.pycfn.com/Article/details/gt2ttotpiyz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gt2vmbaughv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gt2vypsajsx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmwnqvyk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gzhubu.top/Article/details/gt2xbwrooac.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigfzy.top/Article/details/gt2rewuyxsy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhoulong.xyz/Article/details/gt2bqdwmfbp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cheryme.top/Article/details/gt2lnyvnltd.html

[A07] 数字转字符串
来源：http://dali.c1oappe.top/Article/details/gt2qpefhxvm.html

Py:   str(42)
来源：http://dali.c1oappe.top/Article/details/gt2ivavtkxq.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gt2powkvypv.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2vrdfbmxh.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2gbphcdkp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gt2xcsxcido.html

Go:   strconv.Itoa(42)
来源：http://dali.gotoacloud.top/Article/details/gt2hlxcxvgy.html


<!-- 参考信息 -->