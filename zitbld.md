代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2soufbwhb.html

[S08] C：动态内存分配与释放
来源：http://dali.hfpthk.cn/Article/details/gt2keeobvqc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gt2gwmfxfec.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gt2rhyxtiop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcudhhcv.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gt2jqhimqgx.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gt2tgggkids.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2lqcbybsa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2qtldhjtq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gt2ktxrknhh.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2doozundo.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gt2ysmjjnmp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2pvxzlyde.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gt2bjytksdd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gt2blmslvmp.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2slwdmxtd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gt2cfptuthu.html

[S15] C：类型转换
来源：http://dali.yongpay.top/Article/details/gt2ierjigll.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gt2awurrtvc.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gt2qeulifui.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gt2fmqqnbse.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gt2uygwbvtx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzlzlmgc.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gt2yluvfgpn.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2daojjbut.html

[S19] C：快速排序
来源：http://dali.hnqzz.top/Article/details/gt2xwapkeii.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2hwaujmoi.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gt2xkgwkong.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2zyrbsnah.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gt2jrroxgob.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gt2hqvncmbf.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gt2ggivvfdl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gt2tnbldzhq.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xboislxw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygemhdel.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2ktbbnvxl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gt2yjrloggd.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2juekzilk.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxnbgenh.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zmhxlkya.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gt2tvgsunfm.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gt2cikwtwax.html

const double PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2ragpejsr.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qyiubxyr.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gt2brdswjwk.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gt2jgmafzub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nherkmzr.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gt2mkozqajn.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gt2vfxrxout.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2gmvnucpw.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhlgltbo.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2zpxvisjg.html

#include <iostream>
来源：http://dali.hysaishi.cn/Article/details/gt2dgoytiym.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gt2cistnszx.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gt2ouomvedb.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gt2crkbwqud.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsecqmxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xziqi.cn/Article/details/gt2shazpvyc.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gt2wxqighdc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2ekopwfrm.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2ydmbgmex.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2nsntcvde.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gt2kztcfxld.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2evhthwzi.html

[S37] C++：set
来源：http://dali.hysaishi.cn/Article/details/gt2japttvhm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cdnleiting.top/Article/details/gt2pxxelkxn.html

[S38] C++：排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2afaacvot.html

std::sort(v.begin(), v.end());
来源：http://dali.yuxming.cn/Article/details/gt2vozicttf.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbbpcoqe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gt2vnoghggf.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gt2anbmeshv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gt2vahicelq.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gt2vdqgqlai.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gt2wegzhfov.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gt2zacyyuvg.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gt2ewifublz.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gt2iynauzzm.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gt2uhaitamw.html

[S44] C++：引用传参
来源：http://dali.cdnleiting.top/Article/details/gt2gbeucaoi.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2rowwhzky.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynvekydf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2krlcxnbs.html

[S46] C++：函数模板
来源：http://dali.aibaodan.cn/Article/details/gt2bmcwahwa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2mdgceirl.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gt2wiwvoxpn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gt2sqveixkz.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryuwmctc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gt2dordcmhq.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2wfdyqpzh.html

[S49] C++：写文件
来源：http://dali.yj202588.top/Article/details/gt2ehoebnyz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gt2ccjrelxn.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gt2bvmdrgoy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2rirpnzhq.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2cyvgjqcv.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2nyrgnhvg.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gt2dkiuekzv.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gt2mgmpjynl.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gt2lqangbcr.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gt2roimnkpy.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gt2yyaemnco.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2teqzdzli.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gt2nczcuvoq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gt2bnudfozt.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gt2imtahcps.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sirvdrbj.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gt2pnblyimx.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekwezvoj.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2toazozef.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ziixhywq.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gt2mthzdmxs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2cmcbsiqh.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gt2akvxdegi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2kbtheelz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2vfvgrmpa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gt2itakbrfc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2afquavxr.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gt2ieqvmysv.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2pfhicaah.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gt2ysaqzpmp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gt2rnzcjfrz.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2wfionemg.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2nkxctsqr.html

[T04] Kotlin：空安全
来源：http://dali.jinqigfzy.top/Article/details/gt2fducevmn.html

val n: String? = null;  n?.length
来源：http://dali.havefunace.top/Article/details/gt2gvmnenqw.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gt2lzzvyhla.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omfkmcxa.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gt2xthiwibq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mderurnl.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gt2pznsuvrl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.redwolf501.top/Article/details/gt2ecrrjfpu.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gt2hlonoekb.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2fevvdiwj.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gt2vvlguexo.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qniryeyy.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gt2youafspr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2zfvjsshk.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gt2otybcyto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gt2xzsxrqdp.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2sydkvovs.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2rlmsclop.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gt2wzstbtzo.html

val m = mapOf("a" to 1)
来源：http://dali.cashguo.top/Article/details/gt2gvqofrij.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2kghdwgbe.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2uifqesve.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gt2rmhphtlm.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgqerbxw.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2atwziwze.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2nrqtetkp.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gt2jigjekqi.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2nzpdvnph.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2ozschhho.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gt2plhptldf.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gt2mbirlgod.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2thkrdeuh.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewcumrdw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.havefunace.top/Article/details/gt2xljqmnnb.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gt2xfkffgbu.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2edigsrjo.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gt2yqlttuql.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2hgtsunqm.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gt2ixwgpuba.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ehwqpu.com/Article/details/gt2polkbgzq.html

[T24] Swift：闭包
来源：http://dali.zhengqikj.top/Article/details/gt2nmtgaioi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rupxumrb.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gt2fshvfoij.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gt2kzytabnt.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gt2eaounisg.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gt2fikysuzj.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gt2hyyfbaev.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gt2gcvjsltc.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gt2rhvnzmit.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2txifmhak.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2nhnucapx.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gt2trhebpwz.html

[T30] Swift：协议
来源：http://dali.yuanzhike.top/Article/details/gt2xheuoxjd.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gt2icrmffps.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2dffgekji.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2gcvapahj.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2qtblzcry.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gt2kpmrxjcw.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gt2ylrhjyyl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gt2gnpyyoko.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2ayzzuixd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gt2tqxamapr.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gt2qiulzhrm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2ejecvxof.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvxfedtd.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2hivxiruz.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2xeddxunb.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2wqjvwhgu.html

[T38] Lua：条件
来源：http://dali.jqgfzy.top/Article/details/gt2acobovur.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gt2iuuxsfvy.html

[T39] Lua：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gt2udzlemsf.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2uumjnkrv.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gt2llrebgwg.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gt2bodgvrom.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gt2vsawypxa.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2tbophygd.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gt2tdoqnezd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gt2esosenqh.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gt2ynfgcbaw.html

"值: $a"
来源：http://dali.daria6918.cn/Article/details/gt2chpzdupv.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdbupzcu.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gt2wtbuliym.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaytfqdu.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gt2qtkhtocn.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gt2npilyrth.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zrpxsscg.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gt2bfukrgoo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ffizbxlr.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gt2eccfsvry.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gt2rgiqnfdj.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gt2cjtbaouv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvfvimvb.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2nlnvwlbo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gt2vsrpobng.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dianchejie.cn/Article/details/gt2pmvvhxik.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gt2edahgryb.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2ijcgjgue.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gt2iooypgfc.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gt2trvbvyvz.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2vuehrebr.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gt2keitnsjk.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2gbzaebnx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2xchhhibi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnqkbcl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fykanglr.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gt2zswyecku.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeodhxvx.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2egadhjii.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2nhscwlnf.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gt2qzxiuyjg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gt2akrccjka.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2meomnzhz.html

for (i <- 1 to 10) println(i)
来源：http://dali.cheryme.top/Article/details/gt2gvdemlbs.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2bsvujtgj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gt2cmccoebz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kbguulva.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gt2kjtzxmck.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2afvybibi.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gt2yuicvlpr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gt2kcvgbxzi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gt2daxnqevf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gt2fzovydns.html

[U03] Py：加载 .env 配置
来源：http://dali.sufxvd.cn/Article/details/gt2zynzjlnx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gt2mfksawsr.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gt2xtxzdjdg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gt2mkijcyjh.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gt2zqziktqa.html

list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2mstfjeeu.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gt2nnmxsewn.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gt2nxjsgfym.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gt2qtbjntru.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gt2alyxrrin.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gt2jcczknha.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gt2ecqqxljn.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gt2hbgfikps.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gt2vqsksyoo.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gt2wnebeymm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gt2nqlggfii.html

[U11] Py：生成器表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjnfnnsk.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gt2teddjpjo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gt2cyjzkpdw.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gt2ioiailqi.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gt2gsvyxcla.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xrtjlmde.html

[U14] Py：分组收集到列表
来源：http://dali.bjfxy.top/Article/details/gt2jwlyqmlt.html

defaultdict(list)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qobeutwr.html

[U15] Py：高精度计时
来源：http://dali.cheryme.top/Article/details/gt2kglunuuz.html

t = time.perf_counter()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqypvakt.html

[U16] Py：命令行参数解析
来源：http://dali.sysykeji.top/Article/details/gt2kimnaknn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvzjtpcl.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gt2ocyxrgde.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gt2hkokyguh.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gt2impjumvd.html

pat = re.compile(r"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2vvrcwjmz.html

[U19] Py：正则替换带回调
来源：http://dali.ydzc1.top/Article/details/gt2kudnvbsi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gt2mvzijgdw.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gt2ecnosfhu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gt2zxybokak.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gt2pyimtdmb.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkpsbutz.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2crkldsfe.html

list(zip(*m))
来源：http://dali.cdnleiting.top/Article/details/gt2lbtlccyb.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gt2pkcqcuoz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzqmwyql.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gt2uvdgkfyh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2vgxetibm.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gt2janwiemc.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gt2ximfsugh.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gt2crqdemuv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gt2uewsdhrl.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gt2mpmzofzi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gt2vzofhrnz.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gt2cnythmiw.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gt2tfcqwcah.html

[U29] Py：属性校验
来源：http://dali.yj20258.top/Article/details/gt2arrzktiy.html

@property 与 @x.setter 配合
来源：http://dali.gzhubu.top/Article/details/gt2bbpmcpyd.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2hhesjssz.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjniydrv.html


<!-- 参考信息 -->