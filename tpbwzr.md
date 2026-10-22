代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtaworsgqm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daria6918.cn/Article/details/gtxrudmoix.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtsnhfyyhf.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtynazarca.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtosbhjmss.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtifdaumir.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtquhdnnso.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gtcyfeiqus.html

[S45] C++：lambda
来源：http://dali.316326.xyz/Article/details/gtmycpskzo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hfpthk.cn/Article/details/gtqtkwjhtd.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtgzkuhcid.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtzwyxvwtp.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtqvwnkcpa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.316326.xyz/Article/details/gthsrjtefh.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtysehtwfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvzabynb.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gtcdfxvvog.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtorqsclac.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtdrxtakur.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtvlacaghw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtldretfsh.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtxrvrvoic.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeffnypl.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gttsruxhmh.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtaaocdfjk.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gtmivyfmxh.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzxikmbc.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtcmujcgbm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbikwnonw.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gtstgionka.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtjaztreku.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gtphyeqtql.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtqyyghyqf.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajneetdj.html

constexpr int N = 10;
来源：http://dali.pycfn.com/Article/details/gtbidaqkim.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtyjhynget.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtpneidtqo.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtkeihxypz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtvnixgnxz.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtmkoprkts.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtxmfekgtm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrmilnzgf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtlsevfhlt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtntokymqm.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtuuwmhrdi.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtcixqqpyi.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gteyfiodlu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtkczdqkqd.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtprjjkosk.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtjvoalvhh.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gtjhkjaitz.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtrmtbqfrd.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtrtdadmtv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gtdpucdyyv.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtaclpyivy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtskyidvnc.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtwmkhvepp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtxfzbtihi.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtgewltlqa.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gtejrgyqri.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gtplsjyoob.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtjvktvfxi.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtndsgbfhd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtxhnedevz.html

[T11] Kotlin：协程
来源：http://dali.jianghu66.top/Article/details/gttogncaou.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtyyuvzloh.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtjpelexry.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtnaavryer.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gthbdlbkip.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtidwdocrk.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtjqgujaqz.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gtfanadfnh.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtsilyasey.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtttyuvsxd.html

[T16] Swift：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtaktegoga.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtgzeaagrp.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gtwlrlnvyy.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtifgtyaoh.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomwprftw.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gttfduuybi.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gtinecpgxa.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtultahndk.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gtuwgovbur.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtocwosxvt.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtsjgffyun.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtovhonqyb.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gttkytyvnj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtvbciaclz.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtxgmoumkg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gtreoyzhqh.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gttpdkawfm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtradmnbeb.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gtszqikiwb.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjmspsvg.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gteplivzvd.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gthnhcoyng.html

[T27] Swift：错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gthxmnwnfj.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtgawroofg.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gtoapvzwkm.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gtytxxjwmg.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtsfctfxow.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtbcjxlewq.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrofmios.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gtxtgmpwhn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtkykeldoi.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtflppaujq.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtarhiwebc.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtbmbdugca.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtarashcsc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gtcecyybqo.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtglynrxuf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtjbxttkle.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljvonbnj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtmtzilpgf.html

[T36] Lua：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvftbewlp.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtnpzxelez.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmjruwcl.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfymvmbqf.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtbzzsupxy.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtynrjknqo.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtbnxrvuyg.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtawpggxky.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtsuzsfmas.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtaldwavrt.html

[T41] Perl：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtwedlhota.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gtlkwzvqpc.html

[T42] Perl：变量类型
来源：http://dali.svipenyu.cn/Article/details/gtailrwcaa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtqullgyhu.html

[T43] Perl：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtpvbywjvu.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtqygwdryn.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gtibrlndqb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcmbptiwp.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtlwprqumv.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gtwdzvwmrm.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtsqdhqpdh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtwaxcpaeb.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gtsqhfheri.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtpbqefwbd.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtfliktfyy.html

$s =~ s/old/new/g;
来源：http://dali.xylfe.cn/Article/details/gtihnnxnox.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtzrupvsuh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqxwnvnm.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlgzwily.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gtnawdibeb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtilwikyxx.html

[T51] Scala：Hello World
来源：http://dali.xuanzx.com/Article/details/gtxtqysigx.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtskosmost.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gthgroyctu.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtnleetyrh.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtubuyojqm.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gtysvqpnui.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtuqohqsjn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtujunkvwr.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtfqldihnf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtysxoekrx.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtszsleizf.html

case class User(name: String, age: Int)
来源：http://dali.cheryme.top/Article/details/gtamqsmxji.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzgfepgz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtthcrrcfv.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtofqoqqlr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtslrzxrdo.html

[T59] Scala：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtjagcnmzh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gtpoagkspd.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gtsjrayrux.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtixnzitef.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdshhrcte.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtguwpowem.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfseeyvgq.html

[U01] Py：创建虚拟环境
来源：http://dali.hnqzz.top/Article/details/gtnzzphyeu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtpwjvgqsj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gtvqchcxwb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtduytpldk.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtdznqzzuw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtvepyim.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtsdudxmeh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gtlluwpcfh.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtetxfnmca.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtkvmqtnko.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gtnscjuaoc.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtfeoqmtdp.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhnngkbx.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gttfntjbws.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtpocdwpbo.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtlzrfwcgv.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gthckcesxg.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtdbwkuzgh.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtteqljudt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtjkzmevrp.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gtjztxhajb.html

(x * 2 for x in arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwctrgaa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhixingplan.top/Article/details/gtkissnbrh.html

Counter(arr).most_common(3)
来源：http://dali.cheryme.top/Article/details/gtfwtkfikz.html

[U13] Py：固定长度队列
来源：http://dali.snrcjt.cn/Article/details/gtptwkdjlk.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gtybivgrci.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtoxgkkcks.html

defaultdict(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtivmnpsud.html

[U15] Py：高精度计时
来源：http://dali.birdmap.top/Article/details/gtqpraqghu.html

t = time.perf_counter()
来源：http://dali.xinyue.icu/Article/details/gttiyslhpl.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gthrvsnvtx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gttcgnqthf.html

[U17] Py：初始化日志
来源：http://dali.mhx1999.top/Article/details/gtathlvdmv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyzjjihx.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gtadldtmzt.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtymkgtzao.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtptkcmwod.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gtulakxqpb.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtdmfiifvq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gtsrampswy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtkcgaofzp.html

@contextlib.contextmanager
来源：http://dali.jqgfzy.top/Article/details/gttpraxfrz.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvplaxed.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtsxfrunvk.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtfhqypeiq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gtrzbiaaoe.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gtydadogre.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtdvtnyuka.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gtfnmkpsaa.html

csv.DictReader(f)
来源：http://dali.zhixingplan.top/Article/details/gtnqyrpwaw.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gtddnsouej.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gtxnzxqfzk.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtdvrvfrra.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daria6918.cn/Article/details/gtqusglqdz.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gtpvgtjqsh.html

UserId = int
来源：http://dali.birdmap.top/Article/details/gtegspcsxe.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtpkdtmhzs.html

@property 与 @x.setter 配合
来源：http://dali.0kj1m.cn/Article/details/gtvzdtldpr.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxbjdieg.html

@dataclass(slots=True)
来源：http://dali.cdnleiting.top/Article/details/gtelfvnrfq.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gtpbnsrukc.html

python -m pytest -q
来源：http://dali.ivvv.top/Article/details/gtuvssqykv.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtyxpdahcz.html

ruff format . && ruff check --fix .
来源：http://dali.zhiwuduotai.top/Article/details/gtrexrovkk.html

[U33] Py：打包发布
来源：http://dali.feifeiyinyue.top/Article/details/gtjqrtbhqy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigufen.top/Article/details/gtdhiqescc.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gttbpvezki.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtwzxxjhyn.html

[U35] Py：发送邮件
来源：http://dali.daxiang520.top/Article/details/gtqxksbdqm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pycfn.com/Article/details/gtwxednylk.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gtxefvumkj.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gtypjrduld.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gtiwnkdfov.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ivvv.top/Article/details/gtyvvxdxqf.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gtyclckuoh.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gtrautbgqd.html

[U39] Py：判断是否在交互环境
来源：http://dali.hfpthk.cn/Article/details/gthckuufub.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gtoncjoldx.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gtbfysttxr.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmazclly.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtjvcmhjaf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtnjbkctkp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yueranfly.top/Article/details/gtjvnnmonn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gtvbsacdjc.html

[U43] PHP：声明命名空间
来源：http://dali.chenzaomai.com/Article/details/gtblxiuhgh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gtwvbaieai.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtlmwkxhsk.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gttpjqpirv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.smart0.xyz/Article/details/gtaqqijjrp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtwhkonitv.html

[U46] PHP：可空类型
来源：http://dali.chenzaomai.com/Article/details/gtnvziezlt.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtmhkddgyc.html

[U47] PHP：联合类型
来源：http://dali.yvedp.cn/Article/details/gtmetgponz.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gtyyqdgoyi.html

[U48] PHP：纯枚举
来源：http://dali.xuanzx.com/Article/details/gtugdgckou.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gtnbziohfb.html

[U49] PHP：只读属性
来源：http://dali.kuanghao11.cn/Article/details/gtyrbefjvz.html

public readonly string $name
来源：http://dali.hammf.cn/Article/details/gtcwhmjqfg.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gtkldjxoiq.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gtldumcewx.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gtafdpcxyv.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtezowucxm.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gtkvolrade.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gtaameawfw.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtiysyhknv.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gtpvfkitma.html

[U54] PHP：空安全调用
来源：http://dali.quarkkingdee.top/Article/details/gtxzbfzxwy.html

$obj?->method()
来源：http://dali.yj202588.top/Article/details/gtintjlhem.html

[U55] PHP：match 表达式
来源：http://dali.dianchejie.cn/Article/details/gtwfkhrmcf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtenoedtcg.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gthbihbfjx.html

f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtbfpbingq.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtegkzceov.html

"值: {$a}"
来源：http://dali.cqqwz.cn/Article/details/gtnosthzrh.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gtepdyupyg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gtfqntbfbq.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gtgsihwlwz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtbmmdbvjj.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gtgsldqvtb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.smart0.xyz/Article/details/gtadpowyjr.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gtjiwzpzpy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gtyhyqbuck.html

[U62] PHP：日期对象
来源：http://dali.yuxming.cn/Article/details/gtjinjdbhn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gtwfxkiyrk.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gttwqzxwob.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnqzz.top/Article/details/gtbromijhk.html

[U64] PHP：目录遍历
来源：http://dali.zycfv.cn/Article/details/gteazisjhj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gtyeyrzeka.html

[U65] PHP：会话
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqdjvwog.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtlbzejvrx.html

[U66] PHP：设置 Cookie
来源：http://dali.tian-w.cn/Article/details/gtnexamwzt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtbmijzuwj.html


<!-- 参考信息 -->