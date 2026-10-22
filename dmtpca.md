代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtfvffeyyh.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtwdyrcgwz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtswcjxqjh.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gtkqbrhotb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.feifeiyinyue.top/Article/details/gtcryaprpo.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtfpqyhdlf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gtxrbldjcv.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtswhahlcl.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtrdebynub.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtnhajccax.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtrnfzxykr.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gtsoenuxuj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtwisbfzfu.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtoitpnycu.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtumgmztyn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtshlwattl.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gtpyfzraic.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaylfiyjb.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpcbztpu.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gtzqmqadef.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gtklgvwcct.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gteloqwhpk.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtujspawnq.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtbzgnbhpg.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtvvggspku.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtuysfgrub.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gtyjuqcbne.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtxedzqbtc.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gtahjrwvhb.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtniogrrpw.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtlzbgmimy.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gtwbdittul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtslzniwta.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gthukuhhru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gthyanszai.html

[S09] C：结构体定义与初始化
来源：http://dali.cucudq.cn/Article/details/gtimxqbbhp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtsvzwbggv.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtawxizqia.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtlxwtycdl.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtwlscocst.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsqzyslp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtogbslggv.html

fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gteltstnel.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtdsjtklrx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtxztttgpf.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtomfuzamo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gteofkfwnn.html

[S14] C：枚举
来源：http://dali.jyoumei.cn/Article/details/gtjmybntnv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtcakqjvfk.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gthsleizbg.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtdfjnozey.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtuyjtwxed.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtvlicszbe.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtbcmtuyyr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtitawbbqj.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokwfgmqh.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtkupsbzti.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gthkjfjqeg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtmfacrwbu.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtvsfwrfcf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtendayqky.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtdgclztja.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gteoxyncug.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtdlmrkfxx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gthhhqurde.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtiqertsbi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtftcpevxc.html

[S24] C：获取本地时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtfdkjjd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtmdskhurx.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtsycqjewm.html

memcpy(dst, src, n);
来源：http://dali.zhoulong.xyz/Article/details/gtqcgrqajd.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gtzsvakwlx.html

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtyrgcfmvz.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtdtegwsml.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnizsygd.html

[S28] C：静态变量
来源：http://dali.chenjidiqi.icu/Article/details/gtytutwzhg.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtnytppjil.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtgwlqhfim.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtnmhsncqz.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gtryfqgszg.html

#ifndef X_H
来源：http://dali.cqqwz.cn/Article/details/gtvgmswqkn.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtveujolht.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gteuezlgbw.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtjplowjtc.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnhxqkkq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtfbksqjuo.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtxnhenuee.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtfcnnhfyc.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtcoakbycx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gtfftyqsuz.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtsvihqgtm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtomxwmynw.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtjilizhox.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtexmgywef.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gteydypoip.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtadnmfrao.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtgbmebaxh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtqgwcgdgi.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtdpkdpgbd.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtynordmqm.html

[S39] C++：自定义比较器排序
来源：http://dali.shangyingyoupin.top/Article/details/gthvjvahpn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtuelijkdq.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gtmzwtcmvp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvvsmfxd.html

[S41] C++：类与构造函数
来源：http://dali.iojbl.cn/Article/details/gtqjvrbqud.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenzaomai.com/Article/details/gtcqiyscai.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtqzarohtn.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiymkfxd.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtwrjokzye.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkixvtlt.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtvwpchxaj.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gtpjeykwwj.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtxybgzhmk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtjnmxnjfy.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtqwiaxtbw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtsukcmkgj.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtccavptij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtqhqxpquk.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdnyjidzh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtsvrtczqa.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtdzfivqhj.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtmxjmzfud.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtfqcgxvtm.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtfsvazeuh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtwsrqorco.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtgupegxyd.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtquazopdc.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gtzumjlqgj.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtvjtrzwyb.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmvbcbtj.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtzxrqdhea.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtcwtqaxkx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gthucspeud.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtiyshtoqm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtowztxygs.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfgthzbu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtlzdxehgc.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtqtdcfdzu.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsajasam.html

[S58] C++：命名空间
来源：http://dali.iojbl.cn/Article/details/gtxjzrscdw.html

namespace ns { int f() { return 1; } }
来源：http://dali.ybcxt.top/Article/details/gtaggpqfyz.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtpckqzrdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gtwjbrysiw.html

[S60] C++：遍历并删除元素
来源：http://dali.jianghu66.top/Article/details/gtxhzgbeol.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtenmajsvc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbjnceie.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtnrkwgdqo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmqmeynfh.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gteiywddml.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gttusvxlki.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtdvuwtjmd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtlycfonlg.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxijnbhth.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtzlrupcgz.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtrjwluijt.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtyzjnzefc.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gtobgetwzh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtigvkurmo.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtdosfcvnn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtumewqvvr.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtoszgjbto.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtjfkyagjt.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtfcokjveb.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtmhstkqih.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gtudjptukb.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gtlnedpqyw.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtparfamrw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.bjfxy.top/Article/details/gtrzqcvrfq.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gtylrgrxut.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtjuplvbuz.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtvhuukoqx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gttnkogfsy.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtptoxcmfm.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtzazipfon.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gtkhsfihwf.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqortfvqg.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtgaqlrphf.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtlmjkbljw.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtfguyza.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtikqvbntz.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtxjrivsfe.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtiqakkwas.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtcrqzdzaf.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolfrlmry.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtjjprurqp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gtrcxjnhky.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gtetpyyyei.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gtcgqcscgr.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtawvwidle.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtojtowkjl.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gtmidgubhj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtyauxtpkn.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtieiwveqw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gtshialmso.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtdbbrmdrz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtaxdjwkvk.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gtpmllgidq.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtuzusifcz.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzekiclo.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtjeoazpua.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtcsfysxfz.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtqzfnkrmh.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtsmspmbbq.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtibinisnw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtcxirvusm.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gttfxlamff.html

[T30] Swift：协议
来源：http://dali.xylfe.cn/Article/details/gtsujzlcxl.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtlydbybqb.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtapxxkgbt.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtojxrymlj.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gtzkzjfvqo.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtmcvbamiw.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtqvejobaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtwisognet.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtgcufmclq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.9152youxi.cn/Article/details/gtksxusrgz.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gtvtgvepya.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtejqjkjqc.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxkazueht.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gtjvvhtlyo.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtxeespctg.html

"a" .. "b"
来源：http://dali.wangdashe.top/Article/details/gtbcpfekeq.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudntpadr.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtwhqstlqb.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtooaqodcn.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtzctiewue.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtyvaxqbrz.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtoemeflfr.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtckabhxqj.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gtdulfgwrx.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtsysfxguy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gthweglogf.html

[T43] Perl：字符串插值
来源：http://dali.yongpay.top/Article/details/gtbyzxdhtw.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gtuzumtdfx.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtvsfekwpm.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtamysvxrv.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtbhfvcgco.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gtvqfxkgqt.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtpznklawx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtsypmeeox.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtzkzgyjeu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gtkvfvltmg.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtggqaiagg.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gteazpdttf.html

[T49] Perl：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlznotgal.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtefevloxo.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtjhcvhtel.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtxgconzfm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtttggmkxu.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtfzlwzkzr.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtnwkoyjan.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvtuabkj.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gtchqkjxxy.html

[T53] Scala：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtcssabspo.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilvayonb.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtmrmhwxgk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gtnsqltgck.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtsnxivtzn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gtwezahjtz.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtnggloxjo.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtgdvlodfn.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtxjkzhjdj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gthshvjftz.html

[T58] Scala：函数定义
来源：http://dali.kuanghao11.cn/Article/details/gtmrppenzt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtjgwrlmke.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtqffklkvm.html

for (i <- 1 to 10) println(i)
来源：http://dali.yongpay.top/Article/details/gtmifcigao.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtgtjuhqec.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtpftvmtnh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtuizldxbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gtnolonobs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxghtrgxw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtomupezya.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtcpumbbka.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtrtdmzljo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtwyimjgbw.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtgcedikzb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbkxoann.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtgvqgfnqc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gtclxnjrhv.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtgshxzhvk.html

list(dict.fromkeys(arr))
来源：http://dali.meibo888.top/Article/details/gtmtswpgav.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtblobsdjg.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtbxqvfqhb.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gttytzbopi.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gthtpizefu.html

[U08] Py：展平二维列表
来源：http://dali.nanxuanxn.top/Article/details/gtxbsafuej.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtwrtybnat.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gtxiibomrg.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtdabdedbo.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtundkagom.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtazbwpkon.html

[U11] Py：生成器表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtqrluirby.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gtfzxpmhgr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadfggoqg.html

Counter(arr).most_common(3)
来源：http://dali.nanxuanxn.top/Article/details/gtnvvgihlk.html

[U13] Py：固定长度队列
来源：http://dali.xinyue.icu/Article/details/gtbdaefygl.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtckinaczr.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnyhpcae.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtzgljphqc.html


<!-- 参考信息 -->