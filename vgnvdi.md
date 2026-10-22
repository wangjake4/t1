代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtjbtdpngf.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtoeexbqnr.html

static_cast<double>(a) / b
来源：http://dali.yueranfly.top/Article/details/gtntcqfoey.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtwooenktw.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtoezfeojh.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtyqnpputl.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtvczeycdg.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtpkhsqyir.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gteydjroqr.html

[S55] C++：结构化绑定
来源：http://dali.fzhhl.top/Article/details/gtrqyvwlhd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gtlrqlsivb.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtjnqphfgi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gttohxwygt.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtzgkmnelp.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtxcqvhsvf.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtpfrjoiny.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxursnhn.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtnpvcnpwr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gteuxrcygl.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtumnkcyue.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtxtdxzyqy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdkgankfl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gtxybtubxt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxcwnlhnj.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtpxsqavmg.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtlbpxdvbm.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gttowjtide.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtbmknenfq.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtpdxikjnc.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtvoehggvm.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gtquirnvwc.html

val n: String? = null;  n?.length
来源：http://dali.yj202588.top/Article/details/gtfpmzvezb.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtxvefvznz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gtyguldgbq.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtophuwnzl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtidjlwxak.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtqcbmyovz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtbygczjix.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtwaxwlkgc.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtqqclqiiw.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtzlteuhgi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gteeoljukb.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtwiesfnct.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gtlpydhddh.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gtqbwsgjrh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtznscrpad.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtnugwygwq.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtezntfbaz.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gtthvtsosc.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmydydkty.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtpcjtczpv.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtrwqvxmgs.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotnucrft.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtedxnqtlk.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gttykcudwo.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtcqcavudn.html

[T17] Swift：变量与常量
来源：http://dali.svipenyu.cn/Article/details/gttjirggpx.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtgczahlcq.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtywnihxus.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gtjxbcievm.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtssgcuohs.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtkqqxzkid.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtgoprzyqx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtnzzsxksd.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtljthljkm.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtuuxrahny.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtoswtshap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtwkpfgogk.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtiyxqicjx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtkwhxskhw.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtymmehukx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtwxovhipf.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtjeffthah.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtgrpqfkqv.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtwciwxjqi.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqybojnum.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtbxcpulum.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gtcigztvpr.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelfdokjm.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gthoqiegtz.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtbojgthhu.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtyrqyrngn.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtdyubmkhb.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtasedxaia.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gthotgxiou.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtvylrsotg.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtquhveiqg.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtypsjtzwu.html

[T33] Lua：表（数组）
来源：http://dali.cheryme.top/Article/details/gtbrwthpbm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gtwrmtsxvo.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtaytuicbo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtaqeyexpv.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtmrrxaqer.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtqctolvmr.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtkwozywmh.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtvvcmyeyv.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtyktqeuzk.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtzbiwdlrx.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtmzzjzesy.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtolijnlck.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtkimutotl.html

string.find(s, "%d+")
来源：http://dali.hnqzz.top/Article/details/gtqvqecmxf.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtzubhssoh.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gtgdijeysa.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtyubnfouw.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gtxmhhxkjf.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtjycijgxm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtrpnfdkxp.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtplmltggb.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtndyjcaxv.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtilwuwvar.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjcnlipz.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtvpwacycn.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gthmeravtj.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnqmdnhd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtxjfueczm.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtczoytukl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gtkecrfsfr.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtvbmxandy.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtyzcmnmkh.html

[T49] Perl：函数
来源：http://dali.hysaishi.cn/Article/details/gtceymduhe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtxpvhzrzo.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtrtrxyhxr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtbaniqctr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdantrwbz.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtyqakrltc.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtblkjkleg.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtannsegob.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtltizncpw.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtranboacb.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtoekzrllo.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtzetgmvbh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtvopfgnqg.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtyfoluzek.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gtzymlwwal.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtotfecvxt.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtzhnvrvld.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtofdqfbav.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtusisfwhk.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtnqqydmjs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gtfmlmbydr.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtcysutypz.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtyeftqodo.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gtnrmsqscx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cdnleiting.top/Article/details/gtabmwvorc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbhmxkxrg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtijyklgqg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdjbvpavp.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtkyhihkqb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gthxfimufx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtklxhzphl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtfwpnsbcy.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtzhpkdcsg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenlongwang.top/Article/details/gtzqjtiutz.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gtgevjndtn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gtvimvnjqy.html

[U05] Py：列表去重且保序
来源：http://dali.tanke756.top/Article/details/gtdvjnvupx.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtsjzszros.html

[U06] Py：合并两个字典
来源：http://dali.kuanghao11.cn/Article/details/gtywylwoin.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtrodpquzk.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gttgxphpsp.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtbmrqvwqp.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gtkidjlefs.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtykfzqtnx.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtppxopftb.html

max(d, key=d.get)
来源：http://dali.jyoumei.cn/Article/details/gthxfgalrc.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtupchydgr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtcwewkhnl.html

[U11] Py：生成器表达式
来源：http://dali.tianlin.xyz/Article/details/gtnzitrkvn.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtwscihzln.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwqbhyrf.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtuhnncsdz.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtthrjhovd.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtdiqheaht.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gtezgksouh.html

defaultdict(list)
来源：http://dali.sysykeji.top/Article/details/gtmwgklyvl.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gtpziydppl.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtebwakgfp.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtomxylhqs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gtdxibzknt.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtfittosld.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gtzeoxgpic.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gtmoasggyq.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtfihdinia.html

[U19] Py：正则替换带回调
来源：http://dali.snrcjt.cn/Article/details/gtwyaraffz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtcdwdlrfg.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gtdfehrorc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gtpcgxsmak.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gtszkpcdrv.html

@contextlib.contextmanager
来源：http://dali.ivvv.top/Article/details/gtvquhsalm.html

[U22] Py：矩阵转置
来源：http://dali.wangdashe.top/Article/details/gtymmqftsg.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtqfirkxrb.html

[U23] Py：分块读取大文件
来源：http://dali.cqqwz.cn/Article/details/gtnjshtzqi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gtknbenord.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtxpxmsxki.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtjeaoqpsx.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtnbvjauyd.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtisqliqhd.html

[U26] Py：并发下载
来源：http://dali.meibo888.top/Article/details/gtyhoufcek.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuetiantiany.cn/Article/details/gtejmooani.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtzcuzoqyn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gtjyrjqjsr.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtqntmuaey.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtkcagdssb.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gtdxtycdwt.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtrgoesdsx.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gtqhugnesa.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gtdkhtihhs.html

[U31] Py：单测
来源：http://dali.yanxiufei.cn/Article/details/gtstimqhsm.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gteczyyrws.html

[U32] Py：代码格式化
来源：http://dali.jyoumei.cn/Article/details/gtmyvvkjzc.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpblsxjc.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeqlnysc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtjzhhdexu.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gtzovflome.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtapgtdtqa.html

[U35] Py：发送邮件
来源：http://dali.redwolf501.top/Article/details/gtybexonwe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtctenplqh.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtkgymnpdj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtvoqsjbxl.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gtfvbypfzd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fengsongda.top/Article/details/gtsoeniyvv.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gtcxsrewby.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gtlllzgstv.html

[U39] Py：判断是否在交互环境
来源：http://dali.cashguo.top/Article/details/gtknqndrxl.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtqzofmjzm.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gtztrvkcyl.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtfiuzaitp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ivvv.top/Article/details/gthcockmhz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.birdmap.top/Article/details/gtjapymknv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yanxiufei.cn/Article/details/gturjuqvxm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfkxarrh.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gtgnsfoqyo.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gtvmtxrkol.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gtmeetudkk.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtduzmqtsj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtnjbsnkwe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gticotufqp.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gtuodqyjgl.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gtwcrhpabj.html

[U47] PHP：联合类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqrtrswyc.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gttabfkwkd.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtjsislyvq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gtbdfbhqhy.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbniiswug.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gtbslaamwp.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtubtakojz.html

public function __construct(private int $id) {}
来源：http://dali.yangfankeji.com/Article/details/gtfragoawu.html

[U51] PHP：数组解构
来源：http://dali.chenlongwang.top/Article/details/gtqfqrpudp.html

[$a, $b] = $arr;
来源：http://dali.meibo888.top/Article/details/gtnsfhwwdc.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtjsouawyc.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gtlgvonpqm.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtrbxeddqg.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtgxsqzdry.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gtjrvxtnba.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gtihknetyj.html

[U55] PHP：match 表达式
来源：http://dali.yj20258888.top/Article/details/gtcrkcizpx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gtzpewnbvu.html

[U56] PHP：命名参数
来源：http://dali.yuxming.cn/Article/details/gtzyfphhqs.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtvsjmenec.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtqwttjqhb.html

"值: {$a}"
来源：http://dali.pengpengdd.cyou/Article/details/gtklekjtkc.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gtjdrxahkb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yangfankeji.com/Article/details/gtzzqgnrmu.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gtkuynfvjb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtiytdqson.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258888.top/Article/details/gtguzookti.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtogzbwiyz.html

[U61] PHP：正则
来源：http://dali.xylfe.cn/Article/details/gtehalmwio.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtfvyczecb.html

[U62] PHP：日期对象
来源：http://dali.yongpay.top/Article/details/gtlrnfxlry.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtdjuvnljd.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gtwqsuizxq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jianghu66.top/Article/details/gtyvstnxik.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gthgmhjlty.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.quarkkingdee.top/Article/details/gtoozwafni.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtgglendyt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtatjnmtre.html

[U66] PHP：设置 Cookie
来源：http://dali.guannengcc.top/Article/details/gtfletnvgo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtpqaawxqo.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gtmbusbrky.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gtgxitceos.html

[U68] PHP：PDO 连接
来源：http://dali.mhx1999.top/Article/details/gtiqtsorob.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ppjwa.cn/Article/details/gticsjokvx.html

[U69] PHP：PDO 预处理
来源：http://dali.cheryme.top/Article/details/gtgbwntrey.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gtaxgxyhqp.html

[U70] PHP：PDO 事务
来源：http://dali.andypj.xyz/Article/details/gtgbhrtnwm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hysaishi.cn/Article/details/gtyylpbvdn.html

[U71] PHP：抛出异常
来源：http://dali.redwolf501.top/Article/details/gtxfvyemhf.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gtrqfgrfwp.html

[U72] PHP：写错误日志
来源：http://dali.gaohongyu789.top/Article/details/gtvjditnum.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangtech.top/Article/details/gtoiavpfjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gterrlpwjn.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtcluryxue.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtnfppvbdu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.havefunace.top/Article/details/gtnlpmqqpy.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gtajdbbmvf.html

composer require psr/container
来源：http://dali.haohaochexian.top/Article/details/gtwyrrfgvl.html

[U76] PHP：简单路由
来源：http://dali.yonumen.top/Article/details/gthezjnbwn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yangfankeji.com/Article/details/gtycwstnhd.html


<!-- 参考信息 -->