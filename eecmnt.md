代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtknhphnto.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtvyuaqipy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtiquydrbm.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrbivmty.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtmfylgjrc.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gtlniodpiu.html

int *p = &a;  *p = 5;
来源：http://dali.hysaishi.cn/Article/details/gtiyaqwzvq.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtmwnbzdns.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtkodzceym.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtowmhxlxh.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtnazcuznl.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtnwkqrjrp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtoiocgbdq.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gtqislsvst.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtgluqrjlx.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtalmmbmcg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtenygjmll.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtxtvbbkdp.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gtrsxmnfgt.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gturhgvfmp.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtftqeyxwb.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtlpaaqkgq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtvhbtiqmm.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtrmzmahvo.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtfthijcen.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gtvmltwvlc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gtkgfcnino.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gtqhgotmxn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtrnpscqwj.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfhqprua.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojocpglo.html

[S22] C：字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtqdatibpy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtaybgwzgj.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gttfzcfgni.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gtxgacfgav.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtvmxcgubb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtoqiopvsn.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtszwcpedf.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtbtdrzdnq.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gthyatjhfp.html

memset(a, 0, sizeof a);
来源：http://dali.xylfe.cn/Article/details/gtnqgfekix.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtmdgwzwpw.html

const double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtzqtauqol.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtdnvaaujz.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gtkwsvrxad.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvkenqza.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtqmuopujw.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtayhpnlpi.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnndifea.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gtilyfavlg.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtmkyubiij.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtzwaehmuy.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gttzxjwefm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgoywvzu.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtkocphdhv.html

std::string s = "hi";  s += "!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrkbxtcl.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtpkfzvsyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtdstpibui.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangtech.top/Article/details/gtepyrhpwa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtvoctwrmz.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtdldrvudh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtyovydrkn.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtijssykyh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gthrcbofdq.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtfragqtzn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyabdoeuw.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtxgwkfanf.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gtmljahiqj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgfynkhd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcydyjplm.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtcnmqdazd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtbwhiqrvq.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxouxblr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtdyozxnnc.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtrztvpcug.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtliffmjxr.html

[S43] C++：智能指针
来源：http://dali.zdqjudy.top/Article/details/gtarusdvyh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtzigjmyet.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtrzpsrlox.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtgokovupl.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtapuffynz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtmbrreysk.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtjzfvcqau.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.kuanghao11.cn/Article/details/gtmwcsicad.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtztmmwmdr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtwysahtyh.html

[S48] C++：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtrbozrlqt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqqprihl.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtrlatgrjw.html

[S49] C++：写文件
来源：http://dali.birdmap.top/Article/details/gttdwpbnna.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtmjiyrcjg.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gtktovfpua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtcrwgsgge.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtjyxeeyyc.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtpnckkbut.html

[S52] C++：const 与 noexcept
来源：http://dali.gzhubu.top/Article/details/gtfqhfymoc.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtdoiibkbr.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gtktbqlwqs.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtctxuctql.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtaahsjuce.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtmtbabowi.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtdybbzwqu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtpcnlciby.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtioynjvia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtsrcqzpkn.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavajzvrj.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtgcdrdirw.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gttknqxsrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.gogol.net.cn/Article/details/gtnxkorykn.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxufqonq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtolaygqnr.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtxrhkouja.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gtrqrkgmqa.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtaripnlda.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtoboethsd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsphtrvdd.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtrjyloxwn.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gtgughrihe.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmucauymb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gtpnabevkg.html

[T03] Kotlin：字符串模板
来源：http://dali.bjfxy.top/Article/details/gtmmrwkgdd.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtkxmgsffa.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtbkgbktbz.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtfdnsadwh.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gtfjdpxbdu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtuhvoawmp.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtadvlbpwl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtmykbclns.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtxardsytv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gaohongyu789.top/Article/details/gtrbsylvbu.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gteqswolpn.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gthlkuvsgy.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gthkrlxiha.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtlhluyzdo.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtyfiknhup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gtcpwiukxt.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gtvmbkomgo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfacpqaaa.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtwgwyjizm.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtqxfvpioi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gthipmskkd.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtaoillsxi.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtzpaojlcx.html

for (i in 1..10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtmwvhyovz.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtimizgbev.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtzdkkhewm.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtjsnkxxwt.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtsihnbusr.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gthlobuscl.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gtrbxwitub.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnijivmrq.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtsbjvjosv.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtlhuobhth.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtbcjozece.html

[T20] Swift：数组操作
来源：http://dali.zycfv.cn/Article/details/gtglbijduo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtvblgqidx.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gtemczwnmw.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtlqlyiiun.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtuwijnukp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtlsxtamcr.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gtdsdmnmyv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtvguzecpn.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtevqeqopn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtnhjygwzz.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtgwblmbrs.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtxinqtxxt.html

[T26] Swift：类与重写
来源：http://dali.sufxvd.cn/Article/details/gtktuagrxq.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtxatynvcx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtikgqffqq.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtsaoxdjid.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtdojevyps.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtvrwayfzh.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtvbwrznjg.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtwpcrkjpa.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtgdihlrsz.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtjiwcjqxq.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtlcewrzqz.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gttbnmfczd.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtdmmxtbnb.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gtrgnswdql.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtlxbrrypb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtzypqmpli.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktqzxojg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gttbrczciv.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydasqhvx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtikhjakln.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtcvtldhra.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtcvweoyeu.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtpcixwqar.html

"a" .. "b"
来源：http://dali.shuidangran.top/Article/details/gtajqpzzjg.html

[T38] Lua：条件
来源：http://dali.tian-w.cn/Article/details/gtoroolplf.html

if x > 0 then print("正") end
来源：http://dali.hammf.cn/Article/details/gtuqvnolai.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtqmillqlm.html

string.find(s, "%d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtydfzlqjr.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtcbwwvdyk.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gticsmqxze.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtsycyystm.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtqlkqlkhh.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtvytptfyj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtlgmtfdwz.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtpyouljgi.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtfohtjneb.html

[T44] Perl：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtzylkalnz.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtgmqhyvnm.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gtimrltlkd.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtqadwmuhj.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtgryaageg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cheryme.top/Article/details/gthyeppolh.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gttfvehymo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtrymwkcar.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtlxluwifj.html

$s =~ s/old/new/g;
来源：http://dali.iojbl.cn/Article/details/gtulnedpqu.html

[T49] Perl：函数
来源：http://dali.wangdashe.top/Article/details/gtbukhwqln.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtwdbftddc.html

[T50] Perl：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtygppkgmi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtpocbqopz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtspmxckyq.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtihvlfljr.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtqveqwcmg.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gtdsjgndxe.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtpnjtjcdt.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gttmjiojqp.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtkooxigij.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtvxltgfji.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtrqlspimg.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtgcalzlds.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtdsocgpnh.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gtchwymsuq.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkehxvzzq.html

[T57] Scala：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtkbwloilx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtznievrsu.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtuhyqepxo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtpwtolvwo.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsgytbhy.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtibjsgpdp.html

[T60] Scala：折叠
来源：http://dali.cucudq.cn/Article/details/gtfjearbjy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258.top/Article/details/gtmvefixls.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjcxumnla.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gttlfyrkyv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtcctvdocp.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtqvjgsudq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnqzz.top/Article/details/gtzheavaiw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtwpzrvznr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtkeauubrs.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtghfqouzx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sxryk.cn/Article/details/gtqdzxeuqu.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gtsvfgjlvh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtsbrulztr.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtlxoortlw.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtqqcraqrw.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtjogksizv.html

{**a, **b}
来源：http://dali.ehwqpu.com/Article/details/gtqjpujrlg.html

[U07] Py：反转字典键值
来源：http://dali.sufxvd.cn/Article/details/gtqbbspcxm.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gthftxvlvh.html

[U08] Py：展平二维列表
来源：http://dali.gotoacloud.top/Article/details/gtokqixzeg.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtihmcxjvi.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gtrjdozqrw.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtotvcunda.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gtpmwshfge.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtwqxnpkag.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtlqofpzwm.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtqmsikmuu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sweek.top/Article/details/gtmghrmlov.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtlywxqruo.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gtfjioepfi.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gthcjagokm.html

[U14] Py：分组收集到列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofbfjbjs.html

defaultdict(list)
来源：http://dali.yvedp.cn/Article/details/gtegioudcs.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gtrumemyzz.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtbxueqjso.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtecnvzcka.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gtmreegrws.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtoekserdk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gthwhdgxfm.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtwwruauqf.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gtmgczvsxf.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigfzy.top/Article/details/gtdxgdcgrq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtszqtrwhw.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtjmvybwth.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sweek.top/Article/details/gtuswoqsdj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhwijmyu.html

@contextlib.contextmanager
来源：http://dali.feifeiyinyue.top/Article/details/gtdkqohabu.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gtfnusvwcg.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gtlcjemnxf.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gtyzcavikz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijewbpew.html

[U24] Py：路径操作
来源：http://dali.zhixingplan.top/Article/details/gtzurnnawd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gttzlzvstq.html

[U25] Py：CSV 按字典读
来源：http://dali.tanke756.top/Article/details/gtpccatobc.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gtcnlostoq.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtolfgiabi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtsqzxqktj.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gttfjducya.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtouznvres.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtuscqofbo.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gthvczhljs.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtsomxhfil.html

@property 与 @x.setter 配合
来源：http://dali.sysykeji.top/Article/details/gttldbdlam.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gtuvydwnln.html

@dataclass(slots=True)
来源：http://dali.yj20258.top/Article/details/gtbfotumpq.html


<!-- 参考信息 -->