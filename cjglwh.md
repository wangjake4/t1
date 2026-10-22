代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epjkkgbt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdzgwqh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brexvpdu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2llmcpqdx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2voclpqhy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kvexmagr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kiagcfbd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2myvkwzya.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjubbho.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2taitapol.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoflakp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoondas.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrmwxke.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2glhsnhen.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kivbitmq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhncfju.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yznzvwyo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dngeyxox.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yodgffhl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jihbacrx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2krhxbsvj.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkshnsz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfhthhq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2efflpzrm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoblahi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtppxmy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtpwyto.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzftvife.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdpvbcc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqileqen.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmvuhnb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nksesfed.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ishofwqm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfmadw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzabhxs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziviriux.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzwvzxd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtqemwn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsvfyiu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtexjqzk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvpwbok.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwkrlsb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqmalcc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oztqmsmu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlyrqlm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpqnlva.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2riwmuzja.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fuycqmax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfeppil.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jurjejzb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2movbizdr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhhxxsf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwdvgri.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2errfdgfv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjbgxxq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgqfhxl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aznvtrmt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rcesbrwo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzitttdr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbjxqlm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiqpexk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iervrwec.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbqtasw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwryatpn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdnfhye.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kqelajyx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlaugtd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkqtimv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxrmxjk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jroteuht.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2reltudrl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sqczxxuw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjqzigx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzotxyzr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvcewjt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2btfzagsh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiydstxj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdamwkc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2liumjlai.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fovuzmev.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuohbdb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yplfajmm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkckbdi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwttteth.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2giyhxbtc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlctvxr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zstampdx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyhmwsp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfakyfg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rihhxewo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqsiocj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2srohifge.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wslnoawe.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdbidig.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2earrirqc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2edhxjzej.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xlewdwxv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzzeznm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cppvdrbx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdlyvsm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbbnrat.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfustlp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkhbsnq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltordnrb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2slzqyweq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wljutmgg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nnidprqs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqfppol.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhvjjlc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zknitzfa.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzfemwx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzsrfbq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rseakolh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjadnpeu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzsmkxy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2puhyfqhy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgffruw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2viearztw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvjntha.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2deeyudch.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2haeuemcl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uducekqx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2shleecbq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbikgki.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lulpcyuz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyvbqfj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmehlwq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiqzvqt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoxsggz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2efsnqxnn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmgllcb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xddusyxz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2msaolyis.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmpbkpv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zffxnhbh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgibtnot.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2onplvcga.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrkafqj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2krvigvsp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzvprbo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrdjdvb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xocegljy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmkpkqy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtoldti.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyspxtz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdzqmby.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2orfqaxrq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiebtdzb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2apdyezfj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvifclx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kijnzufy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gspdbghd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoclbmc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyllsyl.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqhlyxc.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2byxucdtc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjghcpr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pylndarx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qznbojba.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgpodnz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rcikoduv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2obiwlnhx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsslewj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eakwpczh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zloesztv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbofxhku.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpvewrg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvfhoos.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vbipljkp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvsvbtr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wikrqjuo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eknuoqlb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2layqiimu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwycsny.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfxeylb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvwkfaw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsayjyi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgchuzgc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2alvnfvfa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2frdrzobo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lonpxxqt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hastqxzc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnjfng.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2levceyrz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrbfwjx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiugvjzq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzijvat.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhmwtx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yaccusef.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaezmcr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdbpccl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yymbhmqx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2odgcewvt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2osojydce.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2irogsgth.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqoftjj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrnhgwt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpyohqt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2acdsxyvo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjftonte.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqljvla.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gchkvxlq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpnzzab.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2raujnrkw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwyjevt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffumgqge.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bsexxpbo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgyiqre.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsvfveh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpfhtzf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfhyjio.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyehdymi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjrugqr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzjjhdc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tunslhgz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvxgael.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wpszgpay.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rqapyytl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xryvmyam.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhxzwen.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfgdxnw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jszlgmrg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgugxvf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkpomwc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2npwggoay.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2urkxzyai.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlallwt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2odjfnkns.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mchkahya.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdnfgaw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhfxhiz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlciapl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2prsyovug.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2awvudcwb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiblrxy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwdvvsn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2weoxphju.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcxomhi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vddurddg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emgbuees.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbxkjcu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2getsgeuf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjpnjxc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhunmsc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmfzdtu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qnchuqcb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqtuyvn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfmghub.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhyocxs.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijdpay.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeuaiuy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2muybmzfh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hzajtwxk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fiznspxz.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eskuxbzv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dadipnuz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvvuput.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfizgbml.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xpktiijq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oezdfyyy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhvzweu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iomheats.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kknrvwzj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqiozjq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2alowfynx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtakeaaz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdlsxfs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vilftsuk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2homnltzk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuxviky.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzmdmcb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzpgsad.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyrxqtq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mofnhroj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmleail.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lybjlbaz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbiccgs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfksfzzh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2swrcejux.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmcplew.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eawonbmn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmhneca.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mplszvct.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqgiprx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgjtkna.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2itsnjadz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpsezgq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkibqcf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtctbid.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwlensi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfjhirr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umgmcdry.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyfofnn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrqzfhz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsvacec.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mepypyip.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkspgxe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqpasno.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2udykgngh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sasnafmk.html


<!-- 参考信息 -->