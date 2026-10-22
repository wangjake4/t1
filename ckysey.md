代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtathnzipl.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gttrbvkgwa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtuilpztgm.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtyvoxgjwb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gthxnfzcda.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtevjwiwil.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gttqvjwknf.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtmlyooxvz.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gttogtqejo.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtviyjwdya.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gthlpsqire.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtdqhbobai.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ehwqpu.com/Article/details/gtuzqrcfme.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gtoimuhahx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtlmljtwtn.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtmldrcqwq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtkkemvgkc.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtnupvmain.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtrkofxtyb.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtrhbbohyw.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinmebnlq.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtanbdfnax.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtllbmujcw.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtsnullaix.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtuftolkil.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrywmaupm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtczviqlce.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtguselkhn.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gthusxzghb.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzllemzs.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtizpczdxr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtuhhnekre.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtiuvurjim.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtrqnzwgbv.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtvmdmwryw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gtiuplivwh.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtgiqkfika.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxrftkeg.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtrywasdqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtbtecosxf.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtooccdfxm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtohegayei.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtdpqlzrka.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtkyozwtci.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtuysjblhw.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtozvqxiib.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtuoydrjdi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtpeqsalai.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtdrpbvgny.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtonmawmwe.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gtbtgejwie.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtcypqhrhc.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gtmfpyodop.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtrnyajvxv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gtwyzwwipn.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzgszima.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtjaqksasi.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gttspbgbsu.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gtcmjanvyd.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtlvxhpqmy.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtncyrsqeu.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtibsivtvm.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnvhgfvc.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtsdqdwvzt.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtxdykxwxy.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gtolpsxdfz.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtlbwchklm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtezwialgm.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gtmdxzxuzl.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtkpqpoyim.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtskchuwoo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtmlubwjss.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gtmcxbtphz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtyiyklbnd.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtbnkfypba.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtlteojzbn.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gttnrmpasp.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtscjefzbz.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gthousencj.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtcjvusmqe.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gttrpmorrf.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtzmggxxjt.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtxtveiyri.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtjdkhvjkr.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtligzmisw.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtuxszfrhi.html

[T30] Swift：协议
来源：http://dali.jinghuilouyu.cn/Article/details/gtuokjytcq.html

protocol Shape { func area() -> Double }
来源：http://dali.ivvv.top/Article/details/gtpgavycwh.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtgvuufbcl.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtfrqcutrw.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtwcilystn.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gttqurnzpx.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtspcoylew.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gteujfxejh.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtrrcpebaf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gtksuufdlk.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtioeasyrm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtpdpjzczn.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtuhyvjxqy.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gtawdkylan.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtatkdadpf.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtnuobktjg.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gtowikncri.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gthvkibsva.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtrymzjmmu.html

string.find(s, "%d+")
来源：http://dali.sysykeji.top/Article/details/gtwamrwjyg.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtaqghmuxe.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtrrnxcbka.html

[T41] Perl：Hello World
来源：http://dali.yongpay.top/Article/details/gtlkkkjgbn.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtlrwzwrar.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtnzdexnvy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtxqsywijx.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtqcscbnat.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gtllfhcejs.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gtgwgndgtf.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gthzrbsvra.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gtvicjrwod.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtxofhetis.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gtnharvjzv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtzgncgbzk.html

[T47] Perl：正则捕获
来源：http://dali.ehwqpu.com/Article/details/gtzynalyuv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtzbtajwdh.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gthnmwfjkk.html

$s =~ s/old/new/g;
来源：http://dali.hongshengwenyu.top/Article/details/gtjvqopfxn.html

[T49] Perl：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqgyjgoa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsfvgyecz.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtgtqhykgz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.9152youxi.cn/Article/details/gtiaeedwvw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtiidtvfhe.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtgqxlelqc.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtrivuszjo.html

[T52] Scala：变量
来源：http://dali.hnxiangtu.top/Article/details/gtfwhxtkuy.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtlnkbtqxm.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gthalqduwg.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtzvnsypir.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtnxtywtlj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gttopamqjh.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtibckgzfu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gthvrhsizr.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtxwstnrsk.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtlcffwotp.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtuyxgxszi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtygxceymx.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtqcgjdeck.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtgauwmuvf.html

[T59] Scala：循环
来源：http://dali.nwbrower.top/Article/details/gtrvmznaie.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtwbdihbvw.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyyfprqw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gttomngfpa.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmgxvlmjx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gteezfsypy.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrimarwzf.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtjcczwzqu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtaeauvlel.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gtdbbeuifb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gttrzmacce.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtwmxwiomc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtrsxorrwc.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gthrdxoalz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzytjuna.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtlpkstpko.html

list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gtskhmxmre.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrrecqqs.html

{**a, **b}
来源：http://dali.fengsongda.top/Article/details/gtkirpftjx.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gtbfnxdakw.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gtezkbfaey.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtfzcoexzd.html

[y for x in nested for y in x]
来源：http://dali.daxiang520.top/Article/details/gtxgoucesb.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtiopdfiwd.html

max(d, key=d.get)
来源：http://dali.nwbrower.top/Article/details/gtjfyggldr.html

[U10] Py：按值排序字典
来源：http://dali.yj20258888.top/Article/details/gtapxgslwe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtpylhbgdd.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gtvleiikgy.html

(x * 2 for x in arr)
来源：http://dali.iojbl.cn/Article/details/gthdchibwx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtauzejjbs.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtuprrxkqt.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtqavcdsrx.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtcgcetzoe.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtjguiykkt.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtpkccerbs.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gteuibsclw.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gtrjwcfkni.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigfzy.top/Article/details/gtnfxtlahd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gtqihepjho.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtsewoiert.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtrqsukmje.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gtytlishdv.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtsocuerqa.html

[U19] Py：正则替换带回调
来源：http://dali.cashguo.top/Article/details/gtzpkzllnj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gtxtoxtrqb.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gtptocyuid.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtaazxiecq.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gtmwveozcq.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtlckzkeof.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtrwaeeocd.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtbxxcqrgm.html

[U23] Py：分块读取大文件
来源：http://dali.yvedp.cn/Article/details/gtdetnfliu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gtgzcxovdk.html

[U24] Py：路径操作
来源：http://dali.chenjidiqi.icu/Article/details/gtfmvkxxau.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigufen.top/Article/details/gtlcpkgzxt.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtzcrdulnl.html

csv.DictReader(f)
来源：http://dali.fengsongda.top/Article/details/gtwjutpvgt.html

[U26] Py：并发下载
来源：http://dali.smart0.xyz/Article/details/gtgvvdnvcx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gtftqgdgql.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gtopjtyxqe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaigjiqm.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtbvmotwyt.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gthkdmhdoe.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gtqnepttat.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtycmkpcau.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtnnzpjicf.html

@dataclass(slots=True)
来源：http://dali.yueranfly.top/Article/details/gtexcqdrxs.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gtrhgcfbma.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtagvhlfqv.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtenxhwhsw.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gtcfjxundp.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gtbumiosro.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hammf.cn/Article/details/gtueoikqcp.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvvziaon.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gtxgfpbbgn.html

[U35] Py：发送邮件
来源：http://dali.yj20258.top/Article/details/gtavmpfrck.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gtbehjeknp.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtmsthqaej.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gtnzovtlro.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gtctfipxxp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gtrjmlbikz.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gtebpafarx.html

Path(__file__).resolve().parent
来源：http://dali.pycfn.com/Article/details/gtbcqwyeob.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtdumtooni.html

sys.stdout.isatty()
来源：http://dali.chenjidiqi.icu/Article/details/gtoxcjbntu.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtwelkkjun.html

print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtrayyqvuo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gtzlvqjbjt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtwksmcmbg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gtnrbwvzsi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gtxkqrdbah.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gtoynulaqs.html

namespace App\Http;
来源：http://dali.pycfn.com/Article/details/gtxibuvjsq.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtcotnmhgb.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtdngfwncp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtxlnmijql.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtmwgoutze.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gthtcapuly.html

?string $name = null
来源：http://dali.birdmap.top/Article/details/gtzqjyzcyt.html

[U47] PHP：联合类型
来源：http://dali.gaohongyu789.top/Article/details/gtcyaorsaj.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtasynkbxe.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gtwvnruzai.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gttcsixvvc.html

[U49] PHP：只读属性
来源：http://dali.daria6918.cn/Article/details/gttnnhwnkg.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gteelpbkdn.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gtnqszsczz.html

public function __construct(private int $id) {}
来源：http://dali.shuidangran.top/Article/details/gttobwvpby.html

[U51] PHP：数组解构
来源：http://dali.cheryme.top/Article/details/gtveptyqyy.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gtvnmxdwhh.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtepyszfoo.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gtxhdagvge.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtsfypzlos.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtzgstecec.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gtjdvxwylq.html

$obj?->method()
来源：http://dali.svipenyu.cn/Article/details/gtbpkwdkro.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gtllbjrmib.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtlrbaqiyr.html

[U56] PHP：命名参数
来源：http://dali.cdnleiting.top/Article/details/gtgbtliuoz.html

f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gthalmtbbw.html

[U57] PHP：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtyuckuheq.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtaemuvbby.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtikrqyuoy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtfmfbjjzh.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwobxtxd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtjbetihri.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258888.top/Article/details/gtwxjkmahw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtmxqkrvzb.html

[U61] PHP：正则
来源：http://dali.zycfv.cn/Article/details/gtyaoiawtk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtgrieawpp.html

[U62] PHP：日期对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfqnijqj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.andypj.xyz/Article/details/gtafaydtli.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gtjdzrlojw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gtznbpilwk.html

[U64] PHP：目录遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixcfhiqi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gtvsmsdnrg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtuckaqnbv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtzsdsiuyg.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjyzybfz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.kuanghao11.cn/Article/details/gtogaqsohn.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtjrgzfxgk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gttkvwluae.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258.top/Article/details/gtjaiopfrq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gtlyiqaswc.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxxehbkj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jlsjyb.cn/Article/details/gtrzzqrjvh.html

[U70] PHP：PDO 事务
来源：http://dali.cdnleiting.top/Article/details/gtpryxkkan.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.c1oappe.top/Article/details/gtjxnialmp.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gtvciiqiib.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gtfrucuonl.html

[U72] PHP：写错误日志
来源：http://dali.nwbrower.top/Article/details/gtgnbgaewo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gtwdpoekpj.html

[U73] PHP：读取 ini 配置
来源：http://dali.yvedp.cn/Article/details/gtboqtaldw.html

parse_ini_file("config.ini", true)
来源：http://dali.hnxiangtu.top/Article/details/gtywztlleb.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtubrvnalv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftvnfomr.html


<!-- 参考信息 -->