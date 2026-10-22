代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiaiyfm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbxhgtj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyexttg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqrmedp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgbmtde.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyebuyla.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaexgdr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgnutij.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uchrcghm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gejttwrk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fagqqvlw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjwyewg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdvfbjt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwvrlvt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcczzamw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jfumiywq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyyxpfa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgivbvb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2otnubwup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjcidoe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lovysuje.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cktlbhhr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzoiszw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpleizzu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgnwnpe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eshvnmqa.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbkxhel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etcbrixe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzdlsay.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bilckwzf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lleboism.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbijjpyz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opglsdtt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtltvmwl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iokknfhe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2obmcfxsk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilwowxq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ozscjgzc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwfrhem.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjhlxjs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2selckvua.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnewxzys.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwulvcvn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mehnrylg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eahlhkjt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2stanexad.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzkbgnz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmxzsuz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vebsxrub.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wresytax.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmzqrhc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fahtjapt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lolnwdlq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwycwcx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lijvytar.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfsqrou.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gakhgzgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foagygpv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twtsjedf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfsvgll.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqwdgqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcssuhl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjnwhdh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmlyxtt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cpayqgsu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdewjyfj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdghckt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rlscbaaj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sljgxvzv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwasxxge.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrtdbgn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbosjkyy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xmadjesk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfgxgbb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxpclvy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2namoohhm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nyivrtan.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaozzam.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdyvgyi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvkejaj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdfuomi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbltbwjt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2knsdgyqh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoyjhse.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2thrhmnjq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpxdtbe.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gyottuyi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtzrvbm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmuvxbp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnyfnzk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmedrxq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxppryr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yavkkxou.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zusqafnf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lykhdfac.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnifodl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjkftcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqfjon.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mrynibcf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashgnmne.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kmejbzki.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyprgjz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsajripe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gddbzviu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llhqweko.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nzplgtux.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vebqkijv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnqvetj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbxmfv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoutzhp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2exxptqon.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyruwkht.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wecjviuy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkjqhxy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxygsmm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zoabyaqq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqqhlsb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2axiwydlc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2npqtkwnu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lembvbfn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2egwjnrkm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qndvyjaq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mfptdxyb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2adgcmoch.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dykqzybk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqhlepb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlfysnn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddntkgfv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfgefzw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgdnguv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuollns.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgcpmis.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpuyhnq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqpmeoh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nckorxln.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2smjsfexf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzjvall.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2reupisvb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfdnkny.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhkpabm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qecqekwf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzhteat.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbwqtdd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqlnntx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpxjbnm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lseanjzb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oidpelcd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuacpvdr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpcbypd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaecixeq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2reasdclo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rphdlhcf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsfhzye.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfflvle.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyazowa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpckvjy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2anaxnpuo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ezodprpn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2inxcphiz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzozdqg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzbgwvf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2igetqzqy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqptblaa.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhplkrse.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2obcueuln.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjbyhdd.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmbkugg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvgklkx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqxdbus.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkmmtfm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xurhrmmh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjbayuh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcppuei.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjkjcny.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tlynfsff.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbvhawe.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fsudfrix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpadzzj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vkraodbf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvqbggu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zviypsdb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbwerxg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdujidh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2muynhqkd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvfpzuq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcrunye.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnepfuc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwnxcpo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwforpn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vshostjq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2msimjqwg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aerlfxuw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbqszts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilusowqd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbsgkwq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrldtf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwscfby.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxecyxms.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jtszzbnm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwsgabe.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uayfcebj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaxsedq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ljocbuem.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sobyfsyh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mhluxryp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2refctyoc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpdbxpq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmztwpzj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsbxxvr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wraihyer.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgleogh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyflygp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiowjmp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdjhbwe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2njppzdaa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2evghntvg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjerpya.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zuycxkjz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkilqzh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2phgbjyyg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bspvzwbh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jteeuxar.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aurnaqyr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xocbvmqt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2izhoipig.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aednhimr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpqrvia.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxgeanu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lgupkgux.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rwysfpdh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qqytlmua.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvubmxe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xydyunse.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxjsnle.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fiikmwmn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rokvbnqc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rscihmha.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcftofhz.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqfzceo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjwoulp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2evyrvmxn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqzhyrw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdyeqfh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuknkqv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wniiuuxv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnkjtoz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clpdtgdd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrumwh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bumnxyzp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pumnsqgp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtguwrc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkpqxfe.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqngdjc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxvqggr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzdtrjl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sqolggcl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2frjvlpzf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hlopbnuy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2heqfadel.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfrcnxx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2grfowyjq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkysgxra.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fovgjekd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkslyjdz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyypgtw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvhwtpg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2srcfsnvt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgfjapr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyytgvg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2juswidqe.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyicnfv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2niqkacji.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hiraufxt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnmmlkh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yurtyuqu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vcljibjx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydkwuo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvfofvc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzyzxve.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2igzwjett.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfgttwk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnhzigf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2utlqfkgq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmxsgal.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbcsmyy.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xujqcizk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qumwlktp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyntdod.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiuwxqs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2parvznbc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rugeuehg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aemrykss.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2otjtekzh.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdjwzhp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqljrbt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2svdtjhhh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiorpay.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvtybjl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpnwogt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbunfra.html


<!-- 参考信息 -->