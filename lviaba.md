代发 wailian999

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkynvgj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllizdef.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dvovrfzs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmjsotu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnntzhk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpcjzoz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrovxvo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqblixvq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxpfcuv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkjacyd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iofsdhlx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2skgyxfjv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vqknqyvy.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbsrpyo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aydimazx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxijfxub.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwidjlg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cshnrxur.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkvseak.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dokbymsr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpquegv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2newihzxh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2chzyjnmr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimcdarp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ljldwkwe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgumlzwj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpsolzf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yddsdpuq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2upabhrom.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rbatlarn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yogrxfqu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkdpfqr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2voifgvoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khubsetc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuqobbk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnysmdm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fyikdurc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wegltffw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpirytm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhyguxr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcvgsdj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuwndet.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwpskgj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kywxqmrc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acwbucbt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyjwcti.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzxepqp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlzhfdl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouudfgdz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2aajhrxmm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmnpib.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onflrylk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2svmgjiqk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxerzqzn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcwusbb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxnnmwb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwgwlsc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxsjwkx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqovxhg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwoddxk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfflkjl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfytvzez.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbbwtrp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftumeagg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpzxfkm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yagxvssf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfohjgkp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjqhpul.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvezxuw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhnlfxc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jntrirey.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjhxoax.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyymped.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoellxv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txhrtknd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwgvigs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2htykjfpg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpfnkfk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wppzohyo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwzcdlf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxfuvve.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmvczpq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhmszpe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bskbswsa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytenyhsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsdtuxe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfalwdnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwfacps.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmljgql.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqfbkjk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jptnemys.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kiopznlx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oibesote.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiwovwe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxtpbbo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2otrywgau.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jsslmcui.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrceovp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2csiqbmdk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2optlamlw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbhqeqi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2javfrucv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wasebtkz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2semjgfhf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxwbfjk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvpjxtc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcirtsn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxgcnqn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaylugn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyyfamb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlcdlab.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eitugron.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhgrmbh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2naguysok.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zswqiyct.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpxurbm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwimpvp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnudwga.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uuscilqi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjfdxms.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuzbymw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrbmnfh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xobhbkbh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdlymuu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rizqbbdn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwvlwoi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkzwsji.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2aulpawle.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eurmhvbt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gazdckvf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pashvvdd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oklafeze.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awugekqc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrkgbgs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwuxhjz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2putadgpz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2szjjdyep.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzidvkfv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bidsyqve.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2klnmtcxf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2irhemgiq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxwmfrj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdzocri.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sldgsyve.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gloqtxzy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwqivsn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oblmgglu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaezzuk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2srrcbiqm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtdrlzy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2quilfjpe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pkukmkxu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcfoksp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2brbgwfxp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpdcqlf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2obqazmro.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwcaalk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpytikjv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xovnwowt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aovhbfjs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtyttnx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnjebec.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2murrdttp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2acavoxud.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyqiydu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsgnhfg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdygwlr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lngfdvwf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqzudgv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2caeydsqp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2aputszrv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyofkvag.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuvwpxr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqusmaa.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gaymrlhl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiaqwhb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xngybpci.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cowffylk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksucyuaa.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2omodvnlx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjbsqii.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnirczg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wuprvlcj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyhigwu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2flokoofw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbodpuz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2enimcige.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiktlmqw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2txlmsvwa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghjnjao.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqznlisj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ripzzhwm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbnfuvb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqmokqm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfvqpve.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtvgiof.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhfkide.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2izjcbcow.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsluqpp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aderysui.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oeagknhf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeepwjfy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gdruimqf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnosmfsm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqhlre.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zoufzony.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dxogsvgy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxykmmk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oowgngdh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2inddktxf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2msuvnzig.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyktoucb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2poldusxu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbdyygz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2grnieoqe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwldpsie.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsiwgbh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvilggl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dhylxqsi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfurymz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jztpqecc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2txegjebu.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpaiqds.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2skkblyjh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2auvvwjtg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhufive.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzcfpxv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wiepurjz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fchaovfz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcssczy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uudcdxps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnquckm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2inauanre.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopdbqpb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfnuytt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlmrozf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jpakyakh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwjssm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2glwdgoho.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yawgxpcq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mlegxaov.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2apykmucu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnffosx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ispglcze.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gxofeptz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zahriohs.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbhqhtb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpxfyso.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkonvhn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uabauejp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgoguia.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaxbmgj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuhkkxk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwajpzhi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmoksqv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeulkfh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xknadtny.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2equvvdzc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mkruobwd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfddyek.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzkoybc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkkwmvn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qygcootv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoszgvl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhgycsh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2igorhwxg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2quktmymf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlawhwv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhvdztg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2trxiqtnv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuaooue.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwalwsm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezizqtgv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2stpzgupz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlecavsx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvwqrjr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjmxsxw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uovwqxtv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2svmawbrk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyfcbie.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpqidvn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2embmcwvm.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsfmtod.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvlcqum.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2foxpjurr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2myvoehdo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwdetol.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnrqefg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vexizkab.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyijgqe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lytcwike.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpohqnfs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2evzdmluo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwegwozk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqfpbfj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqggzhtv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkfetcz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gswzbeoa.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxafcwxa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hytthxzu.html


<!-- 参考信息 -->