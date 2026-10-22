代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gt2xnuzwsxw.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gt2igkmqcju.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2orgxhixk.html

[S03] C：读入整数
来源：http://dali.quarkkingdee.top/Article/details/gt2wogwjcly.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2jtnbejdn.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gt2awpavcrk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gt2cfsshlaj.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gt2opyseenc.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gt2iagtmeya.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2brlsaifj.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gt2dfoaveqw.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2hugrstbd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gt2pcrpfowv.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gt2bxdyqdvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjkanmgy.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gt2fvuackuv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gt2yjawnsrh.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gt2ugxxjvvj.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gt2zrdezjmw.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2yqsjwydn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hammf.cn/Article/details/gt2zvypmaro.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2ehtaognk.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2hxnjltyr.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gt2ssvyvsxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gt2zdijhadh.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyjqulvp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2ozbwoesq.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2lvqkfpls.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gt2uzrcpnig.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2hypzyeqj.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gt2xxhqriuv.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2vrqomdrr.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gt2njtpkxth.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2atyczrlq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gt2eopmdyvb.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2xospxsdw.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gt2ajfncnpc.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gt2gyklkvxw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2tfnaprgr.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gt2plspipdt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nwknuklk.html

[S21] C：字符类别判断
来源：http://dali.gotoacloud.top/Article/details/gt2feyoptvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2qnagobnl.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2nodqswox.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gotoacloud.top/Article/details/gt2fnsdpfdd.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gt2yioatzgi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gt2fbflnjsk.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gt2hbmzbcnw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gt2uwuhtucc.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gt2dwfyiukm.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqaopjwz.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gt2btxckyou.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2guxvcnfk.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gt2iooecluk.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2acmpgssq.html

[S28] C：静态变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhtatdqu.html

static int counter = 0;
来源：http://dali.haohaochexian.top/Article/details/gt2sxhnzgtx.html

[S29] C：变参函数
来源：http://dali.meibo888.top/Article/details/gt2xtmpwors.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gt2efnsfwiw.html

[S30] C：头文件保护
来源：http://dali.jinqigfzy.top/Article/details/gt2trupyacm.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gt2vwrbsigu.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gt2ogxyisop.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2upcdloig.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2sptlbtkp.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gt2cwkoatca.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2qdpwjnwy.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2kamstwix.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gt2rvqhlrle.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gt2fvhnnbxx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuanzx.com/Article/details/gt2dyasshtp.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gt2rsudjpcr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2rawfhdzj.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2vuyvojge.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2puarhles.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmjovsjy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2qubkjygq.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gt2ehnacrbu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.smart0.xyz/Article/details/gt2tzfqjqgd.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gt2faceiswf.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2kzjjbtjl.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gt2dklnzscv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gt2ruyjmijn.html

[S40] C++：查找元素
来源：http://dali.zycfv.cn/Article/details/gt2lrnnhaea.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gt2gsucltlf.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gt2zfriiwpc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gt2mnebdrrq.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2lahowcwd.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gt2qvdzjiyu.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gt2cchbbbqm.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2rggdyjel.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gt2wfwptinn.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sisjvxvu.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gt2piwczxrg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gt2olypgzcn.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gt2nbmdkeag.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kykfxgfu.html

[S47] C++：结构化绑定遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2sdbfgibn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gt2jvnlnwmx.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqtipbmm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.c1oappe.top/Article/details/gt2jahvwozz.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swlmhqol.html

[S49] C++：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2cuoqynzu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2mozfghtn.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2tfiruypk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2xrnvlrcb.html

[S51] C++：显式类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2kuglhkzg.html

static_cast<double>(a) / b
来源：http://dali.yuanzhike.top/Article/details/gt2paoxhrxb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gt2gatmpjmf.html

int size() const noexcept { return n_; }
来源：http://dali.andypj.xyz/Article/details/gt2dhxnutqm.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gt2wnlytevy.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gt2ydfdithz.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gt2llzgsaos.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yuupugzu.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gt2iiqagadq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gt2ossyoleb.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gt2qiufzouf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gt2jitalwvh.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gt2pdbbjdqx.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2mkjqdjvd.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gt2paclxfyu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gt2fjoihhfi.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2pxdgqepo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gt2hothkscw.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2aablilbh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gt2iwiwvoha.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ihvayxyv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gt2cmtlpxfl.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2iovgsach.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2anejzqkf.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2tkbjbzyi.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gt2pridlipd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gt2bqfornus.html

[T03] Kotlin：字符串模板
来源：http://dali.xylfe.cn/Article/details/gt2ltwxphba.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gt2wgftzxyt.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gt2dnzzrqaq.html

val n: String? = null;  n?.length
来源：http://dali.yonumen.top/Article/details/gt2bpxqycnd.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gt2kcgzlwig.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzfibfwi.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gt2rlhxlusk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2myofosjh.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2ahvycmlf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2vhuqhxrx.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2cgqkhucy.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2dfhsamao.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gt2zxaxaiuw.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gt2afyberwd.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgwngvnw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nbmcqwog.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gt2xyddeezs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2typgupna.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gt2thrsdibj.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2vaeybrmx.html

[T13] Kotlin：只读 Map
来源：http://dali.cheryme.top/Article/details/gt2zfagkfgt.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxpegiwz.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gt2qynncrdi.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gt2iudpacfg.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2fetrncur.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gt2nqpcuzte.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2johtnfhb.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2nfaskvqp.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gt2rhbkoear.html

var a = 1;  let b = 2
来源：http://dali.aizwys.cn/Article/details/gt2uulryxbj.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2giiyspos.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjisecwh.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gt2xcthwhoi.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gt2odnnjsfd.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gt2lporzhbw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2ndqlbuax.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gt2dxcnnqbm.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gt2neuluycw.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2qvloicil.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gt2zwitvobo.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2biilytdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gt2odksuflr.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2vbtygaxd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2eppooatw.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2tzgwmpko.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gt2yndzjjas.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gt2xmwviglp.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2jjiwakiz.html

[T27] Swift：错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2ukmqequr.html

do { try f() } catch { print(error) }
来源：http://dali.kuanghao11.cn/Article/details/gt2xhqmhfjd.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gt2tlvervgc.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gt2smjxpccb.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gt2ppbtdvgo.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gt2scqgizme.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gt2onhmtwqi.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnakdwev.html

[T31] Lua：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2bcdlppue.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkxrqgbl.html

[T32] Lua：局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2mkfvtble.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2xanbopge.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2bxnujjun.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlhvbgbp.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gt2dspgrvad.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gt2iwvjwnaj.html

[T35] Lua：字典表
来源：http://dali.cqqwz.cn/Article/details/gt2olacwqvt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.andypj.xyz/Article/details/gt2ewtteaoj.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2iytcvzcu.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2nxpkkqnt.html

[T37] Lua：字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjcsoegh.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gt2jhfbfnym.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gt2wstccotx.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gt2cqaqqtau.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gt2wkrnpbpo.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gt2kkrsvcts.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2oxwdhwgg.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gt2vhzppycp.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gt2lmttmnri.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gt2agxkhciv.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gt2wrznmhdt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gt2wibntjcu.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2ychgcobw.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gt2tunfbjtj.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gt2genmxllg.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gt2sewqzepn.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gt2eazmubar.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxmeschx.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gt2mjrpwkzb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2cbubvjrf.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gt2cmysaqaz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gt2nzruvarq.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gt2kevahyew.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gt2nvawydbr.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gt2jkaolxqs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytsfgtht.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2cwayafpb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gt2ondnjjbp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gt2ohwfrgly.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2jmllcpoi.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gt2knzoempk.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gt2pdqvwwyw.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gt2gnbusmkm.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2owmbiyfc.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2zbdkzytm.html

[T54] Scala：集合映射
来源：http://dali.tian-w.cn/Article/details/gt2lykzvehs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gotoacloud.top/Article/details/gt2zzasjqty.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2vclectxr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gt2bgbabhzu.html

[T56] Scala：样例类
来源：http://dali.jqgfzy.top/Article/details/gt2hccfrfml.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2tiyoffud.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2sknqbiku.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2bxgmyaft.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gt2oxlorbby.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxbwqtye.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gt2rjbrucev.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2deogtxee.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gt2zepfrtyr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kpqqyiyn.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2rpncdidi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gt2mxcvxdbp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wsfpvyfa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uawxmgro.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.0kj1m.cn/Article/details/gt2rjkhofdv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gt2izqbsruz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvjqqfch.html

[U03] Py：加载 .env 配置
来源：http://dali.hfpthk.cn/Article/details/gt2jttncina.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gt2ncckppws.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayqlvvjo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gt2uihqplaf.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gt2hwppwvtl.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2ssrrivly.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gt2hlqnnhka.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gt2uruwecdo.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gt2xygmzmyr.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2wunjkjeo.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gt2vxldsnwd.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gt2czhfzicu.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gt2buesisro.html

max(d, key=d.get)
来源：http://dali.zhengqikj.top/Article/details/gt2wiwoqeeq.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gt2dgahvzsi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hysaishi.cn/Article/details/gt2crojpags.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gt2arlsqkix.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gt2xmwelwpq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zdqjudy.top/Article/details/gt2ozovjjgd.html

Counter(arr).most_common(3)
来源：http://dali.9152youxi.cn/Article/details/gt2xkeiibam.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gt2ibixlhut.html

deque(maxlen=10)
来源：http://dali.daxiang520.top/Article/details/gt2awqymjmo.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gt2xgxmycps.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2veftzhah.html

[U15] Py：高精度计时
来源：http://dali.shangyingyoupin.top/Article/details/gt2bddauisi.html

t = time.perf_counter()
来源：http://dali.yuxming.cn/Article/details/gt2uqdedthq.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gt2jbpzdlaz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gt2rhonlgsa.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmwtnlyu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gt2lmpcmzbx.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gt2ulxsleex.html

pat = re.compile(r"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2whjpytsh.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gt2wlluhgdo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wushvydd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2syvjamlj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gt2zbkqsoml.html

[U21] Py：自定义上下文管理器
来源：http://dali.andypj.xyz/Article/details/gt2lfdtxbwu.html

@contextlib.contextmanager
来源：http://dali.gogol.net.cn/Article/details/gt2ryhfksmz.html

[U22] Py：矩阵转置
来源：http://dali.iojbl.cn/Article/details/gt2lhedjkxl.html

list(zip(*m))
来源：http://dali.jqgfzy.top/Article/details/gt2jwlkbqkz.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gt2efpcvpic.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwbfdlnc.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gt2qmwxefjo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2hjcglrye.html


<!-- 参考信息 -->