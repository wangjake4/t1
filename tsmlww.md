代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtarppbvrc.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdaowlxz.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtgtsukkid.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtjgtkogfr.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtwobcbtqp.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtqqnpxcul.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gtpskfoqeu.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gttauxeity.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtcwecwfat.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtedaukjih.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtorxskhdi.html

[S56] C++：optional
来源：http://dali.zhengqikj.top/Article/details/gtvywmgifs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzmcaxelq.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtrwlvnand.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gteqykouhj.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyssnrgk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtyadwqvqq.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gtazybjirl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtsblndwva.html

[S60] C++：遍历并删除元素
来源：http://dali.haohaochexian.top/Article/details/gtyaqhxdfg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtlttvkigh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtvdxhnmsf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtdkftfokd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtryhvxoxy.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtidcwrfwq.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtucvxrfmm.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gtgtkzjklx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtjdzsteew.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gtislqsjcr.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtjvrlfgvz.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gttymbqgdb.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkejkjmu.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtrwudckdf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtalfwnesh.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtjcnmsteq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtzvwywgje.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtzhtgzupw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gtekheogzy.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtekorfrzv.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtnvbmewcd.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtnbaclkki.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtdwaxxgfx.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtijhluzqt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtkcwgcmty.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtlnqlblcf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtummkohhg.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtnomagixx.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtmemkfmph.html

[T13] Kotlin：只读 Map
来源：http://dali.haohaochexian.top/Article/details/gtphhcijxh.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhfwskuz.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtxepeoynm.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtlolcezyh.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtuestpraw.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtauypnbbz.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtqbmzgsep.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtfprqcmsz.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtxqepnxyt.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gttchjniqn.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtvfszcdji.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtjwmmprgv.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gtljvnnuos.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtsrykskpg.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtcrpjkuqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtzzwxnvwo.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gtoejtigoc.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtrdsraebe.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gtlzoitkkh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtkzlraxly.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gttmmzyizx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtgygptjge.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtdwsxvwsw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtzofqkmtj.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtopdxqhra.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gtggxmgfcf.html

[T26] Swift：类与重写
来源：http://dali.havefunace.top/Article/details/gttuvgwznd.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtcgzpktuq.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpgcdyrm.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gtoawbxshx.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtuxwbviex.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtxxgsntem.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gtlnghofxe.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtkiprgqju.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtonylfepx.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtjoqcosdk.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gtgfwouqeh.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtafckzfsd.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlsvekbev.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtzdsefmnc.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtoyijkryf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.smart0.xyz/Article/details/gturybzdkx.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtdypheigc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtgimshnjz.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtrlgaiggb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtmadiqaie.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gtzqassacj.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gtjvfrtrcf.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjowxejdn.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gtjzsmqvyj.html

[T38] Lua：条件
来源：http://dali.yangfankeji.com/Article/details/gtvnonavag.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtbqjwinuu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtmuwprhlz.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtrykmksic.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtmekabsta.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtylloipux.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtzvfiifft.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtwezufkdr.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtwjlpcqgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtanvseqhj.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtdjqdbvgj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtfgfuztjk.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gtrcfzolxy.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtegnelhpt.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtclpujszn.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gtsvcnjmxc.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtqwaniwnw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsliaxky.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gtqemrenpu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258.top/Article/details/gtzhycfkig.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gtwfybpmxs.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtttcwnjek.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtjduevhuo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtzcthotet.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtclwjpwfy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtbmpuvgnc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtrbjqfyqv.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtggdpulkv.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtfpgpuorc.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtdadoyzqg.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gtvrxvuopq.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gtqnxbkkcg.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtscsptxox.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtgymjjfpm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gtlfggnvgy.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtgfuxjlcd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtdnasbsvc.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gtygfcqqsb.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtyttlszii.html

[T57] Scala：模式匹配
来源：http://dali.meibo888.top/Article/details/gtudbfviak.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtlcwxafcj.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtqdjwtyoi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxhxzmkz.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gtjhoyiamp.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtyswtrogh.html

[T60] Scala：折叠
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhkanoxc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtgdcbzphw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfouorpmp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtulfhxewr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvqidmkqb.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gtvwrcascb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guowangkeji.top/Article/details/gtuqlkxftw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuxming.cn/Article/details/gtvlzsrizo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkjnsogq.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gtajhgosmx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gtyuzsmflt.html

[U04] Py：变量调试打印
来源：http://dali.cucudq.cn/Article/details/gtgmwwdosu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtzzdntrmb.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtokmhpddc.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtojlxxgvp.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtpntipkif.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gtemcrwtey.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtlrmqoyek.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtyrpgczjk.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeykpjkp.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gtywjjrddj.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gtueuraijv.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtovsibtyp.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtfvwdyfmt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtbtydsjmq.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gttpleymku.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtpxknpmbc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gtgxpiiihs.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gteqqchzrz.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gthwdhostc.html

deque(maxlen=10)
来源：http://dali.meibo888.top/Article/details/gtujtyqueq.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gtwivzlaif.html

defaultdict(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtocyhalma.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtdhcpbslm.html

t = time.perf_counter()
来源：http://dali.gzhubu.top/Article/details/gtmmktvmfx.html

[U16] Py：命令行参数解析
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaxvsisw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtbxflkbas.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtzjznpfmy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.bjfxy.top/Article/details/gtvpixiczc.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkxdhoqj.html

pat = re.compile(r"\d+")
来源：http://dali.yj202588.top/Article/details/gtitscqvnv.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtmbxepacj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gtchlgdiym.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gthmbhdwfs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cucudq.cn/Article/details/gtvazdzjvb.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gthyzjlxjt.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtaanvouoy.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtuzzuyxur.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gtyvtorkus.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gtpslgydsj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gtpkkoouey.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gtriccobqa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtfvxatmcf.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtebufeoqw.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtrgbnmbds.html

[U26] Py：并发下载
来源：http://dali.fengsongda.top/Article/details/gtnytnddjs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gtudwhnwyj.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gtrxtuxlel.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gthmdbmkvl.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtgyomwgiy.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtrmwrmncu.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtokwmfrle.html

@property 与 @x.setter 配合
来源：http://dali.sufxvd.cn/Article/details/gtnivsdkcv.html

[U30] Py：数据类
来源：http://dali.cucudq.cn/Article/details/gtkvmrgstp.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtjguyjugj.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gtwspxrxty.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtomzwymue.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gtjjwochwi.html

ruff format . && ruff check --fix .
来源：http://dali.aibaodan.cn/Article/details/gthgobbukv.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtioasupao.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtsqibbwmh.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtqcajfqxp.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtzdjmfbnc.html

[U35] Py：发送邮件
来源：http://dali.birdmap.top/Article/details/gtfeijdwaw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ivvv.top/Article/details/gtgmqvfndy.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtgmmikpvt.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gtctuszgxa.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtlthbgyxm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gtyidlyrwk.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtnbijwhqx.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoxfghqs.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gtwsqfwito.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gtzcmootlv.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gtdzwiicti.html

print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtrsnfstcb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gtyfsdwwve.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.feifeiyinyue.top/Article/details/gtcocgmbfb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywhdhgrn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hywenlv.cn/Article/details/gtotmnzefo.html

[U43] PHP：声明命名空间
来源：http://dali.jqgufenzy.top/Article/details/gteiqrjmvw.html

namespace App\Http;
来源：http://dali.andypj.xyz/Article/details/gthdnreoic.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gtejhostxs.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtmgtpihib.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gtndecjoii.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtrhdzdkct.html

[U46] PHP：可空类型
来源：http://dali.daxiang520.top/Article/details/gtuglssdkt.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gtrbkbtktn.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gtxbkmkxrl.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gtwsrenbbi.html

[U48] PHP：纯枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtjixhxuuy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gtlfqfpdmy.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gtyfwfqstm.html

public readonly string $name
来源：http://dali.cdnleiting.top/Article/details/gtwwtqkriq.html

[U50] PHP：构造器属性提升
来源：http://dali.iojbl.cn/Article/details/gtxghdzcze.html

public function __construct(private int $id) {}
来源：http://dali.guannengcc.top/Article/details/gtgmyeftww.html

[U51] PHP：数组解构
来源：http://dali.bjfxy.top/Article/details/gtoqygfquu.html

[$a, $b] = $arr;
来源：http://dali.hnqzz.top/Article/details/gtmwcpndzs.html

[U52] PHP：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gtulonutle.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gtkafvqmim.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gtpptdvcno.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gtftqwbjmm.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gtvrpyskhq.html

$obj?->method()
来源：http://dali.wangdashe.top/Article/details/gtjyzmusik.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gtpmsbswfk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtchgqbhvt.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gtqjfrrmle.html

f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtbtakrkmp.html

[U57] PHP：字符串插值
来源：http://dali.cashguo.top/Article/details/gtlzomxngx.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtjijuarnw.html

[U58] PHP：数组三件套
来源：http://dali.pycfn.com/Article/details/gtyciemijw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtznqocyge.html

[U59] PHP：自定义排序
来源：http://dali.gzhubu.top/Article/details/gtfkyreakf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gteikoowva.html

[U60] PHP：JSON 编解码
来源：http://dali.pengpengdd.cyou/Article/details/gtztrlqstc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yuanzhike.top/Article/details/gtnqcydhpf.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtvefwcnhm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtqbbdzgmz.html

[U62] PHP：日期对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtztlwdgme.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yvedp.cn/Article/details/gtyawnhitw.html

[U63] PHP：文件读写
来源：http://dali.zhiwuduotai.top/Article/details/gthytierby.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gteuwarekh.html

[U64] PHP：目录遍历
来源：http://dali.zhengqikj.top/Article/details/gthrobchpm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dianchejie.cn/Article/details/gtvbbxsbfq.html

[U65] PHP：会话
来源：http://dali.xuanzx.com/Article/details/gttwvqaafx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtyeklakkd.html

[U66] PHP：设置 Cookie
来源：http://dali.c1oappe.top/Article/details/gtatyfjucs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gtycikferm.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gtrbbpkhgc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258888.top/Article/details/gtgrtxvulz.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuliftefu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sufxvd.cn/Article/details/gtfimbwpfg.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gttsttkzzi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gtsfjmpztu.html

[U70] PHP：PDO 事务
来源：http://dali.cheryme.top/Article/details/gtwnqxqnvj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.vqdsnc.cn/Article/details/gtkdcwihjr.html

[U71] PHP：抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gttpcjgyeh.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gteuhcponp.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtvejafcee.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xinyue.icu/Article/details/gtsfxujaxh.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtddzyqqaw.html

parse_ini_file("config.ini", true)
来源：http://dali.jqgfzy.top/Article/details/gtegudemoe.html

[U74] PHP：读取环境变量
来源：http://dali.cheryme.top/Article/details/gtmmzgynqp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.aibaodan.cn/Article/details/gtgvhofnyl.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gtriwfazxw.html

composer require psr/container
来源：http://dali.havefunace.top/Article/details/gtcykttsqg.html

[U76] PHP：简单路由
来源：http://dali.sxryk.cn/Article/details/gtomlovrvh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sufxvd.cn/Article/details/gtsadvwhkc.html


<!-- 参考信息 -->