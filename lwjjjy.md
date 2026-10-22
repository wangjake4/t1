代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gtqbyvpzei.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrbaboie.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gtcvlhajyd.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gtmakoapsa.html

[U47] PHP：联合类型
来源：http://dali.cucudq.cn/Article/details/gtnesczcoo.html

int|string $id
来源：http://dali.sysykeji.top/Article/details/gtmetilzfw.html

[U48] PHP：纯枚举
来源：http://dali.guannengcc.top/Article/details/gtckhictee.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfarqqpqa.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gtzzqwbbxi.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtouhwvmeg.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gtgphavast.html

public function __construct(private int $id) {}
来源：http://dali.zhoulong.xyz/Article/details/gthdbsigle.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtpuqqarim.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gthazzlqsw.html

[U52] PHP：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtaeyiwefg.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigufen.top/Article/details/gtbamjlvvt.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtgdmcpnnu.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gtqqvttzjo.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gtxkgyvkfm.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtjcshiqys.html

[U55] PHP：match 表达式
来源：http://dali.gogol.net.cn/Article/details/gtumoxmlzf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gtqjlchxah.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gtdykalvtj.html

f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtqzrplyem.html

[U57] PHP：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtdvoblylu.html

"值: {$a}"
来源：http://dali.bjfxy.top/Article/details/gtualhkvyz.html

[U58] PHP：数组三件套
来源：http://dali.xziqi.cn/Article/details/gtqejuyvjs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtlpzhcxhj.html

[U59] PHP：自定义排序
来源：http://dali.bjfxy.top/Article/details/gttlsqxdkk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gthipnvxwc.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gtsnwuazgl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gtvphowlza.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gtdppdwcud.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtkjflbjcn.html

[U62] PHP：日期对象
来源：http://dali.vqdsnc.cn/Article/details/gtloowgqoa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gtzvfzusrf.html

[U63] PHP：文件读写
来源：http://dali.hongshengwenyu.top/Article/details/gtcngwaenl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgtlsfad.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gtcodvwols.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jqgfzy.top/Article/details/gtnmlotadv.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtlkfomgyp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hammf.cn/Article/details/gtuyiwebnb.html

[U66] PHP：设置 Cookie
来源：http://dali.cqqwz.cn/Article/details/gtvmfxmeob.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gtnrlvhmgj.html

[U67] PHP：处理文件上传
来源：http://dali.dashuyun.cn/Article/details/gtqwyxmght.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xinyue.icu/Article/details/gtwfhczprd.html

[U68] PHP：PDO 连接
来源：http://dali.hywenlv.cn/Article/details/gtknqvqoep.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtaobvteie.html

[U69] PHP：PDO 预处理
来源：http://dali.hfpthk.cn/Article/details/gtjyihvhyr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtanxufmqi.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258.top/Article/details/gtakxikhfh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nwbrower.top/Article/details/gtjzbjilux.html

[U71] PHP：抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtrgeibera.html

throw new RuntimeException("失败", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtfbdyoyio.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtdjlhfbzu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gtuwtyrjyn.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtofjwyjzx.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gtmsnzcvqi.html

[U74] PHP：读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtlkyqeuwf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.quarkkingdee.top/Article/details/gtzlygrhlw.html

[U75] PHP：依赖注入
来源：http://dali.jinqigufen.top/Article/details/gtuhjtpnhb.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gttngbvlep.html

[U76] PHP：简单路由
来源：http://dali.cucudq.cn/Article/details/gtpmuxxnvc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jlsjyb.cn/Article/details/gtbtkujhoc.html

[U77] PHP：模板渲染
来源：http://dali.hfpthk.cn/Article/details/gtknasjrgu.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtoafgmxdw.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtlgfxiovm.html

composer require --dev phpunit/phpunit
来源：http://dali.ivvv.top/Article/details/gtzhjvkltm.html

[U79] PHP：静态分析
来源：http://dali.yanxiufei.cn/Article/details/gtuacfhzra.html

composer require --dev phpstan/phpstan
来源：http://dali.chenzaomai.com/Article/details/gtnyilxtlz.html

[U80] PHP：代码规范修复
来源：http://dali.guannengcc.top/Article/details/gtdqktffbf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtaritxjgf.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtapmupwsx.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangtech.top/Article/details/gtggfnanaw.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gtwdzihxmt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbvbyfgt.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigufen.top/Article/details/gtcupsblqu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtzvmabnvo.html

[U84] JS：CommonJS 写法
来源：http://dali.jqgufenzy.top/Article/details/gtrcdgzuwc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gtidnfodgr.html

[U85] JS：可选链
来源：http://dali.hnxiangtu.top/Article/details/gtudabpjja.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gtnuvqygto.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtgombgkcj.html

a ?? b
来源：http://dali.xinyue.icu/Article/details/gtonluhxau.html

[U87] JS：解构默认值
来源：http://dali.birdmap.top/Article/details/gtipuzlwvm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.feifeiyinyue.top/Article/details/gtfbfrtena.html

[U88] JS：对象展开合并
来源：http://dali.shuidangran.top/Article/details/gtytfijosz.html

{ ...a, ...b }
来源：http://dali.ppjwa.cn/Article/details/gtadxdvlkz.html

[U89] JS：数组去重
来源：http://dali.mhx1999.top/Article/details/gttdwdxrzb.html

[...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtfpgrbjcv.html

[U90] JS：数字数组排序
来源：http://dali.zycfv.cn/Article/details/gtqwzzycuw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtvuryittn.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gttsrkbsxt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sysykeji.top/Article/details/gtjqgbvjbx.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gtqmmbdyrx.html

structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtwrworbbc.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtcjrogqsz.html

`共 ${n} 条`
来源：http://dali.quarkkingdee.top/Article/details/gtnexhijrt.html

[U94] JS：箭头函数
来源：http://dali.dashuyun.cn/Article/details/gtutchjsjh.html

const double = x => x * 2;
来源：http://dali.xylfe.cn/Article/details/gtvitretww.html

[U95] JS：Promise 包装
来源：http://dali.daxiang520.top/Article/details/gtjlzcknqg.html

new Promise((resolve, reject) => {})
来源：http://dali.cdnleiting.top/Article/details/gtswtkagxl.html

[U96] JS：async/await 与异常
来源：http://dali.smart0.xyz/Article/details/gtbiydmbrj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtbjditmrn.html

[U97] JS：并发请求
来源：http://dali.cheryme.top/Article/details/gtwnpnfstz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gthgpntthl.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gtjtojernm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gtjecvqjyc.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwspskyhn.html

el.addEventListener("click", e => {})
来源：http://dali.yongpay.top/Article/details/gtuazqxhcc.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtkiqiiyjt.html

document.querySelector(".item")
来源：http://dali.gzhubu.top/Article/details/gtjabbvyau.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gthzjexeph.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgypgbuxu.html

[U102] JS：本地存储
来源：http://dali.xuetiantiany.cn/Article/details/gtdzynbdeh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gtfemptlce.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyfjmmrq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gtmppkzhdu.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtgodzsslx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtyxlzbhfq.html

[U105] JS：节流
来源：http://dali.zhiwuduotai.top/Article/details/gtcrfjedtn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gtbtrlmepz.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtuqjujfmy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtwcmjoxln.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtvltgwnlz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtqumaakxu.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gtwnkyhygq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gttelofcuq.html

[U109] JS：数组分组
来源：http://dali.dashuyun.cn/Article/details/gtkmpipswr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtifvcvtqr.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gtygcxvfli.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhongyouzk.top/Article/details/gtndoywucu.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtzbjcsiof.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtktmldyas.html

[U112] JS：字符串补位
来源：http://dali.zhiwuduotai.top/Article/details/gtxdjdnwvm.html

"7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtaraklhgr.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gtlqsbdgdg.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjmkoddbh.html

[U114] JS：JSON 深比较
来源：http://dali.zhiwuduotai.top/Article/details/gtulkmocba.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtpgximdlr.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtjhfgrepd.html

crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtqwkdmtbg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.kuanghao11.cn/Article/details/gtcukvqymv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gtpgyufdzl.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gtkayuvqsa.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gtmqqvxthr.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gtezretsuo.html

npm i -D vite;  npx vite
来源：http://dali.jyoumei.cn/Article/details/gttqyffwxk.html

[U119] JS：生产构建
来源：http://dali.haohaochexian.top/Article/details/gtvibulrij.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gtnqklakrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shzxlz.cn/Article/details/gtqoqgkbsl.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gtsjtiivsr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvsqatpdl.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gtgytyqudw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtxxslrwbm.html

按语言统计（条）：
来源：http://dali.dianchejie.cn/Article/details/gtaqsnuxti.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtjxrkslcf.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gtpdwwpgzc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtcxylckea.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gtetdyttml.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gtqsogshxl.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpgzyngo.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtruhwjlmg.html

C# ............. 212
来源：http://dali.ivvv.top/Article/details/gtcddtdpvz.html

C .............. 30
来源：http://dali.hammf.cn/Article/details/gthzpiqkxy.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gtdbqbbhff.html

SQL ............ 90
来源：http://dali.cashguo.top/Article/details/gtsdfhiimx.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtjtuxaran.html

Kotlin ......... 15
来源：http://dali.birdmap.top/Article/details/gtpcukibwr.html

Swift .......... 15
来源：http://dali.zycfv.cn/Article/details/gtnuzgkyen.html

Lua ............ 10
来源：http://dali.ppjwa.cn/Article/details/gtpyuhpwhu.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtqmpndzsi.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtkunqtaig.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtykpnaofa.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gtbtrzkwwv.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gtoyfxyyce.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtktpsmehv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtuoekcind.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtzajkbohw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtnmeaxkae.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gtzpgmfryi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtpgsonvdn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtdgenfpeg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenzaomai.com/Article/details/gttlsphqpa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtaoupblag.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gtdbekuejx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sweek.top/Article/details/gtgrxwmgav.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtwfbxxegx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtcoyausav.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtluydyrur.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.daria6918.cn/Article/details/gtxxsmxtab.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtajenlusu.html

Q SQL 专题                              90
来源：http://dali.birdmap.top/Article/details/gtqwajityx.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gtodhndwkx.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gtwruqvwfj.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtoacyzfbj.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtnevcsfmu.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtdedmpxcy.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gtdoxrclrs.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtvfnvyomy.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtjibiivmr.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtnonfgtod.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jyoumei.cn/Article/details/gtnvuvzwpg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gtvfdhzxhd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gttxjgiyjo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ehwqpu.com/Article/details/gtdzjovxvg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gtsrioqfxs.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gtbfwwvktk.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtalfwnddn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hnxiangtu.top/Article/details/gtfvzhzwhn.html

Common Programming Examples Cheat Book
来源：http://dali.meibo888.top/Article/details/gtbkruefne.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcohbidmj.html

【收录内容】
来源：http://dali.tian-w.cn/Article/details/gtybluuriv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gtknuunlnq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sweek.top/Article/details/gtpbrwtmkl.html

SQL · Bash · C · C++
来源：http://dali.pycfn.com/Article/details/gteoqarjub.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.redwolf501.top/Article/details/gtvrhigvwa.html

【使用说明】
来源：http://dali.wangdashe.top/Article/details/gtxpbymtgy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtyjpgmvbo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cucudq.cn/Article/details/gtslhektda.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.redwolf501.top/Article/details/gtqajvegni.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gthadfqzhl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xuanzx.com/Article/details/gtvnpobvnj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.dashuyun.cn/Article/details/gtnehspmsn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hnxiangtu.top/Article/details/gtfqzbcjie.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gtjicnowhv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.kuanghao11.cn/Article/details/gtklqmqjqc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ivvv.top/Article/details/gtuousulqg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gtkkizcqmo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtpsahjdtr.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gttnbubgqv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinghuilouyu.cn/Article/details/gtkifcvapy.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtvjqlnixl.html

目  录
来源：http://dali.birdmap.top/Article/details/gtgsannsfd.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtmqyzzzki.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtokftztlx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtxycclukq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gticvxtqxe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtihjdhedq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gtwsodbebe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtejyisukt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gtdmrdxunv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gtwzeoispx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtzsvvbzei.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvjyiywh.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gtyepxhgds.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtxymhenmx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtznshmcjz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsjbxuht.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gtaybnpbqg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.9152youxi.cn/Article/details/gtxcwlmddc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daria6918.cn/Article/details/gtfryszcaf.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yangfankeji.com/Article/details/gtwcdtwryh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gtzkzqkiej.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtmedyuctf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtzgkegpzz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjxwamveb.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gteypevweg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtehwqiyqt.html

[A01] Hello World
来源：http://dali.yangfankeji.com/Article/details/gtcqjcslqe.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtssjajeyf.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gtwjnjtmbt.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqytnigg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gtymielgus.html

Java: System.out.println("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtysatkluy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtfvqnowmv.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gtgqldqpfs.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcptkswrg.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gttpcrfapu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.meibo888.top/Article/details/gtanefqiir.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtchpnwxkg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtmkifgjhn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenlongwang.top/Article/details/gtbmvdrcjb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtoahkzjbl.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gticcwmyck.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tian-w.cn/Article/details/gtfptlradx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtzhnijsup.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtmwrbpjdo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.mhx1999.top/Article/details/gtdymyeuug.html

PHP:  const PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtbbvzwidi.html

JS:   const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtjbnwdtco.html

TS:   const PI: number = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtyrkhwvos.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtzqmqtkfy.html

Go:   const PI = 3.14159
来源：http://dali.gogol.net.cn/Article/details/gtfblqevzg.html

Ruby: PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtmyjvhxik.html

C#:   const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtedwjsago.html

[A04] 判断变量类型
来源：http://dali.yuanzhike.top/Article/details/gtnsijkino.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtjxmzfggr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yonumen.top/Article/details/gtndgrjijb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shangyingyoupin.top/Article/details/gtrqvnqowp.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gttccapvnj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtwhvnmtqr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtrtghkxar.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nwbrower.top/Article/details/gtpqlecskp.html

C#:   x.GetType().Name; x is int
来源：http://dali.xuetiantiany.cn/Article/details/gtygcghtac.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtrxryuvxv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtldlislse.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtawqjwwpp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtqtqjihre.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtqaldkpoa.html


<!-- 参考信息 -->