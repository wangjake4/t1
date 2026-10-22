代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ortlscle.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktngozpy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiklzzi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2blifqupm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwdcdep.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mycydwmz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwknavw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2haxualwi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oijmneti.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vujtlwth.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgagpfv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmrxffs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2iljbqrkj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwsdgde.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjrefpp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cdstmxpn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmxdhxo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vljdedxe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvdmizo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjfhntv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwnwpdi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sajpfpyb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcocunq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwdxzno.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwglyhv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2akpzwvmk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfwtqvf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxurlmp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnhhyzw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrygxypq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2swvzgcfi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpwjbcr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2edqfkqus.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcqkmba.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vehdxxaw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2czyxnpop.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsbxoip.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2shiakdza.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzjiese.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuvdehv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhzuydk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yemjsgoj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luuwvvcg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuuruob.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaikgftz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdkgzrj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpvjrzj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxnjfxi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrglxrdy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtaasau.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wimxdzrj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2umglknbw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlggtvrk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpwmrmo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2heegbcxa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdslnar.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yizfeqdj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2boilapof.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvjmqja.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nofkyyxk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyomsht.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfhghya.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqelaajc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgyjstr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cypaghaf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgrxooj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqkkuc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nofiymez.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkotkub.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2espehjfa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vakfhzti.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2abzgzrse.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwqqiyq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwslgsz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gkshiqvv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2khiersqd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sndkmquc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jzidqwwu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2krefpohf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktktuiff.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwusyhtt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwanyyc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqtnyeh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hmecvwoi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2egopvhqq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2weqmxgnk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvuepis.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hzggrrsk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvouwtns.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qghumryd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnznvoux.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwsiork.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqykcmyv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lppbascy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2enjihqkg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzituyb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kchgiegh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmmtbzf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvczaku.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urxctdxu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oquehxio.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwdmbxh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2geawjirm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qokbbjbj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbhvdch.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjljqox.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkhmoku.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bglqtltb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2veepwatx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsskfid.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bglboqtw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzkvphx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hobptnfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzobojiv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtavxgb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jreoqgyx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2amhzotay.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfrpzyu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xoulndwz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgluvex.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2omgqctve.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftihvfos.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgbhtlw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jelndbfk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2idyfkilw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qhchjfny.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcovynw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcrdyc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtikvdsf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpwgmrx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmwqynl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvfagmp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoequzu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfecfpq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbjbsea.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nebafhhh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hklbiywx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wskasmoa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nkybtymw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfjeyhm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwcdbni.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjmpgew.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsjgggf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaczvtid.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoczljk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfazwqws.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcketds.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfjcxfw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gufjcxwl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhusltxz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzdhxnp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuazkid.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmnmsyh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqxkmof.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2txostfbh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2btfupcgx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmicsa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmjcufr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkiimaf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbjwuvd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmqhitf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgkwwye.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxuuaec.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2orttqnsw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2txloczde.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqkyqjm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqvjifm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ckidxttt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bqismdyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbsresz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmqjyos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfbjhsj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rijicuai.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdlmgj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxvwzch.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ldydmvwh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxcqxrm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eppsuyzk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wdndcwog.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ydajustp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tlosdxpo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgbvfgr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2crplqakq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqfhlcn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcyshpt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aktzibev.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ibobvuvd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfzvwwe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npuzvjwh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2orgkxrgi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gukwfcju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkmtktu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzzoslo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eorrknlx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2syquwhwc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vohswmgs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvdyikt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2urkghcrc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdomamy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eexlsbch.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nervdcyy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtbeaen.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxioliwz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2deyfjmyh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2guxsjmkf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdaejhs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxduxzw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyrcekd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fsetdzfv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njlroors.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuvmbye.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwywxol.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sqshhvgr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvvprug.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzmdlhj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vejidfsb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhlthms.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnxwrfy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2riytivdj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrszgbzu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2slxtszew.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2enigjjhm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2edsiigkj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlhckvx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgeskpy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygourxsz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbercc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2urpqnjco.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pkobwudi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2elmzlxnq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwvqlqx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvgyszb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2biasrnuh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeqmqgp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iljviste.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdomyijw.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aekgjmsn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwzehtj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwuvhzu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvhbrhb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pngqguwr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxgdvut.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgztusn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqvzlpc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdcqxlc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfjnwev.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocescjdn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwusgxw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlelnibo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiglvanq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oamimqcf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxmejal.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmceqtpn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuzsnfj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxoyqhyf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgopplcp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoqspyx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2khjriqxb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2myezsuyh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wihujvac.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2holfkofg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxesetf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2irtvboap.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muaftoni.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yprjzsph.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswhryt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyhijug.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kommlasq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpdofqh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eluagikw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruewrqqp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsssbez.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsipdggj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wddxxxgz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrnndyw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgbyltm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdmiksb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsgorfj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lllfrbrb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtanpfe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lurqdjou.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrkrzbi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvakloh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhulsbj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pglorinh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gilwmjyq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwbjouu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgncsogn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzykknt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsufffd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqepegng.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lddsfzeq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jthsmbko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpmjnmy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrdjmbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlypxhvx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkhigyr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjcbzel.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xefhlrix.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ykltyhsy.html


<!-- 参考信息 -->