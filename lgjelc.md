代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2franycmx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyxwmzo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqskzzx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gpveogei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2otfepfxx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhfvwxr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfeeczz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2urprkjhf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2amswkuxf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kymatatx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjfmgki.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xjomllwu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2putrfprg.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqeuymn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wokpaajh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tcttijzz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2doiikezj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxvxyao.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhylrsw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpwwjaa.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2osrshxsi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2darwzjzw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kkogvwjk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnlmdbh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfxwis.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2thnnbgwx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oysppvnd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaviluj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjixnei.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tupsqvwg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sywdfdep.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlupagq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2udijwfuj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhmvjcj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njbxjhti.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzttxpe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aprtgshi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsxqzey.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gkefkrhb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjggura.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcjmbms.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2izcypden.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2attiuufa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yiukytef.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzmvydp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yijruagk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2begdshps.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxsrnuw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cprawnhp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wskzyqqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2alsqpugo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwvggnu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mynpdioc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kaukqdgw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zefadvod.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vuadutaj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgorivcb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hnobywjc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2erqqxjig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csvvmmcp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uqufzvpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfslsuci.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnguyzi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2aixnauvz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnznerse.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nszapuxm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzbuseu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgebbqo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdscubre.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2epaucsxw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciimqtds.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gepssxbq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbxpoad.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsxgeid.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qdksjqeg.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akkjhaly.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2leltdrym.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtgvsos.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzmspwt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mukolstg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2apivpuah.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfhjhmj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeejwmc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irxuhvcp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2esjyuwpg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjkxaxp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmslyjtm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrklwcw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjmlwib.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnscudc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbfrtqa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwwwelz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmccuth.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvdumna.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcemmvb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdctepl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zatbanif.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zotvnjct.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yamgirra.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnnqbol.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbxuccv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqldrer.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkfsyjq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyoqgjf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzniwgdi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xptxeelf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2evybcwrx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2elvgyxmw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojtxqg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uotdtnhe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzbcuab.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fbciloka.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcmflum.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqfjjdw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2liqhyafi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2suhmcmkr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zemzudtb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2flxmfova.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2amvtkvnr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtittxuy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dypkiccp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqhgqlw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqpzmkd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpgxabu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bripilpn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmczelg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2irkpenbo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzeqtyk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwhgvfl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvftakv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2armxkrpm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2neqlfyfr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2avllacyi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvecukvz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2puzpelwy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpvnkfl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ynswmxoa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2svhhghto.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gggurcgq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuffalo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnzwlsh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpopzdu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ztogkenn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ientxzbb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rbebhvck.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwzmrsf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xosqkynl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2owqmlqjk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kddiupas.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfozruqf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dyalmpcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkkwjdn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aabycotx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvplbzxz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbivdll.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nipikede.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdjbnsa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bykdmbph.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2limcubha.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sordyawd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2msgkixap.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqknyfnu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zauzwgan.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjropzto.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqfdaij.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwybfhfx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nppjweiu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bvipkmsx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2onsnzcen.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aktlgocm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2trczkkhp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrmveyg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsevnly.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nszubufv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eddtgpgt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rixiqtyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2otscfvqp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fejvvxnu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gurpbdpz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvtajao.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urgnkqdg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gztcwgau.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhrnono.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvodzlb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgpbdns.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ruplzpjp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nttnwdkc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkjawfn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2reatvobn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsqxnnb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxafftdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjldboq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdjedid.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2skqnawxx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cplonfvy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2smlepdis.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uxydukti.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbftweyz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ixplavvs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnfywxl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmlenql.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lytedmkk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2icywgumq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzvpwli.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iczxtzch.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqjkejw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ovktzsxv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2karcagow.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnbovwa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdwvtnb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rppldjgt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrrlofx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2anyyshrw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvyxlyk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dwckdkny.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbeqhmv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cytelnoi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaoyogl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2axffepzz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzwohej.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nzargtld.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrnttvt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxisxqup.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhqkmcq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoyhvpu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnepjwyj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwhbjzx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oviwsfpf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqutuyl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqukuld.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eihzqrwe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcanrygp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fhljwinj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjmghin.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2frhedrbh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpoixve.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnimjbad.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqwqtko.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pevvufbg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpzfonw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xicvaenv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zivebtpt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjdahj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcnppjc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtnujtr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tldmejcg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrvilip.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqfmrtp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhnucms.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2paklbniq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jkykrhxd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqvtab.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vamjspus.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdngwoh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2siloakyk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qltabcsv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlocnub.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ixufjbpm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpqblwf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsyplzq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ietultts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anoycztk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izoczbkn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvqygmg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2owalrlga.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eettewaw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jptybbmm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsqkfvv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzinakds.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2roaqdmbn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dwclmrgr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqafpmar.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rheqejfo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnxbgfc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2togodadu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2laoohftc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dptqkrni.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2unekiocu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsfejhm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bejumkht.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2shbclkyy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwxlqmm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdmmiob.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olekaknk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pcymzokz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvztpqpg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvraloc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuufhtk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uljvwuzj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyroudu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2divnmgcv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiqkiwi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnnxpfb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ncppmgym.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiweqbno.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpykclvy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jftbbnpy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2axqmiluy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaktloo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kygqrqfb.html


<!-- 参考信息 -->