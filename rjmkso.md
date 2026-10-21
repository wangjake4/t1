代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gttmwcovaj.html

@contextlib.contextmanager
来源：http://dali.tanke756.top/Article/details/gtebdscsgp.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtngeikhgt.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspfbtjpn.html

[U23] Py：分块读取大文件
来源：http://dali.snrcjt.cn/Article/details/gtnjjcodqm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtoisfpign.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gtbvyygkqi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtabgxfpez.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtauviqvrq.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gtdomtpmye.html

[U26] Py：并发下载
来源：http://dali.svipenyu.cn/Article/details/gtlagvbkcl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gtocwxiolf.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gtfykgmidt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtssygabma.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtascrlfyr.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtlvhmmcqo.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuzvuxgm.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gttvnqmsgt.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gtumoyjoyx.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtsswmvjjk.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtionkhrmm.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtipkznahz.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gtnzvpxeyz.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gthnxvkrsl.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtbvgrbrfi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gtjpuqblnj.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gthdoveqfe.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gtmvbkpwzu.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gtadtyxiui.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gtqxtbcfuq.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gtpezntnid.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdqhidjw.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gtsveqhckb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gtohizsacj.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gtdlqsoueo.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gtqawwegqv.html

[U39] Py：判断是否在交互环境
来源：http://dali.yangfankeji.com/Article/details/gtdlizzhsz.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gttiuzazbr.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gtorwpbivr.html

print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gturzbtrpr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cheryme.top/Article/details/gtoorimkie.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtweetctsp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhongyouzk.top/Article/details/gtebozreyk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gtmtvirmld.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gtpjfpemhi.html

namespace App\Http;
来源：http://dali.chenlongwang.top/Article/details/gtkamiobfq.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfleqcwc.html

declare(strict_types=1);
来源：http://dali.9152youxi.cn/Article/details/gteltvdaek.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtnzfypmna.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqllbtbk.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gteiwybeyt.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gtevczqwfp.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtidqcwyst.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gtrpakqhhd.html

[U48] PHP：纯枚举
来源：http://dali.ivvv.top/Article/details/gtdyorkgmz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtubwgruzr.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gtqqltzwyw.html

public readonly string $name
来源：http://dali.yuxming.cn/Article/details/gtbjowzhys.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgfzy.top/Article/details/gtfqfulqvb.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtynfeuboa.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbpuenzo.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gteiaumyfk.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtosrzrrxm.html

$double = fn($x) => $x * 2;
来源：http://dali.xziqi.cn/Article/details/gtsjqkhnie.html

[U53] PHP：空合并运算符
来源：http://dali.zhengqikj.top/Article/details/gtrsjsmnmj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zycfv.cn/Article/details/gtvfljdnxm.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonqrzmjs.html

$obj?->method()
来源：http://dali.andypj.xyz/Article/details/gtnvcptdkc.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gtwlcsxteg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtebejeiln.html

[U56] PHP：命名参数
来源：http://dali.hfpthk.cn/Article/details/gtuczkvdkv.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtxsxbzvvw.html

[U57] PHP：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtqwiqfnbz.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtgdvrwrdt.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gtkdmjhhey.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtxlcszrdz.html

[U59] PHP：自定义排序
来源：http://dali.yj202588.top/Article/details/gtftlsjyso.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtvemhynbx.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtqqbolxpm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gthshktnnx.html

[U61] PHP：正则
来源：http://dali.vqdsnc.cn/Article/details/gtgkeimfxp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtztcalehm.html

[U62] PHP：日期对象
来源：http://dali.aizwys.cn/Article/details/gtmjugiipn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnauaslcz.html

[U63] PHP：文件读写
来源：http://dali.jlsjyb.cn/Article/details/gthpgxcjoi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.dashuyun.cn/Article/details/gttgaxyier.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gtogatshcx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gtpppisqvf.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtkwnotfpv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtergpnxkx.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gtisykajug.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zycfv.cn/Article/details/gtirmymzkc.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtrobrklrb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinqigufen.top/Article/details/gtujmclxqw.html

[U68] PHP：PDO 连接
来源：http://dali.sweek.top/Article/details/gtqgsqlujh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sweek.top/Article/details/gtobgervsv.html

[U69] PHP：PDO 预处理
来源：http://dali.tian-w.cn/Article/details/gtgqlmwabd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gogol.net.cn/Article/details/gtbpjqghbq.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gtczbkzkam.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.redwolf501.top/Article/details/gtczxsivwc.html

[U71] PHP：抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtgmojcdow.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gtgfesdxgf.html

[U72] PHP：写错误日志
来源：http://dali.tianlin.xyz/Article/details/gtmznidpze.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangdashe.top/Article/details/gtobqthusd.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gtsadlnttp.html

parse_ini_file("config.ini", true)
来源：http://dali.gogol.net.cn/Article/details/gtnmbjcpwl.html

[U74] PHP：读取环境变量
来源：http://dali.fengsongda.top/Article/details/gtiqxisgqu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pycfn.com/Article/details/gthwwnaxof.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtkssqpowt.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gtlxymlmqa.html

[U76] PHP：简单路由
来源：http://dali.meibo888.top/Article/details/gtsbkyiavc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gtakzwepwy.html

[U77] PHP：模板渲染
来源：http://dali.ppjwa.cn/Article/details/gtapbwdqso.html

composer require twig/twig
来源：http://dali.xziqi.cn/Article/details/gtfpjqvljj.html

[U78] PHP：单元测试
来源：http://dali.jyoumei.cn/Article/details/gtaqavmphm.html

composer require --dev phpunit/phpunit
来源：http://dali.andypj.xyz/Article/details/gtozuendya.html

[U79] PHP：静态分析
来源：http://dali.ybcxt.top/Article/details/gthhxsewep.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gtjdheydmb.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gtzztmnlur.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtfvpftvgz.html

[U81] JS：初始化项目
来源：http://dali.chenlongwang.top/Article/details/gtneypgtaf.html

npm init -y;  npm i express
来源：http://dali.nanxinkj.top/Article/details/gtpeejavtf.html

[U82] JS：package.json 脚本
来源：http://dali.redwolf501.top/Article/details/gtvuqzxexw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yongpay.top/Article/details/gtehtedaiq.html

[U83] JS：ES Module 导入导出
来源：http://dali.cucudq.cn/Article/details/gtvimaimzk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gteknjqwkt.html

[U84] JS：CommonJS 写法
来源：http://dali.hammf.cn/Article/details/gtaykcnheg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.redwolf501.top/Article/details/gtvrzpwtxp.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gteshboaap.html

a?.b?.c
来源：http://dali.zhiwuduotai.top/Article/details/gtocxommes.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtxeehqaei.html

a ?? b
来源：http://dali.hammf.cn/Article/details/gtwcyjqejv.html

[U87] JS：解构默认值
来源：http://dali.jianghu66.top/Article/details/gtexudzhtn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqphwbnk.html

[U88] JS：对象展开合并
来源：http://dali.jianghu66.top/Article/details/gtmwtbwsud.html

{ ...a, ...b }
来源：http://dali.yangfankeji.com/Article/details/gtmzgjylmg.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gtfubbeibh.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtofhekxjz.html

[U90] JS：数字数组排序
来源：http://dali.nanxinkj.top/Article/details/gtnfrtgkmw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gthwjypghx.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gtdvahkvuw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gtkfzixdwk.html

[U92] JS：深拷贝
来源：http://dali.aizwys.cn/Article/details/gtodgiufad.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtxfuzynlq.html

[U93] JS：模板字符串
来源：http://dali.sweek.top/Article/details/gtbqtpabpm.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gtwcxjfdrj.html

[U94] JS：箭头函数
来源：http://dali.yj202588.top/Article/details/gtspfrwsqs.html

const double = x => x * 2;
来源：http://dali.ybcxt.top/Article/details/gtciafizqt.html

[U95] JS：Promise 包装
来源：http://dali.gaohongyu789.top/Article/details/gtikwiaenw.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gttlpmwaco.html

[U96] JS：async/await 与异常
来源：http://dali.iojbl.cn/Article/details/gtnngypsml.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmaurodhb.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchluagde.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtscxwuiyf.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtvlwabezw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gtqxnnpaos.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtulhxnzkd.html

el.addEventListener("click", e => {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfbxckqs.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtuazmrlgf.html

document.querySelector(".item")
来源：http://dali.yongpay.top/Article/details/gtdgeidwqb.html

[U101] JS：classList 操作
来源：http://dali.sysykeji.top/Article/details/gtxeawwwsh.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gthqcpzxqz.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbsuffjn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ivvv.top/Article/details/gttqdojjtr.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtsqzjzldn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gtiiygfazk.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtkqbvdcal.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gteeqnkfff.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gthrinceka.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhengqikj.top/Article/details/gtwouderkz.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtojmrjnfn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gtwcxdbhxt.html

[U107] JS：数字千分位
来源：http://dali.tanke756.top/Article/details/gtipmerogz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gthtwcgbah.html

[U108] JS：随机整数
来源：http://dali.hongshengwenyu.top/Article/details/gtgvjenpgo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenzaomai.com/Article/details/gtmkxncczs.html

[U109] JS：数组分组
来源：http://dali.guannengcc.top/Article/details/gtracdiohg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtvzfqblfk.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtqoajcugx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnqzz.top/Article/details/gtuzlhvqgi.html

[U111] JS：对象转 Map
来源：http://dali.dashuyun.cn/Article/details/gttupuroft.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtlmfuycxx.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gttcjdbrmd.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtnywgfxao.html

[U113] JS：正则替换全部
来源：http://dali.ehwqpu.com/Article/details/gtldmkacmx.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtnomkxiyw.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gtbbsfagzq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtkdjbmqji.html

[U115] JS：生成 UUID
来源：http://dali.yj202588.top/Article/details/gtnnkcbxwn.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtnzeliwlp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtppvpszmf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yueranfly.top/Article/details/gtlccijrdi.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtxibgbudh.html

npm i -D vitest;  npx vitest
来源：http://dali.wangshuangyany.cn/Article/details/gtwjntzycx.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gtdrkxmskm.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtvpdfursq.html

[U119] JS：生产构建
来源：http://dali.cdnleiting.top/Article/details/gtvdbhutza.html

npx vite build
来源：http://dali.chenzaomai.com/Article/details/gtjbhfvreb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjttvxitg.html

import.meta.env.VITE_API_URL
来源：http://dali.svipenyu.cn/Article/details/gtmpwoxxpl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtruagding.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtjgwhzfjk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtueupfotv.html

按语言统计（条）：
来源：http://dali.c1oappe.top/Article/details/gtpseyfpny.html

Python ......... 252
来源：http://dali.shangyingyoupin.top/Article/details/gtpfnplrjr.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtyofqhafr.html

JavaScript ..... 252
来源：http://dali.havefunace.top/Article/details/gtvlrckkus.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtwlisijqz.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyyhytje.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtaiicopbj.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtvucnwcxq.html

C# ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtaundztkz.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gtydnymfhg.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gttrmoxhmk.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gtuvkvthmr.html

Bash ........... 80
来源：http://dali.sweek.top/Article/details/gtxwducqvx.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtlxllzwvx.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gtfdhruihv.html

Lua ............ 10
来源：http://dali.c1oappe.top/Article/details/gtlvjjrvay.html

Perl ........... 10
来源：http://dali.sxryk.cn/Article/details/gtdszctcco.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gtdklazgxs.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtpxupsyaz.html

合计 ........... 2106 条
来源：http://dali.iojbl.cn/Article/details/gtnjmnqycg.html

按章节统计：
来源：http://dali.hysaishi.cn/Article/details/gtjuymkouy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gteulfcrao.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtqknfitmf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtdrnhiprc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtqcsesqhh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewtafmjy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtdxinyhsn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtaqglyjsq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gtkpnvdqss.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtzxhjmntq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtyovphfcs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtvskbqskq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtkzhgogmd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtcxxkwrzk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.vqdsnc.cn/Article/details/gtsnpuhhqe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtptyriagz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtcvdcrcuk.html

Q SQL 专题                              90
来源：http://dali.nanxinkj.top/Article/details/gtaltggapj.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gtvucojlji.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtmofajqio.html

T 其他语言补充                          60
来源：http://dali.aizwys.cn/Article/details/gttquilgmp.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwbkxvwa.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtvflpwgyr.html

合计                                  2106 条
来源：http://dali.0kj1m.cn/Article/details/gtbwlmtdui.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtquusoihj.html

使用提醒
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuborvclu.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtujsdsxnl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fengsongda.top/Article/details/gtecvtsncb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtqzoaxkdq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnqzz.top/Article/details/gtifyvadjl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ppjwa.cn/Article/details/gtupbwireh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.iojbl.cn/Article/details/gtnbyiwufm.html

—— 文件结束 ——
来源：http://dali.cucudq.cn/Article/details/gtewpmslne.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtldfulolz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jyoumei.cn/Article/details/gtncupmpjm.html

Common Programming Examples Cheat Book
来源：http://dali.jianghu66.top/Article/details/gtehsnxmez.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkuysdnpe.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtxsvlcnkx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cqqwz.cn/Article/details/gtgxqqgvtz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gtaafgpvbf.html

SQL · Bash · C · C++
来源：http://dali.jinqigfzy.top/Article/details/gtxncxruah.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.tanke756.top/Article/details/gtkffazxhh.html

【使用说明】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdldloma.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgufenzy.top/Article/details/gtlggtaosc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gtcduzcoqd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjfdjrcj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daxiang520.top/Article/details/gtjbnoywfy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gtnybtjyje.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gtfiwphtgm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtfogblicu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.haohaochexian.top/Article/details/gttcztnjii.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhengqikj.top/Article/details/gttvnrxqai.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtftmnlsdk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangshuangyany.cn/Article/details/gtbcfddinv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtgwrmfghu.html

【文件统计】
来源：http://dali.smart0.xyz/Article/details/gttinecrgo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gtdioecupw.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtieguccjl.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeubzwaw.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtabvwftkw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gtaxkvchzz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtfptdvrpq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xinyue.icu/Article/details/gtqukzucch.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtxenpiimk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtagixpuzc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtshscrvfi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gtlucvxzdz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtznvdzdlg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtobsgsetd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtbqgdwjoa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtwybkkjxq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gtqbabnvkb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtuxwitjsj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gtnzpkmztl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gtmvbprkws.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtmegiocjo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yanxiufei.cn/Article/details/gtdssybsoa.html


<!-- 参考信息 -->