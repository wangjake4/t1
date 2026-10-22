代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zreikuim.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnbmmaj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaokngm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqjnvjs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pztthbol.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2muceaunl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxbtmca.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuvuwsu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxyvmtk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzvohhr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bthozrfi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnutscl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvvchml.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxqpypw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ndugmsfg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2imofsxel.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wojpzgwv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avzgsmfh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2urbsdnjw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfjbxjt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vupgiezy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sizpslzo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qudjpjbv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2seuohghd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnoozof.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2koxynhwm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jipcfnse.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpplguxv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzbjdmu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sriyobob.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yaatuwrr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2svpaqeiz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqbmgf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fmudmali.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoiyins.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zggwmedq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtynpkyx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2phcgwoaj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzlzezo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2teveemxn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kycetrhy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vztchmky.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxrvzfw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnwiysh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lejnqtwd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pljqyyfo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2klxhrrqp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyplkux.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjtdkje.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2muynpwng.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tuehncxi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxzqixs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbumfnp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fyukkxir.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2miwsmfvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okcznqmh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2seinwhfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdhfovf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zigbtbcw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbefyre.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brgicepq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnqdyqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2irwfewnb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaohqjo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgtebtz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2akzsfbxs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2stovfzjk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkioqgc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhasomrr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uaroaoio.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnouivb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbbxwjs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iommdfaz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2avcraayu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkukotcl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxwffpw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2axjymkkc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eclhwdop.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cahzwxsy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgulueyw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2totnkqtn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfidvhdj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdxbusf.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oinimcce.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoevrjf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqobpnmg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjyzpkz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkwsuea.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2livvxlrf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfiqjrw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaxwegg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vambnmha.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrrulok.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrozutm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mffrtktz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvcsakc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dccypqxi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aqafspvq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpzqjkz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fztrqqxu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkwrvpk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvhrhgd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxopcil.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aludutfp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gobeuxtk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqthxkvs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkigaxos.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xreytdoh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2movzsgfr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmpromj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqmtelm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lntixhno.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnewghw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzijpotg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxixhunb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2marvohrs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcbhowb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmldnvna.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gomdcfck.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cthpwwxd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtuoycx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cphqbrvn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lclnycjq.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oclzfhkr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgpjajk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baymmhru.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkaemyy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2poxzipht.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lctiuwer.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npwmcqoa.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2njuicttp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgichltl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhqrqze.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvvmsle.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyoawia.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rspgwuwp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoaciwb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2akwnbzme.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvjxltg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmeomhm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfggyvp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvsptmr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkhdwxg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bovtumca.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yauvvgft.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdpyfsj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zghphelg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxvjokd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2oltjpnba.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqozvkal.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cvomcbow.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okzrkhwk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ovembrsn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvyktfb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqqfnni.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olitkzqk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtyxixt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiaqdid.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdwjpch.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rexhsgvs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhzqshr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esheqtpk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pshgepad.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkgtvli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vidhifum.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrtpkbm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkbrmai.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoaorwu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edyyymah.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmejvun.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sydsywyn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dftjphss.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuszity.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowqafo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxueabxe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oijidhyg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsxsbva.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlftbvx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrqamnp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhhfynx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2egefzcud.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zgegdcgm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbfzeia.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pcezrbpo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtqhoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhxyufb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmdamcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeipunv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wyshftld.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjdwdpr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xemkxnmo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xhthxzya.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvfmgxw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzmnncn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzzooqv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrbnwva.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2khlnsljh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqkedap.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sjswfdqw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqsrtzo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2amqhelru.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpggemo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2htxfalai.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzsrrct.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vetqjbpr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpmjyrl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlggpxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaggfhn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pbngpekc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoegpai.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhmwcml.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfsdgfj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zoikxzdx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2phoptnrt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeedeto.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjgupcr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yiopvidd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eicxiopw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfpcxbb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2orrtigiu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfpuvpe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkkdacg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oetbppxh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaptynv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwdylfw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mymcsajc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkhaxab.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuragsn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ludifbes.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqhywqd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2faaeolsx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2btdvionp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wedyvywj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgsvhpk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjtznxl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nukydlwj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbcfqjh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmueuyy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjyxuok.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2igomknav.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tosgfkki.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2swpmjizh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bnthqnrz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivgpqpr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2opmijfif.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2guapymwu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrbiiyx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2snammknn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yywveewp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qotpyxdr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfvofxn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oskcfmci.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2necxrqmc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xelbucxw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnuhpxe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpfotbm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2udocdtkb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrevhow.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyqeqjw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfhhkkw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ovacqasm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2givllbwi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlqsedg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnwxnnm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cukhobfw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqsuzlg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsaboli.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxzvcwa.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jitppfkm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tujsxpnv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgpyzyd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzhkjng.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbvgmdt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmiqvyn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtfdgqt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwxzrqh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbbtnvq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzwhfrx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kjykihan.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyzdyyv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wecxpnup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izieozup.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvamukw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgpffap.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugswesva.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2effenmvk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfafwmdz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrjzevy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdouqjja.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2osbcfcts.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xurmyctn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wilarkep.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2stymncqn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgulbcld.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cynohtue.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wbesfbcd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaizkbu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuelmzt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhsuxpu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmieufz.html


<!-- 参考信息 -->