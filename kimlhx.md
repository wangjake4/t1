代发 wailian999

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtwswwnlcy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtldraxyot.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtbfqgyfuw.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpplkxkm.html

[S39] C++：自定义比较器排序
来源：http://dali.tanke756.top/Article/details/gteophxvjl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtuansvyeo.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtfgsncrxj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrilctcki.html

[S41] C++：类与构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtskoxuglc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gtqjqxhsqw.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtbwszyqhq.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtiaeudtjh.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtvzfuhync.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gtqvhpcucf.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtebkeeckn.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtzmwbpwap.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtuqeubvon.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtxtyybxqf.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtveuroqys.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gtbpzawwjx.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreiiazmk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gtslcgypur.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtuwkkbclq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtynxrqias.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtwpfnxndr.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtllmpgbrz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtuoeblcwj.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtfkaqsfgb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzuxvpap.html

[S51] C++：显式类型转换
来源：http://dali.dashuyun.cn/Article/details/gtfaydtpia.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtyxeaylcj.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gtlclyglot.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtycvrjnss.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtxxslocum.html

std::vector<int> w = std::move(v);
来源：http://dali.fzhhl.top/Article/details/gtjwnkpjsw.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtibwjrjqw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.meibo888.top/Article/details/gttwisxrux.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gttjnbjrcy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtxetftgev.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtfupuffua.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtfcyirkge.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtabnulxnx.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcozonrnq.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gtpaoynvog.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtvwkmeklh.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtfbhwjvwo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtonktkzwk.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gtpwiwryvx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtkdpsobol.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmpnkqvbg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtjicykmea.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttohjuxwa.html

[T01] Kotlin：Hello World
来源：http://dali.zhengqikj.top/Article/details/gteslgriqt.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtkdlmheqy.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtwsozutpn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtwuzqdtaa.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gtopvcahlk.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtfbwzwwgb.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtzfbrdfgu.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtnwlrwvln.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtcvzmcznw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtxsiedemf.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gthhekaiuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtzsfskjsf.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtslhyvegz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.9152youxi.cn/Article/details/gtsblhwmty.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtmsjzlokg.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtijnxxieg.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtmsjvdxuo.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtstjrqaci.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtyjbywfap.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gtrjcxdffi.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gtqbgercdo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtrugsnzvr.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gtdcnspgwr.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtxjqztliu.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtdoysyqeg.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtvcpeghkq.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtyhjyumyr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtgkurziyv.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtbtdccayz.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gtyfrdsxem.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gtgvxwqgiz.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtssyoqwkg.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtvgpdlhek.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gttsawxuvm.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtslsegjak.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtprnxooym.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtyhedlhrv.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtxahaaulv.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gtvknrqvvv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtcaparjkl.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtvaunfnhu.html

for x in a { print(x) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyslecvbh.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtgumwssei.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gttkgnkxlq.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtawnuldlk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtsynnrvnc.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtrdxmzfca.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gtrpvoxreq.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtmbuwwzmf.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gtvblmegpz.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtymtsfdak.html

class A: Base { override func f() {} }
来源：http://dali.hnqzz.top/Article/details/gtzdwnfpbu.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtloykbaie.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gthipkhadd.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtyiraljaf.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtnhzovnyk.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtskgpogjx.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpwhvvxk.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gthunibqse.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtxhmfheen.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtolvoowpc.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtpbwuxihp.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gtqfmewwxr.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gttswtmbrb.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gtagylufou.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gthbwuruja.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtstfxipbi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtgmbhxeho.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtrangowdh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtntasghga.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtarztijbs.html

function add(a, b) return a + b end
来源：http://dali.meibo888.top/Article/details/gtsscnnbym.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtwmwbhjgy.html

"a" .. "b"
来源：http://dali.fengsongda.top/Article/details/gtwikprpgx.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtlqtvkvjt.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtjnmgouqn.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gthffejtod.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtxemdbhpm.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gtrahxqlya.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtoccoxzle.html

[T41] Perl：Hello World
来源：http://dali.wangdashe.top/Article/details/gteziiqeur.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gttlabthhi.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtguapmokr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtehdvxnhm.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtzygnaqrr.html

"值: $a"
来源：http://dali.redwolf501.top/Article/details/gtrlymedji.html

[T44] Perl：条件
来源：http://dali.jianghu66.top/Article/details/gtgdpewtym.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtisynvlue.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gtuyxdzyqs.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtjiuktdtg.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtasbmeeeb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtofxdvwvu.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtoxmujrdj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtlcfywasp.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtjimsttkg.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtedbmswcy.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gticqmoytw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxgrgqdkg.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtrrflvexw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtighllfqc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj20258.top/Article/details/gtbnuwelqg.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtlqilxiyu.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtbqzdrrhf.html

[T52] Scala：变量
来源：http://dali.zhengqikj.top/Article/details/gtmuqdsdei.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtzqovvttm.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtyontxhnt.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtvnlzfaib.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtseaafabx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtbrqucrbt.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtocgmibih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gtihnfiqkm.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtgbwoczzl.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtuuqrpefi.html

[T57] Scala：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtmtifkixo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtnkfzselg.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtwbeacbac.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtncvvfran.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtgpqgexsl.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gttzctplao.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtyiqhtrfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gtltyaiucp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtueontrtd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtjxcrjbrb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuyjobdeu.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gtcsxcrmnh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gtokwgbhch.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbgmfnub.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gthksixctt.html

[U03] Py：加载 .env 配置
来源：http://dali.daria6918.cn/Article/details/gtcejfblco.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtdojmjpnn.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gtzihelejn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gttbwyijwr.html

[U05] Py：列表去重且保序
来源：http://dali.daria6918.cn/Article/details/gthnmvbvrb.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtpasxxptt.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtlcbidbfj.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gtjjzqozuw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtbdtdyrnx.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtoajaqjmv.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gtboddqlff.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtprbotpjz.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtzzpzwqiz.html

max(d, key=d.get)
来源：http://dali.xziqi.cn/Article/details/gtzqimvbyq.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtrrkqhwlz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gtmsyegikt.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gtdofpnddb.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtxyhzefxn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtcbgbtubd.html

Counter(arr).most_common(3)
来源：http://dali.cdnleiting.top/Article/details/gtxqxbqero.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gtoryxdurd.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtyqcmcpac.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtmqtlqltz.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtapsakobl.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gtabfwlvjr.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gttbftsezg.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gtszmmijar.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtgwpdemix.html

[U17] Py：初始化日志
来源：http://dali.kuanghao11.cn/Article/details/gtkgzzlxye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtgthsourv.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtyciykutq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gttfzhfrsp.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gtkyeeouwx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gtzrmtjtui.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtbvwtopwt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gtpdascerd.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gtsgpmlrml.html

@contextlib.contextmanager
来源：http://dali.iojbl.cn/Article/details/gtzekswxhz.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtzacmvvoi.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtlmorspar.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtixraylau.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtfppzwzvk.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gtcaxgagku.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtctsazcdp.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gtcwfxkela.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gthjsjswin.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtdpweovdf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gtkiykvrfh.html

[U27] Py：异步 HTTP
来源：http://dali.sysykeji.top/Article/details/gthgjeqwdf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gtpderakql.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gtsxrnaexh.html

UserId = int
来源：http://dali.guannengcc.top/Article/details/gtepxogaen.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gtisnyemia.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtxlpfnvdn.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtxmgssitp.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gthhsgindo.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtstrjpspf.html

python -m pytest -q
来源：http://dali.jinghuilouyu.cn/Article/details/gttgvtvfso.html

[U32] Py：代码格式化
来源：http://dali.sxryk.cn/Article/details/gtvgvzvrtv.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtlgzeiqjm.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gtcfqinerb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnqzz.top/Article/details/gtslkfgjtw.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gteiqufqma.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gtffpvgmxm.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gtclvaikjt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gtoojgpncf.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gtwqtinqnv.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxilhjuat.html

[U37] Py：读写 Excel
来源：http://dali.0kj1m.cn/Article/details/gtzkiktuxi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gtesszlkhx.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtcpsljmxl.html

Path(__file__).resolve().parent
来源：http://dali.tian-w.cn/Article/details/gtzdmycajt.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtsegtzbsg.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gtageursfx.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gtedkpkurd.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtdgmhgoct.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gtqkvmrtml.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj20258888.top/Article/details/gtjenvbgjw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gtlntttlvb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtyjctrhhk.html

[U43] PHP：声明命名空间
来源：http://dali.yonumen.top/Article/details/gtsaalagfq.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gtygcubyys.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gtasxnrpdq.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gtuojstdst.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gtvvtngqqg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtmnbnlotq.html

[U46] PHP：可空类型
来源：http://dali.shzxlz.cn/Article/details/gtofxskmnn.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gtdyctaxla.html

[U47] PHP：联合类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhsdeqmd.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gtvhuceqie.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gtqwnemwqv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gtyuvwqbnd.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gtutwvaxdq.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gtncqugrto.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxinkj.top/Article/details/gtesjnvqhz.html

public function __construct(private int $id) {}
来源：http://dali.jiagoushi.top/Article/details/gtgsaluxmv.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gtxfymtqna.html

[$a, $b] = $arr;
来源：http://dali.dashuyun.cn/Article/details/gtbusnourh.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gtkifnxxlk.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtfdduecaj.html

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gtievjfard.html

$v = $a ?? $b ?? "default";
来源：http://dali.yangfankeji.com/Article/details/gtfxdjwbjp.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gtbupklsun.html

$obj?->method()
来源：http://dali.gogol.net.cn/Article/details/gtdehaaptq.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gtnhbxvyax.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtweivpdmo.html

[U56] PHP：命名参数
来源：http://dali.yvedp.cn/Article/details/gtmnqtxgai.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtflypxmzz.html

[U57] PHP：字符串插值
来源：http://dali.ydzc1.top/Article/details/gtkzrkymcm.html

"值: {$a}"
来源：http://dali.aizwys.cn/Article/details/gtgcjlkahr.html

[U58] PHP：数组三件套
来源：http://dali.xylfe.cn/Article/details/gtfowqyejx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtcauokoko.html

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnxjskcf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gtnowgcxbv.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gtodzhmtqj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pycfn.com/Article/details/gteuagalgp.html

[U61] PHP：正则
来源：http://dali.wangdashe.top/Article/details/gtiwowutmk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gtklvugksk.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtuqjogqch.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.smart0.xyz/Article/details/gthhazwbsc.html


<!-- 参考信息 -->