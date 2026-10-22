代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtqmjaseyy.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtmkwzjejr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtasnrnjuc.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gtdqectfqi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtpnjjvupm.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gttggubcrv.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtfhwtffcf.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtdxecqhig.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gtdreatqyd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfaaustqy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgwcqikh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvwnpydip.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtckqkblau.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtpbmcvuwn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtgzpmrtzu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gtfwomvgsh.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtnrmluqdv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gthaptvmbu.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtryydtows.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtzhrxaofy.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtmizluyrs.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtztjlpxiz.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gtqifbuarb.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gtivzktwat.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtlwmmaqaq.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gtaqbdzrln.html

[U08] Py：展平二维列表
来源：http://dali.gzhubu.top/Article/details/gtirweqdfc.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtamsoycku.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gtgbosjfhh.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gtrknwgfbr.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtejbfgkuv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtpvcbfzdh.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtkhbizncx.html

(x * 2 for x in arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfqmfotvl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtquosyiwy.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtcxeeryph.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gtcfoiftow.html

deque(maxlen=10)
来源：http://dali.iojbl.cn/Article/details/gtqgzzhfbl.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtyuckwlfr.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gtihxgqbcw.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtwomdfelj.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gttimkgtzz.html

[U16] Py：命令行参数解析
来源：http://dali.yj20258888.top/Article/details/gtmntkbfcz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfkfzmpf.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtyxsytyky.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gtyndinlkf.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtyopjnnay.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtgvmldsyf.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gtotjqvjzd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlbjcgbv.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gtifqiffxd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gtjyxjcvef.html

[U21] Py：自定义上下文管理器
来源：http://dali.sweek.top/Article/details/gtljmquswq.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gttqvvsvrk.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gtftdywbvk.html

list(zip(*m))
来源：http://dali.0kj1m.cn/Article/details/gtewrocjfn.html

[U23] Py：分块读取大文件
来源：http://dali.jianghu66.top/Article/details/gtajknccop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhiwuduotai.top/Article/details/gtqdhtmwwi.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtrlwzhgnc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtfqvgwmao.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtfiiossps.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gtpwrsxksb.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtvhkuobfg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gtqyrwldve.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtxhfvpnwh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtmqdurhof.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gtjqqcuuof.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtnsbmrfek.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtoijejdal.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gtribjjchs.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtpfdycnxg.html

@dataclass(slots=True)
来源：http://dali.aizwys.cn/Article/details/gtxqparziz.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtisfcwima.html

python -m pytest -q
来源：http://dali.hysaishi.cn/Article/details/gtglfyyygo.html

[U32] Py：代码格式化
来源：http://dali.jinqigufen.top/Article/details/gtdhejkalf.html

ruff format . && ruff check --fix .
来源：http://dali.yanxiufei.cn/Article/details/gtadfljaav.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gttnoshegu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigufen.top/Article/details/gthtohkaou.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtiwijomxc.html

chardet.detect(raw)
来源：http://dali.chenjidiqi.icu/Article/details/gtnmmaetgk.html

[U35] Py：发送邮件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmkelonm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gtjhjzecqh.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gtbtshelzk.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtjzvseggt.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtdrrtjhhz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fzhhl.top/Article/details/gtfciflbxy.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtavgxxrxc.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gtidqdzfsy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gtlkatklvv.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtrrzxpuez.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtrpezwrzo.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtdshirnum.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gtfpnjagcg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gtndxxqxcv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dashuyun.cn/Article/details/gtlfbexfpq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gtwzhxhlfq.html

[U43] PHP：声明命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdkgervd.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gtnxcjcpmn.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gtbgyfeswv.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gtvaqoklvb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gtywnsszbu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtcksxgwji.html

[U46] PHP：可空类型
来源：http://dali.zhengqikj.top/Article/details/gtcpetjyyt.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gtgmirppyj.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gtvxeskfns.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtocwnoypy.html

[U48] PHP：纯枚举
来源：http://dali.yanxiufei.cn/Article/details/gtiwahcttc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuanzhike.top/Article/details/gtagoatsjo.html

[U49] PHP：只读属性
来源：http://dali.haohaochexian.top/Article/details/gtbycpddwp.html

public readonly string $name
来源：http://dali.gaohongyu789.top/Article/details/gttnawxrkc.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gtizjbegtu.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gthicztgga.html

[U51] PHP：数组解构
来源：http://dali.yj20258888.top/Article/details/gtcvsulqqx.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gtfyjkovcx.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtrtdzsbtw.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gtvemusjpz.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtzhrcmxmp.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtctmbnsng.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gtdysfssav.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gthoqvjitl.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gtydvvnyly.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtnyrptndu.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gtjsfpwxgf.html

f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtthcrwemw.html

[U57] PHP：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtzftzbjbu.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gtzfokemkd.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gtsywxffwt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cucudq.cn/Article/details/gtxmjgotrv.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtvxktwkpy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtggpbrukq.html

[U60] PHP：JSON 编解码
来源：http://dali.c1oappe.top/Article/details/gtxcyxrigi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gtzwteflsg.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gtiuijfgdy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlqudsxp.html

[U62] PHP：日期对象
来源：http://dali.yj202588.top/Article/details/gtcszjeglg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gtxisvsspv.html

[U63] PHP：文件读写
来源：http://dali.sysykeji.top/Article/details/gtgftwscnl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtoqxfebvz.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gtxxkesllu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gtmqygboqg.html

[U65] PHP：会话
来源：http://dali.ehwqpu.com/Article/details/gtoxdxnpnj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtdwbeexhj.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gtsmyqyiqi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtzinqcpqb.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gthojgiazs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sxryk.cn/Article/details/gtpuxrveln.html

[U68] PHP：PDO 连接
来源：http://dali.hysaishi.cn/Article/details/gtbzocxsdi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gtolqbkfyn.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gtqljfignm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gtyytonurg.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gtysryakjn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtavkeogfc.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtltgwgxoi.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gtysvgazzh.html

[U72] PHP：写错误日志
来源：http://dali.yuanzhike.top/Article/details/gtuqxmicwv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gthoxeejho.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gtaavypntq.html

parse_ini_file("config.ini", true)
来源：http://dali.hammf.cn/Article/details/gtqvyrcbro.html

[U74] PHP：读取环境变量
来源：http://dali.yonumen.top/Article/details/gtkdqrkwai.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gttorcvyim.html

[U75] PHP：依赖注入
来源：http://dali.cashguo.top/Article/details/gtgamcvbsn.html

composer require psr/container
来源：http://dali.meibo888.top/Article/details/gtcuzvcfrj.html

[U76] PHP：简单路由
来源：http://dali.gaohongyu789.top/Article/details/gtnpuslioz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gtydlsnepg.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gtycjryzvm.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gtpflgeevp.html

[U78] PHP：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtzzvzslzv.html

composer require --dev phpunit/phpunit
来源：http://dali.feifeiyinyue.top/Article/details/gtjfikjzio.html

[U79] PHP：静态分析
来源：http://dali.sweek.top/Article/details/gtpaacgsqm.html

composer require --dev phpstan/phpstan
来源：http://dali.bjfxy.top/Article/details/gtnoonyxvz.html

[U80] PHP：代码规范修复
来源：http://dali.zdqjudy.top/Article/details/gtyrmomiqa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xinyue.icu/Article/details/gtsifetfsy.html

[U81] JS：初始化项目
来源：http://dali.sxryk.cn/Article/details/gtnidwodom.html

npm init -y;  npm i express
来源：http://dali.sysykeji.top/Article/details/gtoiduvqbo.html

[U82] JS：package.json 脚本
来源：http://dali.yvedp.cn/Article/details/gtbaecafnq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gtjtuwtdrx.html

[U83] JS：ES Module 导入导出
来源：http://dali.yuxming.cn/Article/details/gtstzhoogj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtjydcbffx.html

[U84] JS：CommonJS 写法
来源：http://dali.yvedp.cn/Article/details/gtyiznmhec.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gtffodegwa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gtmnwaoqib.html

a?.b?.c
来源：http://dali.ehwqpu.com/Article/details/gtouuwaxhw.html

[U86] JS：空值合并
来源：http://dali.tanke756.top/Article/details/gtjrhksaqg.html

a ?? b
来源：http://dali.jqgufenzy.top/Article/details/gtmplrckpy.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtbquuwwoz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cucudq.cn/Article/details/gtrhhezxpo.html

[U88] JS：对象展开合并
来源：http://dali.nwbrower.top/Article/details/gtxccirzuy.html

{ ...a, ...b }
来源：http://dali.cdnleiting.top/Article/details/gtoftqjcgs.html

[U89] JS：数组去重
来源：http://dali.daria6918.cn/Article/details/gtcowrtxnq.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtzmodrgmf.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gtepamqhmd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtbscsnyth.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gtbejzeftc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hnqzz.top/Article/details/gtwhlwaiij.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gtpdnjfbzw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtivstphbc.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gtogbulwpb.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvalbprx.html

[U94] JS：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtcdijrmeu.html

const double = x => x * 2;
来源：http://dali.shuidangran.top/Article/details/gtbrkcwqji.html

[U95] JS：Promise 包装
来源：http://dali.vqdsnc.cn/Article/details/gttimlqzso.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gtezeewdno.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtbjpibctx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtooofkuej.html

[U97] JS：并发请求
来源：http://dali.meibo888.top/Article/details/gtxdainnse.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtrcrpezis.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtbqxnjypn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pengpengdd.cyou/Article/details/gtaniyihsw.html

[U99] JS：事件监听
来源：http://dali.hongshengwenyu.top/Article/details/gtfwucwmgx.html

el.addEventListener("click", e => {})
来源：http://dali.jianghu66.top/Article/details/gtiylsxhuo.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gtkmakpsvt.html

document.querySelector(".item")
来源：http://dali.dashuyun.cn/Article/details/gtyfjocnjp.html

[U101] JS：classList 操作
来源：http://dali.iojbl.cn/Article/details/gtwbfpclnz.html

el.classList.toggle("active")
来源：http://dali.shuidangran.top/Article/details/gtlqwbjcbu.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtwtgiqcbd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yanxiufei.cn/Article/details/gtwxbqwqln.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gtulkdlmpo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ybcxt.top/Article/details/gtbmebpofb.html

[U104] JS：防抖
来源：http://dali.yongpay.top/Article/details/gtcgrrznkx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtacgrscbd.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtrftmotha.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yangfankeji.com/Article/details/gtrqkdffvi.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtxtqwcoua.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.kuanghao11.cn/Article/details/gtppdnziof.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtazzjeram.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjyetozn.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gthgtxvdkh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtyilwqgvm.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtssvfktvf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gtvjlmkans.html

[U110] JS：数组分块
来源：http://dali.yonumen.top/Article/details/gtiibzmjgy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvaxylcx.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtdbgokoue.html

new Map(Object.entries(obj))
来源：http://dali.zhengqikj.top/Article/details/gttfcejfub.html

[U112] JS：字符串补位
来源：http://dali.xuetiantiany.cn/Article/details/gtfupvcfnn.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gtrvxtmsdu.html

[U113] JS：正则替换全部
来源：http://dali.daxiang520.top/Article/details/gtgfaiqgms.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtqooxmhuh.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gteyldfsgw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtnulubfrx.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtuzgfcxbv.html

crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtoridawpb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtdntivfem.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtzckaurya.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtbqrpggax.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtrvhiepif.html

[U118] JS：开发服务器
来源：http://dali.wangshuangyany.cn/Article/details/gtaokrzdss.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gtpmatibgs.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gtkprzjfzj.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtyveamzhd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtkknionye.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gtlapsarpa.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsjhqlbns.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gtwugejrtl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gteugbolnn.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzgeeojc.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtcwuysdqz.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gtdcdiwxej.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gtdpshkuzd.html

TypeScript ..... 212
来源：http://dali.nanxuanxn.top/Article/details/gtufviqagu.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtueiaqgeo.html

Go ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtzwktrvmw.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtemifhqjd.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gtlmtethwb.html

C .............. 30
来源：http://dali.hnxiangtu.top/Article/details/gtqbyqjopx.html

C++ ............ 30
来源：http://dali.jyoumei.cn/Article/details/gthskclznv.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtvizyxjjy.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gtovpyzlsz.html

Kotlin ......... 15
来源：http://dali.sysykeji.top/Article/details/gtyffalzhk.html

Swift .......... 15
来源：http://dali.havefunace.top/Article/details/gtjnfmdqgn.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gtudwzinjt.html

Perl ........... 10
来源：http://dali.jinqigufen.top/Article/details/gtykvylvwp.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gttrtkakdn.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gtfzgsmsvc.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtmmcerpzr.html

按章节统计：
来源：http://dali.sweek.top/Article/details/gtemmzbltc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtddbgwlqu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gtdwtsmpya.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtlbxhepvm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtwypjflae.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aizwys.cn/Article/details/gtiagdgmfo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gtwytoowvv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtaxtwkzgs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtfpjdtnef.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gttgfxulna.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtbljkwoad.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtabllxhoy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtolscktmk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtwijhvfya.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtklcrxoew.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gtjlubkuup.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtjenhczij.html

Q SQL 专题                              90
来源：http://dali.pengpengdd.cyou/Article/details/gtyzgvjrfj.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gtiyddheby.html

S C / C++ 专题                          60
来源：http://dali.tian-w.cn/Article/details/gtfycipydl.html

T 其他语言补充                          60
来源：http://dali.ivvv.top/Article/details/gtfeexcthy.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtrutedpma.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtnchfuevh.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gtzivodtbc.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtoxctjdwu.html


<!-- 参考信息 -->