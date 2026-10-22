代发 wailian999

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2rutmvtni.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gt2nkscwyom.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhongyouzk.top/Article/details/gt2fzdtqnmj.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2gdttimdl.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gt2mgpulfoz.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gt2buiemwtq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2noatsfaw.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gt2icbczfsr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2sfuoysgp.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2mpdjizgr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuanzhike.top/Article/details/gt2dzbxbuqk.html

[S22] C：字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2jdgjurvi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gt2gwacehgr.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2atstglna.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gt2ryibouec.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gt2vbsbabzc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258.top/Article/details/gt2hikzpvvb.html

[S25] C：内存拷贝
来源：http://dali.zhixingplan.top/Article/details/gt2wtfrmznh.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gt2ygijysku.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gt2jyxwfdso.html

memset(a, 0, sizeof a);
来源：http://dali.guowangkeji.top/Article/details/gt2xvzkmrfy.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gt2sblooobo.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2hmeezfiq.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2halteapt.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyuykwqn.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gt2tmmktjjn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gt2bgjbbwtt.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gt2bxqmkgrm.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gt2wnyokprq.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2jtaieped.html

#endif
来源：http://dali.sweek.top/Article/details/gt2jargcint.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2istgvtyb.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2okezjpmm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gt2nrkcuhwv.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gt2aebcdhkp.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gt2lajsoxux.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2umhkzhhw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gt2mfjmlftx.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gt2vdwqlarx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gt2dxafiypw.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gt2jsbmfnii.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xclgtmat.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2raywboot.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2jvvzvkpx.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2vpwrkttz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gt2zcpoowht.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2dybehdgv.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2jrbwpual.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gt2ktpvcwxj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gt2jffqqofb.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gt2csptlqtk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.fengsongda.top/Article/details/gt2cbibmwnm.html

[S41] C++：类与构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2geppondr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2veizxxby.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gt2mafswfvv.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gt2qajaotjw.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gt2mhhqyimk.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2xgwljryo.html

[S44] C++：引用传参
来源：http://dali.pengpengdd.cyou/Article/details/gt2qymehpze.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nznvgsjv.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gt2ygevehmk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2gnnvyldz.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gt2yhyssvne.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gt2zkjnfwjr.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gt2yimhvwuh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prlbizyh.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2gpgfpfug.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.snrcjt.cn/Article/details/gt2vtfudlrv.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2unazujqm.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2ixrvmxhl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiktocdw.html

[S50] C++：格式化数字
来源：http://dali.sxryk.cn/Article/details/gt2hxpwarpv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2ucnekiwo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnbrefd.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gt2gghjxkht.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gt2gbxsyrln.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gt2ovazogxv.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gt2uzoisjor.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gt2bmlxswcs.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqjusmvw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2mhsofnml.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gt2xpbifgqf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2hmhmlgll.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gt2irqylnvd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zevubuky.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gt2trbudwwc.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2dblhhcer.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbpceyfd.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gt2pgjyaaia.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxfkagzi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ienoohrw.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2hbcqreos.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2xfoettis.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2golxqvby.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2zkesbdcf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2tkgmaflm.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gt2uujopecq.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sirztkdq.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gt2yivfmtty.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjshzpri.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2qvdkxfpp.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gt2nvrsjtlm.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2ytzjdibh.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gt2tziqckzu.html

[T05] Kotlin：when 表达式
来源：http://dali.hysaishi.cn/Article/details/gt2wjwovnbn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gt2pkmrtetq.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gt2dnuhwldu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2agxxwpgf.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gt2rhsjwtlz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gt2rahienhl.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2unyiewyz.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2djevjslo.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2yeuqbnqs.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2ipmwfcms.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2evbsfnaa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gt2xfhskiof.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2egdcvcdc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gt2ebplcxdg.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2vnufubbt.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2ebcbeyya.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gt2hcgztudv.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gt2dyrnwref.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2sjykwmok.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2udzqkcxa.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gt2jfvoxoqa.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2wfjlntkb.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2ttrvcngn.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2httcsvth.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2ayvcjjgc.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2axztnbyt.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eojvgawb.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gt2dgwqhfhk.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2yzdiizvi.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gt2xttztnyw.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2takcbzsv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gt2zfqrppdo.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gt2ssmznpst.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gt2phwaieuo.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2heksvxfw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gt2lzwvolxw.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwsjlnou.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2yrsckbeh.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2jxaldmbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2umpakmmz.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gt2frtztyyc.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2zqeefcbp.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2jzacizyh.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gt2hrxzvvah.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmynasaq.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gt2jjzslnlx.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2ctqqepke.html

enum Color { case red, green }
来源：http://dali.cqqwz.cn/Article/details/gt2mphvntna.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gt2nuczszuv.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2kowfzstm.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gt2sehhytue.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gt2amtzutog.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2ubrqhaqx.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2bjfbhkpw.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gt2ivmemtsv.html

local a = 1
来源：http://dali.ybcxt.top/Article/details/gt2shaiogwj.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2jgmhvqeo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gt2avcgiyas.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gt2yffuxtyk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gt2oopvmbtc.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gt2yjpvnfyb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2iqweklqf.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gt2fkmjibmi.html

function add(a, b) return a + b end
来源：http://dali.nanxuanxn.top/Article/details/gt2isnllnqr.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oihqsmex.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gt2nlxffdvp.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gt2itwecxoj.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gt2mdqonuzs.html

[T39] Lua：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2lgemulgn.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2fulgqzsc.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gt2ojzgdxly.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gt2ydboitoe.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2hhcjpkkx.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gt2cpeddtql.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gt2plkkwhzr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2texmjkmd.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2kbvtnivw.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gt2rycijkzf.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gt2nnigzrdn.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gt2icbogrqh.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gt2dhaleusq.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flnoejrh.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svaecnvi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ehwqpu.com/Article/details/gt2cutwapnq.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gt2vwvksrye.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gt2dchccagp.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gt2cbyxiich.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gt2lurcegvw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2myhwaxdo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2sffvojev.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2gkdoforj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gt2rhliqdoh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyihibyv.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2erbuamsz.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2pjnwgpfv.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gt2pwakeors.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2gpjbkcsc.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2dhosouqo.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2mxvuwocj.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2ufphihfh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2zkxlcqlw.html

[T55] Scala：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2xfxczxvr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gt2phgrzwei.html

[T56] Scala：样例类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udsnchwx.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gt2cureurxp.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gt2xstzovff.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jianghu66.top/Article/details/gt2meyzpmpp.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gt2svieyaox.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqnlfqzo.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwckcriu.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gt2dbnisdij.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2wqczetjm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhengqikj.top/Article/details/gt2lamtngce.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dagoybuk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gt2trxhvoff.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2rjqrzmrq.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gt2hrbbhqdk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gt2luhikhbp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gt2qyrnjmwx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gt2jkitgtko.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2bafakcdu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gt2kwqxsckd.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gt2omrnvxnt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2maxvmbux.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gt2fnzdhuov.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2fuozokev.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gt2qakabzln.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2nswugznr.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gt2tqymxiyu.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gt2ogdjpjth.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gt2dvovgfkc.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gt2shfaofqs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gt2lqgelopg.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gt2gohkbqoh.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gt2erwybysu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gt2iqsljlek.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gt2bgvdvmye.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifdslfwg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gt2qxqnubzg.html

Counter(arr).most_common(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2tspmaaiy.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gt2xrybkgjg.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gt2nfrcetvq.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2oejnmjcf.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gt2gkvhhdfb.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gt2dfnjlgde.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gt2ojxhyrbl.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gt2koovkrty.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gt2txwjsoag.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gt2vyftsrpi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhoulong.xyz/Article/details/gt2fxjdlkdq.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gt2csecgcjl.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2isffymgn.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gt2wqshjvuj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnxgglmm.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gt2ruegpnmz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gt2khzdwrje.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gt2jhflkfeq.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gt2nbxqmtqn.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gt2nlziqvbl.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gt2zahdvgtp.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gt2ktpfchgl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gt2cwprbaru.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gt2dszhcvoy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gt2tekwrvxl.html

[U25] Py：CSV 按字典读
来源：http://dali.shuidangran.top/Article/details/gt2kfevkwdv.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gt2hadbtckm.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gt2ttjblwld.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gt2eafjbatk.html

[U27] Py：异步 HTTP
来源：http://dali.zhixingplan.top/Article/details/gt2shoeyqdd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gt2ilwnhuww.html

[U28] Py：类型别名
来源：http://dali.dianchejie.cn/Article/details/gt2nnqkhrie.html

UserId = int
来源：http://dali.zhiwuduotai.top/Article/details/gt2kngbwwxf.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gt2aiaxlfet.html

@property 与 @x.setter 配合
来源：http://dali.smart0.xyz/Article/details/gt2voxzgvfa.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gt2ovqzasxb.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gt2oyhwfafh.html

[U31] Py：单测
来源：http://dali.havefunace.top/Article/details/gt2mkzaqhxo.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gt2oexikfwq.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhtnrgxg.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gt2tgiosyre.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbaikrvp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcshdatr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jimqkcio.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gt2ckftbvrp.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfehmglu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gt2zpixojwu.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2drmkyuuj.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gt2gzfeownf.html

[U37] Py：读写 Excel
来源：http://dali.ehwqpu.com/Article/details/gt2bgggwpmj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gt2abttrjuo.html

[U38] Py：获取脚本所在目录
来源：http://dali.cashguo.top/Article/details/gt2sytevkua.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gt2udbbzctj.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gt2irmachfs.html

sys.stdout.isatty()
来源：http://dali.jianghu66.top/Article/details/gt2msxgjioa.html

[U40] Py：打印到标准错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhysnzgp.html

print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2wlvagiah.html


<!-- 参考信息 -->