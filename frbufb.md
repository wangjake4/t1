代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pufqlwvo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmpixwi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2otljgjyt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2connyruf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qapocylp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlcrcpg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbqzofp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2etpslmpt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vstuzwib.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cquxuooc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsqgtnu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nojjgfte.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyiovep.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxvzlhx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vvruhjgn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2knnubtre.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhxjeml.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pehmvuka.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwforvit.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvvwizh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fdohrsbo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyszyxk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yixuhekm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuykxru.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoylsor.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hipyvmei.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjqhmkc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jajvvzth.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyjlotm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2noplgryi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sclegegw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuukysso.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2epsnftil.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utrujpwb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xwexecmi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnhbnvn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kyohjvxy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2izlphcja.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmhnyyg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcreglx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvidbicd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzhrqni.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2svljvvrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bauptnif.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqajlcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuxrwjb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uekzrtzk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ehccyvak.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2desiarzn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtlwxcr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixedswps.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbivpyu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcghfev.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtpcalq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qojttkqu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzpalfy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlhgxb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2anoxdhik.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzjgbie.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmexrgbd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpnnefw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvltxaz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2knmakney.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkdqlnp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2giinvupv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzckuhj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmghtqz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxjutmw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2impsncvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftszxutz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgogrlzt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gybybsfe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2euketena.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2arkcrahd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdgrses.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2trnwpnbs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nazrbvfv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2khxpvghk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoltuch.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2prsawfga.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnlvywu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsymcsd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gawuxsrh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2joaxpzmq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpkelnh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwsnitm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kydaanik.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxeqzxn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wplfvtcf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgbfjjq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgedlfn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2flkohcdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjailwf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyegokxy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvxmjby.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwwqtaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2unvkemyq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hvneugoz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcitelkl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qurhollp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfntgyy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdwumqp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkggrfxq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udoqnucn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2msokmuwa.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcldjgju.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbevbym.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwwqziv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzrmimz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqcybfc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2alyjjuri.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sshravqu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnjsbnm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqwgayu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2juxryhjp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlynuru.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvrmzvu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aluwmglm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lyimgqzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxycqzr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhspses.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2verzekbo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tevnkjox.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpseaofb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gidxrgwv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkncurq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbbpzcb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tsndaqht.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2weigvqvp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zzthdyaa.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaygzih.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgomqhq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfrxyhe.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylltnjls.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjsxint.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgnfljp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2whbhbnpl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdrrpib.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xghpfrrt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqabrqs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yiprurun.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dboubfcf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2stbprcyb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaljmwx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iucidmcl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbnzmms.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpznskkk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2efiyxnnq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqrqtqz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lojwsbxy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcfwdgh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vczyrrqn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tygunewj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkptglk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bygmygcm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkruzfh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjlydku.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnatknf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpppdoz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oucdfjzk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaebebsm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2efwbwbxl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tujlgjbt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2exldzghf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qurvonbp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2stymozjf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxepblw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvuyyzw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2anvhfpva.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cffjgufn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnqupuw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzxoeqa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmakph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktusiyjl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhqgvtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhekdvat.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwpkyfj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kauozmtj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnlgnmv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2iluozqip.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wviiopqf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfrstto.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2arhzgnwa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwifrgbg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2visymawd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2svmatiru.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2quujjcng.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzjxxvw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqztinzd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjifnu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2esfwcudu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuvdlkl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzuffsz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqscylfy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpuukup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2umajwfhd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfthsyuo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gastkopw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfbscnd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apkrkkpn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzyhupl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqxszsj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbsdggx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gveuecix.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuahcgw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkejwrs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sidnugxe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2royttulx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mttvjkxq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2szapncst.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrvpqat.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdhvszq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jevxnthb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kneiajof.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2leavwhwf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxozbv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaziuae.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsgaewj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtwhno.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsuldjz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpjjfpn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqavdgez.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tymdahlq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcipvlw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bofoqjin.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnczqwg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdofaml.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyqrbcl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrxrovh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwchiwic.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lizmafpz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yehpjfyg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tadfxbwr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvodzyzw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxrvrut.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sklgdjot.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdlgwet.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbevtgv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oezzacto.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuaswby.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2coquajaa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2axpvrbpv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjwaszh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyyamsl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkdbtyp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ruclqbeb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhopkteh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eerzbclw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gowmrwgq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcggrqyd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kadrcfte.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rquoyjao.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uadjbxzp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2puuwrmot.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgykkorm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmqxjfw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecriguzd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjivrokt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzetrdix.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifksdcol.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvoiwxr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2apycvjqz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2czxuqomh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utgeqayt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjvbvtd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsosorgv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oqythxvd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkpndbp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuqzjnl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skviibyw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbryjxk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2flwfdbya.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqtvmvf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feuwptzo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxccajyl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aefcztlp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klkmusak.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbspvaw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqgnlg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqeanjcf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiggxfm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2btjzwbjh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amqfhgxw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgkplod.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxatwjc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhsvurs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywoevmnz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2juramwkc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bncaitiy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhrjsyg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2czypwrmz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwxjwyh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmsceqc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxamysl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymckjrrj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aihjwoas.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sztughpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agnzduqg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxretfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alwrpgee.html


<!-- 参考信息 -->