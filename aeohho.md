代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsvpyae.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adgozlzg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emhqiohw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpufetfo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvhkkdt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkzkyyl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ppltogyx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nddurtdr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frosqhbm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2famyngrr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uomaxngq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiwdqpj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmfnssq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtytxrc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcglctdn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwhfnar.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rngkapuu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwlsltp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2icaahlpy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfkzvzt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sepjsqkg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukjfbw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfmplwa.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixktaujz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxioaui.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimtzae.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsbgtcv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppukfzup.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqcppvo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbkrsie.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2omxdgacx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ummqkxpp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqrzutp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grlxqshw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkoppel.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xntjqlrn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbshpld.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtxsqxq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzmylun.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjjezfx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwdlnst.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlbwwte.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfkxhob.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2irwzxcbv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdorxnt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfkfzzo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzmisht.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lcujflgf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxfypkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otzxbwap.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwpugjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rujrqjse.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuwuahw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdbagtb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmisuqa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkvqkoh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzgzgux.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbmrkhy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxqubhk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjsqjkh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxcwtrc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhatuzqw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eclyzdqt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ongjdyrd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kohjeqlu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkglzqu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfvuvvb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghestzsj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqezfce.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsouwlac.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prakalta.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2arjvxyre.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ababyzqw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhslraf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2orxjlhas.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfyslay.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2myufkpgo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuiapyq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuxdvxr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdumitls.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvoaqvh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mufdneke.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wafuyyxb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmjzepe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxbxcir.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2maiqdslr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2srqstpfv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjeyoej.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpkyqfk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2maoughqd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uhycgibj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfmmegb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rwobvlhe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2okrcdlla.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmpdyqi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuajoxx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dquihaoq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkzqlx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgopjrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayosjunq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zojooout.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhquqkuo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zskneozm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjmdagx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfyumno.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfanpjo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pjisczpc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkvofge.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pdawuveb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmtrsrv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eampabxm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bginbqri.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eabxtool.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ergogqfe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvpxaia.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pchfsdkt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhyrcvl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2edilrkwd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2omfwjmoe.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewbrutl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcktxfei.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiecked.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2diblhvut.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtpejwu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwmwwsj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ynefywny.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kijpiwnb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2penxcxmz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wiethvft.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vujlbimp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmlgxkx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuxhwrh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lyltzxls.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdhnffo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnjqesn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlglkgma.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjunqbcr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqkcwsh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eruzraly.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bttijryb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwqsxjn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfusjoui.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isuteygr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wubekmvr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxakrjo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkpmpni.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbastin.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfucwwa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaodzqs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlpqgxl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkvmdrq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xchupibn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2keugeqba.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmushfze.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2miawlclz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oywdgsyo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kbworzsr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpgzkkj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2imxjwsnz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2buumgefj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpbwsig.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqldjmzt.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2marsoxww.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2injjawrw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtbhgaz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iogtrrxg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnrqcjs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxoggvmo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxmuivh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgmqlev.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tltzdasy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxxmmem.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2apagttag.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpnlbdu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rvypslze.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxluagre.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rysvfiro.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2msmrojae.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwrysgl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxafgzsk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcbikvg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lemencxu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qnspstba.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrvlhai.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hknwqkis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqlhznd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gseoqroj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvhibsz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvbxijv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmdsyof.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmxdjoc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2chbbiuzf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eruccjcu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wncdwkqo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtagcyw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2spdrqlun.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gkezznny.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqfruzg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeaatwh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxaaess.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpbtcwl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lengevhm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzwzkjh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2spwoheuo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2dauopzhj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2puyfpsxr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcnelcy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fybkjgct.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2volxhdgt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxgjuqw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ybekbnzn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpcrewv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vcibugng.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfkzjfn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rgobgfgs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axokzefq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2aackjmfr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzixovfv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgvhzjw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsjpahr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdymmrh.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rngwdbrb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stypabhb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqflekwv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyvxpbt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2attdpont.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hluxkaes.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lruzypzu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcvzbpb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfhzsqs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvxozeq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrydwgu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecblzwaj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdthfbl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdgkcka.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydvkirm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2npwalvjq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdsxrgn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfnaibb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyatmjql.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uffhbsva.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpbxnze.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhmcqhq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcuptma.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnhrhqv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tplnnkui.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hekybieh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgbpget.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnhenpc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mimvunys.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmixjif.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrsxdtg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmpwpoy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhlmhpw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxhohmv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyfqnoy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxzlhzc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2anodntbu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2enadteuo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rlejrwag.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zicdobas.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vuefwfkc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2brodtqfo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2flxtpogf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yvflfrmh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2usjbutit.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlucpnxs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2plskjqrs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2prohhdjf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lviijtpa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhyiuuc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cibanssy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2duserkfo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdvvbdh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hoerfvxk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfzeeyl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2recgaijn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zevkdbbt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjzlxgo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujnahva.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkvfmbo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpgdnox.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekphksif.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyxianl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfyvcae.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2quhyymvw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrhjhbn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xepsseqn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2krttnvcn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2laznrvfu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvoolko.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcxqqmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnjryko.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfzjyxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfcsiws.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zorcztii.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vixonofs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzwxnoz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqtijif.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsztebh.html


<!-- 参考信息 -->