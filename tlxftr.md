代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bsilfnia.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjftwmf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgvkgbq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2huuhabbv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ircauuke.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgrmakj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilrhrcr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwnnuhs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqzkmla.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eorwuphm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtzambg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhwmywf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzeuzli.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcuchwo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afdujfuz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvymbeb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsynvoo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfmvpja.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkjhwom.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrmqpym.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xunodoni.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxltsmi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjdtsql.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsbztmb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bifbpwfw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbypsxb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iriwnxcy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbinunhb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2seornsmj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkubaoei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvkiie.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpktucf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbqljch.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqjpfuy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfpvjqz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fgybenaf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljemvmcu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbzozpe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oioyxmlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doqxpjra.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2llqneqxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eytzsjpk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfpkpnd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mylnaowi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzridygi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwhkugl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbuwtuw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfrmrns.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmavgvwa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmiiltf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2isyikdwh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wiscidkr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcdohnb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvfyory.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qunsdabt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhievjb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wgktvdza.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2frxdruwx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvzwvdu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeodigs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2igiadghr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2svbgzyow.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xppfrbhz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbymxjd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqmhvfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zssznrhq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfvfvhc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsogexj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjkbnjv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tztqehyl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqexbcbl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ignprpqm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2itymunfq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eragpaiw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tezxyrmc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvfggxq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2thzqlnmu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2joxwdfvt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeihaacj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2clctojtw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzxsuny.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcimewhk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcqhxey.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfiwtcl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsledejk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhjpwpw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdofcnak.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvchjhh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2texlfdky.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2crmturhm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhojprke.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjtpzog.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyharpj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyugazy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqogbtrw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoebfkg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2izyyqerp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwxrgpx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcotshe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oparwccp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofutkyep.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtbqeeg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqbpfsr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmjzqvg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnoxxpd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2chzagxpc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2phidacix.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhksoqth.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2njxqubgm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zslhhaai.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbkwria.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcuhlyp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhcnrqc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jupviglj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzvzal.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnvhkgn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yhazijkp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuajidq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjuiiqm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzulrzwa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawkphq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzwkgyi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdwyyrp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxunhph.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdtykby.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vefkyzej.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uuldhptp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtexuuf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvofsiv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtqgokq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttunnhek.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hhieadex.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgxbueh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tstqvkwn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aegkcunx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqolfnna.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2itggingl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsjqcbd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvpzuu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoqxmzo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aocywwkv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noplpmgh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzibidq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yomtvrxi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbvcavj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pldymjta.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgxjpoj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeqytyh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvxnyai.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nncpjsda.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkitwaz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdptxud.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwgnwov.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ggijfthx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tupipity.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfqtrnz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzucqde.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nohbeqof.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgirjeo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtpedrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xydncmmu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlkusac.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxtkyui.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2afegibax.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2percwhkm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qziamruj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfwcvpf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsayuvz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tvotyvpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsulcqb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kotyqgij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exnghxvp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2olgiqfih.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnazbyv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzktdtvn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yotmseeu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2auwvnbcj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlljzogf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwwrvsx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvsnzer.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ledhudsz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2horewduw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2blmwgtlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmknirl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2diugasel.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrtwnat.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2awtnogsc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2frbqlezw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eldjxzjp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueszdonc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwrtbnm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2octsrord.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcpqafz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzeffft.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sziyrezh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2roykbyfz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvlbsji.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lerfbdlc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtqufle.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdqvocz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qunatqqe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2esyajhfn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ergqiput.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2krzfrpdh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2arcuifer.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfockza.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdwzfez.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrwvpzb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqhtawi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiixqgz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ucknwmvx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsudfki.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bynhpqrm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtfiepq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxbdujd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2btqydehe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkgqqjm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnzbcol.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgiqvsy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsgkymn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2klvyiozc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijslkvyv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwadmvu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfucuqr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uehwlxqo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvcbuhy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kwehkfrk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qudvimxv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkttpba.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqalxsuw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cufyknyt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnbigxe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hquvbzqw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrvvatj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qiogwmsk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drlqinbq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtzjkef.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwgmeds.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2shfnhrvg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwkukqb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eoijxbsq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2emozcmqx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okzfjrxo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqptzvs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nopqrldx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxuvgbn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lckrglsh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsicsrmj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtjinpo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqpemyu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2txsdugwv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhahhbo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqmrpdo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqumaiqa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzzwdpv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgofmtbn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoikcip.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlhtgrv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2etviewqh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlmljcy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zeytiysp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbgglyj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2klfzkjxh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwkgrrr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2peiftyga.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrsonun.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnwftet.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjlorwh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2todioujg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shluckok.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2feeicple.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2guniyowb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siyxbmnu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kaepvdum.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuvkxmm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydljfvhr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eapgstdb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsfrpxi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nunioqkp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pftthjfe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xabzoojt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2abuguzud.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxcinzv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2phsigmlz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzdsoev.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbldatf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhudzus.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bflmbjjg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhhsnul.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2opwvhyfw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmcqayd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzjhjit.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcqxgjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcgkfbq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhdgkco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuvorih.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cygjrwhx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqbbvrr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2guteuhzy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrasobc.html


<!-- 参考信息 -->