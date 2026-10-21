代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtxieblpks.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtfvahxhpo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtypndhkeo.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtcrnenamy.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtdiltajob.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtqdyhvzed.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtrkgcjxrc.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtklufahfh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gtjznwiysy.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gtpucybjqn.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gtbswwubzn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrmocuqxi.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglcodhky.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiugwiiib.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtzaytzhwa.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gtbxfykhkz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtvmyhjvse.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtbnitpt.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtznydkmas.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimcaolbf.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gtxjmewhdk.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtxyhieiqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtlgabjctc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtlnkjorhv.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtsvmtgcxp.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtypeoayow.html

strcmp(a, b) == 0
来源：http://dali.fzhhl.top/Article/details/gtegicjdev.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gttpxksmoz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dianchejie.cn/Article/details/gtjnvseqre.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtijawmifm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtxbixecmg.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gthdlmzjfy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gthyqsxpab.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtmyspmjig.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtnssgirke.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtwcfuhiho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtedlumvpj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gthmjqaejx.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtetaillaf.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtqzlmejrp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtdcolyywr.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtjcnuujdx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yueranfly.top/Article/details/gtjvnodsdi.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtolvxvlti.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigfzy.top/Article/details/gtwymnqhcp.html

[S15] C：类型转换
来源：http://dali.yuxming.cn/Article/details/gtnrddoefn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtvtokwkru.html

[S16] C：位操作置位
来源：http://dali.xinyue.icu/Article/details/gtustkjwlb.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtbufnhpkn.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtpermydsu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gtsucynuun.html

[S18] C：命令行参数
来源：http://dali.pycfn.com/Article/details/gtrtdrowfe.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gtgylrgzid.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtehpcikay.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtudckrlqc.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtbvxuyapq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtnozybssq.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtndhohfzg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtthugypmv.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtcdufxyyj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jlsjyb.cn/Article/details/gtxwbdrhmf.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtgytprsbo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtkyolrdya.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtlubglffd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gteshoisii.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtfvgwzgfu.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtjomaoaaj.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtelydkyda.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtzftkyfzz.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtchlspaba.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gthnsgexjd.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtbgxytiwl.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtosjoqizl.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtrptfdbkc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtgqdbyowk.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtmoghtniw.html

#ifndef X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkngblcfc.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtgyqnkabm.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtljpbglzi.html

[S31] C++：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtvalrhngg.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtdgabyfku.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtewctoggy.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtjwwpvhyq.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gtezyyebnr.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gtmaohblvc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtpzwuybuq.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtgybuvhxr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyfamzmg.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gtsevsnpwu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtwuiyjbqg.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtmwsjaclo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtkkpcbxzd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtddcbxytk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtlozrkdjn.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gtqjhmfhps.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtvgmqbvsl.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtenphdryg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sufxvd.cn/Article/details/gtkidsacqa.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gtnwhekxvs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gteqfldfsq.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtomiggkcx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtahmibnnv.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtwpamnhgy.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gtuvxskadg.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtorxgfozj.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gteilujfwn.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtndxkusjo.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtpxysznux.html

[S45] C++：lambda
来源：http://dali.vqdsnc.cn/Article/details/gtbxkmbcqn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxuanxn.top/Article/details/gtfphhaqwc.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtvhsrmhno.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.havefunace.top/Article/details/gtjdlkaeyg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtjqauabyu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtclgvoijy.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtyjhwqdor.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtalcjqlxn.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtjjyrqmsv.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtsziqjyex.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtaiexywni.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtldsynpuw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtyezwvagj.html

[S51] C++：显式类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtfepayzog.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtjyrfyoex.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtzclozipe.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtdcidpneo.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gthtezueui.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtxkdwevzz.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtstqgvahe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtgxxotxrs.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gtouevrcca.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtjvdwwduy.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtfzowioax.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shzxlz.cn/Article/details/gtkkuvevkr.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gttrmsycea.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gtetmzqrnc.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gtpajzzntc.html

namespace ns { int f() { return 1; } }
来源：http://dali.tianlin.xyz/Article/details/gtpcbkvafs.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtdnttpczv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gtypdgwzle.html

[S60] C++：遍历并删除元素
来源：http://dali.ppjwa.cn/Article/details/gtapxednil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtuivtjfba.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtemmdikxg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtxjkmnphp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtjkztbkdf.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtkfybziya.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtjaykdaya.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gttuhlbhvw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gttgfxkbvh.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtbvcdihog.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtpbfrdqdr.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtbhkoquyv.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtewmboiez.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gthtjwhckd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtuxnwrngk.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzoihmeh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtlsyekabp.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gthwgqsblf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkzmvsas.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gtyloynrqt.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjlldbcd.html

[T09] Kotlin：扩展函数
来源：http://dali.tianlin.xyz/Article/details/gtldgjrftp.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtsyghqjfz.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gtgtwnkghd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtxacmuhpd.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtgkqllgag.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtezhjipku.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gttbjiedah.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtkmyivyge.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtvtuhjymn.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzjmckmom.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtbyrervvr.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtzqfstcxx.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtztznalsq.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtbhanqgzs.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtehlxjzyn.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtrdctccwx.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtungvsqmh.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtrhbhxmxz.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtrnqzcwve.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtdpjdeakt.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtsilgxswd.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gttdalhefi.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtmkbyatee.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtptvwvmhg.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gtoahnhxuh.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtxwdkmvbp.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtjghrbljz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtrbpjzscb.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtaqmqpkcy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtcpeskzln.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtehjvugwx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtmictpzmc.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtzlybrmez.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtqiindeta.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gteyqzbvvt.html

class A: Base { override func f() {} }
来源：http://dali.svipenyu.cn/Article/details/gtldceizsk.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtutultejc.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtqgbdfbso.html

[T28] Swift：枚举
来源：http://dali.guowangkeji.top/Article/details/gtcptgszki.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtcluslqfq.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtlngclugy.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gtabmzqvim.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtmsdszltx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrvryoub.html

[T31] Lua：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtosardllj.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtiokukwex.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gthyskfisu.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtyzbqwzpj.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gttbshxipo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gthrutyeep.html

[T34] Lua：遍历表
来源：http://dali.jinqigufen.top/Article/details/gtgsdifknd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gturaqahll.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtipdeiieb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtcznrnpgw.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gtoepruxoy.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gthwfsxxlk.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtqoimfjja.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtljlrshca.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gturjrzzfh.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtquqmwvhu.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtogjygkmq.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gttdmjarbh.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtlgitnlao.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtcgxfeycl.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtsphysdoq.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gtttmndfrw.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtboozggny.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtrwkuhrpx.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtcppyftfo.html

"值: $a"
来源：http://dali.hnqzz.top/Article/details/gtbulztbfv.html

[T44] Perl：条件
来源：http://dali.gaohongyu789.top/Article/details/gtbyeydfds.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gttuaolqjc.html

[T45] Perl：数组遍历
来源：http://dali.redwolf501.top/Article/details/gttizouqwl.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtfakmibpb.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gthsrifwrl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtcioibuca.html

[T47] Perl：正则捕获
来源：http://dali.yvedp.cn/Article/details/gtuegqxhwo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtpieisgna.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtlmgpdvax.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtajlvomlv.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtxoptjqvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtclcyvyvl.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtrubbclwr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gtprurvnik.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtmvgqhafm.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtpozzbhvx.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtlkamhiye.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gteaeakfdy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtlxkfeukq.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzqjwonk.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtpzjmcldi.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtacvnhbcc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gtmnvkvbyr.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtukoptmhz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtqigatuxw.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtyixhfhro.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtkqthqzhy.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtmsbckiiz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtgplioxwd.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gtrfbqtols.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gtiubefejs.html

[T59] Scala：循环
来源：http://dali.mhx1999.top/Article/details/gtblwbfsne.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtsuoyjokr.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtvrggztet.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtpubhfxck.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxgagxrnm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtbbgrhzsw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxmcwxdis.html

[U01] Py：创建虚拟环境
来源：http://dali.cheryme.top/Article/details/gtyfcaoysf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtvylhuyhu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtqnifilkp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtlmnbjgre.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtcchfxfnu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gogol.net.cn/Article/details/gtafxadsie.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gtqyhfjpcz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtztyztqgp.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gthhzusezv.html

list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtoquyrbnb.html

[U06] Py：合并两个字典
来源：http://dali.feifeiyinyue.top/Article/details/gtklbbvpey.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gtqyvjxhbq.html

[U07] Py：反转字典键值
来源：http://dali.shuidangran.top/Article/details/gtncsnmefv.html

{v: k for k, v in d.items()}
来源：http://dali.jiagoushi.top/Article/details/gtmbsrfjdq.html

[U08] Py：展平二维列表
来源：http://dali.yonumen.top/Article/details/gtsgieajaq.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtfrapgnpl.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gtadrzpccr.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gtnfmafddv.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtonritdpg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gtcjkoxzhc.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtgufvysnb.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtyxmaltzs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cashguo.top/Article/details/gtxxxgsfih.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdrsqctg.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtfdcgmdtn.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gtndknwhyv.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtqzomppyi.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrxowpnn.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gtwzhcjnwq.html

t = time.perf_counter()
来源：http://dali.yanxiufei.cn/Article/details/gtdyvrqnuw.html

[U16] Py：命令行参数解析
来源：http://dali.mhx1999.top/Article/details/gtaygzpdhu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtujyszols.html


<!-- 参考信息 -->