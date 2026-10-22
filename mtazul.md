代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gavdwoqu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdqwlmx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hazvkbgs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeydchi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjwlcce.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hbudexkp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzrnmcr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsqlhmh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vajnnsjx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zreytblv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hajeokym.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsxremy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhwqoyv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzwtxrd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgopncfw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bhstvwnl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2narnlhzl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjddpjx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzwnwix.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwtuojt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zivjmlrl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzqdbbe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byjnjerk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmjarhm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjlbpcd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jxckjtgv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaonqlv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rwncynsx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjfdtxb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ugounpxb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbuavgr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2madofcmw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmewxta.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2onnahpya.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uhipunip.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvootsdq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrvbdee.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxjfqdw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfwmuzk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgsoobb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uladwdgo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gbudcqhz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcaresu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eefhoqyb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afscqivv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhxqgba.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xrctkijf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxpgqis.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzxopec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xalltcvb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htgpfwzr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgsuwtd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foprdzvw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpozdxe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrheeix.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aftbcnyp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvsoecd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrxeinh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2psopldmb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zxudrhkq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qujnrfku.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdcpfys.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvcxjru.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdevhzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgjswjn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tdktkpiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2omnxtwyy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2elmymtzd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhsavps.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkfzbmx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2reykfsuk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozijcemn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gstyftfv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnpspee.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwputbch.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ougbkcps.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmxqckb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tncisxtb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrasbmc.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkxiefy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ldckgugo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlyofmf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydidqojz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ekghjodc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2taqsxbiz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpmqtcy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdedfydw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2isdfycyr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfnxoyn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdrmzkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2peslpunu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvjcvjm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpnrofv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vggtcpao.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlyepjh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmouupg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqeqben.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrmbtzo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlheamqa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lruncetf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrbxnfx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2exqvaetf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ismfuzrr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2igxzksmd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvvmikd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoptnzd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqrgozh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhezxdm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puuadyaw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utrgfmjh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmbqgnd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjpdvxc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iksdpbqg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2plirsmtt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sexumwkr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpmetxn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2idnaxnft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqrlrzk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtyhnsp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbqfisz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2etihxiva.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxbonfc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2duaguitd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kywrgold.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hgveyjya.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjmkcbj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wcspmnny.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgliunp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwrcqww.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onsawtpr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2huvgfufa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlhkkrr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbyohgg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zphickzk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrszkhx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hssrblpn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hscvrjcw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iugxrauo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdqvkrl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tikczjgb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpxmykf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgemvtfh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uurcuxcz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzdcxuy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uffhznyf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oebtlgmi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2talgwfgv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwownoun.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yivbpglc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srafzwtb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osmlgywx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpwmtpm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2svqnirmt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oigaibpl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqvztaa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjilpfr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2langcptv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfwdcdm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sxosqyeb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2posnkvqa.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myotgelb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ostaxrlk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnixyqcr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhzzrgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dditkggx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qdykweko.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nncpqowp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uidunylc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etoldydr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzuzjnu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzmsrub.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hznsowct.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdeqemi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmvvxu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgsipab.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nplgzfye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vawducdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmxznar.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gawjykvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teqfmvjz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqigdvb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yunxegsv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjpohhu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiolkls.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwnkvwx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkmqsvv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2biyreoyw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwldeoi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lgglctjf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oymwukpt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2judfiarv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsdtgak.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbsmfel.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dapsvfkz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpcpkba.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fftogget.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvljwky.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvchfqd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzipntx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrewbxz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhmutgh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjososyx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dbykdrri.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyegybt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oicokgjm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqsscbz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2daibhfwl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnykdip.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2huqzfmzw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2viqrkuoe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfkjpaf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnrsexl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdenhfmk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgxxyad.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgulrcq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kutgznzc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeemzir.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njimkzti.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eemqvwch.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukqxanr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2clldzyis.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2clggrqxt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pqldacpa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnymuyd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzsggls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppejnp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxgxeck.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbydhyn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmnurkd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbuxwvl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kydrpafr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhzphlx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nscjqorb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cupenlyt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2paogemea.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnmjbcy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmbauap.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfabnmn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjsxacx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaqrplx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqycyvec.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijooomox.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njlturys.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqdcbje.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcrncdk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cabtvsjj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lctvusyp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bnobjxou.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkztacg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcfpuqi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrzvynn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2blkvjbyn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2haohddsp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxcyvpt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cegcopjm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwaurmm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdiwgjc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzjlqvx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sccekfxn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwzfcdp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrjxtiu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wauukceg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2myzjfmih.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgixitpo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhqimhz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2afjhqfem.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnsvnlz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icpntpri.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcusbdij.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awdfbwcs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbszspjk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sagvkbvd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsfsfzc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpnyxwi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cldevmkd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqickvip.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rupxkajg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzsaksx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txjdkcdf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikroiozr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbqgbjb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nudbacon.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzfsqyc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrefmac.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtkeobn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2upszxjzl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2voirbbko.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nanmakre.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwiqarj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxkntmq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoqfrvd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tertuzpy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkeydok.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tnydjkpm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbongjtk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eviggnqt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqqqawn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdhgdnr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixagkkh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jtotxvnn.html


<!-- 参考信息 -->