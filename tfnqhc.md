代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2ewwvpovi.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkiojgpe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gt2ekxjmqes.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gt2objvzhrp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gt2lldhwccs.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgxljiwx.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2jlvyowih.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gt2njwpgcbx.html

x |= (1 << 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghqqgllv.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2kamsgjhl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gt2mvanudda.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vniulrwr.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuctuqpk.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gt2gqhwfyvd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gt2brftjiyc.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2krfkkjvj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2gdkcckxo.html

[S21] C：字符类别判断
来源：http://dali.hammf.cn/Article/details/gt2zipjczwh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2ukcboduv.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2fbwcseew.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gt2wfwbyjmf.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2outtaiob.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2ejdptbyk.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gt2ivfhaljo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2agrmztbp.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhrelunm.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2kzmyugib.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2paxalzto.html

memset(a, 0, sizeof a);
来源：http://dali.nwbrower.top/Article/details/gt2tfipyieg.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gt2chkszgri.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfostned.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gt2nvkvuccp.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gt2wioxclmc.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2ontdlabc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gt2wlxzonms.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gt2vbxaiody.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gt2ewyuwooe.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2cilgmvfi.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2haxasnpt.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2jvgqmkmx.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2sliydtfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gt2erhnjiau.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2iynqrvtc.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gt2eziotmtw.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gt2wetwzzme.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gt2cljrjrys.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gt2cenkglfs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjslatto.html

[S35] C++：map
来源：http://dali.vqdsnc.cn/Article/details/gt2velsnuhz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2uzcagacs.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2femewado.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocquemis.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gt2zttxpegf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nifkqcxc.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2ddjyrlfu.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2roldncgo.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gt2vsmrkjcr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gt2dikipanu.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gt2wiohntcg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yangfankeji.com/Article/details/gt2upjaksxl.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gt2pouzedcu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gt2hdirkbqa.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gt2nszipbmz.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gt2zopunbsk.html

[S43] C++：智能指针
来源：http://dali.jianghu66.top/Article/details/gt2cpmugqon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mulpkrqk.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gt2czgycoem.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2tnibrccb.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2zaawylmx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2nslqtuua.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2hhoftptc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gt2nqjfnhrk.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gt2kqxargdk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gt2ryynoiyv.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ionvseum.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gt2qyxbwnan.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gt2ljafwarv.html

[S49] C++：写文件
来源：http://dali.fengsongda.top/Article/details/gt2ozkahojv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gt2zfzcmmcc.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gt2pitttgxz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2hqijuyik.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gt2ezgdxydj.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gt2wtlmiyqo.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gt2wopbsqpo.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gt2jvpjcjvm.html

[S53] C++：移动语义
来源：http://dali.316326.xyz/Article/details/gt2mlywatfs.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gt2vtyigakj.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2betvmjot.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2allgmrgs.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gt2luwmoyyd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2llfjumjj.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gt2pnsrgjbm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gt2trgegsyl.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2wrptydpc.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2pcobwzdv.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yisrevuo.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2cohdflme.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clteydel.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gt2wppihqwk.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2oopwiexu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gt2cmfsuunt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2dgrpdsaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2noxydhqr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2whumripc.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2krfgljli.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2fkgqskgz.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuftbzwm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2crzyhtad.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gt2bskrtjqa.html

"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2pxfcqpyw.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2vsymenrt.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmfoxprt.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2ilgezotm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gt2gkfeaoan.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2elcqzfqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2mljwmgmy.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gt2luvbyjhv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2qbermxvf.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2ruwvrero.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2kqphowdm.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gt2uwvaizty.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gt2wdhffbfo.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zcnmllmd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gt2akbtzyph.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gt2sknvmvpy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gt2ngxhgzmf.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gt2fcjzzmnm.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2sfpuhmwn.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gt2zatdhypa.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gt2nhqrhdmu.html

[T14] Kotlin：循环
来源：http://dali.yonumen.top/Article/details/gt2vcvmhuot.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gt2jqzljbek.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gt2qvlsekuv.html

interface Shape { fun area(): Double }
来源：http://dali.hywenlv.cn/Article/details/gt2mrqhmvdo.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhefymrp.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2tgbxqjgb.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2dcnvncll.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2xczncdqm.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2vttkcxoa.html

"值: \(b)"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrttbayu.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gt2fuerrvfl.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gt2gxbcwjsz.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2nllgwcgs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gt2iipbiviz.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gt2fdnbwqhh.html

for x in a { print(x) }
来源：http://dali.cdnleiting.top/Article/details/gt2gxxxrrmo.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gt2raskgwor.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gt2fdaikxdf.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gt2bbwmgxia.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydkylhgx.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2gjdtggah.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gt2lijkozxv.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gt2mtzrwjbi.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkwryopi.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2ypqaklnu.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gt2ighgnvah.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2toifbhee.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gt2zhrmfref.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gt2owfuvpkw.html

enum Color { case red, green }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnylmrdo.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2ksjgxeju.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gt2lqplgiij.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gt2suvpimse.html

protocol Shape { func area() -> Double }
来源：http://dali.hnqzz.top/Article/details/gt2zyklorei.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbqyswah.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2zdgvvead.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gt2ubbasblz.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2glbyqcvp.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gt2zgmgjmqp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.svipenyu.cn/Article/details/gt2qqijnbbi.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gt2rjfrifor.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gt2epnlqatb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjdlnvf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gt2qlanmoha.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mybepjgw.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gt2blfbdtrs.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gt2ewstzrmu.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gt2xfulmhwi.html

[T38] Lua：条件
来源：http://dali.yueranfly.top/Article/details/gt2yimrnzaj.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gt2xjdzbbee.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2afvaeuph.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gt2qzzsxfgq.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gt2dhhtlxiz.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbhrshyu.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2inocpvqp.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gt2vlkilkex.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gt2bmvazabw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gt2zmxyfcdo.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2ckegssfa.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gt2zubnrfrc.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gt2fzpbapum.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gt2jsssipzw.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gt2nximgvdx.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2vrlhwafc.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gt2usrlzniv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gt2laklfuoc.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gt2aqfqmzex.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cqqwz.cn/Article/details/gt2dbzgbmnu.html

[T48] Perl：正则替换
来源：http://dali.xylfe.cn/Article/details/gt2zamuiitq.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2qwxxtxbk.html

[T49] Perl：函数
来源：http://dali.sufxvd.cn/Article/details/gt2vilfnifw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2jjtybqdz.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2agjxkpji.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqgqtvy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gt2jlvjvigj.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2vpqdnelm.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gt2cseclbxa.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gt2fnfqzllm.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gt2todbwmft.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2tqonricv.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gt2vbgpkrkz.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utazbsre.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gt2eldpehsi.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2jmntkgjo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gt2scfczudh.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gt2yffmfzzq.html

case class User(name: String, age: Int)
来源：http://dali.316326.xyz/Article/details/gt2jvzmbxhf.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2xzpdmfqo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2fciulwto.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2pihpddoe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigfzy.top/Article/details/gt2fsliaoqh.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gt2ywzwoohc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xygodidr.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gt2ucxwlrch.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gt2voqwihsn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ddavfkwo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2nuafkfnd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyowwyrb.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2ahwycezd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gt2nxqdyzjv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gt2ybxwvpdn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2oqqzawdl.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2oskzuzms.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gt2cwvfsfhf.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gt2rpzdomby.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gt2wvuyopew.html

[U05] Py：列表去重且保序
来源：http://dali.havefunace.top/Article/details/gt2nirfbban.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2zlkwjjlo.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gt2wlzvcojc.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2tqsrxsub.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqbiavqs.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gt2wkgvuvsw.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gt2ltndpijp.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gt2vaiwnulj.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gt2imsajkla.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mlqpifxj.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gt2qfjogsyh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygjnnvky.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gt2kfujhgzx.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2uymfvbaf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gt2ktvrknug.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gt2nfuatgwy.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gt2wvgnjnzi.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gt2bkchqpoi.html

[U14] Py：分组收集到列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqgsjkfq.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gt2codbcuzh.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gt2ccjfdwjb.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gt2jwxktdqq.html

[U16] Py：命令行参数解析
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjqtanit.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnxiangtu.top/Article/details/gt2dnyvcvrk.html

[U17] Py：初始化日志
来源：http://dali.fengsongda.top/Article/details/gt2seixkpfh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gt2qnfkxfzd.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gt2ifudmjto.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gt2bbsmhsej.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gt2ceywzrsf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.quarkkingdee.top/Article/details/gt2luwbyexk.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhykuhxj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.iojbl.cn/Article/details/gt2xzswzwlu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gt2yvuzrsim.html

@contextlib.contextmanager
来源：http://dali.hnxiangtu.top/Article/details/gt2dlrncyda.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gt2ilznpbfg.html

list(zip(*m))
来源：http://dali.meibo888.top/Article/details/gt2onydbkuk.html

[U23] Py：分块读取大文件
来源：http://dali.ydzc1.top/Article/details/gt2bkkjbbxy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2unzyyxuk.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gt2gbxqynta.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2fwvtstlf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gt2ydowzzlp.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gt2slvqnykq.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qelpbjix.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ppjwa.cn/Article/details/gt2znfmvktc.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qgmtjsgu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gt2apxnovbr.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gt2tbmmadan.html

UserId = int
来源：http://dali.jianghu66.top/Article/details/gt2ecmotcrm.html

[U29] Py：属性校验
来源：http://dali.jyoumei.cn/Article/details/gt2luhtfzpb.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gt2gqpqwcfw.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2tfclfwbr.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maxvdpmd.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gt2myvctnsp.html

python -m pytest -q
来源：http://dali.tanke756.top/Article/details/gt2sqqulqap.html

[U32] Py：代码格式化
来源：http://dali.ivvv.top/Article/details/gt2bagsrebo.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gt2qknyowsh.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gt2huzfdmoj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigfzy.top/Article/details/gt2mdczworc.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkanbogl.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gt2gzbutjgn.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gt2zjundgad.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pycfn.com/Article/details/gt2skooqvxc.html

[U36] Py：定时任务
来源：http://dali.quarkkingdee.top/Article/details/gt2cqtubhto.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gt2cdwiqupg.html


<!-- 参考信息 -->