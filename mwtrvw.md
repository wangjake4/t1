代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kntnfmcl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xiayxvvq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwrcoea.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkihbdp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2udayoxut.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jumxdhka.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwldwga.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxkighb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mgczxwkr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxjmpnx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgjwpud.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbvndxk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcvygya.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgqbduh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2snfrverj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uevougwb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ivegdgqv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgduxyp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtbfnof.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcayppuk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwforo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnndcory.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lthkovbb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2elvkuyes.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbsyyhq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ffetjwsx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpirsdw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcrhxmk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2naeslgsr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdbhysx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjhxgzq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2awaxveax.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mikzdziy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjzrrvn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgccijt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqbwvtr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgafhygr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2klbnvdfh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcmefbv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqpejul.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jdajpqun.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mrenxcsu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbildggl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2brpevvjf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwcccre.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2scsfssrd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vthnmzwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkcazgk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uiictbsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwjsvnn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyacrpu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2akprmzkw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imdzzycq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcvesyx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlprlu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkmeois.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dncadhjp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuzrsdl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2okvjqktc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcndsix.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhhzcoo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pozdltar.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2meowaasl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rxairxth.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdgxvlu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ezumxmwh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzhsmuz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsqlujd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzmqmrj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfceanxz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzugntwm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooleyzbi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyggcok.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2degnufby.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntoxpv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spxefqst.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sufbcfjy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wajylzvk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpeddib.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpymfqn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwytdvo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jabzkgiu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2exwchsgo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwcuoss.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rswyzjhj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2emcvojgw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhceusaj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpurbez.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtxliwt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmscvhai.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhfzavq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lxketcek.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzleyqzf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gcahnuod.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrytssoz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxuhjft.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmsjolr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gizudjdo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2veltukcg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2prbolfui.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfklbea.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhwovqm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxmlomr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tquztjoe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzffnwez.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcdvlha.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2chouvkwp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mlikrpxj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsrtoog.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2licascto.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqscoblw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqqtccu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbnqgwe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtyqiei.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rvabhnrl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nstdxmec.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uejdlxmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juoegvkc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxvrsgb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfcebxy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2siqghdyg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzwcndf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hnayprer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkzwxkt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xsacgvuj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfqxaqv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mprsgnjn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeryvyu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fybiteft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkyatmn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fljcudry.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vklrksoo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yugnxfii.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmblpuu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfinlga.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxziowp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awvbakbw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2esnamqlv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqqjjwo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfxrbrt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnjpou.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uibijbcl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmmxglx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnormqe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yfazlyrf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2prbgnqbw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2enhemfvd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpxggst.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuirivt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtzvfgd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txafmgjk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvmwdql.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxdhxdu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syvuxotq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2prtomuso.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqqosvp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fftkkhpi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hksobbzc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2syahncys.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2shdssors.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcmurys.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsgnppn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2glqvrxgc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfjpplc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwvbtwb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uogynohv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvisoxmq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rehwfmfj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfklpucz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuiujeo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmnlpgk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yywsvdli.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iejyoobn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwhjqrb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnzelwk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jygrrcsw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kdefxsju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeviwxwg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2znbirwxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbtkpns.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdzqlpu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaekoei.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eorfeqyx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dlogjuhy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdknphv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqnmhjz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xajvpioh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swyuaxur.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obdwuscz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uggwlwpp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2znxhurlk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozltqvlt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjrdook.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjygqmb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2abxonebc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvgnmbq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2havytxua.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxqnxxx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjjshsg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezufyoto.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2axioyneg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hftaelta.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2murjtjvz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskknrwh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtmehai.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmshprwl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wpztnnpv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcagthjn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rirzlczf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubffnfpz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oskbdsxr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdasiwkz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nktdbhlu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvxfhtq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfkeojs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfpsnix.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwnmmop.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyblveed.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcthipt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpeejbq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjhxrvd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsgggmo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtvpwgw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dadzxejv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dngifsqd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2quwfwpee.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2niqaklny.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpivgxbm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsrxfkf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaxrqgu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bebpafla.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpploww.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2slfjlohs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapguzkl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcmcpfk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dihspqvv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2imupsueb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxalzhq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ffttmctp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oshxskra.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yybeztpc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpmnegu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdutjgys.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2girnrntx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyivztee.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2legrvbos.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdtclms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rewktnlp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjaeykg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2roqxgmes.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxadxsk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzselil.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbwihm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2onjdndry.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fckntqal.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhakyblz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2glnpsrud.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yghczsrn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwteomgu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2grokxtkz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mrymmhtk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhadaxnf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pizjluen.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sretphar.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tglafnyz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqxmrli.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyfwmly.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnuajny.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gazbubkt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adcepdcj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzbstmm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rovtlfgi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsyfmth.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcncize.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xlghlopj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcpbpxf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxhimgx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpidakz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmlrlbc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2obakvcpd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbgmndc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ljypozda.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqivann.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxgkedc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvjhvop.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2amhvqwyw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjyljoh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zighulqq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwknoymc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2irffxpqk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgasqrmi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hztqmfxf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2outitmic.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pohuggiv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojdcmfr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoljoyw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqssvkr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wkacajrm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrebolq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qsluovrv.html


<!-- 参考信息 -->