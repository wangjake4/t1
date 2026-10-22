代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbcxljl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2neqyfzha.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2colvhpec.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2muinzvky.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqfbqiu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jneqfkoj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsqutby.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmfpgfa.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cngduhav.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcqlhvp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rleozmbi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwajwglv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jkivcrmt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lzexrtau.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2itnifvmu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2frnywqqr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjnicia.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ononszbv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnfclog.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbikoflh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kegpcyvt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vabufrbw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhumgwbg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsymmsl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjgtipa.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpypesr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsbuxke.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvnbbwu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrszmdtq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhlkwjx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtsrfdb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rlevaamv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkiklwv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzjpiuv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emvtavdt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgrstcb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pidmdxae.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvosntm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpexuzmr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2czatplsm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtxxuwi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyerelo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lemzdezz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcwfxui.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twniqvod.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2frjdcibg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2chjeposx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aoddxpln.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxajmo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhahcbe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uttgosjq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdwkgaf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eefrejij.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcsqcvl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaasfrjo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzimxbcw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwtodzm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ublwuxpz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nibtcbcl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwduzgk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlncphp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqkrnce.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jlifvnkf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kutwpfzg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cbawsrjo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkqotzn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmmmuoa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqwkggv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoxsfcm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdcfvod.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiipmac.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwjuzot.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkerhsro.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohewfoi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtouzak.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryinnqit.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrcuwmd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kaswhuhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eemssrbd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxvoryp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewynnsrq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xshfbsvr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqdmoxf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wiocvcit.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvdkfti.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsdvhdz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtxhjev.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpnyxuj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2neuedgtz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbesodj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2frsqrgxw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpzhsw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvltxguw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyzujla.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpionug.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sovhzcze.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhkgrhd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiotmjrp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnunhglc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gecadgbh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsziyko.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoeuokl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqqubne.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hxitzuzn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzxfnsb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2auucuisj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2atbsfvlj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwzajks.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdhwqdk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxotihqw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnktljq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2skefanye.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yiovjijz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkpstem.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2svjvsssp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaqmquy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhtmbfm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwwkrxh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sccovpux.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mebpyxot.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ptctnpvk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdaxpwm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xegxwzzu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfufyrr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2phywrwpj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csghunrf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dplcaqkp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcksawuh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtvjfbg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwabibov.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjtpurh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuefefy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwfhvfi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgcxexu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2emvuggrc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpzqipy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbglatg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcgewvt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kziabqgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hodfiyab.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vozlrzxz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntewvqum.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sxatddxp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aonoaicc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eullljtl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyyzprb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsctydo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prklejcs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrudaqr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkckdacv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdhclwv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqladcn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxtevit.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuwswbw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lojhsqsb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzyoewu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prvyllou.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuocwyh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2djdxyzna.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrbebfd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwbzcjv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxxzcux.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyicrwt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tyebicjo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bakhzfqe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrudxel.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2avejfzfu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2veuvxahw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeshrnf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hryjllib.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pylzlffe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eomlhcdk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcbjbcs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2txeupoey.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkurgna.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyuuzkr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpecofdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoevupl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvovsedx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irwvrbzq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqyccou.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiahycn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbigvcf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxxtzqs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2frkwrugp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adspwytr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2olyphlrm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2resalknq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwnxbod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnxvlck.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dsttpcpw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiyzjui.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbyhfis.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqpmnwq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhfjhjd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhsgbyu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgsxwnh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2btskcsoc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjjcihr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2isrqrukq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yufmlgtu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsbozbq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ojktiiom.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yskjrouw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwvypyg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blnczqxa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2grawthnl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zptwvnoo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kifqtocl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqsfhwp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuhxyss.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uojgykfw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgesiof.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2btptowgy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyeepab.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwpzuef.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2axiujnxl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpxtzeb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtkdfdw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnadgbch.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjryzoo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2itlkmxig.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sgepsfye.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrksqiat.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwpfkeo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eilcigdd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2drbfeasw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvtieq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2deumrcij.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2alujpndn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaawbie.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkkmpam.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoaeqjv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhvwvgk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gpebmprc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sibrbxvp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qsptizvn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfhsfmc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kohmbhgt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaazannz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlouzen.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qflxlgtt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxzyher.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvqpwoj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yluqxbra.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oegoknal.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lelszrdb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2czelflhm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2anuolewm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpospjfu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqouctsc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pswghtfl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrjpzaw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2apnffgsy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgxmhkm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bklitofu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwqcnhz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiulpep.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoszrcm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqkbhjt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjcadwv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2buvhnoqa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwswvcm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2myytsbui.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atctvpbf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ippzjjes.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvluzxl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2runqzpco.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxssiyk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vltkeyyb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2roqqaddj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyqomuh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyypsfe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wynrwvbu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwplfcqv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmavngf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mekbtkuc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwpsyqe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaijtbks.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcehciks.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgmctmq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tswifwsp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jawoinuo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iitbukzt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbeigme.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgofhyjx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nafiansd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qrssabnx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2royjwkrf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhtkejf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eraiboks.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2krkjfchq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ferrmoyr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdflsng.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoygmjxl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpkjpip.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2exdumhaz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyapfdi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkjhodp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hvckwttf.html


<!-- 参考信息 -->