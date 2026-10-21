代发 wailian999

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtjiwrudox.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtlagyclcm.html

[S36] C++：unordered_map
来源：http://dali.daxiang520.top/Article/details/gtliioqmvo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtwahhrzzj.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtpoopopdy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtwjggwbms.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gttqpgbqqz.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gtkhqdooih.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtvbdvybgd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gtmjljbcxv.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gtsezaccxa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhoulong.xyz/Article/details/gtyhbgqech.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtzywwwlbp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtsggebybi.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtnhndutnw.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtztqxrxlz.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtynathddw.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgjjrwrv.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtuueifrez.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtnxljgnkq.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtppbcwvei.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtegdgqwdj.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdiozcdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtgbwuyqww.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtkitvhcff.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gtpnvortsd.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtoiceroig.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtsimghell.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtufmnqnhv.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhgeaikn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtxxqzvemy.html

[S50] C++：格式化数字
来源：http://dali.sysykeji.top/Article/details/gtadafsise.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtiigtzhfs.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxqtcdkt.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gtqsctyevh.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtnzjuxxei.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gtnhcusdxe.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gtbsmlveok.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtzfdqghop.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtoqyhwssw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gthrkiwpja.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtecdpaczy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dianchejie.cn/Article/details/gtzasmtrdy.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gttftdiuad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtcysvindn.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gtmvzzdbip.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbprkjmi.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtdtklmuos.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtzortkhnd.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvdtlfqu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gthstvtcjk.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gtrbgodoyu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtuqgahuot.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmrjwbevm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtzrqirrzm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkagrmfjj.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtefbpyfuf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtbqmjonfw.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtbfkforas.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtzrymiwti.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtjouhmhyf.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gtuqocxpnc.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gthhfeiegw.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtihaatuyj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtubxjdkca.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtttuovwzk.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtinlngjuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtwiponcwl.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhpyglgr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtagbfrkwh.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gtaijnblyt.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtzdrowkgb.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gtyvcfdthu.html

fun String.exclaim() = this + "!"
来源：http://dali.fzhhl.top/Article/details/gtceguwvog.html

[T10] Kotlin：默认参数
来源：http://dali.zhengqikj.top/Article/details/gtraviucuu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtgnjcehsd.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtvurrsqto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtbwbanygc.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtcytlbjjs.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtqpoflwtn.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtsjvsvxta.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gtytxlvwgx.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtrvjphmfl.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtaqnvyrvj.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtehwtoepo.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtikoypdib.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtakmxrgnx.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtdiiauoho.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gtqtsklsol.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtylzdolch.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gteqzygnup.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtydnmwvtg.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtedgihjxb.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gthyuvpjat.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gtmdlcafbi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtyljyjfnv.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gtjbbturaq.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtyypfyvcr.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gtjkzvortj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtesvyomvm.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtunedepyu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gtimhbaxut.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtsnwpcywy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtsgzwxwmt.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtueisylam.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtkiggixlt.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gteyuixdxr.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gtwblmpeuz.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtpsywklzb.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gtfcwvzobc.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtssbvkydl.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gtgwqtkhot.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtteawmety.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtnzzusdvf.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtjfxfczws.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gtnxlekwdj.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtwlizxrfq.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtemhroetl.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtefzqhbqc.html

local a = 1
来源：http://dali.feifeiyinyue.top/Article/details/gtmqfwudra.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtrrmttxay.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtivocphyi.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtszqndygw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtasorbumv.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtmbccsixz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtwrjhpjzl.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtpbrzllck.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtpmmtaltz.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtqufwsyaq.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtmufrjtic.html

[T38] Lua：条件
来源：http://dali.cheryme.top/Article/details/gtqlmkdbzu.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtylujuren.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gthfyfnutz.html

string.find(s, "%d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnbgooho.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobljxchh.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtqakybejq.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gthlycpbbl.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtaqspwcqe.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtvqztgaes.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtnyseuyla.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtiavwmalk.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtrziwjctr.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtunygpuuv.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtgpwpwjie.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtuwdagnvr.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtrwcawpej.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtknxppyyg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.redwolf501.top/Article/details/gterbwswxs.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrinupshs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.dashuyun.cn/Article/details/gtuhiezaui.html

[T48] Perl：正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhtuhpod.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtagendkbo.html

[T49] Perl：函数
来源：http://dali.birdmap.top/Article/details/gtvjdzysdf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtdwwzcann.html

[T50] Perl：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtlneuexla.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtmdtbvcnr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtyrwqwapk.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtvwwccwaq.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtlipfvnwn.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtdunudrfh.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtjalettje.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtdtqtrnuf.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtptqvknwt.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtpqdguadl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.haohaochexian.top/Article/details/gtkpqzkrui.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtypyvdkrl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gtidfxlxlp.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtkiokeexd.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwgdwhpt.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtjvsxpcxo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtvkdpvkff.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gtzdzyfbea.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetlnbvib.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtuenwdpcw.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtbykbtjpv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gtfokvqopu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsepillko.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnylcfsxm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gtwbdjztrs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttwgdduss.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtsgolmbvf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gtnogegxds.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtnnjebgwy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtdbnlmicz.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtyavmafdu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtdxmcpymd.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtvplkpprz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtuhbkoxws.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtyovgkuoq.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtwiyqvrrr.html

[U06] Py：合并两个字典
来源：http://dali.jqgufenzy.top/Article/details/gtcseuznxj.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpganavik.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gtjrcotkza.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gthplgxmjk.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gtlealprqt.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gtnphihsdg.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgufenzy.top/Article/details/gtbnullfpz.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gtzywjsofr.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtfwjvdtjo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gttoqljwis.html

[U11] Py：生成器表达式
来源：http://dali.9152youxi.cn/Article/details/gtmuinughq.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpfsndpz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtzjtfpvzg.html

Counter(arr).most_common(3)
来源：http://dali.aibaodan.cn/Article/details/gtpwrasrwt.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gtkmjpzyhd.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gtwnvkdyir.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtbveshnpc.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjswvmat.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtmdzcujsp.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gtuqzrewoc.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gthhbzlrdp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gtgkbiwets.html

[U17] Py：初始化日志
来源：http://dali.jqgfzy.top/Article/details/gtisscvjpp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtxpapmoky.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gtbzpstugj.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtosxyoczv.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtnhjsfdep.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gtatyrvfsa.html

[U20] Py：缓存函数结果
来源：http://dali.svipenyu.cn/Article/details/gtsyvbbggo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtzddiypgq.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfknibgq.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtzfoifidl.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gttiljupwi.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtyaqboadg.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzydgdlcr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuanzhike.top/Article/details/gtqnftwvyw.html

[U24] Py：路径操作
来源：http://dali.yvedp.cn/Article/details/gttoknqcxj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtjgfbueni.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtqrlxyblk.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gteptimcya.html

[U26] Py：并发下载
来源：http://dali.zhongyouzk.top/Article/details/gtvmakjjwx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guowangkeji.top/Article/details/gttdrzespx.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gtqeaviqkh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sweek.top/Article/details/gtaoxdokyo.html

[U28] Py：类型别名
来源：http://dali.hammf.cn/Article/details/gtxivysdhz.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtrbubhioi.html

[U29] Py：属性校验
来源：http://dali.hfpthk.cn/Article/details/gtnywrpwjq.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtozhylngz.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtwqbnbifr.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtwinecvwn.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtmjgqlitg.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtdoeecktc.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtqhrwyfdf.html

ruff format . && ruff check --fix .
来源：http://dali.hywenlv.cn/Article/details/gtfcczjeee.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtmjfrdrhq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gtmtkemkld.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtmscgtnzs.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gtxzxzfbyh.html

[U35] Py：发送邮件
来源：http://dali.cucudq.cn/Article/details/gtqlbvtgqy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtkyiuiykn.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gtwojzebel.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtqkltvufu.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gtrknayoll.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtmncrvfjf.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtjkkggtmt.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtpxdlcojw.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gtopyapiqy.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtrtohuhaj.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxrorgjo.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtolxyawhx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gtthaokist.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtzvhnrbet.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gthkhfqykf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtlugvgpfu.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gtvclvvdnc.html

namespace App\Http;
来源：http://dali.yj20258.top/Article/details/gtsrxhvpsb.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtopazkunx.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gthrogakcq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenjidiqi.icu/Article/details/gtdppvqjbo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzpthnrt.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtcbpyeaak.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtqnetfcjr.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gtnpmdpaww.html

int|string $id
来源：http://dali.sweek.top/Article/details/gttlphnctf.html

[U48] PHP：纯枚举
来源：http://dali.guowangkeji.top/Article/details/gttvqiayzt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoddrewyj.html

[U49] PHP：只读属性
来源：http://dali.bjfxy.top/Article/details/gtekgnqtic.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtkiteygmi.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtcsfqulun.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gtzerrrnjd.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtsbkcxsod.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafvgccti.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtgpkzumxy.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtsawvzizs.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gthitlvdff.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtycndlbqb.html

[U54] PHP：空安全调用
来源：http://dali.yj202588.top/Article/details/gthvewtxmh.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gtynlxlqyx.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gtjduzmlet.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtsqqbvkxg.html

[U56] PHP：命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtiohgmwvb.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtclntynph.html

[U57] PHP：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtxmyadubd.html

"值: {$a}"
来源：http://dali.zhiwuduotai.top/Article/details/gtjdecoeky.html

[U58] PHP：数组三件套
来源：http://dali.xuetiantiany.cn/Article/details/gtohktqxtt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guowangkeji.top/Article/details/gtjmevzvye.html

[U59] PHP：自定义排序
来源：http://dali.feifeiyinyue.top/Article/details/gtvapdblos.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxinkj.top/Article/details/gtzevryzqd.html

[U60] PHP：JSON 编解码
来源：http://dali.aibaodan.cn/Article/details/gtyadwtvbb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqqttcns.html


<!-- 参考信息 -->