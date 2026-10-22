代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtophvtycs.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtezwtrkbz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtzbrwvtcu.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gtwmmrbgod.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtbzcnxniy.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtajpruuum.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gtewqbwnsr.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtqzitozxi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtduslylxg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtfnnrdmic.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxteusfo.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtukefibxm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtxkrdezaa.html

[S13] C：宏定义
来源：http://dali.chenlongwang.top/Article/details/gtjbqtmifb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtdhgverph.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtiaeqpmqs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtwimzszkx.html

[S15] C：类型转换
来源：http://dali.0kj1m.cn/Article/details/gtxriwozwb.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtojqlqciw.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtxaqtezuh.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtqsxmokwr.html

[S17] C：安全拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtilnmqrqs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtdenprosl.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gtgxgjxxqy.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtwwzyweir.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtaitminnw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtbdnxkvok.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgimrlfo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gtqhbjwnvk.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtwbtxzupp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtptsoqvci.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtgjxpxaza.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gtinmwrryk.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gthmuhqxtm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtpwbvswfb.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtlbjwejtj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwudcrljr.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtczqiydpu.html

memcpy(dst, src, n);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdtqugwv.html

[S26] C：内存清零
来源：http://dali.yanxiufei.cn/Article/details/gtzvnfprmr.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtrokvokbq.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtdqpwuflu.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtvrctpmcn.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtmztoogtb.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gttoaigmca.html

[S29] C：变参函数
来源：http://dali.xylfe.cn/Article/details/gtrilwihqf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngtybpju.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtyyhovhcw.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gthdogzvqm.html

#define X_H
来源：http://dali.zhixingplan.top/Article/details/gtadgxgjjn.html

#endif
来源：http://dali.tanke756.top/Article/details/gtiodnabaf.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtbwovqawz.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtjwejnect.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtbxnpmiln.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtmzmvowya.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtvlrsfuod.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtagbqjehb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtfcarscqu.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gtyvprcoud.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtavodvfwv.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtjmbwyokt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtbeshldgk.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccxejrwx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtwddvwxim.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtqtvmfojw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizykxjcw.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtionpjwea.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtowhvqaay.html

[S39] C++：自定义比较器排序
来源：http://dali.zhixingplan.top/Article/details/gtnaxgzyze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnabvvkr.html

[S40] C++：查找元素
来源：http://dali.vqdsnc.cn/Article/details/gtptutgnbt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtoqsiajkn.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtydznnubf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtykmaxzhg.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtxolvfrog.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtjbomkwid.html

[S43] C++：智能指针
来源：http://dali.gogol.net.cn/Article/details/gtanslbjve.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gtjhpahltf.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtyznguxpz.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtqfhwegfz.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtkxysorhe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyspftql.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtqopfhach.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtitxzvmaj.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtkquollzw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtecegtzxf.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtfibcuitz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtrliqkjmv.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gtyoykuxjt.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtewkprqpm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtpyrfpmbn.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gttolofuzj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkbahuxl.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtycclyjjh.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtfuxvdyuw.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtidljdmop.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtjuxxpssl.html

[S53] C++：移动语义
来源：http://dali.mhx1999.top/Article/details/gtjtjynahn.html

std::vector<int> w = std::move(v);
来源：http://dali.shuidangran.top/Article/details/gtifhmefeq.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gttgkblvpb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrvujcsm.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsshmxihi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyztonlxz.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtfuzbayuo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtlvcjzvql.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gteksyleba.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtviziytbu.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtwmshhark.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtwtekvbnw.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtaizdvrsd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gtzjnucsii.html

[S60] C++：遍历并删除元素
来源：http://dali.ivvv.top/Article/details/gtgsowjowk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbrcgjvt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthiwfvayq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuddmjfnm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbrrzhhjj.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtonnrtbuq.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtevelhffh.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtrwmoyycf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gthveywmiu.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gtmehycxwh.html

"值: $b"
来源：http://dali.xinyue.icu/Article/details/gtzdswyxdr.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtobapomcd.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtiipqdbfs.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtihbvjsuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtsafmocfi.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtufmmyudc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtmltbdfqz.html

[T07] Kotlin：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtczswujvf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtnsgfsnnr.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtcfqzfgcb.html

data class User(val name: String, val age: Int)
来源：http://dali.daxiang520.top/Article/details/gtguogqzsh.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtvobctnej.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtcsknqawh.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtmlfeacyi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tian-w.cn/Article/details/gtngctlsbc.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtxnwsnenr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtongxdybh.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtvauogvaw.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtbngtqqti.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gthazlayzv.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtkvjxbeqh.html

[T14] Kotlin：循环
来源：http://dali.xylfe.cn/Article/details/gtkrziuaaz.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtydcifzvc.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtuvawvvzs.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gthfljdryq.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtltnvqyqh.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtiqkuikwq.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gteaqonavy.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtqfjneuxa.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtupiievla.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gtyrykkqvd.html

[T19] Swift：可选绑定
来源：http://dali.svipenyu.cn/Article/details/gtitrwepvv.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtzcnxfsxk.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtvsywnywj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtmcdeorud.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtzyozvbfc.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtguubqrmx.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gthqpbnubg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gtfmfulrge.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtgywniauc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtbbraehuy.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtpwfqvkof.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtywctadtu.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtssdxwips.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtbkhqsnuz.html

[T26] Swift：类与重写
来源：http://dali.tianlin.xyz/Article/details/gtfshnoemz.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gtyctwgzki.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtkmjgxdiz.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtdutzvdxc.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gtbqwquagg.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gteneatzme.html

[T29] Swift：guard 提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtvcmoafnx.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtfhybiqpb.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtsvzzqacp.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtrrwhygyf.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtwlcyrlgg.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtdcwkbsnq.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetawpdkh.html

local a = 1
来源：http://dali.c1oappe.top/Article/details/gtmwctuwvq.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtoufuniix.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtmtngzrfn.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gtthlkcusb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtvglvvhdx.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtearyujfr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqkxrgaw.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gttlbzqegp.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtdemezgoy.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtsxcmhclh.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtwgrvfbde.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtefgmewbi.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpamsktd.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtoplumynm.html

string.find(s, "%d+")
来源：http://dali.gaohongyu789.top/Article/details/gtnvfwwqdl.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtsvsvfmws.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtnvxkkidk.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtvmdlmypa.html

print "Hello\n";
来源：http://dali.jqgfzy.top/Article/details/gtvwlowybr.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtgrfcznyp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtphhgipjn.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gthhrtgirg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtfgqtqwbu.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtaasuqieh.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtgtroojeo.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtyfalsptf.html

for my $x (@arr) { print $x; }
来源：http://dali.dashuyun.cn/Article/details/gtlyexbygx.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtmntrerbz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gtlwahreoa.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtxqbonilz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtvqmekguh.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtgjpbcvyk.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gttjfbjmsw.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gthwgacgtw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtkvizkrpf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtmuxbseyk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtjzkoziwv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtimgsinbc.html

[T51] Scala：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtnxpxhbqf.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtgroxbdnl.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtnwgilici.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gthgcrfqga.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtulaswbna.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtmbcltczc.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtcjzhzkei.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtbunnhnem.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtsnzqfphq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gthgilnkhl.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtglegbaae.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtnlckfjti.html

[T57] Scala：模式匹配
来源：http://dali.shuidangran.top/Article/details/gthumomdne.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gtostipcqw.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gtkpziqcnt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtfbjvrvog.html

[T59] Scala：循环
来源：http://dali.svipenyu.cn/Article/details/gthvzdnoom.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtoemagysf.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtpizxvevn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gtbvgoavrc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwptkbnyg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtuslmsrcx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfoetfuju.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtsgucwwpw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtrtgpwvwi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhongyouzk.top/Article/details/gtvzdhjbin.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtvlwcajnq.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gttocqhqeb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtjnzmtkfb.html

[U04] Py：变量调试打印
来源：http://dali.cqqwz.cn/Article/details/gttcwuxzyv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuanzhike.top/Article/details/gtztyzzzup.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtjpualpim.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtecrievpk.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gtinhhatoq.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtogbrgyer.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtynapcnsf.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtymidubbb.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtzgglriik.html

[y for x in nested for y in x]
来源：http://dali.316326.xyz/Article/details/gtgvenmbwm.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gttjxkjeyf.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtsranjios.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtssbfkbgs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtvsxjkmjs.html

[U11] Py：生成器表达式
来源：http://dali.meibo888.top/Article/details/gtrnaxdahq.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gtundmmecw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gtmlyiccbe.html

Counter(arr).most_common(3)
来源：http://dali.quarkkingdee.top/Article/details/gtrmyenwwt.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gtkhnevbui.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtalyojstq.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtumlhrhog.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gtlqlypqti.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtgthavedb.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtxfofvgcp.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gtbfnqyuay.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gtzekoinmu.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gtiseafotg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gtxrjeaahu.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtxmjpofhg.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtpuobghjg.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtgmadteso.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmmyxlyp.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gtixzwmhvv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.andypj.xyz/Article/details/gtjlqyzafo.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtomxfxpqb.html

@contextlib.contextmanager
来源：http://dali.xinyue.icu/Article/details/gtgzvcnpjs.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gthszecvos.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtyhceoyly.html

[U23] Py：分块读取大文件
来源：http://dali.c1oappe.top/Article/details/gtnjhpdxuj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gtdwvxybor.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gtrlvqukvt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtchsvxwvj.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxuanxn.top/Article/details/gtzqgrqkuo.html

csv.DictReader(f)
来源：http://dali.316326.xyz/Article/details/gtnbndxpdl.html

[U26] Py：并发下载
来源：http://dali.nwbrower.top/Article/details/gtmwntpthp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gtqxcmsqox.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtqfxbhxca.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sxryk.cn/Article/details/gtcdozjxwi.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtdcibcbxg.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gtfwiwzgrv.html

[U29] Py：属性校验
来源：http://dali.xinyue.icu/Article/details/gtjdelnvop.html

@property 与 @x.setter 配合
来源：http://dali.ybcxt.top/Article/details/gtnpupyaiz.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtecgwklkh.html

@dataclass(slots=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtgsnuwtoh.html


<!-- 参考信息 -->