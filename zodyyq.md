代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gt2dtvpbekw.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gt2hgvpmoqy.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gt2jtaranjk.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2cfjhlmsa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gt2knhabrwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gt2hukxatbp.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2ebxxcmbo.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gt2eubjmbdp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gt2xpqftbjl.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdnvlypr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gt2lodvlkbf.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gt2zkypvtfk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2itbcmcqs.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gt2kcgppetu.html

(double) a / b
来源：http://dali.hnxiangtu.top/Article/details/gt2gkvynpsp.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gt2upkauafr.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2yycytqqw.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2qoqpyngu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsljerug.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2qczolrrr.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gt2fpwoyulj.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gt2ywqedesa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2imaxeqkt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tltbgxtk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2dyunlygh.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekpjcjvc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftbqvbiz.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2sswtkhof.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2vhaogqdl.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2tinxevzm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gt2uwgdimjq.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2vjruqeii.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gt2pkevbwgn.html

[S25] C：内存拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2rnxblmba.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gt2hkyalcsu.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gt2auwjckws.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddcueits.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gt2dgzqfmon.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2cojdfwhz.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2cziqiwmi.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gt2biobvtsc.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xqpyarow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gt2lbxavtcc.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2cqasubye.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gt2nholaqee.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gt2ppzghcpp.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2swqloclh.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2dotnihis.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gt2gzitfgra.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ezjbmoaf.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gt2vckpazor.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gt2nwkyrejk.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gt2uradnwin.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gt2mcupvdvs.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gt2reljdbpx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gzhubu.top/Article/details/gt2wofbzbjk.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gt2uwzjmbgq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2ucxnkvmq.html

[S36] C++：unordered_map
来源：http://dali.nanxuanxn.top/Article/details/gt2dlqiseyx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2ncldrrzr.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gt2ciulhkyt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2bqcxhjes.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gt2jscdfbsy.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gt2xkfaryss.html

[S39] C++：自定义比较器排序
来源：http://dali.ppjwa.cn/Article/details/gt2qirrgvtq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2hiibbyzl.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2okfvnnio.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gt2qsjkjkhk.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbasvnxf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gt2zmsdgxbx.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gt2xbxuhujr.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2kyvhwabk.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uispzqoj.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2zxtcgjtt.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyawaofs.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gt2fyrbtzmr.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gt2skmlwywe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gt2ejywzoig.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gt2ktnsdccd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gt2aaxslwpo.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkngisdu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gt2bxhtiyhf.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gt2bvazvjmq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2vebczqxf.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2lshkzysc.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2sqqiaomu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gt2nlfrwjun.html

[S50] C++：格式化数字
来源：http://dali.wangdashe.top/Article/details/gt2icsiwjzr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gt2cyxqzoii.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2vtbzhquh.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gt2bxyskebu.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gt2faqdaqof.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2whhokeiz.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gt2skxuacow.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2anoljgtw.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2vxsnxxqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2eqyaxghp.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2ldnyxqrn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gabtkttd.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gt2ldytvaff.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2ztfwggmv.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gt2efabkrgj.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2drklauvc.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2thvzsfex.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gt2azmunaok.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gt2fkulrjly.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gt2tzycrvav.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyuhwjye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2kokfbuvo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjjdrhit.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gt2xhkmkgdr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2myrbaysw.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2jnuhfzjj.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2denwsdhu.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gt2geiwavho.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gt2stxkzjcp.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gt2qxsvlygk.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gt2ktnlaomu.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crgtezny.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2sczqvuln.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gt2pchzrlns.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2ebwypdbi.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gt2gnjbixlz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2jwmyijjz.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2ujvbuozt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhrojwth.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gt2hbvytepi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhixingplan.top/Article/details/gt2hwkgujqj.html

[T09] Kotlin：扩展函数
来源：http://dali.guowangkeji.top/Article/details/gt2iiyepufy.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gt2fbkzagdx.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gt2xnmykqtq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gt2apyeuvba.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gt2mzgsmmgf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhksspbt.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gt2ifpjvguw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndjxfogx.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gt2jnggvlfm.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgmhcwbd.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2fnimndrm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkvoifs.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gt2zkzxeprq.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gt2mwliljbf.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2oijfylwf.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2lsfnynho.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gt2hraxfjlz.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2uzdmwiad.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2jnqolapq.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gt2wepggfbh.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2pandujkj.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gt2pfbpbhhh.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gt2fvyxhufg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gt2wlqjelrk.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gt2mrcejvol.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zndlalur.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gt2kyskdtfj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gt2rimghlfw.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2fuglyztr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2rylypdja.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gt2sptybyfo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtrqyzig.html

[T25] Swift：结构体
来源：http://dali.dianchejie.cn/Article/details/gt2eguwsuzl.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2ysbhaeza.html

[T26] Swift：类与重写
来源：http://dali.shuidangran.top/Article/details/gt2uremcrbw.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gt2zqlghxyz.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2jvysbnqb.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gt2zpcmzljf.html

[T28] Swift：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2oegyueio.html

enum Color { case red, green }
来源：http://dali.cashguo.top/Article/details/gt2blwuuadb.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gt2yoqllenk.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gt2vztmbfme.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gt2ftbrnizp.html

protocol Shape { func area() -> Double }
来源：http://dali.sweek.top/Article/details/gt2cltpawhx.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2nsdbivbn.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2qepjwulq.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gt2agqeyjij.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gt2przgaxlx.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gt2wgmvsnpw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gt2nxgsgazz.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gt2islgregl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gt2yvrillia.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gt2rcpgaahn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2srpynrcq.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2nyfxwpbe.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gt2cbcbzlsp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzqlqcj.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gt2lsgsggsa.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gt2genlvqmk.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gt2hvpvuupd.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2syzedcop.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gt2rmfaivmu.html

[T40] Lua：元表
来源：http://dali.yvedp.cn/Article/details/gt2djuqqffz.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gt2spdosmtq.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2fnysxgtm.html

print "Hello\n";
来源：http://dali.guannengcc.top/Article/details/gt2cbfmpcvz.html

[T42] Perl：变量类型
来源：http://dali.yuanzhike.top/Article/details/gt2kggwfiln.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uavxohls.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2hpbzpwzw.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gt2gaybtamc.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gt2uinrbekm.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gt2mdwnefvm.html

[T45] Perl：数组遍历
来源：http://dali.cheryme.top/Article/details/gt2cxwnjusu.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rxihpyid.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gt2enylnokl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ajhhlafj.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gt2blcltuqq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gt2yajaqffq.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2chixgdak.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2aewfrywv.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gt2ousxguee.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2rhyszesv.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2yqdbmtpr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmhrxams.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gt2kexeocae.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gt2cmbdfgxe.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lcqnbsrj.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2lvyrebiu.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gt2tfcwxcsb.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2gytkpige.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2rfqwvhrr.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2rwpudozf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2rxfhqdbs.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gt2kaiaqsrb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gt2mwfddcjb.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gt2sxtexlbm.html

case class User(name: String, age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2mkgplxqy.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umjgywlg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gt2xfffgwnz.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gt2lrplusws.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2dtetzzye.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gt2qdvdkmot.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gt2xhlgmvak.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gt2mefgjvuc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gt2dqdeykqi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ejbkpyxo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gt2ktzvrwme.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dmjznyzz.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gt2gypxbygp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gt2kekeofzz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gt2nhoppknd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gt2bcfpemuq.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gt2obymxxch.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenzaomai.com/Article/details/gt2qtbmxnez.html

[U04] Py：变量调试打印
来源：http://dali.iojbl.cn/Article/details/gt2yydhctmz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sysykeji.top/Article/details/gt2gbgnrceb.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gt2shgqvoks.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyjimroc.html

[U06] Py：合并两个字典
来源：http://dali.cheryme.top/Article/details/gt2hetltjgb.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uecacdxq.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gt2ybrtetdp.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbmofhzn.html

[U08] Py：展平二维列表
来源：http://dali.cheryme.top/Article/details/gt2agmpmarj.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypotlwpp.html

[U09] Py：字典取最大值的键
来源：http://dali.hnqzz.top/Article/details/gt2smcdceyw.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gt2zqdbkxke.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gt2rytilsgh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gt2mvacgwfq.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyhsrywd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtytwxoz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yanxiufei.cn/Article/details/gt2nmvmpnmw.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gt2nusadbqg.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2pbsimxna.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gt2jaygexti.html

[U14] Py：分组收集到列表
来源：http://dali.tian-w.cn/Article/details/gt2jggzttlv.html

defaultdict(list)
来源：http://dali.iojbl.cn/Article/details/gt2bjpbnwbu.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gt2foldlhkf.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gt2zmyatywo.html

[U16] Py：命令行参数解析
来源：http://dali.jinqigufen.top/Article/details/gt2opkmucqd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenlongwang.top/Article/details/gt2ikcxlgab.html

[U17] Py：初始化日志
来源：http://dali.hnxiangtu.top/Article/details/gt2cghplwme.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuubujqj.html

[U18] Py：预编译正则
来源：http://dali.tianlin.xyz/Article/details/gt2xxznriai.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gt2kgsxbohe.html

[U19] Py：正则替换带回调
来源：http://dali.yanxiufei.cn/Article/details/gt2vatcyhyb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lfmmcbpl.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2wgpqmopt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlhxpaex.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gt2hjarwgbg.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2cdcdzcqg.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gt2bakwcwjg.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gt2fczldodb.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfqceotu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eeobhwph.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gt2kixntdks.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gt2mbvsigvl.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gt2pflsxhyo.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gt2cymibtpu.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gt2xpmnmhjd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gt2jvnlaaly.html

[U27] Py：异步 HTTP
来源：http://dali.birdmap.top/Article/details/gt2ztteapzq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nanxinkj.top/Article/details/gt2evknmubu.html

[U28] Py：类型别名
来源：http://dali.snrcjt.cn/Article/details/gt2dujxzgpe.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gt2jetsxokl.html

[U29] Py：属性校验
来源：http://dali.svipenyu.cn/Article/details/gt2teuwzgny.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agibfyts.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2spknjygh.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2fmcsjuoh.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gt2tqnhevnd.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gt2rppgoxlt.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gt2sshplwiv.html

ruff format . && ruff check --fix .
来源：http://dali.gogol.net.cn/Article/details/gt2rxnzwtlk.html


<!-- 参考信息 -->