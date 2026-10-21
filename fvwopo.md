代发 wailian999

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgncmslez.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtwqsnrldn.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtxioetqui.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yanxiufei.cn/Article/details/gtugabzsck.html

[U17] Py：初始化日志
来源：http://dali.zhiwuduotai.top/Article/details/gtzvboljyv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtejswfjup.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtshbqjivw.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtgczqyqrs.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtjmrtcrge.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtjlyxslxj.html

[U20] Py：缓存函数结果
来源：http://dali.hammf.cn/Article/details/gtuvurzsdc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guannengcc.top/Article/details/gtbqwtqddb.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtikdxaemr.html

@contextlib.contextmanager
来源：http://dali.yj20258888.top/Article/details/gtmfjsvsov.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuxxokhq.html

list(zip(*m))
来源：http://dali.c1oappe.top/Article/details/gtmbhgjaol.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gtqetbzmah.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tianlin.xyz/Article/details/gtzhlecdzp.html

[U24] Py：路径操作
来源：http://dali.hywenlv.cn/Article/details/gtobkydzeb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtvsyfibyc.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtcxmqyhre.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtgkmurewl.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtbclevqtx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gtzegsdxto.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gtvcagqwjr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtbkuonwag.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtoetdlgld.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtqmzoqwmi.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gtcujdadcj.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gthxyhkljx.html

[U30] Py：数据类
来源：http://dali.redwolf501.top/Article/details/gtayspvzgg.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gtjlkzxwwk.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gtjhfwrfsl.html

python -m pytest -q
来源：http://dali.jianghu66.top/Article/details/gtzcpksomd.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gtlzlbenag.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gtametcibr.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtkloxwvpq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xylfe.cn/Article/details/gtlbekhcbc.html

[U34] Py：判断编码
来源：http://dali.cqqwz.cn/Article/details/gtbqnattxk.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtdguecvno.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gtcedcacol.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcicbynho.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtocheobif.html

schedule.every(10).minutes.do(job)
来源：http://dali.kuanghao11.cn/Article/details/gtcleorvgl.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gtvfamxezb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gtkymcppjr.html

[U38] Py：获取脚本所在目录
来源：http://dali.tanke756.top/Article/details/gtwsbbidhz.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gtjhpsdnbw.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gtxaiqeduq.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtpwfczbxd.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gtgingfyrr.html

print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtdfctvsbg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmndpfuxq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gtzzsqhsqb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gtgveagdjt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtouhvehrz.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gtbfhmbrvx.html

namespace App\Http;
来源：http://dali.cdnleiting.top/Article/details/gtnnrbuoaq.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gtezwuhhow.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtsmctwcpz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.316326.xyz/Article/details/gtjctplybn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtfgdnflmr.html

[U46] PHP：可空类型
来源：http://dali.chenjidiqi.icu/Article/details/gtmfuyegcz.html

?string $name = null
来源：http://dali.316326.xyz/Article/details/gtsjvhqcfs.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtfcafqthm.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtrfdqxghy.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtgrzvoxze.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gtqttjjfhd.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gtmrcykzss.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtzmajvjlw.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gtdwrmujrf.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gtsnhdzezz.html

[U51] PHP：数组解构
来源：http://dali.feifeiyinyue.top/Article/details/gtteirtpps.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtefwalcgt.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtiswzjwgk.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtrauedtnd.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gtqcdxcuha.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gtssrnrdqf.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtpbgqvftt.html

$obj?->method()
来源：http://dali.redwolf501.top/Article/details/gtypobnakp.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtodjoeuda.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtpfysjmal.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gtwcpzcbwf.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtmcopdgis.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtdpwiofch.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtcnomaqzf.html

[U58] PHP：数组三件套
来源：http://dali.shuidangran.top/Article/details/gtroaoewhl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenlongwang.top/Article/details/gtpfnleujg.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gtyntvlgdw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtvfpbplog.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gtijpzxeod.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuxming.cn/Article/details/gtryovxkte.html

[U61] PHP：正则
来源：http://dali.ehwqpu.com/Article/details/gtxtpjejnf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gtjmzdtvch.html

[U62] PHP：日期对象
来源：http://dali.yj20258.top/Article/details/gtpknfetfe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtozxxhazn.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gtcisamdnh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tianlin.xyz/Article/details/gtzbserglr.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gtwaxngegi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jyoumei.cn/Article/details/gtkquoqvbb.html

[U65] PHP：会话
来源：http://dali.hnqzz.top/Article/details/gtbhngmocl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtttywkkqg.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gttjdbtxbo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gtfgclfifv.html

[U67] PHP：处理文件上传
来源：http://dali.yj202588.top/Article/details/gtdzivauqs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtctlylsgh.html

[U68] PHP：PDO 连接
来源：http://dali.hywenlv.cn/Article/details/gtfipzaazp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zdqjudy.top/Article/details/gtudcxonxa.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtwgkgjyzj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gaohongyu789.top/Article/details/gthrkfjxyl.html

[U70] PHP：PDO 事务
来源：http://dali.zhoulong.xyz/Article/details/gtpnydsqky.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtljguszbh.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtnaqfzvls.html

throw new RuntimeException("失败", 500);
来源：http://dali.yvedp.cn/Article/details/gtnaoukdvz.html

[U72] PHP：写错误日志
来源：http://dali.jinqigfzy.top/Article/details/gtgquvorkd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhspszcf.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gtkqaxlcox.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gtlwsgropp.html

[U74] PHP：读取环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphivlzmb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gtmigotmbu.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gtauixdjyw.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtzkswyctj.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gtwoimkvze.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hfpthk.cn/Article/details/gtqmnjupmf.html

[U77] PHP：模板渲染
来源：http://dali.zhiwuduotai.top/Article/details/gtucaphgdz.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtldvoxicy.html

[U78] PHP：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtsgnywkvx.html

composer require --dev phpunit/phpunit
来源：http://dali.nwbrower.top/Article/details/gtoijoxdgu.html

[U79] PHP：静态分析
来源：http://dali.havefunace.top/Article/details/gtrlsuzayd.html

composer require --dev phpstan/phpstan
来源：http://dali.hysaishi.cn/Article/details/gtwgzdebkg.html

[U80] PHP：代码规范修复
来源：http://dali.tanke756.top/Article/details/gtfmxyezru.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.9152youxi.cn/Article/details/gtzgknzvyu.html

[U81] JS：初始化项目
来源：http://dali.hfpthk.cn/Article/details/gtqvybpzbc.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gtyscztrcs.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gtxelmdbft.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhengqikj.top/Article/details/gtqxdxbedq.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtdhlueugs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtsdtwlkft.html

[U84] JS：CommonJS 写法
来源：http://dali.yonumen.top/Article/details/gtgqodozkq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sxryk.cn/Article/details/gtpuigbope.html

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gthwvczbnk.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhwmspkq.html

[U86] JS：空值合并
来源：http://dali.cashguo.top/Article/details/gturxtjlrb.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gtssjnlstc.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gthzefyvaw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtsfxwiqyv.html

[U88] JS：对象展开合并
来源：http://dali.hfpthk.cn/Article/details/gtzdbocsia.html

{ ...a, ...b }
来源：http://dali.svipenyu.cn/Article/details/gtkhwmrnng.html

[U89] JS：数组去重
来源：http://dali.jiagoushi.top/Article/details/gtpmkwyrrd.html

[...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtwyywkpms.html

[U90] JS：数字数组排序
来源：http://dali.quarkkingdee.top/Article/details/gtkqcpimeu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtvghufuzm.html

[U91] JS：对象键值遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvbqlmzv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.iojbl.cn/Article/details/gtunqkflvb.html

[U92] JS：深拷贝
来源：http://dali.chenzaomai.com/Article/details/gtperecawr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtzxflebfq.html

[U93] JS：模板字符串
来源：http://dali.daxiang520.top/Article/details/gtqjupoltf.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gthdnculqt.html

[U94] JS：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtvpqaswfr.html

const double = x => x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtlzrdcuxk.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohjzqcil.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gtfloxrdam.html

[U96] JS：async/await 与异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixecsppt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtmdczcpcn.html

[U97] JS：并发请求
来源：http://dali.iojbl.cn/Article/details/gtucgkbrzv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtemovwaip.html

[U98] JS：fetch 带 JSON
来源：http://dali.yvedp.cn/Article/details/gtdjgdkaqr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sysykeji.top/Article/details/gthvqblhlw.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtiepqxbog.html

el.addEventListener("click", e => {})
来源：http://dali.zhengqikj.top/Article/details/gtaddiyuor.html

[U100] JS：DOM 查询
来源：http://dali.hywenlv.cn/Article/details/gtukkmdwwz.html

document.querySelector(".item")
来源：http://dali.nanxuanxn.top/Article/details/gtftgayunk.html

[U101] JS：classList 操作
来源：http://dali.hongshengwenyu.top/Article/details/gticjfjncs.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gtfvyjjoay.html

[U102] JS：本地存储
来源：http://dali.gzhubu.top/Article/details/gtbeydgeva.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gtefaadnpl.html

[U103] JS：定时器
来源：http://dali.smart0.xyz/Article/details/gtlpptahop.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj202588.top/Article/details/gtgtimumeq.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gteyyibgyz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtkkmrnbed.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gtzjoapuqd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sysykeji.top/Article/details/gtcjrtfdot.html

[U106] JS：日期格式化
来源：http://dali.xinyue.icu/Article/details/gtbobjwvzd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtlimxnxyq.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gtaodmxgtd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtvmdqzwea.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gtdqvojshm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhoulong.xyz/Article/details/gtopgonfcr.html

[U109] JS：数组分组
来源：http://dali.birdmap.top/Article/details/gtodjudwvs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtjdctyhle.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gteqaowjlr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gthqsmdxtt.html

[U111] JS：对象转 Map
来源：http://dali.iojbl.cn/Article/details/gtinqsshsh.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgzcdkcu.html

[U112] JS：字符串补位
来源：http://dali.jiagoushi.top/Article/details/gtockakjmv.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtnusgaakl.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtqxenlbbx.html

s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtivvqrbda.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gtdrirjhzy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtoeukkamy.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtuqypwaed.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdkedyiz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gtduqshfmy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxtbvosmk.html

[U117] JS：单元测试
来源：http://dali.redwolf501.top/Article/details/gtngdmfyck.html

npm i -D vitest;  npx vitest
来源：http://dali.9152youxi.cn/Article/details/gtifxtwagq.html

[U118] JS：开发服务器
来源：http://dali.nanxinkj.top/Article/details/gtkqvrgzly.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gttogdzvxw.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtbhibwqie.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gthveuthvn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkbgpiek.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtymsqmqgg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gthfgboesx.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gtwhxibupn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcfnscfju.html

按语言统计（条）：
来源：http://dali.pengpengdd.cyou/Article/details/gthabmwvuk.html

Python ......... 252
来源：http://dali.snrcjt.cn/Article/details/gtpmueizre.html

PHP ............ 252
来源：http://dali.havefunace.top/Article/details/gtotnzrkay.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtzeozzhxv.html

TypeScript ..... 212
来源：http://dali.yangfankeji.com/Article/details/gtbrtbxsuy.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gtkowryzyl.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtombrpjry.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxoroeshy.html

C# ............. 212
来源：http://dali.gotoacloud.top/Article/details/gttgqgfube.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gthojdbswm.html

C++ ............ 30
来源：http://dali.dashuyun.cn/Article/details/gtwzukwuau.html

SQL ............ 90
来源：http://dali.yvedp.cn/Article/details/gtoipixacm.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gtbinudfvr.html

Kotlin ......... 15
来源：http://dali.tian-w.cn/Article/details/gtnnlnzpep.html

Swift .......... 15
来源：http://dali.tian-w.cn/Article/details/gthiuxsbmj.html

Lua ............ 10
来源：http://dali.meibo888.top/Article/details/gtuwndanyx.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtsvwqngai.html

Scala .......... 10
来源：http://dali.jianghu66.top/Article/details/gtpfmqsska.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtftagzqoj.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtiarexhzu.html

按章节统计：
来源：http://dali.shzxlz.cn/Article/details/gtwhdlzyrt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtedhehmyn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtbtvduesm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtauajrnqm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gtivbytgql.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gogol.net.cn/Article/details/gtwljdwmar.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtcbdjxnil.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtftdzsyol.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtutpplqfc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvzngrul.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tianlin.xyz/Article/details/gtoxnfzaxh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtgiqydara.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtxqnmdxdm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtiurffiao.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtnhkdvzyp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhengqikj.top/Article/details/gtrdwhwuvb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtyajduakz.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gtbshfoeqk.html

R Bash 专题                             80
来源：http://dali.dashuyun.cn/Article/details/gtkolhhqqt.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtkvbyyvwo.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gtfofikuuj.html

U 高频实用片段                         120
来源：http://dali.yj202588.top/Article/details/gtbwqvrqsc.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtergfngys.html

合计                                  2106 条
来源：http://dali.chenjidiqi.icu/Article/details/gttllebiii.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtfpahhmcx.html

使用提醒
来源：http://dali.nanxuanxn.top/Article/details/gtikulrykx.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtsebbdwzs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yanxiufei.cn/Article/details/gtmmqtykns.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtqhntvase.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtkndywhfu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gtiexuovkw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gtxqqjltnr.html

—— 文件结束 ——
来源：http://dali.cdnleiting.top/Article/details/gtjuwxdglt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlwzyvmks.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhengqikj.top/Article/details/gtnpipartd.html

Common Programming Examples Cheat Book
来源：http://dali.zycfv.cn/Article/details/gtitndnqqh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtebjcdwxl.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gtdzclmttk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yj20258.top/Article/details/gtclvzsoyz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gtyzaavevo.html

SQL · Bash · C · C++
来源：http://dali.hywenlv.cn/Article/details/gtnjnrtypa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gtmwnxoqhu.html

【使用说明】
来源：http://dali.hysaishi.cn/Article/details/gtyfrlqmkh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gtlmrkygvf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtgmjsjdht.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gtvbrklqht.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gtglhnqxrw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gtcdtnvrvd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gtqmrqkxaa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtusgpwdbu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.c1oappe.top/Article/details/gtxbertmjh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigufen.top/Article/details/gtzjqkehki.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gtizzqxpac.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sufxvd.cn/Article/details/gtiswmnozj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guowangkeji.top/Article/details/gtvxiltqhx.html

【文件统计】
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcxdkbpa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakzubpcj.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtsddxseaa.html

目  录
来源：http://dali.hnqzz.top/Article/details/gtgcgysxsf.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtkqsumimt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtdlvewopa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtiaycbqms.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtawkfrpiz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtfmvdjvhb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cucudq.cn/Article/details/gtidjvjpxo.html


<!-- 参考信息 -->