代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2jpzdtrov.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gt2eikwpdyq.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gt2pxkhqqya.html

[S16] C：位操作置位
来源：http://dali.xziqi.cn/Article/details/gt2zyymsegj.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gt2uuyftsbf.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2kamhsraw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2tthepvgz.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2gkoqkssd.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gt2ttvxzphx.html

[S19] C：快速排序
来源：http://dali.sysykeji.top/Article/details/gt2gsnzhuho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctzvkcdn.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2zzhsopzt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2bqjnotzi.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gt2tsdruqsm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gt2phlimakj.html

[S22] C：字符串转数字
来源：http://dali.gotoacloud.top/Article/details/gt2ksaucmxw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irtxjzjp.html

[S23] C：随机数
来源：http://dali.zhengqikj.top/Article/details/gt2fegdeajk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2dppjskjk.html

[S24] C：获取本地时间
来源：http://dali.gogol.net.cn/Article/details/gt2jbcjvudb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gt2ibilspek.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gt2udopoyng.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gt2rbmprbee.html

[S26] C：内存清零
来源：http://dali.quarkkingdee.top/Article/details/gt2lnsxieyo.html

memset(a, 0, sizeof a);
来源：http://dali.zhengqikj.top/Article/details/gt2cnlwlkoo.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gt2wingpeil.html

const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2eqvyzrrz.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gt2pobbzkgi.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gt2opgzyrhs.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gt2kkijptri.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xinyue.icu/Article/details/gt2blthqhpr.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2gujyxvvk.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gt2qixidfev.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sbhnakge.html

#endif
来源：http://dali.xziqi.cn/Article/details/gt2kjuwxwxl.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2kvjowxua.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trmluazz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmdrqndf.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gt2cmtovuhq.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gt2ymusytwk.html

[S33] C++：vector 增删
来源：http://dali.cucudq.cn/Article/details/gt2xoosztbx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gt2jqwzksty.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gt2vpkjffws.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nfcmstpw.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gt2mqudqjgi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eahpextv.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gt2camkurqq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shjmoypk.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2efarbwhk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2lrgkmyhm.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gt2zobewfod.html

std::sort(v.begin(), v.end());
来源：http://dali.haohaochexian.top/Article/details/gt2zwcgttrc.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gt2ynbtzokw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gt2vaxnuxue.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gt2wsouptdm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gt2blcifejq.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2rmnzxjrz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gt2yehofrjv.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gt2qiyceobg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gt2wffnparn.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gt2ghqolmzm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gt2sxjuggsm.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gt2kxzzrzoe.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gt2cssfgnum.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlnloqui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gt2lcjwmfsa.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gt2mhklwfie.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tczmenkg.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gt2qgbemmrd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gt2geiknuod.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2ewbblzif.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gijgzpco.html

while (std::getline(in, line)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2oscgdarh.html

[S49] C++：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hppimsso.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmzynwae.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gt2ezbbzvqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzxoixkn.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2ciliuule.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gt2yzqtmxyj.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gt2qfxqjfyd.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gt2kfzfgrpq.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gt2pmdfxago.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gt2wmanowqa.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2euaotmre.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gt2yqnzauri.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbidiirc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2onluytvj.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gt2birnpkrw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gt2nsbfkthb.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gt2fwpfhmbk.html

constexpr int N = 10;
来源：http://dali.meibo888.top/Article/details/gt2svitcmts.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gt2gmwtjprj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2csnfnxwr.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gt2dhfbgyhe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2wdboffxh.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gt2vsnwubke.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gt2vajilqgs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2rdjerelr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gt2bglechai.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2hiqttgte.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2opcovjmi.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2scdjpxwz.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gt2oyimadau.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gt2jttzzhob.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iifqishq.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gt2tzvjxtqz.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gt2epuufvmk.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gt2hxzxvocx.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2nnmypqkb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gt2nfakhrhr.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gt2jyqjgprs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2gdbqqhvk.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2njakonou.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2ntjzwmyk.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gt2znsjzsxs.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2rzsypcoc.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gt2qofrzdax.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gt2auuoflcy.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2ermqezxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gt2dfenwpad.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gt2mkmogglf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dsscdaro.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzxcifsn.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2xbrudakt.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gt2pisawhmo.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nyussldu.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gt2lvsqgeqv.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2agszqmke.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mflkigbq.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdzmjyqn.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gt2oihjcgst.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2ilepambk.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gt2mmjcfvuj.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvqouaxe.html

[T18] Swift：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2jgkxvwmx.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2rmxotrya.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gt2dsaqhnmn.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2yupgctzn.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gt2pxrvmxxg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gt2ndydgmro.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2wbwmnnvw.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2tufyvbcl.html

[T22] Swift：字典
来源：http://dali.smart0.xyz/Article/details/gt2jjorhdvb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhixingplan.top/Article/details/gt2fqtbkvca.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkxjfhvj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2juxwmaym.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gt2lrcejjnm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbewkvfj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgeqmpv.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gt2vkaijlpb.html

[T26] Swift：类与重写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvlbuijg.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gt2neykwdmc.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlrdgtqb.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gt2pwmzbpaz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqjgrjh.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gt2wttabopc.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2kfafkysy.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gt2ahyqhnqq.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gt2iuareazq.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqaphokw.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2qtfbpmsg.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2ojjrhikf.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gt2rjmxyzqv.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjjmdbzh.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2grdighwi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gt2geuyknav.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gt2sfqjokyp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cashguo.top/Article/details/gt2uicleilm.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gt2dpnwijdj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajsfrthy.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gt2pjedduth.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gt2tzzegglg.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gt2hwafowoh.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gt2wkbeouzy.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gt2cwfimznl.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gt2lwwrztyd.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gt2iybckkiq.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2leohxiwx.html

[T40] Lua：元表
来源：http://dali.jianghu66.top/Article/details/gt2iwmlnhsi.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gt2ydewrilw.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2llqqlqvq.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gt2jaithuxe.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gt2vuqwopwu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpetpvk.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2wsfaolzb.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gt2psipkjgx.html

[T44] Perl：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcsllhji.html

if ($a > 0) { print "正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2rzbfjjfn.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2ddrhpfwn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zyjifuwi.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gt2agzmxaft.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gt2tawwdofz.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gt2ktepzagy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zerqrkhx.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gt2mqztzlyl.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oyopdrjh.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gt2cdbqjjtw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cbfbnicd.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2qctfnkoa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cheryme.top/Article/details/gt2vovssafl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gt2broaakhk.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2yczpbixz.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2mzeawqsj.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2cebdvbbj.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2wsvufwxj.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajtxqlin.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2iwxbnysh.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2ohkoegyb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gt2lrnoywlr.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2brdfnebq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gt2yrtmgcbw.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpsudlxw.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2nzmwtrjm.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gt2gcoqzogv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2hwpxneao.html

[T58] Scala：函数定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2koaynxid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gt2tyqkpvzm.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gt2dsitmjgw.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gt2utniqhus.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gt2zlvjalue.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2ipgufqkt.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2sjybhkxn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gt2hxvaaogf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2glaujjvo.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gt2uouuhdal.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gt2xnqrdkjb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gt2dpgznidy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zycfv.cn/Article/details/gt2qcrofpaj.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgfzy.top/Article/details/gt2dvkbjbbh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gt2svfygnfo.html

[U04] Py：变量调试打印
来源：http://dali.gotoacloud.top/Article/details/gt2neeloixe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gt2zphqgaca.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gt2nitzibqj.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2ymtshndg.html

[U06] Py：合并两个字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prrzgogs.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gt2cejnzddh.html

[U07] Py：反转字典键值
来源：http://dali.cdnleiting.top/Article/details/gt2taaglvrk.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gt2rxmqvjqc.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gt2dzegskcs.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gt2ktlwkubs.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gt2qpvsibxy.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2elvdvois.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gt2ietzitig.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gt2zwbphmsv.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gt2cwafcdgs.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2mnjsbcvd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcekgjmf.html

Counter(arr).most_common(3)
来源：http://dali.meibo888.top/Article/details/gt2sljixnkb.html

[U13] Py：固定长度队列
来源：http://dali.meibo888.top/Article/details/gt2fmeviwzj.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohrawnah.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gt2gnrcmkri.html

defaultdict(list)
来源：http://dali.guowangkeji.top/Article/details/gt2zbxmbzii.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gt2eritihky.html

t = time.perf_counter()
来源：http://dali.meibo888.top/Article/details/gt2ivfplimd.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gt2zifjlinw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gt2uvvneqqi.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gt2mdiddhcd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cheryme.top/Article/details/gt2bsrfpcpl.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gt2onfzzmjr.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2usuqbsiq.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gt2aipyfsli.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gt2sqmwdrdw.html

[U20] Py：缓存函数结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vndnhrsw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gt2htefoooc.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gt2srjylobj.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gt2qettzukw.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gt2pbawcokf.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gt2pvowavrm.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gt2aoemuygv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2tmugwpif.html

[U24] Py：路径操作
来源：http://dali.birdmap.top/Article/details/gt2yswsroqf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2pnvnpwgz.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gt2faqccyda.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2raueknox.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2jwvnmnsn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gt2lddxeypj.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gt2lsjtlbgf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gt2xvxppvvs.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gt2fwtyvwmw.html

UserId = int
来源：http://dali.guannengcc.top/Article/details/gt2hcmvwxhw.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gt2jofrltgg.html

@property 与 @x.setter 配合
来源：http://dali.yuanzhike.top/Article/details/gt2wegjculg.html

[U30] Py：数据类
来源：http://dali.jinqigufen.top/Article/details/gt2urjggetr.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndfmhzep.html

[U31] Py：单测
来源：http://dali.daria6918.cn/Article/details/gt2elkhiwxy.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gt2nedwhegw.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gt2nycxufgl.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2wjiralgh.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gt2hnkdqbip.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gt2eqodlrxf.html

[U34] Py：判断编码
来源：http://dali.sweek.top/Article/details/gt2uedjjezp.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gt2itnpubew.html

[U35] Py：发送邮件
来源：http://dali.zhongyouzk.top/Article/details/gt2fkzoijiw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqojclvg.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2dqamirga.html

schedule.every(10).minutes.do(job)
来源：http://dali.yanxiufei.cn/Article/details/gt2tacohatk.html

[U37] Py：读写 Excel
来源：http://dali.yongpay.top/Article/details/gt2xlvvffjh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuxming.cn/Article/details/gt2nzoashgz.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gt2ninfcflw.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gt2jawyiyjg.html


<!-- 参考信息 -->