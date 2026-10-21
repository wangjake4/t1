代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtcweuslts.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtsvzriyka.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtajidxqlw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtskzzvvvh.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gthxrelqux.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gttddxgigz.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtbpaxcixq.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtnugvbirk.html

[S43] C++：智能指针
来源：http://dali.jinqigfzy.top/Article/details/gtsxauzilh.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtlmlxboxa.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtwoyscdaf.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gthckjyyra.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtczjqmvea.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtodfgswze.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtkojnmhvh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtkjmdpvhq.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtvscsfcdw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gtdkfiwnpt.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtpvylvnlq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtgzubjqct.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtdkqoajwv.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtnigthxnv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gttrauwapf.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gthbntfhuv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtonygclji.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtwdhgopmx.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtpcpjugle.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gtsxrhjvuj.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtkspigxpu.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtvhfvmsoi.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gttrvzhjoi.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtmzbqaadu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtblxjnqzc.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtgnpgsxgq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtoxvmymnb.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtwuknjygs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtiminxkni.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtxpixdtzx.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtdhscjclm.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtjvicroga.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtbsgfqtlf.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gthwphcoqm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtwfdnphqc.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gtjpteepgo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtmapebrik.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbdgnzcqp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtmphqlzfv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtoubcjznz.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtstqprnco.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtnuegnpqe.html

[T02] Kotlin：变量
来源：http://dali.hnxiangtu.top/Article/details/gthstrhhhr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtrufoslni.html

[T03] Kotlin：字符串模板
来源：http://dali.hywenlv.cn/Article/details/gtgokhgkdb.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtjwyixthx.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtifbbyyni.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtnmawlefz.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtjcskbyhm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtqhyctuth.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtdtwryjij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtenwidiaj.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtqclqdzts.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yonumen.top/Article/details/gtfjvxlcyq.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gthadsvvzm.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtfggefphp.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtvanuweta.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtamcxwjty.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtjaqvojyy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtusekhsba.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gtychtwhdw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gttkkneipc.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gtkyamxfty.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtaypllvuv.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gttylpsbyo.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gttzuqrjkv.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzqktrsk.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtqmrieexc.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtfnsmpgvn.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtsiorzkpg.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtvzctesmd.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtywuwugap.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtqetuqfmh.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtujtpnvxt.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgwytydw.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtbprhcysm.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtzvjuggud.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtqfqapbra.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtxuyyotxr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtgecnbwyk.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtixvpdbwq.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtcqudlmkn.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkovtjakr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtpskyckdy.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtjaynqhsg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtepuwlwjy.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtmnbthwrt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtbvzobxcu.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvtlbudr.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtbmeofpqz.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtcehohuny.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtmytwobzh.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gthhlvowsi.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gtwxpunafw.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtiexfxtez.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtprtgwuvs.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtgytleolc.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtgtpqftog.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtwyiprryt.html

protocol Shape { func area() -> Double }
来源：http://dali.yongpay.top/Article/details/gtjnvrayuw.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtozswuauy.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxefpxan.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtpundxlab.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtpistptci.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtucwhvyuq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtwkmkhjjl.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gtokupdsve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtkocigucw.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtcphgdyav.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtccxzfxfi.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gtsligxeut.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtbpkjdnte.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtvfquotep.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtfdyyixac.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtajrtmwjr.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtqjevcgeq.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtreoqvdnc.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtfqxkzubf.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtxqxttddh.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtomnijfar.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtchfjlbpu.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtflothymp.html

[T42] Perl：变量类型
来源：http://dali.yuanzhike.top/Article/details/gtacdmbvcq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhixingplan.top/Article/details/gtjuxpsyny.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtopabmjuy.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtjphsnhjs.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gtfbolhmgh.html

if ($a > 0) { print "正"; }
来源：http://dali.iojbl.cn/Article/details/gttlonrtin.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtpaigejig.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtkpfxuudy.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtznbmmtko.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tian-w.cn/Article/details/gtoromvrzt.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtixslryut.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtpcfhrkly.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gtuohouxgs.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtzxzpyqlo.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarsvhwyk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtsrrxpbnq.html

[T50] Perl：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtalytcznh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtnmtggqqy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gttvwyxdls.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gturkvkhcy.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtgcynlxrk.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gtdnsqtkgx.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlycifahz.html

[T53] Scala：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtqkasmsdw.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtmkoeeovy.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtcemncggv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gttobqjflx.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtxkuqrqwz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xziqi.cn/Article/details/gtabobjdhs.html

[T56] Scala：样例类
来源：http://dali.wangdashe.top/Article/details/gtqafcvcnf.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtubwkfawp.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtztsnjnzo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtzjrczdge.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtvipqllsn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtvrdztkhi.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gttuhnxbeu.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtqtdxljag.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtwolfhoic.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtinotgrta.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthjgrljnh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtfykakozo.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtffvbpisb.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtsluvotsb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtzfgaeloc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gtglskpczu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtahsdwgbn.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gthklgwbyf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gtxlbrhfyc.html

[U04] Py：变量调试打印
来源：http://dali.hongshengwenyu.top/Article/details/gtneyvaknq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtcktctufx.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtwizfaqau.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtcnjfcarz.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtkrwoxisb.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtivhwsoeb.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtlmnnmgvf.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtcobulzbl.html

[U08] Py：展平二维列表
来源：http://dali.daria6918.cn/Article/details/gtsnkuwfvg.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gttjcjlfia.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gthtvzelys.html

max(d, key=d.get)
来源：http://dali.redwolf501.top/Article/details/gtyxwexxdy.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gtxuetynwg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtbgoxppef.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtbmczqyfw.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtirmeessh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtshsewkpj.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtaiibfugf.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gtvlvdqptk.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtdcrfpemk.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtarcmriay.html

defaultdict(list)
来源：http://dali.cqqwz.cn/Article/details/gtgcafnywv.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gtaaucbvvs.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtlgsgkfvu.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gttykmiidz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrznkrdzt.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gtzlazcakn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gtesilacuy.html

[U18] Py：预编译正则
来源：http://dali.tanke756.top/Article/details/gtehftzqeo.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtdllihoxb.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtbfycuhwa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gtpglhudsf.html

[U20] Py：缓存函数结果
来源：http://dali.hysaishi.cn/Article/details/gtciqpmsfh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtjqjogrby.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtkuilvnxf.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtstdfklef.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtzhtgshya.html

list(zip(*m))
来源：http://dali.hfpthk.cn/Article/details/gtfmeawqju.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtrphphqei.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpyvdsjt.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gthgugcaym.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gtbvgehunz.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtctkevzqp.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtgbbrndwk.html

[U26] Py：并发下载
来源：http://dali.gogol.net.cn/Article/details/gtjkbhwxzu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sufxvd.cn/Article/details/gtisqnpudt.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtyboyoltm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtnnnzpfii.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtkxeagies.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtcohajurf.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtibmteomn.html

@property 与 @x.setter 配合
来源：http://dali.vqdsnc.cn/Article/details/gtjvpbcqrs.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gtoocunxyk.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtiafmvbnp.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbbzmrlt.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gtcrshioyw.html

[U32] Py：代码格式化
来源：http://dali.jlsjyb.cn/Article/details/gtxkzaboak.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdzkxdns.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtugfhtcyq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gtbimrgghv.html

[U34] Py：判断编码
来源：http://dali.yongpay.top/Article/details/gthlfczgbc.html

chardet.detect(raw)
来源：http://dali.chenjidiqi.icu/Article/details/gthdrrdlyf.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gtmhtgjpvi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtlgtnimmq.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtamrsuqcl.html

schedule.every(10).minutes.do(job)
来源：http://dali.svipenyu.cn/Article/details/gtcbcwwhvm.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtbbstpkes.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nanxinkj.top/Article/details/gtnebjdozh.html

[U38] Py：获取脚本所在目录
来源：http://dali.jyoumei.cn/Article/details/gtmncohqzw.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gtbdzjukqi.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gtykqwgbou.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gtztensmvw.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gteguqzcga.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtzpfwhsug.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hywenlv.cn/Article/details/gtnqoajqzy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xziqi.cn/Article/details/gtcokwwera.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gtxkymhqbd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gtenkldips.html

[U43] PHP：声明命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtkpvutmhl.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gtmdcagzeu.html

[U44] PHP：开启严格类型
来源：http://dali.chenlongwang.top/Article/details/gtlzfvurvk.html

declare(strict_types=1);
来源：http://dali.fengsongda.top/Article/details/gtpvztrxmy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gthwxgrgaz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtpqqstkwa.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gtxfbyxmlc.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gtspcflvbs.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gtqqbvthlm.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gtqpiebuml.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gtotjuoikb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guowangkeji.top/Article/details/gtajagtdgo.html

[U49] PHP：只读属性
来源：http://dali.cashguo.top/Article/details/gtvxzlgfja.html

public readonly string $name
来源：http://dali.gogol.net.cn/Article/details/gtujhschpv.html

[U50] PHP：构造器属性提升
来源：http://dali.sysykeji.top/Article/details/gtrofnerak.html

public function __construct(private int $id) {}
来源：http://dali.yanxiufei.cn/Article/details/gtyqtodhrz.html

[U51] PHP：数组解构
来源：http://dali.jinqigfzy.top/Article/details/gttypuutmo.html

[$a, $b] = $arr;
来源：http://dali.9152youxi.cn/Article/details/gtiwfyhddz.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gthrtuejxi.html

$double = fn($x) => $x * 2;
来源：http://dali.dianchejie.cn/Article/details/gthksguzjq.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyldvvlj.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgfzy.top/Article/details/gtslzoqpjp.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtpzroxpjx.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gtdtsxlimn.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtfvpvgbaj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gtoarsiyxa.html

[U56] PHP：命名参数
来源：http://dali.gotoacloud.top/Article/details/gtgtyipssg.html

f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gthvdunjuv.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gtftbdfcyu.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gtgnhtvhua.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsofadjm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gtpxusimpr.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gtaaxyoozo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gthicvhylb.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gtluxgpwjk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangdashe.top/Article/details/gtorhkyfbz.html

[U61] PHP：正则
来源：http://dali.havefunace.top/Article/details/gtoatfyoug.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtmcntwvro.html

[U62] PHP：日期对象
来源：http://dali.jinqigufen.top/Article/details/gtnkcosjkr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jyoumei.cn/Article/details/gtglybjyqt.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gthzyfgrbn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtukcjuzso.html

[U64] PHP：目录遍历
来源：http://dali.nanxinkj.top/Article/details/gtooptxnwq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xinyue.icu/Article/details/gtznvpbxxd.html


<!-- 参考信息 -->