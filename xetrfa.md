代发 wailian999

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqjukvdx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gt2jeugzqjb.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkzlytxo.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2ncjddrvm.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gt2yobnnpmx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gt2axulrcrq.html

[S40] C++：查找元素
来源：http://dali.meibo888.top/Article/details/gt2dmrbwqpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gt2ifpxfeyi.html

[S41] C++：类与构造函数
来源：http://dali.sxryk.cn/Article/details/gt2murfkfhr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gt2xforivap.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gt2fbucgdmr.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gt2yjniwrjs.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2ywkcdrrg.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gt2wluuvhau.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpcxatha.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oloqkfgc.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gt2xjulwdlm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenlongwang.top/Article/details/gt2pktykmyt.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2hrxcxjyp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2njtnwmdi.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gt2thayuzlg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bcrifmjd.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2ganzxakg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gt2jmvykgco.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2edsyoxed.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gt2yvrnaasn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2osikfmlm.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2xofaqeka.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2pohirwhw.html

[S51] C++：显式类型转换
来源：http://dali.zhengqikj.top/Article/details/gt2kmwrbnkb.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gt2vzsovqba.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owxobrds.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkdyraxp.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gt2pgxuwnls.html

std::vector<int> w = std::move(v);
来源：http://dali.gotoacloud.top/Article/details/gt2pnkwsbyb.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhgsuact.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gt2bwvkqwxt.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gt2nothzoiz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gt2xpssnqvh.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gt2hxgypwjk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgtcuuhs.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2dkbbjiwb.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2onlkzstq.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gt2riiwinhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gt2ugjazjfo.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2hkuhkbsl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gt2aiximrio.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2shqttwkt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyxaadwl.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2mascmsvo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhtaowfa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kydsnkdq.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2mutpdleu.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2xodehqht.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gt2xrtamhhv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gt2wrtjtkrw.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gt2legbyhyp.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2roopslap.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gt2phfwuysq.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gt2ppwauhdf.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2xmmjxpec.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xylfe.cn/Article/details/gt2vrgplshr.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gt2zughttqr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2gwxxmils.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2jxdeeqhz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2eszwxuec.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2aylbkidx.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2qsctigzm.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gt2zngctkmw.html

fun String.exclaim() = this + "!"
来源：http://dali.quarkkingdee.top/Article/details/gt2fqxaaesy.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gt2jlvmfqvz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfqkpdwg.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gt2pumprvqs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gt2etxyktxm.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gt2ahxbocvx.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cnuryqmk.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szzmzywg.html

val m = mapOf("a" to 1)
来源：http://dali.hywenlv.cn/Article/details/gt2amnukzbl.html

[T14] Kotlin：循环
来源：http://dali.xuanzx.com/Article/details/gt2kfremzci.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2sydvneit.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gt2ujggdfet.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gt2vkikdeut.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2sxrqzlmw.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gt2qaufwsem.html

[T17] Swift：变量与常量
来源：http://dali.yvedp.cn/Article/details/gt2dyehrtwa.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttkyryda.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2kfxucjfa.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gt2lrrojjbc.html

[T19] Swift：可选绑定
来源：http://dali.tianlin.xyz/Article/details/gt2mzkggtyc.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gt2sjkeuapj.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gt2nyuhhyuc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gt2vbrnbarr.html

[T21] Swift：遍历
来源：http://dali.ppjwa.cn/Article/details/gt2ddcitumy.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gt2llfokloi.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohaujvfe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.dashuyun.cn/Article/details/gt2wkxtwxir.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gt2wfyhehcq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jchtmxip.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2norzeguj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2rijvmqhp.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipthezuq.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gt2zkizxgvd.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gt2jxdlozgc.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2jqcybaey.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gt2qkcxaixc.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xitwxwff.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gt2vrahvhpb.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gt2jdtzlhae.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gt2ispxifyp.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gt2etbpnxxe.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejgvkycg.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gt2utopylah.html

[T31] Lua：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2aeucajqb.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2ltujdepx.html

[T32] Lua：局部变量
来源：http://dali.ybcxt.top/Article/details/gt2swwzyvcb.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2gqrkerqh.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gt2ahrxqajf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wducsdsv.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2impkrbii.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gt2gposjehm.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsamkiag.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gt2sqmcgouf.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2dnnybrzn.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gt2ykysyief.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gt2cetcvkof.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gt2miunaxwf.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gt2oxatlqax.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gt2yzcocqiq.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2oszryqve.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gt2arxylgjk.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2cqwkzovn.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sediqrwu.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2httzdnix.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gt2aizcvida.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gt2dxesjfuv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gt2iqmlcyna.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2gslurnxz.html

"值: $a"
来源：http://dali.yuanzhike.top/Article/details/gt2pdcfdhuy.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gt2pstlnovk.html

if ($a > 0) { print "正"; }
来源：http://dali.yonumen.top/Article/details/gt2dceevpao.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbcgyqlc.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2knpyzijh.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gt2ecubmdkv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gt2sktnkczs.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gt2ltyctpty.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gt2tpatnasw.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2raxmhfzp.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnzbuojw.html

[T49] Perl：函数
来源：http://dali.yueranfly.top/Article/details/gt2oqxigtnq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmxuaaks.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2ligdoyyi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gt2bqshzkrw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2lihognji.html

[T51] Scala：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2smxulylo.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2iakkhtsa.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gt2goqqjlgz.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gt2ezasnraf.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2volnxufa.html

s"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gt2afzydghg.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gt2xaosotdk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2mpqmaqmu.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2vxaakpqf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2uorazsst.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2ifxsdlij.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2retsvuww.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2fembwnwx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gt2vroyxyoh.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2pzjtfhml.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gt2aqjwivie.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gt2ipbinvfb.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iszszzdz.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gt2hippdzgg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gt2bznlnpsg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2kfeeqkfb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2wqkaycnj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sbghjueh.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gt2hfavaoqc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gt2yyeavgml.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gt2hprfjgnd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gt2uvlitswn.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gt2phhvgtjt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2cucwmejs.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gt2zytxhipf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2omolkjcq.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gt2itqkycsm.html

list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2aqvsiqrj.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2mcyfqqsg.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gt2lpburjqu.html

[U07] Py：反转字典键值
来源：http://dali.haohaochexian.top/Article/details/gt2dfqhzcpv.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gt2mcjoyhed.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2sywrwaih.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2favzrwvb.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gt2ufugrrpz.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gt2tmhudxeq.html

[U10] Py：按值排序字典
来源：http://dali.zhixingplan.top/Article/details/gt2tufdpupd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylrebagb.html

[U11] Py：生成器表达式
来源：http://dali.ivvv.top/Article/details/gt2zbfngync.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gt2tddsuezx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gt2dufygqbz.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gt2xfmhiezd.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gt2zmgstyqq.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gt2mvtlkcib.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gt2yzxabvzt.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gt2qgvqkprf.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gt2giesqunp.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gt2pjlluyjx.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gt2nhczbiaj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxuanxn.top/Article/details/gt2tfengxzt.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgkaviae.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gt2goqgddan.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gt2oycedvet.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gt2bugityzj.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gt2nfuwzwbk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2semvkjjo.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2tpbgfzum.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yonumen.top/Article/details/gt2gtmddlrw.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gt2sesiyzeb.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gt2qdymiqmt.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpmxwyyv.html

list(zip(*m))
来源：http://dali.aibaodan.cn/Article/details/gt2ezkybspv.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gt2yxjzopyo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gt2payvyfgh.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gt2aklpaggg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2ngwkuraz.html

[U25] Py：CSV 按字典读
来源：http://dali.cucudq.cn/Article/details/gt2xkaxiqnh.html

csv.DictReader(f)
来源：http://dali.kuanghao11.cn/Article/details/gt2uohcspkt.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcndfjkx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgxbiidw.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gt2chudecns.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gt2vrwwlgqe.html

[U28] Py：类型别名
来源：http://dali.jianghu66.top/Article/details/gt2jwddaiik.html

UserId = int
来源：http://dali.jyoumei.cn/Article/details/gt2nxwqolhc.html

[U29] Py：属性校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xavdnwsf.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gt2clsyptgg.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gt2shrudehi.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gt2djhkwwnz.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqaublkn.html

python -m pytest -q
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoavanqn.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gt2xcvbjekj.html

ruff format . && ruff check --fix .
来源：http://dali.cqqwz.cn/Article/details/gt2mimitxqf.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gt2gcmofzkj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ydzc1.top/Article/details/gt2qznosyow.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gt2zmvpkhsi.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gt2xvysrqth.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrtrlstf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gt2qdguatjk.html

[U36] Py：定时任务
来源：http://dali.daria6918.cn/Article/details/gt2wozdesfa.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gt2ppljduuf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cpspswdu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gt2ogqzgode.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbtngryi.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gt2phjsdghp.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2midyrndi.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gt2stvdbzyh.html

[U40] Py：打印到标准错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtqtnvmc.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2xahppfkg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gt2awpnarfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gt2wyvwrugi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gt2llbadijv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guowangkeji.top/Article/details/gt2itvmgqlt.html

[U43] PHP：声明命名空间
来源：http://dali.andypj.xyz/Article/details/gt2fwtlocng.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gt2ukfxzqoz.html

[U44] PHP：开启严格类型
来源：http://dali.quarkkingdee.top/Article/details/gt2dxhcflio.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gt2hzcuxjdg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiuhyvdh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxqzhgoc.html

[U46] PHP：可空类型
来源：http://dali.zhixingplan.top/Article/details/gt2wakzckuc.html

?string $name = null
来源：http://dali.mhx1999.top/Article/details/gt2rrvgyhdh.html

[U47] PHP：联合类型
来源：http://dali.sysykeji.top/Article/details/gt2iotgdbbe.html

int|string $id
来源：http://dali.sufxvd.cn/Article/details/gt2uwarehzm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lckeezly.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tdtlwavx.html

[U49] PHP：只读属性
来源：http://dali.daxiang520.top/Article/details/gt2wfdnumyy.html

public readonly string $name
来源：http://dali.ivvv.top/Article/details/gt2taevtwhm.html

[U50] PHP：构造器属性提升
来源：http://dali.cheryme.top/Article/details/gt2miognotf.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gt2hghnyzzc.html

[U51] PHP：数组解构
来源：http://dali.yj202588.top/Article/details/gt2obtdmvma.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2xxnbodsx.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2skbjtgji.html

$double = fn($x) => $x * 2;
来源：http://dali.xylfe.cn/Article/details/gt2osexmpfx.html

[U53] PHP：空合并运算符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mebhreiw.html

$v = $a ?? $b ?? "default";
来源：http://dali.ivvv.top/Article/details/gt2wblglqsg.html

[U54] PHP：空安全调用
来源：http://dali.xinyue.icu/Article/details/gt2uxyytkra.html

$obj?->method()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdujqivw.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gt2klxnazqw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dianchejie.cn/Article/details/gt2dghtiyxb.html

[U56] PHP：命名参数
来源：http://dali.c1oappe.top/Article/details/gt2frdcpxmh.html

f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwnxpdty.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2acusstbm.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gt2sabpadnd.html

[U58] PHP：数组三件套
来源：http://dali.yonumen.top/Article/details/gt2vptigfzu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2utxcknon.html

[U59] PHP：自定义排序
来源：http://dali.svipenyu.cn/Article/details/gt2wbqfuofu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gt2gsxdjjow.html

[U60] PHP：JSON 编解码
来源：http://dali.chenlongwang.top/Article/details/gt2riolcabr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aizwys.cn/Article/details/gt2hyrjxztm.html

[U61] PHP：正则
来源：http://dali.chenzaomai.com/Article/details/gt2vaargiaw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2psisdnxq.html

[U62] PHP：日期对象
来源：http://dali.kuanghao11.cn/Article/details/gt2ewzyqczy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnqzz.top/Article/details/gt2btvjhqra.html


<!-- 参考信息 -->