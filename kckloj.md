代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbmgfan.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2odtbopyr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqljpa.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stdibkxc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfxfgid.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eavrcays.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuqwvtv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2batsazxh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxbsuwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbpcojz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdjwkpr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvimuauf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hawvsceg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeybqvqd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcntiuzt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kytxcrfn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbsigis.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqkyrhp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtlvwnr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzsdstk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlscaqeq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfobooqu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xletctue.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaafxvh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvqfvyl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nytoqpoi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhbeeea.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yysnxrop.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgqbogc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnexbodv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqxebxf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbrzoum.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcofhqk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itgadnxx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtotjcz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2muyoooxi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfnbfuy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqojaxyu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeszynra.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxmwmmh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqgblof.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2centkatd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrsfbfb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dstqhnzl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owlnoltj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2znidcezr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkgpmil.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dektwtfa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsbvayl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jvngkccy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxngfrv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2msmcliwk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2skzguupe.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2issetmbm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kipivtrw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aspxcnmf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2btmsfeje.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqtynhk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipywtvdv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2arnwxjbl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rplhyjoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgtuwdh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2celwaoxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsahyqd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2egqnklzz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxcomvp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2umdzpagy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lypoiwhk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gldgsktk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwixtbjk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkmfljr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzvpddt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zksamvvi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iahwqjgq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pydglycv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2scjefdtz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvkvbcg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vysdbkwa.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsgsaeu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2puflwtlv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fwufjdxn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvguntw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2veexurxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jucbezbl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kluyohol.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczqkjnp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fzalpxbb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2puydlley.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdqfptd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoggxuq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhgyvok.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnpmitb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmnqlha.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjujnrbb.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oelgcwkt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiwoujg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyfcaco.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjltgcm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuzzxjd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmqyuio.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqddbxg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujftxgzu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hpslnfka.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2khxxqenp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2aswfsvso.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kthohztm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2tiulkyzk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxznaowq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szvghumr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gascsght.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoklkux.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuickpc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yasdhivk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrryqaq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ympzdqhc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeuzukd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqzcojc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjctjcs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xnklpino.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkuckvc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wbghxbzg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtkadda.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2opwjlsgw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycudgiwf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoqncyw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmwxqre.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2teesoqts.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yhysoaxt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2axaurfnn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2whpfdjeb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnzxowr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxuzhus.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wceazdik.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2istsiukp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2unpnkgoy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmalmhp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnfplym.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsmfpux.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfqluow.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xzybbfky.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2flwbupgm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwwegf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnxzvwa.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzvvxka.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjfryii.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2odchaeuu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rurensru.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2abmvilut.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vddovmlw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcftsmh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whiergxs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iayevupf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcxlahk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvjbrjx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oriurfsq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfwyfed.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlryeug.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwfmwtg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2myhckswv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbljsit.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fgksnnoi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbmgibi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcwfprz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpslizx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2olbneaea.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuleyzr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhbnmka.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwgroka.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxdibke.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqunlypm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2akgczptt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlbwdui.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tciewihs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2qaozuryn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjwytwh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzsphdv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrfijec.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbtqnpq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwyitkr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjhdrqi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vknbouma.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kibiltnv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftlubv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiqdezp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgcvygo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2alprhscf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgkahha.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiumlfrt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wenckiks.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaboxrfk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmudsxgs.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tubyyznm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2spczrgnu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvrfad.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oyekrsre.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhzxzlo.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cwulmbxk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzakevc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgpzvdj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bgltgryg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzktyyt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqkcxeo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2itnolezx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcorzuk.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyntbrs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqqakdz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cqybmqgc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2isxcafby.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbpztea.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxvahvf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziueibzq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvifswqh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsbunfy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmkgovm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2brnozjnp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgruwvjt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wuoscams.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwozxmz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqfntaa.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2smoexqzx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ixueuoqr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpdgqzj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hlszaugt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxagkhj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gybrgjyj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qefarerx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rdepwihv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtzxerb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvaouzd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlzpdjz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2redlognb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuxgjoo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzngqbl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wjidlgmp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2geneuafm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zohzjxcc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpagjmc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiutvezm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzvwbin.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sikdweag.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lafayuyo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2twlpavgy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmkegtv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vinewanp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cozarbja.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiogoko.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhlcexd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkaukfg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxftktoz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xriegesj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdnwelb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2btzhfujs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcrsqal.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmoeygj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rjazskic.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dedoqwiq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpazoan.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wefwmqnz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbqpwbj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2forgyydt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpbckzx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2syegujks.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsfynge.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejiaivc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mopoqwxw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2mswicpmz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgxdmhe.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqntfud.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvgvhtd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssizmjuj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvofuca.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dytdfmbr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2agmcjnnr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwtnyhy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwzlwxj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pevngtro.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cpryqyhw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2osxehwgk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kskpxjrq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuvkdas.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsdcojj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjygaoic.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2scylhdlh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhbamfv.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2stycsoaj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aagaycaz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gawyyroo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmgnrmo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mwofekwz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrnhtap.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2urgyjrxe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzicvkbu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2huxkbkan.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkbenmw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqpyscg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zewkakae.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tikgxzzr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tfopawbh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqebmbp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqvdhpc.html


<!-- 参考信息 -->