代发 wailian999

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gt2jnczasze.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gt2qdhvtqhw.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejobopcv.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gt2oprdmeda.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2ogllmcue.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2ytakoipo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gt2wqkzonmv.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2ndmsotps.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkwblpxw.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2oxsxczys.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2vpfagywb.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gt2kkplgtkk.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gt2uamqgjlx.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2eenxkugx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvlsckbk.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2odtnfoqu.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gt2oscihkvd.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2qqkdmwjl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxilsipv.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gt2izilxkzq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2aneqbnzm.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gpozlhff.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2vujchkih.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2lulqnctk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2frrvhozn.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gt2szpvgfpw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cheryme.top/Article/details/gt2jumvgzkl.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmlvwazw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gt2rjgmecop.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2gdbkmxgv.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gt2bgmstoco.html

[S26] C：内存清零
来源：http://dali.xuanzx.com/Article/details/gt2nzxvuiyn.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gt2ewwdfdwa.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gt2gqipkywj.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2kfjozvek.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gt2fmrpeuaw.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gt2enfxjksi.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gt2miktmklg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gt2gyssjmaj.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gt2rkhsivaz.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2bknvucuy.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gt2hsunvbcx.html

#endif
来源：http://dali.ybcxt.top/Article/details/gt2khysgyke.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gt2egyljfie.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gt2askewoqp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gt2qjxnquch.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2okohmsov.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gt2zzgmxzxp.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gt2pyqitfhf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpargymm.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gt2nppdgrhp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2hhoxyple.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gt2nswcqmbz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2jkbrhmkz.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gt2ncjfcpgu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gt2wfgyjrrf.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gt2vsllycmr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gt2jpzolqtl.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2bohlbgwa.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2toerokuh.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2tdqswdgf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2skwoijza.html

[S40] C++：查找元素
来源：http://dali.zhengqikj.top/Article/details/gt2ptufpyop.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gt2irksfjqc.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2lvwwwdry.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gt2akiyxjtu.html

[S42] C++：继承与虚函数
来源：http://dali.daxiang520.top/Article/details/gt2nemuaato.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuanzhike.top/Article/details/gt2anhehkdu.html

[S43] C++：智能指针
来源：http://dali.hywenlv.cn/Article/details/gt2dinlpnts.html

auto p = std::make_unique<int>(5);
来源：http://dali.ybcxt.top/Article/details/gt2vdwcmebi.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2zzpmujvp.html

void inc(int &x) { ++x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqykgdtu.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gt2dkjcrmrk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gt2awmlcyvz.html

[S46] C++：函数模板
来源：http://dali.chenzaomai.com/Article/details/gt2qxlqfznr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2vbmnlima.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2donpxujk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gt2rrmsxqgl.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2vbonhyzr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gt2lxrwxtqk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvqndkj.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvhqnwdo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gt2pozdibxw.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gt2xbptvdok.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2ltcoayvp.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gt2pmibjqlm.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gt2cqkhgnjl.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2jkyzanwh.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gt2idcshocn.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gt2bxlwddyc.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gt2fchmlybw.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gt2rutypujy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gt2mpkuhiby.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gt2lyebricw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2yxqesnaj.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gt2eotzdmve.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gt2rakcrwkd.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gt2lncigzyo.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gt2irzbptmp.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpzwurke.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gt2ttkmovpt.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2nvcytpgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gt2zpqmklif.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gt2xnrvwqqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2zuqcydyg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jgconbiu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2cjsdirng.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gjsmyrpn.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2kgkcdhdb.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2zkmrjxgm.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2dbexgonz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfrhwrmd.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gt2cyzstluw.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2qsmiilbw.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgftxjyj.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2ntoflyha.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gt2cioxnelx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gt2dxvvmfme.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2zkwtxepn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2tjzdnefk.html

[T07] Kotlin：集合过滤
来源：http://dali.xziqi.cn/Article/details/gt2crwhgsjd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2guyzhhbl.html

[T08] Kotlin：数据类
来源：http://dali.zhengqikj.top/Article/details/gt2wrbzbenr.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gt2vpeidrbw.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gt2baqtjscg.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gt2ylipjbpc.html

[T10] Kotlin：默认参数
来源：http://dali.cashguo.top/Article/details/gt2gygimvmo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gt2baeslqpx.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gt2dlyoqomy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2aluomzlb.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gt2nqihkoha.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2akowlwtw.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gt2fuqaczju.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gt2tsgzecsi.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gt2upmzgqhe.html

for (i in 1..10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2jaeyfvfn.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gt2jvqikggy.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gt2jaqokpjo.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvqaszrf.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2kcqkjhqq.html

[T17] Swift：变量与常量
来源：http://dali.yueranfly.top/Article/details/gt2kkkpyaip.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gt2lazociyn.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2brkcciik.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2imtetacf.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gt2jwrfooki.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2cbpucqpd.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gt2vwmtirhe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gt2vpkjnvgo.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gt2sembuxxe.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuiksmdw.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxshkfdv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gt2bsgzxiar.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gt2allbwasl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2fynnwmhl.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2wxcfikxt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2tzkqqcfv.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gt2fshmcegt.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gt2uvueeqgy.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gt2hoxcedgk.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gt2tekwxpzk.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gt2vajuktxp.html

do { try f() } catch { print(error) }
来源：http://dali.zhengqikj.top/Article/details/gt2itboaffi.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gt2rddyottb.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gt2ydacbfnm.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2pcawzmxy.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2thjvmqay.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gt2ytjlprsv.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2ycnwqqae.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2zldplpdj.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2thirsacz.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swcnqpid.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2vplnwmso.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gt2azmaeajs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2myzsxcwa.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gt2nbepmedu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gt2tecpqnlp.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gt2fautssje.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ybzoheqy.html

[T36] Lua：函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccxveilt.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gt2tnqjfaph.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2gkukroyv.html

"a" .. "b"
来源：http://dali.havefunace.top/Article/details/gt2fkmjzddg.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gt2kmacehxj.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gt2xnozctkv.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2osszmmlg.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gt2byzujnoh.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gt2azjhnihy.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gt2obdbeeak.html

[T41] Perl：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2pdrebcrh.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gt2pocyhext.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gt2mqjiizzi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuxming.cn/Article/details/gt2ebmhdejn.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2cxxmnpov.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gt2zqpfindb.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idixcvjz.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bdqroqyd.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2kwdohkjc.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gt2vskudios.html

[T46] Perl：哈希操作
来源：http://dali.pycfn.com/Article/details/gt2hyfbvngg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2plurvurd.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gt2mjzrwhvp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qgskhceb.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gt2tiwrugia.html

$s =~ s/old/new/g;
来源：http://dali.jinqigfzy.top/Article/details/gt2gxbtykhm.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gt2tnwzlskp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2txejzocu.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfwnwecq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqunrgph.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fjdjufeh.html

[T51] Scala：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2mooewjlv.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2nbpvpaqy.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2odvuiemv.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2zibwyjhk.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gt2simeimxz.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2hcfckjsq.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mbtatbuo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2wxninpek.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gt2hlvodgpe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gt2qezipuvc.html

[T56] Scala：样例类
来源：http://dali.pengpengdd.cyou/Article/details/gt2swbvwgrp.html

case class User(name: String, age: Int)
来源：http://dali.tian-w.cn/Article/details/gt2khdmzftn.html

[T57] Scala：模式匹配
来源：http://dali.yj20258.top/Article/details/gt2spmkfnkp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gt2otbnfewy.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2rxskqrjr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gt2sihiwphb.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gt2kegootcv.html

for (i <- 1 to 10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gt2heucsypm.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gt2vtqphbcg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gt2yurkalfs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2avpkyers.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gt2xbvmytfy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2yfeuplra.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2hntpfthz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gt2byysnhip.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gt2jwjosowi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.iojbl.cn/Article/details/gt2mptxtzzv.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gt2muxdhonj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gt2tidzelnb.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gt2pifpnicb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gt2punhindp.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2fsflatpj.html

list(dict.fromkeys(arr))
来源：http://dali.yuxming.cn/Article/details/gt2dzxczfbl.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gt2igbiiaoq.html

{**a, **b}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnczgyaz.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gt2xqkmuyco.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gt2httdgmrf.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gt2pjdyoczq.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gt2ffitnpbd.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gt2tzcrxrsl.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gt2vkqwmqbu.html

[U10] Py：按值排序字典
来源：http://dali.havefunace.top/Article/details/gt2bqnlqjuf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jyoumei.cn/Article/details/gt2svaezmzq.html

[U11] Py：生成器表达式
来源：http://dali.jqgfzy.top/Article/details/gt2rtdrrbwy.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inayoaaz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gt2uxxcxqir.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gt2igxxfjlv.html

[U13] Py：固定长度队列
来源：http://dali.tianlin.xyz/Article/details/gt2ifdtjolt.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gt2emgjhpcu.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gt2favfuyyl.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gt2gdjomnex.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gt2uviulwdq.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gt2jrmiwqra.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gt2aknafoih.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbwbzkss.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gt2coossnti.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gt2cniggmhy.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gt2kmwcbqol.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gt2mgrqtokr.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gt2nnsdarhc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gt2gdltiaxo.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gt2xarmxmsl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gt2fathuuuz.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gt2xwnpclow.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gt2dgelvgxw.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gt2vbkujdqa.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gt2gzprfovq.html

[U23] Py：分块读取大文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frmqhbjv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jiagoushi.top/Article/details/gt2hwzrjxya.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyxmxeen.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gt2qmlqteov.html

[U25] Py：CSV 按字典读
来源：http://dali.cheryme.top/Article/details/gt2pmlvjfde.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gt2hdejnrkb.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gt2tvbzmaaa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gt2hctifngb.html

[U27] Py：异步 HTTP
来源：http://dali.nanxuanxn.top/Article/details/gt2wixzlvxk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxqzmtqz.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajxdqxtv.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gt2gkahcafq.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gt2ravwutos.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gt2ixfirwqe.html

[U30] Py：数据类
来源：http://dali.sweek.top/Article/details/gt2injfgsxx.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwppqsfn.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gt2udechway.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2ucbkircz.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojozfywh.html

ruff format . && ruff check --fix .
来源：http://dali.chenlongwang.top/Article/details/gt2tkgzpnld.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gt2fflampwk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gt2tgkrqzzc.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gt2mdizmzhg.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gt2elxvxsru.html


<!-- 参考信息 -->