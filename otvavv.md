代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtaabhnytx.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtyorerlpc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtmwnrsylh.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gtjolggkny.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gturvwpgjb.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gtvufifiru.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyczjihq.html

[S11] C：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtljitutwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtvqygtjcl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtqupcjwqy.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtmfkhzrye.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gtppvjtbph.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtgiywsszs.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtahgurrmu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtgtxlzdgd.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtpoanluos.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gthugrfcgv.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtisweeiwo.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtgqibsyue.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtlwuevhse.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtljcvrjcz.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtgeemzydm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtxldpusvq.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtyaejhloz.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gtwwmvbbbu.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtslqatdne.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtzwbfkpnk.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtgyqpivwk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgzvpaeh.html

[S21] C：字符类别判断
来源：http://dali.yuanzhike.top/Article/details/gtwuqcbpnt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtsgbnskky.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdfmpyhu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtadddoykj.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtkonhbgsz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtkmawsbhh.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtqwaxiwaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsybzfwa.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtzomflcdt.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtfdgpsoiq.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gtahevitag.html

memset(a, 0, sizeof a);
来源：http://dali.cqqwz.cn/Article/details/gtmdmbafma.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtljpjdcjk.html

const double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtayevnosk.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtcqbzuuoo.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtqlhcpcxe.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gtptxifhvp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtjsjustxo.html

[S30] C：头文件保护
来源：http://dali.yj202588.top/Article/details/gtfagokvsd.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtkrfzgkva.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtlhjaweug.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtemqaoxzy.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtsktmzmpk.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gttkuxxovh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtysnsmszj.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gtdlfpzjhk.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtqolnklqz.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtmvqykycf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtmobteqgz.html

[S34] C++：遍历 vector
来源：http://dali.guannengcc.top/Article/details/gteilvuueu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtqmckhbwh.html

[S35] C++：map
来源：http://dali.hammf.cn/Article/details/gtalgwalmt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtlvkdxmfo.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtknvttrvs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtrjpowuby.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gttmvnteai.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtbjlwwflt.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtcmfxezov.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtggmrlqvd.html

[S39] C++：自定义比较器排序
来源：http://dali.aizwys.cn/Article/details/gtvsjqudfi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtxdrjfxyj.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtvjdcqcel.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtbbmdpinw.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtqqpngvri.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtawjdiamv.html

[S42] C++：继承与虚函数
来源：http://dali.yangfankeji.com/Article/details/gttmauiwqc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdminsrq.html

[S43] C++：智能指针
来源：http://dali.xziqi.cn/Article/details/gtljgqpckd.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtceqrcfke.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gtvowmxirv.html

void inc(int &x) { ++x; }
来源：http://dali.yueranfly.top/Article/details/gtlncwixnf.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gtfcpcpnqm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvdmmycc.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gteiufknle.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtcwhxyuou.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtzqenmcph.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqmgwpgil.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtuirmfwvt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtuoqjcxbo.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtvpidqvaw.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtgabfllxy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gtzpyfijkv.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtddczrzxj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtrxyzunlz.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtxvdnsaka.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtxbgzndyt.html

[S52] C++：const 与 noexcept
来源：http://dali.hysaishi.cn/Article/details/gtktvtovya.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtnwrglpmx.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtwoiwxugl.html

std::vector<int> w = std::move(v);
来源：http://dali.yuanzhike.top/Article/details/gtcyrnhifx.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivpejyfi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtpjzhlwde.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtjssygybe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtmssnnllt.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gthfjfxkwz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtdzuwgnzt.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtkvnvotsa.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtcpwrjxpt.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtllpbeksv.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtjsdcdanj.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gtgkuwugex.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtnwmblzzm.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gttzdokzcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gttjpvwyzw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbcrsggpe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtggtmwnog.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuloswzpa.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gtoqobrlcq.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtllylovkw.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtgmxcbigu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuanzx.com/Article/details/gtkwggncgy.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtdntwrktj.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtrtoouxjs.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtbnxkvhmm.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtbcngudfe.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtsfdynsuc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtkkexciru.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtvsklrhmj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtawrqvbwu.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gtniaoztgx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtqnomiggo.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtxiynehbw.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtifedmbmk.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtqxzarmbk.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gteyogbnfh.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtzscpxakx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtcdeaooio.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtenutwclo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtyfnrtwjs.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtvanrtkqt.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtigeoohwt.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtqmhmfida.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxnczxqk.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gthjotjdrx.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjmgqgjw.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtkuakfqxo.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtqpzxskfd.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtyxzgspsb.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiavlqjv.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtnmaddzgk.html

var a = 1;  let b = 2
来源：http://dali.nanxinkj.top/Article/details/gtqehqykku.html

[T18] Swift：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtvkenjhtt.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtkkaxgpri.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtvyvnevde.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gttmzuoglo.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtvuzfwjpg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtliydyavy.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtxdelspbk.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtqaveislj.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gttxiynmfq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtxbjfwzun.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtdraronso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtljxnkfrt.html

[T24] Swift：闭包
来源：http://dali.hywenlv.cn/Article/details/gtkyyakjqn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtivbreqwa.html

[T25] Swift：结构体
来源：http://dali.xylfe.cn/Article/details/gtjlevdhin.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtlbxvyhke.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtvaokjeqx.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtshbknbzi.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtjehzysli.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtocwyabzq.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtunpidrwv.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtmndijtkk.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtbbnzuood.html

guard let x = opt else { return }
来源：http://dali.jiagoushi.top/Article/details/gtosqznzjd.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrhdwxsd.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtcpbfyehe.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtteuytdtn.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtjlphfneu.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtodpbblnc.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtumwsbpff.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtvoykhmya.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gtjwhbnjps.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gtvzaxaztk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.feifeiyinyue.top/Article/details/gtsgvlrtxz.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gtsocmrivh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gttfxdnkxv.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxajhbxc.html

function add(a, b) return a + b end
来源：http://dali.vqdsnc.cn/Article/details/gtzyqexpwe.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtaxqefmkd.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gthglquzmo.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gtaarqoxxe.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtdmoqsijd.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtiqyblmxd.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtsxxcvmyx.html

[T40] Lua：元表
来源：http://dali.andypj.xyz/Article/details/gtfoozwgis.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangtech.top/Article/details/gtapzqplar.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtokuwvgpy.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gttoggxzti.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtkjlogrqo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtebaqiucj.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtxcbzxniq.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtsatyeuiy.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtqbtmhlik.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gthmhajfez.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtucomwtnu.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgfzy.top/Article/details/gtswwlbcgy.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gtvgebetto.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gtfhsyhnqj.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtoziupsvd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtvmermgkn.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprmfmmts.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gtemzrbihz.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtysxwzfdz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdsopkkln.html

[T50] Perl：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtzdrelcrs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gtehqikpna.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmhtunfmq.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtvybopkmf.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtvcgvjcns.html

[T52] Scala：变量
来源：http://dali.fengsongda.top/Article/details/gtpuizrjgp.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtnqpiadpp.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtcuhsvcja.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtkkfavjgz.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifxpezug.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtlqufkxjp.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gttssongxx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtylosjmlp.html

[T56] Scala：样例类
来源：http://dali.shuidangran.top/Article/details/gtyilvicyj.html

case class User(name: String, age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtjaetecon.html

[T57] Scala：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtmwfpxqob.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtwptmyllq.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtogbmbnjl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtaxtedaib.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtlieinjwg.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gtfwhineir.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtjddvywdp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gtdetgoqhy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlimksnfl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtfdvsljaj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtagnhjqim.html

[U01] Py：创建虚拟环境
来源：http://dali.xylfe.cn/Article/details/gtreagqxlu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shzxlz.cn/Article/details/gteziwulex.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gtoatzzvsa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gtajrzpzax.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtzkpcfrcb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigfzy.top/Article/details/gteytcfwkv.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gthvvztbvu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenjidiqi.icu/Article/details/gthrnxqpca.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gteejxfvst.html

list(dict.fromkeys(arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnnxpdzd.html

[U06] Py：合并两个字典
来源：http://dali.mhx1999.top/Article/details/gtwygmajux.html

{**a, **b}
来源：http://dali.jqgufenzy.top/Article/details/gtiuadtzvm.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtxjvunfar.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gtvounygzn.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtdktkdzyi.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gtsdgabjzv.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gtuuzfvich.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtafsoyozv.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gtkjlesxei.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gturlscppy.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gthhgiwirz.html

(x * 2 for x in arr)
来源：http://dali.gogol.net.cn/Article/details/gtfhjxwsoc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gtbnzfzzjr.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmafhbku.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtuvrxlrjm.html

deque(maxlen=10)
来源：http://dali.aizwys.cn/Article/details/gtsqcibwey.html

[U14] Py：分组收集到列表
来源：http://dali.daria6918.cn/Article/details/gtfecbfxqi.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtehwvbotg.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gtdbutiwlm.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtmyrvgjzi.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtmmjhebfz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yvedp.cn/Article/details/gtewhsgomc.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gtkhmqpogs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gteapwvgjn.html

[U18] Py：预编译正则
来源：http://dali.daxiang520.top/Article/details/gttvtkirnp.html

pat = re.compile(r"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtssppptgd.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gtpyntsncm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gtgtkqisid.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtlapbbgfr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtswofwvfn.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gtlaucgjvr.html

@contextlib.contextmanager
来源：http://dali.cashguo.top/Article/details/gtdosodwnc.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gtgxbvfhvm.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gtoasfnxjo.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gtiedryqzf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtciapeyba.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gtxlhqxxen.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gtznskmkbp.html

[U25] Py：CSV 按字典读
来源：http://dali.nwbrower.top/Article/details/gtestxjtck.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gtiknrxlps.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gtftpazpwi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ybcxt.top/Article/details/gtwtyimmvu.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtugihmnyt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gtzuhwnfho.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gtmjdxhzoo.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gtmekqigew.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtmrecvzel.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gtxnkviuvb.html

[U30] Py：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdzobgmz.html

@dataclass(slots=True)
来源：http://dali.yangfankeji.com/Article/details/gtxojckzeg.html


<!-- 参考信息 -->