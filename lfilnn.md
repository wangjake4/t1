代发 wailian999

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtzfglgwjy.html

t = time.perf_counter()
来源：http://dali.hongshengwenyu.top/Article/details/gtaltgmswa.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtpfyycxgz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtvbafqbvv.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gtqmhmttjv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtzcyfaurd.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtjcvechou.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtppbpuxbb.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtvgraygvk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fzhhl.top/Article/details/gtlavbmiar.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtfnmpunld.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtujuvvnuo.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gtatslzpjy.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtfmupwamb.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtfghpacdi.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqfaetxq.html

[U23] Py：分块读取大文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfipzeagq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtxirnotdg.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtkftolgrl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtssjhsoig.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gtjfqqpghm.html

csv.DictReader(f)
来源：http://dali.svipenyu.cn/Article/details/gtwpxbxsfc.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtwmmpsitw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtgszsipkj.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gtktkhssvu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtuaitjwwm.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtjqqqhrbt.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtdvfdvihe.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtsrvsjyhi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gthecoghmz.html

[U30] Py：数据类
来源：http://dali.chenzaomai.com/Article/details/gtycdgepkl.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtpgcfuvwr.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gttiepzqqv.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtcrueuvua.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gtxjhdedig.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbcannih.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtlxpjwkka.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gtkimsyfol.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtddtgfftz.html

chardet.detect(raw)
来源：http://dali.gogol.net.cn/Article/details/gthbdgtojj.html

[U35] Py：发送邮件
来源：http://dali.havefunace.top/Article/details/gtmtqfmcpr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gtymjiwslp.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gttlehjvae.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gtqmaotfzu.html

[U37] Py：读写 Excel
来源：http://dali.sweek.top/Article/details/gtssfeoluf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gtkxeskvsj.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtnonrqbcf.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gthrehejso.html

[U39] Py：判断是否在交互环境
来源：http://dali.nwbrower.top/Article/details/gtfjvsrhaq.html

sys.stdout.isatty()
来源：http://dali.quarkkingdee.top/Article/details/gtnkixefqi.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gtefrqekxy.html

print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtyamxsrco.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtevmcqygk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gtrqgkmiml.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtkpqxntoa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtjkjufaad.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtkdzzilim.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gtovckwpnj.html

[U44] PHP：开启严格类型
来源：http://dali.cdnleiting.top/Article/details/gtdpljmuft.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gtyxeclckj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtnnfbeckk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtrdfxtuvx.html

[U46] PHP：可空类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsidnxyn.html

?string $name = null
来源：http://dali.redwolf501.top/Article/details/gtrffxuhjo.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtfnxdjpts.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gtcraxlgnu.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gtaxsdtqft.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jyoumei.cn/Article/details/gtoiklemqc.html

[U49] PHP：只读属性
来源：http://dali.andypj.xyz/Article/details/gtccmstzrz.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gtvcjljwvj.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gtrwivkrio.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gtioiwjnzs.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtlyirzcof.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gttevjfils.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gthuwwouyv.html

$double = fn($x) => $x * 2;
来源：http://dali.jyoumei.cn/Article/details/gtjbjjqdoz.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtgnarbazj.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gtxjxrvoqo.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gthcfebpvo.html

$obj?->method()
来源：http://dali.hfpthk.cn/Article/details/gttyykkird.html

[U55] PHP：match 表达式
来源：http://dali.snrcjt.cn/Article/details/gtlsgvxtjq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtwacgmzpb.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrevhpipa.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsbxaptfp.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtdihcegtz.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gthkxntjxq.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gtbtckyhom.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtkgitpbpp.html

[U59] PHP：自定义排序
来源：http://dali.zdqjudy.top/Article/details/gthrzyjbbw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtirpaxaxy.html

[U60] PHP：JSON 编解码
来源：http://dali.sweek.top/Article/details/gtdbtwxyue.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gtxulicrry.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gtkhrasgar.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gttmwjubqw.html

[U62] PHP：日期对象
来源：http://dali.pengpengdd.cyou/Article/details/gtymwtzvmy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenzaomai.com/Article/details/gtnqpfewbm.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtfwsqhtqw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxinkj.top/Article/details/gtjmmcjcue.html

[U64] PHP：目录遍历
来源：http://dali.wangshuangyany.cn/Article/details/gthjvnrieg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gogol.net.cn/Article/details/gtszkxnvar.html

[U65] PHP：会话
来源：http://dali.chenlongwang.top/Article/details/gtsrdqulwd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtaqaorpkq.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gtxvsfmdyw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hfpthk.cn/Article/details/gtkqvbcjhb.html

[U67] PHP：处理文件上传
来源：http://dali.jinqigfzy.top/Article/details/gtuzfkkndn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gtkscfyomd.html

[U68] PHP：PDO 连接
来源：http://dali.snrcjt.cn/Article/details/gtdmmeepmb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pengpengdd.cyou/Article/details/gtkujtcrcw.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsjxdblv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.feifeiyinyue.top/Article/details/gtashzsghu.html

[U70] PHP：PDO 事务
来源：http://dali.cdnleiting.top/Article/details/gtogpgtddv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cqqwz.cn/Article/details/gtneladynw.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtqjkhwyqj.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtpwniqkgi.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gtvxntlskg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gttgpxmtns.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtreahgxuj.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtyewhhqqv.html

[U74] PHP：读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtainrhgqf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gtirkghbos.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gtcjztwtxv.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gtmuyytddb.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gtowbqnzit.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ydzc1.top/Article/details/gtfykzrpcz.html

[U77] PHP：模板渲染
来源：http://dali.pengpengdd.cyou/Article/details/gtiorhwjjw.html

composer require twig/twig
来源：http://dali.0kj1m.cn/Article/details/gtcdjwwopo.html

[U78] PHP：单元测试
来源：http://dali.jlsjyb.cn/Article/details/gttdkasykq.html

composer require --dev phpunit/phpunit
来源：http://dali.sxryk.cn/Article/details/gtoxqciybw.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gtaamelsju.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gttmwiriuh.html

[U80] PHP：代码规范修复
来源：http://dali.nanxinkj.top/Article/details/gtybndffdy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guowangkeji.top/Article/details/gtisilmmbh.html

[U81] JS：初始化项目
来源：http://dali.ydzc1.top/Article/details/gtcmbjddpg.html

npm init -y;  npm i express
来源：http://dali.guowangkeji.top/Article/details/gtjjfwflgi.html

[U82] JS：package.json 脚本
来源：http://dali.chenzaomai.com/Article/details/gtvsbncmpf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtbmqogrbn.html

[U83] JS：ES Module 导入导出
来源：http://dali.jianghu66.top/Article/details/gtlpruzwjw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtdinfhlhg.html

[U84] JS：CommonJS 写法
来源：http://dali.snrcjt.cn/Article/details/gtcxcimzyc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gtuiuxdypm.html

[U85] JS：可选链
来源：http://dali.meibo888.top/Article/details/gtylfauatv.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrudchadt.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gtpidgajog.html

a ?? b
来源：http://dali.guannengcc.top/Article/details/gtpxtpovyy.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gtwsxunqok.html

const { a = 1, b = 2 } = obj;
来源：http://dali.kuanghao11.cn/Article/details/gthrihwjat.html

[U88] JS：对象展开合并
来源：http://dali.redwolf501.top/Article/details/gtdxriltyp.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gturfghgcp.html

[U89] JS：数组去重
来源：http://dali.nwbrower.top/Article/details/gtsgykbesv.html

[...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtylaguler.html

[U90] JS：数字数组排序
来源：http://dali.cucudq.cn/Article/details/gtykouuefa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gteaxczntr.html

[U91] JS：对象键值遍历
来源：http://dali.jlsjyb.cn/Article/details/gtrcnmaebx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gtbkqnkbso.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gtmqodgnbt.html

structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gttcgwhbnc.html

[U93] JS：模板字符串
来源：http://dali.sysykeji.top/Article/details/gttuyxphhf.html

`共 ${n} 条`
来源：http://dali.cucudq.cn/Article/details/gttvgnkczd.html

[U94] JS：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtynknuscl.html

const double = x => x * 2;
来源：http://dali.c1oappe.top/Article/details/gtjblojsaw.html

[U95] JS：Promise 包装
来源：http://dali.vqdsnc.cn/Article/details/gtluluovkb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhongyouzk.top/Article/details/gtxhpxstxb.html

[U96] JS：async/await 与异常
来源：http://dali.tanke756.top/Article/details/gtbifojhgp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtaekhvbsn.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtwunamwlt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtzduaazgs.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxinkj.top/Article/details/gtlaoktlts.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtmddlddrw.html

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gttvbrydkc.html

el.addEventListener("click", e => {})
来源：http://dali.mhx1999.top/Article/details/gthikhsemo.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gtondavcpm.html

document.querySelector(".item")
来源：http://dali.quarkkingdee.top/Article/details/gturzptnzm.html

[U101] JS：classList 操作
来源：http://dali.zhengqikj.top/Article/details/gtvniybbul.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gtuypfusag.html

[U102] JS：本地存储
来源：http://dali.feifeiyinyue.top/Article/details/gtuczcfdpz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gtktmcqges.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gtphhufeuz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtkdkgysde.html

[U104] JS：防抖
来源：http://dali.hnxiangtu.top/Article/details/gtikxiwbtj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtkiogvyrp.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gtmnmpmhru.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyspycug.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gttblrmkiq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ehwqpu.com/Article/details/gtwicbocdd.html

[U107] JS：数字千分位
来源：http://dali.andypj.xyz/Article/details/gtiolwpgrv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuxming.cn/Article/details/gtemgaleaq.html

[U108] JS：随机整数
来源：http://dali.guannengcc.top/Article/details/gtqsjnjhpr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gtlosjwnsw.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtsgawvijt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gtcvdlvicr.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtddlgasvi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gtairooxtc.html

[U111] JS：对象转 Map
来源：http://dali.gaohongyu789.top/Article/details/gtdqhuhnxn.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtxepejvud.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpzkjmeg.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtivmsgdzz.html

[U113] JS：正则替换全部
来源：http://dali.jianghu66.top/Article/details/gtpbweetvs.html

s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtpkejsbnx.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gtwihbrroy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtqkmaapzw.html

[U115] JS：生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtnrkuljaw.html

crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtqsfgfuqj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fzhhl.top/Article/details/gtwuagznkh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtkavlqeba.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtrmckucss.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtcwdjmlpz.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gtdptoamak.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtgbsbidyr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gtuxqbdogj.html

npx vite build
来源：http://dali.tian-w.cn/Article/details/gtopfbgtmv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gtivdlrxjx.html

import.meta.env.VITE_API_URL
来源：http://dali.zdqjudy.top/Article/details/gtenwvkvim.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtdnspet.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtjixbktrw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydijwvev.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gtslhqxxkg.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtlzffvuin.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtkaxzszpg.html

JavaScript ..... 252
来源：http://dali.yj20258888.top/Article/details/gtgpcghnsq.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gtoukmlkuo.html

Java ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtjhghockx.html

Go ............. 212
来源：http://dali.gzhubu.top/Article/details/gtxnqldfnc.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtjwjkanjz.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gthhbkjzqw.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gtusaegamt.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gtrlfhvksj.html

SQL ............ 90
来源：http://dali.andypj.xyz/Article/details/gtgsxzrbme.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gtnxqtgtbc.html

Kotlin ......... 15
来源：http://dali.zhengqikj.top/Article/details/gtldcywfsw.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gtebhpfpky.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gthybdrvfc.html

Perl ........... 10
来源：http://dali.ehwqpu.com/Article/details/gtjknlvyjx.html

Scala .......... 10
来源：http://dali.yuxming.cn/Article/details/gtmgytekhy.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtpupgtplb.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtkoscykdf.html

按章节统计：
来源：http://dali.haohaochexian.top/Article/details/gtilclzcnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtphogwghb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtciqeyonh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtsdzusccj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtzgmbdogk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufcmfcav.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtxwppnfgf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtmnyylohx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtcupivkgm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtsipllrsn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtfppxksfj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtrxzmpzxs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtxkyfuakk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtazxsplsk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtexpcitme.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gthxdyubkx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gtfrrtmfgx.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gtwphnbkry.html

R Bash 专题                             80
来源：http://dali.tianlin.xyz/Article/details/gtrcolmsmi.html

S C / C++ 专题                          60
来源：http://dali.cqqwz.cn/Article/details/gtdwufctib.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtseimpmfk.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtfscgzlro.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtdbxlubue.html

合计                                  2106 条
来源：http://dali.smart0.xyz/Article/details/gtchpooaoi.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtpqwcjnlw.html

使用提醒
来源：http://dali.hnxiangtu.top/Article/details/gtsqgrxzcf.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtrobtcgbs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sysykeji.top/Article/details/gtdrqpvweo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gtgrcwjufl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgufenzy.top/Article/details/gtishpsdkr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daria6918.cn/Article/details/gtdgfjuuev.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sweek.top/Article/details/gtnkhrczct.html

—— 文件结束 ——
来源：http://dali.316326.xyz/Article/details/gtjfqhgtkl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlhuhjujl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gtvgijcjwc.html

Common Programming Examples Cheat Book
来源：http://dali.nwbrower.top/Article/details/gtihddsgbe.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgsbuyedc.html

【收录内容】
来源：http://dali.xylfe.cn/Article/details/gtdimamxhv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.wangdashe.top/Article/details/gtqdnwifrs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yongpay.top/Article/details/gtmrvyaate.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtqjsbvosq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejzyddgk.html

【使用说明】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfztuylkb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gtecfoyeuh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcssqtuvv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtrtonwtwf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gtlvjgavcm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jiagoushi.top/Article/details/gtsxhnxmqw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hongshengwenyu.top/Article/details/gtqtntyaaq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jyoumei.cn/Article/details/gtyjdmhtbt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gtrpdszuqy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pengpengdd.cyou/Article/details/gtjrbjglej.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.c1oappe.top/Article/details/gtmuqfclgd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpgxvjqv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnxiangtu.top/Article/details/gtmsgvwekt.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gtgsjjzwfz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tian-w.cn/Article/details/gtnpqypybr.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtjemhevlr.html

目  录
来源：http://dali.zhoulong.xyz/Article/details/gtrmtpthvb.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtemzxovdm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gtseaopuev.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtwjvmxkyb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtqwscljqa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtouzsbtfj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhixingplan.top/Article/details/gtxoenyhdz.html


<!-- 参考信息 -->