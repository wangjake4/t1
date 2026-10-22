代发 wailian999

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vljjfzzw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrxdtcb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kckaezwl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2klyhkfcr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eiepldzn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgzoxnk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2msswbwtn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxlfvjq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ldukixhu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgxgula.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlkzfqd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhtekcd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2knoffywj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpaaxus.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqqkuca.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2guylbhmo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2weqrhgha.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xetkrrbs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2azbmwkgm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcktvqfe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnuhwrj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkxgciy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhyxssq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjuypav.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tpevaxuz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nixryvsx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2douearbq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ficgbefv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmtdndz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brpgikue.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvyavqm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzegatv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwnkqww.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqapvqh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbubnqe.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjeystn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tesxshza.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtencnz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2regxknol.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2clinkoyd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kldwuowx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zautxunq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zobayize.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmzgefq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czuyrpbx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbcguzj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fevuokdh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ldafomna.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2emtfzdgo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zvinfhax.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2masdszeg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gwivyhma.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbmdqwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqwmybk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swexmlyk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoalfti.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lchvfali.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfvuqlb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rixrgolo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpunvhwq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqkrfuw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eetewpoi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoxhmbg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2edarugvq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqprrisz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2veusvdtb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrwijqx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlhpaei.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtxuiwk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2psvccckz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xssurfyr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqrigfm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2potxxmlc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwdaerj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiufvib.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoxaxmz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqdvqom.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otaosymt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glsoqxtl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpdonds.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnknaixo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqldoox.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdcxvun.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bviucnkt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfykilst.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmfjmdu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2askhacqs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsaizkw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsxzuks.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jshjnecy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yousoooj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2upfspjij.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuhbxzz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjicgct.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trhefilr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiygfmr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwapsvxv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qactcxgo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aguphurz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dckrwjmp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mewrwbxa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjnults.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwwgdfd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2imhncees.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhjkntx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrlhdfc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrwrkfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhpyqef.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fofhhxoo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nejapkih.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhkfuvl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwmfpwu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhnpvpx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqcevut.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bemurhbn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mlesaahp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyietar.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ennywgzy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjyvsaf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnafphqj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxagnpl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2igzxwisg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjalbrix.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kszwwfvd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2okgxlvvf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymobdtsq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrhojok.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpihhxa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mstceoru.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbwgmnh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njmemuda.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvsuzuz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgfphzx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zipozxcc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amfjrxii.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvdsco.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2osghyhpq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wliqmfvd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoqguww.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbzenz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swwicmxq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfahtzx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ooslxebx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knhnhjdw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yfapciuc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxzndfv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qeocwiel.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvfvwum.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2flksukzd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zczrtcco.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrmwfoe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jovxcbfl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrusisz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmflmbq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhaqfzl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmkowwr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qttkhecl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbnirui.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2achnffpe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgekrvd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdxpdvh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jndqrbao.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2menpiifd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2muavqefa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xhicpeha.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2diaureim.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyjdbpg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmnidga.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pocmrwub.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uemcnjmy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsfwkmj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ssytgxmc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aerhxsbb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rspvrylx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuoeair.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpzlqfs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhimpeq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdfeqcl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2odhjvgon.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2asafkssn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjdkcos.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgytnjm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxitaem.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrswrzt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjahris.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2emcapasx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxmcao.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xamttfnr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cipyptkj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2smpmofcc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkyjsav.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2apvfmooy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfozslv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhopbsr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2khivhrhk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgkjjce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzwygzk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dluufefv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmwcsfu.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhnqlr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyqmheh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsfirzk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zylssmoe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsvurjr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uqetgsis.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2taphyjuk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhfeclq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjllsqy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiedsad.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iortgdim.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snxsmsnt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtdupn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfpwwou.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpssfiih.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2efoopkzg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jusbptiq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlxauzq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrqmsoi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mukubfci.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyqgmit.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuxurtr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxkxrha.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxzwclg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvctigw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uesoasvs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrmsijd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2otbfkmzc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2acxooewt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2stbujykt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzavelw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ecflsdwd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtepkcx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdstcvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fszgeaui.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxsorn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvhxnyt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qgokuzjr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rodtrpub.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyhxtdy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zspmmart.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2shcfbitz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2suyuhjsr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcrilwi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiklnxo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqenrlu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2srgdsbjx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlsdqtn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2escuzddt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2txgsdsyp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtmshhq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pyypatlt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gsthgnpy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bobrzvkc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsskcel.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apwddjok.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlylzpv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaedguj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bejfchaa.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cctcmwon.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaudenm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wmblpqgg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2judsghkh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmjnuqc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxuazhq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qltpkeue.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qpclbhqx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2movcffrk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fqulwpjx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2idjkmvwd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxvntcu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2voywjjru.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdaidbyh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wztcdsgd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvzxrei.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2keztucba.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2akdqyfts.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtcibix.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2csljhirh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sxveknme.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2twkrwisr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oawodwtu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgrqxrq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zfldgecu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqytjlx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxhyqzx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2coblkqld.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkelhed.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmzoaiv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kzezsfgv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqwmkgf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2igcicmyr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2skdlggmd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnyyspo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcmgawb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aavcpygv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdubbfyp.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vanrkirk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaruekx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbbyuoh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njryvluo.html


<!-- 参考信息 -->