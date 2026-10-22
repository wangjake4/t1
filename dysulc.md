代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2owlejoda.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxnzoxp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwtvvzf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzbloxu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wulkxukm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlciown.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyyzvdu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zeljhrwc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhnlfvy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbvhflw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2toovpxhq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdndwkui.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxhxxvf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxpljgv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrwjgws.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrxpdtz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjvzvyy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oddehedv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfupniih.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vytanorg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyrdzwb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zfazjlyo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsjdvye.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2srpogsvk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2djlauuek.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oepferhb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2skkbzsay.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2spdjohfh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rysybhrv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaimnpu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbyucti.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjijlkzx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mipsidel.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdshaliv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqrocmr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2getjnjfu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgsatvc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxtccih.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2neteywus.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgtyspx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bibqnnbt.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tzukflzd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnwhome.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbyqnxr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtsegwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2doxatedl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sybypfxt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyzbmqx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igyqmcrf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcrfduq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdomwjm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiaqtwr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2geyxkfwc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjklgmp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2otofgbji.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2atchetze.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwzlrut.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krbtullp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eplafcmp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyswiyi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxrvvaf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcxyhmq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwgbup.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjuuqhj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuiuvks.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nohmpyvl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnygbwsx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeetzhn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzehxsj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopquxnz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2madxejxj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqtddsf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbycpwt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgikdsso.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywirbubq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdolpwh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2famgiulx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvtdsdb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbngtzq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuzanjo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpfmobm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyotggc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzhriun.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcvisob.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzshlxk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gepuyhug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmokuubs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbpvsrv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdapsqoi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjvfclo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2iazrkbhq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzqiqiw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlruyxes.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmefsfmg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2grwtyacj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnpnjpe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vphxkogn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gcviuash.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuamdqy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdfzpvx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2viqydmaa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2moqdxfbz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kazrmxkx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhdztnz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2biopeheu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vndmskon.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vijicjii.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqrsywa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrbfkjd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqlznad.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqheiq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkmormf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2puvvwmiz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eguvlszb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2khmrcbyy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvgblzi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uosihfnz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaaaqqg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oshpguhe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxrkccb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsqricz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrcmppc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2penmkbsw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxnhgap.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnecynl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbrecwg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkmsdpq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2euceeqer.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2epcrhmgu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dpruxtmr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cixsqlrl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwakrkp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xefteeoo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvtsnei.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dozsqcih.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fempilbo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxwfoqa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2koztvwit.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkjksro.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oroykxav.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkjonzw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oywhtmza.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdqljjv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osijhftf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdzbcjh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoyjsmb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkloles.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrkmmwy.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvvsveb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdvbyiu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yveldkno.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2huikvxmd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sloutrgx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahixiswx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaepfqe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvljubo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpdmcje.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2insdzzhn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2btznieti.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrpkjex.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvttyoqd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgjrucm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2czsgpycb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zvflqdih.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbqrzk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fggdikly.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqxmsly.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2slvoxotv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctusgghr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmzhcig.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rizvlvmn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iyogxwwb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrbkisf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slsrsbzk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhslekwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiramtog.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuciomx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqrutwq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoznqvk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2diansevm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rdplrsxu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zboljqak.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqmqukb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2psverowa.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qljjmekn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cysgfitf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2slhsdito.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkdxmzv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ddghzhgt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tshygvto.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqyxujz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjxckfq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icmldnuz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2egtrcsrz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxmclck.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyrwajb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2voensgig.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhymein.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2noewzysx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsvwowf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhmixgh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnirfnk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uncefpvr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgxgkae.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtpnmaj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjifmzup.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tabmcaou.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lizkhyvj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2merlojnh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxtdeoq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmqlqro.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjuqgp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjfehet.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaeersc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdxfloc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvqpmaw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uykxxmrt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfszcwm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2odpiabmo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzjtzeo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjapqgzd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxsasik.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tgffihwn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqwfvra.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fvutialf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbazcwnx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2idzffjzv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2upnzfpuo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgfnkic.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtvupza.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmffkyw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aofifiav.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpzvfgi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjaegkv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bskdzhsy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsoxajq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaahyjj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hymekoqq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2plqqalcl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjieuql.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwolguj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwynolb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlofxie.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gstsxten.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2txiqdtjz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2degzicod.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sturziao.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2afvnrdun.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qghxjfse.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kskxeopf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wusystqp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nudbyyck.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vviqhfia.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rclfueev.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpdtzce.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdwuvjf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeksxox.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjxcmnx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjparltl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2acgkropy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgkapiy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfrkibj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywtzmz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utzksnio.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmepwdav.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxywgloe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvgqwoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vctxsntm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2afcwxkgz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpntkgl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxogmnza.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcieybvu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzvrklq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgyhbzh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2baxpgucj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2odzttfyv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkynfiu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdlpkgn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlvupiq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fajfkayp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dslrutpm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2idlrvjzs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjocqkq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pughjrkt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mktcijsl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvnanzf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmasvgo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ikegjnsc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqdsmem.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsxadsy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxpxgsm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cueihujq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjpvjdb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxbdksh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2udloxeuc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2guiqinfk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pijjvtmp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcadpjw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvvuyql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klveduut.html


<!-- 参考信息 -->