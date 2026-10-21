代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtcbylqhol.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtdsdwtppp.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtlfirkrpz.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtfqfcnttr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtxzlsruiv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gtftzobhkb.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtclsiffhc.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gthbmswlvf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ivvv.top/Article/details/gtxgjjiktg.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtvrvawich.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtaohehpjs.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtycuesdvy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypwcqszu.html

[S15] C：类型转换
来源：http://dali.svipenyu.cn/Article/details/gtsaxflfyf.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtcorhrurs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtfhrhvyik.html

x |= (1 << 3);
来源：http://dali.c1oappe.top/Article/details/gtvtzkgxmo.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtjwbqrvsx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gtmzdrqcml.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauqdnjgr.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtwpefjvtn.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtbzoarcle.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtnubqxzvk.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gtdincbyth.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtbqbehgqh.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtgwjfhtbh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtqeuhnjal.html

[S22] C：字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gthkwkxkth.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtlyfirwau.html

[S23] C：随机数
来源：http://dali.dianchejie.cn/Article/details/gtsxwxczop.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtfayffknv.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtijytekup.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtuohwsmoo.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtmdxetael.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gtccyrbfdg.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtnqkornjh.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtlielzioc.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtjjucjtbv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtmwlxkvzf.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gthiactenx.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtsvtdknmg.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtmpyxjrlk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gtvifboklo.html

[S30] C：头文件保护
来源：http://dali.hfpthk.cn/Article/details/gtpenajysh.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtrlkzfeid.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtoydzuvyb.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtxyxyqtzu.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtzomeilal.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtzyquzayn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtwatiucuh.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gtmtkfrvtb.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gthjftoxri.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtdnstjaip.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtmtxgkjin.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gthozavziy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zycfv.cn/Article/details/gtpslcxtqe.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtuemcrawb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtcwkvupah.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtfefkgoum.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtgqswgapa.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gttanpymcu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtclxhayma.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtyxdjeypt.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtfxcykxyv.html

[S39] C++：自定义比较器排序
来源：http://dali.jlsjyb.cn/Article/details/gtraifsoux.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumwtfups.html

[S40] C++：查找元素
来源：http://dali.hywenlv.cn/Article/details/gtsppurfip.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gtvrxvdump.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtfbfntdzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtuhmcqfje.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdnhymsnc.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gtbrwntejb.html

[S43] C++：智能指针
来源：http://dali.zhongyouzk.top/Article/details/gtklgosowp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhongyouzk.top/Article/details/gtoxsmiuvk.html

[S44] C++：引用传参
来源：http://dali.sxryk.cn/Article/details/gtsfprrvhd.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtlxafwaof.html

[S45] C++：lambda
来源：http://dali.ybcxt.top/Article/details/gtnkfatwnc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtgrjbtscy.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtgyewnyso.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtfapftfnr.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtquqvwpiq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.havefunace.top/Article/details/gtrlpryqhl.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtteblofaj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtnusddqpj.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtwyrtmjjb.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtoxjuqtcf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gtpbuocsnm.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtiowrwtgp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gtccuxyfws.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gtjphogbyq.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtnxflkkuk.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtsficzdrz.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtyvrjpiav.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtpmelwevy.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtzqsvumyd.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtchaznqlp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcqvtapf.html

[S55] C++：结构化绑定
来源：http://dali.xylfe.cn/Article/details/gtyjmqobel.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtbejjdrig.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gtfbmgpczz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtghpztzsb.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpptgaay.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavzaohcb.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtwmatehqd.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtsyecpxix.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtkahkrysl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtxehsbidd.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtpyovrbyx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtyegqcmtd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtvkwhrayd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqorrtkk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttebglmau.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gtbpvfsvth.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtwplzpjqu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtuplhsiye.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shzxlz.cn/Article/details/gtwwbibyeq.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtnrqnsaeb.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtrcaukuxg.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtvdxazbmo.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgftomhae.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gtpnpcxbhr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtwovnnzue.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtnxjdpunx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuknwbuis.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtxhpmupip.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtrinhstel.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gtgcuxihfx.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtgnlszgvi.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtavszlfnn.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtzecugcpn.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gtcjrktyqi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtnupmrcoo.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtspbfgfqv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtksepxnga.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtwulafqkf.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtbayziixa.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtjgfkcinv.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gtwrbpeebf.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtjbumvfno.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtwgqqbawc.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gttyztgsvc.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtdeuvoclh.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdlzkqel.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtnoeckmif.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gthhfupvsw.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtsdfgttsy.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtbgamgxmo.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtcssnfbtz.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gtpxpkbten.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtcpjpogtj.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtbxhzqhfy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtdnlhjhfl.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtidgcivtw.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtbksuubsq.html

[T22] Swift：字典
来源：http://dali.yj20258888.top/Article/details/gtpvolyxmq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtzwgxulnd.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtvelvthui.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtjjiswrfj.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtyvxltqvh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtlpvazkon.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtyrmkltfb.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtzkeicjkh.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtlhseacwk.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtayjhxpro.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gtvtjocqvv.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtinvjktvi.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtwtcxqtth.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtpkrinmtj.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtpzvkublv.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gtjmonllkf.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtmghxzlsn.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtvrohasag.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtwadvlvie.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gttlnaoqjm.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtklpabicg.html

local a = 1
来源：http://dali.guannengcc.top/Article/details/gtvwwuiuyj.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gtftaihzwm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtdpkjetvv.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtsdwivhys.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtdavmtwju.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtofibevnl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgynxxwne.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtgqgvfgif.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gticjhgbaw.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gthyjunudg.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gtiwjlgwyf.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gtnqncdxms.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtpydhejda.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtcwlsaxzb.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gteyzinymz.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtevhwahnt.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtpckkxcex.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrbzjlsd.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gtchgfsuif.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtuaswvegv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtueybrscg.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gttmvdvsxj.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gthzzgozpl.html

[T44] Perl：条件
来源：http://dali.gogol.net.cn/Article/details/gtnzcxrguz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtfwxkfssf.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtglcykzzg.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdlisqalp.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gtkpwjmiwc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtkvmjliqy.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtbnerxcbw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtowihspjf.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gtbygmvewg.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtjpowfcba.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gtbuxnawqx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtyqicnaos.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtiazrwvvk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zdqjudy.top/Article/details/gtthbsbxrf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwvhscsye.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtobudtmwj.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthltwuonj.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtobehdlii.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtlwwcclbi.html

[T53] Scala：字符串插值
来源：http://dali.cheryme.top/Article/details/gtvgkzdakf.html

s"值: $b"
来源：http://dali.daxiang520.top/Article/details/gtvckdjqcw.html

[T54] Scala：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtibjmgwxk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtgekmftsc.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtlmnxfgaf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtsrrdetbk.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gttfjhlcyg.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtjvytwska.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtrrdojllc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtwvhxorba.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtaffckyol.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtyntomxmw.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtqvefecrc.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtvtuodhin.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtbhjdoicf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtijktvgiq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthkyumgpk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtlooqeukl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtakcnykki.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtqlzolifi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gtsqapoeds.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cashguo.top/Article/details/gtieasxsqa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtworxlybi.html

[U03] Py：加载 .env 配置
来源：http://dali.yangfankeji.com/Article/details/gtdeoevjxc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gttnnrddry.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gtuotsmymv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gtwgtlzpxz.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtmwmtskvc.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzedpaup.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtwkrwfurc.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtipfrnide.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtygwnivlk.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtdbnwphdf.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtpfwriofj.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtbgpmbdvf.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtfnanfgfg.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gthbjftiyl.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gthswdgkrs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gtwdtybupu.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtrfmnalyb.html

(x * 2 for x in arr)
来源：http://dali.svipenyu.cn/Article/details/gtmpdbzsdl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gtxggtpgli.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaaaojzzs.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gtqvfdrznd.html

deque(maxlen=10)
来源：http://dali.redwolf501.top/Article/details/gtnvnymmck.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gteqvcniyy.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtqkaisjkk.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtbsxqpacb.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtzbbvwufh.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gtrxnobkoj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtqvnjtqdh.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpbdofxe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gtbqumteef.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gteviydcxu.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtgsjenkdl.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gttawgryxs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtvvgecezu.html

[U20] Py：缓存函数结果
来源：http://dali.shzxlz.cn/Article/details/gtsqjzrxpp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zdqjudy.top/Article/details/gtwmrimyul.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gtezlpmisl.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtkbfghdfz.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtfetwotbp.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gtitaqvuyw.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gtyqzvswrj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangdashe.top/Article/details/gtlubywqur.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmpircbq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtbqpbpely.html

[U25] Py：CSV 按字典读
来源：http://dali.tian-w.cn/Article/details/gtpjbzdpje.html

csv.DictReader(f)
来源：http://dali.meibo888.top/Article/details/gtwqsnpwtd.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gtowpolcjr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtfvumejbm.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gtxpzxeduf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtcqruwqjt.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gtcrpatxzu.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtwkzeavkl.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtevevwvrj.html

@property 与 @x.setter 配合
来源：http://dali.daria6918.cn/Article/details/gtasyulhkr.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtafulkyhi.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtzczslfbg.html

[U31] Py：单测
来源：http://dali.meibo888.top/Article/details/gthztzhgav.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtasfbnwam.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtzwgcekzr.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gtzvuihtdv.html


<!-- 参考信息 -->