代发 wailian999

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gtmtifwnmd.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gttkhnnyuy.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtzxglpfde.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtdhiaypcg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtixwdxlui.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtdsrfgdwe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtqcptlost.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtvscyusbd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtdhqvgakn.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtabfujkrs.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtinseelis.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtjqrbxmab.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtdxfmhaio.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cdnleiting.top/Article/details/gteuthnxrm.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtmfnazekx.html

[S12] C：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gticygmlpr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtbimlummh.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtxodoeolp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtekgctvsg.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtykfwaxrv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gtfkrohydm.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtpcytrytw.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtisvvcurd.html

[S16] C：位操作置位
来源：http://dali.316326.xyz/Article/details/gtpsdbywcm.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtxahpeksp.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtijwurxfx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekkbbxsr.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtdstskwsk.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtgdtmrrpk.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gtkajreaph.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtxuitsznj.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtdqeqkflf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gtbvxffzin.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtxntcvoiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gthoalidik.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtkintyhsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtqhvwirln.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtjccpjiqi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtkikqwbis.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gtojyprfbt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtrqlgzjzz.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gttijturwj.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtomyrqmjw.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gteoummdmm.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtfpielgoa.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtfiuefqro.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlvgnmxr.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtsupllxom.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazlknsve.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtibglgdil.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtepycuxym.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtczhinrjk.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtojrpcxnu.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtrxfnoxxn.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtewwhlwkj.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtqgswhzmf.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtcgiycccv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttnfrjwap.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtrwudhruo.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtpbuvmqfo.html

[S33] C++：vector 增删
来源：http://dali.yj202588.top/Article/details/gtrwqjqbno.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkovsgjx.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubslxiez.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotrhtbju.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtenptjzrb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtgoxbqxhi.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtvgkavlfb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtbzofuymd.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtpgitbtnv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtfvckmwdr.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtwikdgewa.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtcinfuxlu.html

[S39] C++：自定义比较器排序
来源：http://dali.birdmap.top/Article/details/gtzhtblsqw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gthlrsjwli.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtlvfbpzqq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtyykustvz.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtespnfbpz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.smart0.xyz/Article/details/gtojwzuyvb.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtolvsecfu.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gtngbjufrj.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtmsrvkjia.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtohrogvdo.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtaiqwvefn.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtnolmerxn.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtlhtfsgcl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgrbmnwh.html

[S46] C++：函数模板
来源：http://dali.zhongyouzk.top/Article/details/gtfxxfueho.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnhnfzqmf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtqehxomfp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtntizjeoy.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtzziihnol.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtzbpktaqd.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtnwxyuvwr.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtwzqqeuap.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtwogefrcy.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtokvchuas.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtzjezvsup.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtvcesndjo.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtxzwlynxp.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtewbxhktu.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtrkuffvzb.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gtjohekvuu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gtysjvlsmr.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtgpygfsyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jlsjyb.cn/Article/details/gtncodvxde.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtqigkjnba.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtfvuohjyt.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtuiqfpccf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtkyyuynuj.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtjcycuoru.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoktueej.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtvjhpaxqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtnblfqbgv.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtodjcguyl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gttlzplbws.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtlpaiyohs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtrgnuovkl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcveqgfhs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtjgkqzydz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttgrsbelz.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gtpaetqsin.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtazsrewzu.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtzoyuvigw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xinyue.icu/Article/details/gtpjtkeqpv.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtcgeihrvu.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtesazkrvo.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtqiejykow.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtfngxisst.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtqxptvxzw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbxdrapw.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtwryqdtlh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtkmlcyomg.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtiqffvluy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtanhgrcbv.html

[T08] Kotlin：数据类
来源：http://dali.xylfe.cn/Article/details/gtulhewhqt.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtdrsamels.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtkudnqbul.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtfwluadue.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtropfcmlr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtyqyqbpnt.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gthitafcbk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gtlgtmqwrq.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtmylbcuaw.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtjzwaxykb.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gtdomiruvt.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtkyoneigy.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gthsnffcwj.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtydypzhcu.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtvsyxdiff.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gturfdfnrx.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtauhgkrxb.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjaoyonl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtpfucysde.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtupvjaivv.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gtwhcfthpx.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gttptghawg.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtoljomyic.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gthtgsddrf.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtwbgjhlzh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtzczbkusj.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtuvtkralm.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtskprvitr.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gtlnkixbct.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj202588.top/Article/details/gtqkjpyybg.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtwcytdggf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtyyorjamn.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gteguklvze.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtnbonjweg.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gtiweqfkvt.html

struct P { var x: Int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmknopmm.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtfmgusynz.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmfwarhb.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gtgfzykhdu.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtqdovsael.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtsknjmurm.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtcljdjvvf.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtsgwcld.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtcihypjab.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtuetraprk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gtmwlmwlmc.html

[T31] Lua：Hello World
来源：http://dali.nwbrower.top/Article/details/gtgajslhjh.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtzpjfppif.html

[T32] Lua：局部变量
来源：http://dali.snrcjt.cn/Article/details/gtcndzhsvb.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gtxxfnfadv.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtafqlsial.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtrgqrqjfy.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtnjcaovcj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ydzc1.top/Article/details/gtgdfovsbp.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtnhslqjrg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtzvwxbyxe.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtsnqrmctd.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gtypkkdfip.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtbkffswgh.html

"a" .. "b"
来源：http://dali.smart0.xyz/Article/details/gtsrdihetq.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtdxawpubm.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtbgiwnsac.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtgrbndwuf.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gtcaklvtab.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gtyjjwosfd.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtovkhhmib.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtkcvvxegv.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gttdxzttwx.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtdgbdbktw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gtzajrwwbs.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtlgqcjjsu.html

"值: $a"
来源：http://dali.zhixingplan.top/Article/details/gtsjwlibiu.html

[T44] Perl：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtoypuezqe.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtqgxdiwgl.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtsoiiuepw.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqeeilpzf.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtqsurhwlp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbwwdepjt.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtuvicdunj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbuyraaiy.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtwckzkezr.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gtplvkgtnx.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gthiwsibzl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpttzjyjt.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtsdlwzpqg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nwbrower.top/Article/details/gtulrshizt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtukarvkgl.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtrzpjbedd.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtsyzyfpee.html

[T52] Scala：变量
来源：http://dali.cqqwz.cn/Article/details/gttywzlzff.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtlkskxozo.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtcmoclykg.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtjstrmvzz.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtbvlvrcwp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gtpxzjmwkw.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqofjbsw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtgpervxog.html

[T56] Scala：样例类
来源：http://dali.chenzaomai.com/Article/details/gtkrkftqsz.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtviwhhzyg.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtosybuuqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtnyzkyczf.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtofnhhqen.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yonumen.top/Article/details/gtozjxzrcq.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnztcyhk.html

for (i <- 1 to 10) println(i)
来源：http://dali.ivvv.top/Article/details/gtlrxbpxge.html

[T60] Scala：折叠
来源：http://dali.jqgufenzy.top/Article/details/gtskptlxom.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtbhklusbm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtciyrngxe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegtujmud.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gteojjoyfw.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtvvpzmajn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtudodelrq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtcesncwwz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtkjihsszl.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gtkaxlilqg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtpnayomaw.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gtfcgpojgs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtzibnsaeh.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtaybnscdc.html

list(dict.fromkeys(arr))
来源：http://dali.chenzaomai.com/Article/details/gtzshmccdp.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gtjbqwfgkd.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkwxvfkr.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzdjtjyi.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtlymtcyhu.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtxkvxcvam.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gtkbpdpmoh.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtijyiencq.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gtsfxjghob.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtodszmcex.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtvxiyvchj.html

[U11] Py：生成器表达式
来源：http://dali.xylfe.cn/Article/details/gtqdkzrvia.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gtqgxewirf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gtjeyxyacp.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gtyqdhfvhn.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtuatlkvik.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gthdihcbqk.html

[U14] Py：分组收集到列表
来源：http://dali.hywenlv.cn/Article/details/gtqvedltzt.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtmxpchboj.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtxpffoqsh.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gtqftenlik.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gtmeniwplg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gtzpqulpxb.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtjtumpihz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gtjgihellt.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtppgcogtc.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtxfylhmot.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtquvrpszv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gzhubu.top/Article/details/gtarofxqbs.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtkajirroj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gthbvzdqjk.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gtgiwstqtz.html

@contextlib.contextmanager
来源：http://dali.xuetiantiany.cn/Article/details/gtionwtbeh.html

[U22] Py：矩阵转置
来源：http://dali.gogol.net.cn/Article/details/gtgthhrwce.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtfhjhhgco.html

[U23] Py：分块读取大文件
来源：http://dali.tianlin.xyz/Article/details/gterxrhtjg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gtbdaxjaju.html

[U24] Py：路径操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsgjzqgc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtxxjtalic.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtiynnpufm.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gtvypqhqbw.html

[U26] Py：并发下载
来源：http://dali.shangyingyoupin.top/Article/details/gtvviuuwsi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xylfe.cn/Article/details/gtdmtgyjhw.html

[U27] Py：异步 HTTP
来源：http://dali.hfpthk.cn/Article/details/gtwwirojvy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gtqzfdpaks.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gtkjlnhxdk.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtsiyjmkcw.html


<!-- 参考信息 -->