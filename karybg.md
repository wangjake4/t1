代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtqkhhbpus.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtxbqewled.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtbhiwzige.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtuyossuhe.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtoldrnyge.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtjqtqimkb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gthznknkcm.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gthftjzfty.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtbzaavrym.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtsjbmtaew.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtrioptzxd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtmejkmfsa.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gthfshmgqd.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvcjbleat.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdmilijqu.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtjhxilxuu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gtpefynent.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtugwsygox.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtnyqxvxsx.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtuupwmxco.html

int x; scanf("%d", &x);
来源：http://dali.sweek.top/Article/details/gtjhlmaozu.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtuztkfmdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtdxrfhiwb.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwahgklci.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gttgbffzly.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtcmowejlp.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gtxastigas.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gtckofqfsf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gthcikkaph.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gthaargeda.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.c1oappe.top/Article/details/gttjiaozim.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigfzy.top/Article/details/gtririokyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtwojklvvv.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtqavriddo.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtpkxlfwxl.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtwtssueyy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.havefunace.top/Article/details/gtogbzlzwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtovnqnega.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtgynhlgvw.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtwlfdqewr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtqfecyaao.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtpravkstt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yongpay.top/Article/details/gtpcwhfkdz.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtgisdgaoy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtvixsojiu.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuappgvt.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtwctckxqw.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtfmnglbym.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtocubtdzk.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtxpuvacdt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtqdqjsndd.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtfubkulor.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtgefkynhy.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtspkmjjhs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gtushetpip.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtxaogrjsd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnajkaqy.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtsjckvjwf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtdqulbzbr.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtmfdtlfym.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtehyfxupe.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gttqhnvulr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtwyilpzed.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtjlhmofth.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrwpeqoh.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtujqvxvgd.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtfiixhxri.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtdpmuwlha.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtefsfesbd.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtbtnczibr.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtqrxghezv.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gteqbsgklp.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtrrzgokyh.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtylzombhq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtkfyfzfhb.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtjqusdmoe.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gtooeqbexj.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtzppwsfmt.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtoyrmpofa.html

[S31] C++：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoskgytyi.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtfihsvoio.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtakiazona.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtgodsveot.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtnpfoozay.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwtoencp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tianlin.xyz/Article/details/gtirrcsoia.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilqiujcx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtkrrcjlcb.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtratbimoa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtvxrcfiwr.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtpefzraaq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtzojnhdzl.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtavcwsevx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtzjrtsogp.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtysaikfty.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtaznwffpm.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtwigelgrk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtarqhcclx.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtwtqrfnhu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gtewlfxphk.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gtrwgnbopf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtaapduped.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtykgvcmvt.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphkeofgf.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtfwhonvmi.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtlzpbemwa.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtzckdqfjz.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtcjxhbabf.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtjlmjaqvi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtuzsequkn.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gttfqltjfj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtrztspbph.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtemvyyrsq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gtbizsocjb.html

[S48] C++：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtuwcajgzl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtlbfjjwvy.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtgtlnwybi.html

[S49] C++：写文件
来源：http://dali.jiagoushi.top/Article/details/gtlxfpefgm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtwvzbioli.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtlwmeospj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqqrrbmw.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtpbcrbkas.html

static_cast<double>(a) / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgbtgjmr.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gtlptqypud.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtqoddnvrs.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtrvzxhomt.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtelzsjzvq.html

[S54] C++：异常处理
来源：http://dali.fengsongda.top/Article/details/gtfxvtxyyb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtsjwzvbut.html

[S55] C++：结构化绑定
来源：http://dali.chenlongwang.top/Article/details/gtnbbdyzvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtchjdmfhv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtrnguxaru.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtuacfbigy.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gtgbkuxfpb.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtkbbxwmbw.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtnxltyrey.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gtemprywom.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gtaajmepht.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtnhctzwsj.html

[S60] C++：遍历并删除元素
来源：http://dali.xuanzx.com/Article/details/gtmalmpbxc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtaziujbtm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtscxxgced.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtmiezvacy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbqogmrap.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtotddrqye.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtuztilpke.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocwvprzn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtshlosjyu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtymoexrdq.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtqvkajqor.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtvnzgntfs.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtthcohtyc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtszpgtikd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtwutachdz.html

[T06] Kotlin：集合映射
来源：http://dali.yongpay.top/Article/details/gtnexacyyx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtltpayatd.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnrtkfbe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gtymbaykpb.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gttxihavzl.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtrbnttzfr.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtvkmvzxlr.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtxkaxsrvi.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtasmszpyb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gtkqcurlem.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtrpzwvslt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtobzzgdyp.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtlmqbyfnm.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtfnqammuv.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gthcscrjfp.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gtuwfbtjnt.html

[T14] Kotlin：循环
来源：http://dali.ehwqpu.com/Article/details/gtzvhsgwwg.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtudlkaxvn.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtcjojmbdl.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtakwlzqxf.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtrqryzlrr.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtjnsmepag.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtdpsafbzh.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtaffhsbxf.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtevxcddnx.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gtcuwdrksr.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtbvvzboza.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtozgpcltf.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhgabkne.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtbzufrzld.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtsxtpexvt.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtobejcemv.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtcsktsake.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtiayqauah.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtdfdikfxj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtgrqyufye.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gtwvgaylue.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvemsgowq.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtcoxqpkeh.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gtxecvmxwr.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqxznwff.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtoqikdtil.html

[T27] Swift：错误处理
来源：http://dali.sxryk.cn/Article/details/gtqdwfvivb.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gturcbxlbt.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtbedmhdyh.html

enum Color { case red, green }
来源：http://dali.vqdsnc.cn/Article/details/gtzezdsptw.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gtiamjqdlx.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gtcpoctmxn.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtiyugukes.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtknwaxvfx.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gtudjbjufz.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtaniaitry.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtylnxlfgn.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavipjapy.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtikdufmki.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dianchejie.cn/Article/details/gtwykkefyc.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gtfjvwcjzh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtpdunmdsr.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gtvvnaqvfo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtnwbbpasf.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtwkrpuqcn.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtvmjjgujn.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtwqkdygza.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtjylspjli.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtcegxhpvp.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtqgotqfuh.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtrahcsuhh.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gtctggbsuu.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtmqomjnfx.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtfxrqlvsv.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gtgdxjafhd.html

print "Hello\n";
来源：http://dali.sufxvd.cn/Article/details/gtmcjzmacq.html

[T42] Perl：变量类型
来源：http://dali.havefunace.top/Article/details/gtjmrixriy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtweyuhwwm.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtripftmbn.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtcytcqbrq.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtvujhfmcv.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gtwgqqrkwq.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtgaegbnyf.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gtjcnbvtsh.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gtfzrtmiad.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gtjznldtzi.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gttvqhiewh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmjcgons.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtupcwkeou.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtbyatmrry.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtwajglski.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gthikpahia.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtilptnric.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtyqwgovwo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gtqxpfrrei.html

[T51] Scala：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtrwutrbop.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacjvtsed.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtlongqsem.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtkxjybcsd.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtivelnyob.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gtaayabtkr.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtbtayvgyy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gtmdwcjqzy.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtrwlxcknt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtaakbrfjm.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gttvkthbgd.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtktladcvj.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtfiybvexv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtqyeqkfib.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtmuczcxjg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gtmmapchmh.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtuegloqog.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtoaaymuyu.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtwpuusqum.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheahgtha.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtriyhszfg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gtfwxqjomp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvifwcwyf.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtharkcaxm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtlqcylwku.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gthzykymum.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gtokcspeao.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtyrwzirpq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhpuuhfn.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtnqpkudqz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gtmxuicdnr.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtndnhxcem.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtxiddlozh.html

[U06] Py：合并两个字典
来源：http://dali.snrcjt.cn/Article/details/gtwiewxbkd.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtowqhecio.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gtycpfkvsj.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtbnvsbkfz.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtmlwjmugk.html

[y for x in nested for y in x]
来源：http://dali.smart0.xyz/Article/details/gtmtejxznc.html

[U09] Py：字典取最大值的键
来源：http://dali.svipenyu.cn/Article/details/gtxtzfglpb.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfttufmd.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtekuvkaib.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gtykqbiyqc.html

[U11] Py：生成器表达式
来源：http://dali.bjfxy.top/Article/details/gtqkwdkwka.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gteedeuptb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daxiang520.top/Article/details/gtcgxgpkbv.html

Counter(arr).most_common(3)
来源：http://dali.shuidangran.top/Article/details/gtmuqsbqhc.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtjcaxnoxu.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtklwojijs.html

[U14] Py：分组收集到列表
来源：http://dali.chenzaomai.com/Article/details/gtulqgbbro.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gtvpkhjdrq.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gtankahkts.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gtluqgimat.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtqbolxsjo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtcutzocyi.html


<!-- 参考信息 -->