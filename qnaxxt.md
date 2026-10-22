代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhfpyju.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vprqkejo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrwtddj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eefceebr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkuykeq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnpytvt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhjnoln.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgdwhvh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dgebcrly.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzglyyu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvzucli.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxzemrq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vflkxmmt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnloqej.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxruoozx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eojcbgch.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stxvhvyk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qobjbtkp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2trsxihbc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2djtscklt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2msvpqosh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwatzge.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjftelk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhhrslq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwntbl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefibhyf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrgbafj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2perjrabr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2opmnfpxm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drnjtqtn.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmynjbcq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqtmsal.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkphyffw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hagvzfyt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaejrjr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqpgwgl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxoliqk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkawahqf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecawkdjt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcateqip.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gahbcpgl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcwlovn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzuprep.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gzplsfyh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvghakzj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2slnjgine.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwrobay.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzkbvut.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjqacxv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwnolbx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aolszjnj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjkmtbp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ojraarpe.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsoygjg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeeqmtc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2srrfaxac.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2thyjwodh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znzvrxmq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2angdruum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyncjmie.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxlvvyx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xipwnjrk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwygmud.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lidhktoa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzcunlq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwottszi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbmtgeq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuemdzd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbxxhbl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvsjxcd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtnzxki.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2anhsgkzi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvwiarj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hribaddj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gafmeoay.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmkfrsj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2smsqgece.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vimlsycq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxizfdz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hruihoyf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pghzwnqe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtltutiy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ehucjacc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyofvvw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxyofxz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuxmfov.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvskswr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuapdfi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqalnua.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhxizic.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xigpnjof.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjwfgco.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xteswzos.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2usneoqcx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpnvgww.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fssmsyea.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aebrrqhe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bssckqxo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eqloztfq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2oehwzdlw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lmujlieh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mcexxvwg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2auqzlcgf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdvdryr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyyvvmf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtjcsvt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiekumw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjozntqa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2okjiyzxu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bocjjywb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mwefpuam.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhgpkss.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2noeayvlr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ngikkzob.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtzuzbo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxrakga.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmnquof.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ofackaan.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2icoaylxd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvghrsct.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2apjabxdz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oupxhqbr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rlimoxxp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rurwongn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbkdwlb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwezgvln.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2evwnhpvu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdflhewu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnsfaea.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jayrjejx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyahhfq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuowluz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuzmviq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvuimum.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbhhocq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmmydmo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eaomqlqf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzxdgxu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fadharao.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkzwtea.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pipzpjea.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2axuzbedn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vujxdgsa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhynlui.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfkpegt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2idgfmklh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shueamgr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvhldmn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pskixbgi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klcvewnj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeezkex.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsshwnb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfescpq.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2idnulmoa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbqcyyb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcptzli.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pgevscde.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxklrxf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvvzguh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmamfnnj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnonush.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2momfjdeq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bffpdpwc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvktpjaw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzjmbyn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeolwgc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlphbjin.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkxyvyu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2anilyyml.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtabbhis.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2icxcktqq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdjxkls.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfxbazh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2znwtqehy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgxiddo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeosrtb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mphkeojp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjlyapp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oygzutwf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qusqyncr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfhbarf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpmjhoh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzhxqwj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ultexrkf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ziieiwmd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fownormi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgcdjvw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwzzdwj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2szyzeazs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaqfeav.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbslvrb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2anrvekzj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qohxthbs.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2szfccsih.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjhirzl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrhluco.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dxckxigu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2khhwwryj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vpszaprk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2axackexs.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsoyujm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsbabix.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zatqiqby.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxjmfty.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ausfnguf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhhraun.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zffjcxis.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsiqgjm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2emtejtyx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoudrfe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrhumbg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbijmvcr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2myswrimp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxjgqga.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyqcrrv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2naheeqhq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzmmpqm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeldvct.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cvimplif.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgzangm.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjzvosb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpnnqoa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vdakvzgc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjusrrqz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqzdjak.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2begfkema.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2esqisirc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbrbwtp.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dcchybfj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2msipqvrg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2efedbaei.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yokallxf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcnrmwt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwicjizc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvrmrhn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvezunm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqxfodh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2hoizoqel.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sohqjmul.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoykzvh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaafwtv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sjayldmo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ipicgzbz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfecwwh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfohskh.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lliqibzy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnxrrtd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhnhmhd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrpznv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nldwjvka.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whbheyzf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmlmmyy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cvovdcgs.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2imodwojy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzpjmqx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2abtfieuo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzvrzkw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rpssragz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2unhemhmx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcvidkp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2onwelmjj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hikghuns.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kyskcllu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzdqiwa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2scsvvlpi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eivgnkyl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkpiinw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jivbsprl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2imlzdewc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfzmjwb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbgfygv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2inxbasns.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2keirmkpy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2atjxyezv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tveuqhsc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yskgvkei.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaeoqzh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmtwriv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nfagkoew.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2asofhkmh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbhpezz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2msupuadd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xakaxulj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rizwhpxx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wkziogcu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmikzzf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbwzpkv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeyccli.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jjugpgpr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjbelae.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2goikiqmu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mntgohxc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qabtyirm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2seitfuen.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2efjsbejt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2umqslksk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2elppulcy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdggqdx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mycnmbnn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mdesapyr.html


<!-- 参考信息 -->