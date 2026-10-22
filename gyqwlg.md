代发 wailian999

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtkjkcbypt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtgiibpnzd.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gtdlehvptx.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtsrxoycau.html

[S33] C++：vector 增删
来源：http://dali.daxiang520.top/Article/details/gtyzpzzazp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtfiulutaf.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtttbpkehh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtagpszupi.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtlfwosqpp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtesdltxen.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtzqpcejzg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtrcydbthg.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtmleuyucp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtxfzcqjmz.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gttfivjwnc.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtgjwxzsyr.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtuydbvysv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dashuyun.cn/Article/details/gteaumwirr.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtplcztnvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtesmaxesy.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwvrjwmr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtcwzpmpbt.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtgzmdlwjf.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtjeduiehh.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtavfrhrxa.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtvsuskywx.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtxigmeich.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gturgvmxft.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gthytedeuy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.316326.xyz/Article/details/gtljhyzihp.html

[S46] C++：函数模板
来源：http://dali.dashuyun.cn/Article/details/gtoycdalmh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtkxqfhlcb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zycfv.cn/Article/details/gtwypmwhzd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtcsgnafiy.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtjxwgstvb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtkpcmiqyo.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gticktcyzk.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtixvnqmsb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtpgjtyzuy.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gtncaksrcj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtjtbjsppm.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtgfzzljzf.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gthvleajve.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gtybaxahap.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpjmeymq.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtuienaheg.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtxhgxaelz.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtpiroxjxu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdyurfppz.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtjpmtyejv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtrntgvfbe.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtikugksfi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtudrsanrt.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrrbhjcb.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtskuczmoh.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtvaljvmjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtndgktvif.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gthfibcuee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtlsmbtuam.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gthatwbfly.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtrazzjrvz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkffmswiy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtajkpkokk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcsfktihw.html

[T01] Kotlin：Hello World
来源：http://dali.gzhubu.top/Article/details/gtlbzwgrih.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtuftivsqg.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtmjfhekrk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtiejpxyqt.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtnzcthozz.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtxsnnajob.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtwmwsgjqh.html

val n: String? = null;  n?.length
来源：http://dali.yuxming.cn/Article/details/gtknjvhkgg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtabirthed.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtobzefpxs.html

[T06] Kotlin：集合映射
来源：http://dali.jqgufenzy.top/Article/details/gtffpzwnnb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtesslvvhm.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtdpgksdoj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtwpkeeavw.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gtwpqbviis.html

data class User(val name: String, val age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtunfkeiew.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtmlxeoysq.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtmldbijlg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtehkmgqlt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtfjsvjkyb.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtuttnrpvd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gthqtttdai.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtsrnsblzf.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtxxblwfcd.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsxokoob.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcjrjlat.html

[T14] Kotlin：循环
来源：http://dali.quarkkingdee.top/Article/details/gtuvntgmwh.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjnreomc.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtignvaaik.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gtctnvaujp.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtdixwajyj.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gthttwhdsb.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gtnhxfyujo.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gtnkwrppcj.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtugfuhjrm.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtqzzpjbzj.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtnelhcfce.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gtaozxarav.html

[T20] Swift：数组操作
来源：http://dali.yj20258888.top/Article/details/gtxnodktbu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtpjulekrv.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtgmpdquhj.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gtgnmguhfm.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtbhjopdwu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtudtqyrpa.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtsiwvcumh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtbcaibksc.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtwtryopma.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtnyiuhpwx.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gtbmiuagoh.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtppdevqyo.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxihstsu.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtwdolbluc.html

[T27] Swift：错误处理
来源：http://dali.havefunace.top/Article/details/gtlmnzojte.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtbqfmgynd.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtzsamdyzn.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtumfwsezw.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtkvajcisp.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtmrrudgwn.html

[T30] Swift：协议
来源：http://dali.hammf.cn/Article/details/gtiuvhsgrd.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtuulkcyxz.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtoanyaitm.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnrlugdv.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtdehxxirr.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtpyxxjmlc.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomrwuhwf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtnvnelfhs.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gtvimgsokp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtwoytznoi.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gthruvyrvw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntypahhw.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtgmibejdz.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtosnxvqer.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtnmnsaatf.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtnpchvurr.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtjxznaxib.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtysyyczcs.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtvzegweuw.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtxskorbep.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gttrunyimw.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtajswxoai.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gtwrvvejqa.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtojyegfuv.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gthievwewd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yangfankeji.com/Article/details/gtqfqdldvd.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtxjwokexs.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclanwzij.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtwpoaareb.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gtzzzpgokm.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtjowjudym.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtcquofilh.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtoquidikw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtlvtgrpad.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtbbavtguy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtxexwmczz.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtpipbgupm.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gtaodeeaij.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gtpwyetfvw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngvmiiye.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgzshnyad.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgufenzy.top/Article/details/gtiatafpge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gtofwmzcwt.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtvythjzrc.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtqakwfhjx.html

[T52] Scala：变量
来源：http://dali.zhongyouzk.top/Article/details/gturxhpxro.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtswhqgbwf.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbbrsupt.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtgblrsmdf.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtkivrlzgj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gtjbqftpnv.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtuycifiuk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtdvehvaps.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtfaveqctj.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfolplwy.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtlvejdlch.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gtvqdeqivb.html

[T58] Scala：函数定义
来源：http://dali.feifeiyinyue.top/Article/details/gtpvfqvnyw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtrvhrsakj.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gtxroikguh.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtfoimucpf.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gtbtnpcjur.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtknjkjjsc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmwrqbol.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gtfibobfat.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlwtyfwgz.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtdadvhzjv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cdnleiting.top/Article/details/gtnektdbiv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtwuegiyqn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gtalekhslf.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtsxzmskhi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtvknlgorg.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtgtpbuvma.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtwotxlgbk.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtubfqjdfl.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmpocobr.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtoimermee.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtyjzlcuxu.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gtwmunxnhd.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtzrutbfxy.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtsbnbblxk.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gtibnkfiop.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtjtpjzhen.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gtgamnjjhy.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gtkjksefvp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtbvohluyf.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtlrzjhenj.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtjvhirwcd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gtdxanmlaa.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtsmrmgsvz.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gtxqrynnes.html

deque(maxlen=10)
来源：http://dali.yj20258888.top/Article/details/gtdjqybwfx.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtjkfllmck.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtgbwmadma.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gtfwildtir.html

t = time.perf_counter()
来源：http://dali.jinqigufen.top/Article/details/gtpseodbrt.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtdgdrcnih.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gttmjfqfns.html

[U17] Py：初始化日志
来源：http://dali.cucudq.cn/Article/details/gtpejusdzm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqdinrkd.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtxfohsuzu.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gtuccgcamv.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gtlyeumkrz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtniifvffo.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gtaqoiexnu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gtcquknktj.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gtwywlkodc.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtmvjgpxqs.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtoujvbrys.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtlayuiszj.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtraoxofbq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gtmmgvqmqd.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gtedxgjqln.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtxhqpegih.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtnjppbqku.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gtsuxmwzxc.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gthzgpsnri.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtwsyrimqr.html

[U27] Py：异步 HTTP
来源：http://dali.mhx1999.top/Article/details/gtvrgnfnwq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtiilszcih.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtoqgpcqzr.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gtlkpshplj.html

[U29] Py：属性校验
来源：http://dali.jianghu66.top/Article/details/gtdtyeaxix.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gtrfkavfgy.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gtixdgrcgo.html

@dataclass(slots=True)
来源：http://dali.guowangkeji.top/Article/details/gtjtrsymjc.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gtgiodmpcr.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtlrbgzanb.html

[U32] Py：代码格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtlwyotrjf.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvzibikl.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtyldpoihz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daria6918.cn/Article/details/gtyluisyag.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtheqdtzii.html

chardet.detect(raw)
来源：http://dali.yuxming.cn/Article/details/gtoeevgjdk.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gtpeoklxop.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gtotojwpse.html

[U36] Py：定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwtehnod.html

schedule.every(10).minutes.do(job)
来源：http://dali.hongshengwenyu.top/Article/details/gtcziozgev.html

[U37] Py：读写 Excel
来源：http://dali.wangdashe.top/Article/details/gtyhlbkmtf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtucmybujj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gtypeigaev.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtvoekruhw.html

[U39] Py：判断是否在交互环境
来源：http://dali.yonumen.top/Article/details/gtmscjziic.html

sys.stdout.isatty()
来源：http://dali.chenzaomai.com/Article/details/gttmenzyoq.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gtkspyseqg.html

print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gthnodlozl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gtexazimfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258.top/Article/details/gtsqqmdzoy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xziqi.cn/Article/details/gtrsiwkrxx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gtsckwoqny.html

[U43] PHP：声明命名空间
来源：http://dali.jianghu66.top/Article/details/gtlfwtdfvj.html

namespace App\Http;
来源：http://dali.aizwys.cn/Article/details/gtzxnpggsn.html

[U44] PHP：开启严格类型
来源：http://dali.yonumen.top/Article/details/gtvjlhrdsh.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gtloqbdnte.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhongyouzk.top/Article/details/gtwwxxlynd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtfhkvfcva.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gtopssitbt.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtqrzdaruw.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gtmhdhknfl.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gtghajbird.html

[U48] PHP：纯枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtmrpqnjwq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyxsnfjlt.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gtlmbpaslo.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtgxvzbteo.html

[U50] PHP：构造器属性提升
来源：http://dali.yueranfly.top/Article/details/gtloegfnlq.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gtallqmfaj.html

[U51] PHP：数组解构
来源：http://dali.daxiang520.top/Article/details/gtxyawfgat.html

[$a, $b] = $arr;
来源：http://dali.xuanzx.com/Article/details/gtihckmcki.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbhxhfts.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gtcqqayewh.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gtjfhbqbsv.html

$v = $a ?? $b ?? "default";
来源：http://dali.c1oappe.top/Article/details/gtjfwlwebe.html

[U54] PHP：空安全调用
来源：http://dali.0kj1m.cn/Article/details/gtsneoalzy.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gtkaxazgju.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gtmrxvhmlb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtwopsppvy.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gtlydjmwnm.html

f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtddrobplw.html


<!-- 参考信息 -->