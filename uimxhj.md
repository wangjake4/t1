代发 wailian999

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtsdkubanv.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtmbetfmly.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtpfqliupf.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gtarxiislw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtxcxbgwic.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtdhukdulh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtzvtyfmfi.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtgzjjvlra.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtzpamzudu.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtpjqiqzfk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gtclfqmcmz.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtxxmdoxwv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioammgpx.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtbokurglr.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtfdwxedve.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthzyclsvh.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtdecvdtdh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyxzbugjl.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtxpfrfafa.html

#include <stdio.h>
来源：http://dali.gogol.net.cn/Article/details/gtqdmjzvcg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtbkfdryqn.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtsawhcxml.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtpillaote.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gtokgbtequ.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gttvqxnioo.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtilhrspog.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtqhljuqul.html

[S05] C：字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtvcjyhlrh.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gtxijexhpa.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtyrqnqsyo.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtwunsimym.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtfxnkmjnh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nanxinkj.top/Article/details/gtpmdlzmvu.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtrzerveme.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtglabiwby.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtldadzzdq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtmjebhssn.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gttqvupthm.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigufen.top/Article/details/gtpubfqldk.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfxvpcoil.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtdarhymrp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gtebkrrqao.html

fclose(f);
来源：http://dali.yj20258888.top/Article/details/gtmowoasap.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtwzzorexe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdliiuoht.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gttbyasohd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtxmxybvhq.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtcnjgcdys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gtyefuyftq.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtfbznethk.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gtdvankywq.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gtxiaxnuse.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gticabptup.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtshinqlmq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtrityfcyn.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtfvtnneaw.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtytyyzxpl.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtthumliea.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtorqszraa.html

[S20] C：二分查找
来源：http://dali.hammf.cn/Article/details/gtbyxgnksn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtfvqiebwx.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtebsvpted.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtzmsjgajo.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gttjymsxrb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtufqwncas.html

[S23] C：随机数
来源：http://dali.hywenlv.cn/Article/details/gtencbkvhe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtqnilnfah.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtbsoxmzut.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fzhhl.top/Article/details/gtdzasyylf.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtxdwfdxra.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtopowganu.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gtxmlxnrqs.html

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gthvvjepql.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtjbuuarpd.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtptzadtlp.html

[S28] C：静态变量
来源：http://dali.jianghu66.top/Article/details/gtkugbskyt.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtagxqmpkv.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gtljjtyujk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtxtyhqiwr.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtmvcfpyxp.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtluepgaih.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouohkuwm.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtfljgenqs.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtilhkrdrk.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gteqhzgdzr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtyuaduiff.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gteqmtqacl.html

std::string s = "hi";  s += "!";
来源：http://dali.yuanzhike.top/Article/details/gtfdmphniy.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtxwgayzeq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtjndooubn.html

[S34] C++：遍历 vector
来源：http://dali.smart0.xyz/Article/details/gteztmwsfv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtyvgmpupn.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtccabredh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtkipvvmma.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gttnvntndq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtqvvacjiq.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gtifeyhlik.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshzmstiw.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtwlzirnbc.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtkkaebykc.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtfavrpazu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtjlawgkzq.html

[S40] C++：查找元素
来源：http://dali.ivvv.top/Article/details/gtebxkrlpc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtrmkdfgvw.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtvucwillw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtwqznnueq.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gtcargmqxa.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtrfkbjblk.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtpzfliosj.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gtihhukgml.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gtazatnuxb.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtuxfnjztd.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtuyrahaec.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtzpichnni.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtphpphjyf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yongpay.top/Article/details/gtwionizrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.vqdsnc.cn/Article/details/gtkfrnmisi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gtaibkxuiz.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfcsxnlp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gtdovvdxdl.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gteqywncnh.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtvcdfkdcm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtefntquhj.html

[S50] C++：格式化数字
来源：http://dali.snrcjt.cn/Article/details/gtrgtikffe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gttwwfzrkx.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtsworgvvi.html

static_cast<double>(a) / b
来源：http://dali.cdnleiting.top/Article/details/gtxobiuvii.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gtqlifbhfz.html

int size() const noexcept { return n_; }
来源：http://dali.cdnleiting.top/Article/details/gtqkwjflek.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtbqnvmgvb.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtfbbvntsc.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gtcboxqibu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gttlecnwbt.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtduavwxqq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuxming.cn/Article/details/gtieglfrln.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gthfcbagia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtcjflzjjy.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtdwhxxklo.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gtkmjumify.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gtvdiqbezt.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtlyyltecg.html

[S59] C++：静态断言
来源：http://dali.tian-w.cn/Article/details/gtjbfrpuad.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtwakykeyp.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtbfbkctie.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtgocmmegu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdqpjlzzc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtbuivmcdx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteqxooddv.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtmbyazxfh.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtintndebn.html

[T02] Kotlin：变量
来源：http://dali.hongshengwenyu.top/Article/details/gtncngqvhu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daria6918.cn/Article/details/gtrimjezmx.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtrglicoom.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtwfqpiwve.html

[T04] Kotlin：空安全
来源：http://dali.jiagoushi.top/Article/details/gtymbrlsih.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtzzxbdtsv.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtuxyfvzoz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gtnmajbxar.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtwqftnwun.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvjjmiql.html

[T07] Kotlin：集合过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttptvfvn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gtgxuqhzvk.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtnuxqdmrk.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtvcmtjqgr.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtvhdkjdbj.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtzfmoluph.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtcxegyiwh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gthjsierbj.html

[T11] Kotlin：协程
来源：http://dali.fengsongda.top/Article/details/gtiyajpgbe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtkueylaxo.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgujitju.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtrycbmvic.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gtsmcjnfog.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gttafspkgi.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtocyxepnj.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtklerkogw.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gtywwrypjv.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtrxyeebmz.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtijvpsxjj.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtvasdefdq.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtqtqxebmr.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtvxvsomhz.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gthcdmmxqo.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtwvauiasj.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyewuboir.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gthjfaqndy.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gteevrocff.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtecmkpdoy.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtrrpbisjj.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gthnsxvajq.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gtixrcyaad.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtjaefzdya.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtavemnzdo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlymwggqt.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtwtzaxqct.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtsjyglbue.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gthyanjufe.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgptpivw.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gttrbndupu.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gtimrbfofu.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtavsmxpim.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gtsikocjwe.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtwhubpnos.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gttkatjoqs.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpwajaff.html

guard let x = opt else { return }
来源：http://dali.jqgufenzy.top/Article/details/gtomcfqjbu.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtcnbosfpp.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtivwccaia.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtyxmwvjqq.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtiqobhehy.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gtmzuwkngn.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtlhwfklww.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtuzpcypbf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gtxruvlwwo.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtrphluyzq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqnlmupz.html

[T35] Lua：字典表
来源：http://dali.sufxvd.cn/Article/details/gtukisthmo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gttdypafsy.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtjgkvbqom.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtjyklfjcg.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtqqgcfedu.html

"a" .. "b"
来源：http://dali.yj202588.top/Article/details/gtscmkztqj.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtcvtteqez.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtzqoyxrkj.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtdrzzcylq.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gtfyriyerq.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtrmdxoxgv.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gtfsxirzjw.html

[T41] Perl：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtebuhqlgt.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwlbitdg.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gtqfeaneie.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtxvoewqnc.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtoffdpqhh.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtprvagxqc.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gtbsbfceep.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gttknwqucj.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gtekjeafjx.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gtqqfclacp.html

[T46] Perl：哈希操作
来源：http://dali.cashguo.top/Article/details/gtmsnygapy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtypflxnyr.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpyyhzua.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtpzmndvwy.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtmwlfhjsm.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtdqwkdbjt.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gtlywrtmuq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtjgwjwepz.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtzhgdhxyr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gtjznfwioq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtkmrfkcom.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtzysjuwjs.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtaiefpahf.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gtevalcxyj.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gttodepihp.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtqyajgfiy.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtljpsjxdx.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtvjijjedm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtahxrwvuf.html

[T55] Scala：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtblmjhbfz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sxryk.cn/Article/details/gtkfjlbsgb.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtzamevleb.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gtdbipmuop.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtmkqfpzka.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtugzzngkq.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtoajqlooe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxfqajld.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtteufvnht.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthqgfmjc.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtmfzjtkij.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtktpnorld.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvsgxxkrr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtmcwmrxbd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyogkparw.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtypsmnkpv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hnxiangtu.top/Article/details/gtmslrawqs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtsqmspbdx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gtuddxhbib.html

[U03] Py：加载 .env 配置
来源：http://dali.wangdashe.top/Article/details/gtsxoqumjz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtsvmluhmi.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gtuukecgaw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtosmjhwkv.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtgbnookeu.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtcsozkiko.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gtoapituzz.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gtiyttqwyw.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gtivvmzqsn.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gthxheipzt.html

[U08] Py：展平二维列表
来源：http://dali.fengsongda.top/Article/details/gtzxfkzlzf.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtgwhcwwdk.html

[U09] Py：字典取最大值的键
来源：http://dali.smart0.xyz/Article/details/gtybdoazvl.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gtmrxbxqyk.html

[U10] Py：按值排序字典
来源：http://dali.yonumen.top/Article/details/gtpzwgpokc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.aibaodan.cn/Article/details/gtfesnqjkm.html

[U11] Py：生成器表达式
来源：http://dali.pycfn.com/Article/details/gtzjjtdgmh.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccplvtgy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhiwuduotai.top/Article/details/gtrxkurstg.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtmuysbgvg.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtwbcdmttx.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gtfvfzchhn.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gthtyernra.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtkqjmwbud.html


<!-- 参考信息 -->