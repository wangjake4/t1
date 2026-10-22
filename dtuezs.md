代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmjajhj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iatvmsgm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdtflqw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijraaopu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrfdfuv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2emajwqog.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrjsqug.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2satxhgcq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoiyarx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wusukotl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsjyhuq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2humvypdw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aprrxfgl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyjsacj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sohqvzzx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjkmibe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdrlcfq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcfgnau.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzyyegw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2uzafahma.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqialits.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugawmmix.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hldxetwf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oozzgsxn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfupqqe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2smyowlfp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbpxvqe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2admnunoo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2snkmjwxt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbbhuxs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwonqkn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfppfrs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oppcmgmc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apdbkfwf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qckvxycu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyhoxri.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sozbpggu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlfpinu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxstvmg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtuumdp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzlzkwp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxwbmfz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoerehw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvfxrhi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcfctvw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnbogrp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtpfgca.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ckplimgp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpcvypm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xnskfhsz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtgzokk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2enxgyiwz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoicvkr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kueyjseq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecujobql.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdtjvlz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhqlfhl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vknaksct.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hukoupde.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nprldcny.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqncvjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbbikgp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpkhmbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qitflpza.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vfebmitw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2btpolpgp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpzrbwz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdqakxh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeuggxs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2grbziwul.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2onnzbkbk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iyshspkh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2epnosmxr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pklvncbt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qlucsuad.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vefolrcb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2swofjrfw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwxaagp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2djibsfed.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wydyhkyz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cehwntdv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2quouhfzo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dothznan.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxgezqp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cohcwjvp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcubxkwu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvzbbyw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkwdigc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zftnjztf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2urawjwxx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2waywfzmf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqqkcky.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjxidpz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2epzbnlja.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnbiwcz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2weqipjgc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dppooxjb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgdioln.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zllmpifp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2atldwhyw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2afhldznv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxdzlhk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wlecfcth.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2miwwbvbp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2urpljrru.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddfcvm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2clnalvss.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkuyqgo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcivfdf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbugydx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjnngep.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2diyapzpw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gbecikoj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tntmbbdb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nscjlyym.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgckaabp.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zyocspii.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zywxedgi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ugulblop.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjvdkw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqajtft.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xevjnajt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hltkxowb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwajvhfr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2szdvbxjc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zryixsku.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaagtcd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hevtdmzj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwcvasp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkwtrnp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaqrafs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xadgbzbk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhbaqit.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmxkefh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2klodxarv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkvveou.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mkblfcsv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbbnaej.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgfmlag.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ymisgdbd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaghkrj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxzajqy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjubpem.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evwravqg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjxnocc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iamlxloy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2msnsydrq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcqtret.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhuyopn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wosrynxo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wluucxpc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbiytlt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqwnllw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2favjkawu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhdvccu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ohketuhl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhwhacc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfgfjop.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkkivkn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiueioc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hfftatvo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2foxffifj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hoosznxo.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwcaojb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uphvfwft.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcezfruy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkkscca.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqdbzwd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pogibipi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2iucfgpch.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyapfrh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bklbssuf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tupjansg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgumfxqx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oylveqlf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2emvwdegz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czyukota.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2turlkcxs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cajtzqan.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqgyasa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjeankxc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrxhzdw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fssbwsle.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoowxbtq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iupqmzle.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2psifmnsl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bldcljpv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpkshgs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2czclsbpy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rckglhjg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2udgqhphg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrjfszp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2mjewhsuz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kosrdgub.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgbnfho.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybygnssp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xerxpzpn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyokpsth.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyvemfx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxnzmmx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhazrck.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwdyhfh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmcsxgt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnqwgks.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpiaspu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywijrkrg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eyksmqob.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xokvsfer.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2piuhlmsh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oanawsfk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oosvdbcb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqqjlwo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrpmscy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dxysjxas.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tnncshky.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdxaqnc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2armxasad.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2oujrdphz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2acudrrvj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uloawnam.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfuczwu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsmeapg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsjwuiv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaggyjg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vinxmoqv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhnzuki.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2soyoxmuk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2onkpasqw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrxcjed.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fbezirpj.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2edxquwkm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yibvhnzg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qqysyjln.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2giskodvp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvtudle.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tphwclcl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dltrqmsb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufreyyav.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vifcebef.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsvprks.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjcblam.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjuxuoy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvjmkhr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwjpvls.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnvigvy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsggbiq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfrnelu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrndfjg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhyluwf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2arckijmq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwyotld.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eytbfryn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2awnzmbes.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxhsybg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgncnff.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfimrsj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqublvv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cglxtbfo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtmmfav.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhhflsx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zomndcox.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gzigbwra.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kamslodd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ancurbec.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjpamyi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhefxhx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyqgeky.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiuruja.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fkngaexx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oagqzlsa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2llwobfyr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcjxdln.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qudvpmia.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsmocfk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vkklzccl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfpncof.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rvigyigs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfkxvge.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2irokfzun.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rnumciqi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfrrcdd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vixooqdm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvackds.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtilnga.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwyrokf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bifxowde.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lfppfobo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiyuznt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sxritpbw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnroiwr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhcczgh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqhjsrx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2teztpvwg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhefamw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtgdgvq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjoduen.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2awoxinqq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2japmvodd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ldymvnyn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcqnzfi.html


<!-- 参考信息 -->