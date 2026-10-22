代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.tianlin.xyz/Article/details/gt2tgkokvgq.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gt2msqwcvba.html

[U54] PHP：空安全调用
来源：http://dali.dashuyun.cn/Article/details/gt2lrxpgybz.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gt2gijxqeac.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2mbclwktv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gt2zgzactbs.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gt2fajybkhg.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2dmcpadjg.html

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2asgwctko.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gt2tqmmjlgm.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gt2wvmjmafh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gt2covqjhqu.html

[U59] PHP：自定义排序
来源：http://dali.sufxvd.cn/Article/details/gt2qzmcthlu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2afsexsop.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gt2ngduqstz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2lnftnsji.html

[U61] PHP：正则
来源：http://dali.xinyue.icu/Article/details/gt2xjhgapmx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gt2qcbguirn.html

[U62] PHP：日期对象
来源：http://dali.fengsongda.top/Article/details/gt2vjpzegea.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gt2izfdahzt.html

[U63] PHP：文件读写
来源：http://dali.hysaishi.cn/Article/details/gt2fitspmui.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigufen.top/Article/details/gt2ydkovewj.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gt2mvjihhcp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjlzvlfn.html

[U65] PHP：会话
来源：http://dali.cucudq.cn/Article/details/gt2fsorwqbe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2nflslkhf.html

[U66] PHP：设置 Cookie
来源：http://dali.sxryk.cn/Article/details/gt2aylpxflq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtrutzb.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gt2jncxcjqp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gt2rsbakolh.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gt2uklwvena.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gt2pifuapvl.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gt2sefuyhhu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlgdnwqk.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpladdmd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gt2bmiielrz.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2dttttsth.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gt2ismwykth.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2axigytuo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gt2pyqzspbp.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvmcipbq.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gt2pswhsqua.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gt2exraufrn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gt2oqhoujjs.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gt2umekilhd.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gt2flwuawjd.html

[U76] PHP：简单路由
来源：http://dali.iojbl.cn/Article/details/gt2jzmemxyk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jiagoushi.top/Article/details/gt2xjclrcif.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gt2btzweojk.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gt2jpsjbulw.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2nmcfwblu.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gt2kxxdfdqi.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlysjojq.html

composer require --dev phpstan/phpstan
来源：http://dali.yvedp.cn/Article/details/gt2nfzfrnco.html

[U80] PHP：代码规范修复
来源：http://dali.9152youxi.cn/Article/details/gt2cdohkfii.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.mhx1999.top/Article/details/gt2oyvpnkxl.html

[U81] JS：初始化项目
来源：http://dali.zhengqikj.top/Article/details/gt2cfhfuogf.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gt2bfxzzqmp.html

[U82] JS：package.json 脚本
来源：http://dali.yongpay.top/Article/details/gt2fdaajvxh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlatmrjl.html

[U83] JS：ES Module 导入导出
来源：http://dali.c1oappe.top/Article/details/gt2oxvxtrrl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gt2hqxrdfxu.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gt2epitfjhs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yangfankeji.com/Article/details/gt2famgjeaw.html

[U85] JS：可选链
来源：http://dali.ppjwa.cn/Article/details/gt2hqswrarh.html

a?.b?.c
来源：http://dali.sufxvd.cn/Article/details/gt2vxnjhuia.html

[U86] JS：空值合并
来源：http://dali.fengsongda.top/Article/details/gt2xtunkmwo.html

a ?? b
来源：http://dali.ivvv.top/Article/details/gt2pgkwjwxg.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfusrgjx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yueranfly.top/Article/details/gt2kkhavgng.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2cggwxjda.html

{ ...a, ...b }
来源：http://dali.sufxvd.cn/Article/details/gt2wqyxnigf.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gt2mtsrsbki.html

[...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2amdacigs.html

[U90] JS：数字数组排序
来源：http://dali.tian-w.cn/Article/details/gt2rqeedwma.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ayzdjivg.html

[U91] JS：对象键值遍历
来源：http://dali.cdnleiting.top/Article/details/gt2nconpnut.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.svipenyu.cn/Article/details/gt2tbqsqjya.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gt2szepryvo.html

structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2onatzvix.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dhbrafll.html

`共 ${n} 条`
来源：http://dali.hnqzz.top/Article/details/gt2cgkdsipb.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efwfgnta.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gt2juczpict.html

[U95] JS：Promise 包装
来源：http://dali.ivvv.top/Article/details/gt2whwpqheh.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gt2aixpwjsc.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gt2qmaetuwu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2deuvasmd.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gt2cxsskdvv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gt2zuclfcoa.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2hdekteda.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hnxiangtu.top/Article/details/gt2khaidwws.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gt2aecsnjzh.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gt2ypwhnrwb.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiamiicr.html

document.querySelector(".item")
来源：http://dali.zhongyouzk.top/Article/details/gt2vyogiutb.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gt2kjczauyt.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gt2ozqqhedl.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gt2pobmeymf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.haohaochexian.top/Article/details/gt2aigdtlop.html

[U103] JS：定时器
来源：http://dali.nanxinkj.top/Article/details/gt2momkukpd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjlgfbud.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2sipgcqxc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2bjzajefd.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gt2ptbajpdg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sufxvd.cn/Article/details/gt2ckxltzjf.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwmclczh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gt2voclcxxb.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffilimfp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gt2dxttkheo.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gt2seafojjt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgvmougf.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gt2nykdkwzd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuanzx.com/Article/details/gt2jqisfhbu.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gt2ijsubzws.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gt2wxfeuopb.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gt2ffwiwiha.html

new Map(Object.entries(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cpcwkrge.html

[U112] JS：字符串补位
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynajdaul.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2ireakohq.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gt2mxclmjqy.html

s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2lcbsgiaf.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gt2mhrmxoce.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2xccmufqo.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gt2mlmuouar.html

crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2yhqeypqh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gt2tlmufffk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2yvvsqddm.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2sdovbwtl.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gt2fwzxdjzj.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gt2nsmotnvh.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gt2tjxnanut.html

[U119] JS：生产构建
来源：http://dali.sxryk.cn/Article/details/gt2hnbaiwhi.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gt2olnlwvlo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gt2xgmtfrxz.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2lpgjbfkv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2bhnavsse.html

统计汇总
来源：http://dali.cheryme.top/Article/details/gt2zdklkeci.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vniioyxr.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gt2rvxnnwgu.html

Python ......... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2fvbgwvqd.html

PHP ............ 252
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhcqedes.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gt2hstlqjrm.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gt2gyrunydc.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2bnhqyryf.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gt2pbsezivh.html

Ruby ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymnavpyq.html

C# ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2uicnafol.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gt2nnsyexgy.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gt2drebmxfo.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gt2jcvalzpw.html

Bash ........... 80
来源：http://dali.kuanghao11.cn/Article/details/gt2xxusywwy.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gt2gnosvcex.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aiyxxzbv.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gt2vjwbrkoy.html

Perl ........... 10
来源：http://dali.nwbrower.top/Article/details/gt2mjosblll.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gt2muaehqcj.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghhixxkz.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2hjqnfovl.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gt2tagcotjl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2lpdcvbyk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gt2bijvdked.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2fjilkukt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gt2rjniyghj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdusmo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2wpgtbawq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gt2bkfixpcp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gt2huftqkhy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2vwwhfype.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gt2zsrbzmbb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckkdkpym.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gt2feysjfpe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2fvklnmqn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.smart0.xyz/Article/details/gt2omcnnyjc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nwbrower.top/Article/details/gt2jrwwyybq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2hvbftugh.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gt2gokthsns.html

R Bash 专题                             80
来源：http://dali.smart0.xyz/Article/details/gt2valkltlz.html

S C / C++ 专题                          60
来源：http://dali.zhengqikj.top/Article/details/gt2prerridx.html

T 其他语言补充                          60
来源：http://dali.sweek.top/Article/details/gt2zbadrahj.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gt2mehvhlsd.html

------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2oufymoay.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gt2wcxzqihb.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gt2mcjubrbg.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gt2glldvozl.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2euombkbx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shzxlz.cn/Article/details/gt2habxqyeu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gt2ysizxcfg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.vqdsnc.cn/Article/details/gt2rnaabfzw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gt2gahpewqc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdfkxgzp.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gt2cggtovea.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2blucbdgk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guowangkeji.top/Article/details/gt2oalqwshp.html

Common Programming Examples Cheat Book
来源：http://dali.cheryme.top/Article/details/gt2rdpybtwf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pfgjeedu.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gt2jaxovsta.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuxming.cn/Article/details/gt2gecjbnjs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cheryme.top/Article/details/gt2lqvwsqdw.html

SQL · Bash · C · C++
来源：http://dali.hammf.cn/Article/details/gt2koqxejni.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.pycfn.com/Article/details/gt2sstupxoa.html

【使用说明】
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gevhgpsr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.birdmap.top/Article/details/gt2wwsdeveh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.iojbl.cn/Article/details/gt2jhszvywl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gt2qxdqlynd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gt2khjnutjy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jlsjyb.cn/Article/details/gt2fopyyiaq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xylfe.cn/Article/details/gt2jmpypuym.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ehwqpu.com/Article/details/gt2uruoivdk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmfdcwkq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sufxvd.cn/Article/details/gt2qwfvxdda.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ivvv.top/Article/details/gt2dyeglhhi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gt2rnlmpcpt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jyoumei.cn/Article/details/gt2yoenozhs.html

【文件统计】
来源：http://dali.nanxuanxn.top/Article/details/gt2xpnfktpz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gt2ipfbatsq.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gt2xguivnrf.html

目  录
来源：http://dali.guannengcc.top/Article/details/gt2hwrgwmyp.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2oxkhfwwm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gt2vaqzfjut.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsejbzw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gt2zbalilwo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gt2oaonisyz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hfpthk.cn/Article/details/gt2jeycpotj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.nanxinkj.top/Article/details/gt2bkdolwtr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gt2bacgaqmw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cqqwz.cn/Article/details/gt2ylbascgb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2brrgbfbk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2kbcjydzm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2ycocucdk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2wffhtjsd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ebugracc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gt2kxvxlqrn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.smart0.xyz/Article/details/gt2ktnkiync.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2braczkzn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ritccwhv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.meibo888.top/Article/details/gt2xcxcmjnw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lboqgmkk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gt2utzjfchs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpdjtfbw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2nbjcxsbw.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbyvmrwa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2eeuzceng.html

[A01] Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2voumrmjm.html

Py:   print("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gt2vvjynkcj.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gt2ivayjdig.html

JS:   console.log("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2yycawhue.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmluvmoo.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gt2kuzuhhni.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gt2efrrlybm.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gt2snwfylmw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gt2bmmaexpu.html

[A02] 变量声明与赋值
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdrqxxyi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gt2njtlzcpf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gt2xeaysalu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.snrcjt.cn/Article/details/gt2thiausyf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xladzdxe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gt2jgpnzwji.html

Go:   name := "Alex"; age := 20
来源：http://dali.yonumen.top/Article/details/gt2hdssasiw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.haohaochexian.top/Article/details/gt2cumjpuhx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yuanzhike.top/Article/details/gt2uqkfaopq.html

[A03] 常量定义
来源：http://dali.xinyue.icu/Article/details/gt2zlmpjgfp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gt2rkcrzdhs.html

PHP:  const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gt2pakmzkit.html

JS:   const PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2lwvsybgk.html

TS:   const PI: number = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2iblakmpy.html

Java: static final double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2mqlkpfep.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gt2qfvijwky.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2mpgeyefe.html

C#:   const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2lrhfcumo.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gt2ikkbqupe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gzhubu.top/Article/details/gt2xfqzctzu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pycfn.com/Article/details/gt2noegqpeg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhongyouzk.top/Article/details/gt2aaphhtsb.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gt2spvnlzfc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.feifeiyinyue.top/Article/details/gt2lutqrulk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shuidangran.top/Article/details/gt2dphzvpbf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gt2ememrkoc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gt2xlmlnnfq.html

[A05] 整数除法与取模
来源：http://dali.guannengcc.top/Article/details/gt2jgrcofwx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yj20258888.top/Article/details/gt2rqznwdff.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gt2mjpkczfl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2gtpznonj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gt2wekxmkeq.html

Java: 7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2yjumfibg.html

Go:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2nuhslzok.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2xosdrnpb.html

C#:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2cgbvszhn.html

[A06] 字符串转数字
来源：http://dali.yj20258.top/Article/details/gt2bdiyssve.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gt2uledeala.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ybcxt.top/Article/details/gt2jwsytxxg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yvedp.cn/Article/details/gt2tnsqbopl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2ptrxvbjg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2cexyvfcc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yangfankeji.com/Article/details/gt2ptqovnmw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yangfankeji.com/Article/details/gt2qdaqzapr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2enxrffvm.html

[A07] 数字转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2slupgcop.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rquoxmsg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aifbsxqu.html


<!-- 参考信息 -->