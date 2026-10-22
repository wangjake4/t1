代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2ymlycucy.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2kcjqbqkw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhengqikj.top/Article/details/gt2qsecqwrx.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gt2aecykzkd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2rbmcknte.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gt2ekxmmpop.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gt2uhalhenf.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gt2curjpmvk.html

x |= (1 << 3);
来源：http://dali.tian-w.cn/Article/details/gt2wiiidodo.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2gfftzgfv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gt2hdgcqivj.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gt2dmubhwjj.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2dyoioskv.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gt2ezrrgqqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gt2btjtishv.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2xexcqepu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gt2jtwtyeni.html

[S21] C：字符类别判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2xphuyozf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tianlin.xyz/Article/details/gt2jflbubpt.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gt2izvrjsvm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gt2hmbikeyc.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gt2jvqprmfu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2bkznurjt.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gt2xazhmqpk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2okvkxgjy.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2nmnogmir.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gt2sufdmuvh.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gt2xbmfxoql.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gt2yvheazlp.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gt2nfdeuont.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpqrxrzx.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gt2jmzrhcam.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gt2kcggqgsi.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2vqlmyuyc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2aiereclx.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gt2tksgiilf.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2upsadnll.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2takduyfy.html

#endif
来源：http://dali.bjfxy.top/Article/details/gt2vebprqmq.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2viduspov.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gt2vfnbsfyw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yyvowhse.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2klceyfth.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxgdszyq.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gt2ykrocmrq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gt2ubhyrpcg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kehsrowp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlzuxrkk.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gt2xtlkediv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2zktwkbtz.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2fljykqwo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2rpirlhwg.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2owudvdul.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gt2twmtqwsd.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2mrcuctkg.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2occugehg.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2yszhhilc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gt2odtjfivn.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gt2naylvywp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgfzy.top/Article/details/gt2tkpxrcdc.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2rfdqxaml.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gt2dexszkwt.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gt2blycvnxf.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gt2oxxwkvql.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gt2iieyuhwp.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gt2ycljahie.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gt2fdoybzsx.html

void inc(int &x) { ++x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ptvdrujl.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gt2sdyrdowq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gt2klsqtahr.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gt2dnjgfpag.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnwysxbg.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gt2ugurppnw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbtehlea.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gt2yvfeyhau.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gt2bvohtvxy.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2necbqill.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2viaclfoc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gt2brqwilxx.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2mswooxig.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2aoejyama.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gt2zwynhczf.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gt2ssjydkyg.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2cyeavhtw.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gt2mmckwcrb.html

[S53] C++：移动语义
来源：http://dali.9152youxi.cn/Article/details/gt2zirdvtup.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gt2rqsfcpca.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gt2hmmywhdd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gt2hbkyorii.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2ziqvmcge.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2jzqxizeg.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gt2senbgcpd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2daipbywo.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gt2loqoveix.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mtwgwirj.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2layshgqt.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gt2ihdfzkzw.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gt2qgprrbsg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gt2rzhcfkxm.html

[S60] C++：遍历并删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2stgmmuvq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrczjwkw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2icpidelf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2whkuzlgl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2rauclklk.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2orawchuc.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zukumkrx.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2rqhtteaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gt2rvjzytag.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gt2sglgycih.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gt2pdpszqvr.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gt2eezifxrv.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gt2ufiubyiu.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gt2hsszhall.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrkqzvmo.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gt2hluncszl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2lguhhvqb.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gt2gdkzqxfq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2lnjpwnro.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmwpgvfr.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gt2etbwdlgu.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqzzhfwr.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gt2jvthvlvf.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2mlhczhrs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2ylhaecmd.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gt2twshujdx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbisqwfp.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gt2cxhhfiga.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2woszamzj.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gt2xdonhmyn.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gt2wmgeosal.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gt2lybfhksh.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2zynkbxyx.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gt2hljtpjxj.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gt2gynwpogg.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2rynmehpw.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdbticdu.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gt2rejniuji.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gt2lnwerupw.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gt2vzahxyfm.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gt2waxweesu.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irmwjajz.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gt2emzwjbmq.html

[T20] Swift：数组操作
来源：http://dali.sweek.top/Article/details/gt2ezebhiwe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gt2etkzzskx.html

[T21] Swift：遍历
来源：http://dali.ivvv.top/Article/details/gt2zjxvwzii.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gt2bibhpnps.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gt2eenzuyrw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2ewirrnkr.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkgpscnx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2gyzrazvo.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gt2lxvmkiaq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2fmeunzdf.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gt2dcvozkql.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gt2kpvndxgp.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gt2ntopqukx.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2vmjpfmhc.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gt2imxybbaf.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwicjrko.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gt2aibscewl.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gt2cbhpiyxx.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gt2zpuxlsmq.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gt2xpslgnvf.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhmxotsd.html

protocol Shape { func area() -> Double }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekgplbjm.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2otngnwxf.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2npgkckzt.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2teckyand.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2nnapdivw.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrzagdkr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2lbwpuvjt.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gt2zlspogmk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gt2uabtuqgm.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gt2zwawkjby.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gt2smqlmzwr.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gt2nnzegnxp.html

function add(a, b) return a + b end
来源：http://dali.ehwqpu.com/Article/details/gt2mcrdmzbc.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqjtpask.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2njxmibyl.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzskvhvq.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gt2feuplrvk.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvxwcxsz.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gt2tpayzxfi.html

[T40] Lua：元表
来源：http://dali.fengsongda.top/Article/details/gt2cphuflga.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gt2cpcitnif.html

[T41] Perl：Hello World
来源：http://dali.meibo888.top/Article/details/gt2ihlmyunk.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gt2hcfnjafn.html

[T42] Perl：变量类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqwkkppr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gt2jozabglv.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2edkosbou.html

"值: $a"
来源：http://dali.yj20258888.top/Article/details/gt2osjehbik.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymchwazi.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gt2whhdthxp.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gt2dkwfuoez.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhysbzr.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gt2sbzxpzjb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2wocbxwff.html

[T47] Perl：正则捕获
来源：http://dali.vqdsnc.cn/Article/details/gt2kemwyzdq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gt2hustykti.html

[T48] Perl：正则替换
来源：http://dali.jqgufenzy.top/Article/details/gt2eoktrbrf.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gt2iygmmmoo.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2agupagpr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2eraqlvlr.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2nzgfxjqs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gt2vfnrpymh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gt2bwqpsbpx.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbffdmvo.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2ujfdyazw.html

[T52] Scala：变量
来源：http://dali.jqgufenzy.top/Article/details/gt2qqowhdca.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2mjpgnltr.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2lfnrejwa.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2tdivyyas.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttxoqodd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gt2vkkdizon.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gt2qktvkbxq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gt2aetgkygi.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gt2devxjtts.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2srcjifto.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2ezqqehje.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2pvroyglo.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gt2hmgrougx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gt2zlvjqkxj.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gt2fehojakt.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2lemxjilc.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gt2pqxoukmg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gt2mncrdqgu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2sjmvcrye.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2gnsjpacx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2znumtnmn.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gt2vrvqhsgc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vhjowslg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gt2trcsfwjb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryujlwzv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gt2xevpqzet.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.iojbl.cn/Article/details/gt2orjiwhvl.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gt2dqimdnct.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gt2fszvjohp.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gt2iqacggjo.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2btoekmvg.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhlnmfhp.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gt2yebbmhuk.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvobdgag.html

{v: k for k, v in d.items()}
来源：http://dali.xuanzx.com/Article/details/gt2bbdotkfo.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gt2wazmvyqe.html

[y for x in nested for y in x]
来源：http://dali.pycfn.com/Article/details/gt2ekrgifwy.html

[U09] Py：字典取最大值的键
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmvmsnkx.html

max(d, key=d.get)
来源：http://dali.sufxvd.cn/Article/details/gt2tvfduvur.html

[U10] Py：按值排序字典
来源：http://dali.yueranfly.top/Article/details/gt2fiezrlej.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfaozkhd.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2xiqczzox.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gt2cejzbgba.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gt2vefmsbzi.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gt2ilpxymow.html

[U13] Py：固定长度队列
来源：http://dali.daria6918.cn/Article/details/gt2jjamyplu.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gt2mfurvcck.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gt2setzhpja.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2nesvbhgr.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gt2pcjkrjad.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gt2htulyibp.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gt2xfusifpx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gt2wpujvzqw.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chkeomob.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gt2wjufvdbu.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gt2evixzkoj.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gt2vsltxsug.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gt2mpmtveqp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jianghu66.top/Article/details/gt2thzeusji.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gt2jpqkktln.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gt2umpkljzq.html

[U21] Py：自定义上下文管理器
来源：http://dali.kuanghao11.cn/Article/details/gt2shxlfxtv.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gt2bleebrui.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlmctkfz.html

list(zip(*m))
来源：http://dali.jianghu66.top/Article/details/gt2oljprfnj.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfttqrzx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.meibo888.top/Article/details/gt2ucajbscv.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gt2xqpigmkd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gt2hoscgelz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gt2kcdjwuyt.html

csv.DictReader(f)
来源：http://dali.yonumen.top/Article/details/gt2ctgeyryf.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gt2vdweergm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xziqi.cn/Article/details/gt2yowudzbn.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gt2sbgiucho.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gt2yrjiklxe.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gt2xgazffav.html

UserId = int
来源：http://dali.zycfv.cn/Article/details/gt2wxagzwwj.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gt2srfggkdl.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gt2jpymmnpe.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gt2mrteivps.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncrwggqg.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gt2lazldgmj.html

python -m pytest -q
来源：http://dali.ehwqpu.com/Article/details/gt2oiexgolr.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gt2wdppfmcj.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gt2ujdfcxjr.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gt2fuxcauwv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2rktwdikt.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gt2snvejbup.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gt2zyfowzjr.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gt2ipxwlaru.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gt2cjymbsmo.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2xpsxlxyo.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gt2dadjlcue.html


<!-- 参考信息 -->