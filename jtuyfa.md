代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2geayysdg.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2keuyiewt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsmzchf.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2csejktcd.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gt2ndnsecnm.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gt2hwforsve.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gt2uvivbjiv.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2benfboii.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gt2lujtopti.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gt2gcqpczmk.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2qklawivq.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gt2yytzczcl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2qptgxqrh.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gt2whrasrrh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gt2kzaayqwa.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frtfwkis.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gt2dzarbwzj.html

[S10] C：指针与解引用
来源：http://dali.hysaishi.cn/Article/details/gt2qtkeakwx.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gt2mlodwcew.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2bbhzsien.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gt2voemqouz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2xsfexnhh.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2hdrejfis.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gt2luejzckr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2tlkyqoaa.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2srgkahuq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.daria6918.cn/Article/details/gt2ixguvvvg.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gt2nwkxtjjt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gt2ykhjikes.html

[S15] C：类型转换
来源：http://dali.tian-w.cn/Article/details/gt2wsdhuygf.html

(double) a / b
来源：http://dali.yvedp.cn/Article/details/gt2hcnvunxb.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gt2wkryznde.html

x |= (1 << 3);
来源：http://dali.tianlin.xyz/Article/details/gt2oyelhskt.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gt2sjsqtjjf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjuwtmrd.html

[S18] C：命令行参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ljvexvqr.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gt2dknheksw.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gt2mtpkakje.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qaflpgar.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gt2ilpodkpm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2hardslfh.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2ldhdgbli.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gt2gabyaljc.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2ldupdhyg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2woepsbdc.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gt2gsciegvs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyddeohd.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gt2nffjwwnd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gt2vzbbltyc.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gt2bkqylgjx.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gt2qnxukigu.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktsllbog.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gt2zpffjyhb.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gt2aryopvpr.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2pcrsqlrw.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxvsyrxg.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gt2juhxnbzs.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gt2nlgyqkuz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpelohvg.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gt2gzrjnzsf.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gt2nmzvmlwc.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gt2vhqruffc.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gt2yxgbitdf.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2csiputrx.html

#include <iostream>
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzxhamtq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gt2mpbejfoz.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gt2sytitfff.html

std::string s = "hi";  s += "!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwqcdlqe.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gt2ymjgqpsf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj202588.top/Article/details/gt2pktvndye.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gt2cjwwtrhg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gt2vkobysgg.html

[S35] C++：map
来源：http://dali.gaohongyu789.top/Article/details/gt2bqcwmmmj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2eehsrxrv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlqutiy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjdxxdqk.html

[S37] C++：set
来源：http://dali.nanxinkj.top/Article/details/gt2smyrsuxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gt2esuqgbmm.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwldlysp.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gt2ikfwwdyt.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2eojcsubp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gt2cfyejdga.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gt2uncnpzjj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gt2klraddpm.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2thubhtrr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gt2zchtsiaq.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gt2udfnygue.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnxiangtu.top/Article/details/gt2gnqskzub.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gt2easyeave.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgfzy.top/Article/details/gt2cbibvnsm.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2akjpjxza.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gt2ajjzwmty.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gt2vidjraur.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2urujkasb.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbjlfves.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buowlalh.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbubllcn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2trikatkg.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itdhyklz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2ibmbtwqf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiucgej.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2rjgqrygr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gt2stjetwtr.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gt2xhqmawip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2lqnjjtsl.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2bzrzhvme.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gt2rkxsfeoq.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gt2twroseia.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gt2qzdeajoq.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gt2aemxrdld.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gt2kbzqpjay.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gt2frydetgu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gt2mnbawydp.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2mtieusqj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gt2qpzbhksr.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gt2ujbwowww.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gt2mpgtvcxg.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gt2mwujfmrj.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2zzsztual.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gt2wkmuqpzm.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gt2bnvqiisw.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gt2nxaemkso.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gt2vyzvroir.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gt2pgnrmfcr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qbesohso.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2xaxflcmh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2cfxgglch.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2nmpeeyfv.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2lyvgqjqq.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbwqnsra.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gt2hgfbnsos.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bhobwkbo.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gt2tackhhvf.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gt2phjsviov.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gt2xefhtxzq.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gt2lpmbdlpo.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2jwkweesg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.vqdsnc.cn/Article/details/gt2tmltfaom.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gt2ojbucnba.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2uzgimvxm.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2nqmxqgks.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gt2hpawooue.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2nfoxcebx.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gt2ydulavgo.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gt2srnrezjc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2actkqfah.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgjhjywq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2eakqfnob.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gt2vrjuguni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gt2bhiabkqx.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2podevfrh.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2jzndyhoz.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gt2vfmpglxf.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gt2nenxtyab.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gt2pppswzow.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2sznukhvt.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gt2uwsfagpp.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gt2ykupffwc.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gt2tshfhpnt.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2ovzpgvvu.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gt2iblcnifl.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2zknbakqi.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2jeoilfai.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gt2hkindymr.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2njxqeena.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2ohsbquut.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2hpfoyjfn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gt2zacbjjiv.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gt2upppaslp.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dppqzudl.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gt2dattizsi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gt2hfewadoj.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gt2satkmxyy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2lwyifovr.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2vsbgkxvq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2ixlbrfjs.html

[T25] Swift：结构体
来源：http://dali.jyoumei.cn/Article/details/gt2pdzdvkuc.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gt2syvgimep.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2pgdnemeh.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gt2arqbqetz.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2mimfggmz.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gt2dxaeijhi.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2gwmqsvqx.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gt2rkyloskh.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigufen.top/Article/details/gt2boqogmaw.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2usdkqwhl.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gt2lxcbbkcw.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2hdgkzyyr.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2ebpbpblq.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gt2bpsatdxl.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2nxsppwmg.html

local a = 1
来源：http://dali.9152youxi.cn/Article/details/gt2roiqdyuk.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqnisaik.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gt2ffinscvv.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gt2edjhwgbv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gt2pfrltlao.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gt2xevqmwwt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gt2xahcogyj.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gt2bpzoogvl.html

function add(a, b) return a + b end
来源：http://dali.jyoumei.cn/Article/details/gt2kbryrdoy.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gt2psqmglkx.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gt2dbbigsgv.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gt2mskqqbyg.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqrdfabr.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmkkfhwv.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gt2eavtkjmr.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gt2vcfvxqfd.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqmbzuaa.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2teaxxrvm.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gt2noemuqfk.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gt2ciwznrtn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2hwtizqzo.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gt2alppljdn.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2hxlmluuy.html

[T44] Perl：条件
来源：http://dali.zhengqikj.top/Article/details/gt2pgfwlchv.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nigrembi.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gt2etnfkvjg.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2gpdduyrg.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gt2vxmaincq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gt2lirphuvj.html

[T47] Perl：正则捕获
来源：http://dali.mhx1999.top/Article/details/gt2uevnoeep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gt2zqiecyfh.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2pjkddjno.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gt2kuutsrrl.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnhroaxp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2jytqzyya.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2ormzsith.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gt2rlrdmleb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gt2hyktgmgd.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2wmhgamww.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2wxkdqiqi.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2miuycmdk.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gt2yyqrezpe.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2agjcybhh.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gt2vzhgywip.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2zteathza.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gt2kvnopodx.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gt2tyfcpbgj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gt2htdbnnps.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gt2swfjxthm.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2foolofuq.html

[T57] Scala：模式匹配
来源：http://dali.daria6918.cn/Article/details/gt2jijmlztr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gt2hkltoiun.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2luhdlstu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkwqbqkd.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2kbdstutm.html

for (i <- 1 to 10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gt2ybzdyjst.html

[T60] Scala：折叠
来源：http://dali.sweek.top/Article/details/gt2whixltuw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eeacozze.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2qtaqftlw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2csxvbhze.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rxpouhct.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2rgtfwdgq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gt2boidxcmm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gt2eosuejtj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2wstbmwwq.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigfzy.top/Article/details/gt2zdxvrpxr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gt2sqnibofn.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gt2uylaqsrd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2gqzhwmeq.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gt2phycexrq.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gt2phtkecuw.html

[U06] Py：合并两个字典
来源：http://dali.cqqwz.cn/Article/details/gt2dtzdqhjp.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gt2rjdcmfvs.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2irxzlhpn.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2vgghnkpp.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gt2vtqlzshq.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gt2ytejqolj.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gt2ikdwdlnn.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gt2znvitjxb.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gt2fhgsascg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gt2kpgsbdan.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbposyqh.html

(x * 2 for x in arr)
来源：http://dali.guowangkeji.top/Article/details/gt2zeyjcgor.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gt2yhlslpeq.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gt2xteaxltd.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gt2vtmqhhed.html

deque(maxlen=10)
来源：http://dali.yueranfly.top/Article/details/gt2mhrklvas.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gt2qnaxkmkq.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gt2axqammhy.html

[U15] Py：高精度计时
来源：http://dali.yonumen.top/Article/details/gt2mfpechfy.html

t = time.perf_counter()
来源：http://dali.hywenlv.cn/Article/details/gt2wvsuqjok.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gt2jthpotrl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gt2khxgnnox.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gt2tezqyxzc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwzohpe.html

[U18] Py：预编译正则
来源：http://dali.xinyue.icu/Article/details/gt2jaasiuit.html

pat = re.compile(r"\d+")
来源：http://dali.fzhhl.top/Article/details/gt2amusziwp.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gt2iktfiqdv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gt2pbjvzjff.html

[U20] Py：缓存函数结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isilrxma.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdrsvofh.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gt2xzlxramo.html

@contextlib.contextmanager
来源：http://dali.hnxiangtu.top/Article/details/gt2zozkvhal.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gt2hyzkbltb.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gt2cmzcczyj.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsgodnhn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gt2iiqublqg.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gt2yiubsbuw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnwjknkl.html


<!-- 参考信息 -->