代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmehlnju.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtwlyiibws.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtnbxcubdp.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtqeqybmfp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtglmxeoii.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gtruzrvwzq.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtyrpwuhvg.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtifxaamlu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gtjesnblrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jiagoushi.top/Article/details/gtocknxmic.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtmiimwflj.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtghghyjej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtqkwyfeax.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gtpmxajusm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtgdsljyhv.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gttzumhofk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtbwvfyjsb.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtmbcfwdbj.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtzuecsceu.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtlbytttsa.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtdxnaifwc.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gthjvyysyw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtwqbmigfa.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtbnnbkcbz.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtkvkaaiqf.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gtuarjelvk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtegxdjmkg.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gtvtnmpebn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtidxcsvdt.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtceyygxvl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtygaqrlgm.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gthkoficiu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtpvndfxek.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtfsyzpidl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtqvddkisq.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtjauwrqqt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkxjgywh.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gthtsyesob.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtzhkenitg.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtvszbluwm.html

memset(a, 0, sizeof a);
来源：http://dali.sweek.top/Article/details/gtwrqcnfxq.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gtnrxjbgpd.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnfnnklfz.html

[S28] C：静态变量
来源：http://dali.gogol.net.cn/Article/details/gtkqbtbgkh.html

static int counter = 0;
来源：http://dali.tanke756.top/Article/details/gtjommawoq.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtryqbuzcd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xziqi.cn/Article/details/gtafrnfzhx.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gtpnrdkgjg.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtvylinxze.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtaqppzwih.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtvewrauiu.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtxubqwhlm.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtnomkcaqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtplmcpcmz.html

[S32] C++：字符串
来源：http://dali.yvedp.cn/Article/details/gtkpudyype.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gttoassdjt.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gthaydmyya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuiooaptl.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gttaodqqxo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtkaxprzpj.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtjufajmyi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtxgklctgq.html

[S36] C++：unordered_map
来源：http://dali.xylfe.cn/Article/details/gtytgspaxs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtkizgzaee.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtwwqluvzp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtjvyciywq.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gtaxizimke.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtzaetycqz.html

[S39] C++：自定义比较器排序
来源：http://dali.iojbl.cn/Article/details/gtevupredx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtqiwwncss.html

[S40] C++：查找元素
来源：http://dali.ehwqpu.com/Article/details/gtfhkxmnnn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigufen.top/Article/details/gtxhlyossr.html

[S41] C++：类与构造函数
来源：http://dali.birdmap.top/Article/details/gtwlzihnqn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtcgykwymz.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtyjzirqyk.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtzxdpfncy.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gtssfnewsd.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtiwopmgyz.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtvsgjnqar.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gthixzjmys.html

[S45] C++：lambda
来源：http://dali.jqgfzy.top/Article/details/gtcdsjeqbz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfxdlbjm.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtdclyiyns.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtzccffebe.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtyposppnb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtttakajeq.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gtkhcwndcq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhiwuduotai.top/Article/details/gtywjemvug.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtjsvrbciu.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtdboarwqr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.9152youxi.cn/Article/details/gtygbvubdi.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gticuyahzb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtplfjoibl.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtykdcnjli.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gthbtnccbl.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtwjbsatzo.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtxxzqulxh.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtkfwuoqwm.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtjkdbdhgr.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtvjadcvfh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtxqasikhg.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtndbelusl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtpvodamvh.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtsawywxlw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtztokxdrt.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtgdgdusam.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtmhebmycb.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtddgyiewp.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gtdgiraevl.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtzhuhnhdo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gturofgjrr.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtshumjlaf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtjrgrznic.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjaupjozt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtlunvbzmw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqjdfnuvd.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtzyykxrwp.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdpyciqd.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtqyjkewyj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gtcbhodjrs.html

[T03] Kotlin：字符串模板
来源：http://dali.iojbl.cn/Article/details/gtidtujymq.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtwntqcdus.html

[T04] Kotlin：空安全
来源：http://dali.fengsongda.top/Article/details/gtiizdwpex.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtfqgjbrlj.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtlccycqja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtryqeuyng.html

[T06] Kotlin：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtzzqfsqbk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtkyqcomto.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtxgcnakod.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtdqzafbwv.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtnoiugrbi.html

data class User(val name: String, val age: Int)
来源：http://dali.hammf.cn/Article/details/gtqjcjyboj.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtcvrjnlrx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gtpwinthuv.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtysvsmqvr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtnneblbid.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtyjzralew.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtmgargpue.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtdvldpvke.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtblqnecuf.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtgwifhwjr.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtcpfwkrhu.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gtljolsads.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtfblynxrp.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gtqwnzkuid.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtrznzlsmn.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtjysnosbj.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtlfxevkzi.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtjpmshopi.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtyqsgmubk.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtnanddgfu.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtxkklptsf.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtunjkonfw.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtmwdqdkvs.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtktyssmit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtboyrjdsm.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtoywyywiu.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gtqkhhwdux.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqhcxpzk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtibjliuli.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtexjtaxsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gtxbjgxgdr.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtpxndbayc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtkxeadnxc.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gtxagcpcve.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gttatzamuq.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gtirixingb.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gtdhuprhyn.html

[T27] Swift：错误处理
来源：http://dali.yvedp.cn/Article/details/gtpmbdhgao.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtbnnfkzjt.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gtfetxhhfz.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gtarnscwrm.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugvqblxx.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtldfcuuej.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gteaztnsig.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxjjketd.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtizzfnaya.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtndeabesn.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gtdsaagobz.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtaalolhoj.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gtqxzrskho.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gttzpntbxx.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtdaypxdzx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtsiijpuqx.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gtwjxllfco.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gtblcvkgiq.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gtuisddkhc.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtzzuesrtu.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtnbjyvyed.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtrzmulysp.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtimalwktq.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtkiheouzm.html

[T39] Lua：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtsjcnpqgw.html

string.find(s, "%d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydmfytpw.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gtmevtekog.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gtlufvhpet.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtgljbvmlv.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakzuwnuu.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtavvggqcd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtmofysmtw.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtuxzxfvtm.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtrxoihvzj.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtlztprgjr.html

if ($a > 0) { print "正"; }
来源：http://dali.hysaishi.cn/Article/details/gtcugysfsn.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtentsqfgc.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gtzjpudifd.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtipycrykz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhengqikj.top/Article/details/gtmnjketjg.html

[T47] Perl：正则捕获
来源：http://dali.pengpengdd.cyou/Article/details/gtsbojbofi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gthppsxmwy.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtdexmfdom.html

$s =~ s/old/new/g;
来源：http://dali.pengpengdd.cyou/Article/details/gtwilazqnm.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtlkmermsx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtafytrpul.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtyckduqlr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtckybfykp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtazjjqttk.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtkoaqfeul.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclxlidpe.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwlrvyro.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gtrnzxkziy.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtktfjkixw.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtxlbylzhn.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gthuceporj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtykjwhpum.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtkkwzcxsw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gthlrknxho.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtdocgbsgj.html

case class User(name: String, age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtpplsmsxb.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtccoikage.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gtgkmfviea.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtvntxhmxj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtahgnctdo.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtiittxmxe.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gttjkjmtob.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtbarkzizn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gtbdxzzdsg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtvdghmjot.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtvxylqlfg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwevjatxa.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtkjethbld.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtzsidcovq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gtdlkpzjcj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gtwxwzsaha.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtswrdvdrg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtavaqikie.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gtjtohgjfp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtparlimlo.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gtpzxtuzbm.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxjpnirv.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gtjgshesgv.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gtqsfbhkzz.html

[U07] Py：反转字典键值
来源：http://dali.gzhubu.top/Article/details/gtvwruufhj.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gtfwraxquy.html

[U08] Py：展平二维列表
来源：http://dali.vqdsnc.cn/Article/details/gtlghwciil.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtlugghebt.html

[U09] Py：字典取最大值的键
来源：http://dali.gotoacloud.top/Article/details/gthjwjqerd.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gtavpbloxs.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcjhoklc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtvukgbuxv.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gthgffcfgv.html

(x * 2 for x in arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkitpeav.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtswprrdit.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gtqafcpbqa.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtavvtmkra.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtqqoradvz.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gtrqkjbjot.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtnutygafq.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtgklttvho.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gthasdcxcw.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gtlgqmsjeh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtydawcldn.html

[U17] Py：初始化日志
来源：http://dali.gogol.net.cn/Article/details/gtelmuidwe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtrozrjjqi.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtdqhuitnl.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtdalpokyl.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtzffziwyp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpklgnlw.html

[U20] Py：缓存函数结果
来源：http://dali.hnxiangtu.top/Article/details/gtiqbjkgzh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtfcvwwgvx.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gtbhpjfwns.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtpoxwethe.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gtobdvenup.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtdxpkabof.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttkfbhzgl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hnxiangtu.top/Article/details/gtcgidrpwa.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gtkfxhhgrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtffltuvat.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gtyqnwjrvd.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtxiinkxpk.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gtyoxyqeey.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gttfypewdj.html

[U27] Py：异步 HTTP
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpultinr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gtedmdlwxv.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtofiiamzn.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gtiuzykesr.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtyzxbitiz.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjiwmvzyo.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgwchhrw.html

@dataclass(slots=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqswnqtvy.html


<!-- 参考信息 -->