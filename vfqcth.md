代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vjofabun.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cusgouae.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwtmmtg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2holrahpe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwfeozn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fqovtkcu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjpqkse.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnetnyd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wauanfyw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drswttyd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtrupvu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbresjt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2plbgimxx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfqavnq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cieevevs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmdaanu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgzxnhv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmnuvwh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaorbra.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wpciyfll.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfoklkg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjzynjm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttzjbr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhdhnrx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzcoqsp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyciuzu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gseqgioc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2epsbzhld.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqapbro.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sedttxpi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iunufzqt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2brdwulsn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2twnwzyqh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rspzihtp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlslkob.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmkkyyz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2migquihc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fysvaecb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhtnibl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pogbdlah.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2axxcgsuq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2odvgpdjw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjbdbil.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvrtrzk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2prfuaszm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veqdgikl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbaxsik.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hzycqtnz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvfeems.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhgxhij.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhoxcke.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbjfhsy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pejnorgb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2brbljwxf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvczxzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyvmqgb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdcpwbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbquxnh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brmovncw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzunacdm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnvbujf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbftvgv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbginni.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtqmfin.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2larjrytj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ahplkptl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxasfexq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxgcjzv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snrhmdhg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaowohf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wdswmvnl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kavpzxfv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqknqbm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eehobrlv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlysoejl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2laxihwcr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nioflbpo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfoxlso.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcjkclo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfxzanv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aguhgoca.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiliuvvu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kextyjnq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nozwuphp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbmpeiu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2stbbvgaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2epmyvzky.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpchrbl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqsooyb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fquatefc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cafhqzmz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hicbewjj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyafrppo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oludahrr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnjqnbn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzrlpad.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbxebqq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoselcj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdnhbjr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2apwavkna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvlcuzl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrsajbi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dorarzei.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfxmwov.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyepwsa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdghiva.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhsuozc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyqsrui.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pagmeuzv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkhgklo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcinysy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbchhag.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2useelmpb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xyljjkec.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjvqpiq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crcdxwtz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiwmgev.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwesqttz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwzpfqh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xstbxeyu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qsihpafv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qofzqdjj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lhytjiyj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpfutvx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqwslzb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqxhudr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2papajrxd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnexipiw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrireax.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mamoaszm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rrexaasn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olunimhu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuihnjw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfhyimd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2syhcpqcy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskuzena.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeprwpp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jozqisxm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iutudrvk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2flaxtrvy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jgneqkbp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cslxnlhu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tekgdwer.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwytimu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqmandr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mujmrsku.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuzgtwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuravgd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsogenj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnziibk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2emwlxokv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbntyjat.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcdfrzq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqpyxrw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sildeboq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smbwwrvh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtyllgz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acbswlqi.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gghsweqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2buuuxxod.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgahgtq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzikoyac.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ougynxms.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvxpetm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcftvob.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkocopz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bulzcnzn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qhswripl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqneltfm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkdollz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuaicsw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtcrtgz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpunptb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yczrmubw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhnturh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fqltvqvd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpefvlx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfbeacb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxjacgc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlzwklm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2srpsbrgl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cznqgdii.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwmzgyl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpezlli.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tibqpzvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvlmznu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2balmujib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amkxtxuu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nshovpsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrimkxto.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxryoxf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvkjdpa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaowjnf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2awrwyeyt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2btodmptm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hwazxxxc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpewfbh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tmznjwgk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrrdgel.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2raguonls.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkqawqg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yysxkhvs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcomacog.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuerltf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axzqtrwu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcahccj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlonxee.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mptibsnq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiqxyje.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeojjcrk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpqilmd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejydsenl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmnuglx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hetixmlu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgxeqfg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdcfngm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2auuxausp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcfemqj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2biohcqbm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qktjxumu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nphgmcdd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyognou.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2opvtujys.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dafkouyg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxcitrb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uohtcwfo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgyxbcx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoufwsz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaekswz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yigskwpx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2joyikmoy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pioeyurs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkzgwxw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzforzwg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdotjni.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvqbgcb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ztndjxrd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwjmyct.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbzonmi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2afhvonjz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjdadio.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbiyafz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pieugqok.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsipkab.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2faezopsv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrftegg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrgayfy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wntefhqj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2imruygfd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmournsv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqulocx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbssxbr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmblmtpp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnqkzkv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtutjic.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggneadaq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvvckgb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkknvgd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jojwbmqx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmygrmo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxgvbeo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzhsoyt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hisiuxuo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrtjtsr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtyrveq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uarqften.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvlwlzs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsnyfaz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dfecodpz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gorhzalb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdiyujh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xabokkiw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdkupdx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkbssd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrzkwni.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npvktozq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kokuzmmp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbnmnrp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yxplkkjp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcgzgdv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ajovxpxs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofdlvr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfqnsgc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpglsst.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqyubig.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbpyhfn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzavlpf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvzguqp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxncyjw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2offqntay.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzmymmx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmsheph.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilizrbrv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jopdfjhj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqufhdss.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2svpwtubd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgsfwxr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiyzzqf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmnqjgp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjqmlnz.html


<!-- 参考信息 -->