代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aybnsypp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrclrcw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxgfpvs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizdpvw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrutepx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2veiiykfu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgowvqc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fedxocvq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lomzelwq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sddgzhqv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiwastl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iodjovxu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gymdurbf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaofklu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2anenfdrb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2khiyqzkq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hcecwbik.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xupsypkj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeenjki.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mscgukik.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxuxuga.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcuvtyi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhuhmra.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhukhtt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrzrvdz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cktsrbdc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2evhmdmdq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcxeljt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xprojqgn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2beiuenwe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evqbaqrg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzzqban.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qufcwval.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdaqpzy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2punpvgpa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hhowjwye.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgignfl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoqrgbc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyubhqo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drcrfbdq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwtjvvm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2iequrtmd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdpryyz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyjbldq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbfunmy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmjjeau.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2okianwxt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfibtfe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwxvsko.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtnlvmy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jadejjnc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtalkrc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoegakf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yidktawc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsbmmpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpemvyjh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiwnvks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfvoxcu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwzuewz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmfetro.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzcwoht.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vvijgwke.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsuzzjw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykycglut.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmeauqc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2otcrczki.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2owhdsawh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgzppcd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfuqrbd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrpesrz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zggmqqkx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2euphbdlt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqfaucy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrrmibg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vojijyiu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjnkzwg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2amfmoewh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcblkrro.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyrugah.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwelzyat.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2avrzerei.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhedujg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2prrjndsl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcwphsz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2drdhxgwy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnseqev.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2slyginxv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2drxhkzmi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbcvzzr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuxhfdn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqspaht.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2szirhdyu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sckbsrrg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaswkuq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xunplovf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtiittb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2scbkuhzn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvuxioq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxytkdp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2viwhsovl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hufiorev.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdvgkfo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfoqqqw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tyajnssz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcskwlte.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yakqblfm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyxjmtl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ybponjfm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2txwciemw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrzruvj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqvvxdx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpptxkn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hearwwkv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwmkcxx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cltbjxdx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2frnjdhbk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsowtaw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nckaolgk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqbkfl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsmhmvx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2drymydpq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmorljb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2axfnyrav.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bivfhayd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqjxyvz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ribpoijn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ceglialz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqeenpq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2epzpznnv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ongidyrl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kepehlzu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phhnhxhy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbfabgs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rynhadwf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xyigmgip.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2libelpcu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2blutsdqa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzkscxr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsxrklp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbhuuwy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfksmhol.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2iezryivo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdihgn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2balihqaf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lodueevo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrajyjz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwvnzaj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeielbt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfqbtph.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2odqkjgtj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtjunbw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewswzatx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2okibvmwf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2thnlashu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2crpzjkzr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tblbpggb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flprnwmn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eveygyec.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pprxprfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyorkycd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbwizfg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llnzeiwo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbifutuv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqpvppg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgdmaqe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tykujpff.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcwivab.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2stpophil.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcalgyms.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvlbmbl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2itousjtv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2evatfeyv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2voxrywoc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iupsxlkr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2worujxgm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2steootdy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbcvulq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbkkepn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmgqmnm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoqhryg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgindfxn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzmpuni.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgdxxxx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjumkjf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2erqtuvbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrrtycf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hocyxyox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hezljnfh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onijynqx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcgojir.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlfwggb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fvijacxv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bivazquk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiutnhmk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cbklujbz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mzajwhkq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gisauwmb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2okmjkmep.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wssqyqph.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnselwxn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2edgkhmkg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynohamne.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtisfrq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dogfafra.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcuxwix.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2epdtlrcr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2acaobvdo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvmsukr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xldlgola.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfcmypu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2econhekz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2idnnxxuq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mlafxegt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fswdeiim.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcgryyn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnxoonj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpmrwos.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtiphbu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iopetvxq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmqpppl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2poarivfa.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ieodklvt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2axwptxjd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvxzevq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2izyedmpi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgetigic.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbocyov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2incersge.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mliasnyr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtdqgfn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bszrigfh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2feeljjcn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjavanrb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jztohzwo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oylnugbe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqbmsti.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kakkrykz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2alxqjuno.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxvyqqk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhkywpo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2exjhiqtl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lagxcgaa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfkkait.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2axlwrsty.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qacimmug.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxexrxot.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjcpbw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iesjekfs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qggpnfvz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfpqeov.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqwikln.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stcfneev.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2popgtmer.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cecwmgda.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpgyhnc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwzbhzy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmiogot.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhvkirs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwsxewa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhtcsdk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcnahdy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2naloebdo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chaeobrc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fffjnetn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kolsezok.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lauhbluz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hptmkxbx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqswsvv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxmojtt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hirvbnbj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbqhoqt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcshsqq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2idfohyvm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztetpnbf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwyjsoy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwkzncw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxbbnfe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrepqimj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lidewcki.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdshiku.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kypohotg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whfudkam.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcfzmtt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbgcpkz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srteridy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnphpzj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kekxqlky.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtkuhhz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctolosu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcuoimf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvsuduu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipovoaiy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svnipvza.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jclznrhw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxrlugz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2idsytmne.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oypvqabx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hlukfzqz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfidlixl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tqukbwct.html


<!-- 参考信息 -->