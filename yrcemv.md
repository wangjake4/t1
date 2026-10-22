代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sjghitff.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2rxkycepr.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gt2fwujefgn.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gt2yzooexiw.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gt2bxrjupkg.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gt2iugxxzny.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gt2cavcpdit.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2fccdehgi.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsdwruyx.html

[S06] C：字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2lspkklnf.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hlxdlcur.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gt2ezvunmwc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gt2ykgvosol.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2fpmevubj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gt2vvflnntj.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gt2wrnndrwy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gt2gwxzljco.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gt2aldassim.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2iixkrwrd.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2suonxkdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gt2jppiveoj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2rjxuqdsf.html

fclose(f);
来源：http://dali.smart0.xyz/Article/details/gt2rcfuvysn.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gt2uflooaqs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2wakjemwk.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2gtmdvqxs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gt2zhfopluz.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gt2zwbyahvb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gt2vrhgtupz.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gt2mbisxvyn.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gt2frkxrrgc.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gt2gvjxfpsf.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gt2yqgnglwz.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2unmgyjmj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2wktlskgd.html

[S18] C：命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpzplwyn.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gt2lefkfmtu.html

[S19] C：快速排序
来源：http://dali.chenjidiqi.icu/Article/details/gt2fnsldtke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2hnlmjspj.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gt2qhpvqjnp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gt2aysosnxo.html

[S21] C：字符类别判断
来源：http://dali.9152youxi.cn/Article/details/gt2prmzieua.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gt2tihizoqv.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gt2qyteuqef.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gt2awjrjnso.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gt2cmapuefu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.bjfxy.top/Article/details/gt2stbtojij.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gt2ajevhdir.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gt2dmiaklmz.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxxelzut.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfwaevso.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2mqqqyowd.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gt2wfaaziyk.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gt2hkjyivyr.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2nriqjxwj.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gt2pxnyhmjd.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gt2rcvcbrzc.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gt2qzpgydcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2lfbbmnir.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2agnjlave.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gt2nwqbatpb.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gt2ltlehzas.html

#endif
来源：http://dali.0kj1m.cn/Article/details/gt2vaviifcr.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2kizvhrbo.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gt2lzqvhxvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gt2evwgzzbe.html

[S32] C++：字符串
来源：http://dali.jinqigufen.top/Article/details/gt2fvqgqtnp.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gt2fjthznii.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2hhuywszf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangdashe.top/Article/details/gt2fkzxmthi.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gt2azchwgqk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2idetkjfz.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gt2ibhdfmja.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2bjfzmlwy.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gt2hckctgeu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2qicrxpng.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gt2yvcsgwjh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2yosiwwib.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfaspxtd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2izphvrin.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gt2cgklszjp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2lksmkbmb.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gt2wrjeqpcy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gt2oiyrqhxk.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gt2mjpetusc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyyzrju.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gt2iuoktxtf.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gt2asfpjqum.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gt2yesgupuq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gt2fkwaespm.html

[S44] C++：引用传参
来源：http://dali.xuetiantiany.cn/Article/details/gt2kuftwwic.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gt2soxxqjpv.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdondiyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2gvqwglju.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdlzczfh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssxgafyt.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdybszrw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gt2whbmkrbx.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gt2kkhpetjx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2eoncjmyw.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2smazxvaf.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2cznzrqgx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvdcatmg.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gt2yxftsefq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2ymumvviu.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2hzokvhqc.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2cjqpwzym.html

[S52] C++：const 与 noexcept
来源：http://dali.birdmap.top/Article/details/gt2oizxueqf.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gt2rbkwzfxc.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gt2memkzwiz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fysglbwk.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gt2atmxwhsu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gt2tinsmnzr.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gt2ufahethg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2grlsotnd.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjdwnjnb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2cqmwfchd.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gt2gudepkzp.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2mzuwcryh.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gt2ujzdhkmp.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gt2yredaoyq.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gt2qvcwegbd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gt2ztvyuhza.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gt2cyoulcog.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2lfqvdlea.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lpugtawc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gt2iqfjqynb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2uqmidtxf.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqavewnw.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gt2esgrgnjs.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gt2qssuemrl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhxrxjpb.html

[T03] Kotlin：字符串模板
来源：http://dali.c1oappe.top/Article/details/gt2awdhysmy.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptqqnpdv.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gt2szzwmncx.html

val n: String? = null;  n?.length
来源：http://dali.meibo888.top/Article/details/gt2jtpcsoal.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2dlqkbpsg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gt2arfwreot.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2regnfkzz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2nyvxmcmt.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2dbaiokye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lygwkrin.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2uzjvxpou.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2bkwqduxg.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gt2vrxsqgvi.html

fun String.exclaim() = this + "!"
来源：http://dali.316326.xyz/Article/details/gt2rkolaqui.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gt2zqacdcmh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2hmfvxcdt.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gt2ftzuxoja.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2gmzgbwju.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrdvqscb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2bqsxrhch.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gt2nqckalbw.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gt2vgmosymh.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gt2xgnkyipb.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2snlxkiqj.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gt2zhugrpjw.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gt2agxybkbb.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2tvrzzjug.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2cjrhfqht.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gt2nbihwfbu.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2hrxvhulb.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2lcuhsrbz.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gt2trrcehmi.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gt2eyrsjmbq.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gt2zvrwrimo.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gt2qnhkxfnm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gt2zketuykf.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gt2etgxraiw.html

for x in a { print(x) }
来源：http://dali.bjfxy.top/Article/details/gt2gfosuvgw.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gt2awaumwyo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gt2dmaeqogf.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gt2tkidpclj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtkoncvn.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gt2tbrzsqlo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nptnvbts.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nakkqaak.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gt2figxmehn.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gt2qbdwhpph.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2voqzqyvx.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gt2deisvdhw.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wdhytqxb.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gt2mtwwgnck.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gt2xspjpcvc.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gt2xoewxfba.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gt2ggehlrtq.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gt2gcfrolru.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujojcvth.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2ndijfvio.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2reahhyrm.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2rclgpffy.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gt2itfykudg.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gt2mnzwjrof.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2scihxlok.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gt2zbdomymu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gt2fjaplpfo.html

[T35] Lua：字典表
来源：http://dali.vqdsnc.cn/Article/details/gt2ziegjskc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2onpyyruv.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gt2kpkbblwn.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gt2zxyovdfm.html

[T37] Lua：字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2ppfwcgts.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gt2wfbrkfkw.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gt2rddbpbca.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gt2klrkegfr.html

[T39] Lua：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gt2alxhslla.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2solakwhv.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gt2ploxppik.html

setmetatable({}, { __index = base })
来源：http://dali.nanxuanxn.top/Article/details/gt2yqtluxxd.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gt2fuomzlch.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gt2tesgmzce.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gt2futeomec.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnqzz.top/Article/details/gt2eecnmeoi.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2qszvqvrc.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gt2whthgghx.html

[T44] Perl：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mqaakbsm.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2vbwflipc.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gt2fbriuubi.html

for my $x (@arr) { print $x; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znbiwcgf.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcxqgdzg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwovuunl.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gt2eyhawcjk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gt2mrdtrwrc.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gt2vzpubtcp.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckzkvgqd.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gt2lkebrark.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2qbsyuhen.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2favhojjw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gt2ximbcrbh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2sncdinqj.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gt2updwtzri.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2yfwmwbib.html

[T52] Scala：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmeeqpls.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2tlkbjacj.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gt2oylvbyed.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2uzsxzbbq.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2ilceimgf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2upuvjafz.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gt2lzszqpee.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gt2wklwbjym.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gt2yckibqhs.html

case class User(name: String, age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2wpnfbdiu.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nnvchxyy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zphplzoa.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwliktiy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gt2icrsuagl.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gt2wzqnmtvx.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gt2wmnpwxvl.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2zjdsryde.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gt2ltmpubjv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2cewszkrc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gt2gdsjoize.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2ykkinrdv.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2selwnblb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gt2xrucwnoa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gt2kotfesnu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gt2rxenmeej.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gt2ikbiaqqf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwctuvef.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gt2wuqonbsy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dgbyygwa.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2essywadd.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otwtskij.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gt2rlznfwbc.html

{**a, **b}
来源：http://dali.haohaochexian.top/Article/details/gt2roffvixn.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gt2kmqwlzsi.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gt2wwdqzurh.html

[U08] Py：展平二维列表
来源：http://dali.guannengcc.top/Article/details/gt2jafpkulk.html

[y for x in nested for y in x]
来源：http://dali.zycfv.cn/Article/details/gt2vidbbhfu.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2jwbdjdst.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gt2pmdlcwmv.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gt2wymgqzbn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2dxfwqyes.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gt2ugfkybxl.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzdnguib.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cucudq.cn/Article/details/gt2fmzlvbol.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gt2qjqtkwsf.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gt2hslicjcl.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gt2eigaxiwn.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gt2cedpctja.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gt2dybsgjpd.html

[U15] Py：高精度计时
来源：http://dali.snrcjt.cn/Article/details/gt2vfeatqsv.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybxwvigj.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gt2olcufvlz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tian-w.cn/Article/details/gt2csfnthow.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gt2gyvqtkju.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gt2dorzirfb.html

[U18] Py：预编译正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqkohqdb.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2tqhbwvmu.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2ipwrmxfl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.0kj1m.cn/Article/details/gt2puldktoq.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkomhcsw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gt2zvpqcigv.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqppqiun.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gt2gopysccc.html

[U22] Py：矩阵转置
来源：http://dali.cucudq.cn/Article/details/gt2nlnrdcus.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gt2kobxqmhd.html

[U23] Py：分块读取大文件
来源：http://dali.guannengcc.top/Article/details/gt2gioxdwph.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gt2hyyyxazh.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gt2okjhkowm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdxbmwkz.html


<!-- 参考信息 -->