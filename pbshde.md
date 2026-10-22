代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gt2vhojbocc.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gt2dvpahedi.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2rzrrvmhy.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gt2mlfpgcoi.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2duwqhhwf.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lthrqutp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuliiqfz.html

[S30] C：头文件保护
来源：http://dali.jlsjyb.cn/Article/details/gt2qpuilcsf.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwdqkwsv.html

#define X_H
来源：http://dali.nanxinkj.top/Article/details/gt2ivwndrwe.html

#endif
来源：http://dali.guannengcc.top/Article/details/gt2efrmoblf.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2pgnwfgpd.html

#include <iostream>
来源：http://dali.cashguo.top/Article/details/gt2abkmlttb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gt2doxnhrtm.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfaslpnv.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gt2ivguksfx.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2rcvlsbiz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gt2esyluviu.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gt2ehjrxftp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gt2ltsqsecw.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2quiusvgf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgiupcdb.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gt2evfihhvm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2xuobftpj.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gt2gbqsvaxa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2zwoyozhn.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gt2zhyfstqc.html

std::sort(v.begin(), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2tzqqstlr.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gt2xoihbcjv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gt2chkkcmqh.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gt2hbgniknk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gt2butqkdnv.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gt2rtdxqozl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gt2pbdawecy.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2jynkkbki.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gt2czorlyly.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gt2kqlsvqce.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2yygcsrhs.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtpsojti.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wfixtpdf.html

[S45] C++：lambda
来源：http://dali.yj202588.top/Article/details/gt2qhxhcrrz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gt2tzbgsfby.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gt2mezlnvga.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gt2mvbzmqrf.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgxabspi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2eciwrvih.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2zgkbqhnq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gt2relhcmeh.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gt2ajielrca.html

[S49] C++：写文件
来源：http://dali.gzhubu.top/Article/details/gt2vdhchnkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gt2gixddzln.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gt2xcbciejv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2cnqybprz.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tyyukbsf.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yaioimqb.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gt2slcvtynf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afehxguj.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gt2tyoiaxet.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gt2tieiojxg.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2avnzejuc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyhepzon.html

[S55] C++：结构化绑定
来源：http://dali.cqqwz.cn/Article/details/gt2rexfeazf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcmwdlon.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dejrlqyz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gt2axcwkguh.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2fwmhvnmv.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2rvtpcuzx.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gt2mnnlnmrb.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gt2qecezitb.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2xetwtiip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2fdnpqbgy.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2ayuidqhz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2oauixurx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2bkjrejjh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gt2utkambsm.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvizbfzo.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2jtelzzoo.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2yyxvkwzt.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2yzkkfuap.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2hnsxvuap.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gt2nxxflhjw.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2bfeedban.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gt2nxgdvfix.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gt2trjfytyx.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2juvevzyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kgoqgzqh.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gt2pjeczdlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gt2bhwrkdef.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2xkqywtwq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gt2nyipoall.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvfkqeix.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gt2qtzwimxt.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gt2spmtqwvh.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gt2pnipmkef.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gt2yjcvkori.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gt2lxwcacns.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gt2etvakzuh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlkihulz.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gt2kjdmpvdp.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2ouebcerk.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rydhtwxo.html

val m = mapOf("a" to 1)
来源：http://dali.nanxinkj.top/Article/details/gt2vvdbllmy.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gt2pqyklxxc.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybtrjgfd.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gt2mmokrikc.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gt2wzasnoks.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcwzqlkm.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2ldlrtxqv.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2dworuasx.html

var a = 1;  let b = 2
来源：http://dali.xziqi.cn/Article/details/gt2aiekvhzc.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2calupzsn.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gt2hpwmkzky.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqwvuyjg.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gt2nrejzdsb.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2ldmgzdfz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gt2mcmmgksw.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2jfxmhgxd.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gt2mlclixeo.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gt2etyxzzdt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gt2cbvlbzzn.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2vibxpzyc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoczplcp.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gt2zfhqtvmx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2dxgmwmek.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2wjiikuhx.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gt2icvbkocx.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gt2peyclxkf.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2jemjhozr.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gt2ahhlzsqz.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gt2gcpbdzqo.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gt2cnanjsev.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kigmknez.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gt2kxhttotv.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gt2sponkmxa.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gt2guollryv.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gt2mmpuulrs.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugrgkktf.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2iwjdziae.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gt2ckghbyrh.html

local a = 1
来源：http://dali.cucudq.cn/Article/details/gt2oxgkbpmq.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gt2vuejsczk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gt2owflqvja.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gt2xshortcq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gt2swajfogt.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gt2gddtxsti.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2jenestod.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gt2axianzjr.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztpoyndk.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gt2loynycua.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2pkrhomti.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qoxaqbcf.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gt2xojvyzpo.html

[T39] Lua：模式匹配
来源：http://dali.fengsongda.top/Article/details/gt2yomjuujx.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gt2alfeobhl.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gt2qmdecyei.html

setmetatable({}, { __index = base })
来源：http://dali.yangfankeji.com/Article/details/gt2tykcbslk.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2kqnmbdpk.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2plwaklhy.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gt2itzwosba.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gt2lxhaybwt.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2ynudtfwj.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gt2olvhrxgw.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gt2tmvuehkw.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2feyfvmap.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2wskkdbdn.html

for my $x (@arr) { print $x; }
来源：http://dali.sysykeji.top/Article/details/gt2qwngabcb.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gt2pzzspaci.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2srckdsym.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gt2csatdlcl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqjwctkk.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2kdduizya.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gt2tvglwaro.html

[T49] Perl：函数
来源：http://dali.nanxinkj.top/Article/details/gt2poesgqcl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2kxhhemkf.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2uauodcqr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gt2sezpiopo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gt2byardezh.html

[T51] Scala：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2jvsuvfmx.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2tertqsml.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2mtjdplop.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gt2citufdfm.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2ndrhkkhq.html

s"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gt2wvbpdvuj.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gt2rsqyvlco.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gt2qgzsnvxp.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2kolrxlmw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2bwbplzsb.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gt2acpqvuqx.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gt2damndzag.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gt2hplrjdia.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2smindnzr.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gt2hfxcqgag.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gt2ulzfmgpw.html

[T59] Scala：循环
来源：http://dali.hammf.cn/Article/details/gt2yjyogzyc.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjwcooif.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gt2xmlxrymi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rohaoskm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2bthxqucf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gt2lstcynwi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2woyehhqb.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gt2tcvuvodl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gt2ktytkqko.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gt2bzsnpbne.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gt2akuisnxi.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gt2jilnywhg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.dianchejie.cn/Article/details/gt2ryaujpni.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcckwmsy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gt2jgisjbqt.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gt2westuwdn.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzyzwwew.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gt2ddcxlven.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fodncjpb.html

[U07] Py：反转字典键值
来源：http://dali.ivvv.top/Article/details/gt2oufxyscx.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258.top/Article/details/gt2smyzrdoi.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gt2aewcwvlq.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gt2hdqrkpby.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gt2tkmhxqvr.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvouigfh.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gt2clgevmrn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gt2vwamepfq.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gt2ympxvpwv.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gt2fbeplvty.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gt2jplcjusd.html

Counter(arr).most_common(3)
来源：http://dali.xziqi.cn/Article/details/gt2dqczzbtg.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gt2atxvycbq.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gt2cfnugdvw.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gt2allnebai.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gt2htmzfhgf.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gt2tmgnnxdd.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gt2hynrgiov.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gt2uizwoues.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gt2vazussyl.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gt2xuzfhzdh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gt2cmjumxnr.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gt2uscmgkye.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gt2pjskbenj.html

[U19] Py：正则替换带回调
来源：http://dali.zhengqikj.top/Article/details/gt2izfpimga.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gt2gdqialwn.html

[U20] Py：缓存函数结果
来源：http://dali.yanxiufei.cn/Article/details/gt2mammidoy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gt2iyugxmei.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gt2zobwlopo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2itnusrqx.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gt2kumchuwy.html

list(zip(*m))
来源：http://dali.yj202588.top/Article/details/gt2mcyyhcsx.html

[U23] Py：分块读取大文件
来源：http://dali.fzhhl.top/Article/details/gt2gbufegoa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gt2kvqwblay.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gt2blpbgnkw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2kpqwkypv.html

[U25] Py：CSV 按字典读
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnxuuekb.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gt2ayppagwy.html

[U26] Py：并发下载
来源：http://dali.ydzc1.top/Article/details/gt2gbusymeb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gt2toouqfot.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gt2zgtyxqub.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gt2wuafsopd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmrbebk.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gt2szzrwcbb.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gt2qlrgippd.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gt2kvjyymjd.html

[U30] Py：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmzjjcfl.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrjbuzgs.html

[U31] Py：单测
来源：http://dali.guannengcc.top/Article/details/gt2kxbzmjip.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gt2qzjdkaxk.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gt2abgefmrs.html

ruff format . && ruff check --fix .
来源：http://dali.cucudq.cn/Article/details/gt2pzrrxcgf.html

[U33] Py：打包发布
来源：http://dali.havefunace.top/Article/details/gt2povpitue.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gt2nvbdmiis.html

[U34] Py：判断编码
来源：http://dali.xylfe.cn/Article/details/gt2lvntspoy.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gt2uoaiuxyl.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gt2prydfdjj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gt2kzfvbvdf.html

[U36] Py：定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2ajhxkjuc.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2xypwubgw.html

[U37] Py：读写 Excel
来源：http://dali.xziqi.cn/Article/details/gt2nogwnlfk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvqivsjw.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gt2qkqablpp.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfiicudu.html

[U39] Py：判断是否在交互环境
来源：http://dali.cashguo.top/Article/details/gt2umwvivgx.html

sys.stdout.isatty()
来源：http://dali.nanxinkj.top/Article/details/gt2aqifcxis.html

[U40] Py：打印到标准错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvvkwbyr.html

print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gt2rawjucfi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zdqjudy.top/Article/details/gt2iqpkubkj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gt2uljrwlab.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jlsjyb.cn/Article/details/gt2gceuwhfr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gt2pbgryiwa.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gt2seofigud.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gt2bviyinen.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gt2ptavlmls.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gt2spxoanak.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gt2swpmuyug.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2bhwyuvth.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gt2shpudple.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gt2eyilwnik.html

[U47] PHP：联合类型
来源：http://dali.ehwqpu.com/Article/details/gt2ncsovflg.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gt2moshkejk.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gt2ashaomoj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gt2slrxwpro.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gt2vzffjtcb.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gt2wvhtwybo.html

[U50] PHP：构造器属性提升
来源：http://dali.cdnleiting.top/Article/details/gt2uitguavp.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gt2uhckwaeq.html


<!-- 参考信息 -->