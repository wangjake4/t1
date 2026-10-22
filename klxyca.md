代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gt2xheggzab.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gt2ehwgjkqs.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gt2qcvhmwdg.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2gokwbtgy.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gt2vbtavzav.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2rikwctlr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gt2arhxnwak.html

[S18] C：命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2ydqtjhgm.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gt2wxiqaztz.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gt2qphamccj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2imvwrkrp.html

[S20] C：二分查找
来源：http://dali.jqgfzy.top/Article/details/gt2wflljdyi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2txjyakxb.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prdssfdy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bexihdbj.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvefncah.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2rzhhgdmm.html

[S23] C：随机数
来源：http://dali.ppjwa.cn/Article/details/gt2gzneezqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrwoscx.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gt2pksyljxc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gt2leecflgp.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2rogzwsfj.html

memcpy(dst, src, n);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfcclgdr.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gt2adakkacu.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gt2gwidfdei.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2eiqitjup.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2gqhdtnxo.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gt2hmkqybwz.html

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gt2tfrdwvjw.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gt2vkdsweqj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gt2exohskyv.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2wlhiwpnv.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gt2mgvqsfwy.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gt2riricaqe.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2tfofqomi.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2dfzsgnso.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkonktbp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ccaaoywx.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2zhnjcfah.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gt2pfsxbfhc.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2yvosmxri.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nhkhylyk.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gt2vnanfbpy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gt2fgursdxl.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gt2ojjeuitb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2xtpfbylv.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gt2byplrlck.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2alsquuhj.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gt2xroceyuc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2zymqgcdr.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2owklkybf.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2yezewbeo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gt2udgabwhn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hfpthk.cn/Article/details/gt2sebduxnh.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gt2ydbkrpil.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2hqgrlvaj.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2fgvfxaqp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2bzllnmfg.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gt2nfaypjse.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gt2ggfbonre.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gt2gkoxfxwk.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2czzhsevz.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gt2yhqqqptq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krweofnv.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gt2xakkonck.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcoqitne.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gt2mugjoesa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbohliza.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2cmfgjvmy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gt2zmpggpvb.html

[S48] C++：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xymlrdia.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2ybedakeq.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2xdgvwzsz.html

[S49] C++：写文件
来源：http://dali.guannengcc.top/Article/details/gt2orflzsdj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gt2zxmikwto.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gt2affrogti.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2wzmqlsjt.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2xsahbolc.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2ndyswxah.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gt2hgpnnyww.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2iyorfrqc.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwhosaxf.html

std::vector<int> w = std::move(v);
来源：http://dali.jianghu66.top/Article/details/gt2ayclonxi.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gt2krebpzip.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gt2biuxivzo.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gt2rrkliaqp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenlongwang.top/Article/details/gt2lwzyqryz.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2fgfauykr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gt2bybosntx.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2ngpjlvui.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymujmkik.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2teyabdpb.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gt2owdyeysm.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gt2wkbmtarf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yueranfly.top/Article/details/gt2gjmgpqnb.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2syzdkzme.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2anqjauhp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2kbusazyg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gt2hljhwpje.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ljlhjrup.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gt2rjoxzlgx.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2mmpbxvtp.html

[T02] Kotlin：变量
来源：http://dali.shzxlz.cn/Article/details/gt2lvyukiyz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.haohaochexian.top/Article/details/gt2suriiips.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2syfhsumv.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gt2lbndikre.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gt2nbracckr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tewmeqvz.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbgpbgan.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gt2dgpiiewq.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2hpjkaksf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.andypj.xyz/Article/details/gt2qqhiwzgn.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gt2ydutqvsi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2nedxcnuy.html

[T08] Kotlin：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2klfbpfec.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxicicde.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gt2dqoavipz.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gt2ahdcqycr.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gt2mvqgyewg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2drrycybe.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gt2nufwyyco.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gt2huixdkpz.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gt2lbpltuwj.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2awrkblvm.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2mmordner.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gt2zvepildp.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gt2rzknldrj.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2pwoeytpt.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptuoxtaq.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2whoeimpq.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2lnqeiaml.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cirtgnjl.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gt2lwysfcbl.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gt2ashfmonf.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2zcamhkdu.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gt2xvqtbary.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2iqwxbchu.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gt2fgbxaosn.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2zznbxtcp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gt2mlcrjzgx.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2pebrymlw.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwfmavdm.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gt2dguxvehw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2ryjxhvan.html

[T23] Swift：函数
来源：http://dali.ybcxt.top/Article/details/gt2zmxmyhkl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2kipjxpzc.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gt2yjepwlmr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2xqubouip.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gt2lpokouoi.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gt2xnxhjyso.html

[T26] Swift：类与重写
来源：http://dali.yj20258.top/Article/details/gt2tdcidfsl.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urnollxa.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gt2jdishaev.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gt2sszlcqag.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlexoyyp.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2rxyeejhz.html

[T29] Swift：guard 提前返回
来源：http://dali.shuidangran.top/Article/details/gt2urbghgci.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gt2trxxqrgp.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gt2cioidgiz.html

protocol Shape { func area() -> Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2tkoqrudy.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2pewzzrpf.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2txpnscqf.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gt2fnkqdrqk.html

local a = 1
来源：http://dali.gotoacloud.top/Article/details/gt2mbyzkzjl.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gt2guzaoovm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gt2mptogecs.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gt2dvdosrmw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gt2mxmskvmc.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gt2yylprsir.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2ndpgexvl.html

[T36] Lua：函数
来源：http://dali.hammf.cn/Article/details/gt2udpeprvh.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gt2klhcmvji.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gt2tpgejiqe.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2zobqylxs.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gt2hfsmrojs.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovqnvpgs.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhqccsiy.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gt2xvzayvua.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gt2zealklqx.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gt2rtqvybkk.html

[T41] Perl：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2cnjiazjq.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xbjibggt.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2yfqxhwrd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gzhubu.top/Article/details/gt2vzdhptyo.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2qgjdtrui.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gt2qzdfqhuc.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gt2etrpmuwy.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gt2nhqhkbvz.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gt2xfvctnxc.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2tomagfyl.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gt2rxtzmloj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gt2sdorueum.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gt2landbaki.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gt2vaduntos.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2cbrpxurr.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2suhttstz.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luwxnulx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2jowwtyxb.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2ipfbbjwv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gt2tlyyroci.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2cmoxgwbo.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2qjadeyur.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2ncblrvms.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gt2rgsjcmpk.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2wqwtczge.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2jslvitrs.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gt2nbjmlxgb.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2thhinheg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtudkrrh.html

[T55] Scala：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfijgaze.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2omnyxzjd.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2mggbnoyw.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2xtncenjr.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2sibehsza.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gt2nsuybtcu.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2imckopjv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gt2lzawzgji.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gt2zyipnewm.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gt2ppqlaqmc.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gt2tymuvzld.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdtpyihh.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jbgzzyez.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gt2xluzxvrq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2urhqumdy.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gt2ptckwcas.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gt2kkwlsdwx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gt2ffggczwf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gt2hucbpupx.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2tstjsvxi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gt2bvrmtawf.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gt2zlehplix.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2yeturlox.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2njzexmhl.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2sqohtrcn.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gt2ydzdnjig.html

{**a, **b}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpzgalky.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmktghko.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gt2jxzviawa.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gt2hxfzcmmh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqhason.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dljeehkb.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gt2sdgsqrsn.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gt2raiptnij.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gt2herliroc.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gt2sslnexcx.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gt2pctlsnhv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dashuyun.cn/Article/details/gt2dlbkstrt.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gt2sgultuoj.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gt2hopovviz.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gt2lpqvkcgn.html

[U14] Py：分组收集到列表
来源：http://dali.xylfe.cn/Article/details/gt2uekcpoui.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gt2rlqtpkdc.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gt2dvqedqbr.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gt2vmsviojj.html

[U16] Py：命令行参数解析
来源：http://dali.chenlongwang.top/Article/details/gt2caumyvrx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwxhspsl.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gt2efdyzufl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gt2aiaektvr.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2umnqcrbx.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2mdqrjunc.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gt2ngbjqcbm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gt2vwrqupvv.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gt2uyzbwhyk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.snrcjt.cn/Article/details/gt2ijsnqnza.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gt2bonsovgc.html

@contextlib.contextmanager
来源：http://dali.zhixingplan.top/Article/details/gt2hglmenle.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gt2jbyhuppn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhgqtsd.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gt2nyorijrh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytsogjvu.html

[U24] Py：路径操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nipvzapg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gt2nsnjhgor.html

[U25] Py：CSV 按字典读
来源：http://dali.jyoumei.cn/Article/details/gt2cgeqpvtr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuejhdei.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gt2qowazqjv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gt2rrecynsr.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gt2jujoaoyu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gt2tslvcitp.html

[U28] Py：类型别名
来源：http://dali.haohaochexian.top/Article/details/gt2worulckm.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqznwknp.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gt2lksapluz.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gt2gghpnizs.html

[U30] Py：数据类
来源：http://dali.jlsjyb.cn/Article/details/gt2bdkvlzbw.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gt2djzbzpcx.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gt2fqzkwsnk.html

python -m pytest -q
来源：http://dali.svipenyu.cn/Article/details/gt2pmgzevqi.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gt2vxulhyyq.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2mrqpvgsi.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gt2kpgajpyi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aibaodan.cn/Article/details/gt2xtjqvtgp.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gt2jfmescwe.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gt2mhmnplwq.html

[U35] Py：发送邮件
来源：http://dali.jqgfzy.top/Article/details/gt2odolguka.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gt2ognjkpva.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gt2wzhkfpaw.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gt2qvkhckoq.html

[U37] Py：读写 Excel
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcqbrojg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gt2lgykxcrh.html

[U38] Py：获取脚本所在目录
来源：http://dali.pycfn.com/Article/details/gt2mchusuue.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gt2bfirduhn.html


<!-- 参考信息 -->