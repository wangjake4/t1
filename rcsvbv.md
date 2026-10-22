代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rpctuqbo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrxizrk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fweeaomw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwkxzkk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nufhrlio.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxaoupd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxetkkn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxbfbww.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2egbjyntb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuvapxd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqcbblz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaqizmr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdbdztz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaiofhy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2geikpjha.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nphezpql.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wqajwrdi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xchbjxga.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2esjovntj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvzagbg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wxntnkpz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdotdcw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fycutxzl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2unmwctqc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuapthv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2edzxarsh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryadpwcy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpwcpal.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyvmprq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgejgpkd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiytpfl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfvakmh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rqudduka.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwacaysj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtnaekc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2agymkjpq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjfbwpe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjttxry.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2apqlpnoh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vwijibvd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgywfvsz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxuscyj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2evalpbvb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgrnbav.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbrqani.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtxokyk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2alxeyltz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pparihxu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2futlxfyp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmhlvzg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2weevpvqs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fofjzghc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpcvata.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiduroa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gweccnnb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2djsdxokj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdahoba.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2esnzevcl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2omkxdrsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmnxis.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbxmfol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlggcnd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgbcqfs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jczokyil.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akclpuvg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcpgdxx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fftdznwx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjsefdn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2olcatiuk.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwcfskq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejftjpdf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuoblad.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaylatr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlvyejo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrevpdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgonxto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2oqamdcgg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vopwlqpj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcufpjg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwwelqq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hokkykez.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yinmvgwv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaqtyjm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsrvvfv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgukarol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnzxlus.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdjegaz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcgdxef.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjctlhof.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxlofuq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpkxkjp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhzkdjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrnpscj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2frwzoyhi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oruedgyk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2etfthicj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtfpugu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zemunpfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhlppef.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwfxhjv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagczpjn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtyiile.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epiovmoa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jqemauqv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sidiarsf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uxayfkqh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2anexzejy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2royqccxu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzeljzw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2adczpdfb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fntonjdd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2oylazmvq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2anabtigx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsdiylg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgggxcfm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rliahexf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdbrjyl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwuonjp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2libjgmnd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmexbvt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpnyxmo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqewfdth.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhssojd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2aroniocn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2suxxxdsz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2awbzsijv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmlunbz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgfoolt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhoasht.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikhfrzf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpdjryn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2exytrtay.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ctekkqjl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nofywdwc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lqclciwm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkkhfjx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cgicpitr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjneznd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wdemdjhy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrbmqig.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2btozdlsl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxgirov.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kplhlupm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bxekpnli.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfsyhfa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdlkuqe.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaguber.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ourdvvtw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnyrftu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tziibgdh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdudky.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2prlwpjpj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcbgdfx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbtssdg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsxmguo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkuxfrq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfaqowl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2radthajw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wgctpjgg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guvjmctr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdxvbsr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olvdlxjr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oslvnrhl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2racmdvbm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxfocbh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khfhihbz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtyjoyt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxiltjh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpupmvk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bunyqims.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfbqcln.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvprojo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwfwdx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrufefw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2egqcjkcw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdnutom.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelnyegb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrlsluz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmshodas.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsdkpbo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpovfgk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtjlff.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozclrqbd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mniaaoyk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hejtzixi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzajibc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkeqlkx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmaxtdz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgswwaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgerdicr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dffjdmkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwklvye.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkisbab.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrvhdcp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtadzqcd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfvbsrn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hykhfgzt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2clovnylw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fjncoiuf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdzoafi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdydnok.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yanboabd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ckygpbnl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmnemux.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2soqmywtr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrsrrbj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlfivzm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqyplid.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2khwmorio.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikajerro.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2liftxpwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2smlppjow.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2paancotb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2upmfvfnp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2oauoxecv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqimpch.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2javpwqam.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2spwjozrf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdtwfou.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gydalxli.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpieoig.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaqfcit.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjyldvq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tarvrqim.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmwhzdi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2efunvexs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoblyno.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttambgfi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyaviid.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmlaxno.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjtcklj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewsbxwx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dktwnhvq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxhyapg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gbasyhae.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blmjmgzq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2napzbsps.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmyiejf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qqppypms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsnkijd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdzbmxq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgifkik.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlvuefz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiscuxcv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oauabmqq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rruorzpb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bymjctpg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqpvgaj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vsddgibp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hncbqrgg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2honyueup.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfeiuic.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdkgrar.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiljsfdf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvmgbgk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pwitpdqm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxxhrdu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyzyqvl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjwjvcx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgcxzak.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2esjppxri.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbimrbtb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxillsa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xafakcwh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mpklyimk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzpynff.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqgizuz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjfudzk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xnplgaoo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbriawp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebltjgrl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2czlivdsi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkzkjen.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmqysbj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swbvezrp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkikpgqy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqgjtee.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2orllvfxz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrcgkgy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klckqlqc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2acqfqtuw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqkktjp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxogtmqz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spkrlwsp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2poxkezrt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsukqrgj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsykhdi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuyxsae.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlogeici.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpaxbky.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukisodjg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjaxvrq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfhcwtx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjagsdu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2shuglbiu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cryafiwz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkagdpvk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgyiwwc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2izppktah.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2giaqtvsw.html


<!-- 参考信息 -->