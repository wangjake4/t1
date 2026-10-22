代发 wailian999

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gt2kbbjhfvg.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2hlzakysz.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gt2jbwzqscn.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gt2hlwsyaxm.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gt2blxjucnf.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2bxxyifoz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gt2rwjkqzzr.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2aenaipbe.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2wbzvmzlo.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2dwgejiqg.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gt2wazyunhv.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gt2vxxkhohd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gt2kefcnlcy.html

[S08] C：动态内存分配与释放
来源：http://dali.sysykeji.top/Article/details/gt2bfylrneb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxpvcncv.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2viiifgop.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gt2mcivrwua.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2oniequwj.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gt2xxhclieq.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2jeavsauc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gt2hwsszlhn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2kvxslrsr.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhwekadz.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gt2rsqrwlcc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gt2omwzcjyp.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2qgdeqkxd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2aqzwrglf.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gt2uabydrwz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gt2wgnidzbf.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2oiskhboe.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gt2bppjvqtj.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gt2izkgdily.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwlzevep.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2hodqozof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gt2kdtgldea.html

[S18] C：命令行参数
来源：http://dali.zycfv.cn/Article/details/gt2eafkvxew.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gt2oagqxjzw.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gt2bfdtwnys.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2fkxgdral.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gt2egyylony.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gt2miyaerqp.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gt2ngsfaoki.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2yiaanqpo.html

[S22] C：字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gt2ornkwqzx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj202588.top/Article/details/gt2dprhugme.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gt2ugbmnmsh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gt2zekpkchc.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gt2obethosi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gt2inxzmnxm.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2zjzzgbbg.html

memcpy(dst, src, n);
来源：http://dali.hysaishi.cn/Article/details/gt2jeubcjdu.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gt2pljjrsvm.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owcwpezo.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gt2pmhzmlni.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2cqggzdcv.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gt2hgnzffsi.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gt2iszjybgf.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2ueuxwkcs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shzxlz.cn/Article/details/gt2wgpytcgk.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gt2nyzqpzqu.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oysiihsm.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsfkoxzr.html

#endif
来源：http://dali.aizwys.cn/Article/details/gt2jpuqqedd.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2vqbdoqmp.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2ukdtwtmi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ualdstcz.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gt2jhtxhgnp.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gt2ddxhyqhy.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gt2ysospddz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gt2gvbpoiwe.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gt2enyhaiou.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tianlin.xyz/Article/details/gt2tqwibdes.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eitjrhfu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2syxtbawz.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gt2cxjvvqyf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2nfyklmsk.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mswnmymv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gt2ackgwzxe.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gt2dzmilyzj.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2kestpvdc.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gt2atawigyu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2rogebfwa.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gt2wnsokgsu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gt2fabcciaw.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gt2fpwkcpsm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yangfankeji.com/Article/details/gt2tdfucpdz.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gt2kwptrnxk.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scrcbkxe.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gt2napvciop.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gt2bskrifcd.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gt2erpqujsy.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gt2lehodgme.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gt2rddfbmqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tianlin.xyz/Article/details/gt2ofoshikz.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gt2fqcfrarf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gt2idyjznxj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gt2mrglgbhh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gt2quhncqen.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2nbclwybk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gt2wjxrwwjb.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gt2lgymrikg.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gt2wrdudxba.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gt2rlugklbl.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2gxvajfrg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2enuhqlxo.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljtifdjw.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gt2rqmvnwbe.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gt2jdbevfdc.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2npydpsiu.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gt2odqepngv.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gt2cknlowvm.html

[S54] C++：异常处理
来源：http://dali.andypj.xyz/Article/details/gt2hbzdozab.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gt2uyniflyk.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gt2uzbxjylm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2hdpndsmh.html

[S56] C++：optional
来源：http://dali.redwolf501.top/Article/details/gt2asfjzsos.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sysykeji.top/Article/details/gt2qrerbpty.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gt2yxerdjxj.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gt2gobwodlq.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gt2xyiyxqkw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsbaeltz.html

[S59] C++：静态断言
来源：http://dali.nanxinkj.top/Article/details/gt2kdnejazl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gt2dkeyosrl.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gt2gzpqhzmt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2bnxmnuvg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2zpegjcub.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gt2klhqjfff.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2pttpgyeu.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2wgoysyan.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gt2fmeepdda.html

[T02] Kotlin：变量
来源：http://dali.9152youxi.cn/Article/details/gt2dvfwwgog.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gt2kgqiorqh.html

[T03] Kotlin：字符串模板
来源：http://dali.chenlongwang.top/Article/details/gt2wsuavngk.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gt2reefiwyc.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gt2lkntxutw.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gt2tbuqzoju.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2mnikqnkt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gt2djcwfzki.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gt2iohspdlg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2wpzqvqoi.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2sgcbgcib.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gt2iyhzhxoo.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gt2xcwsfupu.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gt2lohdxxfl.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gt2mrxgusho.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gt2fpfwhdhf.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2hxjogtqv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gt2pthucbex.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gt2yaskgukt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gt2oltcljdz.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2qwceyimg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubwilmbj.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gt2pcdaphae.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gt2bpoviukp.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2swebxyzc.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2xavprejf.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2eqvnhfah.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2nonnvwap.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gt2tzxumyvh.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2jvfyvwgm.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gt2sokrcpvf.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gt2ogvhkver.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2yirgiczd.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gt2rtannkii.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gt2xlogxizn.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gt2kddtvegy.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gt2rccrhvnk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwzwridh.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gt2zbvgqufk.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gt2xjyhimmx.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gt2ryvmewlu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2ycivpyqh.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gt2fnbyulkr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gt2aitspllv.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2qkliiyai.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjpfzkcv.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njatqfre.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2fobwlqek.html

[T26] Swift：类与重写
来源：http://dali.daxiang520.top/Article/details/gt2emwvcrdu.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2uutjbvfw.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2stfemohm.html

do { try f() } catch { print(error) }
来源：http://dali.jqgufenzy.top/Article/details/gt2oiusdjth.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gt2aphwuanr.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gt2mpfueltf.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gt2zttxobec.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gt2wdnibwvn.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gt2ekjyoyul.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzhvolix.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brkttwyq.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gt2qanmoyof.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2jkorrfme.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gt2pzfmfbid.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gt2fpvjlgek.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttntpaqx.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gt2vveobiik.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yvhbvhqn.html

[T35] Lua：字典表
来源：http://dali.iojbl.cn/Article/details/gt2xyecwhyj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2yibtuaax.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2mhlgnbxy.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gt2wsobbddg.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2tigyupoj.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2pnekxyil.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gt2cxgvzext.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrxglvyk.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2kztcnsse.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2yowphncx.html

[T40] Lua：元表
来源：http://dali.jlsjyb.cn/Article/details/gt2mwxrfjdy.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2glqqesmd.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhikteye.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gt2regesfhf.html

[T42] Perl：变量类型
来源：http://dali.yueranfly.top/Article/details/gt2napfcwaw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gt2vuyjprts.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2njqdqfdu.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gt2ttaldspt.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gt2iznwebjn.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sucdoxlm.html

[T45] Perl：数组遍历
来源：http://dali.gzhubu.top/Article/details/gt2gnxyivqh.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gt2euoqoruu.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gt2iahocmtg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gt2haqxirvz.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lywdjbcw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gt2cmjmztej.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgnsfutr.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2ezpnpwog.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gt2ojnimmfv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2vkljniws.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2rzhhtcqj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gaohongyu789.top/Article/details/gt2uoonzuiq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mfeifhfg.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2qlcopwnu.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnmnviab.html

[T52] Scala：变量
来源：http://dali.c1oappe.top/Article/details/gt2xlluohet.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2pznvdgds.html

[T53] Scala：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2vrzypapj.html

s"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2zzoknqae.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gt2hcapkkhz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mhbnaqpf.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gt2fhzddxod.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gt2byibilet.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2tkhddneu.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gt2wadnqtxi.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gt2idvrtkal.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2gwvpmllr.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rcrkdlmc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2fhrjyogo.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gt2wjnppjtm.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2jbeqargm.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gt2wgndlklt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gt2qgjamgru.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hdihgqfw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gt2ftaymenx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2gejegxjo.html

[U01] Py：创建虚拟环境
来源：http://dali.yuanzhike.top/Article/details/gt2xwdhjpak.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gt2ijjgqxuu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shuidangran.top/Article/details/gt2ybmskfqn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gt2iddnuvgg.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gt2cfhmuvpf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gt2wpjccdqr.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gt2gdyjddoz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gt2xjokusqy.html

[U05] Py：列表去重且保序
来源：http://dali.cheryme.top/Article/details/gt2pwznqcqu.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilxdgsjw.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gt2mbuvsebf.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gt2cmijvuhn.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gt2bzwklwtu.html

{v: k for k, v in d.items()}
来源：http://dali.gotoacloud.top/Article/details/gt2nuvlvril.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gt2gauktqnt.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gt2himrianw.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gt2mimvmiza.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gt2gciaxvzm.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gt2qdigcfgo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gt2ocwjicim.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gt2jptlhdux.html

(x * 2 for x in arr)
来源：http://dali.sufxvd.cn/Article/details/gt2rujqvubk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xinyue.icu/Article/details/gt2xahmewnm.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gt2lldjqefa.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gt2ssmcklet.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gt2jsywozal.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gt2kcvnitde.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gt2pjgleygs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxwvspa.html

t = time.perf_counter()
来源：http://dali.gotoacloud.top/Article/details/gt2musfjhbf.html

[U16] Py：命令行参数解析
来源：http://dali.xylfe.cn/Article/details/gt2ktxblaql.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yonumen.top/Article/details/gt2jvtkwhkj.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gt2zvytwhkw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gt2racgnzjf.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gt2hkirtcot.html

pat = re.compile(r"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2jdgxlman.html

[U19] Py：正则替换带回调
来源：http://dali.hnqzz.top/Article/details/gt2tapauqpf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gt2qvycyogt.html

[U20] Py：缓存函数结果
来源：http://dali.gotoacloud.top/Article/details/gt2aksriofm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gt2lszsqthb.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gt2pnhlwmxi.html

@contextlib.contextmanager
来源：http://dali.yj20258888.top/Article/details/gt2tbbqpilp.html

[U22] Py：矩阵转置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzzarlxt.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvysmeoh.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gt2vytsgero.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luvbquyg.html

[U24] Py：路径操作
来源：http://dali.jianghu66.top/Article/details/gt2evptmhbx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oayreyik.html


<!-- 参考信息 -->