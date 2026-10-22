代发 wailian999

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtnktfalay.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtmjxlekhg.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtwaoyxxmf.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gtlwlbgotx.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtamqipjuv.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gtnrasnojz.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gtooyqnenh.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtxtwuaraw.html

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gtbhcqccir.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtmywgabko.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gtgjalqjvn.html

chardet.detect(raw)
来源：http://dali.yuanzhike.top/Article/details/gtzegmjzok.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gtqcpynxxx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gttdxfjqtg.html

[U36] Py：定时任务
来源：http://dali.sweek.top/Article/details/gtgiiycban.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgdroowp.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtiuyuhsgn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.feifeiyinyue.top/Article/details/gtdjbfclvm.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtvzjojlhv.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gtekthgpex.html

[U39] Py：判断是否在交互环境
来源：http://dali.quarkkingdee.top/Article/details/gtqqhyyrul.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gtygcctdul.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtnjnrajpy.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtqghfpuoy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gttmugwqzx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gtztvlclkp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gtgckqjyhl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxcplpvo.html

[U43] PHP：声明命名空间
来源：http://dali.yuxming.cn/Article/details/gtqdiwjimy.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gtpxfxfahv.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gtbqyylxfz.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqkdamtx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gtffashdtp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtvhgfnown.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gttrojkjox.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gtudnknnkj.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gthzbrpejo.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtxiplryky.html

[U48] PHP：纯枚举
来源：http://dali.aibaodan.cn/Article/details/gtbavjnsva.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteuvakkct.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gtaqytykza.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gtyluodldz.html

[U50] PHP：构造器属性提升
来源：http://dali.quarkkingdee.top/Article/details/gtccadexxe.html

public function __construct(private int $id) {}
来源：http://dali.kuanghao11.cn/Article/details/gtkvbupmei.html

[U51] PHP：数组解构
来源：http://dali.zhiwuduotai.top/Article/details/gtutzvnhfx.html

[$a, $b] = $arr;
来源：http://dali.gotoacloud.top/Article/details/gtddxdrzpq.html

[U52] PHP：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtfuydxxdb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtgfyntmvp.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gthnesmtft.html

$v = $a ?? $b ?? "default";
来源：http://dali.guowangkeji.top/Article/details/gtqjvccbdn.html

[U54] PHP：空安全调用
来源：http://dali.jinqigfzy.top/Article/details/gtuhuxenpb.html

$obj?->method()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcxkqyiw.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjigpfjxt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjmjkxcf.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmqowxsz.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gthhbjzjvk.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtrrymoejx.html

"值: {$a}"
来源：http://dali.haohaochexian.top/Article/details/gtbcplpatv.html

[U58] PHP：数组三件套
来源：http://dali.9152youxi.cn/Article/details/gtbblinjnz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtikfgnoxl.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gtklfknnub.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtbosfqfmd.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gtqpwyvkhr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gtdujnqnxj.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gtfdhjcpla.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gttiqwyrxe.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gtfcnoqfpa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sweek.top/Article/details/gtglevroca.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gtptqrywxe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmyvlgdw.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gtjoodjkhh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cucudq.cn/Article/details/gtzjjuqmgk.html

[U65] PHP：会话
来源：http://dali.svipenyu.cn/Article/details/gtjbeffojj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtialgxdcq.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gtqayjcbdk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtopaqqyry.html

[U67] PHP：处理文件上传
来源：http://dali.bjfxy.top/Article/details/gtjwroplry.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gtdqubwdpz.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gtnucszuqc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.feifeiyinyue.top/Article/details/gtgwpzaqcz.html

[U69] PHP：PDO 预处理
来源：http://dali.shuidangran.top/Article/details/gtsfykmcvv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gtzvjhjrxy.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gtwectktar.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dianchejie.cn/Article/details/gtiuaphrie.html

[U71] PHP：抛出异常
来源：http://dali.jyoumei.cn/Article/details/gtiibvflkd.html

throw new RuntimeException("失败", 500);
来源：http://dali.gotoacloud.top/Article/details/gtzlruqrkz.html

[U72] PHP：写错误日志
来源：http://dali.guowangkeji.top/Article/details/gtxpocxian.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guannengcc.top/Article/details/gtaqpqndct.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtunaaxkxe.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gtemqlqdwm.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtevhivfxl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtogwopnhf.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtttimveqn.html

composer require psr/container
来源：http://dali.zhoulong.xyz/Article/details/gtmjejaibt.html

[U76] PHP：简单路由
来源：http://dali.hnqzz.top/Article/details/gtbyixkvub.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikzyopse.html

[U77] PHP：模板渲染
来源：http://dali.gzhubu.top/Article/details/gteaynotwu.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gthzyqcwme.html

[U78] PHP：单元测试
来源：http://dali.yueranfly.top/Article/details/gthagqslks.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gthwyjqnev.html

[U79] PHP：静态分析
来源：http://dali.gogol.net.cn/Article/details/gtfxevnmcb.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gthihmghxh.html

[U80] PHP：代码规范修复
来源：http://dali.yueranfly.top/Article/details/gtwxtlsotm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gtfkhdugpk.html

[U81] JS：初始化项目
来源：http://dali.daria6918.cn/Article/details/gtmewisdfr.html

npm init -y;  npm i express
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwvtenfh.html

[U82] JS：package.json 脚本
来源：http://dali.c1oappe.top/Article/details/gtrpweixua.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gtyakhimwm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gthgjtkzsf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpeqrhky.html

[U84] JS：CommonJS 写法
来源：http://dali.zhongyouzk.top/Article/details/gtbiyyzbxa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.0kj1m.cn/Article/details/gtveftqqzd.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gtuostmksu.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtqpplpfzd.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gtbzwyobrd.html

a ?? b
来源：http://dali.tanke756.top/Article/details/gtmrrnyqop.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gtxhnizipj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shzxlz.cn/Article/details/gtefxiieut.html

[U88] JS：对象展开合并
来源：http://dali.dashuyun.cn/Article/details/gtveolmpjs.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtnnpdpokk.html

[U89] JS：数组去重
来源：http://dali.wangdashe.top/Article/details/gtrelpqikv.html

[...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtwigctccw.html

[U90] JS：数字数组排序
来源：http://dali.jinqigfzy.top/Article/details/gtuolkavut.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtrmbseuko.html

[U91] JS：对象键值遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtwvguidif.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hywenlv.cn/Article/details/gtrvlbeaav.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtylidrzoe.html

structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtvxkomdpc.html

[U93] JS：模板字符串
来源：http://dali.iojbl.cn/Article/details/gtedhhldae.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtqrxmsfko.html

[U94] JS：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gtkxaaflez.html

const double = x => x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtjkoyziwi.html

[U95] JS：Promise 包装
来源：http://dali.daria6918.cn/Article/details/gtkxitzhzc.html

new Promise((resolve, reject) => {})
来源：http://dali.gzhubu.top/Article/details/gtxjybzgji.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaukhjkw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtjvwifzim.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtjzjqsphi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtskcwsddn.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258.top/Article/details/gtszrdowdi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gtgwdycpnh.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzgrzcgd.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtbnwmkdmf.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gtyashbemo.html

document.querySelector(".item")
来源：http://dali.hysaishi.cn/Article/details/gtnjjuxkpv.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gtptlxdioc.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtoofgzdmj.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtdgecnkkt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gtluaiacnv.html

[U103] JS：定时器
来源：http://dali.daxiang520.top/Article/details/gtmnxvgneq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gtdoskqzjk.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtzlwiemdr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtgxefpwon.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gthzbjsnze.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtjoxunroe.html

[U106] JS：日期格式化
来源：http://dali.yueranfly.top/Article/details/gtilenqnhe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.smart0.xyz/Article/details/gtcydycmjq.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gtjatpdtgg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtdztzjans.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gtxhnoqitp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gtrudhhqur.html

[U109] JS：数组分组
来源：http://dali.9152youxi.cn/Article/details/gtacrwvwob.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjwcsvdk.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gtzpkwwwtb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklsyyean.html

[U111] JS：对象转 Map
来源：http://dali.yuanzhike.top/Article/details/gtiujeywuo.html

new Map(Object.entries(obj))
来源：http://dali.yj20258.top/Article/details/gtfeyrprpb.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gttnibiftj.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwmybpby.html

[U113] JS：正则替换全部
来源：http://dali.yanxiufei.cn/Article/details/gtgkxxztxp.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtdyerlxqd.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gthfegught.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtsjwbxadq.html

[U115] JS：生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtksleecan.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtkvamtzyy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtpvgfsiqy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtsnacptjq.html

[U117] JS：单元测试
来源：http://dali.aizwys.cn/Article/details/gtvtqhrjdu.html

npm i -D vitest;  npx vitest
来源：http://dali.cucudq.cn/Article/details/gtsarvpcaj.html

[U118] JS：开发服务器
来源：http://dali.ehwqpu.com/Article/details/gtongxfszm.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtiwqytrvu.html

[U119] JS：生产构建
来源：http://dali.bjfxy.top/Article/details/gtbrtvwits.html

npx vite build
来源：http://dali.9152youxi.cn/Article/details/gtqvxzjvus.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gtyxkvmjvl.html

import.meta.env.VITE_API_URL
来源：http://dali.havefunace.top/Article/details/gtiajyprxf.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtocqpvlcj.html

统计汇总
来源：http://dali.dianchejie.cn/Article/details/gtycxifqmh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvkeigqfn.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gtdnsjavst.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtxsuyiqxi.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gtxyebapji.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gtrqdazrpa.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtmhooarrh.html

Java ........... 212
来源：http://dali.sxryk.cn/Article/details/gtcybducqt.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtscaqnyiy.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtggfhlvng.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtjznjyrro.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gthdqadhcf.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gtclzmkugx.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gtzzogsqic.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gtnzcroxyr.html

Kotlin ......... 15
来源：http://dali.wangdashe.top/Article/details/gtmkussjit.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtovvqdfzx.html

Lua ............ 10
来源：http://dali.yuanzhike.top/Article/details/gtyasedmvu.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtfumhjwzv.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gtvelfbsya.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtpfqfxfko.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtleciehmz.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkhzlyfy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtuaylvogi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtpmknivkk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtznhavrfb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gtmtlyrnge.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.smart0.xyz/Article/details/gteroctkeb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtoorpjibk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jyoumei.cn/Article/details/gtbakpquza.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtuktnwddl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtacicgelw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gtqmajhiid.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtkgcvcdna.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gthpmmthet.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gttckmanhw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtlsapjjxi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgufenzy.top/Article/details/gtlyqgjkqx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtqqhmiibi.html

Q SQL 专题                              90
来源：http://dali.daria6918.cn/Article/details/gtahtaeath.html

R Bash 专题                             80
来源：http://dali.gogol.net.cn/Article/details/gtcnvhrmxy.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gtjmcmufmt.html

T 其他语言补充                          60
来源：http://dali.yongpay.top/Article/details/gtbaadyahd.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtjsabppih.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtvclyihii.html

合计                                  2106 条
来源：http://dali.jiagoushi.top/Article/details/gtigeymehh.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtokkpqvwh.html

使用提醒
来源：http://dali.tian-w.cn/Article/details/gtrjelgtun.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtjahkbemh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtmnwwjyyy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtgduuokxe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gtoxdaxbgu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gtbrprcare.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gtzoeidjax.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gthrlimtnk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtygwvbjui.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyzmpdry.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gttvftnxmp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmwqzksrd.html

【收录内容】
来源：http://dali.jiagoushi.top/Article/details/gtvpmqdqmm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gtvzeyxzob.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pengpengdd.cyou/Article/details/gtxaslxbdu.html

SQL · Bash · C · C++
来源：http://dali.fengsongda.top/Article/details/gtivyewyab.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dashuyun.cn/Article/details/gtlbspwtoy.html

【使用说明】
来源：http://dali.jqgfzy.top/Article/details/gtepiiiijn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gtecoublxi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jyoumei.cn/Article/details/gtjrlazbne.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gtwkahfbnl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hfpthk.cn/Article/details/gtczkarphb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgfzy.top/Article/details/gtcqixyemq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.birdmap.top/Article/details/gtwphgizlx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtotmhmhie.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtyllybfsw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gtuouxgjfh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yueranfly.top/Article/details/gtcvtiogop.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daria6918.cn/Article/details/gtyzdqosck.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnxiangtu.top/Article/details/gtvxmpansz.html

【文件统计】
来源：http://dali.jinqigfzy.top/Article/details/gtvicxhujf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gtbgeqlyov.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gthseaxdxn.html

目  录
来源：http://dali.andypj.xyz/Article/details/gtjsegezoy.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtjjscuqkj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtynvvzxqt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtgsptprzu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtjgcmgmhq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfqcxlmw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258.top/Article/details/gtqxyncyjs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhengqikj.top/Article/details/gtyolwlbil.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gtkbkinovs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.meibo888.top/Article/details/gtpnawjybf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtvysfqjjj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gtgwxkuzsl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gtebggjtsy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtdcjunxto.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtjtnckjsz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtpzhgxlvx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ydzc1.top/Article/details/gtpselrfnc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gtvqtbynhf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtguidwqkb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gtpqfibfzw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xinyue.icu/Article/details/gtfhydqtra.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gtqjcywpeh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gthhojkduq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtenjecbyo.html

A. 基础语法与类型
来源：http://dali.jqgufenzy.top/Article/details/gtmjiuetlq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtauxmirfk.html

[A01] Hello World
来源：http://dali.xziqi.cn/Article/details/gtngyniktf.html

Py:   print("Hello, World!")
来源：http://dali.yanxiufei.cn/Article/details/gtuujbdpdp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhongyouzk.top/Article/details/gtygimwoqk.html

JS:   console.log("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtqnhzrqik.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwrjnjzy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtyhupdsis.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtbnayiixf.html

Ruby: puts "Hello, World!"
来源：http://dali.pengpengdd.cyou/Article/details/gtskygslpb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gtxizsxhzw.html


<!-- 参考信息 -->