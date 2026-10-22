代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mseokvff.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzekiqvd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgkagjy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvzjvem.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqwdjip.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ansawvfl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2caxwdsnh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2norbsciq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhlfetx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zipezwfb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2emkttzrs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cguwftyj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmisdgit.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gotggsrn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnoruco.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2efwaydmi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfovwbib.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdiqzyb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2noltfvvu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdunigk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2glnguyws.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoyjwsa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hchzieji.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiwzqke.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yylcibel.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgrvokp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcijtkg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhbmwpv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqhhaae.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2puezruyg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgtswte.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uicpxgbm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhickzk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atgikugk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhggejq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iatjjnqs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrkwntk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igedqwop.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efznhlrv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrennqe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgxwria.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmemjezz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flwtwkbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkvsvzk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkfoqyl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uadtwtre.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvubvepa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2haabxern.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrykcbd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2onqisujb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdkjwlw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnonupo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgdclyx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnjnyfa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvccoqte.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrfdjuk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pshsqoqg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcgknhj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiqfnvm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2payvertg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oifsvuel.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sqocernc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqhlmix.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qusztlbv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjvlqvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwtddkg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpjvxut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvjjisc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2adgnjnta.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hvymbgtb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxvlbxp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnfankj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxqtmkl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qetznekx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2etecpxxj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2igaqzxwv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qecdbpjb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kaznxfrd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oltvklzw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwesvzkq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2drigwhzj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uawrnlxn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nytyfiwn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2quzrdxar.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dacsqctv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmywpyfs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tphbljly.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgdktki.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnurdsh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkafmcx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2koojfvkb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxspjfwd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhcfdvt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkdpilk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdaykpg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsqkjee.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmujnlh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrqshuk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxwzbaw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrzvww.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aioqzudf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qshuywqo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwsaxni.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqhpoyk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2pepcqrlo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lonmfsuk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dazdyzff.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhsuovf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rfemlmvh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qizvqjvi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaoavbh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmehmmz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwqhhwy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tlueswha.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uuezldym.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2apnkvcjr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjynydu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2opgvyvuh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ycajrgfe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2amwxwinx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xakdhdzw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqxdvdw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiwcngr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaethep.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpulscq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjcbtgp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kagmjriv.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubhjbga.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlwzbbq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cuumphxb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2alyuowin.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkwhxrh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmxytoe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhaevqr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxefbp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwqatsw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbltyyyc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhqjkvl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhmccap.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuozdjt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2udctgkjh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqejzvo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kpebllkx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvlvgsr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvztdts.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsgwovq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eojnggvk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxszisu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2noqvuokz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtlenes.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjpyiza.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zacvdtgz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2chrysrbm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvictra.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zskivpks.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfecihl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqhixqb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fensimce.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgozowcr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wckdktgo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rebtoepe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lckkajqi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sznmxbjr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfzizxp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2znxyzygj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zehmvmzb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dufygsmc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2baozdijh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2clrmpgnn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvywlij.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pohtbdbd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2boblroxd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfvfmew.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzoewmv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yozkltvj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2turlqscv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgchvkj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxahfxeo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlfxrw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbatzrps.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvynptt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmwkybk.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xiedayil.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fattucno.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pamljocz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2irkwvouc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2drglwted.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfowcrwj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvcodwm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbswtqb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yarpwlwj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hytcjdwy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrmbvkm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgprlpjm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrgkvam.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cypuxomc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2icrwtumt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqelzxh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2alkspshp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2azavzxjh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nglnsbdi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2trfazjoy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzkpiou.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbzrhwx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxticrkp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whlgyyww.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2azcdaoqo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2csidutwn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkwebyd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvafswvk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvpdadq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2igetdypj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2umrqfoua.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxqgcxs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicmqua.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rukdtwos.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qhazpyrw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcggsbn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvgirap.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdpbkem.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlksxeg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2axgurnkq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqvvhwf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnkfbwd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2baahvxpl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgmrzed.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wucnezfd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pblueacc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmqgbct.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2iqajvnrx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjapfof.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2izfiuudi.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2oyimerpe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2llzhhztp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pryayjyq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekulchlj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kprcozil.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwrxgya.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfxfgin.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2eaytlgyj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zycjnngf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2umdgbpkb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2inyomaow.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djwbughq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iitcnipd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoqqpdc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sppruewt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkccdec.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbuohvz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjhbcrc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaplhkz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxnqdrz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsrwesz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvemmdt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucchlzcr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnyqrxn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2emtaegfn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwgyvpj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aueibqlc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgsxlpg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tueoriqj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cakxbnor.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2whfhfzpc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2webpuopc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zplluwod.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2efaezzmn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuhulge.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgspxgil.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfpulcn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuejhfw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2djehupoh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2micmweif.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxblenj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2axmidqcz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgxsnfi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiriokxq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjwimil.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfrgdwi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwoogje.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uijjimfm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbhzxzr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnizcli.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqugskwx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnlckph.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvmjbpi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbioufya.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fcodonfd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2afwgcxdf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qautnrtv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhnwxjm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvsmwye.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfkoytd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ighscitq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uifmodsc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vedoazcx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwektfsm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwkikkg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iehudnnh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfkjrqg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trlrpcsu.html


<!-- 参考信息 -->