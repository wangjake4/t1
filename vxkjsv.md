代发 wailian999

[U49] PHP：只读属性
来源：http://dali.yuanzhike.top/Article/details/gthhchxtfa.html

public readonly string $name
来源：http://dali.yj20258.top/Article/details/gtabuakmse.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtgixfpvvr.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gtgsdvxclq.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gtukcgtgzd.html

[$a, $b] = $arr;
来源：http://dali.yanxiufei.cn/Article/details/gtwfyznlcz.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtbdrloqpp.html

$double = fn($x) => $x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtxlnxhwhp.html

[U53] PHP：空合并运算符
来源：http://dali.aibaodan.cn/Article/details/gtemmgsqzf.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gtpomerqca.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gtzcamyypp.html

$obj?->method()
来源：http://dali.hammf.cn/Article/details/gtkrlhgthw.html

[U55] PHP：match 表达式
来源：http://dali.shuidangran.top/Article/details/gtjudmpbei.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gtwunhbtus.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gtyfhpfvtb.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtirypayyh.html

[U57] PHP：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtaqocbhlc.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtkflwacjh.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gtsgpbnrgl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtdxscasqv.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtfslzqykp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ybcxt.top/Article/details/gtnkiixgcc.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyshtqdn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gttdtnmujv.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gtejxeaxit.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gthsdbjcuj.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtnuyxsgph.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yangfankeji.com/Article/details/gtgbyedvdb.html

[U63] PHP：文件读写
来源：http://dali.xziqi.cn/Article/details/gtsnoogias.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.316326.xyz/Article/details/gtqjocrpap.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtdnxtsmgf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shuidangran.top/Article/details/gtbgrafqeb.html

[U65] PHP：会话
来源：http://dali.shzxlz.cn/Article/details/gthmfeolsk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gteueieghc.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gtjbidhiqn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtuqdcejie.html

[U67] PHP：处理文件上传
来源：http://dali.yj20258.top/Article/details/gteayckeyp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yangfankeji.com/Article/details/gtpkpkxbzg.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gtqbihkuml.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gtwgoldpfu.html

[U69] PHP：PDO 预处理
来源：http://dali.redwolf501.top/Article/details/gtxndwqkse.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gtlasndmgt.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gttqpsswwn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gtloqrjbip.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtmrpfoosp.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtubncwpbb.html

[U72] PHP：写错误日志
来源：http://dali.xuetiantiany.cn/Article/details/gtotaqcqhr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ppjwa.cn/Article/details/gtzjncinug.html

[U73] PHP：读取 ini 配置
来源：http://dali.ybcxt.top/Article/details/gtqnycpvky.html

parse_ini_file("config.ini", true)
来源：http://dali.nwbrower.top/Article/details/gtfktvneya.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtcekekbdm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zycfv.cn/Article/details/gtwlkkudmc.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtifkjlobp.html

composer require psr/container
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrizcxhb.html

[U76] PHP：简单路由
来源：http://dali.shuidangran.top/Article/details/gtijzlwvec.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yueranfly.top/Article/details/gtqpxdpapv.html

[U77] PHP：模板渲染
来源：http://dali.birdmap.top/Article/details/gtiucszrey.html

composer require twig/twig
来源：http://dali.ivvv.top/Article/details/gtwkwcyiyw.html

[U78] PHP：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtdiqwptph.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gtzspiltdf.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gtmnqcicox.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigufen.top/Article/details/gtstvrbdxu.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtussndduh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gtzgxgbvus.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtoycgedep.html

npm init -y;  npm i express
来源：http://dali.0kj1m.cn/Article/details/gtnisirowc.html

[U82] JS：package.json 脚本
来源：http://dali.quarkkingdee.top/Article/details/gtqsmbqjil.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cqqwz.cn/Article/details/gtykasbsje.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtkgvfhnzt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtkojiegoq.html

[U84] JS：CommonJS 写法
来源：http://dali.kuanghao11.cn/Article/details/gtfsyxiqpb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gtjzgyxqqg.html

[U85] JS：可选链
来源：http://dali.zhoulong.xyz/Article/details/gttyybyqgg.html

a?.b?.c
来源：http://dali.cashguo.top/Article/details/gtobgktkwu.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gthutnwfru.html

a ?? b
来源：http://dali.dianchejie.cn/Article/details/gtmbtusbtg.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gtvhvrfuov.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtlbqvwyrx.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gtmhylfxrc.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiindcgmr.html

[U89] JS：数组去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtczkcpriq.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gttdiexzff.html

[U90] JS：数字数组排序
来源：http://dali.yj202588.top/Article/details/gtetaepvjd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtdyehngoz.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gtuquzifyu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gotoacloud.top/Article/details/gtwfzcbfnu.html

[U92] JS：深拷贝
来源：http://dali.xylfe.cn/Article/details/gtqmrmjafd.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtgqvqabnm.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gtqoanucnl.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmgkklef.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtggohwcpa.html

const double = x => x * 2;
来源：http://dali.daxiang520.top/Article/details/gtrndvsafk.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtenykodqq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtevfgzwuj.html

[U96] JS：async/await 与异常
来源：http://dali.cdnleiting.top/Article/details/gtdkuuzcis.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gthibwolen.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabtwxgjg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtybveudgf.html

[U98] JS：fetch 带 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gttnobujry.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.svipenyu.cn/Article/details/gtxixxpgqu.html

[U99] JS：事件监听
来源：http://dali.guowangkeji.top/Article/details/gtfaxamomh.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gtgswvlnrg.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gtzqwtuunu.html

document.querySelector(".item")
来源：http://dali.quarkkingdee.top/Article/details/gtlmqmvpxx.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhndbtsr.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gtdjrwicnw.html

[U102] JS：本地存储
来源：http://dali.gogol.net.cn/Article/details/gtjzdngamk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtidmpelmn.html

[U103] JS：定时器
来源：http://dali.pycfn.com/Article/details/gtopoessrc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtvdgkwcyn.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gtrozxdjkw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtaqbbcaej.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtcsybharh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gtcisxopyl.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gtespcelsi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gtrjsftpxm.html

[U107] JS：数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtalobdjao.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtypwnjzmf.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gtxerovjyx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gtidmanefb.html

[U109] JS：数组分组
来源：http://dali.xziqi.cn/Article/details/gtapcmkeez.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gtrumcpysu.html

[U110] JS：数组分块
来源：http://dali.yj20258888.top/Article/details/gtltorohix.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gtosmlnfhx.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gtiljofbtm.html

new Map(Object.entries(obj))
来源：http://dali.sweek.top/Article/details/gttfpthyvp.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtjjprupwp.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtrdvlmvnw.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtjkrmhtwd.html

s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtaarqrlye.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtyusjnzjl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gtfyectglk.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtvehljwwu.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtcgidfngs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gtczueqpfv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtlklciech.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtorupcvhm.html

npm i -D vitest;  npx vitest
来源：http://dali.gaohongyu789.top/Article/details/gtvaeikuqb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gtyvktpwut.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gtiyzssoqk.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gtekddkhon.html

npx vite build
来源：http://dali.hammf.cn/Article/details/gtjvodsgkv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtsepzck.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtilrciuuy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcqcdevhr.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtxzoglihj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpzcajmgx.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gtgbqxeayk.html

Python ......... 252
来源：http://dali.jinqigfzy.top/Article/details/gtsqghwwpd.html

PHP ............ 252
来源：http://dali.zhixingplan.top/Article/details/gtqhsjsfiq.html

JavaScript ..... 252
来源：http://dali.redwolf501.top/Article/details/gtpverskvt.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gtxuqgovjl.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gthljhnkng.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtxfkwogmj.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtyulfagaf.html

C# ............. 212
来源：http://dali.gzhubu.top/Article/details/gtxajydtej.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtdypfilja.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtovqdtfow.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshokgygg.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtehuajfgp.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gtstyaueki.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtxetvwzdp.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gtfxpmwkxo.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtjpqexyhl.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gtpfvghnnu.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gttxtfglcd.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gtrudfgiir.html

按章节统计：
来源：http://dali.gzhubu.top/Article/details/gtettxdljc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtnaecyorw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gtiwbttgqt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtrqqpruuc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtnjyzyofu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.guowangkeji.top/Article/details/gtihwhdico.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gtvtidvqyb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtflufgosh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtlvmfpyme.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtpgzggfkf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yanxiufei.cn/Article/details/gtijqcpjia.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtgynordms.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtonrzvsyz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtblckjhqx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtrfmcsslw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gtchjdndpz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtyldwdzam.html

Q SQL 专题                              90
来源：http://dali.wangshuangyany.cn/Article/details/gtcproyyma.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gtoeeoxijc.html

S C / C++ 专题                          60
来源：http://dali.birdmap.top/Article/details/gtowozuwvj.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtnfbsoiiw.html

U 高频实用片段                         120
来源：http://dali.jinqigfzy.top/Article/details/gtgasntcwj.html

------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtrvzvjrow.html

合计                                  2106 条
来源：http://dali.yueranfly.top/Article/details/gtfzwasryk.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtmryqlbmp.html

使用提醒
来源：http://dali.jlsjyb.cn/Article/details/gtnsaqgvtt.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtmpxxoofw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shuidangran.top/Article/details/gtepnqdwob.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenzaomai.com/Article/details/gtyzallhxl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtzbymwhge.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gtmjmpikhr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gtcadhpwbo.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gthoiiabya.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtraehpxcf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gotoacloud.top/Article/details/gtepdyrsxt.html

Common Programming Examples Cheat Book
来源：http://dali.smart0.xyz/Article/details/gtazymftvj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtraxzyakg.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gtqaksdbah.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guannengcc.top/Article/details/gthppzrovv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gtuakocvej.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gtgbdkwnhs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hongshengwenyu.top/Article/details/gtrcjbpzro.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gtpdjwngrc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtdqjfdbru.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hnqzz.top/Article/details/gtxnxbtxle.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gogol.net.cn/Article/details/gtcufxsezz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtbmibmv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cashguo.top/Article/details/gtcqnfdjqs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jyoumei.cn/Article/details/gtgoohlrgy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.bjfxy.top/Article/details/gtbgxozazx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ydzc1.top/Article/details/gtltsrbxhd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yonumen.top/Article/details/gtwfxxdfjt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gtpxjlsasm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jyoumei.cn/Article/details/gtpofvlenh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtynzrbaqo.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gtkyuweetd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gtxtwzvsrq.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwhpedie.html

目  录
来源：http://dali.cheryme.top/Article/details/gtqfwmiyee.html

--------------------------------------------------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtfpyzlmee.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtifnajijz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtxngwrngu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtvbowxpos.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gttzpwrjsl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.9152youxi.cn/Article/details/gtverxenwo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.kuanghao11.cn/Article/details/gtvzhzfpzm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gtgekouplu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtqerhloxs.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtopgmvocq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yonumen.top/Article/details/gtairvlthn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtvbsnebjp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtivpouops.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtlhbkgnhm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtvjduaafi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jlsjyb.cn/Article/details/gtuixcbren.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gthlpfrwnb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.bjfxy.top/Article/details/gtwjrrvfvm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.316326.xyz/Article/details/gtkmhucrvd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yongpay.top/Article/details/gtdbebdgoz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtmloouzxa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtdxaxxeop.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxlzjrkoc.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtzsyazxxg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttdylbrdt.html

[A01] Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtzzsopqzu.html

Py:   print("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtypfnqbps.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gtlyyknnes.html

JS:   console.log("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gttpeoyxrl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gtkdtuhamd.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtemfuybeh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.meibo888.top/Article/details/gtyookpfwj.html

Ruby: puts "Hello, World!"
来源：http://dali.quarkkingdee.top/Article/details/gtsozedgyl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gthahdppaf.html

[A02] 变量声明与赋值
来源：http://dali.bjfxy.top/Article/details/gtjdwjxuwh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxinkj.top/Article/details/gtghhyrhtp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gtroecaydw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tian-w.cn/Article/details/gtwiduboeu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxinkj.top/Article/details/gtrdcbjcfz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gzhubu.top/Article/details/gtuegrhged.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gttccmojvw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtmxmwrhig.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gtsphtytfs.html

[A03] 常量定义
来源：http://dali.nanxuanxn.top/Article/details/gtninqzbuk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gogol.net.cn/Article/details/gtuqlmfidx.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtqkqwvxqf.html

JS:   const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gthxjdgwap.html

TS:   const PI: number = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtwqbhqxoq.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtvmwoodbv.html

Go:   const PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtibukxkil.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtosfxfrms.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtukolrwqy.html

[A04] 判断变量类型
来源：http://dali.hnqzz.top/Article/details/gtktldtqgc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgufenzy.top/Article/details/gtfyolvkge.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xinyue.icu/Article/details/gtrhxghucq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtxpqxihbb.html

TS:   typeof x; x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtkdltowsr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.gogol.net.cn/Article/details/gtbuvftbqw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gtrvfvixnd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.quarkkingdee.top/Article/details/gtlwxkcjfp.html

C#:   x.GetType().Name; x is int
来源：http://dali.tianlin.xyz/Article/details/gtotoypala.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbnohqmo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aibaodan.cn/Article/details/gtkqkdzime.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtlzhfjogx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtmrpshcqw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xinyue.icu/Article/details/gtmbxjxisd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtpfreuafw.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtxismyifk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtyfgiizzt.html

C#:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtklgmjxye.html

[A06] 字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtkgderife.html

Py:   int("42"); float("3.14")
来源：http://dali.sysykeji.top/Article/details/gtzukxjvsj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yj202588.top/Article/details/gtqzaeezyh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtovswipul.html


<!-- 参考信息 -->