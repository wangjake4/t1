代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2xhvkvumg.html

"值: {$a}"
来源：http://dali.yueranfly.top/Article/details/gt2loisdyvf.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gt2pceitbba.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gt2jtwededj.html

[U59] PHP：自定义排序
来源：http://dali.hnxiangtu.top/Article/details/gt2uyqqfpex.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2ztmxeqqu.html

[U60] PHP：JSON 编解码
来源：http://dali.cashguo.top/Article/details/gt2ustphcnf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gt2cwbzqkpa.html

[U61] PHP：正则
来源：http://dali.yongpay.top/Article/details/gt2yeekwhnm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gt2aknpfsby.html

[U62] PHP：日期对象
来源：http://dali.meibo888.top/Article/details/gt2xjcgsbgt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gt2wvmzotqu.html

[U63] PHP：文件读写
来源：http://dali.iojbl.cn/Article/details/gt2ysssdiuf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gt2actwplfs.html

[U64] PHP：目录遍历
来源：http://dali.tanke756.top/Article/details/gt2zuwetjzn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aivtdyvm.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acdkpocv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2udqtekgx.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gt2fasxutte.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lnlcdoao.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gt2cxrbjijk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuxming.cn/Article/details/gt2neddvmej.html

[U68] PHP：PDO 连接
来源：http://dali.meibo888.top/Article/details/gt2dyjwgakr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gt2xyyopoqm.html

[U69] PHP：PDO 预处理
来源：http://dali.guowangkeji.top/Article/details/gt2mzndthxm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhiuqugw.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gt2gayxaupk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gt2ivvsnbid.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gt2oanwsczc.html

throw new RuntimeException("失败", 500);
来源：http://dali.316326.xyz/Article/details/gt2toollgjo.html

[U72] PHP：写错误日志
来源：http://dali.dashuyun.cn/Article/details/gt2tlpplbfa.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gt2qmaosxmt.html

[U73] PHP：读取 ini 配置
来源：http://dali.cqqwz.cn/Article/details/gt2jkkhvpju.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gt2ibzesjzz.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2lenylkqe.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gt2inhorgqc.html

[U75] PHP：依赖注入
来源：http://dali.svipenyu.cn/Article/details/gt2ecmxljzo.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gt2mruklasc.html

[U76] PHP：简单路由
来源：http://dali.yuanzhike.top/Article/details/gt2vizondbo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gt2bifeclsv.html

[U77] PHP：模板渲染
来源：http://dali.jinqigfzy.top/Article/details/gt2kbpmxiwr.html

composer require twig/twig
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvfwrnzx.html

[U78] PHP：单元测试
来源：http://dali.xuanzx.com/Article/details/gt2ydzuwhpy.html

composer require --dev phpunit/phpunit
来源：http://dali.xuanzx.com/Article/details/gt2kefttcil.html

[U79] PHP：静态分析
来源：http://dali.zhiwuduotai.top/Article/details/gt2wubfpelg.html

composer require --dev phpstan/phpstan
来源：http://dali.zycfv.cn/Article/details/gt2neqnrvaz.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gt2hckvnsig.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.vqdsnc.cn/Article/details/gt2onnqurdn.html

[U81] JS：初始化项目
来源：http://dali.zdqjudy.top/Article/details/gt2wvdzapdq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2azdmlasy.html

[U82] JS：package.json 脚本
来源：http://dali.sufxvd.cn/Article/details/gt2svlxenge.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daxiang520.top/Article/details/gt2apqjemtz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gt2okjhlifc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2utmfrmvs.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gt2srqgigps.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258888.top/Article/details/gt2knudunru.html

[U85] JS：可选链
来源：http://dali.yvedp.cn/Article/details/gt2mcwyhivq.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gt2dwrlvshp.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gt2pzjetbrd.html

a ?? b
来源：http://dali.dashuyun.cn/Article/details/gt2vnqdplmt.html

[U87] JS：解构默认值
来源：http://dali.aizwys.cn/Article/details/gt2pxruexqh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xylfe.cn/Article/details/gt2nbeysxys.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oixhokuj.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idpovrrj.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gt2paaxdbqc.html

[...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2sgmgreei.html

[U90] JS：数字数组排序
来源：http://dali.yueranfly.top/Article/details/gt2whkulbtz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2exihkffp.html

[U91] JS：对象键值遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2nouhmuud.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gt2fdhtdlvh.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2ahcvfncz.html

structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2hgtnpslr.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yakhomgx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgdoqem.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gt2saizohvk.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gt2rowzpncs.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgqhgvnv.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gt2lhyrwkjy.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gt2uzpbbwbh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2fgpffaig.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gt2vvgsfhat.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2donvfutz.html

[U98] JS：fetch 带 JSON
来源：http://dali.iojbl.cn/Article/details/gt2gkdqrawn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gt2qilrngcg.html

[U99] JS：事件监听
来源：http://dali.sxryk.cn/Article/details/gt2rgynufwy.html

el.addEventListener("click", e => {})
来源：http://dali.sysykeji.top/Article/details/gt2bcbrsvuq.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmhdhich.html

document.querySelector(".item")
来源：http://dali.9152youxi.cn/Article/details/gt2cqekuodg.html

[U101] JS：classList 操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsydinxw.html

el.classList.toggle("active")
来源：http://dali.hysaishi.cn/Article/details/gt2omzzidgn.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gt2huwkklzg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gt2anmmysfa.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gt2pbcmapfk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbdtwrkt.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gt2tkrernqu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2grlukpjp.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gt2gmndmonm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gt2qttjhytv.html

[U106] JS：日期格式化
来源：http://dali.sweek.top/Article/details/gt2qfpnqpml.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gt2xrxqcyrj.html

[U107] JS：数字千分位
来源：http://dali.mhx1999.top/Article/details/gt2rpkyurpc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gt2uxuhokge.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gt2ptiyqqkk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gt2omvltcsb.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gt2ncushikn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gt2iqnfzvhk.html

[U110] JS：数组分块
来源：http://dali.cdnleiting.top/Article/details/gt2qsrbutlb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gogol.net.cn/Article/details/gt2hwqzegqy.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2vtmvmmuz.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gt2fjdyrpjl.html

[U112] JS：字符串补位
来源：http://dali.tianlin.xyz/Article/details/gt2kuaqjmgt.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2dsbcnmdk.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gt2prrlrhtm.html

s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2bsnwllvh.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gt2guhrwuii.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sadmpcyw.html

[U115] JS：生成 UUID
来源：http://dali.jianghu66.top/Article/details/gt2zaaopeiy.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2bdhauvia.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyipeash.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigufen.top/Article/details/gt2uarrlppq.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gt2ntudtlcl.html

npm i -D vitest;  npx vitest
来源：http://dali.sxryk.cn/Article/details/gt2dlzolzhz.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gt2hdrpceer.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gt2jhdoebhq.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gt2draklldx.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gt2vfwvhafw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gt2ixwmhvze.html

import.meta.env.VITE_API_URL
来源：http://dali.wangdashe.top/Article/details/gt2ugexrklc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2haaxdqwt.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gt2bomdmkwp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lurlmcsw.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gt2rltjxjir.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gt2huhkmlks.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gt2xifejadx.html

JavaScript ..... 252
来源：http://dali.meibo888.top/Article/details/gt2uxhcdlal.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2wjcyzkbt.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2knxhmgsi.html

Go ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2quhitilb.html

Ruby ........... 212
来源：http://dali.gzhubu.top/Article/details/gt2gryqlmwf.html

C# ............. 212
来源：http://dali.redwolf501.top/Article/details/gt2fnmorjqj.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gt2vgdmarpw.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gt2kpfxoewa.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gt2hnowvrlt.html

Bash ........... 80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyssyqmk.html

Kotlin ......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2fewbmlbl.html

Swift .......... 15
来源：http://dali.yuxming.cn/Article/details/gt2bfrxphse.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gt2nwktzabd.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gt2ehjkswcp.html

Scala .......... 10
来源：http://dali.tian-w.cn/Article/details/gt2chqhhmuy.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gt2mqextpag.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gt2ynecmmtw.html

按章节统计：
来源：http://dali.shangyingyoupin.top/Article/details/gt2pblezywp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gt2ruoojrpk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gt2pelvdoov.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gt2glnarldn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2mlchadgs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gt2tdqtdktd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dianchejie.cn/Article/details/gt2temfygtc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gt2qvsuawit.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gt2lwcwhtut.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2mvdzrapc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gt2qhxsyxoh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2qagofkqe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cjswrxdo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2ogygbdbf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sufxvd.cn/Article/details/gt2qjgyrink.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgneihkt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2kvlihmsa.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gt2bpqbobpe.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gt2arpfszst.html

S C / C++ 专题                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erhypqfi.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gt2rjlejnra.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gt2ccbudzba.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqxsjlv.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2ykihjsqf.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2zcflgvsn.html

使用提醒
来源：http://dali.zhengqikj.top/Article/details/gt2hoxiztzg.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2zcjsyxkw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gt2edhrfvow.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnxiangtu.top/Article/details/gt2axlyxytx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gt2eaocllol.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuxming.cn/Article/details/gt2edlnrkld.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.9152youxi.cn/Article/details/gt2otjmxupv.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilwcdfsw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2vduwkxsu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pycfn.com/Article/details/gt2rfostesq.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gt2owmeuhsf.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2aycwxcxc.html

【收录内容】
来源：http://dali.redwolf501.top/Article/details/gt2lmvptyzf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guannengcc.top/Article/details/gt2rbufdadw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.smart0.xyz/Article/details/gt2iujnlkig.html

SQL · Bash · C · C++
来源：http://dali.yonumen.top/Article/details/gt2mahcjmlw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gt2afbjfwms.html

【使用说明】
来源：http://dali.cqqwz.cn/Article/details/gt2npncgdtt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guannengcc.top/Article/details/gt2fkzzdawl.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gt2xtstalpk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.svipenyu.cn/Article/details/gt2qeyniksl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gt2asyuslao.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gt2sullxwox.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tianlin.xyz/Article/details/gt2ghgwatdz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cucudq.cn/Article/details/gt2ypkuuiee.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xziqi.cn/Article/details/gt2ytsegunk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gt2qyhvkgwq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shuidangran.top/Article/details/gt2jrtityir.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.snrcjt.cn/Article/details/gt2ugrzwrxt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cashguo.top/Article/details/gt2dnaehivk.html

【文件统计】
来源：http://dali.shzxlz.cn/Article/details/gt2ymucldzi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.svipenyu.cn/Article/details/gt2rjwxvexn.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2rwcgmvxf.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebfszqrx.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gt2xxvxlldc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gt2nvcpleuu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gt2xiyxnlwv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2abjpjgvf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gt2tcscddhq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guannengcc.top/Article/details/gt2ufxqovjo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gt2wniovpsg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2hrmexkvy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyqxaicg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gt2nyvaskro.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hqrbrsvn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2zgxynxlz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2rpbqgpae.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2tecgohzk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xyuqsosc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gt2dflxhurk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gt2gtsdtfnw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jiagoushi.top/Article/details/gt2epgkmjqv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gt2irzjeqri.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daxiang520.top/Article/details/gt2yktzcfor.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2pfngvqpx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2kiyctftd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ogffzige.html

A. 基础语法与类型
来源：http://dali.gaohongyu789.top/Article/details/gt2ngaddxfs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2imeywcos.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2ldzndcvh.html

Py:   print("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gt2pjewpwqm.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258.top/Article/details/gt2kfhesmaj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etjqkypa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cqqwz.cn/Article/details/gt2zqieosyx.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gt2dpoikpos.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2kjbpkpfq.html

Ruby: puts "Hello, World!"
来源：http://dali.shuidangran.top/Article/details/gt2sbbhmyxc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gt2wxbblasd.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gt2feadajos.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gt2plufagrd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2fpbunbcy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gt2ovajuwpe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.birdmap.top/Article/details/gt2slcxbthq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gt2fzyttgnz.html

Go:   name := "Alex"; age := 20
来源：http://dali.snrcjt.cn/Article/details/gt2pmchpddw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.quarkkingdee.top/Article/details/gt2wskwdkvt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gt2ncsthaxx.html

[A03] 常量定义
来源：http://dali.havefunace.top/Article/details/gt2vzvaefls.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gt2hfqjxglg.html

PHP:  const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2dtfcqezy.html

JS:   const PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2vqsvuogp.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2wecsgvut.html

Java: static final double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2irygomcx.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gt2javlthmp.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gt2nedcdryz.html

C#:   const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdvkuckf.html

[A04] 判断变量类型
来源：http://dali.yangfankeji.com/Article/details/gt2qgaqgbhz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sysykeji.top/Article/details/gt2lnetounk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bezoikfm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gt2xajpagor.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2glhgwmyd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjlivgfb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gaohongyu789.top/Article/details/gt2funhuorq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hynvkohl.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gt2ducphqup.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzxqtnkd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gt2luikbtvp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2chzlffbb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2fgqqeolp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2pexiqouk.html

Java: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2tibzukya.html

Go:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2qjcusshe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2jvgftqfs.html

C#:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2dhlapcvk.html

[A06] 字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2pmahdyiw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvajwhts.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yvedp.cn/Article/details/gt2hfjkxzqu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hysaishi.cn/Article/details/gt2gtkesbfe.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sysykeji.top/Article/details/gt2cuqsodem.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2fwmgcjzp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tian-w.cn/Article/details/gt2ieuzwpsa.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhiwuduotai.top/Article/details/gt2covrwiuz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgfzy.top/Article/details/gt2ukgxdsxp.html

[A07] 数字转字符串
来源：http://dali.cucudq.cn/Article/details/gt2azuqctpl.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2ulcbyqll.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzqtbgca.html

JS:   String(42); (42).toString()
来源：http://dali.shuidangran.top/Article/details/gt2nwamfgzp.html

TS:   String(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqnqmcod.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daxiang520.top/Article/details/gt2ypvqlyas.html

Go:   strconv.Itoa(42)
来源：http://dali.nwbrower.top/Article/details/gt2ydzbqjgj.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gt2ymcvlgys.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gt2jkuqwyul.html

[A08] 取整与四舍五入
来源：http://dali.sysykeji.top/Article/details/gt2pgvctson.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2noqmgqjw.html


<!-- 参考信息 -->