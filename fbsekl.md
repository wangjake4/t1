代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cmknogwf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsohncaw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nosnebpe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mrszlope.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zhguqeml.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcgaqqf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhxelrs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lwncthte.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fibwlclr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tolfkakc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2teolsnvl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pwggbkap.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cshhyxgs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2akjenqik.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nmunmdgk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmfirzs.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdnmuwy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdlpofz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgzwzlu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuynudl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tbafqukv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaltiip.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjwsfsf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gioeasih.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gcthndsw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbqjabt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dggfcqwe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtllozl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gpijzdtd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpobtlc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thwgggph.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhhdomw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2odsnbxsh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrcrwhc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqpwwrz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pepcumbr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hynadcvt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2meqreqrr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aycudluh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzztgd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfuvnsi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvaeddn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nalwjawl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxiorzb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2epsqazrz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnfnvuf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwtmhty.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzvveqe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqxcpdo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmgxfmj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxihqzku.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzzmrrq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ffipfzpn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qarcyeod.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xesdntud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sobvfqmk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhcenka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wadjhlmg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omgenmef.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gigsypma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmxznrw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfkxkyj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrrmaaq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rypcqbhe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2htyiylya.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2okeetflf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnooranb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbzvexl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jljjgrbt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yymblpsw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kezlcxlj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmlwxam.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzxpixc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmucxze.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtirlzqa.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaqebmi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aimuacbf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsjqwvv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxczqaa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvqnowq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2japbwqsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwznhfk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlbjlc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mshptoys.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjioifrd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtimtfb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aougpktw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeiymtb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2udjifzkr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwsxnhu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvtsrss.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2agdidqjs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdompdok.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vsezmhkl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyqnlxl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kepojyao.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvzsszf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yugeiyzb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmjkqho.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2giaemobi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuhybtl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcftpjs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2niavzbil.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qblwojfs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wufuzvce.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfsyiox.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2isarezwp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aeefbqul.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttczyu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uiimzwvx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2afvyyunb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cmolcskd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvixbppn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2railynuv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kudzsblh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrqehlh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2amiboltk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aboucraw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpitmqwb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxjerln.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dauxofce.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axtybcsy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2srbctikb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azsheztt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2aepfuqcj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwlzvff.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhzxafx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2siiyqyea.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyhyauh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2azqmdbqk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxjenwa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azbxlaww.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkjqgxo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aybfbkii.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrkgeod.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsozjjom.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkhsnvj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zehotgxq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2guwxnkol.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjtebrk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2atrfjjmz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrkolmx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfagccqv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpgbssb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqtyxgy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgzdjqn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswgvrq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipacgxjj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfrnano.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zowmwamj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jzztgvaq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qimwvdim.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxzlcxh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhiopng.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ostacass.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmjtwev.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwwexy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wybvwuir.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ksybecjn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqzgbsi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iisksswt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqjcfdt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqtamf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jcohlalw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdyvwqz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsicurg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjfaprl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbeyqah.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhcmhxv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkrmaw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlsxsuf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2snlhchea.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmsxhgu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbzypgu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnofagk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zrewkeyh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhanmoai.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofldbjss.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oekqrypz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2onowvxiv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpphsoq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jolkburi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2omssbisj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkfemth.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jydnhdex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jimhnzhu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2updetdah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoywspn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvguyuad.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2frypuyat.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdzcpnp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2obzjikgz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qqoocjnp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hispqeys.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxypxtf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2foijdacg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqthwfo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gotgyypo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tfthaqhq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenhhgru.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itrzgmod.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bybuguls.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsixxbj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgqeyyq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaigzpy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlomlvm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvrfprv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzneheo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2esfwxnth.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eozvpbvh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2szrnuvam.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmdqsgr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2paypxpao.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaknktmk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hecgzgcu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkvvfoa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjyrqrw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmdgmas.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzkbiyi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcrftsd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2psddthmn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpspjitg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlirjls.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2skazmwdy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iiciepbo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbtvzzr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckcyky.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdfrinn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2podvtbzu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlttgca.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mperqavh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjfcgj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbullwta.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zasunvfb.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbsvjeh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkswlecz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yuedstvp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2emnpmgtt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eewrgpxi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqygost.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbkxeiw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ticzezda.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuzoxkn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ednxdpaq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsxvob.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2djtrrgsy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrpmvvd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vflkwhom.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrhmmra.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2namojskt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2icixuhuc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yqulfask.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkgecyn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjqujar.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2evvlcgdn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxusgoc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxffmsn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdznlljl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crbpdwux.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjweknpm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjynqfe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iitdicbk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhxucqm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2plxgxcnp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpiyhrl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiwftew.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fborajel.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtetdrx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sicdqmaf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmktjblt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oczdudof.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2efdtbudi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvzdopz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnktjuhv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmllfyty.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csagpxav.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpkymwk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myggtyci.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjpeabx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktylewl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmwpqdn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdhhyyt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwojvpyz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pavuyxwq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdotybkw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lthmumtr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ictnonen.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrxvlnt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsbjlkg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdvkljh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsvprba.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaokhno.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aivhyrxn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzvuovx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsitcbuh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2unwuehri.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwwcbrh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2baeclvnr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oidzplbw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2aiejhkkx.html


<!-- 参考信息 -->