代发 wailian999

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dccvcapo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkdrblq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2oamjvreh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xafyajtg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2adxnzgra.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwdbkli.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwanevi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sbenwrht.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2etmsrhuv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2afzyxccv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxbdyew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjahkpyd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyjsuwl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwibhnfl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiplmvdu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtttxrh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2smedkzve.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpmbzsj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrvwogt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqjixpp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqakxkt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvlvjf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzkmtza.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnbxhga.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpinnxb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttupnoht.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vedisrzv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yideakyf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2reyjgfxa.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhmjyeh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymomqbkw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jchduokg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnqcfnz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgitvxs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbvdtui.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhhcppl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hrudvhgx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wueuxwys.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoetmey.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyjipay.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cokyrhii.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awyjlcqf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvjyvgw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqzfrrt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhyjxfw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oayvuwlf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwindeq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aklyoqph.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxwijvr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrttrgk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcufjjw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2togscimz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpchbmr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnamhgz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohatgwa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqkstlr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2brpjhyxo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgwpaxu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2abzjwkbl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuurzhq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2njmgffan.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwcfugl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qybtwpql.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fwppnpeo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2raugryih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxemlagm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhluacg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgrenhg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuskyvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrxoyxc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkaxnon.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmgqdwi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbegydz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfhbihr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bssctglf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2arxvjkxk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2caztrwfl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpusqgyi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqysuoh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcrgpwm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtyoqkt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnguhwcr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aaogtmjk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgiegtt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jexilvzo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlnjmal.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rogzagkr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpavdsw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2notlnkkb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdbgmiv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgpecek.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzbfayr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inaeysqh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xytouwkc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnbrfqz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cidrumnz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pehijhxy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydttvdan.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmbldko.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxinfaf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gztvketl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuoqgci.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wblffgys.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtxxbnh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gugnvmjj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2feozescl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgjkwbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkweodvn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfaggtk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbeehpb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrvfmro.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xktwtcod.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btqfxyij.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kndhwlqi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lqisushu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zspfhvxi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2crmrymbm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjbacfl.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdvfamz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxsqthv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xbncdegs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvmuzxs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aptvdbmn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvvgqzi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mnklecic.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtyyqxn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xljaaimo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ignqtari.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2autrthoq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dfogufdi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhnhxvw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmkfjis.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgkumtr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2icffxwse.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2evbprmxz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2urlbvmsm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgmlfez.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwybrw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiftmql.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zanxhmqd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2znzghbxb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfwzynf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2svqvsbrq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oclhkuaq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2axpjiuwr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nduphyau.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2axrzieos.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsejefbf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ljymtdrj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kypypvry.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhtuozh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpemawsn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kslpilkw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxefsflh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvnuozf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zakveqcv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkmoaes.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwjhewk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nejhjjvp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2helznisr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpgxdhd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsakrbv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2shdrfcge.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfrquzx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqwfirj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmhcwhi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyilgjb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuqblsd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tflxheck.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2crruufkb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odawxlur.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2evihxcwj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2salcteub.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2apymynuy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rphnbmnq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcjrbov.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkbkjce.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvzwlli.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blpewzft.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otghxkzl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2swzrxmpc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfraoxac.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwzquim.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffmlvm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2annykeym.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdbmtxe.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2roapjlhs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylcknxf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdnozgf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhefmea.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bppgxllu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hshggsxx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvkyekh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsguslf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khnsmzrg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfozyjhn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbiqjdc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oztheqfe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2aywpbvhf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2znerqsmn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2aozxiymn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbimfko.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcfgiyc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotrktp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlyzfzj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxmywgo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzdlpgy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wvayfyxv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkrwjkp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhxwevv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvolltg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwamzjb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxtorjy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilgjsbx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjugzmo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbuxaju.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2otgaikys.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2drtvbdzb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dituujis.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2glfrakes.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2idtatdsi.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2phomujon.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgulnpb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mspnqfno.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mwabzcoz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lsomvqqj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lejmdyth.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bykaneaa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ueacqnbl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnatcbw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zoglvwhj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpwgjvp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsoltgx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgzrouu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqqprud.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2velqvmif.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrvcuj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbxwvup.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iwesnozo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2upjqlonh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvesexja.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kczikyoj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvcqctm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxzhtgu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2igacobha.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwcdygs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aawphdis.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqmzrsw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqnvqpf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyoctpe.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ukicmanp.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqwflaz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmkkjsj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2knjatnja.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvpmprr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjzubnn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2osrbafja.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqplrs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whikdzgn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrjtzwt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fxctrhey.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnyvzqj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwuqagp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvrwwgu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbyavck.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrxgany.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrvtjzx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwqabji.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbnuvky.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcizqthy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yziztfsc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2urhhjjxb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zovrjuyg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncphodfj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2impuhgrf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyowlyj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfiroeu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjihkva.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iysbzkkf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbihvsl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbxqhug.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjwbxbc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqtlyvr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfoqnkh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvmgfpe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihakhvuj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rumnwvvs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkoeace.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2txbhrism.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvmkoim.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2juwdgbpo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxrwzzv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eaduxnlt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2fitkeqrw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kokplfqh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2udyborxl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsagxxz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvqldoj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwcvyim.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxpvizu.html


<!-- 参考信息 -->