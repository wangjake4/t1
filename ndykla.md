代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gt2kjzesjei.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2nlqxhixn.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2wgcxuhlr.html

[S12] C：写文件
来源：http://dali.yonumen.top/Article/details/gt2cczayjmh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2neawgmcv.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gt2hqqixnvh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2ahfqqvfd.html

[S14] C：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2wwrlvfhz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gt2mxfugsew.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gt2ghiagqwe.html

(double) a / b
来源：http://dali.hfpthk.cn/Article/details/gt2qtvvcxbe.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gt2okgidrcc.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wkapthqo.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2mcsslujf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2iqdvtudi.html

[S18] C：命令行参数
来源：http://dali.sysykeji.top/Article/details/gt2ebsyoptf.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gt2hwcfoxgc.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gt2ijevwutn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2zolncgsn.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gt2sqqwwffz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwboogyd.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gt2xesgpbht.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sufxvd.cn/Article/details/gt2aczqzasb.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2uydejzei.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gt2tdqgmvlz.html

[S23] C：随机数
来源：http://dali.svipenyu.cn/Article/details/gt2ebjuqjmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gt2jvbfguug.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2yhvonsvk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gt2elxvshjc.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gt2opkeudtk.html

memcpy(dst, src, n);
来源：http://dali.jqgfzy.top/Article/details/gt2mjoxuxoy.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gt2hhbwqazd.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gt2ezkxeoyt.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gt2qhrqmbdp.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gt2flaffflo.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gt2myrynbax.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2jjsxrpsh.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gt2jvfhxtdh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gt2qkinpghi.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gt2rwimtikb.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gt2bniprtue.html

#define X_H
来源：http://dali.jqgufenzy.top/Article/details/gt2shiudjpt.html

#endif
来源：http://dali.yueranfly.top/Article/details/gt2tozsnobc.html

[S31] C++：Hello World
来源：http://dali.tanke756.top/Article/details/gt2vhanscki.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gt2uytdmpim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2csqwppzm.html

[S32] C++：字符串
来源：http://dali.cheryme.top/Article/details/gt2dsuajhnt.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwiabfgz.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2jpbkqqfx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2bvgfmcdx.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2oaejwsgg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gt2smokhukf.html

[S35] C++：map
来源：http://dali.sufxvd.cn/Article/details/gt2zxvwtogr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2vneacktr.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqismotc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2xmpvtzsb.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2gqbadkwo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2rpvsrjzb.html

[S38] C++：排序
来源：http://dali.meibo888.top/Article/details/gt2cciowyav.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2lopylysw.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gt2rdbckrso.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gt2kybogceq.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2pouoftqh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gt2zapsyvvc.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gt2lsdtvbmm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gt2cdwhynlz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsaairk.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gt2wjcrgqea.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gt2sotqwwjq.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2ohtbnlac.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2apmzasve.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2irjlwvbw.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gt2ewguaywq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvlpcjbm.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmzfitri.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gt2yutbqzqi.html

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gt2itdgukxh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gt2qbwjmpdl.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2fmxhmyhx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gt2utyyoqqp.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gt2jlbjsvqn.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gt2ibkaxmta.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gt2urrywead.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gt2omsvrypp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gt2ejdnqxqq.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gt2yrdhruxg.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2pyrgxofu.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gt2edrtzvvt.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gt2uzfchrfq.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gt2sdyoaftk.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gt2ypcjxbvz.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2vdlkqmqh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzutlcoy.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gt2rlgjdggo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jianghu66.top/Article/details/gt2rkeyjmmi.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2adbjrvgf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gt2yypusgyf.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gt2hktslrlh.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gt2ulnyruca.html

[S58] C++：命名空间
来源：http://dali.zycfv.cn/Article/details/gt2drbmvxyt.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gt2zwtiyjjt.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gt2kpiwkgne.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gt2lmjshnfw.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqhstobq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohhngepd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cjneovzd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2zxispuvh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2yhxupwhm.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gt2lapkhnxf.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2unxbmfmx.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gt2jygoylcl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2leajjlnf.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2ajfvdpwi.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gt2cvwqxjut.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2uygxqytp.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gt2kxlcfyuu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2qicqglzm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2olrqngjw.html

[T06] Kotlin：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcjvebfo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2gsuiiewb.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gt2ffrpjbwy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2vlrxbhlz.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gt2ubsfcxko.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oytemcfy.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gt2zedzceuu.html

fun String.exclaim() = this + "!"
来源：http://dali.nwbrower.top/Article/details/gt2npaxdcup.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gt2tivtantw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gt2srzhwazb.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gt2atbzlyfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2nxypaqpi.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2kjpbutpm.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzxljeok.html

[T13] Kotlin：只读 Map
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssdvxuat.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ankcopce.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gt2yvwrdfsg.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gt2hwwjuyit.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gt2lciofkjd.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2nnjfstiw.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2ybccaxcj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uytmxheg.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gt2yrxrqhgf.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wsayuxyo.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2insoetcu.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gt2lfyqiyvo.html

[T19] Swift：可选绑定
来源：http://dali.quarkkingdee.top/Article/details/gt2ppfggddh.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2bufurwka.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gt2sxackrhq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gt2xxcgpvnx.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gt2vqtgwvgn.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gt2cacozlub.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gt2vpzeibrt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gogol.net.cn/Article/details/gt2jayldmkg.html

[T23] Swift：函数
来源：http://dali.mhx1999.top/Article/details/gt2oztmaekp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2dxliqjni.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gt2nftsfqek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2ezgnghog.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gt2folifbft.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2rpxstiyy.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gt2yfazzgea.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gt2fgqvgwuy.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gt2qmcmview.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2njsblywn.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gt2kifjpeov.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gt2updrsnbi.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gt2kchenrvw.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gt2yagsyndv.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gt2txjiifvj.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigufen.top/Article/details/gt2wikiljzp.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2felerdhv.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2qgvmovuh.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gt2dhhiclzx.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gt2jlnsutpg.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gt2ptigwzyr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gt2bifhepge.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2wmyibnkp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gt2vrztlqqo.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gt2qprtkwld.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gt2upimagti.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gt2bjvozmhm.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gt2zfeokksx.html

[T37] Lua：字符串拼接
来源：http://dali.ydzc1.top/Article/details/gt2wyuyjhzy.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gt2owijwxzf.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gt2pqzosvcu.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gt2xxipshbo.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2yrkcqhxm.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gt2skpctokd.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2fzkrnxqa.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gt2hdnsvbyu.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2xyvnvqaz.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gt2zluggtsl.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2rxtvmljd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gt2todffqmu.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2piikovsw.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gt2xsmtigvz.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gt2wdnmvvoo.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gt2cpywzdyo.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loictomz.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gt2zwresvtv.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gt2fpvsnngh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gqzpcfuo.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gt2lxegpvro.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gt2tidmxjcf.html

[T48] Perl：正则替换
来源：http://dali.cdnleiting.top/Article/details/gt2odzijshu.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2wrwbktcc.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2xocwsvru.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2wgprzpno.html

[T50] Perl：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2acimspnh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gt2efxbweff.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gt2kdofxluq.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2xjcgamuy.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gt2fmwyoozh.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fdfdwsxo.html

val a = 1;  var b = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2dnfquszl.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2ryjtqlwb.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2dffiuepb.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2lstvhfuk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eaimbjzw.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2nikzrawd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.snrcjt.cn/Article/details/gt2siilsmzx.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2ipyqwgwc.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gt2pcpdzjqv.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gt2jeafyihh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2wmunbyts.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdoivonw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gt2uowkcmzu.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gt2tdyovqvw.html

for (i <- 1 to 10) println(i)
来源：http://dali.tanke756.top/Article/details/gt2oaifmbqn.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2lrqxdqzv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gt2ywaqbqye.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2oxapjpvl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gt2onautdee.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hnzklkie.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gt2syxuaxfp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gt2jauinart.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gt2zhkcsock.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owksbppy.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfprkfcs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gt2fppptcxp.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gt2cbwxfakz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tanke756.top/Article/details/gt2ezgwpoas.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gt2ahqxfdky.html

list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gt2suxjhleb.html

[U06] Py：合并两个字典
来源：http://dali.chenlongwang.top/Article/details/gt2vnikzitf.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gt2rfndwvly.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gt2rnelsbrq.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gt2iiawjhxu.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gt2cnhgoxxw.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gt2yqjnintc.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gt2jcipotms.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gt2jqjcammk.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gt2hjqjybvp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gt2frrkczvj.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2djvymonq.html

(x * 2 for x in arr)
来源：http://dali.pycfn.com/Article/details/gt2nbuquzcs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gt2loeeuflu.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2tutdtraz.html

[U13] Py：固定长度队列
来源：http://dali.redwolf501.top/Article/details/gt2beagkvsx.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gt2mqlcglbe.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gt2jupgealk.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gt2moyjjbpa.html

[U15] Py：高精度计时
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzoefmcj.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gt2twihwueu.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2chbpaojv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gt2cqphunnw.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gt2jlotusms.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gt2dwfwpkqa.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gt2uvxpefms.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlltjkib.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsesnmjg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gt2uhocahzc.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gt2vjrmvyax.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2xgbqyctf.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htrpssoz.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gt2hxniqzdy.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szoibkuc.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gt2vitqzffv.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gt2ykligggn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shangyingyoupin.top/Article/details/gt2euhmszvw.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gt2qkumaide.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2aeebczjd.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gt2ytnznqpm.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gt2fehmwixe.html

[U26] Py：并发下载
来源：http://dali.gotoacloud.top/Article/details/gt2byzacztz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ehwqpu.com/Article/details/gt2llbnrszo.html

[U27] Py：异步 HTTP
来源：http://dali.wangdashe.top/Article/details/gt2ojdelwbs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gt2jrxmxnff.html

[U28] Py：类型别名
来源：http://dali.zhixingplan.top/Article/details/gt2kqvuqohf.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gt2sgccznxi.html

[U29] Py：属性校验
来源：http://dali.zdqjudy.top/Article/details/gt2mrjyvcwc.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gt2mqkbcdzn.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gt2tzxwetsq.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2glbxppqg.html

[U31] Py：单测
来源：http://dali.fengsongda.top/Article/details/gt2obalubdb.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gt2pujkyyvc.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gt2tdxkulfu.html

ruff format . && ruff check --fix .
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvsbfeic.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gt2dttxdzwy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gt2skkbrldd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbkhriy.html

chardet.detect(raw)
来源：http://dali.tian-w.cn/Article/details/gt2tflqiojs.html


<!-- 参考信息 -->