代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtpjcotndh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtkhujnrsd.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtbxrqwuby.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtzcairvcq.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gthifikyzl.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdpfghhf.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtmqpbgexq.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtusmqahcd.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtokkmibqh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gttjcbopta.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtzocaxslf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvuloopaf.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtaahwdzkf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gthmangkof.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtinmzkpkf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtucfjrqis.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtapztcrqk.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gtjxjleubc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtrtvekavm.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gteqfzxigk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtxfjjajqd.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtaydbmxov.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gtdmtoxsaz.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtwcmukirl.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtbqzwkwxq.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtunffidsw.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtgwrgtrkh.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtgjebuoqi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtwgqzdwud.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvrgjycp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtqmdisphh.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtcowretpa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gtxompynzi.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gtkolpfzot.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtxkjdaidx.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtahjfjhek.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gtacpcoytu.html

[S59] C++：静态断言
来源：http://dali.iojbl.cn/Article/details/gtudpmlcwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtlfzuhvvd.html

[S60] C++：遍历并删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtlsnyiwaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtssuyywqq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtupgznzso.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aibaodan.cn/Article/details/gtcvfwfrhg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtfcggdobk.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gtnbocsgyn.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtlzggdouj.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gteajqdgmy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtwfxwmsor.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtedohkjyy.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gthxvahxzy.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtisjcggjr.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtgrxibpug.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtwvzepjss.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gotoacloud.top/Article/details/gtinbeedyw.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtsygrexcl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtnxjdjttv.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtnamnaipu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtysfzjcey.html

[T08] Kotlin：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtnbqjtxql.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtzlwpjbti.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtiyijcqws.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gthlzywexy.html

[T10] Kotlin：默认参数
来源：http://dali.jianghu66.top/Article/details/gtmuciorrc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtjkxcadik.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtlopxncxo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtpnwnhwga.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtevxbphqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwwnzukt.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtphbvwhka.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtpypymnvp.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtcyweuzjm.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gthuuviydt.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtjlnreams.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gtghucezsz.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtzjswfamd.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtpxiocjsv.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtzzyokuft.html

var a = 1;  let b = 2
来源：http://dali.snrcjt.cn/Article/details/gtbaissoia.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gthddfxzob.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtabaljeal.html

[T19] Swift：可选绑定
来源：http://dali.gaohongyu789.top/Article/details/gtibamkukd.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gtakpozzga.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtabxkpgak.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gtittyncfr.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtthemdrvw.html

for x in a { print(x) }
来源：http://dali.gogol.net.cn/Article/details/gtcwjxkfjx.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gttonuiiym.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtvqbpenkx.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtnhqgpoxy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtfqpgjuwk.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtmdwqefqr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtlqezbvud.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtsucbalwd.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtiwycpypq.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtmjtrihyq.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gtthqqglbd.html

[T27] Swift：错误处理
来源：http://dali.guowangkeji.top/Article/details/gtbdcvdnug.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtsxhyvwng.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtlnhifoyk.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtsyhetvnb.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gthkwnpola.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtlhrlsjdj.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtsqulwups.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtgqocjvdk.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gtugxfzzgt.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtyyefscqy.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtelymkvdf.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtnwtrrctu.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtphjmiaqt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtxikfmyzj.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtbktnpzpt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shuidangran.top/Article/details/gtgvdjybfe.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtnnzfcpxf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtwqnybxfu.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcsqbdmvv.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtngedtfvy.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkannqtmi.html

"a" .. "b"
来源：http://dali.hongshengwenyu.top/Article/details/gtqsdqvtft.html

[T38] Lua：条件
来源：http://dali.cucudq.cn/Article/details/gtftdbzatx.html

if x > 0 then print("正") end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlcuphqp.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gteqmtrmmj.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtnrhjqbij.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gtuqxaxxmn.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtxigzonjh.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtjewrvyaw.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gtnmtftleh.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gtasglhtch.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cqqwz.cn/Article/details/gtatkclbju.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtvsdhitzk.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjilexlc.html

[T44] Perl：条件
来源：http://dali.ppjwa.cn/Article/details/gtmzluzcrq.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gtllilcdtc.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtnqkddtax.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gtmsgkwzyi.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gtllwxhnod.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtzhlykdvu.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gtzikbuadg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtkqfomvnp.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtsszsfjlv.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gthnlyymnh.html

[T49] Perl：函数
来源：http://dali.snrcjt.cn/Article/details/gtjuaieuhw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwuenzsfi.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtjlybfvij.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtbvrvsddd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkzffuqfk.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtemvubgdw.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtnihlmscj.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtjmkiccif.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtpzogyfrj.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtbvosmfnp.html

s"值: $b"
来源：http://dali.yj20258.top/Article/details/gtzqfhpzve.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtatlhiyhk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtmzlyamde.html

[T55] Scala：集合过滤
来源：http://dali.hnxiangtu.top/Article/details/gtbuhqwxfn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gtwnrwwxcv.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtqhpmycls.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtwocnvxls.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gtunsobtua.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtrqkiolsd.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtheexzzgt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tianlin.xyz/Article/details/gtdcwbptue.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtsofyexyw.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gttkndedwp.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtancdluai.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jianghu66.top/Article/details/gttbfoymps.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtcqipsdib.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtnayaxseb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfzpgjkrc.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gtwglcqslw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtnvjqzgzv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gttmxsmmek.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gtfukueslc.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtsgixieta.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.pengpengdd.cyou/Article/details/gtesfudaix.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gthluqwarc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gtutwknkqn.html

[U05] Py：列表去重且保序
来源：http://dali.aizwys.cn/Article/details/gtpbocsxbq.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gttgizciym.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtbrwwnckz.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtzyzjcnit.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtcpzmplzz.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtlxtxpysa.html

[U08] Py：展平二维列表
来源：http://dali.gogol.net.cn/Article/details/gtdcfwsdyy.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gtnqxziblr.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gtmbbmgftv.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtndakhwzk.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gtqaevpdba.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gtbixdhxkp.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtuzyujgfn.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmpbbnfpg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gtafajucnq.html

Counter(arr).most_common(3)
来源：http://dali.andypj.xyz/Article/details/gthrntzxqy.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtdfrgppoj.html

deque(maxlen=10)
来源：http://dali.yuanzhike.top/Article/details/gtwnpkwytz.html

[U14] Py：分组收集到列表
来源：http://dali.fzhhl.top/Article/details/gtrrroyfdz.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtoycsundu.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtzxhdlgps.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gtjstrsoqd.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtnpxfwvqf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gtsfaaunjj.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtskkbfefg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gtgoebmlxg.html

[U18] Py：预编译正则
来源：http://dali.jiagoushi.top/Article/details/gtvnnvzjst.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtqpbkushj.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtdiewvyoq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gtyotpptst.html

[U20] Py：缓存函数结果
来源：http://dali.xuanzx.com/Article/details/gthyxjzdsj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtteuritfv.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxinkj.top/Article/details/gtwjykjdyh.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtbgbgmsyc.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gtwxklqhep.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gtpdxgizlk.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtmohtrtqc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gtuttqmtvh.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtlodinnmo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtutjdxdma.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtkbgbffvq.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gtvwourpex.html

[U26] Py：并发下载
来源：http://dali.jinqigufen.top/Article/details/gtwapgejul.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gtfxqwdaew.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gtgdpxjnth.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtliulnjgk.html

[U28] Py：类型别名
来源：http://dali.guowangkeji.top/Article/details/gtnldbemor.html

UserId = int
来源：http://dali.shanyushiyangtech.top/Article/details/gtppumqjxm.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtdjesurnu.html

@property 与 @x.setter 配合
来源：http://dali.jinqigufen.top/Article/details/gtfzqubsoh.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtqrnnlqsn.html

@dataclass(slots=True)
来源：http://dali.xuanzx.com/Article/details/gtudbrbrgb.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtotwywleg.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtmoygaxhe.html

[U32] Py：代码格式化
来源：http://dali.zhoulong.xyz/Article/details/gtiigjklcp.html

ruff format . && ruff check --fix .
来源：http://dali.jlsjyb.cn/Article/details/gtgdkgvsys.html

[U33] Py：打包发布
来源：http://dali.kuanghao11.cn/Article/details/gtnnsdybhy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtoyulsgqc.html

[U34] Py：判断编码
来源：http://dali.ybcxt.top/Article/details/gtibiwnxgk.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtajbiqbdi.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakyazfrf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gtdszkcdau.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gtnluchzfv.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtavorzvzz.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gtlyaazoaf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sysykeji.top/Article/details/gtzmtyqnkc.html

[U38] Py：获取脚本所在目录
来源：http://dali.guannengcc.top/Article/details/gtcltxqfwp.html

Path(__file__).resolve().parent
来源：http://dali.jiagoushi.top/Article/details/gthfhcjonn.html

[U39] Py：判断是否在交互环境
来源：http://dali.kuanghao11.cn/Article/details/gthfqygdcy.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtnaxfhkug.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gtbysczgxq.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtnihchnrf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shuidangran.top/Article/details/gtkiogrplm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtvpggrhfb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sxryk.cn/Article/details/gtvmrmcqcc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gtybtwceuw.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtpftunulb.html

namespace App\Http;
来源：http://dali.yangfankeji.com/Article/details/gteabnetyw.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gtalrlxguy.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gtfamtptku.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sweek.top/Article/details/gtoooomrbr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtswwbiejj.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gtzogehann.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtglrgqyeq.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkubzhbi.html

int|string $id
来源：http://dali.pengpengdd.cyou/Article/details/gthwpqfdpe.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtktrohxjf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gtyoshkyjn.html

[U49] PHP：只读属性
来源：http://dali.yuanzhike.top/Article/details/gtfvtwhimg.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gtoskvrxzt.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gtncdnewyj.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gthoiyaocc.html

[U51] PHP：数组解构
来源：http://dali.yonumen.top/Article/details/gtcjfcsixk.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtztnrssyz.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtupmkvvhd.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtilvloqdr.html

[U53] PHP：空合并运算符
来源：http://dali.dianchejie.cn/Article/details/gtkjcpgnbo.html

$v = $a ?? $b ?? "default";
来源：http://dali.jyoumei.cn/Article/details/gtehnoybfc.html

[U54] PHP：空安全调用
来源：http://dali.cheryme.top/Article/details/gtqqbbgyte.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gttjmvkjkc.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gthwajhmql.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtrhefcdne.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gtgqtuycyo.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtvlnsbicp.html

[U57] PHP：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtdydhykby.html

"值: {$a}"
来源：http://dali.nwbrower.top/Article/details/gtqsngcdmv.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlhleunw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gtlurwdnky.html

[U59] PHP：自定义排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdttipmy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtqfkxmkmw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiispofvo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbuxuzow.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gtmxszmony.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtexxhpiua.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtmczdlslr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.c1oappe.top/Article/details/gtzqoxhxzn.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gtdserwunq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ehwqpu.com/Article/details/gtfrjvayyf.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gtzuvrunko.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gtvihlxpvd.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtsvuzrxyl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtnbmoajan.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjukussc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yanxiufei.cn/Article/details/gtyxezmkek.html


<!-- 参考信息 -->