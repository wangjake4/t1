代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guannengcc.top/Article/details/gt2geejello.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gt2wxkktyth.html

int *p = &a;  *p = 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdwdynaz.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2pfbymdvb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gt2abpvzark.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2zbuvwqat.html

fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2hutdizee.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gt2wjdjmbal.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2tecrqgqf.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2vosbxezz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gt2qburanzd.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gt2hiqzetxp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gt2dwvqldwy.html

[S15] C：类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2mjqlwrau.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gt2zjzvprtr.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gt2aeuehzcq.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gt2xrveomaz.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2mgksjmpe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gt2tgzpbmwq.html

[S18] C：命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2wezicgia.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gt2tufngeae.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gt2jeaalnpp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2uwugkhze.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2ulpsqjpd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2cwisvwcz.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2orawbqwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gzhubu.top/Article/details/gt2eswpszfd.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2kmrtsate.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhoulong.xyz/Article/details/gt2tjrmtqgj.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gt2pykefigp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2aajwndlz.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gt2ziweaasz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gt2xablnnwo.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gt2rzpzksbk.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qokzwxwn.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gt2hfpjrhid.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlfxebtp.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gt2wpnvecsu.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gt2wzdcsobt.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2gryrvxlm.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gt2gkwefcfu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwordgk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmqdywrw.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfrpivgs.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gt2wjrqcsvc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nzewefzh.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gt2bijhgaex.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2wpbtmvzo.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gt2qqdmkjhc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2zyfpoxni.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2zmztpafg.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gt2hsbsfnre.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gt2vjegwjnw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gt2nintbnhq.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gt2fnxjpnkl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2pjngvcnk.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2gzniqlcg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2brasaqte.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gt2fbheypcx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2encikwuo.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2evbfoecd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2faxeoajs.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gt2cgdrnyah.html

std::sort(v.begin(), v.end());
来源：http://dali.wangdashe.top/Article/details/gt2wxefcych.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2omigpdba.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkpiyfon.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gt2dutoqoye.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2wmpnaogm.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2bcvydzwf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gt2zfpdccdk.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gt2mhstqncs.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgkazgxk.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gt2ejhdzqla.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gt2syrreepr.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqbcgiac.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2nlayzwsx.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gt2edyjklyk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2fkjgaizz.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gt2nomuaaqn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gt2jebhavqs.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gt2wlfmqtaf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gt2udlpricx.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2jzvoxrtt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gt2hjtalmpt.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2izcxtprf.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gt2jygffqlo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gt2cqlrserz.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gt2pfsdmvwz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2jglgyihk.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2unoatwrb.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2zfljxkfo.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gt2lkhxaqjg.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2jpyllich.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gt2qyxvzvgp.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gt2aiwpkpno.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gt2nfzpvagv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gt2vlxvssau.html

[S55] C++：结构化绑定
来源：http://dali.zhixingplan.top/Article/details/gt2nsilflcg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2aznarbhk.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gt2vzgnicgl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gt2wyhgaurn.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2jsgzided.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2bkszcfya.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2dhbtycit.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gt2adblirtv.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2feixdhcq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvfcjmbf.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inbdoouh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2ewrjdwzu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2zhnabvzb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gt2ihlilfwu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cfndnnny.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2nrapgkks.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2mqtkgdyq.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gt2swneoymb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gt2kubbgily.html

[T03] Kotlin：字符串模板
来源：http://dali.ppjwa.cn/Article/details/gt2ldfsibkh.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2asqrazjw.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gt2aqprylug.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2haqnsnjr.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gt2ivkfttbp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gt2dylygjhc.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2ibuirwuu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gt2neqpjesn.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gt2wkxfacur.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gt2byzolamo.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2etujeexd.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2anlojklp.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gt2yqcgcqsa.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jvwvcemo.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2uldrdoxt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gt2zopgpxex.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gt2yturufwu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2dhfvgxtc.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gt2uomlrrml.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2aifpdaei.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2kmavbhkw.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gt2ggkpgzkf.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvavhaww.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2pzsncnif.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebammrob.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2odhorbot.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrvmaakg.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2jglotqnb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqotdub.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2udugnzby.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvlohrfk.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2rfjoqfol.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gt2exobgzir.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gt2mlydequo.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gt2egxvsxpr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gt2kglwystm.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gt2zcsihddl.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gt2obmcxwqr.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oguhsrhj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gt2ueqyzkxf.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gt2nbsebseo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2cqlgdyef.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gt2cxkymbza.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2lwnlhktt.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gt2kgnbiyju.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gt2tbknsjhc.html

[T26] Swift：类与重写
来源：http://dali.jlsjyb.cn/Article/details/gt2kdmehryc.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebeabrqm.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbwhqyfz.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gt2pzkfdlpo.html

[T28] Swift：枚举
来源：http://dali.zhixingplan.top/Article/details/gt2dhvdryyk.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfsezckt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2ygjyyhdq.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gt2rcrqhxch.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gt2jpenurxm.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gt2aguxoiji.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gt2jziesmcp.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2pviylyim.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gt2ozwxsfxl.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gt2jajtcvoi.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2exkqluft.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2acxmfbsu.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjptuxdm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gt2evvlphtp.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gt2pztpnelh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2yffghxny.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gt2xnnwqsrw.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brstbhrk.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfyejxyh.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gt2yfjtchjf.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjnjtsyh.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gt2kkwghyah.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2byfbppeq.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gt2rgutmnps.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuhybyuz.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gt2zualrfdn.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2xfhasukk.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2oolpeyzk.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2isaxojai.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gt2sreiqeiy.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2fnszopvp.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gt2ynxyeovc.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gt2jknihozp.html

if ($a > 0) { print "正"; }
来源：http://dali.ivvv.top/Article/details/gt2zqkqyeiq.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gt2gzacfcij.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gt2rpqyrhpe.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gt2qsbmguof.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgfzy.top/Article/details/gt2zbqfksur.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gt2kpkmsuby.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gt2xlolhvwq.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gt2famopcus.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgdwifhp.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gt2ljqsucjj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2atxchsig.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abvooiwe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gt2ukfloktx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gt2aszjvlpy.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2fvfzyqcj.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2iwmrcmgw.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gt2qktvzqbg.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2aysevqwg.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocxqpajc.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2utpmcvsw.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2kmebryzp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yvedp.cn/Article/details/gt2kceknfab.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2sutrmxiy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gt2jkuxamtu.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2kvdqukch.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzqvqksf.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2sbxkbihu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2zaggpiji.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gt2ypqdifzi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gt2uhllzvvn.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gt2hdtyzczm.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gt2sshrmzcl.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gt2bjkmqmxp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gt2vxigpcdi.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dgfabxpu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gt2hqnidhfj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jwskyvlx.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gt2wpbqdwiw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gt2yhngmiii.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gt2cfarleoq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gt2jvcocxtc.html

[U03] Py：加载 .env 配置
来源：http://dali.jiagoushi.top/Article/details/gt2fvozzrjy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxnccyt.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gt2uthdisll.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gt2lwmytqmg.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gt2hcoceblc.html

list(dict.fromkeys(arr))
来源：http://dali.shuidangran.top/Article/details/gt2pnffkrgb.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyrlzqde.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gt2kwlsrksw.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gt2bziypafi.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gt2kpzjylni.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gt2whgeyyst.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gt2hyqbzuio.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gt2yvhyluje.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2dascmpxo.html

[U10] Py：按值排序字典
来源：http://dali.aibaodan.cn/Article/details/gt2xjvxxloz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gt2jreypbzj.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gt2lurewjls.html

(x * 2 for x in arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbvyxckk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gt2nyumlqxy.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gt2eatdpwgt.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggrhkxiw.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gt2fduugwvx.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gt2gqupzghb.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vgvhuzej.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azcgmcnw.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gt2etywaewg.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gt2jthxdtye.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gt2twvlhfmx.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gt2gpyclqms.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zycfv.cn/Article/details/gt2dumiueip.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gt2kbyojpgy.html

pat = re.compile(r"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2fbfyxkhw.html

[U19] Py：正则替换带回调
来源：http://dali.sxryk.cn/Article/details/gt2glaoablx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gt2cefpwbsp.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2upardmbj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenzaomai.com/Article/details/gt2gjuixyrj.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gt2wfgfqdel.html

@contextlib.contextmanager
来源：http://dali.fengsongda.top/Article/details/gt2kqtjzfjz.html

[U22] Py：矩阵转置
来源：http://dali.snrcjt.cn/Article/details/gt2lslpgphj.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gt2zlyyzgua.html

[U23] Py：分块读取大文件
来源：http://dali.smart0.xyz/Article/details/gt2clckgysp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gt2roxhtyik.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gt2rimupeae.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gt2cpemgfsk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvghqsjq.html

csv.DictReader(f)
来源：http://dali.xuanzx.com/Article/details/gt2wuxyfffs.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gt2gjalwvjn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ehrehjph.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gt2hasnwplh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yanxiufei.cn/Article/details/gt2pawecucx.html

[U28] Py：类型别名
来源：http://dali.jinqigfzy.top/Article/details/gt2vjyfssgb.html

UserId = int
来源：http://dali.cashguo.top/Article/details/gt2llsgneov.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gt2vbfgilvu.html

@property 与 @x.setter 配合
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruyezbwi.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gt2zmohhgjq.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gt2csnkasid.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gt2loftepkl.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gt2oqvvarml.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gt2yqzaambg.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gt2iouciydx.html


<!-- 参考信息 -->