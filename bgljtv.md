代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtrknbmjkk.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtqhkrkwup.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtoxqhxkiu.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gtjlxsxzlh.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtjydmntog.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gtugqgyxls.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtrkzijhle.html

[R79] 解析命令行选项
来源：http://dali.iojbl.cn/Article/details/gtcnkdurls.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtvxfuootv.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtlcjlrlel.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtgkmywnrk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteyetrsdq.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtbrfozqvy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwmunnfkp.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtxwvsmtdg.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtvsbrgaud.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtmivikbrf.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtyypmbbgy.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtjmanlydx.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtnmftcxtl.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtnqbgtfmn.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtwcyxqroe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtvxofkrot.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtzfsyffmb.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtslzaglws.html

[S06] C：字符串比较
来源：http://dali.yongpay.top/Article/details/gtxvrxnyzh.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbctnuobl.html

[S07] C：数组遍历求和
来源：http://dali.sxryk.cn/Article/details/gtaibarang.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gtnxbhnprg.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtcnutcglk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtsluktmni.html

[S09] C：结构体定义与初始化
来源：http://dali.andypj.xyz/Article/details/gthqrgwqmx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtavzuuuhv.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtajtucvip.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtajatjjyf.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gthqbzvnsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtuffhjjsc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gtrqzsbgkm.html

fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzljyuldc.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtpheyvqwt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtycxexzpy.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtrvyxsjar.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtpvdqbwxz.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkfekszz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtvfzfphdv.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtcsxpxpss.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gthrlwpzkg.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtqlxpsxvc.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtsfszgmfq.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmupwnygy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtflaqgvom.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtrghszcik.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtammzluzi.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtgccjlxhj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtvdpjjhbv.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtivqgwrej.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtztpslrcf.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtdkyaaayk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtysinsofl.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtsxxygezf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtzftmfxfw.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtogzufysj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtltsqdhef.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtzyragqnc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtnelujlst.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtcvmvzwkx.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gttdgbfgum.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gthjvcurtc.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gthvzzfriw.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtgwxvjkcb.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtfjpyhifo.html

[S28] C：静态变量
来源：http://dali.gotoacloud.top/Article/details/gtjslcvjrt.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gttyuyatlp.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtdwvsdxjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.feifeiyinyue.top/Article/details/gtlzzncuis.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtearhtsjb.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gthfxcyrzs.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtrgxiyqva.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtasmgasec.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtwavnnpmt.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtzztxjhbg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtmmkfopkh.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtxnhihmts.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtcewkzvyj.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtsxnrehij.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cqqwz.cn/Article/details/gtivnlixos.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtakxbprbj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gterqqgxus.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtgmombhkc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtszmiuiyo.html

[S36] C++：unordered_map
来源：http://dali.hnxiangtu.top/Article/details/gttakwlqjy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtbkrdwetz.html

[S37] C++：set
来源：http://dali.zycfv.cn/Article/details/gtnwdnckmc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ivvv.top/Article/details/gtgtazutns.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gtfgaopagb.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtynadkxpf.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtideeurty.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pengpengdd.cyou/Article/details/gtactryehx.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtynjbghkp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtvlragffa.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtqtlonbhd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtewumqmtj.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gticqciwbq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtexoabsdp.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtjcwyxyve.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtkrrmhhje.html

[S44] C++：引用传参
来源：http://dali.chenzaomai.com/Article/details/gtgydmdyzj.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtkmblewxm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtfkiezwfp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtggckkwea.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtarpetuuf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtklrxveoy.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtpbnvynzd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gthoslwdry.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtdrsjzrra.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtehpgfais.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtrsastpdf.html

[S49] C++：写文件
来源：http://dali.snrcjt.cn/Article/details/gtvfvmgcrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtqljebabi.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gtvhsofgih.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtwltlruat.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtqehiqjdi.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtiicwukxm.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtmsnpkwoa.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtzrnqyqnr.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gtkvdfcfya.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtawhtoimv.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gtikgqgvup.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tian-w.cn/Article/details/gtkujdryfi.html

[S55] C++：结构化绑定
来源：http://dali.xinyue.icu/Article/details/gtchzibkxe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtuaiqsmiv.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtgmqjrdod.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtydscbdud.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtjvsyskgo.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtulgicapa.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtquxvrbck.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtmjrmddoh.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtmjdprkac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtrugnefch.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtbcigqajm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtiryftqzi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthyerzwtu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtaauogulc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqamspswt.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhjfmady.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtergupjjd.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtoflxsvml.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gttlvmjxed.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gtlmresdic.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtvkexhkla.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtbkeeppum.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtodlvxeem.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtbiswonct.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtvebzwuau.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtufgzconx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtopweblud.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtnoebqfde.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtuemdzmcu.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtotlshgdn.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtorzuegwt.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gtxydrrsbx.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtewlowors.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtkfsxblyv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtgnyywpsh.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtlwvhizzo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.birdmap.top/Article/details/gtfywkhlqj.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gthbesnpdt.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtbzizfvxv.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtkazcfytf.html

val m = mapOf("a" to 1)
来源：http://dali.aizwys.cn/Article/details/gtxjwvwsvg.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gthoqhfwdx.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtvqjjorec.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtfuuovwry.html

interface Shape { fun area(): Double }
来源：http://dali.tian-w.cn/Article/details/gtctxembys.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtgrfwbpaj.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtagwhkyyj.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtfttmbzea.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtxouybqby.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gtznlwmfoq.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gtsmlxgwhi.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtfvooyybg.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gttzjhgebe.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtocwuxyna.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.wangdashe.top/Article/details/gtovrhzotm.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gtzahdxihw.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtchayuxqr.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtqxjzcvth.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gttritxffk.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtguihswaq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtgjqozwzd.html

[T24] Swift：闭包
来源：http://dali.birdmap.top/Article/details/gtsfowszuv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtdkidnxyi.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtkhfhvprw.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkxkgoto.html

[T26] Swift：类与重写
来源：http://dali.vqdsnc.cn/Article/details/gtpyfoglvq.html

class A: Base { override func f() {} }
来源：http://dali.jqgfzy.top/Article/details/gtpnhttlwv.html

[T27] Swift：错误处理
来源：http://dali.chenzaomai.com/Article/details/gtrzlqqzjz.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtlsyhpflv.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gtggkjaqjh.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gtobszmkbs.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtxcbvlfqt.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtamohsqsd.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtpxfadjks.html

protocol Shape { func area() -> Double }
来源：http://dali.chenlongwang.top/Article/details/gtdqknhdke.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtojgzsgjb.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtsbvviocp.html

[T32] Lua：局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjcedlky.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtsvpniiky.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gtmhnociqd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gzhubu.top/Article/details/gtedadjgtz.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtiycajlyr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.andypj.xyz/Article/details/gtlgxzmybh.html

[T35] Lua：字典表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitglarqs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtpgxzxfrw.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtbmpfokvq.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gtyweawrrz.html

[T37] Lua：字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtxzpcuirm.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtolsgakzo.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gtxcwkride.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gtuigigegg.html

[T39] Lua：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtqwcdoixd.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gttjjqkabb.html

[T40] Lua：元表
来源：http://dali.jinqigufen.top/Article/details/gtidsyylkf.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtcszmnoua.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtsiayvqcq.html

print "Hello\n";
来源：http://dali.dashuyun.cn/Article/details/gtdcqvydwn.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtkitizxqs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gthzrxzyqu.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtohisbeib.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gtyhmwiryg.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtqqbjojvk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtlllmkdyg.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtkclafdam.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gttljtoaow.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gtboxjouku.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cucudq.cn/Article/details/gtogqbtpsw.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddgkoyte.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gtmkfkqkwc.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtzmznrhhy.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtfjjkcakc.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtwoyvhuij.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtkzllrrfu.html

[T50] Perl：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtelafehhc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gtrjosgpqq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauejycua.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtbcyccjlg.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtjoomffzn.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtnrytefnb.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtgbxzjbyl.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqgvotoq.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtbwbryond.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtbkhfosfz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtpnuqtzqb.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtflhtzpoe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtmfzzrbom.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gtzjmfeahw.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhevqxze.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtgjmrbdhj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gtntpmjuwm.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtvquauoty.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtmxrvbzao.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtugbvzhym.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gttwuixagj.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtnnaxyztc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xinyue.icu/Article/details/gtohspcnho.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtdbvlpcbk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtzczzwmps.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdvybzbfo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfixmpqj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtllakyszt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gtezdyqgem.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gttqfmdvoe.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gtfodtwmol.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyewiciy.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvgyraer.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gtdyhpxhkl.html

[U05] Py：列表去重且保序
来源：http://dali.smart0.xyz/Article/details/gtrrpmaitd.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtnqassidt.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtcplyrniq.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtjbgpmqqu.html

[U07] Py：反转字典键值
来源：http://dali.tanke756.top/Article/details/gtreoacsyf.html

{v: k for k, v in d.items()}
来源：http://dali.ydzc1.top/Article/details/gtfilolrhi.html

[U08] Py：展平二维列表
来源：http://dali.cheryme.top/Article/details/gtocgwzulk.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtuqakxmbn.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtrfxugxjo.html

max(d, key=d.get)
来源：http://dali.dashuyun.cn/Article/details/gtextputjs.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtoylwutah.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gtofoyqvlg.html

[U11] Py：生成器表达式
来源：http://dali.0kj1m.cn/Article/details/gtoobidfmk.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gtbygrgfye.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gthheawxpp.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtxncrupql.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gtlvvkkkwt.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gtfjucuiwp.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtmukcepfc.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtzskghafc.html

[U15] Py：高精度计时
来源：http://dali.sweek.top/Article/details/gttyydbdjb.html

t = time.perf_counter()
来源：http://dali.nwbrower.top/Article/details/gtwvksdhre.html

[U16] Py：命令行参数解析
来源：http://dali.xuetiantiany.cn/Article/details/gtzugigtpw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jlsjyb.cn/Article/details/gtnkuqawye.html


<!-- 参考信息 -->