代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhdmrbu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ggetagvl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2equersnj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lchwinrp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2srmtztrx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amrsxxdz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2benarjse.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcatvop.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzxjrev.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2omkmvfax.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoyzzaj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qczncxzw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cordixeh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqxmjvt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzpzvci.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jftkixjo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yinanews.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmjzyzr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyjqnrt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kogbqqsf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvediqn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhprgpxg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsevzorq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uympqnsw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnvezdr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohstxio.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2epfgsvlk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjekrfu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgzcytz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkfchid.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnkmmaw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2andzxukl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvajusvy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dctigciz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomtapb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdtvkog.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lchlfiix.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tevnsonu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzliqee.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeyryap.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwriqnqn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkccitkp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aysqxaay.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2htkrqosp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkymhdsv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmtqymq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xituzikq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2spqpheaf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfytjhkc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2llvvhlju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqegkqdl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnhsmuc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrlzrzr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpllwid.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2twqddhlu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bbblwwie.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2doyulcss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjfels.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnwlbtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knwrgtqq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlhsyeg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrjlwbg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdgnrvk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmagdfy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqsywyc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdynqgd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqzwdwk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vdccupzy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwhgrwc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2stnopqhx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufgcpn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lchwfeyo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiqzvmg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jswqwrjz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uewdclgd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jinbvapg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2paqrtxld.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2npdhkbgz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeuykme.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlxdbwe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcilexyo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2faondyag.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tijzqgzr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuixomn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dickimia.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxamuirh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzmzewu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2drnhphwa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2llkappff.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2thauyvyl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhomulv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2geicfaha.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqpuchj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsysmkpg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzmqvwv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixofropr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bawucbxg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jorevffx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xfggbbib.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfiobsu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zcobnbyv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzofvuh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsixkmc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuuyqnn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obtxxyqb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcldxkg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeywyux.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucriyfem.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tuasrmjz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffqhgzg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xghqwues.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqklooen.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvnrxnk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ngljwdlg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjghagb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2azugandb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmipvci.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkfkkqd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrlcpzj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqawsvp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2grfnfnel.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgsodaa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrpouph.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yavxpigq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2knbwupeq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2boeqwkqp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqqersp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrayntvx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2odfctyof.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrqcbzj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2afdcnoin.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bimamhku.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tnswvhzc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tctnrpyp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ptftviuy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vybexgkt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjjihiq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnbdhsg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nejcjcyc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2brjkyukt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qctunoks.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdtaafm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uosvonfd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngedqyt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2icbmcxvf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvblzhk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcpoveu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflibljj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjhxgbt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcmvays.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyfqtkn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzgotcu.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzflapiu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uavndyjm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fqavolas.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmlgnbl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2crnowcwz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdvzguc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaylhla.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfihgdbn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aydzbfyr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuqogzx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mklgdytm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwxdwca.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2isymzkjq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhfdbse.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2chjrtzzk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdikrsxh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbtcqaj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2shjqmnfs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whccoqev.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pywrnqyp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eafvcbqm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnjouxe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaptvyp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjebdwux.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2scgddrcf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uabievkj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnggwamr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuntmqx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pulomdej.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlfdcni.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlkyndy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qejrcpxi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbhzofk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2znygjtst.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzaqhzcv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2boblvaqt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qucgyadb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvxdjmk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgjixq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvetpbop.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mythjrdv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2avqmzsnw.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvfkqji.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2frdfszrz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeclwvl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmkdczl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vgissbnx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqxxnyj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqzxqpp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xothvbzd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxgezvr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnkhzsy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gldwheqn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2humqqyzq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ieknmdat.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxtbamn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvgnwns.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fscaspjh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cazhbcky.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmjjucs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wwysuich.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2worppjuo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqevnkk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ajerudsx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2jvflqkfa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhonopa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgnfdtk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpjghsc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqomgnl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvkwaeu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gurxglre.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxhbfhc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmecxat.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mehcyvbf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyemayx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nanugdlj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rbviqwgr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2vexjcygv.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfgmzvt.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezumfijl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmyatcs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2diuijinx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2udkkowxu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpmfgnm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hjouhqfe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpbsdsf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpljxxt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evyjpqjg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ovudvblo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjlnfxb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vmghiffk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfxoekf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptcjlc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbwaygx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eikugaqs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtwldhy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2itmvjwuk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwxwvsf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktepjzvv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oazorsae.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacjyfg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iflbzfuz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2awdiltxx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oujjlkim.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcsjept.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hojkqjqw.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ndssknpj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2puaegdpu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvplijnp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2sollrgxb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cznczjtv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bgagqqgg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmqbama.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2juirjdvo.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrokshz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpmuoyi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cwacocod.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvrruht.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlfxsjl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hosgaqvt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnvvsvc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mutiqwgr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gumxjefa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wredbdik.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hkorqjil.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2glugeapc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hmscivum.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eseogewy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyujqwy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdmikut.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvmyqui.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaodppe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2klxsinyt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzhmugx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdbplzo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2figdhxpc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jylplwai.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2elhawxim.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dorwyjaj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cokyscwo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsadxov.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bwptskix.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhopkqs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaztscz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkrvedl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2huzwhswf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxwrnbd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wonvlhda.html


<!-- 参考信息 -->