代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtjgnqdqan.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtfuilmexu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gtnuhhkyxn.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtqrmluvns.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtizjmoapl.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gtzckicksx.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtzvvsdjut.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtfzhdodjs.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gtqranaoxf.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtwdqlvtkw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtrhjouatm.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtoagcicsx.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtrcgetsts.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtdvbkdfnq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtzvhreoxu.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gtbtafumkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gteegbunsi.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtboenrsht.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.316326.xyz/Article/details/gthkgtrrfm.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtmbaqadum.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtuvcrxskp.html

[S23] C：随机数
来源：http://dali.yuanzhike.top/Article/details/gtbmborxhc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtbzwulyep.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtplaqhnzk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtzuvfhjyi.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtslqgqqvd.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtbatgkyek.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gtntrmhdqv.html

memset(a, 0, sizeof a);
来源：http://dali.sufxvd.cn/Article/details/gtsgelmjvq.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtuskrrcpj.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtnzdekygg.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtwzuifpun.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopjnfass.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtmtzjbdcy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtumbpitps.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gttwcffydd.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gtgxoxfsyf.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtcmlmhzrt.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gttwoxlsec.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gterbqfwzw.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gteofhmfem.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtzgyuntfc.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtkmlvnjqj.html

std::string s = "hi";  s += "!";
来源：http://dali.tianlin.xyz/Article/details/gtaedprgyx.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtgtixhona.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuffljkzt.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtpywovcbv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtzhompfyc.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtdlvspeod.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtrwkarcor.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtpvslbcgu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtftuzusra.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtcanctlpa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtdaeqsvuz.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gttfxftfsw.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtikqmsbzd.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtzojmcixz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtlrrixnjg.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtayqahsjl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsyxqzfb.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtsfntviuc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gtdzjgbzba.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtojyswrrf.html

class B : public Base { public: void f() override {} };
来源：http://dali.yangfankeji.com/Article/details/gtyykkrvlj.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtmysstfgt.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtavgeshgg.html

[S44] C++：引用传参
来源：http://dali.gzhubu.top/Article/details/gtbsojkipw.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtvlwpmgvj.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtntqwblnt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtqxtqbxkg.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtmedqnswj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gthypddfid.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtbygpwiua.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gthziddwux.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtwjytvpyt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gtemftvlww.html

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtzjjcyifx.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtwiojrowo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtrscgzwdy.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtvwbdgcye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtshhjltxm.html

[S51] C++：显式类型转换
来源：http://dali.nanxuanxn.top/Article/details/gtsryvuwrl.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtguaodmqd.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtoiayjpbe.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gtliyuvbgv.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtydjxahck.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdhkfyhgh.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtblyozele.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtufyhvpqv.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtoyccqquf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtwexgplws.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtipnvvysa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gttloukeia.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtskolhwdp.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gthfjpohwg.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gtclqmqjvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtwnmazsne.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtsbngiwuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtboldbrxr.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhjijafz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtptzfczwo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtradrwiza.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtfxdjdmhw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfaputfds.html

[T01] Kotlin：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtmwvgwdpu.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtzyhfksss.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtezdqngyn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtakascdnb.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gtqxzsdtha.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtjubfrvzx.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtgrinjpqv.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtdaysdfzq.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtsffzsqvf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtodwsruyx.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtzscidjru.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtnxxhtkrc.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtyucnqghf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtqletaiqg.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtvsvcgusm.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gteaebkrlz.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtigyrcpkg.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtudcsikyz.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtgsaxvtmd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtunpluely.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gterpjnbmx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gtszxmncok.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtbhmpihcm.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtemnsdegk.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gtvcjybekn.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtrnfmszyk.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtfzhkpquj.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtdtevhtfh.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtesrnyzkn.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gtjdaadlgn.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtbnpwgerj.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtiubocnfs.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtnrdtjitg.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtigsfihbi.html

[T18] Swift：字符串插值
来源：http://dali.havefunace.top/Article/details/gtpwevhwyy.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtinplvjwu.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtbdloqavp.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtnpfruxwp.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gtvkyseiir.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtcvirohep.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtiemvnsvn.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtdkpxsdep.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gtvlprdybr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtixmjvzrx.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtufvxckfs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtkszlfhrq.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtvphurwpo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yvedp.cn/Article/details/gtbimcxovp.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gtkuydwnce.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtyvdzxujc.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gtowfgjmsw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gtaojutvkw.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtzwhwsauc.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtsplwisiq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtvyerdkci.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtyyhnltnr.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtkmgdtsyh.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gtdbrywysq.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtliyelcqv.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtmhiphrpn.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtabygbmpk.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtcmyszuvk.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gtwtwbbtac.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtdknqylqa.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtvmrqzayw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gtjnxagqci.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytxqsxpt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtzfbjmpoa.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtkekbdmsb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhqdlnil.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthesjclpt.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtmliaegjt.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtxvzpvsst.html

"a" .. "b"
来源：http://dali.xylfe.cn/Article/details/gthqctunrn.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfibjhdxn.html

if x > 0 then print("正") end
来源：http://dali.jqgfzy.top/Article/details/gtiijusmiv.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtgmrzqqzm.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtyiqcedjn.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gtrpbsodil.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gtavrymmdh.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtexlwowoq.html

print "Hello\n";
来源：http://dali.jlsjyb.cn/Article/details/gtlzgctwpw.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtkudhjmfc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gttyvyumqb.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtkbwnuuqg.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gtlzrlwygk.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtjkqeojsd.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtzankgmhe.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtyhhxczas.html

for my $x (@arr) { print $x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtydiosfjo.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtgfvalhvr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gtoxapfieo.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gtgghjlkev.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtqfdjilxm.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gteovawbln.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gttotcvdyf.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gtgsljonha.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtlumnhcoh.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtunagpnpb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtmeilctub.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtrzvdgedx.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbeljcaa.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtglmpgvcq.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtuzefjskl.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gtjbelipyt.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtywekjxeq.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtnkmjgdmg.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtxewywphm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjwrmcjvd.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtnanzmnxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gtoflyvqqu.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtrvfdwskc.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gtnhzwnjwa.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gttcppnqpx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtdhratoqt.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtmzwkseyk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtlekkgvki.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gtugsgnnog.html

for (i <- 1 to 10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtaefepvxq.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtlafnbzay.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gtbwlkjsph.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlnnskjlv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtjfcbetsw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqpbdrzzw.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtzmcnjbwx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtogdzugen.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guannengcc.top/Article/details/gtxdgwemxg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gtzuijjcei.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlizetrci.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gtlrbeywcm.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtuvfzgafy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gttfdvrmym.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtyxkchjle.html

list(dict.fromkeys(arr))
来源：http://dali.havefunace.top/Article/details/gtomwlxpxr.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtsdpecbgv.html

{**a, **b}
来源：http://dali.xinyue.icu/Article/details/gtaidimewy.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjhheirj.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gtgfmlqtjp.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gtqojdsrvz.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtocenypra.html

[U09] Py：字典取最大值的键
来源：http://dali.wangdashe.top/Article/details/gtocdnjthn.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtynuwrxdc.html

[U10] Py：按值排序字典
来源：http://dali.hongshengwenyu.top/Article/details/gtddesdtpr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gttfqqgwtb.html

[U11] Py：生成器表达式
来源：http://dali.vqdsnc.cn/Article/details/gthausbygh.html

(x * 2 for x in arr)
来源：http://dali.ybcxt.top/Article/details/gtnhnbsovv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangshuangyany.cn/Article/details/gtfwhmrcrl.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gtewgresau.html

[U13] Py：固定长度队列
来源：http://dali.svipenyu.cn/Article/details/gtqyflxdmx.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gtrtobhtkr.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtoxctbbdu.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtmrwwquzb.html

[U15] Py：高精度计时
来源：http://dali.sxryk.cn/Article/details/gtcalrnvrq.html

t = time.perf_counter()
来源：http://dali.nanxinkj.top/Article/details/gteqdimdll.html

[U16] Py：命令行参数解析
来源：http://dali.chenzaomai.com/Article/details/gtfbqqypse.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.316326.xyz/Article/details/gtkrkellbv.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtomakuajz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtpeaebfza.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gtxgyzohul.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtkkcgiemq.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgizcsqn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtivyfbtne.html

[U20] Py：缓存函数结果
来源：http://dali.jinqigfzy.top/Article/details/gtixzhqwyc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gtaubsxlen.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gtesmzebaw.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gtewaluclh.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcklznka.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gtwtyapqza.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gtobbwfloq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gtxdvxsuqw.html

[U24] Py：路径操作
来源：http://dali.ydzc1.top/Article/details/gttdhegiuk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtiexfavmt.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gtjsmivupz.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtvcpywjio.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtojgildvr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gttfhrbfpb.html

[U27] Py：异步 HTTP
来源：http://dali.pengpengdd.cyou/Article/details/gthfesslps.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gtfxecvtqm.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gtbgzcguvg.html

UserId = int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmbjoyye.html

[U29] Py：属性校验
来源：http://dali.sweek.top/Article/details/gtdwfcjhtt.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gtdkomxiiu.html

[U30] Py：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtxohkkrdf.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtmwsdwysh.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtomqmohtp.html

python -m pytest -q
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblygalaj.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gtdstvqyvh.html

ruff format . && ruff check --fix .
来源：http://dali.sxryk.cn/Article/details/gtnipakzwi.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gttwmsigui.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtacnjchow.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gthrejukus.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gtjekicvqq.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqhwirco.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jyoumei.cn/Article/details/gthzizxgzw.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtqdtnnzdv.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtxenrebgu.html


<!-- 参考信息 -->