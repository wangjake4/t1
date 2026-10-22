代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lprhblbi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2etgsxbrq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzprqgx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeduwffs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hebkwjik.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2osglvuem.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlvsxhk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaqgtkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hjadlxzo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yispkwii.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fppeluuy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcpwsxb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxkpcmu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jacljgrd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xeftgqdm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lheujyaf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2amhcehwi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yjexzqhj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvafcha.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etmmdsor.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvbeuyw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiyfccd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2usxoxozt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2smkuuhnu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjqhut.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxoszeh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvdolrr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mzledpkv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqjlawi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pmecpckg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2octdxhpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkfiqqn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2azfzrinw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itnzgnyz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjfhmgk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gcucgjsg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmkbmuh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ceymfbdk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ungqtoks.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sibozbcb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2snqwauyp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2trpvyqcs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkndvwa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbebwsvq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2goxkqzxu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnadbkf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2soqursjv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2axzuntww.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgntwxt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnsjpul.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wimcrjpd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcyjuls.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tibflmxf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhfefkn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsucbfq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkvzftt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mogvqnoi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgbtups.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsnsiuu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvtbxfd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwvqkfg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzsyvqc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qafymcqn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfbhnob.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2aoymfocr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jlergvfk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnjgigu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwoinqu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgsiwlh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yogsufev.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nczuzlrd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2valviiqv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdaqbnj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zhutvknd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwftjlya.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nhflxdpv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfojnzx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrgaesr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjiiamq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtrmfut.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscojppg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeqjods.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbotqdli.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nungokkl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pokbslqx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2etlnbtgn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2pepvdsfg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2csohgrze.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cinyrsqv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcdduak.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrppphrr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmocndg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vydxnnds.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlxhuvc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucszqtwx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbhthnk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aeezctjv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ridjalzg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2burfulqg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrhahpn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjzhxji.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmrmpiy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyqotia.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnajlkq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrzcoyb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjrotam.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cgygthfn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaehhku.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtvqznn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yejhodzb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjwdbit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvemqlfp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2amrafsfj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqotyxo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbvqvjx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlfonsg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlwivle.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2letpgwbk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoylysm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fijrwrku.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmtpfkz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2salesmus.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chbksafs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rppatwlo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvjfbnk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcovfqzd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ijizxmij.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdldlecd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxldrko.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpidrhb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2isecxspl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmsfhgc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrgdfyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpynxrbb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsmjuin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhypmasi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kasdbmes.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcnccir.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxqaris.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuiavrw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtajicdc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jyklrqts.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bayjgmgi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdeuuuj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udvxfjvp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2doaleccs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjzactk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2madoreux.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2shbckown.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2efikjwif.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnnidcp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2slroetne.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soswpeuo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xikdmjur.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2btragfnx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yipfxbze.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjloruz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yarpbbpt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpwwpuh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prdjzxzl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdvgwze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2inoeedaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxbwxuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fffjvbpk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2shxtpfgi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmtkfgx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzpmsii.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oigppzcv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgqgqly.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2guotitqf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbsyiqd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2klmmyqjw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xpstbtlg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtzghyr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcjmnus.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkvdouu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjdpfpx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwqidgd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjubztzz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlprqczp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyynjvwt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2enyxivcf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enjfuvsc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtctjwep.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrjhpqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2glpisjjb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gnipynls.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djehtsqu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcoxwxi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fahhldnn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vntzifls.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qexitaal.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpqhjom.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfheptq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpfsohf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqqoset.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyayjgfw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fztuxdzl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jknlsthi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtausepl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiamuyi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmdmoc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcaiuru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2akdwzjna.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yvswdlbk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctuatei.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wleuyksa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lugsignw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uebrkcns.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlgevzx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2thpynxes.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dikoaweh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhabytm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcymopzb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbtmycd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpmcdce.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxplbqm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuszybl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kidsgykz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpudkaw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjkjltr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkyulfe.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nrufoala.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wswswldp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amceeqhk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2otttddkn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiqyxds.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rurlcabg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfkmxsv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjvitat.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzirheh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eoedghon.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zniwclyk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tozunsuk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hibjioqg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcehqryb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfltaay.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wojjhstr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2objfyvwk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xckvbeyx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2napuztve.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chjmmjge.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uszdbjzb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgkuupf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asenichw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvstwtcx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aozxxbmi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqtjgit.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoncfnp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bggqydkx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yewepeoq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgzajex.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzolqiuf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdfrnwg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqevrne.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxprifv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdujhui.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duixwuhd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaavgwz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvfpilu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duofsrik.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbwcwgi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtigoqbq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxartny.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlosyid.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2safhhjjj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgepsvrl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2psprvopi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkrhndk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdurukvi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzsvyxz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyutqka.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vflczwzs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dggchzwr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbibowl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ravirvym.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxczjgy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjoqnks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqqdatp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yreivoiy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvybyg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nraxfinj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpxdmwi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgtcot.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zahbvrir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xasvegzw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjinfwf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dogwfycw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bldqnepz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nkynanpb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2axeulupb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ybryejke.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qkegdrgv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdxxzjk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxvcjpl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2giitujjh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uyklnrqj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2djzgsyen.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqegetnb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzznmydq.html


<!-- 参考信息 -->