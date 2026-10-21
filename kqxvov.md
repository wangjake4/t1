代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gtzfrvuuel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtpfiwsrvl.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtoyxxtojv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtbnqhosry.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtfwbfvbxg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtjpwjpjjf.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtedxausfx.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtwrfxqedf.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtvlxbbzif.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtuyumnmug.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtyyvcyxqj.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtobsvzyol.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtncvhhlyq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.birdmap.top/Article/details/gtkphkzouv.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtnrvheqeo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtzsuhbjam.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtjrqgfaqq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gttqfgctbq.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtgpgrceez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtcpvlidhj.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtltyoysmc.html

[S49] C++：写文件
来源：http://dali.316326.xyz/Article/details/gtjbudnthu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtmwyktrvx.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtpyeizzlw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gthqkoxrjo.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gthzmttzmn.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtdmwdsoxw.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtyjukijyy.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqhgnijp.html

[S53] C++：移动语义
来源：http://dali.hfpthk.cn/Article/details/gtlqoohnju.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtrcxbfqlu.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtcsndybyx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtphnpapdz.html

[S55] C++：结构化绑定
来源：http://dali.hongshengwenyu.top/Article/details/gtnxedmydn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daria6918.cn/Article/details/gtnnkikury.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gtgeympgfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyfnrkxe.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtklsnbbmt.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtsgxdiaip.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtoofiavhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtugqbbqpt.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtvnyujruu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gttniunhpr.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtbtgzuesv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtzjzwwibw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwlmqovbp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtwqjhgynx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtxcvspxhh.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtteofsvhx.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtsuigujgp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtkwywttgf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gthitdnwet.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtukrhvqnp.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtoebefsxp.html

[T04] Kotlin：空安全
来源：http://dali.daria6918.cn/Article/details/gttzpcjxxo.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gtotkxqhth.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gttwwflxpc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtwnjqcnck.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtvsduvblq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtcjqntadp.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtbzolzbso.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gtixtipgeo.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gtjbiwnnww.html

data class User(val name: String, val age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtnlkzhljc.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtjvmlevqd.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtgtmbszzc.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtakcigevl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gttnvkvuyg.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtatnadygj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjqejjyz.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtmgnsxdom.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtcxkldotn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtosxpbifz.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gttfoynflk.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtdujlvbbk.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtpckpefjk.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtnciocmwf.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtntfmvrrp.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtdbytnywq.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtlpbtluja.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtpvqcppoe.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtbndmfcdz.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtrvzenlyw.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtbbovjswx.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanipmdlg.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gtrurfgxzb.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtxlqmvpqr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtzjjejedt.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtiyobmopb.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gtliusizhg.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gthexqdlde.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtrcxuvyyz.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtjjyiyhuw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtarjttkac.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gtksxagepa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtiziweqbt.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtixplwuzh.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gtyasvlchk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtpirnyddu.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtryjrwwhp.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtvdrkkxva.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtdcnsfmtz.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gtmzsvzpgl.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gtrbnuesza.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gthoybedbx.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtjjeaoifr.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gtmlslcbei.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gthkcdlhln.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtsjzvuomr.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtlexositv.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtojojhybj.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtgxdglxrg.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gtsyqgmahq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtdrvdyzuj.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gtxojtmdei.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtgkspxxji.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtzbfbiaua.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtjxduebbp.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtckcegmum.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtfnjoovec.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gttsvszeez.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtbqokrtsi.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtswlqkvqz.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtcbyflckf.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtphvhjjmm.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtatuxvbal.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtyzlqinyn.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gtolkfynpa.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtwlpuldeq.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtkfaittys.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtpaxnvvln.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtwmxzrske.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtrpibjzog.html

"值: $a"
来源：http://dali.jlsjyb.cn/Article/details/gtrvkczrwq.html

[T44] Perl：条件
来源：http://dali.guannengcc.top/Article/details/gthbsjutns.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gtotkicpyo.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtgowjjlmc.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gtaatvccna.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtpzkqyusg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtoblcyddf.html

[T47] Perl：正则捕获
来源：http://dali.vqdsnc.cn/Article/details/gtiinhqdup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtdktcckye.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtsccgkfwy.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gtuvyctfsw.html

[T49] Perl：函数
来源：http://dali.hywenlv.cn/Article/details/gtjoezxwdi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzglshuo.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtwrkwczur.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtupyyhqcw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtpwndverl.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gttsodajve.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtzucpzton.html

[T52] Scala：变量
来源：http://dali.gaohongyu789.top/Article/details/gtdofwchnu.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtnmgxlxfb.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtmhbjuadk.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtrwuutmio.html

[T54] Scala：集合映射
来源：http://dali.daxiang520.top/Article/details/gtvkodzgaj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jyoumei.cn/Article/details/gtdnpeslig.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gthnhewlla.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtkbdqmveo.html

[T56] Scala：样例类
来源：http://dali.redwolf501.top/Article/details/gtheirpvzu.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtbamioabq.html

[T57] Scala：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtvpveqvzm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gttgosjxbv.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtjjhcrdcp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daria6918.cn/Article/details/gtjrtzihvy.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtgjtwmdoi.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gteowjfktf.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtreesiodd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtntduesmt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtyrncsxid.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtnnkrxnnd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxtfwddfv.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gttwvigfmx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gtqkwuceai.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gthrexrwvi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtvsdcqvlo.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gtazgghtwf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtkehlmtqh.html

[U04] Py：变量调试打印
来源：http://dali.ybcxt.top/Article/details/gtlnelndqi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangshuangyany.cn/Article/details/gtfxlbwtdr.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtbpgbgcib.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtpedrvyhv.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gteljsuwxi.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gtcmxitejv.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtxmrvuvzj.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtdpalhbrk.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtfghaziwo.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtshrywpfb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gtzgjjbnga.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtbvnormlz.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gtzhgoraty.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gthtrowqps.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtlefqyufd.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gtwfakfwqm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtoakpelzs.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtfuzgzrcq.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gtjujcwykx.html

deque(maxlen=10)
来源：http://dali.smart0.xyz/Article/details/gtvsyylqvo.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtrmkzvpgj.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gtvdqspspw.html

[U15] Py：高精度计时
来源：http://dali.mhx1999.top/Article/details/gtymjnovwf.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtteiirveo.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtaemujycu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtbmaxweqe.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtupigughn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gtdmemofnm.html

[U18] Py：预编译正则
来源：http://dali.zhongyouzk.top/Article/details/gtpvubfggd.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtwrmfovku.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtulisrpzm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gtevotkjjq.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gtyvuecogc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtgpqrylwh.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtgjmymjie.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gtnmqnnvns.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejujirep.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gtjclgniuc.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gtmuthpiiy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtnswsayzm.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgqdhzqi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gtqjxsgtoj.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtnexdpazb.html

csv.DictReader(f)
来源：http://dali.sysykeji.top/Article/details/gtwjunonkl.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gtdhtcscrv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gtboekatzj.html

[U27] Py：异步 HTTP
来源：http://dali.zhiwuduotai.top/Article/details/gthbdyiqzs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtlaviaxqv.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtvqiqbcmn.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gtsqmwukzo.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtliyfvuna.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gtdbwrucbi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gtvacqfrhv.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gtxoestzou.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtbmehbjbb.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtcayawyas.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtrgshxtog.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gttdqndfer.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gtcceljvey.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtsnvssrau.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxsfaikl.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtcgopizhd.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gtxkaocorz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gtratjkeux.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gtomihqkzc.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtqaayxgvu.html

[U37] Py：读写 Excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatysmhae.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gtfpkkeure.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gtwwzrdjko.html

Path(__file__).resolve().parent
来源：http://dali.yangfankeji.com/Article/details/gttnjcijse.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtnvmdtoab.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gtuzfabyzh.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiouxqgqm.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtiltxnmsz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tanke756.top/Article/details/gthutihnes.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtlbkbnglo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gtqoilesxr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtabovxvhg.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gtsgwxsfpg.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gteyatxkwd.html

[U44] PHP：开启严格类型
来源：http://dali.shzxlz.cn/Article/details/gtldltijol.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gtbbfvxeim.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pengpengdd.cyou/Article/details/gtcjbpqbkx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gthihtgoxr.html

[U46] PHP：可空类型
来源：http://dali.jqgufenzy.top/Article/details/gtdxblxtyn.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtguwfogwt.html

[U47] PHP：联合类型
来源：http://dali.jinqigfzy.top/Article/details/gtvwyawlxn.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtiwsskecu.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gtxufkjgye.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gzhubu.top/Article/details/gtjywusivx.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtfkpbldzm.html

public readonly string $name
来源：http://dali.shangyingyoupin.top/Article/details/gtprdmxfdt.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gthnawplho.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtepumrqqd.html

[U51] PHP：数组解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqougckq.html

[$a, $b] = $arr;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjombomcq.html

[U52] PHP：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtkbqvgemc.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtvvpfib.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtlbuvgdwn.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gtyeryseyf.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlompfbd.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtcydearln.html

[U55] PHP：match 表达式
来源：http://dali.hfpthk.cn/Article/details/gtyndywbcn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtrsrryjwj.html

[U56] PHP：命名参数
来源：http://dali.pycfn.com/Article/details/gtfbobeqev.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtvcfyshyq.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtbjwmhojr.html

"值: {$a}"
来源：http://dali.yueranfly.top/Article/details/gtjulpdwhu.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtbvunptqc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhengqikj.top/Article/details/gtpfpzcaxz.html

[U59] PHP：自定义排序
来源：http://dali.gaohongyu789.top/Article/details/gtjcbgnnvt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtjmjbtnrg.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangtech.top/Article/details/gtuthrchnt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtmmjtrexe.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavpwatan.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtbwpqmanu.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gtsjwrusey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtfdsvtsds.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtowdzwsla.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aizwys.cn/Article/details/gtqapvxbma.html

[U64] PHP：目录遍历
来源：http://dali.jlsjyb.cn/Article/details/gtzcbeadfp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhiwuduotai.top/Article/details/gtcuyifidh.html


<!-- 参考信息 -->