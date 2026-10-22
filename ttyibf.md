代发 wailian999

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gtxdjqdhwr.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtgpgknovr.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtfswbhmts.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtlldqsewu.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtqgwmilzm.html

$v = $a ?? $b ?? "default";
来源：http://dali.aizwys.cn/Article/details/gtqsretyer.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gtpelmghbq.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gtzntdctmn.html

[U55] PHP：match 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtybptohan.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gtpmtojwbo.html

[U56] PHP：命名参数
来源：http://dali.hysaishi.cn/Article/details/gttfdahkwh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gturnkjoxw.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gthoyborlq.html

"值: {$a}"
来源：http://dali.0kj1m.cn/Article/details/gtosufskvv.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtzpqxhvfo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtlatgpmon.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gtsudoqxfg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtdrayqgcj.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gtsthqhtcr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtipmhnokd.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gttgldgndf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtnmejsodm.html

[U62] PHP：日期对象
来源：http://dali.yonumen.top/Article/details/gtanobfpuf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guowangkeji.top/Article/details/gtqdqpofhp.html

[U63] PHP：文件读写
来源：http://dali.daxiang520.top/Article/details/gtpwpgkrmp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gtslzxjsix.html

[U64] PHP：目录遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtdbkudnya.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gtdgyysgji.html

[U65] PHP：会话
来源：http://dali.hywenlv.cn/Article/details/gtsswzuftn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtihiegbou.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gtcuivscma.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jianghu66.top/Article/details/gtoadlrmpu.html

[U67] PHP：处理文件上传
来源：http://dali.chenlongwang.top/Article/details/gtfdjbuwmu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuanzx.com/Article/details/gtnneggrhd.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gtdpfdyjqq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gtymtgdigb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyqnpymq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gtlcfunbpm.html

[U70] PHP：PDO 事务
来源：http://dali.nwbrower.top/Article/details/gtxihpqvds.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gtwnrkmkxo.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuusztqyf.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtumogamrm.html

[U72] PHP：写错误日志
来源：http://dali.hongshengwenyu.top/Article/details/gteudnooiu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gtvxdgxjsz.html

[U73] PHP：读取 ini 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibhemcmg.html

parse_ini_file("config.ini", true)
来源：http://dali.hnxiangtu.top/Article/details/gtnkxanfyp.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gttnffxiax.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jiagoushi.top/Article/details/gtwddpyuag.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtsslrrhqd.html

composer require psr/container
来源：http://dali.quarkkingdee.top/Article/details/gthmizwipn.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbfwdxfd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.birdmap.top/Article/details/gtohwkpdnu.html

[U77] PHP：模板渲染
来源：http://dali.0kj1m.cn/Article/details/gtidberpyq.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gtntjqaurz.html

[U78] PHP：单元测试
来源：http://dali.wangdashe.top/Article/details/gtzfubaeef.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gtidusbemc.html

[U79] PHP：静态分析
来源：http://dali.meibo888.top/Article/details/gtgkeuqtbp.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gtvibanzng.html

[U80] PHP：代码规范修复
来源：http://dali.hfpthk.cn/Article/details/gtnooefwze.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gtzseuwrpv.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gtgkiauqjy.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsexfmhl.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gtbnxiqepc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daria6918.cn/Article/details/gtjjgwkbea.html

[U83] JS：ES Module 导入导出
来源：http://dali.fzhhl.top/Article/details/gtcpxmsoxx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtrsrgzuam.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtkjplkdjy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jlsjyb.cn/Article/details/gtyykiwcxq.html

[U85] JS：可选链
来源：http://dali.guowangkeji.top/Article/details/gtituoxqzs.html

a?.b?.c
来源：http://dali.hnqzz.top/Article/details/gtkzwmkods.html

[U86] JS：空值合并
来源：http://dali.guannengcc.top/Article/details/gteebaqmbs.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gtrjlvgwhp.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gtkicgheqz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gttjbvixwv.html

[U88] JS：对象展开合并
来源：http://dali.svipenyu.cn/Article/details/gtyosloxpi.html

{ ...a, ...b }
来源：http://dali.jqgufenzy.top/Article/details/gtpbtyumhe.html

[U89] JS：数组去重
来源：http://dali.andypj.xyz/Article/details/gtzfqqqgiv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtvhgblele.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtjumpmgym.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtecfwbibl.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtoiroprwb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cashguo.top/Article/details/gtoogmbalm.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gtjizdgtjx.html

structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtuhvbnmdx.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gtysabozti.html

`共 ${n} 条`
来源：http://dali.wangdashe.top/Article/details/gtjrrdxizp.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gtnvgojudh.html

const double = x => x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtchzkdnco.html

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gtvsgyvetp.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gtlbvuvdsa.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtaezwlkwg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtsfsazljf.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gtslygifud.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtaofulqmr.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gtmrescrmt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zdqjudy.top/Article/details/gtouyqyaun.html

[U99] JS：事件监听
来源：http://dali.yangfankeji.com/Article/details/gtyuprmlkk.html

el.addEventListener("click", e => {})
来源：http://dali.guowangkeji.top/Article/details/gthzbcxiyj.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gtwqpbidgl.html

document.querySelector(".item")
来源：http://dali.cqqwz.cn/Article/details/gtqxqgczkn.html

[U101] JS：classList 操作
来源：http://dali.pycfn.com/Article/details/gthtglgnlm.html

el.classList.toggle("active")
来源：http://dali.hnxiangtu.top/Article/details/gtjgsimoya.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gtyyzjrcop.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hongshengwenyu.top/Article/details/gtbikrkkuv.html

[U103] JS：定时器
来源：http://dali.fengsongda.top/Article/details/gtywkrcgbb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gthcmamyyn.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gtsuzzsuhl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtxzjsclzs.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gtoqogogjv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhixingplan.top/Article/details/gtaarcugis.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gtyjzdbguh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.iojbl.cn/Article/details/gtgxbxijuf.html

[U107] JS：数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtliikyerq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtmptxahbs.html

[U108] JS：随机整数
来源：http://dali.hnqzz.top/Article/details/gtzwzdvypt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.9152youxi.cn/Article/details/gttdztahsn.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gtgdcgtsxn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtfkuzvzzl.html

[U110] JS：数组分块
来源：http://dali.bjfxy.top/Article/details/gtnpqyplma.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gtzemwtawj.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtesfgymsw.html

new Map(Object.entries(obj))
来源：http://dali.gotoacloud.top/Article/details/gtmqycufsd.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtwehwcbac.html

"7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtsoienyeb.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtaamwxurc.html

s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtrerhfmnh.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtiyppswun.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtpibenlsh.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gttshatcmx.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynxeorxh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtwrumgqck.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqraxsnqe.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtvxwrovpa.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gtxggnvvpo.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtepzcnttf.html

npm i -D vite;  npx vite
来源：http://dali.shzxlz.cn/Article/details/gtneldhuzq.html

[U119] JS：生产构建
来源：http://dali.yanxiufei.cn/Article/details/gthtejmdhq.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtirqueeis.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtbdiynenq.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gteqrbwkjx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtakjqfzsj.html

统计汇总
来源：http://dali.cashguo.top/Article/details/gtppkrhaus.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrpzljcps.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gtjkggabtn.html

Python ......... 252
来源：http://dali.xuanzx.com/Article/details/gtgzsmtbrs.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gtewfkthux.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbygfsdpa.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gtezllrldm.html

Java ........... 212
来源：http://dali.yuanzhike.top/Article/details/gtlpmfgudw.html

Go ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gtdnhmqyug.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gtkxwnmrxp.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gtffmhavbn.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gtgvxdifkq.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gtwakrutda.html

SQL ............ 90
来源：http://dali.tian-w.cn/Article/details/gtxgvpvhqo.html

Bash ........... 80
来源：http://dali.ehwqpu.com/Article/details/gtjiitoxhw.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuqmjbua.html

Swift .......... 15
来源：http://dali.gotoacloud.top/Article/details/gtjapnkjzt.html

Lua ............ 10
来源：http://dali.0kj1m.cn/Article/details/gthlambxlk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gtfmlbdtvr.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gtaaahfzjz.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtezdbbrop.html

合计 ........... 2106 条
来源：http://dali.sxryk.cn/Article/details/gtsrxhalll.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gtjvfxdtts.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yueranfly.top/Article/details/gttbiakbjg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtynkawqfx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtnndtqxwh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtdewztpqk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gtfjbdebyp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtfgikhgma.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gtlbrhnuxl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shangyingyoupin.top/Article/details/gtwkmenxft.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtjyizvojl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtezxoewvi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtxhylncdg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gticspmlrk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtkorinwar.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtnujnryiu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gtbyxydjwp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gttrikrlks.html

Q SQL 专题                              90
来源：http://dali.c1oappe.top/Article/details/gttezsorwf.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxauwgwlg.html

S C / C++ 专题                          60
来源：http://dali.gzhubu.top/Article/details/gtlxhhbjlo.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gtosvkkzym.html

U 高频实用片段                         120
来源：http://dali.yueranfly.top/Article/details/gtbczoyfse.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtcwlrqkdc.html

合计                                  2106 条
来源：http://dali.cashguo.top/Article/details/gtqsbyjjax.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtgkllgjtd.html

使用提醒
来源：http://dali.daxiang520.top/Article/details/gtnfdrcxbu.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtheqnblpn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtngzoetar.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ehwqpu.com/Article/details/gtaqnrbucp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtwrkuawpc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfjseldg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gtdwpgxmld.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gtnutqttjd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqvqquuyw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzylbrzn.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gtukreyygu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsrsvezdx.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gtzumevszk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gtjurcuuiy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gaohongyu789.top/Article/details/gticvjllqo.html

SQL · Bash · C · C++
来源：http://dali.bjfxy.top/Article/details/gthecbbpop.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gthgylkxao.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gtwfeusdcs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xylfe.cn/Article/details/gtmemjtgui.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtbbigzgtu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gttalwzwad.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtjzhrossf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gtdywdhnxy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.meibo888.top/Article/details/gtcnfuprco.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtzsggjztm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gttskankao.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xylfe.cn/Article/details/gtvmzgpzwu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtecssucsh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhixingplan.top/Article/details/gtqyzgucyi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shuidangran.top/Article/details/gtbybduljp.html

【文件统计】
来源：http://dali.yj20258888.top/Article/details/gtpvtpisgf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbokkflje.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtybhfloiv.html

目  录
来源：http://dali.zycfv.cn/Article/details/gtywrlovja.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtwuntqieu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtkkdxtayd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtegkxtaik.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtvxgmweko.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gtkawzvumx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ehwqpu.com/Article/details/gtlbkhtyyd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtcryevffg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlavqokzf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtfduvxpys.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtmdphdypo.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xuanzx.com/Article/details/gtynborzzk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbbbfgvx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtkefdgooj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtmrrlsyrv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtnxxkeipu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xuanzx.com/Article/details/gtwefnigil.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtjhxtvcqg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gtpfqzxqut.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xylfe.cn/Article/details/gtkpyvssbk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gtcqlytxyz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtevfkkpif.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtwayjmvef.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthihnfhmi.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gtzkuiywzi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxwfhfgrc.html

[A01] Hello World
来源：http://dali.meibo888.top/Article/details/gthjqtyhfn.html

Py:   print("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtleqldnab.html

PHP:  echo "Hello, World!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfwnilix.html

JS:   console.log("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtwcyaiyon.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdpznceg.html

Java: System.out.println("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtgdwdjxku.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtdgmayzue.html

Ruby: puts "Hello, World!"
来源：http://dali.nwbrower.top/Article/details/gtlnavxouj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzkhlrgi.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtmcjyjzdd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhuvgwjt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtjmgetyhd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guannengcc.top/Article/details/gtnnifmtay.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtfdkitdih.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtyilncreo.html

Go:   name := "Alex"; age := 20
来源：http://dali.jyoumei.cn/Article/details/gtezlsxlyx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.0kj1m.cn/Article/details/gtimutmysw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gttmicpbcg.html

[A03] 常量定义
来源：http://dali.ybcxt.top/Article/details/gtfdbfnfpw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhongyouzk.top/Article/details/gtkvcltunp.html

PHP:  const PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtonnpdzmr.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpglbssxy.html

TS:   const PI: number = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtudlxfnol.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtmhhkosvh.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gthbkrrrhb.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtkmfmggtn.html

C#:   const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtegdvvwgz.html

[A04] 判断变量类型
来源：http://dali.xuanzx.com/Article/details/gtqtwrjyax.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jyoumei.cn/Article/details/gtxgbgakmr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sweek.top/Article/details/gtldtbyrhk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gtonctuvip.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gtrmvlvrhn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvpvsvkt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gtumzbzdhk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtsepjayof.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhiwuduotai.top/Article/details/gtwdzlqdwb.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gtzndmvfsx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shzxlz.cn/Article/details/gtowyovdro.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtnewnbdxo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtdrrpslbn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtpqhthaiz.html

Java: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtfsgwrhbb.html

Go:   7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gthmenidwc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtdfrsyobm.html

C#:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gtpabgfhgh.html

[A06] 字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtjjzdkjwb.html

Py:   int("42"); float("3.14")
来源：http://dali.redwolf501.top/Article/details/gtrcpzbuat.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gteajvxypr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gtpesegeah.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtqkoelqwh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqvefubr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrqavihg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gtoneafxoh.html


<!-- 参考信息 -->