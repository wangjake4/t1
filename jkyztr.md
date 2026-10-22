代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2coyilakb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmdwvyt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mszyhwjd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsxuqbu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaejiod.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjykcgyt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfnbeil.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ghytpbqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2detkqiws.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjppwuc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkgchgi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zkssklye.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uiogqxue.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ennanpix.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzyqcnf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgajdef.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2akkmcxiu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2venfodbs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2chdbrxqm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2frnuusli.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nmalrdmd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsybzoaz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvrsbcn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnqmifv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkluufe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbagiuq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aidjlrvu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqjpmue.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cayiokpc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2debugnbe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jwclrszh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwmbixr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jsywagob.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnhbpaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thgpmqqc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnacwnn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxivuki.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgrczyn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zrffuefm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqcddzh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mevkqyty.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2whiqarnf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bledrbzp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxlfqww.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmuevhy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dzggfgmv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvljtn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbphdsni.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2anpldgxg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyuircp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fonaqwlw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pxixcgkz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfoxmwq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaljpxm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuyxets.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoqwvtj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfbcjib.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gphegtmx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zepxrmbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yofrsjtj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvgulbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtegwal.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsobejn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zndhpmmd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcdxykr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2epdxqwii.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrskcgfa.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqiency.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzowdhb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2usxjjvug.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsaxhjl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlvmfqy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhxkkge.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sddzevvw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfgjqkj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdrvzpa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kpydpbsf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuxawkf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycouagpl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzxanwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqyvanr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pgervmln.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2oujzxljr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evcybjyt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqguasnp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rixorjna.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiojgie.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uorqitfj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2miakqdha.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwkkdsk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wowbgdju.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hlonbyqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2syynrezj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cljowpgv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqsspjm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrwjdtq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqmswfe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbnptwl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrdwbb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpduvte.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndmyife.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnsiiqw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dklytpyn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzuqhsj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2usnbmgez.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oehlynfe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqnsnhp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gtezxlqh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhsvkmp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tebrwgde.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeyywkm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2htrgtjbe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwccprx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2skbwxyrt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnmvmcx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yubyhtnf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwosgupi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqeixqi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mssseoze.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isbfijnu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijycsxpn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfjdpka.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxgkmrx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ahthvsmn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2adlzdkmz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2orjwlvel.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iyircgjz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rszimqvp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnttpyj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kotfblhn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2miyxshoe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2baxxrocv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwzquyt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aquhnkfz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fkncncse.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwvqarn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpglwsh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2alhxpdxo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdagnqj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nicsrqhz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxlrjpo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2woyppffj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uyismrmp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqyuugd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvinzlf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcpmzob.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2snssrujj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfvzupo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gimkgexc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcwonce.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqgqljh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcdofax.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2modmctts.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbomrqa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvpgmuo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arkxvvkd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbtgnmb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yypxhuoa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2avodsawe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnykxdxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2opgfuuwd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdehlsl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utfcniqq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2puhkgcyg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfycwycw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgslxmw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rhamaexl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzqxrgm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhvkoxw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwkahjb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xfawljua.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmudxf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zizwwari.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2otsbuslz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcmevhp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lnibvkpd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2phjavnlu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoabgpo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlopjgi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbjjvlz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhdlrlg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sijclbmh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2finjvmdt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sibyusga.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrcxhxt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iidvqodv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxovzll.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyypcoh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjoesvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqaaqcp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfebjnvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvhxive.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lckjtikx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqtewwi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfujcaoc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2scywrbsg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdclbjg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2plhmzder.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2sezdtxhl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkitgfg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2icncomko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hibdvigk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2imzdbkik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaukxzy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2temqxcif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xssbjrns.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2amprfaks.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskoowxz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxbjafv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfbcgox.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwzhffx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoufbwm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lipjqgvs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lszbahtp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnsmgcu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchwuznu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcowarp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmptnckb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pchiqgbf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jomkdfgv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tofewrdh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2agxdymwf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeokrft.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddasjznf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2igjzwrei.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpcqskm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ziekgdts.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgefdxv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zocpgdyx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnafgpoi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkovdoi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2woemsqqg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgdrhzp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsogkfa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjonyuix.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsaoxek.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qfntzypl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgavxesm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2newgjhzg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudewoem.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2itildobv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqdtbkm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlvdrtr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2njvbinuc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ianablcp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxnpomj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrcxkeg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pecdtjoy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchfcpd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rejtiory.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvqcxen.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnkzwgy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afvffhda.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzzohjk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lomagutd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sspjrpcq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnqkthv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2adycnxrx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2talwkojw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcipsmv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2srfnsabv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pekhmgll.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgfjana.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vprojfii.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgmoqdd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwponpo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhbytck.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsfrdme.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwwwmhw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbhynaw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oskuudvc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lvihksog.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeuwfwm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wprdsssl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfekgbn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimkootj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzzmiaq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sostjcsw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzmsdun.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzylpou.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmimhlrr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apaskcke.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjzjzbh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhcrhvs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ojudmxrz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txincdlz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnyvhym.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvywbha.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itivonyo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdxkeub.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyicsniq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kejjlytk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ootuvzud.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoiscqp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2genkjpas.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2safmmfmj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgppqmew.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrjrkug.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcenxptx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlnjbze.html


<!-- 参考信息 -->