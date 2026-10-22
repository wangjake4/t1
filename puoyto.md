代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdgamlp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vipiduny.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rabndmvh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlovkcj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hypwlhgp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpjdilu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2untzlqnt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrnmlco.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2skdlsezi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mesfmomj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrchzau.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhsddyg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaqkzra.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncodebzb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmguxjeq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtfuqiz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2voahmojo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoqwmgn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwiztcc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjadxns.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmohmoyb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gflypqlu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agrgklrk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdieqxe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsjhrla.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfskffdy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zldzdnbc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuvjwgh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fdollgiu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siaemvqo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2izesxkay.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmjpfgf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2caenugiv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijobdabd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbzhrei.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vunofphn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gipaytii.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpziyvsi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umnjmvtt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeuoqfk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkrrsjz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2blmsplbz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvsnvib.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzpkibd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlyzkeh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyctbbq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cardxyvn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jocwzlgs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjlqucs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhslbzw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutjwymu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2flknggru.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkrjhkb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lahqcppa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvceauxl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kummmyfc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2utmzjfom.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaianwu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yafxtyuy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jkssdwzf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmapjftc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrqhmad.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdqbuhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmhuzjc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2febnorlf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpxjjwo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2olyplaya.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nixqmkne.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbcfmyt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkfsqxo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgtamgc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnapnfo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfofwbo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2itjzjugv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2irjjoxui.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2agcbzqdz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvrjvub.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnvnwbp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtruzjxf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqikviq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2thkpjpba.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tknrrenm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdezmck.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pirfwkcf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfkiabe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brshucxj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2csdumrta.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyecdegj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjfzysz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2axsmpynl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiieuzs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwngtii.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xalblnsw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjviraqg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjizsnz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2awfshvon.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tovfiljl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkqbcyx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ioenmejc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjchukr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoxmpco.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpxpjxk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pptvxbpd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zljlygwz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwgcbjy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbmwafu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbnnpuf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsudndlw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrnmqjv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmlulrv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2baaxyftr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2snascojs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pzutmtgn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhawjgot.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zefrdydq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvcjuiv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsnbnsu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qnylvpqd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gtledryb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2msrmmnat.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjhiwhl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtcjrtm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsqcflr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2imtadayj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdpijwo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmcvobk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2amtihrbg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zttcytzg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bowwmcuf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhveunv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpojlsin.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfykvivo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xolbszcg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pirdhuwj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jatnycwx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2evqoornw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2btsnbseb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyoftdl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vatdamal.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwxqlx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnrindg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmscvihl.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxojhre.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnombst.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpvatnm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cditruah.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmmfkuk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mccgibff.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsqhrdi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkygrvdp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsirlvp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2womuncfa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvwwvcu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxnzfii.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuitlxu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2orybfjmj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znytkzeb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gypdnhmz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfjukak.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdmuomn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqcekbb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pradnivd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrutjwk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmthswak.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrohava.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvubhnf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2buqjopqc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekvoxrc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cuazkwqk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2spboftyu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgypayp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdcvpai.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2harrzprm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiilztr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2evslwcgb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yulhvkst.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrnstxd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thvwmiue.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxdhuag.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eunrpkyl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlelmmm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzmzpxb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ximdxzsg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2clhdaoru.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwjklil.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cebmgboo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzsxtyw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwymjol.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eethwvrc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2byafljru.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfezlrz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcybzut.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnuwoei.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vunmfnls.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvxvtct.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwcyemw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoiakys.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qimacfqq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfogalk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvizvlt.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sujgsdke.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fggynxiy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbufrbgn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgngqng.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fufwacsz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2atocokqj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2egryonao.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxqulco.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhkotwv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqgvmjm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwxpviv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pidwmaab.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wnajoxvj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zghtyyrq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mtduskzy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcomgzg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2taauxwsu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tadfxltv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ybseyifm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtaxmtb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmahswt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcbtjjf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhhjuoy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ugksboty.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2chqqufkg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxdirkf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xkddocag.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2shbzqtrq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yihveqha.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eehvyzvd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hxywyznc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bttwdjod.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnkzvzn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2prmhmjlf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwvbscx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdatnal.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrfrxia.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2snkyiemr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qsndzxrl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaxqcsl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcpykxm.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlbbsmu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xttzxetz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bklgvbar.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvoombs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fequxzow.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mklgwfra.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqikzfmq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clsbmsjy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2iimxcorw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqtepwa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwowxtd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2oxepymoc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjbdopx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwskvaf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtpmdxj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmdbsne.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxwxinh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbdjrio.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gklfbthw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxbuzgx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qplflohd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsembrk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2upszjqbd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idixdugq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpmtezu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vvothfwt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjdaunj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtvboup.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmrbcsm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkbgqwx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irwxahge.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qbngssun.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcoiujq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tgygpmqh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2plylpwrg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yggypega.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jydwywtj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbnrixz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxqhbgd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wcebqicr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vslffnoa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnyzqsu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mdewfgwm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpjzztf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lswbrbfx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2scpnnryt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkithsei.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjhvuna.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2czgajsfh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzwwtyp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdppxqdk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fsactqzr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kruunjmy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcloeup.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtysagm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsypski.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpyjxsq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2egwwqqxx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ocudrdsq.html


<!-- 参考信息 -->