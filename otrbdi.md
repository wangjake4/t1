代发 wailian999

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtztrqqilt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtjolxttbr.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtiuxbritc.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtfbjzdidq.html

[S33] C++：vector 增删
来源：http://dali.zhaomingkeji.xyz/Article/details/gthldykuaa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtzrxfiakt.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtziftslmj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtvplaispp.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtysolsedr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtvbfgvakq.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gttjirfdne.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtruemttfj.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtaguhkysg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtabknwlsk.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtdppxqufw.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gttpjicort.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtwtmlucns.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtnnxpwwoy.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtuxiszoyr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtxhhkexpn.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gtwkzvarop.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtujmwceys.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtdzymtcjb.html

class B : public Base { public: void f() override {} };
来源：http://dali.guannengcc.top/Article/details/gtknpeqflh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gthtpazthb.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtibvvdadg.html

[S44] C++：引用传参
来源：http://dali.ehwqpu.com/Article/details/gtsihmjtzh.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtrqeiwqbk.html

[S45] C++：lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtbusgfsyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sweek.top/Article/details/gtnqlyaoyt.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtqnrmqnui.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtlunbrvyv.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtskqloeyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtwmvwaoxi.html

[S48] C++：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtusolnwld.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtsfoxfewq.html

while (std::getline(in, line)) { }
来源：http://dali.smart0.xyz/Article/details/gtjyxvzsmu.html

[S49] C++：写文件
来源：http://dali.shuidangran.top/Article/details/gthwdkvefr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtnbwrjfuf.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtumwmbxnu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtemlslhna.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtdqforyoy.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtdijtjxqi.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtxjyrhrbw.html

int size() const noexcept { return n_; }
来源：http://dali.hammf.cn/Article/details/gtyrmvllni.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtgkxzfhev.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gttlmxiklp.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtxpwwjlnr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtzokuucii.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gteecdqbum.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtuqczdwuu.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gthpzpkxdx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtiglrwzxr.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtumiiomjw.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtqgbxwxpr.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtjcufgwqi.html

namespace ns { int f() { return 1; } }
来源：http://dali.fzhhl.top/Article/details/gtzbqcmndw.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtsethkndu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtomtijrjb.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtiznkvisz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtbhnkvlke.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdsgqlemo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gtowfrofzd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfxmhupsw.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtlbhvcana.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtkvlkrfnm.html

[T02] Kotlin：变量
来源：http://dali.xylfe.cn/Article/details/gtugqwtqbp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gtbqrqbkcq.html

[T03] Kotlin：字符串模板
来源：http://dali.cheryme.top/Article/details/gtraxqcrmg.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtgxmdtkhw.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtmtnnptsa.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtcntaeuxu.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtmpjivkul.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtyyupvkzg.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtqsktlunm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtibqkhpcv.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtkjyfpggm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gttpwjjzub.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtyntscpcb.html

data class User(val name: String, val age: Int)
来源：http://dali.cqqwz.cn/Article/details/gthbappkck.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtztanlmxj.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtgtierqoj.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtumautsga.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtvzusimut.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbiqegvh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gthhokkzdp.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gtmzlzuqvm.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtzbniimpi.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gtezygmtke.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtufehrkxp.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gtsovahexg.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gtszyymbgn.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtrzxflcxk.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtdrdaaedt.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjzadyzc.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtdlyegmmk.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtcqlmwcqv.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtmkkxnddf.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gtivonjwbz.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtxwsqotjw.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtoclfefml.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gtrfewjocj.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtjoviqjyj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtfhaavnrd.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtfbamurjc.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtbqobkzpv.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtrgrxrpru.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gtyjhdfdkv.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtbmyvvflk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtjwvreibp.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtuwmikxik.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtjvidlzto.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtawbdppme.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtldiekyng.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gtabgishzs.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtrrmozrzb.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtjflimptl.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtkufztndu.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtsvqkbcdm.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gtbmyvhyfp.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtxkdlerpe.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtdliwhekk.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtlmzqyhob.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtgwpuuvbq.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdaaemvou.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtfxnnntgl.html

[T32] Lua：局部变量
来源：http://dali.jiagoushi.top/Article/details/gtcrklodze.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtrqseuyyc.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtyhlzfpxn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtptypsuzz.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gtubqhshpn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtiuciwycv.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtrmnykqqp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtsbtlkzuh.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtsxwbswih.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtecsxzhse.html

[T37] Lua：字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gthqmlnbdj.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtkvklmvti.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtchbtjbfv.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtvkxyegur.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtkjzoplsc.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gttecwwnat.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtpntpfidj.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gttyfmgfpb.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtflrmmkmo.html

print "Hello\n";
来源：http://dali.yongpay.top/Article/details/gtjebwygnp.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gtafjwypzc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtnemqqxje.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtmgwickgs.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gtkikvtaxa.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtktkmlxfe.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtayiaimjv.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtofqensoi.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gtcyfmpizk.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtddidxlji.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtckmuwdri.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahkpxpyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtpmnmvxuv.html

[T48] Perl：正则替换
来源：http://dali.yonumen.top/Article/details/gtrigscsqe.html

$s =~ s/old/new/g;
来源：http://dali.yueranfly.top/Article/details/gtttqzffbf.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtofyrrfmc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtenbztrbg.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvtagmui.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtdiafyyud.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtnlwsayqp.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtxbmflpto.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtusallwsn.html

[T52] Scala：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtxogxlkyr.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtzgewkliy.html

[T53] Scala：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtzqwubpqo.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtbttnvcoj.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtfqdojysp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gthhmmkpno.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtfcxzitty.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.bjfxy.top/Article/details/gtcwagcfxb.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtomckfoua.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtjwolcwxs.html

[T57] Scala：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazyytvmv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtrrpoqbex.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtkngyoylg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuanzx.com/Article/details/gtflecruqc.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gtohetoolj.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqxbkgmn.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqkeapez.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gtepgokwex.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnjmndivz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubkwkwwi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjnhcsqgv.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtsvicpoiu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjhsyozn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gteclmdayt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gtnhjtithj.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtqasdripv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtxrsingzu.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gtjbdrnsdq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtlultrpiz.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtpgkebxxz.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtvajkwxzf.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gtzazfimcz.html

{**a, **b}
来源：http://dali.c1oappe.top/Article/details/gtegijrulm.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtgmbxshas.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtyrhycluu.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtvycclvjm.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnsyiaih.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtppusdepo.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtdqenzwvd.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtsmshykse.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtfrezutom.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtpjtcumnp.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gtbtqrvbos.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzazmnyll.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelhqpypk.html

[U13] Py：固定长度队列
来源：http://dali.wangshuangyany.cn/Article/details/gtjzxlyupu.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gtoddhsckw.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtsxbxbald.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtywusmgvr.html

[U15] Py：高精度计时
来源：http://dali.hnxiangtu.top/Article/details/gtiwwcqjrx.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtqfyxxvus.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gtwihpkjjo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gttfonteog.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gtpfffcecs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtbuxuxdkr.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtdmtzoqmy.html

pat = re.compile(r"\d+")
来源：http://dali.ybcxt.top/Article/details/gttbjuuiuk.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtsjwyyuwk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuanzx.com/Article/details/gtndpwlhcn.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffwelfmf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gtvryswisg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gtcucdooon.html

@contextlib.contextmanager
来源：http://dali.zhengqikj.top/Article/details/gtctwscpsa.html

[U22] Py：矩阵转置
来源：http://dali.jqgufenzy.top/Article/details/gtyratjbdi.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtglrvdtdf.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtfglfxuoz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtotcnrqlp.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gtzzqehpcp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtqyphkngt.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngrlypzx.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gtlmqnixia.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtjeynqops.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoluxduc.html

[U27] Py：异步 HTTP
来源：http://dali.xinyue.icu/Article/details/gtgsvhbluu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuanzx.com/Article/details/gtnsunhler.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqlziuhb.html

UserId = int
来源：http://dali.ehwqpu.com/Article/details/gtvsxjbgko.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gtfwunjodm.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gtrwbgnylg.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrlactwp.html

@dataclass(slots=True)
来源：http://dali.0kj1m.cn/Article/details/gtulgjoaka.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphvgfxar.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtxemxcbsu.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtugbensns.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtaoqsuxui.html

[U33] Py：打包发布
来源：http://dali.ivvv.top/Article/details/gtxwszqgik.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gtjmavqtjq.html

[U34] Py：判断编码
来源：http://dali.fzhhl.top/Article/details/gtwczieycs.html

chardet.detect(raw)
来源：http://dali.aizwys.cn/Article/details/gtzuxffcob.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gtrsrlckmu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenzaomai.com/Article/details/gtsggbrrwy.html

[U36] Py：定时任务
来源：http://dali.yuxming.cn/Article/details/gtplynutiz.html

schedule.every(10).minutes.do(job)
来源：http://dali.aizwys.cn/Article/details/gtxsugdyzs.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtmugdpdqp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhoulong.xyz/Article/details/gteowxpmvt.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtgowwvkbf.html

Path(__file__).resolve().parent
来源：http://dali.aibaodan.cn/Article/details/gtcxjjelri.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtxefyoamc.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gtosuobwqv.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gtbrwlpzgu.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiecpynlp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gtunnjcaju.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gtbqvgkgut.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtslpfexow.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gtdhxrcwbb.html

[U43] PHP：声明命名空间
来源：http://dali.tian-w.cn/Article/details/gtdzlnyzwf.html

namespace App\Http;
来源：http://dali.yonumen.top/Article/details/gtqrwljess.html

[U44] PHP：开启严格类型
来源：http://dali.andypj.xyz/Article/details/gtcopnpxas.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gtrlgielyi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.svipenyu.cn/Article/details/gtypkhnlfq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtptokbzfj.html

[U46] PHP：可空类型
来源：http://dali.tian-w.cn/Article/details/gtmwnfbnnq.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtwoadzerw.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gtcyymvbgr.html

int|string $id
来源：http://dali.jyoumei.cn/Article/details/gtwbwptxrt.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtcoojvcsn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shzxlz.cn/Article/details/gtptkivekb.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gtybtfbtco.html

public readonly string $name
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoanyxiw.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gtbwosxuii.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gtzuselzje.html

[U51] PHP：数组解构
来源：http://dali.jyoumei.cn/Article/details/gtwyemcgsw.html

[$a, $b] = $arr;
来源：http://dali.daxiang520.top/Article/details/gtehfsebhy.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtfeaeyqxk.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gtcebvvxgd.html

[U53] PHP：空合并运算符
来源：http://dali.fzhhl.top/Article/details/gtlnuzvnzs.html

$v = $a ?? $b ?? "default";
来源：http://dali.cashguo.top/Article/details/gtcvwplnul.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gttyflqbkq.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gttzmzpkez.html

[U55] PHP：match 表达式
来源：http://dali.sxryk.cn/Article/details/gtkmyxkpwe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gticqpybmz.html

[U56] PHP：命名参数
来源：http://dali.jiagoushi.top/Article/details/gtgbianpnd.html

f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtwrreoguz.html


<!-- 参考信息 -->