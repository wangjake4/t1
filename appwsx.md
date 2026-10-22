代发 wailian999

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtateimyyo.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtwwuuxtcn.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtbiwjeojh.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtgdggabzr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtcawiotsw.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtgjshnoen.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtjzreodpb.html

[S09] C：结构体定义与初始化
来源：http://dali.fzhhl.top/Article/details/gtluivxyuh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtzbwkpoxb.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtzlncybcc.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtwgumbkjs.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtthyhqugs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gtumfpwndn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtaumvklfw.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtfvzuwyad.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtmjcuvafn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gttrqndhlw.html

[S13] C：宏定义
来源：http://dali.xylfe.cn/Article/details/gtbkkdxdxw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxuanxn.top/Article/details/gtslgyefkg.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtpmnqboaj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gtmefjnswq.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtqdpznqks.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtsncwwqpg.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gthmahzcym.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtocztkmsd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtytjaqnxt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtmobxxqoo.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtjogxgnok.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gttchilebr.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtomimiemz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtkzcbkrlg.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtjieoljsv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtjozxwoap.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gtvcbhhjag.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtpvobuwhu.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtksakxnkh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhongyouzk.top/Article/details/gtmqqmmpex.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtzskertlz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtgzfxiouw.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtcpwhkjbx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtfoxvnowa.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtweoznosv.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gtzyeltpai.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtoxqzzktt.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gteahpaqms.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtsoiwsnzp.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtchxyhibc.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtrhepdoim.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtzfwfqvfl.html

[S29] C：变参函数
来源：http://dali.yangfankeji.com/Article/details/gtcofmhfin.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtmkwgtzmc.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtdncryujv.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtjyoafpmk.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtthqiprlk.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtwrtqlkqy.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtdsdkabaa.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtgwrdzubg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtcmwwjzrg.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtcnkplnra.html

std::string s = "hi";  s += "!";
来源：http://dali.chenlongwang.top/Article/details/gtdjhppwpg.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtfqeabsrb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gttgffxuqe.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtcxfmwypo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gtuvjdxrrq.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtqrvbatbx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtoxqigclw.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gteickontu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbdxdqbu.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtylftxzgt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtewvvzxji.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtvcdxpdtc.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtjlizjpkp.html

[S39] C++：自定义比较器排序
来源：http://dali.ydzc1.top/Article/details/gtbkvrcyxa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtbnhgpyfs.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtwiwkpclt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtmqzqugpc.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtvyrnchzb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtqgquzzuq.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gtsscwgmfr.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtuhfzkabq.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtozxqroxa.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtiddpdees.html

[S44] C++：引用传参
来源：http://dali.tian-w.cn/Article/details/gtcbzohmjb.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtizrusaty.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtvqdsskkr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtrldbfwcz.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtffxneybw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtavmynwkq.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gteuarhiad.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtuqbdiyvy.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtofrsrjki.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sxryk.cn/Article/details/gtrjqvtamr.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtylzlpnyn.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtfjuadnvp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtpzdgqdlq.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtzxrqtswe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtfsymounx.html

[S51] C++：显式类型转换
来源：http://dali.yueranfly.top/Article/details/gtooddsfxs.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtgilonggt.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtegafxhiw.html

int size() const noexcept { return n_; }
来源：http://dali.ppjwa.cn/Article/details/gttbulifnn.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtpaerqwht.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevknttwl.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtuxiyaiee.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gtshnsgufd.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtngssqniy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtlfbzwuer.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtkvegcsjt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtfshftxne.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtzsirgins.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gthrpdvlut.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gtnmlmjgpa.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gttwjoctiu.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtwgxjbhvd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtdelybpkg.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtnaofhuuz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtwfgfqjrg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtsycjwcve.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtdaxarxss.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtepehznjw.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtqxovzwos.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtjugshhfc.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtyybxdybq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtxpcyifhr.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtjojhdbpl.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtclondekt.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtwgpeyndw.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzeicrmn.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gthsmqrcpf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtuxnzbvbl.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtyddrqzyq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtzcpgltev.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtublgcnik.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gtdyuohfuc.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtdbkcnldx.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gtdkbukfti.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtvwoxijgb.html

fun String.exclaim() = this + "!"
来源：http://dali.guowangkeji.top/Article/details/gtnomnhblv.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtadtpafzr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gtpajyhpgr.html

[T11] Kotlin：协程
来源：http://dali.jinqigufen.top/Article/details/gtlmzxhhhd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtcqlyhyfb.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtxdiprscm.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtepafhggl.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gtchilwgmb.html

val m = mapOf("a" to 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpqzgsgo.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gtsitzzyaf.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtkvmoobod.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gttxkglgrj.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtzsszyjyr.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtovffrstw.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtgynrnawg.html

[T17] Swift：变量与常量
来源：http://dali.hfpthk.cn/Article/details/gteppcjfmf.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtjdhikods.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtiggtkrcd.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gtmplqnxqk.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtnlvlksqh.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtzmyhqxhl.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtvnsohbzf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxdddjwj.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtgrmiqvzm.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtpayjztal.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gtvplpmsto.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtqghavnub.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtekduvder.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtolbwwooh.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtslssxghp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtuutvrepy.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gtkxqlpxqb.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtppilntft.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gtowdstumq.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtktdbqbgo.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgsqyyls.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gtgtvicmwm.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtjkzmptpe.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtqrcniovj.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtidwronqm.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtdujasebh.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtlqyauuke.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtwqsjykoc.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gtlrugplvy.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtdiwbyrru.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtchytaaee.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtysvzdbjy.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gtafmutixw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtnxfuwrzi.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gtjmmvpiha.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtntngeyrn.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gtsbzrwtsd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gttlbumyea.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtzmokqndd.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtbpeesltt.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtyasebmju.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtyortaiqy.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtqoykipue.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gtyumxmoyz.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtuakutiyr.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtavnmecan.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtebopwhhq.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtbmoclqgo.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtxkiinamg.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtfzpuhlyu.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gthvudjtmo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtdbyrptwy.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtiappadgn.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtfvnimvjj.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtnhbqekgw.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtooiisxaa.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtuzgfbclr.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtjxllxwic.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtguwdihap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gtkopsvrkz.html

[T47] Perl：正则捕获
来源：http://dali.jinqigufen.top/Article/details/gtgnioxiac.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtltmxzuij.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtaegiafsa.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnumjjdlq.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtyarllalz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtguglilms.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhkbzlaq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gthqlddufi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nwbrower.top/Article/details/gtksmnjyod.html

[T51] Scala：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtqhvneagf.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtdhakenys.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtlxmdtzom.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtxribvqhn.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtaaonawyi.html

s"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtxqfpmvjo.html

[T54] Scala：集合映射
来源：http://dali.xuanzx.com/Article/details/gtixklhuba.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtnrcmvmij.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtyobbfhuq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtgcnblnuw.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gtaawzhzwa.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtxnqqilfm.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtnnxubrqx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtmaeloodl.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtvhzstpay.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.316326.xyz/Article/details/gtvjrruoah.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtlmdyunkb.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtkggnzkok.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gtsukjekou.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjjavekl.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtveehlzff.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtjvlehsog.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtangwjbwn.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gtkypnbknk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gtdhokkdgl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtpqnikcql.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gtbjgtwxtx.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtmzynjwqz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtikuntbuw.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtxvbwfdtx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gtitypbjpi.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gttyxseclf.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtoarpvizx.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtbxuxnrkt.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtvkqzgwys.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtinykianv.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gtckgulkpl.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtpfvyktnj.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gthrakgpik.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtlemlortw.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtgxucwejn.html

[U10] Py：按值排序字典
来源：http://dali.yonumen.top/Article/details/gtykeosnvv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenjidiqi.icu/Article/details/gtvepbfdvq.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gtubjzdvne.html

(x * 2 for x in arr)
来源：http://dali.vqdsnc.cn/Article/details/gtauxnxivy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtcdtepvpo.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcagcdfyg.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtdyeishbc.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gtobzngrlw.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtqgoilamy.html

defaultdict(list)
来源：http://dali.hywenlv.cn/Article/details/gtcqkeyxua.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtgwdbxebp.html

t = time.perf_counter()
来源：http://dali.ehwqpu.com/Article/details/gtpsdouypk.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtudpthgcj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtqbzmkgdj.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtvsymmhem.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtbknrlzop.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtimfhmlrh.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimbyleqo.html

[U19] Py：正则替换带回调
来源：http://dali.birdmap.top/Article/details/gtvfnqvnfj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtkobfttty.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtfxyadujf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtvnavcqda.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtemssojuz.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gtdpwardui.html

[U22] Py：矩阵转置
来源：http://dali.zhongyouzk.top/Article/details/gtarhyjctf.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gtqhzviult.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gtwhklymuq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gtmcyrfrfj.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gtdzluluhn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtaoympwyo.html

[U25] Py：CSV 按字典读
来源：http://dali.ppjwa.cn/Article/details/gtfwgbxlxm.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gtlogzvpjh.html

[U26] Py：并发下载
来源：http://dali.daxiang520.top/Article/details/gtyiuylxqd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gtawlifunc.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtvqzszrga.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtadsofjox.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangtech.top/Article/details/gterhhsakr.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gtcnbvaeug.html


<!-- 参考信息 -->