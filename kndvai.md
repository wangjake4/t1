代发 wailian999

[S35] C++：map
来源：http://dali.pengpengdd.cyou/Article/details/gtwrerhttn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtyhaizrpd.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtsyjmmjce.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtemklbust.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpdaeoom.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtixdczgku.html

[S38] C++：排序
来源：http://dali.yj202588.top/Article/details/gthdlqxpgt.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gthjxpivpq.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtnjbenrzi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtpvkewisd.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtpzyxacdz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtwmygnove.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtntggcymw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtoeyutocu.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxdozsgnq.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtrkbnkrfo.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtseneqifd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtoqdodd.html

[S44] C++：引用传参
来源：http://dali.bjfxy.top/Article/details/gtngxenwzc.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtmygjwzlq.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtaqeyvbcb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gtxixscxnz.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtdbslfpqa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtfjqecnup.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtoxhhxzok.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhoulong.xyz/Article/details/gtgcydzxhe.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtctrttvsw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gtkpoukcdp.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gttsndtezp.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtjbfpgkzu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtelxiscph.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gteznhkaqd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtprxuuokb.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtmcutmgej.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtxwesgcyo.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gtvtykoptd.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtthabktkl.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtsngvcqko.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtwmgolqcf.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gtegezdijm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gttcjilczm.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtosllyvyt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gtwbliypcd.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gtzribekpr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgecmocf.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtzvaqwujw.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gtpryhiacp.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtbawxxacj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtlurutzmq.html

[S59] C++：静态断言
来源：http://dali.sysykeji.top/Article/details/gtmbafgjuu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtiqveuutz.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtqxkudxla.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtjtrupvco.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttehrvgoz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtwwozyjxd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqnantpzb.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtyuosdbgq.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtlhaisjpb.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtxegtbpxb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtuiggnlkm.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtniejsepy.html

"值: $b"
来源：http://dali.redwolf501.top/Article/details/gticixgxhg.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtwbeuytov.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtujjlmges.html

[T05] Kotlin：when 表达式
来源：http://dali.xziqi.cn/Article/details/gtosegjzvq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gtmtyhevwb.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtbzgvpbve.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.smart0.xyz/Article/details/gtcrceeeyw.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtlyzpkexk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtsybhpgxi.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtkzvptuzh.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtqwxxbdiu.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gtmsfaends.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtifkflsvs.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtpilbtdou.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtolddcglh.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbqbnksx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gtsghdxfgj.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtgqklmoht.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtwlyuttaw.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtkrhphnmk.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtrefikumh.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtcdngojds.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtkxmvwzhq.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gteevwpnvs.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtqyhemyhv.html

[T16] Swift：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtyoqgetcx.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtcynuiash.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtugkircsb.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtcmsuixuu.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuhmqvyb.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gtmkvdhzfa.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtjjplflys.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtagavolwm.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gtgydaorqz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tanke756.top/Article/details/gtzdghjmky.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtybzqlgys.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtmcbexchz.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gtdbpannyg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.snrcjt.cn/Article/details/gtqnuqamtq.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtdftttzdj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtgdwkcvbr.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyhmrssp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gthaunzbhk.html

[T25] Swift：结构体
来源：http://dali.wangdashe.top/Article/details/gtweyaimjd.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gtspyjovgm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtnneuobto.html

class A: Base { override func f() {} }
来源：http://dali.hywenlv.cn/Article/details/gtcisoauep.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtvvxblwam.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtqunrqgyy.html

[T28] Swift：枚举
来源：http://dali.iojbl.cn/Article/details/gtmgdinubk.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtugxkbfpt.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtygahqmmc.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gteceeubvi.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtggevbffx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtckmtlsla.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtxrbtwxdy.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzvxumrt.html

[T32] Lua：局部变量
来源：http://dali.9152youxi.cn/Article/details/gtwolvcnrd.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtlipzwozc.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtgpmckzkv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgiyaqck.html

[T34] Lua：遍历表
来源：http://dali.gaohongyu789.top/Article/details/gtvmeiljph.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258888.top/Article/details/gtbatggdvh.html

[T35] Lua：字典表
来源：http://dali.yj202588.top/Article/details/gtixigfzhd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gtljlwwcer.html

[T36] Lua：函数
来源：http://dali.nanxinkj.top/Article/details/gtxanvrzes.html

function add(a, b) return a + b end
来源：http://dali.ivvv.top/Article/details/gtsxvqovyk.html

[T37] Lua：字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtrvwldvlf.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gtxrpqepje.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtereadssp.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtqhipvjix.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gthrrlvkst.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtrohrnjsg.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtsrpxjreo.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gtglwzddud.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gtnjchrqoq.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gtanoezyls.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gttvftpizz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtmwygvrdu.html

[T43] Perl：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtfxxdbzvw.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gtwtdoblrl.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtrgiirzgk.html

if ($a > 0) { print "正"; }
来源：http://dali.aizwys.cn/Article/details/gtfetdidic.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gtzjembrbn.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqkmnahfd.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gteluroprh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtdollhmoq.html

[T47] Perl：正则捕获
来源：http://dali.xinyue.icu/Article/details/gtucjwmafo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtfuavryxj.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gthilqpnly.html

$s =~ s/old/new/g;
来源：http://dali.yanxiufei.cn/Article/details/gtpdnwuoae.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtdaojzwji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtrmxlcztm.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtelkxhkeh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cheryme.top/Article/details/gttmhqnbfe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gtdfjpuvqb.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvggelwrt.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtwesxunkx.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gtzdrvvyxp.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtposryvup.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtjhtkrssv.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtvnnfdlfq.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtqxtiqvds.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtmrzleyam.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gttbznqlvm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtyfovppkg.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtbqpfpfmd.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtecekncuz.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtfdbfrdha.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtighefmux.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtgegpriqj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hysaishi.cn/Article/details/gtketrurof.html

[T59] Scala：循环
来源：http://dali.yj20258888.top/Article/details/gtzrnvtnyy.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtuakbttwx.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtbpaudlwt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daria6918.cn/Article/details/gtfmzqanzk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtefjpcwrd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtoodhekmp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtildiagdo.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtiuhylvpp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gtqxcwmmaz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gteavpplck.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gttqtqxndg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgavtycu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.9152youxi.cn/Article/details/gtsortdjet.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gtptqdtkke.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtrlefupzs.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gtatxezdyi.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtvhulildm.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtiotuhjrh.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gtjtdgjtqa.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtrjexipmz.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtyrwncpoo.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gtusfempcr.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtjtegcrhh.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gtulchmank.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtpzqwxkiy.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gthrnpvdmj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guannengcc.top/Article/details/gtsnipncvv.html

[U11] Py：生成器表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtggroigco.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gtpqqpedkd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xylfe.cn/Article/details/gtasyijcns.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtqxawgcnc.html

[U13] Py：固定长度队列
来源：http://dali.jyoumei.cn/Article/details/gtectfowst.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtcbwckdnj.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoskijij.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtpuwlwkxi.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gteeuqsgxx.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gtlzpkcdla.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtmmidjkwd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gtdramvphf.html

[U17] Py：初始化日志
来源：http://dali.yj20258.top/Article/details/gtdwkgchfs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tanke756.top/Article/details/gtoyzsqazt.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtwqdesizd.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtzqvwdmrc.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtrltqtrzs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtdzvwhldk.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtsygxwiwk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtjuqnwwcl.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtjudewjux.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtstiowtok.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gttmpwfxoa.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gtojupibdd.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gthdstgegg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtmpapecus.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gtzwruewmj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtlwinqwtr.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gtfaxfbeqz.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtsobrrycd.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gteuhmqpgz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcppfmmjw.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtxltpajki.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtslkfzywo.html

[U28] Py：类型别名
来源：http://dali.hongshengwenyu.top/Article/details/gtacanqpne.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gtrrwwxhev.html

[U29] Py：属性校验
来源：http://dali.jqgfzy.top/Article/details/gtsdbkzmsk.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gtrelxlfnu.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gthpuhywuz.html

@dataclass(slots=True)
来源：http://dali.xylfe.cn/Article/details/gtcpjrbqeb.html

[U31] Py：单测
来源：http://dali.jinqigufen.top/Article/details/gtxxmjppii.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtrcizjfgg.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfzjafan.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtwpyfsxep.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtkavayeut.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yvedp.cn/Article/details/gtcnfdelxf.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gtphdyxzwn.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtgwcrbmin.html

[U35] Py：发送邮件
来源：http://dali.sxryk.cn/Article/details/gtiginuyld.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gtalmjwqhi.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtvsgrwedw.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtsvioajms.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gttpwlhydi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.birdmap.top/Article/details/gttjrgumfo.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gtoehklgib.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtbfdasnjc.html

[U39] Py：判断是否在交互环境
来源：http://dali.tianlin.xyz/Article/details/gtvzixhqgi.html

sys.stdout.isatty()
来源：http://dali.hfpthk.cn/Article/details/gtcjwlqgso.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtpntuztgm.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtiigblkzu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzmxgobh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtwlsaptjx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrerlkvh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtsliiuunl.html

[U43] PHP：声明命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtbtfpcmjb.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gtbmubsoya.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtkxdsxeih.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gtmtweuojk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtjqckxhbb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gttdatkllm.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gtlhsgrtcd.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtnlciajpb.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gthkvzvyrh.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gtkuuaqwzk.html

[U48] PHP：纯枚举
来源：http://dali.c1oappe.top/Article/details/gtmnofhfqn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xylfe.cn/Article/details/gtzvzdbpee.html

[U49] PHP：只读属性
来源：http://dali.cashguo.top/Article/details/gtlddwdqpb.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gtmezpaozs.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtoelxvalb.html

public function __construct(private int $id) {}
来源：http://dali.chenzaomai.com/Article/details/gtcnbkrbrw.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gtikgrsgea.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtblwaxhbe.html

[U52] PHP：箭头函数
来源：http://dali.nanxinkj.top/Article/details/gtzoqkotxb.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccuothpm.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtrwqucrzv.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258.top/Article/details/gtkczbryox.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtqyterzyv.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gtxyclerlb.html

[U55] PHP：match 表达式
来源：http://dali.xuanzx.com/Article/details/gtydwpovyy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtwvknwtbe.html

[U56] PHP：命名参数
来源：http://dali.jianghu66.top/Article/details/gtslvwvfgm.html

f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytdpwivz.html

[U57] PHP：字符串插值
来源：http://dali.yj20258.top/Article/details/gtlicjjvng.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtatkbggqk.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gtilsswjbo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtmunkgnkk.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gtntlndtdw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtxxeawohy.html

[U60] PHP：JSON 编解码
来源：http://dali.gogol.net.cn/Article/details/gtvxikgqnf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tian-w.cn/Article/details/gtdavhfjmb.html


<!-- 参考信息 -->