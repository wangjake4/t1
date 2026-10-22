代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxinkj.top/Article/details/gtpnxtmham.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtyzhkduii.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtdqmkcbal.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtkdararkc.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtknsorfhq.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gtswunhcie.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hysaishi.cn/Article/details/gtglibcdwm.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtsggkidjm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtagfmkhbj.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gtynnuptsq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tianlin.xyz/Article/details/gtsombuotl.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyjytvqg.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtikilonzc.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gtjwobcgoz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtfexngvfi.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtzfrzmdom.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtnkawnbpg.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtehvjrsim.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtkbjrilen.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtohpcylsn.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtmpudeeez.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttjoynjlv.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtgjcfisxc.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtwyguqjwq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtbmnsmtny.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtwijavlko.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtiyfvyuzg.html

[S03] C：读入整数
来源：http://dali.jqgufenzy.top/Article/details/gtnsyvfpbj.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtgaqwjdgi.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtuvirozsg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtlszardwt.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtqzijyfpt.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtbyfmcstj.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtcmojgklw.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtvlbflkrs.html

[S07] C：数组遍历求和
来源：http://dali.yuanzhike.top/Article/details/gtnuscunil.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtanopgnhs.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtzwjtzdzy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gtqqoyffie.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtkuanatda.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtgvsesayp.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlufxzku.html

int *p = &a;  *p = 5;
来源：http://dali.0kj1m.cn/Article/details/gtvjaosucv.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtjorbqtem.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtwuarzxxc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtnztbxpez.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gthezzwmbs.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtljjnrvuv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtbcgwowng.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrmgklgc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ppjwa.cn/Article/details/gtomrmulmg.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtibfaqnvk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtxuhjynwc.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtfkfvyoat.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtswgnwgrl.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtohrqppeg.html

x |= (1 << 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakiwtqow.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtueqzixyz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtjnbpirfu.html

[S18] C：命令行参数
来源：http://dali.hysaishi.cn/Article/details/gtjljrcchy.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtusupmppj.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfyuknig.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtkubshkpk.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnskzgoy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtbmbmptat.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtnfryovss.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtxwowhain.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtwxmcxnxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gaohongyu789.top/Article/details/gthnpfhibr.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtjjouipdf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtqotmvbhu.html

[S24] C：获取本地时间
来源：http://dali.ppjwa.cn/Article/details/gtexbjnndu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtfrztiilv.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gtqeuzpemx.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtstfmhqmq.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gtbufzgczv.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtznnxowvg.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtemlewtot.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtiddettzn.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtrycuozpj.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gtcnzwokby.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtktcslrxi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtzgtnnaba.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtbsqqwhzv.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gttodokdua.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtlgcjpowd.html

#endif
来源：http://dali.feifeiyinyue.top/Article/details/gtfkoehqsi.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtoymgrnsu.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtlfinrbdy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yonumen.top/Article/details/gtnsnznuxu.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtcczlasdt.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtdgeevsrz.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtzblqrboy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtqasxxrfa.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtcgezfbxi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtnewynigi.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtdfvlyifu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtrsgqnwqc.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtzonjbhut.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtwkgoudvu.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtnzwletda.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtlsigfvmb.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gthiiklrkb.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gttzwvlumn.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtulkeqkjr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtkaivgblr.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtyaynmuob.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtfaajuysa.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gtinyuklbk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtmpuaaros.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtwhtrkvbl.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtwavyupsz.html

[S43] C++：智能指针
来源：http://dali.9152youxi.cn/Article/details/gtnwbcxwwv.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtfvqbbaad.html

[S44] C++：引用传参
来源：http://dali.mhx1999.top/Article/details/gthcrxbnvg.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gtoxesehyk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gtmmbjsarb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbhgcdem.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtrnetsrgc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tianlin.xyz/Article/details/gtuwwuahru.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gthvowsrhz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gtqdtqlwpw.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtiubdmpmd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtqdwpmtgs.html

while (std::getline(in, line)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gthoaprdui.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtatjmsmsa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtwabazaoh.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtyrvuvnne.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtuzsdwgqm.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtjszibdkn.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtertcojzz.html

[S52] C++：const 与 noexcept
来源：http://dali.jyoumei.cn/Article/details/gtijyrxekj.html

int size() const noexcept { return n_; }
来源：http://dali.yanxiufei.cn/Article/details/gtxqbdgrci.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtsfpykvaw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtnrtbnfjs.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtfazzzaoz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtzxoygktk.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtseqbjwyk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gtlrcvmvaa.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtbfcumulo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtzorgnpjy.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtkbamanrv.html

constexpr int N = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gthxqdazhj.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gthfulhtrk.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtgqltkxfl.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gthljgjjep.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtcsdrsvrv.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtiaawdltx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtedfslwbc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtffomprpt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtflgvvdjs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqzkhvdzl.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gtlmofjoyi.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtfrvqnotn.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtnseeaevr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtwcfecemg.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtsfgcteco.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtkytwuchr.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gtrvhnafoc.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzlaedxf.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtfzbwkpdf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtwgsxmspo.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtngrbfgkm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtzcrrlnut.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtpwfyslzi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtrbgjdbyj.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtnzcnxjno.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtcwvqktqb.html

[T09] Kotlin：扩展函数
来源：http://dali.hammf.cn/Article/details/gtofjcekvn.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gtpnoucvat.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfqbdemi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtzcyuqtuh.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaywngfq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtsfotguoy.html

[T12] Kotlin：解构声明
来源：http://dali.xziqi.cn/Article/details/gtjckrdyji.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtcksoaflw.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtzozodxiv.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtdpuwaucd.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gtykpillzn.html

for (i in 1..10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtndfrmzkk.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtwsvuohtj.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtuwinfbsp.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtgxaxoijg.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtqqmiwfjn.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtmvbzlzhj.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtkqqzhpxy.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtofxejyiz.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtdnlbfqrs.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gtphqphqgp.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtoitrwjcl.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtqwpfdwvw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtopeyqjoi.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gttxjpfhoa.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtwcokxpve.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtvmpkvldk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtqgmahsic.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtyumfzvtu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtfcjobxcb.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtgkmtvzqx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtdabiwpxs.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gtleerzchz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gtltvnmptk.html

[T26] Swift：类与重写
来源：http://dali.316326.xyz/Article/details/gtobitaztt.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gthuynbjsr.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtdcjxidww.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gttobdwihj.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtduacvenm.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gtgfnhvwst.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtgplbmdbs.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gtubgtyzdh.html

[T30] Swift：协议
来源：http://dali.yonumen.top/Article/details/gtqqrxmdve.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtbzrjsons.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtffkythrm.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtfocumeef.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtokodvpbt.html

local a = 1
来源：http://dali.316326.xyz/Article/details/gtyiydnaff.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtnnbfuwdz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gtfiuczhsg.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtwjfhmzpe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtfwuwiwus.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtyttlbcug.html

local d = { a = 1 };  d.b = 2
来源：http://dali.quarkkingdee.top/Article/details/gthiwmwzum.html

[T36] Lua：函数
来源：http://dali.mhx1999.top/Article/details/gtgigkrabf.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtizoqsyvz.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtpuenvqwk.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gtbjwgcfcj.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gtedfigmjg.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtwfxqmmqp.html

[T39] Lua：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtyizlnqcl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtyiyhexwz.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtcysvgkpq.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtbrkivlww.html

[T41] Perl：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtfxzlukvd.html

print "Hello\n";
来源：http://dali.xuanzx.com/Article/details/gtofqijuvw.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtseuuectl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtzxooqhzq.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtvzyloife.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkouryfrt.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtbltkrebf.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnuxjzsfu.html

[T45] Perl：数组遍历
来源：http://dali.jinqigfzy.top/Article/details/gtjvillamx.html

for my $x (@arr) { print $x; }
来源：http://dali.daria6918.cn/Article/details/gtojjpnwti.html

[T46] Perl：哈希操作
来源：http://dali.xinyue.icu/Article/details/gtqquaigbn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtlswkcbzp.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gtzybwhvit.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtdmfengrl.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtnwtwxedm.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtheewypmw.html

[T49] Perl：函数
来源：http://dali.shangyingyoupin.top/Article/details/gtqpanghyo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtqfldncbz.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gttjhmrwuw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtgotnatee.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gtmmjxppvt.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtapbilbcn.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtxkcisaqb.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtrqxkggtn.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gthcqnhmnv.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtzffpmdst.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtnvaiezfz.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzfqxzcq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gtzwvoaqtu.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtenbbnfuu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nwbrower.top/Article/details/gtegzewmhs.html

[T56] Scala：样例类
来源：http://dali.bjfxy.top/Article/details/gtcucrltsd.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtaicwkzbb.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gthisizxpj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gtxueteqfk.html

[T58] Scala：函数定义
来源：http://dali.daxiang520.top/Article/details/gtgxfalnyj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtooffjtur.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gthmfyjsfd.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtqimiemps.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtczaubtvd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtndizecmd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyiigicir.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtrdwqspdu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtscpelxpy.html

[U01] Py：创建虚拟环境
来源：http://dali.fengsongda.top/Article/details/gtqtbzbwex.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtjpvphkge.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkixhweox.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gttsiriudw.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtapaeasyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gtfxefwnej.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtvszzmdmi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gttoowftyp.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtdiebliid.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtndjyfrwd.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtdvvfwxcj.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gtvnpyfwwi.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gtjcygldxr.html

{v: k for k, v in d.items()}
来源：http://dali.hammf.cn/Article/details/gtheehpdlc.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gteyhdzwae.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtxrbkiwap.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrszcsqq.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtvgrcvose.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtwojnqlxs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shuidangran.top/Article/details/gtprjmrszk.html

[U11] Py：生成器表达式
来源：http://dali.cucudq.cn/Article/details/gtzkmyycvo.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtmxcpearo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtofdrvwfv.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gtymjdpgbz.html


<!-- 参考信息 -->