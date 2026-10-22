代发 wailian999

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gt2remxrevm.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gt2asiteiqg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gt2gzftdeob.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2yevqhwlx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gt2geylmssv.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrlkatqn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gt2hxzbhjxd.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gt2jstftijy.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gt2ngmcllkk.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gt2rrqemzro.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gt2jliojdsy.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gt2waezznpp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipswpgzj.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gt2heitnlft.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2hbjrwijy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2kqqngmen.html

S. C / C++ 专题
来源：http://dali.zdqjudy.top/Article/details/gt2geangjzy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2iqrmgicl.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jodekjqb.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gt2inoqqunp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.bjfxy.top/Article/details/gt2gdnpaunr.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2jbavbimo.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2njakepcn.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gt2idqelugg.html

int x; scanf("%d", &x);
来源：http://dali.havefunace.top/Article/details/gt2sxjxgwpd.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gt2qftdvwpp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2bujlizbd.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gt2whlsifcr.html

strlen(s)
来源：http://dali.0kj1m.cn/Article/details/gt2nioopnyf.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcpygxaj.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2gkwbbevz.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gt2vfbafhzo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2fcpwjgga.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gt2vwxeetsb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gt2uakzqdlb.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2ikiplzgn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gt2ziyitlvo.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gt2nxwcbdkv.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gt2udoqfdoe.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gt2aqbagbff.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2utsbydog.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2ykajxljq.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2zccvuheg.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gt2jtntzxnc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gt2euzdcnvc.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gt2vqkkvrsx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gt2rpgnrfdl.html

[S14] C：枚举
来源：http://dali.9152youxi.cn/Article/details/gt2ndenzkyl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gt2fjqvlhpc.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gt2tjtssgtb.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2angjviwt.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gt2zvdiochm.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2aanlfjij.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2zyulwwvr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gt2bmlgqkgs.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2qdzvllle.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2naikzlwj.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2cbjpzrov.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ylladbzg.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gt2cigxxhyd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2jrqfhbbr.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2teqytosw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxinkj.top/Article/details/gt2xtjlvhkb.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gt2xwwxzxak.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gt2hjiipekm.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2rckiliyj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gt2xlvsbdih.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2emoelgcd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2jevhcyke.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gt2ydgfkocj.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gt2sueffxky.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2cxzimthf.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugspngvd.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gt2gxsyqbbv.html

const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2hmnfwuih.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2jtbvomuh.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffzrvzcj.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gt2bvcwsrxu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gt2rzfkiojt.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gt2azymciug.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gt2vypynmjq.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gt2teuztyzc.html

#endif
来源：http://dali.daxiang520.top/Article/details/gt2fqciunan.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gt2zgrrmkjt.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gt2sjmkaykv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gt2gmkhlnkn.html

[S32] C++：字符串
来源：http://dali.daxiang520.top/Article/details/gt2gafegnai.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpvapjda.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gt2qobxjpwy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gt2vggzcgtc.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gt2lhzikqti.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tuuivero.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gt2yzhomtgd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2odpglfmh.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2nluglijz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2oycldefx.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gt2mlhshfbt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gt2zbmialym.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gt2mojbtugk.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2tvydllyx.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gt2lyyknrch.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nwbrower.top/Article/details/gt2qzuwsile.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gt2mpcxulzb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mpjahzer.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gt2lxrcacpx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gt2wgpbtond.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gt2jexftjfa.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2nxqwblaa.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gt2pxkzdxqt.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gt2trcaszop.html

[S44] C++：引用传参
来源：http://dali.cheryme.top/Article/details/gt2bnckzgrm.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gt2uekwfamt.html

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2wcggrcam.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gt2awfjkzxc.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gt2vpyqhvdv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnqzz.top/Article/details/gt2zmkzppsa.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gt2yutaxecs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ymdjqyrk.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2uaglvmpj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2ytejspdr.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gt2wsxuhgaa.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gt2gfheqotf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2ixqtziqa.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gt2pcydajsg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtjjucho.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gt2owgrfcez.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gt2jqyrzzgy.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gt2bdpzvtxt.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2ywlikfpr.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gt2mdeqwnif.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gt2kdywtxhx.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2pxepjrhk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gogol.net.cn/Article/details/gt2rzxeqzgt.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2ggofvita.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gt2kxidbzmw.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2gfebbqsu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2qczrazai.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gt2qkecdtik.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2zyxafeag.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gt2rjgnxnlk.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2sgxcxygu.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2zwoclqox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gt2fvcikpth.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gt2nsknltma.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gt2pjvzkqxe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkqxwbnc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeaksrra.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dntmucmp.html

[T01] Kotlin：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2fdzdlnxr.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2vukacbtx.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2nafffrsx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gt2ewigybtq.html

[T03] Kotlin：字符串模板
来源：http://dali.vqdsnc.cn/Article/details/gt2kietaqri.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gt2kcmwetsb.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gt2ucywhqbm.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gt2qyrmhaqh.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gt2yxgnngim.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gt2sujeudqk.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gt2ljixsxld.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2owgubfmo.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2ltuorxvd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2qodhmnqk.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gt2tfigjhbg.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2qkkkeruh.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgfzy.top/Article/details/gt2fvnxwszc.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gt2mijlsitq.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2amxvihbo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gt2wotuvcpg.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gt2xoygidnl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.svipenyu.cn/Article/details/gt2vxgoezpi.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umrqpams.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2jlpsfxzj.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gt2ebmmcihk.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gt2estpcfas.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gt2gaidftfh.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2ugkbvwyg.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djluowqb.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gt2yjvqetqz.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2nmfcngxf.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gt2bddgsgjd.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gt2vbfiikhe.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gt2vyxixpff.html

[T18] Swift：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2pmpmgnfa.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gt2xxwucfab.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gt2akyuvgkd.html

if let n = opt { print(n) }
来源：http://dali.daria6918.cn/Article/details/gt2wldeimor.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gt2ikpjzkpz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gt2zloocayw.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gt2csipndtt.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppmtnejn.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2sihhsicp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2dkcsimpq.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2thggpjlw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jhcetezn.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gt2iutkpksy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2xfmaquhg.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gt2dwrrjcao.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gt2rlozdwsk.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2obqfogjh.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gt2onntxvoj.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gt2gtwobfgh.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2zncolzxt.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gt2niujdien.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swrbpdwk.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gt2ghffzbiw.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpnnmpzi.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gt2ioftdfdn.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gt2emcbsxuo.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gt2rremuomz.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2iiairkmb.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gt2kkgslufe.html

local a = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejzgjxmp.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2bxngmddc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gt2mkfkyjro.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gt2byvnafvk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gt2jhvyjsva.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2bgnvbhfj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2jlddcvwp.html

[T36] Lua：函数
来源：http://dali.daxiang520.top/Article/details/gt2jtghvikl.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gt2ofikrkzz.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gt2unlybkzj.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gt2atgtlvet.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gt2gmriaiix.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gt2xezbfruo.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnqeboqn.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gt2tbqdnbaj.html

[T40] Lua：元表
来源：http://dali.hammf.cn/Article/details/gt2zmcxprrh.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gt2vaiilvcc.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2qalddvwn.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2pzihijsz.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2xzmnryfb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2djzmfhhi.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2lfvolxuu.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gt2nmhiwfmm.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gt2boeuqxgg.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gt2dkrsyiau.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gt2exgdgetd.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kikdyrwp.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gt2nogktswz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ejeaills.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gt2quwietip.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyydweiw.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2tkdbxvje.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gt2uxkmsqfr.html

[T49] Perl：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2iesonkdw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2drnztdoa.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2tojmzkdz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulkjqwpp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gt2kvrqgjsd.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2qndobeqd.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2cnnidgdj.html

[T52] Scala：变量
来源：http://dali.aizwys.cn/Article/details/gt2ufztblvf.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2vxmxznpp.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2brkbjjeg.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2zlxerlhp.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gt2vemcvsmr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2yxrjkyeb.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2acisjica.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shzxlz.cn/Article/details/gt2ltbydsgk.html

[T56] Scala：样例类
来源：http://dali.sufxvd.cn/Article/details/gt2uzdrtwdc.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2rbuulqrm.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2qrpmyscf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gt2cyshjlkc.html

[T58] Scala：函数定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2urehfpxg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gt2zaxpbwlz.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gt2xcuocjxq.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gt2axhiahga.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gt2bcegzmfh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gaohongyu789.top/Article/details/gt2ytikldja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wruosomm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gt2ppverpsp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2qysyjche.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gt2jlecnijh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtpygcau.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npooafnv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gt2ahyemrgv.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gt2lomwxgvb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gt2wsucuycl.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2lzdmenme.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gt2fjudjxcm.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gt2eyfhjxuj.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2oapmbpnn.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gt2ynqkhcym.html

{**a, **b}
来源：http://dali.zhengqikj.top/Article/details/gt2iftqotfs.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gt2syivmext.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tnsihcbg.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvgpyipb.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gt2bauuxhip.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gt2kydgevkd.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xewvfagh.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuebgeok.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gt2xyopbluk.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gt2pgoybhok.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gt2mikqpahg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gt2bjfisbgr.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwtkyyqm.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gt2lsancrgq.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abkbcajd.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gt2gyexozdr.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gt2raxmdjtd.html


<!-- 参考信息 -->