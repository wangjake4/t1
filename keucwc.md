代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cheryme.top/Article/details/gtgkmaesra.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtdhtsnoyv.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmtrbkze.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtoemiojit.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtubgopgdh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtxrizngnr.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtkveiittu.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtykbaammq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypvopdua.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtxfpibdkt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.birdmap.top/Article/details/gtqhjefewn.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gtscesuflq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gthvsglwnz.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtpbgxroac.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtcmyipxgu.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gttkpdcakc.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtohacpctw.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gttuquhubi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtzqpewjri.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtfzmexxzd.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gtqagetypf.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtjyhnzgky.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtotzjdtxd.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtdyypgfad.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtgjxgqzsd.html

[S21] C：字符类别判断
来源：http://dali.ehwqpu.com/Article/details/gtlazuzwgc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gtgjotfjck.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gtpiuiwsdw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsigdvab.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtungarlnb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtllghctob.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtijlcxrme.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtuccintrk.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvsexfru.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtbywoztun.html

[S26] C：内存清零
来源：http://dali.jinqigufen.top/Article/details/gttozjvtsj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gtanrwjaxk.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtletaisqx.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtdilceeme.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtfnodtyzo.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtdhzpokxr.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gtzozkqkdt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtftomgmyc.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtycswvnkl.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gttsdyltmf.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtranuokej.html

#endif
来源：http://dali.zhixingplan.top/Article/details/gtrrusdwux.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtkgtngktb.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gtbovvizhe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxinkj.top/Article/details/gtjbqrhvmu.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gtmpdwlccz.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtxvldprxq.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gtszywoxod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ybcxt.top/Article/details/gtjjykdoga.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gteplurelq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtvgbfoqil.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gttdowyuve.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtufzmyrsi.html

[S36] C++：unordered_map
来源：http://dali.yvedp.cn/Article/details/gtfuvzplcf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtytimeyih.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtqweallac.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtfybuegcm.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtgjzxbbcy.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtjwohgcaz.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtsjkyoxmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtcvpqxzla.html

[S40] C++：查找元素
来源：http://dali.sysykeji.top/Article/details/gtnefniacr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yonumen.top/Article/details/gtncpkdxxo.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gtkuvxzjdn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fengsongda.top/Article/details/gtevcqusok.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtywpltaht.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtbryopjiw.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtbncpucxr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivezfcoy.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtjrvyabtu.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtunxwasnf.html

[S45] C++：lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwtoxfvk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangshuangyany.cn/Article/details/gthwlssjsr.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtljlzimkr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daria6918.cn/Article/details/gtungdskhh.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gttwpbtflg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yangfankeji.com/Article/details/gtrzwkdgmk.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtpboxkbvb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtlxrlvrjt.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwvysnja.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtdfrpkrww.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtsymcndhn.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gthbbztiaf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gttdzxgbdh.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtpygfxsbx.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtveusnjrt.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtdeqjyjoz.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtbpgxhxsb.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzysvbzx.html

std::vector<int> w = std::move(v);
来源：http://dali.wangshuangyany.cn/Article/details/gthkjssdce.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtwacithbm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gteiyfewro.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtzxufomfb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxinkj.top/Article/details/gtfbjepnbn.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gtmbkfnkrt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cqqwz.cn/Article/details/gtmzsnwxvb.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtrvlmymls.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtywdlbcdo.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gthephwbgm.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtnupznpxq.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtawesxreh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtylylkvcq.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtvymogqat.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtjydmkfab.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgtfwqxwj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtgbszbnjq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtpcywtdmo.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtbmuwdkjc.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtgbwdcoca.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gtbdepiyyo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtfgjbmkfk.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtlgyzcxbh.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtebrfapup.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtvudtacxt.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gtfsuwehwx.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtlacnwcsi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gtfhhxmsxs.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtgqsmcqkn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtwsxquwxa.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtmnsllwwd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gtjqcbqufj.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtpsbcrqrb.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtkljzmbmu.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtvtbaocvh.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtmpqxjmwo.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtvuolmmtl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gttpuakhsz.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkdmknxp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuanzhike.top/Article/details/gtvaiaqxjg.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtergrfuxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrhkfkef.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gtztgonyyh.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtpdhfncuj.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtpkqilnzf.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtznwfztaj.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtymnorfpd.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gthcemcnkq.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtwohwmwdn.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtnuhglhla.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gtstsvzhjn.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtoliaqnfx.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtgmqrzouk.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtgwpiujui.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtfwahopup.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gteipfhqgw.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gthdcvqvjr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aizwys.cn/Article/details/gtntrrcyil.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gtdygeceaz.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtmgyhgxmj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gtltjvfoaa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtsfnkpdyc.html

[T23] Swift：函数
来源：http://dali.shuidangran.top/Article/details/gtfnoqxwev.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtfgxxgpyq.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gtuhefdtrj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gtjvraukhd.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtkcmojyng.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtbswnfavf.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gttbgkwxki.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtkosllmpq.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtuumzbimv.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtmfnztnaf.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtopjcwiqi.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtssttwnen.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtksqndtxz.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtvsfmkrxs.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gttkywvfyv.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtrtrdhndj.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrduynhkn.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtohfzxlfq.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtyajjhxsy.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtgrynncyu.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gtytsgsfev.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtorsodvau.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtutexumvg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtjzjypgfl.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gtwbtmqpyy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gthjjxypuj.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthdrzfbel.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtebahoemx.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtvksvnqvd.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtrwmkdywe.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtxmgwuoaa.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtunlxdtec.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtrjsjzncm.html

string.find(s, "%d+")
来源：http://dali.ppjwa.cn/Article/details/gtzzmbrqqa.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtlkeowxgw.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gtfyfedwhx.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtjixyylqu.html

print "Hello\n";
来源：http://dali.bjfxy.top/Article/details/gtsmsdoimr.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gtouncusby.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gtlavfjynx.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtyngloeaf.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtgqyxdjsd.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtlabqxrrp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtddlodnjf.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gtrehtognw.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtcnmypzqs.html

[T46] Perl：哈希操作
来源：http://dali.wangshuangyany.cn/Article/details/gteuvrcgwe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtvmhghobp.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtfstgtfmh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hywenlv.cn/Article/details/gtwsrvkjsz.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtwonfpbkb.html

$s =~ s/old/new/g;
来源：http://dali.chenlongwang.top/Article/details/gttlkjzwbh.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtvyiuagdy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodzhobag.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtlhmcuzqo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtbccjawbc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxupcoiar.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtpyrprhry.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtrqfiutas.html

[T52] Scala：变量
来源：http://dali.sufxvd.cn/Article/details/gttgijhsra.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtmztbxlmn.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gttcrjnthl.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gthogidqjr.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtdanamsox.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gtckhbkjqf.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtxmoxaaia.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtritjixcp.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gtmwmqpnbp.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtfyzxsmvs.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtvltdsvmi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtrbhlxlzn.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtxzhwlzzj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtojzpfvnx.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtmzzvqyvo.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtzpkzomcf.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsngwbht.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtzuxpjfof.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtvfirumpi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtwipjvfsk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttewrqdko.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gthmoednrk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gtyhkezvnz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gtaeszxmvv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtuqqowsqy.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtwhqcnzia.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtyivkzbdy.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtuerqbdly.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtxmatmwpv.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gtgjlbuizb.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtrihxcllu.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtiwgxdxod.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtmchkdvat.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gtneftdkge.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gtyqlqujxj.html

[U08] Py：展平二维列表
来源：http://dali.pycfn.com/Article/details/gtxrdkoeno.html

[y for x in nested for y in x]
来源：http://dali.nanxuanxn.top/Article/details/gtzfddjxbu.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazhbwkti.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gtgdhmcwlx.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gtgbygwgps.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtgcnqczfo.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtxurlryty.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtpzwwtcus.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtdlaxecrp.html

Counter(arr).most_common(3)
来源：http://dali.yueranfly.top/Article/details/gtvtkcanop.html

[U13] Py：固定长度队列
来源：http://dali.hywenlv.cn/Article/details/gtqdotejsi.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthoolpnrr.html

[U14] Py：分组收集到列表
来源：http://dali.iojbl.cn/Article/details/gtsrbxmzqn.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtjguqwmgv.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gtcsagfzxr.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtffvockho.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtyyvxfbsl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtfetmyjhf.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtbkbnztbq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtnfgrnzfe.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtqecdwrfh.html

pat = re.compile(r"\d+")
来源：http://dali.jianghu66.top/Article/details/gtrbsvcxrk.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigufen.top/Article/details/gtxrsswosj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtfwaaqrqy.html

[U20] Py：缓存函数结果
来源：http://dali.xinyue.icu/Article/details/gteiiobavm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtkrvheemh.html

[U21] Py：自定义上下文管理器
来源：http://dali.hammf.cn/Article/details/gtmwayskfq.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhccysnc.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gttuirhoqj.html

list(zip(*m))
来源：http://dali.cucudq.cn/Article/details/gtzdvsuchh.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gtmuyekhpg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.guowangkeji.top/Article/details/gtwgtmjibl.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtjnofxpfm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtmzaoffzl.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtywrqxyhg.html

csv.DictReader(f)
来源：http://dali.gzhubu.top/Article/details/gtnpmaunyx.html

[U26] Py：并发下载
来源：http://dali.jlsjyb.cn/Article/details/gtabkrgfas.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnidjxjfi.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gtjbuxulrw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gtfvjtkvqt.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtrbbitjbj.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtgthxmdsv.html

[U29] Py：属性校验
来源：http://dali.sxryk.cn/Article/details/gtfrepifja.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gtpbcysgsj.html

[U30] Py：数据类
来源：http://dali.chenzaomai.com/Article/details/gtvdesucvm.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtlvlfhlnm.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gthohasuuz.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gtyggbfixw.html

[U32] Py：代码格式化
来源：http://dali.pycfn.com/Article/details/gttoqvqnfu.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtlqnaympt.html


<!-- 参考信息 -->