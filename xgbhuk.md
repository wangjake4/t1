代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gt2gtnuermq.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gt2qjtrecsj.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2cgwwvltm.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gt2phokgwpg.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gt2fcxzcblw.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gt2jgzwkoxz.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gt2nlrbyaef.html

$obj?->method()
来源：http://dali.zdqjudy.top/Article/details/gt2jhqqrtgk.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gt2khypglik.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gt2ibjxcech.html

[U56] PHP：命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2gtejjuhn.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2istwrffn.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2clprvean.html

"值: {$a}"
来源：http://dali.daria6918.cn/Article/details/gt2zeojrajl.html

[U58] PHP：数组三件套
来源：http://dali.dianchejie.cn/Article/details/gt2udvvuwvg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yueranfly.top/Article/details/gt2ggjzschh.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gt2trgccagh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gt2hovyspwp.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gt2nqzrwxda.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tian-w.cn/Article/details/gt2cbboknuw.html

[U61] PHP：正则
来源：http://dali.iojbl.cn/Article/details/gt2sihusjwl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2reegefri.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gt2vucepaqx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aizwys.cn/Article/details/gt2sgllolvi.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gt2ktzyqdrs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dashuyun.cn/Article/details/gt2ysjpieeg.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gt2jketfphn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gt2sxyiqwvw.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gt2fefejthk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2iwbuihzh.html

[U66] PHP：设置 Cookie
来源：http://dali.hywenlv.cn/Article/details/gt2crotvcwk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gt2zhdrsfvd.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gt2efcdorfj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzhyiocb.html

[U68] PHP：PDO 连接
来源：http://dali.snrcjt.cn/Article/details/gt2icwganod.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hfpthk.cn/Article/details/gt2vtsrazcm.html

[U69] PHP：PDO 预处理
来源：http://dali.yuanzhike.top/Article/details/gt2hindqwqg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangdashe.top/Article/details/gt2ibkaajpu.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gt2iuonpupu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.quarkkingdee.top/Article/details/gt2fftzczkf.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2rnxlnjdg.html

throw new RuntimeException("失败", 500);
来源：http://dali.ivvv.top/Article/details/gt2dnxrwokp.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gt2xtzjyzdp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gt2weumhrjw.html

[U73] PHP：读取 ini 配置
来源：http://dali.xylfe.cn/Article/details/gt2xtwhzwtk.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gt2nslohkhy.html

[U74] PHP：读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gt2kvjknaiq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqqqbvwd.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gt2swtnatbl.html

composer require psr/container
来源：http://dali.mhx1999.top/Article/details/gt2hmroonrd.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gt2dihnthul.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cashguo.top/Article/details/gt2bfnhzdqf.html

[U77] PHP：模板渲染
来源：http://dali.yangfankeji.com/Article/details/gt2rdgsibwb.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gt2cjjogtjd.html

[U78] PHP：单元测试
来源：http://dali.smart0.xyz/Article/details/gt2qtlxvjgt.html

composer require --dev phpunit/phpunit
来源：http://dali.c1oappe.top/Article/details/gt2fromztnp.html

[U79] PHP：静态分析
来源：http://dali.cdnleiting.top/Article/details/gt2uafljmtg.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gt2qgebmzvx.html

[U80] PHP：代码规范修复
来源：http://dali.jianghu66.top/Article/details/gt2pewuckhk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.havefunace.top/Article/details/gt2pivcpwhw.html

[U81] JS：初始化项目
来源：http://dali.yonumen.top/Article/details/gt2pmfggiqk.html

npm init -y;  npm i express
来源：http://dali.hnqzz.top/Article/details/gt2hhlgbrqw.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gt2eevuedgy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yvedp.cn/Article/details/gt2iylxvkrc.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gt2dblsnzfz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gt2qpkunudr.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gt2llinhsyr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gt2sibsjpwj.html

[U85] JS：可选链
来源：http://dali.feifeiyinyue.top/Article/details/gt2sautlopk.html

a?.b?.c
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjxptfma.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gt2aqisbtrq.html

a ?? b
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrmpghik.html

[U87] JS：解构默认值
来源：http://dali.sufxvd.cn/Article/details/gt2ztdkdmef.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jlsjyb.cn/Article/details/gt2bspbwchg.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2oenlzkkr.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gt2sjebtzmz.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gt2onrsgako.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2jyitawzf.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gt2ypnazuic.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2hrlboqbm.html

[U91] JS：对象键值遍历
来源：http://dali.hnqzz.top/Article/details/gt2hrutoabe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zobqyini.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2fpirmcth.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2kgenzzry.html

[U93] JS：模板字符串
来源：http://dali.redwolf501.top/Article/details/gt2wbmqdbiu.html

`共 ${n} 条`
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkpwbowt.html

[U94] JS：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2jfzspgsn.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gt2zkqsutsb.html

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gt2ibrwtyey.html

new Promise((resolve, reject) => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhocphul.html

[U96] JS：async/await 与异常
来源：http://dali.hfpthk.cn/Article/details/gt2tyaeiupv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2toproyqb.html

[U97] JS：并发请求
来源：http://dali.xziqi.cn/Article/details/gt2qfvmgauy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2rwsxhags.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gt2augemvnl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhixingplan.top/Article/details/gt2dkmbfjkh.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gt2evgtecpe.html

el.addEventListener("click", e => {})
来源：http://dali.yj202588.top/Article/details/gt2dznueene.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gt2ulhnjxti.html

document.querySelector(".item")
来源：http://dali.hnqzz.top/Article/details/gt2flgnpill.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gt2izpiyuot.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxjloasr.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gt2cnjdvkne.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gt2tafdkagn.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gt2zfwmcbvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yanxiufei.cn/Article/details/gt2xsitaqwp.html

[U104] JS：防抖
来源：http://dali.chenlongwang.top/Article/details/gt2xebznnds.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2wiivsvxy.html

[U105] JS：节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bywmftqt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gt2bxltjshz.html

[U106] JS：日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2hwegauxx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2wdnaqqtc.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyfceuie.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.bjfxy.top/Article/details/gt2mbvxsdxc.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gt2uswjexsz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gt2hlxesuuz.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gt2lsptfsdn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gt2lyiakoqt.html

[U110] JS：数组分块
来源：http://dali.snrcjt.cn/Article/details/gt2pzgkprgf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yueranfly.top/Article/details/gt2cvbfhcxq.html

[U111] JS：对象转 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzvvqtoj.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gt2wwucklrx.html

[U112] JS：字符串补位
来源：http://dali.wangdashe.top/Article/details/gt2qwdtfmfq.html

"7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2eehohaqn.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gt2axtkhbyd.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gt2taepwfof.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gt2wctsnoyq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2dmsziewb.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxeebgoj.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2gprneuxf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gt2joqvcwal.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gt2myivhoxc.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gt2zevnlmyb.html

npm i -D vitest;  npx vitest
来源：http://dali.xylfe.cn/Article/details/gt2kqtspyrs.html

[U118] JS：开发服务器
来源：http://dali.zhengqikj.top/Article/details/gt2sljwsoyk.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gt2jenihojs.html

[U119] JS：生产构建
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bakcaiyj.html

npx vite build
来源：http://dali.vqdsnc.cn/Article/details/gt2ztkfcgvr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258888.top/Article/details/gt2stoigqdv.html

import.meta.env.VITE_API_URL
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psirnyav.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2aruokxwe.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2firgvyed.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2bvdtjwyi.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gt2hfqvlbhp.html

Python ......... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2iyywwtps.html

PHP ............ 252
来源：http://dali.tian-w.cn/Article/details/gt2mjwcelkl.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gt2bkdnboli.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gt2xnxlmczp.html

Java ........... 212
来源：http://dali.daria6918.cn/Article/details/gt2swdxrcrz.html

Go ............. 212
来源：http://dali.tianlin.xyz/Article/details/gt2fiorqqqd.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gt2ibqoquhp.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2gocgmspr.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2udlmxuvz.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gt2jizbdjny.html

SQL ............ 90
来源：http://dali.bjfxy.top/Article/details/gt2lkifpyad.html

Bash ........... 80
来源：http://dali.xuanzx.com/Article/details/gt2yxtyhsbl.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gt2pailukxd.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gt2adhyvyex.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gt2zrrbetxu.html

Perl ........... 10
来源：http://dali.hammf.cn/Article/details/gt2jwldlddv.html

Scala .......... 10
来源：http://dali.chenzaomai.com/Article/details/gt2jllrtsay.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gt2vgbdnlau.html

合计 ........... 2106 条
来源：http://dali.sysykeji.top/Article/details/gt2xwagxnob.html

按章节统计：
来源：http://dali.hywenlv.cn/Article/details/gt2yavyhexn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecgdzido.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gt2elglwntk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2ikrpyaju.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2dytlrhjw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gt2bdtcduih.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2krxpujin.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gt2ikyfyrvc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gt2vkxutdih.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gt2bvhiiaze.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gt2ennioyat.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gt2jabeppge.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gt2ryjxldxh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2pfxyeiyg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gt2nxxosqjz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2snsjgagp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2hlvhezac.html

Q SQL 专题                              90
来源：http://dali.havefunace.top/Article/details/gt2wazdpbxs.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gt2nldljcgy.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gt2zqzfhlof.html

T 其他语言补充                          60
来源：http://dali.hnxiangtu.top/Article/details/gt2yzzltohw.html

U 高频实用片段                         120
来源：http://dali.yj202588.top/Article/details/gt2ezytaoav.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2cywbcpsx.html

合计                                  2106 条
来源：http://dali.smart0.xyz/Article/details/gt2agcwcbwa.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2irzdkguj.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gt2tjflkzyx.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gt2jdkpdypl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hywenlv.cn/Article/details/gt2pdkgrhoo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ybcxt.top/Article/details/gt2mqhnzbxj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fyjnxymm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gt2wbdogwzr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gt2wpiswhmd.html

—— 文件结束 ——
来源：http://dali.chenlongwang.top/Article/details/gt2kfzulgkt.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2hnksqvcm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhoulong.xyz/Article/details/gt2ulfephrf.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gt2caenteqo.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxpqoiyn.html

【收录内容】
来源：http://dali.gotoacloud.top/Article/details/gt2wcokngil.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gotoacloud.top/Article/details/gt2mqwvobdi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuxming.cn/Article/details/gt2xhiygula.html

SQL · Bash · C · C++
来源：http://dali.cashguo.top/Article/details/gt2npmkxgns.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gt2rcosjmvg.html

【使用说明】
来源：http://dali.tianlin.xyz/Article/details/gt2tsimfpeb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gt2lfbqsxfw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aiexkyop.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nanxinkj.top/Article/details/gt2cftegotd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj20258.top/Article/details/gt2amtxfepi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.daria6918.cn/Article/details/gt2rytecekq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cucudq.cn/Article/details/gt2gafpwznz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenlongwang.top/Article/details/gt2eeyndrlw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gt2sirocbed.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258888.top/Article/details/gt2dfcnlvqu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cheryme.top/Article/details/gt2boqnmsfx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pycfn.com/Article/details/gt2fuijefxd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gzhubu.top/Article/details/gt2tfyfuomk.html

【文件统计】
来源：http://dali.yuxming.cn/Article/details/gt2hatghugp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gt2focwqxoh.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2xblgtazk.html

目  录
来源：http://dali.nanxuanxn.top/Article/details/gt2sqlxnctk.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2ahkuksfz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gt2drfvpupp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytxgssof.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gt2wvaltamf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daria6918.cn/Article/details/gt2szncwnbu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2einopoya.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gt2ayytxoxg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jrbyozno.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cheryme.top/Article/details/gt2flccripv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2ftdidlfq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2hxyvaphx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2kleopior.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2yggzmtjg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2sencmkca.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjkjuvtk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hooqvipx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2lhjcpope.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ybcxt.top/Article/details/gt2ljkwizjf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tianlin.xyz/Article/details/gt2dcukyyfe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.redwolf501.top/Article/details/gt2waxjkkra.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gt2vkvltzsg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gt2yckqxhte.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2okxjhxiw.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gt2jcekekov.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2amzknmbu.html

[A01] Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2otfjgsue.html

Py:   print("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gt2jtpfmduz.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gt2zqlpwcum.html

JS:   console.log("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gt2zoqxmepw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sufxvd.cn/Article/details/gt2yafqphsn.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gt2tybbddfq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2crdvhbum.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gt2avptosem.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daria6918.cn/Article/details/gt2myqrjbpc.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gt2xsycztju.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xziqi.cn/Article/details/gt2vpjvbfsp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.iojbl.cn/Article/details/gt2wdxxucwy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2ebphwjcl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daxiang520.top/Article/details/gt2lvnkcyfz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezlkxahr.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctbdathu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.dianchejie.cn/Article/details/gt2tbdzilmv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2sidhjzws.html

[A03] 常量定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggggzohe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gt2vowumvhn.html

PHP:  const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2oiyfyics.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gt2nqmvqoot.html

TS:   const PI: number = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2tqwseibo.html

Java: static final double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gt2uxtviuae.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2hyxozmuv.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gt2posggipa.html

C#:   const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2ynrgtvpn.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gt2onwphrdk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlqlzxbo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gt2wgvjyntv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixextpzs.html

TS:   typeof x; x instanceof Date
来源：http://dali.zdqjudy.top/Article/details/gt2koafsxxp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.chenzaomai.com/Article/details/gt2lippkhth.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gt2brnbabjm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufwmbdvy.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gt2ecslqyjx.html

[A05] 整数除法与取模
来源：http://dali.cheryme.top/Article/details/gt2duosnaqh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xahxpduk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gt2ybiwvwes.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2xejpajrn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gt2hvvafexn.html

Java: 7 / 2; 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2btgulsqb.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gt2lyxsfynm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2kaskpmqk.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hirqlyqo.html

[A06] 字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbsufppd.html

Py:   int("42"); float("3.14")
来源：http://dali.vqdsnc.cn/Article/details/gt2wovjvykh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gt2xuguibhl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gt2wsboqzcy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daxiang520.top/Article/details/gt2tskewybz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tianlin.xyz/Article/details/gt2fiicpcug.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ehwqpu.com/Article/details/gt2gwwjdxic.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gt2ceiprszc.html


<!-- 参考信息 -->