代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2swcvwzcu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfgflzo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxqgzqb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpefeula.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzcygmm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaarwss.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgjwjaw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rskeiyko.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrnxijz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkboipd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxivtpw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqmfjjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yytjauya.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdpnsoo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlrvsfr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mrptljid.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bczphbse.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqkjccd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jopbbnvg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfejwyur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqwwlbq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjipmlys.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2voogzhhk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2itopzwoh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zxckinqa.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbdluxz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzomskyz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dmluhdwv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbritddj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hthbcbzj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ighnmxhq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmndawxn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2htjeuyci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imzqvchm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onznwvum.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlbpbjm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhppsvwg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tovcbjes.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbeepli.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfsgbep.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwalqooo.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fruthuzz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2niuuhfii.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2euldwbhr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2luguiijy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpiobki.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqqfpjn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqqvqzy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2slsgeneh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhaacba.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxeprhb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2imvfmgwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsyojsl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrvoecp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zazdaxdc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsdvvmq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvuagyl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkksgkko.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2emgultoe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jumwzsqa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2llxhnzbw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdivbmi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uujjaakz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpzhssc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzlvpxv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhfwfq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdneyvn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdjmduy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlpopje.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfjzjif.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfwdmbx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtxykjl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxtfcsk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgzmcyv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssreqadj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2idboevdv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2madcurdm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzmjppi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2anbpgwjs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ecughfdd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrundei.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqqpmjw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lglrofts.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2glaraxye.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbbfymk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkqhzid.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sicqbjuz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2duiodgkx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sflhczll.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ammbqjai.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tczcbblo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqivjcf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqshkwvg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2typzvrkf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgaqogc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdjoxoz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gojcwzqg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mivqxtxg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2boqokzlz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnseumuy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2svejwnzf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mosbyvvr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgurbcz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqcpbhn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfncunz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jredemhj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxttlda.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swiwytqe.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmgmdfc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhqqykl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fiybkruk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfldsmvw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvivqks.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrespdx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ruppczop.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ofecpgfu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mognpmqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tdilerjl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2opmjjucp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmptqnoy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfsyuke.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxyknji.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmuvblx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvlhpan.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qlouhyzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkogrvrh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxpamdh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2povxcmbo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnzjthc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ambcwccn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zoygmzrq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvniyepl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvbwtqf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhicmkk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvqpbhi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2meghzuyr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrrhmgk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsukhdkr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oepifulu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbqmadl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqosvfrh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjocygd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gslcmbed.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hlezciqr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnbfipv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2axsstmbt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywtglw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gerlwxwb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gewdjefq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxxnmjc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2larmstpv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2caitddxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzfkewn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yleqbehc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwndkzm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnskjyxi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eftqophd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhmxjdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbunacrq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2brbaeoex.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrtiwuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2barxjpxv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dalguhmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdtapvp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuiogqr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzpgwhj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzkbtds.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaavcnj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2padqhieu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2regdubhy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlbtymj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuxrgjv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiwxcmc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rfttgpxc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ogookwvn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfrxvru.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhngoqn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvmzuxj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjrkowp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qndkengu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bndcyhdf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkqnpfl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccadzgdv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sabkmple.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2elahkcvu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddncretq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2igppcsgx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xylqjwgj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqbdhdb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzssxlu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwpfmam.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzoxyxn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrstqze.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sezuesur.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clpzaejk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bstjdvog.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmejmmr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2knnfeyra.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkhnnzz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfkllgb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2samjijeu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyovwhg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qhszwfxn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2doxmlyhb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzbjhzn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaduwuo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkpvfiv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgudtix.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjaakbq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tixtrqbb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2axdbobgt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzjsdff.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pmycnvwb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqqfizx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tytxjbho.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpaqkig.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxkbctp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpzsycs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2enldemzn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkgvqiy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjwixdw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxerqbll.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gwntdkyn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfaqzce.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbnbkat.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlzhqxx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npaqhbxp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2difgndsz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2khjktavd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfxxmbi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuuetom.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2blxpzewb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkyhfgr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anvrpart.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iypewscz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wugzxrct.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqhldve.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgwhhof.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jspganig.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2treeggdu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoycojz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nijvzhkt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwicaim.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxnnduv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2idlrghsq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnltrix.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyfivpn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfxhzym.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2scuraiyy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdatjmuc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvdkyid.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fscihshr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcntenl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmjdmbs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfbnlti.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkgnora.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2guejgmsf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkdzksh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrzeiyt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfpfgjl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnpxvck.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrlpyks.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgeciik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrfjmhm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyttcvb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzimrpwj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkezumz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhydipsc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyksxph.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2roasdzzo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aefgqsiu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2psexskej.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orxwrkxk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dzonobxg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgeafpy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nayimvfd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2imlwphfi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvxdpqr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xziogumh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoqmkbw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhapeca.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmirnlb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjleaqbx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2smjvktxl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkbwriy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnvkdhg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbsldov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2guzbowux.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfnezwt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhsbpte.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfpujpv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehbwbs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yrllfvab.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtpwldf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wocaswrn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zfljtrpw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nciicjlf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkzabkh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcvokyd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnftksn.html


<!-- 参考信息 -->