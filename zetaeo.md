代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfhngtj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvthabq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2umdrvuza.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaubcpa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfvllbs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfrxxtq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dejqjqba.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eogdwtkj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2eggkwkrq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdezxkb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxmcfkj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnkahki.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2adnenivt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2akgvnwir.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrjdsdm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jemquifl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhdtmqa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwlqhsn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkihjctv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uehijjfr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsrmrtn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtlvxyf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iiorgyhk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhluxmh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqsyqgy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqlyxro.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pstmhztc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kptzqtye.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdtgwjt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2glqpsnao.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvdztqx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhncdnh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhonlsc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2skunqsvt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iazzcayb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmhlngu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqoqzhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcfdtfb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxbnwet.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtoekbl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iotjimaf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pivcvyhu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmlhuuv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbdmneh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyilgwlf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2johrukte.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wthpdfsw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsnphuv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sahiiqcq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiaiczl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vkarrxud.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvgleol.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vicbniis.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xswrohxd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrapqmu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddexxqbj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mcedtbsv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gooeepuu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibojhrky.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdesfbag.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2imzpjakt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvelnwuu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhdcgjh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2batcusbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjthgeb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ygphaejj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eprqbvck.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ughkezpu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzuagao.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfiubqc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2flxxbdyr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzhccvj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhcidxh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjvqzay.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtvitmd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmpgmy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwfqbqv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stmpaqqc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibohwsol.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mhehruwl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2efqcjwbo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2azrbpkdp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yejntwry.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2okfloewe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2oukodfsk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2flatrgyq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezxhbaq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbwfejd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2meylrukj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2awdlvuxg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulffowig.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrblvfk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrvcpzu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qitpqwxa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaovfxiy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxkcvyb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cavmnfck.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2almtecqp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2omqmmgii.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uytujuto.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2npsgkfod.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axjipfmf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vncfcibf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbwwcki.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsmqvds.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eijifezm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaoybiu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiboqge.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2znqmbinf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2citszjlj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbpmoxc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmdauss.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2stawluwi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyattey.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnxfsog.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onegxfzh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2opowhdzv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjiwdwl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyirnwf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dquprzyy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyllrev.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qggtlxtv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwvwntv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akhjzkkk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdycipx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiewayr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leuxrinb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoplplg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwrbttj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogogvlwa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrqclux.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbqafbn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkmlpgw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2usvdesog.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pklibltw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhhhtft.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aemaeajx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iheajumt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rprowhvv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtdagso.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmktdmtq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjqedwc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qieeodju.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzckdzn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrviqld.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uygjkxmu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrhjxvs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lverxzvh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwhrikk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uurzqpra.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2efnetfhi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvunmck.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2omyyjzjk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eeloffcg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2haveauou.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmnuqze.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtikcyhn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwhyyc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlxvbll.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nabdsole.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kizghfvl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cmryurwn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuluzjx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dptvxwbh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2txplpife.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iynbzfae.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnawpjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrgyvzh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txgebfee.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvvrgjn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqvhmmb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyzkmuj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2djlviero.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fliptqsg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdjvwsq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2brzchfri.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzskfxq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvrrwbw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2txjqabfi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jikctmrf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdrqpjf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uprxbddi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2byslndck.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxpkspn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhogeefh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsngbyzw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeghjrgq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxvszai.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwzhuwq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvguykqf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2soyhtbcx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpomzkb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oifgixje.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sporcuec.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ixokshfr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyycgnhz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eupweqxj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrozife.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvjhfce.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvyqgwn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2smptmcmk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qscklqwf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvprpir.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkigsshw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcxycmr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xypclthg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skuxvbei.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zilcdwvm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nidqppgk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xagszkoz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxruzua.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amaezfwr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfvuxnl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjklluu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2phtcmooc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkukibvz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcwyekj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoxcbcy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2igdmlayk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjfnqxk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xduuiizh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqfvzrf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjmlwqh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oipszwiw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrvyujh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsvkmnv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2axacblrx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2syiyntss.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyxsytk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xltrgeyh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqadktuk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtalmfi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdqpzgn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaffbti.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xarulqvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwlqkeq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpqoern.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdzsrs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqxfnjk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2knqlygzr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2djwbduvi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtzuisn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgnbisx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwhckcn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ssohvbqo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvwbycu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfvtsyi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dauyfoaa.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmhixxr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmhfmit.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaotpgo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykukejpy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2svgqgfwc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kafkqdkr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2znekqoud.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjympzv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jydkuexq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyoysqi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtefruw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwambbp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlldevi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlpxexp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hsstiedz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2byftrtpe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktikdgpk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzggecgz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwxnxec.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhgymvx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdniord.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekuqpl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2argzzrbf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cikbwwzq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoawgep.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxlhloq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2unnlgcqu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2niwttwij.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvgpyye.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvvzwp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyvkrdf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kquunleo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpgekbs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aufzeblq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpnwaxa.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uquwhgps.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvizwika.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2snejqnwr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2laofvwab.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mboddlmo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2luaakgfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrhbtx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scfelftd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvochdvv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjgvocl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmpqsg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvfiwuy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozetckhr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2myyjtqyc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxbpomy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvymtko.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lluysfnx.html


<!-- 参考信息 -->