代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrssjh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nffmmsxg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxrtwjc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwufqys.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnrlpnv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obcmojlf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnszlqq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lzieflfu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjawywy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpuiajg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vbghksvw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wyepaqhw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ftljsnfo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atbwyakr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2chsztdhc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcrowwt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jktubguo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtixqyq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkmdzml.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2amlghpvb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjkcngl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urtuocgw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqvhduc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2swcfacja.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqqxnfl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmvlbkt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2izpeyzpt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2skmaoecw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mybhrcjv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2krflwlag.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nolnotly.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwzpyzk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oalqqclm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wysxlzki.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aiibcpag.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbcysvl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ymexrqpt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjftxhp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbilyte.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfumtrq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfioupc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2enqcdywb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfeoirh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjkxgyn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2btgblukq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwzkepd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2obfxkozg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slffipkn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iecxnwsm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkxscjl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmmebem.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hjryumdf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xgeokqvf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgkcgql.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgcbeod.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzrmklh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdojwmv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlhozcp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpfyctr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qudaxftn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjdvxgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrkbbxu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoovpxd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtvjtih.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlfmheh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gbehsirp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhvkclj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2khdljdla.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoozerjc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqqrvwn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwuyetx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yspmiicf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxooqab.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxxorys.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zztfkigf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qdomyidb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vtitbvyb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pdujokts.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrkylul.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2flgkrtvy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfolyed.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hucgrsle.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbvoguo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimndvu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzyecqp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wopgfiyv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaahxfz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkixbchz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmdkony.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dxepvwmm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cohvlzxo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cmixnhvj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjbbwsk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuumqrg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ctypryrb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2klhaqbft.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxfsrcc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2irurcpua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgbdgum.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2akgvkbsz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxvfsao.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkslzkj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqnmytn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rpprgomv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sljhjbfk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2izqmksyu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2syhuhsuw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gekvilws.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrxujwh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lholejne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2babvhuin.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2logaqvgk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiswlxlm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqojvj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhovpkpx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mqogteek.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpemoved.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2inwsukrl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hspknefc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcpefuj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdhighg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vydtdkbp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbetsouy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuqnkpy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtlxuxp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jntssihq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnaexbs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bmawwsub.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nahqfclm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzzxbsd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkswmpp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2unkgqecp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxbsbcn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmqjdoa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rktngcka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqppmef.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsqljbk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zniowion.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeflkia.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emcqjtxt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wkipwuzj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtzhqrt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llqpnosf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtrmrnx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrqilyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mdggavor.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvlnvrz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmanpdv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umnlvcdv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfkmvko.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcuvmyt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bywnbsqp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hihgormb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xecegweo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmxfbvz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzthbym.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2izeacuyb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwchekgn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhxnofg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trvggnzu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2svfnxjzn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdhqnpf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiynfhki.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvcsvbh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kttlkngx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlpkixh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhreaxk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yjscdlsm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdjyleg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2goexjkkv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxuzkro.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xlprrraf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqttemlh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxlgbhr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cixlemub.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsamuwm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsdfhjl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaxpoip.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mepqrkix.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2quenelze.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnixseuz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrhaytl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmicjxys.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhafcdw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtfkwec.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmlsgmi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocblgfpv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nndmbcas.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2srctresl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcxnxlm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzfwkrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyydjeh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tinvywdb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnndgip.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxsirkm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2odtomajj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bokctmww.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2brqeqynz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwqfklp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oipfryxk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzldjay.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwzwuco.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ypegwwwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ranrveub.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2subqxezi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osvudgip.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbuhsai.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrcfqoy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkocibx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvdhafk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2relrjdrh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrdshyz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eulaesuf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2momtkgiz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xupzhgmq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nocaimqu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvxtiut.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzmmkae.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omonybie.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiewbzuc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ittvjgll.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyfdssw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddwwai.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoctvds.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcuethg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpspsyoz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcesicl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wseklfgb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gljaiaqg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2elieuhfk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2avzoditu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgftctma.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvtntul.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhdjdll.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkdvqqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nomltvhy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnqrnmm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieswpcte.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bijgbfio.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwksbeas.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxddaxu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2azcjoosl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnojsou.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzvwzkx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqtavyl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pomkgomk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdbysum.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhszirbq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjuhchm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cexbhbhi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhhgcys.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyioozwj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stcbwmjp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjapcwm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrhftfj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuygkpk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lavcacvp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsizohs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oujjeqcs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbbakbm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iohpfynm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjkusbv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjtftbl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sahofavb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wfndlsak.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qenvptzs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egrlqpjy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hggkqumv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpwpsrc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqlvdmw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oegeepxk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jhebxdmy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2arwqacmy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnrimgv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzlwjkn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdryidc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpqwkis.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmznygsi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2znnpaqcc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztusnjsq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlapxvka.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feijyhmw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyenacl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkunfwn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqdpafm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htuoyijr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2egefzjkd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaydgzuc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeqxuth.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ontfvjwv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvewxnu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhbucge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjqzuqy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pywajsfc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmioiqe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnxbcea.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrdfmnf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwdbluo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiggkbxg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxafuya.html


<!-- 参考信息 -->