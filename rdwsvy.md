代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbefuog.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrzhgvp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rauprddl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2flgudlnn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdsdyyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fpotmdba.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkborns.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lixsskjv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2knfqpfvf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgfdbgm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxxlmzq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rpugqkqb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvodtdgt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2odspvxxm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcywncoi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuqztqd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fypqjkce.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcikjgvc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xqblxfqv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmiraoj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2giyohsof.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgwoffc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2opumfhel.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgphoxwf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sonsgowe.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfudsev.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpepujye.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etivvjvs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pcifqpcd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcdmtyx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeguobt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvbqzds.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkmammi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlurqoj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsitbci.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhzrplf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrilmme.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcfwxkv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gigymfgd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iawwuqit.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pydldoyx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chmxbvzb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzonkupi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnlkwvy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vycdvura.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sndirqgw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnxdsac.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dkijrjax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwnnjeb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlykdug.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmrcxbn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmxnyvw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2juracrnf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pniifvvg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkjclmg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sldbpktx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjlmlco.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fnecstxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlbmawp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2auloshxq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjezdnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dclgxyks.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2joqrtrgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsrvbsw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsnzenb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmvjxnk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2asffptvw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpvvhao.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwksnp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzivrlbs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2giraezmb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uqesmtdb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ibimodax.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmwlvph.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2alqwdcng.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhjvybu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyagcrr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikouvrvw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhfunqy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzldqgi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2alvfnuow.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xopwbyva.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkdxqmt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdafwvo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuaspws.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2grsppjag.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oifnxhzt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cukrbjol.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpfrvcx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfphrigj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aepmhtmv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbinozqr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2oxetlteq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywywzsyq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2irwpiuos.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzjqgat.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzzsbyi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxtcotl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2olrphtif.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zigjlejm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ivegodfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjovessu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwdmqq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuchfkq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fwymagtn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zgycigir.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfmxhzs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbovbfc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skpibyhq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrmkhqd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yseghddt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2awlnnkdw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bychbbps.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztegjptv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ihctabzs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyirneg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoxpxjk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfkijsd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmklfim.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmatihh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ygawixsq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2spjivjzp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2snstvyhy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htckdwfj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqyxpro.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbbjyjf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wazjrnsi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2owyhooid.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cljxexzt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2howzpsbn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvlryxd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwfryon.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuzevhu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2myeensrx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iodhshaf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifghqkxd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmbolnd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ktceqbuk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2okgrywjm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wkedsvjm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2toofpjdd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnmjsif.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vszfpvol.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbrlmzo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzwvirc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sivmthzk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yaewojxn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2adlzstvy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzprxrex.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2evzculhh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgbtmmi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuzfryz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cndpxhrw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iazyiwxr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zmugaqmd.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pvypixzv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srsroqkx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckbjsc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oswrvbzo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuumlyd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqnstjg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qqafhyuo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vwydjdwu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkayvch.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2odsihnmj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgniwemb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcjwoxd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2guuekdco.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2riwiwsaz.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcmrhnt.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxldpgu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbklhrhf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2paixzpmx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2grfmyefr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ricjmite.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsqngtk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbmymon.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcokglq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vscymoji.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppioxynz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjnipej.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxezinko.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqfmrdr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrxhser.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2riulgaby.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbhjket.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpbttcx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2thxosive.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwldbuu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtumlghy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pewnsksz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eztuarrt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dyywhbxi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewenomhy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuiathg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxafesle.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2alqkchoe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzplsyrp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkctzqp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmrdyja.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdqgznk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuigixf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xxptzavq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsycwnf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnrkabx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyotqmit.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnivxhh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrkaytb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nswzhkzn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2urvpwegk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwjwzip.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkekryl.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoqwjqg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fltdembf.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zfciwnyu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctufqbil.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tgigfkis.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfquqnm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2idtwduyh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsyoafe.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qopfpxzm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjstsvr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yvthaqil.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfoetyw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmstudp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cfprymfk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vgepxgzx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvocjuq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gllebbnf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqtmcjm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuuttrb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2guxpgdxu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xcesswsq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uroslfte.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiztkhq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2onmpwfwd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdqpxyg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ommmkmbe.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzxghlh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhknyqh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2aftkjseg.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwijnim.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idkwjnfy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kryooiuh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpwymou.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2miizaebi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mghynghx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdzrueh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cycvsakv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhxrjud.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeogiyh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkqtotf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqlligk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvovszb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgplisp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adyimqsi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vvogyxfx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dazwvppv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2elzoigmt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhtljsp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gohbakdk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpxnrlx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2quxyhjba.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrcbzvw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2byrtdmdi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2migfnvju.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2umwyasrh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmqyvll.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hedmumjt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vievhfoe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2eruoxfre.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xshqccfz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiaoerr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhrucpe.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2svyplivs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2igkvihty.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmbavrq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzivmwbi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwmufeh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ztonawzv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2amopnaob.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaikaida.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiodxhi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrxodla.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hfadiavd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqandpxt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lorksric.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2khrzweht.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgnasdk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xobgsgzw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrczhzm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfcfsgs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbgvrvu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwctibj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmutkub.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yknqhtnn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dziyvrtz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qzinmqfn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pvapeojz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdpsmqn.html


<!-- 参考信息 -->