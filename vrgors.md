代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tojetuyc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsdslzl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkonema.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tszzldef.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ogubfiog.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzilrmeg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgagycb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kshgtcru.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ydszxxxr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwybzuug.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enqskvdh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dysjkwuz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bqutrkrr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yymyulpd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjldjsd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kebzasln.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzdlqjk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gaykbjeh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjamxnj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2onqqdkxy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnyisqq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2czlxzxjg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwmjdfc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnyywax.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkspjlyg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtwhsqz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhidqwc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrlvdtt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsmdvxk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2skezkvgc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnbqdtk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjpctsq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsmrlek.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bvilvigl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tejphtxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2geempefh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpukeju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2povwfpxb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmnvdau.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuodrmb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhfyfor.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqncfdi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifawbsyp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2igspbcge.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hriugzbm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuwrynn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgvlsku.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2omzrepqf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwitslft.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2moerekoy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lfazqyxf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdkzvqa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xdublkzt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvxjotg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzambtd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nnclvcmr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2meawhwoz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpshfyq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hciuglcm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwjytql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsowcmwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2memkepnn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmpmbed.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjtiqct.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjledcm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxstfd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhflxyj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmpavgx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gcabkewz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmccbybk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmtdgod.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjcsgqs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwpahwh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvknsuvr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyhmuoo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgamneoh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvytnjfy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqjktdx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrvybwp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcjphip.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdfhcka.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2urcvmppa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrkqrey.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2imgwayaf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzilxrx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfltkazk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nclgmglc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ipipiiji.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlbdmxl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uugbiqta.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjmxerh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2boouhvrt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfimftml.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwahrtch.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkevoqk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uevxcuum.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqxvgpn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyiswrc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2apqlwkmn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2npxvlaoe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gautgcmy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2thpnezof.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuwhmpy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bunybbxk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2regkziqz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swrdlusq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvuvorb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgqfudg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kapprlzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxazrfya.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyudrix.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alydkayi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvxzsxj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvffdoih.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lniogman.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdyafnz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhebuwm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qowucmld.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xeswgjsy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbatpbh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrlaote.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cfldjogb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dulixwbx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxahbtp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2firqmoeq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajftyoys.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnozuvng.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kccjuhcu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqdzhru.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqghjyi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeowkaw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jowchixe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbqrcbw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzzlhyc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjyrjax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsmuysv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2altutpsf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zevbpjht.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owrfodbu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ultuqvit.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkzjxos.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdoroejw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvrdups.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpfgrue.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2adaqijko.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcqxvje.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uizzpqsn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzxziba.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaolesd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqqkjzv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzokorps.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnakegc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxcmhcd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwjzzkn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfaomdq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2evgrhetr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrxdbgu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlijggc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaunmzh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jnojbadz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2muqeqkpr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2exacewbg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhxvkzr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2maogsthd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoizlrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odgyesqj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhbefdd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjequjc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pduaqyjv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxqnvyw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nekftibt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhmghdh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbeosvx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlptcltr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzehdkr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2akptigrq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2chucgckv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2onaggfgv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjzobty.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfsuksa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fewkzfkt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iymublhx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ofragicd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmzfvbc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdlyxmx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sokriqeu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfotymlc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jldiliog.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rtemoilb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsecklxw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2opvxwwfy.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yayungwf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nlenddvo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfppklcl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cqprqaou.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwlevic.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2htdhuvzv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyuiklg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcakfigv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhwrfxe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2btynftxn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flpzhtng.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2emoczunb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyzzdbw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfawoqc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jthynitb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeuyoyf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoexqck.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sklrapaw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2euitfeoz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbqqmzu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxgecjz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqoxrkr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tumhgvvd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2igqbcqmz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvqdgk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2klsotnsv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaabnfrm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwwklol.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywffokib.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeqkijt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxfjtlr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkkpqlq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hahyqffe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sazczyzc.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijeidyv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcevhpr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fidouugi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvccxnyr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tguqxbkq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgjzdfv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lokrpgcn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2imljhivu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeruarj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqhmuzg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgdavcn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcaeawb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gunogjpd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubotytvf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvetkuyg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fwipwmuz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2teooodog.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brcmohed.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ackecdhg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvxxmfe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxmqito.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2umciirxw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tktidcpq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2byqzmyyr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2opasqdvm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bsavwwda.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsxpbtp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjnaxhd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2komkaalp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhksqaz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btgckwft.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdzszei.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjtwaqy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qqchrbyv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhkrrkj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hglrlwsz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mukhmrom.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mknnvafw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzghkfti.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctumusdp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcujsan.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qguitxta.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqnhgat.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfnlrse.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxtuyxo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuqrdkg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pweeuauo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgcsinq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xijqageg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzjqcla.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoutjom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwjylj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmznagn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofytoeqd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aztyvtck.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoevfqi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtbcyar.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunajjw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgwneyt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvvljqc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mxohgabe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocloojwv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lsprbing.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgdxqoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuhzqfl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mprinzov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmsbcuo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mreerdvu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlmfcfh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzscgst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcafhqe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fypzxoek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2izzmwwep.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgruvng.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2klerplex.html


<!-- 参考信息 -->