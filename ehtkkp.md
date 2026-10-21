代发 wailian999

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gtadpzhhiw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yueranfly.top/Article/details/gtyvavpigy.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtftvjpkiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtbezxnfqm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gtqmjrfxap.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gtinoyxavr.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtrenppviw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtcislawqv.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtnnprtbwv.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtilluevdq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gtamycznxo.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtjnlrksvm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtpiiwyfff.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtwhmxoqtx.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gtglsloxwz.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsixevzgb.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgiqnmhqw.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtgtsnbybb.html

std::vector<int> w = std::move(v);
来源：http://dali.xziqi.cn/Article/details/gtmxbnzflh.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtekdtcqmc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtfkakxvxv.html

[S55] C++：结构化绑定
来源：http://dali.yj202588.top/Article/details/gtwgkyerzj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtosympbgm.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtpviulfkn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gthpoxvdwq.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtfkyflxwh.html

constexpr int N = 10;
来源：http://dali.yj20258888.top/Article/details/gtdtilsbqd.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtqbpnfnak.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtcstihbme.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtglibwpee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtblsbnvkb.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gtnzexwrxl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtoybemkqd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnfjeuthr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtnfexdedk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gthrogeqkv.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtnuonsexd.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtyrjxfzoq.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gtgxsqchct.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtemocolca.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtolpgeqlf.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtxfztesfs.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtfmdnlynh.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtfkwbeanx.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtnrtejzhg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gtaopnouen.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotfvfmbt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtafhkypim.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtszwlfkpr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtpmciyfvd.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gttguvsiex.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtmopcbgyj.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtpvlweccj.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtxlxkkpic.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtbsfualhc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gtocshlfba.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtiecaibvw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ppjwa.cn/Article/details/gtschtbyzx.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtigvywkxl.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtrxzvnbtn.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gtglgcgufx.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtefilmeno.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtyskluagf.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqdtjpsu.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtraomwbun.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtielzomqb.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtgpgdvztj.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtbpreqopq.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gtvxlilewh.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gthclogmmo.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtbncecbxp.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gtbfaessnn.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtqbknheno.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gteditpoje.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtaizxtozu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtmdijugwy.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gtwdsmsbuh.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtvexxmdfs.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtpdyixbab.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtetjyeefv.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkuliksj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtuntdmtzw.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gttusovbqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtqsrpmhkd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtewhhqxfd.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtphqgylew.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gtcyidienj.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtduterlrj.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtdoryhrye.html

do { try f() } catch { print(error) }
来源：http://dali.hnxiangtu.top/Article/details/gtjqyqhueb.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtdvunevts.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtabnyzovi.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtjauwzhtu.html

guard let x = opt else { return }
来源：http://dali.tianlin.xyz/Article/details/gtfjfvjknt.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gtqefebfye.html

protocol Shape { func area() -> Double }
来源：http://dali.ehwqpu.com/Article/details/gtuypvjmrq.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtohkkjqsl.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtdeukqnms.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtswzzvcjk.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtuivhdhnx.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gttlvikikw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gtuwtxcoaw.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtskrvyzqt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtdwwqipok.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtdrclgo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtltrzntnu.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gtxewwrvvk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtjconmdya.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtfyhiivng.html

"a" .. "b"
来源：http://dali.tian-w.cn/Article/details/gthyczlycn.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtafxgnqew.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtqfgpltxy.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtgsljgyse.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtqegesvec.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtjrepzxcw.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtczsfcocq.html

[T41] Perl：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtjuzvtjyx.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtdacvjfjs.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtgmbdojcm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtcfxzxhnl.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtwchdadrl.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtkldgcanb.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtjqrstoue.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gtlrjdbbtk.html

[T45] Perl：数组遍历
来源：http://dali.yuxming.cn/Article/details/gtpccgnlqi.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtntuxeaxj.html

[T46] Perl：哈希操作
来源：http://dali.ydzc1.top/Article/details/gtcnmxuflq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtlcbkuwnw.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtatepoxtv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtmxanroft.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtiowbkdig.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtwqoxhiki.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gtrqmfaokb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gttdpihhxm.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtkhvacwdp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtxverwohn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtvoojihdp.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtbxajuohr.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtkemyjifc.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gtrpdbowce.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtmugomsda.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuylylcy.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqrghtei.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtcgmbswgs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttcdbycgc.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtzacczotg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtmbvlfnol.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtgxpjsbxe.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtsuamowna.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtsblqykjo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtjxlojnlw.html

[T58] Scala：函数定义
来源：http://dali.fzhhl.top/Article/details/gtwgxjzoum.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtyfenwfcy.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtdrgvjtyz.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtktitnxod.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtqdsnifvh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterxpuksx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfdalttrg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtlrhckkik.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcngluxvw.html

[U01] Py：创建虚拟环境
来源：http://dali.jianghu66.top/Article/details/gtikuwdcrd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtblhymqwg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtexcphsyp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gtqyxkbvmc.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gtjfudydqu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtuhkgulxp.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtjevkmuth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtbgdsgkan.html

[U05] Py：列表去重且保序
来源：http://dali.yangfankeji.com/Article/details/gtiaixiomd.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtjrbydpvg.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtfssngjzy.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtstgbbclu.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtrltobzbr.html

{v: k for k, v in d.items()}
来源：http://dali.ybcxt.top/Article/details/gtziscxojs.html

[U08] Py：展平二维列表
来源：http://dali.ivvv.top/Article/details/gtgdbohxkk.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gtilkrhjlz.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtwsfaravc.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtnntpydua.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtsesnvkon.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cheryme.top/Article/details/gtfhmyfvfg.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gttvyjoovl.html

(x * 2 for x in arr)
来源：http://dali.yangfankeji.com/Article/details/gtejcvcanl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtbxakxiaw.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtsceidtya.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtpvuhxink.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtdeibnvcw.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gtxlakexhk.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gturwwylhy.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gtfkfrtqba.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtztufobgq.html

[U16] Py：命令行参数解析
来源：http://dali.hnxiangtu.top/Article/details/gtcpkyskzs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtrzgkeugc.html

[U17] Py：初始化日志
来源：http://dali.yangfankeji.com/Article/details/gtiiwkvyhx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.andypj.xyz/Article/details/gtdhjpyckt.html

[U18] Py：预编译正则
来源：http://dali.haohaochexian.top/Article/details/gtunsreqvb.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtljwvvoff.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtqmpkkcih.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtzbmgjylw.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtwazjklbo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yvedp.cn/Article/details/gtaaechmfu.html

[U21] Py：自定义上下文管理器
来源：http://dali.xinyue.icu/Article/details/gtmefqymzu.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gtyalvucta.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gthvroiasx.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtjkoqxiak.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtaoewjuol.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gtptzhmyiy.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gthhbaffdg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtlfegslpt.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gtottuiuqp.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gtrwelwion.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gtpbjqbufu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtsfubseug.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gtbtjujaos.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtpgrifjfl.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gtwufompry.html

UserId = int
来源：http://dali.hongshengwenyu.top/Article/details/gtwqukavdh.html

[U29] Py：属性校验
来源：http://dali.hysaishi.cn/Article/details/gtyruvrskn.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtqrtzjaxt.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gteyeskxzj.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtgodlhuhi.html

[U31] Py：单测
来源：http://dali.zhoulong.xyz/Article/details/gthrlzwmzc.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtrakwlexw.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykrzhgsv.html

ruff format . && ruff check --fix .
来源：http://dali.zhoulong.xyz/Article/details/gtgkgylphc.html

[U33] Py：打包发布
来源：http://dali.0kj1m.cn/Article/details/gtcdtiwzyp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtsdsaposw.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangtech.top/Article/details/gttxjuhrbd.html

chardet.detect(raw)
来源：http://dali.zhiwuduotai.top/Article/details/gtfkrskwdx.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtfpuocprr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zdqjudy.top/Article/details/gtxqstmyhj.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtklzfqpnc.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxinkj.top/Article/details/gtcgmbxsdf.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gtafxotynu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtevxwqyct.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gtaotlehpb.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gtqqjwgbfv.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gttpurfzwz.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gthbeslegm.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gtijnmkoil.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtztbiujro.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gthmowezak.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gtjdxrojrp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuanzhike.top/Article/details/gtfupweema.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gotoacloud.top/Article/details/gtyaukfgjj.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxqhgndy.html

namespace App\Http;
来源：http://dali.meibo888.top/Article/details/gtccuqoouf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gtqpkmjrdo.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtraagsikw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtizqefoph.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtugvjdlad.html

[U46] PHP：可空类型
来源：http://dali.meibo888.top/Article/details/gtykgpjsaf.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtwonffcip.html

[U47] PHP：联合类型
来源：http://dali.ybcxt.top/Article/details/gtfgtarqpk.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gtdlktrwdi.html

[U48] PHP：纯枚举
来源：http://dali.xziqi.cn/Article/details/gtjdoinxmy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cashguo.top/Article/details/gtmivdmqqx.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gtzvhciyqg.html

public readonly string $name
来源：http://dali.jianghu66.top/Article/details/gtjmiofwup.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gtdnmhmhth.html

public function __construct(private int $id) {}
来源：http://dali.vqdsnc.cn/Article/details/gtrjxfmoht.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gtfbfndvrc.html

[$a, $b] = $arr;
来源：http://dali.gogol.net.cn/Article/details/gtgpfzcfpc.html

[U52] PHP：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtbzxtahxp.html

$double = fn($x) => $x * 2;
来源：http://dali.ydzc1.top/Article/details/gtftqyqmoy.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gthqllqjui.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtbcexcoez.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhsnoahm.html

$obj?->method()
来源：http://dali.aizwys.cn/Article/details/gtztntywib.html

[U55] PHP：match 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtfxvjkium.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gthliebjiz.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtifidltkt.html

f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtikrnmiky.html

[U57] PHP：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtpfpzhbiq.html

"值: {$a}"
来源：http://dali.andypj.xyz/Article/details/gtvifdvyqd.html

[U58] PHP：数组三件套
来源：http://dali.xuetiantiany.cn/Article/details/gtdysqjlle.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gtrufutobi.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtdfbdwiqc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtscnqlkgl.html

[U60] PHP：JSON 编解码
来源：http://dali.dashuyun.cn/Article/details/gtqirwjrwv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gzhubu.top/Article/details/gttsubyzmq.html

[U61] PHP：正则
来源：http://dali.dianchejie.cn/Article/details/gtzhfynqar.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuanzx.com/Article/details/gtzjmckfat.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gtghancmtn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gtnyzavavs.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtkunuclnx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258888.top/Article/details/gtjrgjdypy.html

[U64] PHP：目录遍历
来源：http://dali.jqgufenzy.top/Article/details/gtkakleeao.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtbzsomkit.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtvsljuwkg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtcurweges.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gtdznjmjkx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtbrswwheo.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gtzqrereke.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gtifucaowr.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gtkrnfpawe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gtwfmwrxwx.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gtdwaqiger.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gtkxewmzyb.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtoiobipzm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gtncjzafye.html


<!-- 参考信息 -->