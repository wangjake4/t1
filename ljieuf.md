代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tanke756.top/Article/details/gtthfgtmdp.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtfvjtuvfj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtubchwfmj.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtxubrbcaj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtujxvxdvl.html

[S10] C：指针与解引用
来源：http://dali.xuetiantiany.cn/Article/details/gtbwprsclg.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtetgixmhb.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gteoyctdmx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtateksaij.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtswjsimgy.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtbtxzricm.html

[S12] C：写文件
来源：http://dali.c1oappe.top/Article/details/gttcbudzzv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtdefvbrzy.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmirvphc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtsrhwhxih.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gthzgocubz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtmswbtzde.html

[S15] C：类型转换
来源：http://dali.cheryme.top/Article/details/gtecuxwdho.html

(double) a / b
来源：http://dali.9152youxi.cn/Article/details/gtsrxdvlnq.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtcudjxqek.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtetggezxo.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtkpvivtgh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtjveowoaj.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtjbmvdnpc.html

int main(int argc, char **argv)
来源：http://dali.zhongyouzk.top/Article/details/gtbqfvoxev.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtajyvrpfx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtruixldsu.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtcxqdfsyf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtitwopagu.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtopzxpjnx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtrxguwqap.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtqdhuxgpu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtrtavyiwu.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtngurnsbd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtkcujtlft.html

[S24] C：获取本地时间
来源：http://dali.smart0.xyz/Article/details/gtqtvoowmz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtfjrtvkra.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtmorpdxty.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtofkpfjpu.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkjbplao.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtndauxggs.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtiywutvwy.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtobkbxrvg.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtfpkiyyoe.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gtwpwoovnc.html

[S29] C：变参函数
来源：http://dali.tianlin.xyz/Article/details/gtblxrjwhk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtxbdndpeb.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtysipfnvz.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gtumqhmwpm.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtamhilbxr.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtkhhtvfno.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtahkfhtmn.html

#include <iostream>
来源：http://dali.jyoumei.cn/Article/details/gtdvamwpjf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtbabusebj.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtpuxhdqus.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtvklqpxqr.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtbdozcwil.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtrnbapgca.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtxawpgyua.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gttqcjnpuh.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrntoocbs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtoxpvcckz.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtamspsrbb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtpcylbbgb.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtoghiahtj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtdigwxhqq.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gttjieytek.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtbqqdmeot.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtcqdliswp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtfrjvsmaa.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtyracbmtm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtcleesbdo.html

[S41] C++：类与构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtpvwksfmv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtsmwugynp.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgcoghye.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtduufbyis.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtofknjewm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtjenilhpj.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtziopqnie.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtolibuzje.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtvcjcuvti.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtcsrvchnh.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtykfcrpmu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtfdmzubvm.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtrvnnhqio.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtxwinawra.html

[S48] C++：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtomdjvzcs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtlmhaihqk.html

while (std::getline(in, line)) { }
来源：http://dali.hywenlv.cn/Article/details/gtodpvmvqt.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttybhezkz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtbnljxsdp.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmonlclhc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtltsodwhh.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gthqjadmdk.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtvlbstkfr.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gtzsqkqnul.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gttzemvgss.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtzvspdz.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtkpaoqugh.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtcgokssht.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gthiphagel.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtlnbuvzcv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hywenlv.cn/Article/details/gtbnppjhja.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtjiqcfkcj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gtzlyyckjg.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtilfvydan.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtfmnfuzpk.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtbocqmyof.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtwvecsfmv.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gtmwwgqyyw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtvxkfycbe.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtgwuisxnk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtxhawoqum.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvgqisgfd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtjftsuohi.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtamgblefa.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtndtsyytg.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtpfqzmtkg.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtsmssnvih.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtahegkifo.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtmrvzmmdu.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtyrzkxhwy.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtvgqompbu.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtzzvyacux.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtzfodfldm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtnxiiizdv.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtpdzdgqlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtuisnuuri.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gtpsbmpmpe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.birdmap.top/Article/details/gtvaixcono.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtwkerkbim.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtisaeprbv.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtbtxuzgmt.html

fun String.exclaim() = this + "!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfmagunm.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtfopvnzkt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjgjtajl.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtxcxtiiwc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtcxdxpxzf.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gtmcuztuua.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtynvvqoen.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gtilajpgil.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtifxkmkwv.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtdnduoxcg.html

for (i in 1..10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtjuprpvzb.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtzscexqvp.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtygbcacru.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtsmdrdopt.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtcliaxmpu.html

[T17] Swift：变量与常量
来源：http://dali.shangyingyoupin.top/Article/details/gtwolqarhx.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtxdggiwzo.html

[T18] Swift：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtgamhwxrd.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gtlmzgucqs.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gtuzphdley.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtzfuxserq.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtkdowouur.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtevnqgoaj.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtrfnhwamg.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxksfspj.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtbwbnavjv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqezvkyja.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtbyzuuwie.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttotdvdiv.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gtnbtxzdas.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtmpvjjevt.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtvfxaxtzi.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gthxllmpdr.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtpkibfdof.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtiylaficu.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtbjbonppc.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtqmhxpnrj.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtlxhdujag.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtbqmbeuiz.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtofwfhjjp.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gtvbqlitlo.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gtsqsmrjef.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtrclsqdqe.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtphxevfhr.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtkfnrgtxi.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gtzshqoxhn.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtwfdawcjc.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gthcgknfgv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtiqjuqabu.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtxwrygoiy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtntjlgfei.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtoncyqwmy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sufxvd.cn/Article/details/gtectcgzpo.html

[T36] Lua：函数
来源：http://dali.haohaochexian.top/Article/details/gtgmrapbpb.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gthzhmhefs.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtgkzeiclo.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtbkvpiide.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtmtzeywyh.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtorrwleea.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtyqdnvhdt.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gtqxxpobes.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtbqupkitc.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtyfjnudsx.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtbvbjbfut.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtuixdsswu.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtxlypplrx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtgyqjsthb.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtqmddwbap.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtmsjwkkjg.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtwjrykwod.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtxrizcjgf.html

[T45] Perl：数组遍历
来源：http://dali.yvedp.cn/Article/details/gtjmxsunfx.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gttaxjkssj.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gtxpaasipv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gtxhcejebl.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtairzftas.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gtsveezxbr.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtdiomtehq.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtpnjckiiv.html

[T49] Perl：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpsdkjmf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtkbhpkksn.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtkowtofer.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtqwusfeja.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gtrenkfjwy.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gthohvvgvm.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtioxzzlix.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gtadlosivh.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtghgvocfk.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtxanswnvg.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtfczvregs.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtllufosdq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtvdfteelc.html

[T55] Scala：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzihmnxx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.vqdsnc.cn/Article/details/gtbmyszyrh.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtmfpiylij.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gteytzkxbl.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtichkilba.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zycfv.cn/Article/details/gtgzeckksd.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gtzzjbhgiu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtatdjftvw.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtidmhdspf.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtbsuucohp.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gtttrcqndl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtpmhyjpqe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcdmpvsdh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtsvlarqoj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdswqjcka.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gtwwfqhhqr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtwnwgszfh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtaugnlinx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtketrqnxx.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtossunfhe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gtrnpnclot.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtrrxivdje.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shuidangran.top/Article/details/gtxhzmaqim.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtsaipesht.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtwvokawmq.html

[U06] Py：合并两个字典
来源：http://dali.jlsjyb.cn/Article/details/gtctnmwpcv.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtlaaljzwv.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqeklikf.html

{v: k for k, v in d.items()}
来源：http://dali.smart0.xyz/Article/details/gtpawqqfwa.html

[U08] Py：展平二维列表
来源：http://dali.dashuyun.cn/Article/details/gtzkylrtmc.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtfbofssve.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtlkdsxhfo.html

max(d, key=d.get)
来源：http://dali.hammf.cn/Article/details/gtuzarwnxc.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gtvnmiflnq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gtembibnqt.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtckzqktea.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gthhpnighd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gtsiqapggv.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtxgmhgfzk.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gtetfankey.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnivldnez.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtmrlwidym.html

defaultdict(list)
来源：http://dali.yangfankeji.com/Article/details/gtuadmfxzk.html

[U15] Py：高精度计时
来源：http://dali.zdqjudy.top/Article/details/gtinisnnji.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtaeuqiwcu.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtfuaarrmn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guannengcc.top/Article/details/gtoherfurb.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtkcczurzg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daxiang520.top/Article/details/gteqrzrtua.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtrpfgdsdw.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtqrsrmedv.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gtkborrunx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtfecfkurb.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtjpvxwihm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtpderzdbs.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtetorrlsd.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrptqjtfv.html

[U22] Py：矩阵转置
来源：http://dali.zhaomingkeji.xyz/Article/details/gteghtiujr.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gtfktjspfk.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtutnrqgcs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ydzc1.top/Article/details/gttgeznocd.html

[U24] Py：路径操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtswmwfseu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtpaonnmhf.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtxrszyszy.html

csv.DictReader(f)
来源：http://dali.xylfe.cn/Article/details/gtghilqslx.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtfpvyeprs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gtzurdtspf.html

[U27] Py：异步 HTTP
来源：http://dali.quarkkingdee.top/Article/details/gtncfuslcr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtrywlrssg.html

[U28] Py：类型别名
来源：http://dali.hfpthk.cn/Article/details/gtzvkcdedm.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtpzitagpm.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtjbdqvbcr.html

@property 与 @x.setter 配合
来源：http://dali.dianchejie.cn/Article/details/gtcxjvxnmp.html

[U30] Py：数据类
来源：http://dali.yuxming.cn/Article/details/gtgajzxscs.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gthjvupiiy.html


<!-- 参考信息 -->