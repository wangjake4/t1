代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gt2auxnybqg.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iijledzc.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gt2qdnpubaj.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2qyhbtfoo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gt2sohvbttu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gt2cjksckri.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abyfqrtx.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gt2sjhyytbt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2nyvnrafh.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gt2ekvfakvx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gt2vuysdsxr.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2fuslhnwo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2ncqxbals.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2tdihyvoh.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2wrrxqzxx.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gt2gcimtioe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlnhvac.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdskpzdk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gt2pzwkkgvx.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eradvixd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2diimejkz.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gt2eehynvcu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2lvbsyhux.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gt2bsxhqhng.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2xrksqnaj.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2piudqvjr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gt2ylohfhol.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2sbiyafxi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2oayewqym.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gt2hltkxmcj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gt2ffxiwbpq.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2uvzcgrow.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2zfcehzzs.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gt2qpklpbry.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uebgvnua.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gt2ldwkxcvq.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2holwfcag.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfowfsmu.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2nxhqftiw.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2jfqhksfv.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gt2nsfsscxt.html

[S29] C：变参函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztezidvq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gt2owaacmwi.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gt2cucftong.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2apljplhz.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2qvcrecux.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2nxnupotk.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2mtsglyng.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gt2wfdjfafz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2fptlqxdn.html

[S32] C++：字符串
来源：http://dali.yj202588.top/Article/details/gt2bkgmmonp.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlckdqal.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2ktkvampd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2vhviwttx.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2zptocqxq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gt2fulranmc.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2tkihueee.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2dxeiasuz.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gt2unbsdahy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2hdwivwdb.html

[S37] C++：set
来源：http://dali.daria6918.cn/Article/details/gt2wqaigaay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gt2dofufipo.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gt2hletuiqt.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gt2fsqsbrbw.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2mhwqwlzk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gotoacloud.top/Article/details/gt2hijoajsl.html

[S40] C++：查找元素
来源：http://dali.cucudq.cn/Article/details/gt2comnajof.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2leiccfny.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2jnchaslr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2pahufyuu.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2etwfumbc.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2jssbrmlz.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxnpuhes.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gt2lidiwroc.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gt2cgprfuii.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gt2exhhlhiq.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2vmterpam.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gt2kqxuytkn.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gt2onjplyci.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nwbrower.top/Article/details/gt2kjkwygan.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gt2mwqqlvtk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gt2hqlcbrnc.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2kibsvqmh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gt2rsdhiuxq.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gt2pyfbqemf.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gt2shpgpirh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grsixduy.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gt2rbgebulr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2smtoxesw.html

[S51] C++：显式类型转换
来源：http://dali.xylfe.cn/Article/details/gt2aohcjoxp.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2vmzmhzmb.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvswjxhu.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2sikgrfna.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gt2kdfahgnx.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2cqawnrzl.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2ogtuzkmk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gt2hkutifgm.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gt2ruteyyoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2vygxqwqs.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gt2tbhvhqdi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gt2ycqwomgx.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gt2yhpdkluw.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2xubcjadh.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vlpahjik.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2vqnrmcar.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gt2fubmodgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gt2rnepcqun.html

[S60] C++：遍历并删除元素
来源：http://dali.andypj.xyz/Article/details/gt2vevbgncd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2pndeldux.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2plchcylf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2pnzuaalu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2uzeonwlk.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwykdebu.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivayxwrw.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gt2eweiqmdt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gt2xpjmslab.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlxvuvuf.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gt2tiiblpxp.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gt2xjrshirn.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gt2faxrwyaj.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gt2mfonswgv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gt2cdeqkqsv.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2yldgfkih.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gt2pgjoiyaj.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gt2cwrtcaxc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gt2rsqyvmlm.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2phxuvkpz.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2hrfykipl.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gt2kqwmfwou.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2zrhrbtmd.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gt2gesnvwjh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2jfqdzmyi.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gt2erytwjyy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gt2zjwievtx.html

[T12] Kotlin：解构声明
来源：http://dali.yueranfly.top/Article/details/gt2zccgykmy.html

val (a, b) = Pair(1, 2)
来源：http://dali.yvedp.cn/Article/details/gt2ecvbayce.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gt2cxfxnshu.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gt2mpeorcpo.html

[T14] Kotlin：循环
来源：http://dali.jqgufenzy.top/Article/details/gt2dvgzttpc.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gt2vofxarpn.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gt2oxjzzlvz.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gt2vdsdxlpf.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2dxvtyqzx.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2hpsfzawg.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gt2dgutllpd.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gt2mnlfbwvp.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2iutbvdux.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gt2zivqtcds.html

[T19] Swift：可选绑定
来源：http://dali.smart0.xyz/Article/details/gt2juhrduwf.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gt2orofwygm.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gt2ohoopfiv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjnobrjc.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2xaimnjus.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gt2fktzcpsh.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gt2xniosgph.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltbflghb.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2zsokputs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbkwermv.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gt2pxbiczuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2uvecojve.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gt2imhohnho.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2ttbplxce.html

[T26] Swift：类与重写
来源：http://dali.snrcjt.cn/Article/details/gt2brggnpjl.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gt2atwiynqw.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gt2ukzenvvq.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gt2fehfolge.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gt2aeppaqip.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gt2btscvbza.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2heskdfko.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2bjzntkbd.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzutwuev.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ecgvvhqh.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2ndqvmemq.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2ywuvbndd.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2pweweonh.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gt2jreqlakc.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gt2nuzdqubn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gt2rexpiuso.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gt2mrznxyit.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gt2hflexkzk.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gt2fmmpsvcy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2pamgcrej.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gt2cmyjkpns.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gt2grigqmfa.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2xvejlvac.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gt2iitkosun.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gt2cggjzbtk.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2qecbthuu.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gt2dbesahun.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gt2rxkrpsbg.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gt2qvxetpal.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyjxdcha.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2dkhxumwe.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gt2yrynquqx.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gt2aiuscttc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gt2zubpmkvf.html

[T43] Perl：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whbozjsu.html

"值: $a"
来源：http://dali.yueranfly.top/Article/details/gt2oiitfaod.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gt2ikbrhpxy.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gt2jvjgxyit.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2uhciftvq.html

for my $x (@arr) { print $x; }
来源：http://dali.redwolf501.top/Article/details/gt2zvscoeyx.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gt2vfiplsjk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gt2bsrequyl.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gt2ommuzhnf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyshghr.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gt2ibawwghv.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gt2jnhgaskb.html

[T49] Perl：函数
来源：http://dali.zdqjudy.top/Article/details/gt2oytrtbsj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2sxgfetoa.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2vpjvsrjv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gt2dvkvranz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2oxrlfpbl.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2imimrnso.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2ahixfclf.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gt2rjnjojum.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gt2ysnbpccb.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2nqiknlvn.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2xpzpzgjs.html

[T54] Scala：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrbzolgj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2potnbioe.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2ynzkkjmj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gt2mvibzwce.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gt2ugnxymay.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2mecbhjxs.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2dardsmum.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gt2vkmvkvhg.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gt2ooenewyj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gt2iiwgqgiy.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2ljrdbqih.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2cpxjjulz.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gt2usphxmhh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gt2cdqtgckm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utlenpiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gt2gkrmbceb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ehtlpzbz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2xoxplxun.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gt2txcuhuzs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.316326.xyz/Article/details/gt2ujvnsiir.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gt2jwlsbodd.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gt2kjolrxpr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gt2xdxzflxj.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gt2otcgfotx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2hidxwtfe.html

[U05] Py：列表去重且保序
来源：http://dali.sufxvd.cn/Article/details/gt2oygijdez.html

list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gt2htfmyzbj.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gt2gwdtawan.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gt2jpiusnoy.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gt2pufdecjv.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oenxgmnj.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gt2tvmgybps.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gt2aqfzrbgl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gt2cwwwulch.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gt2vdawhnkt.html

[U10] Py：按值排序字典
来源：http://dali.zycfv.cn/Article/details/gt2qsvznuil.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gt2cbhnwbrn.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gt2jtvwshsr.html

(x * 2 for x in arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2xzgtlpek.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gt2lvkcdfou.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gt2malhdvzt.html

[U13] Py：固定长度队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbetohbp.html

deque(maxlen=10)
来源：http://dali.wangdashe.top/Article/details/gt2htmbjlqj.html

[U14] Py：分组收集到列表
来源：http://dali.gogol.net.cn/Article/details/gt2cvawlxgz.html

defaultdict(list)
来源：http://dali.guannengcc.top/Article/details/gt2qamoowjm.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gt2xdzynmzw.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gt2telxcfgf.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gt2kqfvbkoq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmzkbef.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gt2bgwhavmv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gt2kdzdukbf.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gt2ikrldvqs.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gt2iqugrzzg.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2hwbgwhua.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gt2jnwarffq.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gt2imsiykwz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gt2xtbxqhfy.html

[U21] Py：自定义上下文管理器
来源：http://dali.daria6918.cn/Article/details/gt2uuqvojrl.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2eltvjcne.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gt2ndpgwbbq.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gt2qgklkvqx.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gt2fvuqplhi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigufen.top/Article/details/gt2rjgmmsdp.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gt2ytkifrbn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gt2avqlyafp.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gt2endgaugl.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gt2lrehhhhv.html

[U26] Py：并发下载
来源：http://dali.zycfv.cn/Article/details/gt2xjlyoida.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gt2svznmaht.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gt2zkjfuqvx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gt2qtfpyakg.html

[U28] Py：类型别名
来源：http://dali.chenzaomai.com/Article/details/gt2qvfjylpr.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gt2gzpknbsy.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gt2jxooflab.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gt2gncaowzy.html

[U30] Py：数据类
来源：http://dali.hywenlv.cn/Article/details/gt2ilfouiwg.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2swyqbfzu.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gt2zljmmrmk.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gt2adualdbi.html

[U32] Py：代码格式化
来源：http://dali.bjfxy.top/Article/details/gt2pchkvgsh.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gt2ritsrsgj.html


<!-- 参考信息 -->