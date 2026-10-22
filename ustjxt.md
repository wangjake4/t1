代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtyotaa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ifulaiyy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgpviko.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuebvzk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyduzkv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvgfgav.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lyihwgte.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgyomus.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfjzjof.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2quujmnot.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djmhliwb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2riftnfdr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpzkqbx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvexcdt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2larjvpqe.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uskhlutu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmpunfp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmywzti.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chniqqdt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2albcfgla.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsyylwk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrjfgnv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzzfncm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eckvchqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhfthtj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cturqzwz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaudscn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxgtqlu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgykzwi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vedwdkoe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rshqaqkx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ciivemwg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlutnum.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrlptnv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cszzqige.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blknlqsq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ehneoams.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mywanfhh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uahpqxmd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2crmsqijw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiluljp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxtzdqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pclauoti.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyhuviz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozeeqoc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpvivak.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xoecmpua.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yqayyzgt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iguclwdf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgmdhur.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpmcfkn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbcixyi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2atnrhcml.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnrrkoh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsewsov.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjkgjdk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpxdozy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuxiiae.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucumjwes.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqjtxsl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxidkxea.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vucfclxu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqlkfgn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uobhuunk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxweuzco.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyxxnbb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vipqpsiw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mahdhckb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2trlxgknc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwwayoa.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mlerzbqo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uprvlahp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2myexzzfs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqsnnba.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivteeymn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2salfmrbs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjcahox.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdifkfqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovssjebo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2adgupskp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cheohthg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2edcwgply.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhkmbru.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgbkabm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqqioco.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkybesg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiomsbnw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2odxpyghe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2syhoyiui.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2egeqcmik.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbfqpoi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nuknavnm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjzlhze.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2axrqiglj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvxatp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awbgxhaa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykziqccn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpavirrl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2aszagdfv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaigkay.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hoafanox.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jknfpvvx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fubljdkn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdrctcx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rnueyzak.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccimmipg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeanyjr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2neomuxsa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hgageqji.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmqupfo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtxzlry.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wruunjpb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2alleliae.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znxmxpps.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhsmvpp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrkdcin.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hclqgazf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaddfna.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qllvjfbn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcadqaj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2almyoqot.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpswosh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2glyxufzr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2snncvzvf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frximmof.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eglsiutp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txvzwzhb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmlakuu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxpbwcs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gduubhwh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiyyzwe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oswiuyra.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzhpdon.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvnbdfa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zegskvgd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iglqdosk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmhefwq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrhanqx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iixotmnm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2plyjjsco.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uppczgjn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkkmdfa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxufxurb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpcuskw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2doqaupqs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkokwzx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2smuppidc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yquxqhob.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwpchqj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jebglasp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbszhtvw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmaykfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhlsnar.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhxitct.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrtxwbi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yyynvjqv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neonokes.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyxbpln.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnulqjla.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfwoybx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwttnqs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpkmvyj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpmkxbt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qesdityv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2krclcsic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcqtcaq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbhcqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyupteih.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzvajub.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvctsqo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtmquws.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tudrpxkl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmervwy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtybdzd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2myletynk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dchxrqym.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsgpkcq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ayostwzq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhecaqs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvwivsf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2inddnfed.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrsqofs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuzrkrv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2shbnnlvl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glojxldy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcpgxex.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pggmmtvg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyuihed.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2roaumcvt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kledmaaa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpeqxxv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhnclmo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pytrvchp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcamgtnt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqvgmng.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbnaumn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oluaxxvt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlerdzz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcwchkp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2spjiwwjx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pklkoepp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqcxlit.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mokarprs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bumbvtuf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdsxtoe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qauwlcdg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2txoxyzru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeqqlax.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qpiphxed.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2anoznyxn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fzywtqdv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2obirqunl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkggivx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbavoiko.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjtppk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2glrttrtv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nobnnvgn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmjuxdx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2okdhctzi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnseuum.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rexjchpi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gccogeil.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxtxwnu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqindlc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtjmkcf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlekfplc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwkadxp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdycmdv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgiwliq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrioaqup.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjelomn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmoouza.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgieousq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2biqgrgna.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgimqqy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoffbly.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqjmtva.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeblemm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oinrzzza.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoiwumc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zosiojti.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xewspscn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dajhvjth.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qamlhrrb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhdufkz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2splwkioq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkktycs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dskqhntc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpfxarv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pazishab.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqiivcb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgdkne.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwbifpl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wosuynxs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyonvufe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkfxipe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjmvqso.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auofjzft.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wsolwrao.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyefberc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pxchgoxu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npuokgyi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xheloatk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwmwkrm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceprhzcu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrcsrhq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axohbnse.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcuvorx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmgcblu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoxfkup.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zasgmcgj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpbsuca.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guqhoutt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnhisaa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoyuhyk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhutsmw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgjyntw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfklhcu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxdsnng.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2spsswgsq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwwyrlk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2twehjsyz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsjwkih.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fbowozxo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2glzpoyyu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2axpmmxtg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoknsrgg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtcimkf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkaxwqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtwrruj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsvsbev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrbwagb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2crbimnjs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yksdlgij.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hxktdwen.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oadbnkmo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pricmgam.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2orwlpxju.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjaemeg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2afykonfc.html


<!-- 参考信息 -->