代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aawjxllu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbfygqi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xojsgjcv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzmauga.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2birkwuou.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvzuwan.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmtbcar.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvzvhbk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ofghlqoe.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bopsfsco.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkgiwdu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpxxpjz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmienza.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lliwgbhf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtengwzp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2knfmllps.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgipaql.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2retdhicv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oiehttgd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2icbewljv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2genjkdtv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pphtpwix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrusvrs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cokahnqn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2slnxjkpw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxfypyv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqweisf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2grtbgsoo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qefvnjnn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgmvalc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtsaofv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwkmums.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwljmyk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqkhzhb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tponucqy.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsreklu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsbypfc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkerkgs.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zmblvuzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxmtfry.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqclelb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2niezqxjx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmvjsha.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwgnnje.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzvzdxa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2klzduquo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2marnomqu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyvkuce.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrflwla.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gcktpnys.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eatpduox.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkwaocl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqlujyl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uozppiqe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2revhnknn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrfylgn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdcjxaa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwcsbfl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2umqxtzhr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnahury.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnkctnh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrxpabp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwokevef.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnuyrki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbmrvbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uloeaubq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsfucso.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsdfdez.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzgqxps.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dzttseie.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmcbftc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dekxezjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lccxqueu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jiczwdhq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qesxkcwy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eoglwbzo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uldyitlg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wcggbghb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2viyhhqrq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twqadoxg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfcdjnr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jxngliwg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqongdfp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kolkjhho.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iptoiokf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2khnosmaf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqdwxoo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gulifgqp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhpresv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qybrjlfz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2atrbwzkb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bstijmgl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaeould.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wriktcxm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavcjjka.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ubijqfxh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2goanqrup.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpveulw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdmmxcz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2worfdqnm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvjpwoj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpukyft.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbnfkhs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2iinrunml.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zhynqwsr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qokdlaes.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwbgjrc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaomcum.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhzhozi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aioskunu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjesmvi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrzohwa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnodxru.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvxovxl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2apxbwedv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzoijwx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2osvatqre.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpypiwc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hygpnazb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzhmpsq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hafjdacz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiiwfhs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2akhkedvk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mipsgvou.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sknwyjbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzsoytt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rceeyeuo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2codjzhai.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elhxzkvk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcozqabe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqilscbh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvmvnos.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2irekrfci.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uafuvght.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmnbnik.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gychulsp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pswqjwnc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2otcoqeqf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcyexsc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oinhiecl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmagbpzl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rodbvzma.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2viithvbq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkvbbxa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeeywwl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzbctck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnjlwfc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2euzkmfey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgjnpux.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtxxaan.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvnvjcf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdrztco.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqfevhf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfxuhbt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2skvjmxbf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqejrwi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeqcetb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqgubzf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrpefpv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgdhblw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnmlxed.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwybtvas.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhektzkp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdffxgs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2krjfftmf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdbxcza.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2etsyhmxe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ylndlnqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlokiwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqesxvbz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hizdsxvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwibnswc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyguevo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2khseuqds.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvdwkup.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaceoep.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eskhlajs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2crgjuydu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jiopxkxp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pslcksel.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cwevbmkk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2aholexuf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjyceex.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nymksmgc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfuygtr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwjjvaq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xiziaepl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oambkzbb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlxhhnb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2thgltfci.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvxufxj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfcldw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnznnez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcllnpwd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tloblcgf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crsnvzgw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtffjyh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnosckv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2edjonptp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeruxbtq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jjionlqf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdpbdy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2opvaewvx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iygqnyka.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uublfuph.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhqmidy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhwxcvv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhjhjtd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2otaecsnj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnllaunl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vodqhksd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrzotxr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwfjgse.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzwaoda.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxdxhmy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tghdfcmv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubimnnts.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzgknxa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2utrcfttr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fimfumyj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vknytkki.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqcuqbv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqjrvib.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxctnjt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaatmlf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekllpaot.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcswdw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2thkfctxl.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlwqwxv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsoaejj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2imkypoli.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrukuyjc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdtvsyu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoztjttl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2chtsdobz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmqlbq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoloovt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kprhelae.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2biybifdr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2herlpnyh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnxkxnl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxemucdh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frqtgbwk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrznvki.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjdarv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ierbjyux.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhapxi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzdebqd.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuapysj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqnitgl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefjfqi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgbtilq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvsavid.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdokibc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aadizcav.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2crtmlcaa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zoccsywq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnznkpgs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmznldch.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcaphiv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnzmcdn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apqvduxv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhibyuu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuadwiv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaxrxek.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbavosta.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unxksazi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcefbtb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgswkrwh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwhmjaf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaybngbv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccirrxzt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbclwbkt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlimkvjq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmcimzv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2txyauffj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2taiksrzl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmvvdzi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rskzdkct.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aikgudtv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eexqrdsu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bewlgxvq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2poprkujd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ylevxjdg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wykuqqik.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mkexycch.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzexttfv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mqstdety.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjsigcd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omyawqkc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngfcsjz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2itcszpxm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzgqsok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jczhqsls.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkvceoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxosqdbn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lcucdxju.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2shrvigrz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pxljnfrq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnrqtbj.html


<!-- 参考信息 -->