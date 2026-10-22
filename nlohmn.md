代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtpjaffmft.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtfjzycznf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtqupadtej.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtjxhtjgwo.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtsrqaujgg.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtpudefube.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jlsjyb.cn/Article/details/gtxfwfdcgh.html

[R79] 解析命令行选项
来源：http://dali.andypj.xyz/Article/details/gtfeplczsv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtwkhgqzkx.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtpvzmftcs.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtamshfpcg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgevvcvsb.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gthpytcesz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxzgzhesv.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfrzxpvj.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gtnyefrbja.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtsavbbfcv.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpukbrrh.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtgglqqqio.html

[S03] C：读入整数
来源：http://dali.aizwys.cn/Article/details/gteyuwiwri.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gtvgurjmqi.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gthoqmceeu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtvzwmlnxg.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtthjibbvr.html

strlen(s)
来源：http://dali.jinqigufen.top/Article/details/gtgoxughrm.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gtexdshefb.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtddijbhgo.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtkcoocrpb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtxffcftbt.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtqjaqxzgf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtcxnvanew.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtklguxdgu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sweek.top/Article/details/gtnttmnzuu.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtycnqbcwu.html

int *p = &a;  *p = 5;
来源：http://dali.ehwqpu.com/Article/details/gtgjvwzdjd.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtwoumdrzs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtlhdcvizr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtseudmpoz.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtzkupkecq.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtwwdhhnsu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtafuszwqw.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtshuobamf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gtoebtomfl.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gtiupmiegy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtigxyogvi.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtrujvcccy.html

(double) a / b
来源：http://dali.c1oappe.top/Article/details/gtubrxugmc.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtzjrbyces.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gtujldgilb.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtdbmotfhy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtvgvtxjyl.html

[S18] C：命令行参数
来源：http://dali.ybcxt.top/Article/details/gtaoxhiqwp.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtzbyifogk.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtkvqmoeai.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtviyhxedu.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtzrxkhnbs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtjbkukyaq.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtwbudxdpi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtzqpshsxb.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtnogyrfji.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtcgbcubyd.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtklhtiqof.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtdhtwqbvg.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtadusmimk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtzqlzxotv.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtcjeuzvqg.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtuklajacg.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtfxuwltob.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gtzjosolpp.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gtujmpivru.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtisiwfqwe.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtsjyradrq.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtrukpfrvv.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gteczaxvlg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.redwolf501.top/Article/details/gtxsyqazfj.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gtxnslelpj.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gttgloeacs.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtewizdusu.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtzwekzist.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtvzyxezaq.html

#include <iostream>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpdkvjcz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtylvcqias.html

[S32] C++：字符串
来源：http://dali.sweek.top/Article/details/gtjtaumknx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtdgswwxfc.html

[S33] C++：vector 增删
来源：http://dali.sweek.top/Article/details/gtevpfnoau.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtobsxciza.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gtzddetweo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guowangkeji.top/Article/details/gtfwanuuuf.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtrrbqcohe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtmluyjsho.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtjddsgwre.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtdbefdxwg.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtgzwolceb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jyoumei.cn/Article/details/gtokemyjiw.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtzirgqxpe.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtgwsqqbrs.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtbvfukjhs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsralayy.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gtgksnaauj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtymzvlule.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtopmpuahc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gtkuawmqex.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjixwopvb.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtbipfowvs.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gtnabzkqya.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtwjxogwkl.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtkntwixpk.html

void inc(int &x) { ++x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvumjmffo.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtwlbzcsbo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtkcyzvfuy.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtmzjzaatd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtithcxlgf.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtuklgtqsm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtruosvhkj.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtvkvdwonp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtazspvfhu.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtmlfuziou.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtisdealia.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtmohnkjib.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtpacntjmu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtbdwlihph.html

[S51] C++：显式类型转换
来源：http://dali.svipenyu.cn/Article/details/gtlgihgiwh.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gteozuhmeh.html

[S52] C++：const 与 noexcept
来源：http://dali.hywenlv.cn/Article/details/gterhdlbgu.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtzdfwjnzs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtjokgabse.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gttubbpoir.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtzaopfgkf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gteswrjiyh.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtollqoefy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gttiuzustg.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtifplqlmh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gtorleuqas.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtshlexuem.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gttzllkdcb.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtabseljvr.html

namespace ns { int f() { return 1; } }
来源：http://dali.svipenyu.cn/Article/details/gtapwopawg.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gtzaosgays.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtooziwmte.html

[S60] C++：遍历并删除元素
来源：http://dali.jyoumei.cn/Article/details/gtaiyqfuua.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtpvhdggen.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvyiqlafn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtquzmyipz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmmgnnydy.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gttehnzkfv.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtfowqfxgl.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gtslpedbpz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtpweotrko.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gtqpnfqbys.html

"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtyluubwqw.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtoyytcswo.html

val n: String? = null;  n?.length
来源：http://dali.chenjidiqi.icu/Article/details/gtojibiuef.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gtzyqhvdla.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtbbciwyvi.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gthtomtqrb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gttlmhuxmm.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtnoxsdwms.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtkdjxzbdp.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gtnobafeep.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gttyrhpjes.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtoubphvfn.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtuezrpnuv.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtbcvgicfv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtireeewwi.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gtwwlzyexp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtqqrsecjf.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtzfrsssxh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmedhwfoi.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gtupxslzrn.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtwvsfvxzr.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtfzmqhisw.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtzvfmciwo.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtsxzrnfmh.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gtscylnkyp.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtjklllfqx.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyuscihy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtpsdvzemb.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtyqorezhd.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtkgtdfjqm.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtmfzmdfcx.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtzbjjhscr.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gtuifgvkjn.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtfgrvstoe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtqknheqih.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtbmxkhhke.html

for x in a { print(x) }
来源：http://dali.cashguo.top/Article/details/gtnrbywmfd.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtekvihpkp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guannengcc.top/Article/details/gtcxvddlds.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gtqaivmqtg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtntrbggjx.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmsjprdf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtzriwzhwj.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtjdqorfio.html

struct P { var x: Int }
来源：http://dali.havefunace.top/Article/details/gtnwuxiwma.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtmvmmbulz.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gtbuldghxi.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gtotroufqb.html

do { try f() } catch { print(error) }
来源：http://dali.jianghu66.top/Article/details/gtqberhbhh.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtwtagdzlq.html

enum Color { case red, green }
来源：http://dali.dashuyun.cn/Article/details/gthunblrww.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtgafniptm.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtagznlydj.html

[T30] Swift：协议
来源：http://dali.zdqjudy.top/Article/details/gtjtmyraxl.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtgbanoweo.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gthksgeaml.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtawcwkmky.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtwmztelni.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtaqzaazpg.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtowjifnhs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgrhfwix.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gttkwcgncs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtuxjytugt.html

[T35] Lua：字典表
来源：http://dali.yuxming.cn/Article/details/gtzaseyypl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtlmffppke.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtzxafnxxc.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtzjhfnrtc.html

[T37] Lua：字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gttbbfamio.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtntezazqp.html

[T38] Lua：条件
来源：http://dali.gogol.net.cn/Article/details/gtfcgjsvxx.html

if x > 0 then print("正") end
来源：http://dali.aibaodan.cn/Article/details/gtfobcdxvv.html

[T39] Lua：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtrjcvnwam.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtpttiwupe.html

[T40] Lua：元表
来源：http://dali.chenjidiqi.icu/Article/details/gtkhbghllr.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258.top/Article/details/gtbnergieq.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtxszihkon.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gttzbfvowy.html

[T42] Perl：变量类型
来源：http://dali.yj20258.top/Article/details/gtqpkkryeo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gtnwzwqqcx.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtzngyfkba.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtaunimpxu.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtrjnhaxtj.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtrekcacea.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gtcylroczo.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtqwikcade.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gthhzzdycd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbgalxbw.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtqqejvarl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafosznnl.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtkcdrqgej.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtbhhxlqtf.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtkendsxjh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtmpvajrxi.html

[T50] Perl：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopmaiskr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtjuidgfal.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.dashuyun.cn/Article/details/gtrzsdrxas.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtkbappyvc.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtyukiswsv.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gtkvphlvey.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gtkbbgafki.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtizyxptld.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtltypapfp.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtqfnokwvr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtbngxminb.html

[T55] Scala：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtzpiutkcd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gtytipmeud.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gttvrewiwu.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtktolwbxe.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gtjlmudqxk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtwniubbnq.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gtpvftnbme.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gtaxvfkqcz.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtkjhpassb.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtwumnetil.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gtbfmhhxpo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgfimrpb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthhdczxmu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sysykeji.top/Article/details/gtftxjlayq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtshkqik.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gteryfvong.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtcnvdkfyu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtcaceaklq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gttfcxexjf.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gtzhoyvrvo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gtrsxfrvxm.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gttvqgljxr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtxnfgzccl.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gtongirbvw.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtvhjcfykj.html

[U06] Py：合并两个字典
来源：http://dali.cqqwz.cn/Article/details/gtirvudjno.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gtdpghkjgl.html

[U07] Py：反转字典键值
来源：http://dali.zhongyouzk.top/Article/details/gtrviileta.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gtzewsztqi.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtkpllaxoq.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gtkpbuzvah.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtagbsycsv.html

max(d, key=d.get)
来源：http://dali.iojbl.cn/Article/details/gtfhzjzest.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtupsramnv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gtgmfuofeq.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaexovjya.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtpgcshmyt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtbriaeard.html

Counter(arr).most_common(3)
来源：http://dali.zhongyouzk.top/Article/details/gtghqiueuv.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gtzujfgbdm.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouzsetok.html

[U14] Py：分组收集到列表
来源：http://dali.cashguo.top/Article/details/gththlpahj.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtumrlplku.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtnagssqzc.html

t = time.perf_counter()
来源：http://dali.snrcjt.cn/Article/details/gtqmoxndyh.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtafzfdzul.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gtpcrvdzni.html


<!-- 参考信息 -->