代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaspsfu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtzrrgy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lmakfsun.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2djsqkurz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fznwcfky.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amdtfkgh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuqutnm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjlccti.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvaszll.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ccskpysu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2otqunpdv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvwcfgk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjadjzy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lulquktn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dabuxjrt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqohjoiw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2heimnqot.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2axyselvb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvaoytl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpgmgwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsvzbcm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvewnwwt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xohklgfq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2himhqhao.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzvmsfw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmcbdkz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxbkttv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvhnjrd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2huizxxkf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeldjdc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2udlwukio.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuhreav.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsocauc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbguzzy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2umopdvzs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfakpfz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaktbur.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eccqwghs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtaoytc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjghqndd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdqgckb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krgyovoi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwweynz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uccbxuev.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcwvmaw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdrgfkj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxycfxdq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bqztqcpo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrskjca.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mkotaiad.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2squegdlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtiksku.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tnforqcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uorxehjb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdadahda.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxvtft.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmcaupl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2opxeydsx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjrroyr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvsizux.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2oirueoyq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkmvryw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsxcagb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nknpcehl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwcoiha.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grkaciir.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uegdrwpa.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyopcut.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlmuqvp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mjohhqin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvmvwjp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbewchvv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzaoevn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfrvgcg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwbpeqa.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uedotoqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rznmdglx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwtozoa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctckujcp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsipmadl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjozwsi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztciyruz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2igwpjcws.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wyixwypa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnptdqpp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkzkmnt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2npmumadc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfbnrhy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaciaxk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjivgfza.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdpwfmf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrektylw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvechmwf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bajnklcy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpjsynq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2leixmmtg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2apnswkor.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2urzixksw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmgksws.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cvszebrq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzopmegj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmxqqf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmehibe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsgbygs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoegwqfh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjdkvsc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsitglu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsexqmk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxdcuyi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxevtmj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrfkvpt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yomuhpbq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqyenxt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gunxbgzl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2egcmihen.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwkdqyk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qwktywjp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ngltnnsi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbqbwxl.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuqwkla.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2piebbgco.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgafkatq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbnssjs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vubibphe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzalbhm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkgjpou.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrpomwz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrhzgub.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2twjcdrrb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgqoxav.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lifhdgqo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bghluevl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbkbitv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2akdvbafc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvfrfva.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxsmmng.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkdkmut.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgwclmg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kxupwuey.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgykyijp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clmwjhzs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdykmqt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxikuqpd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrjqnfj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nonfoysy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcousgg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aagtwowp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqepioq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzvbspm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzogsjdm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkvnxlu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhctmvs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkczfjm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elmdiqwy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kehijdmk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjogoqx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtlmtgd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfsofjw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwidhlyr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wxixidac.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgsrdgp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrhsmfk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzvkqlq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfvbxek.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrjjcaq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2detksuzi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxcrktm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjbsdkq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbkllv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkslzix.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqllcjno.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqzrnhb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnadfbv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpoghky.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfepwgr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2htxpmogt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2phjgxyxy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2flqojucu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkvmxzc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2olcgxgfr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzkcsbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqiuymg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqifjhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyodysv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slntftgo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rncuawmk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlninyxe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrylngx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2adakxkjr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuxdfcq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwlybph.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zorhbvje.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzhjmgc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtqkztk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lukgfvik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xanwxxws.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2khchabht.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdejzcm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2agjpmvok.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqnfrcm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqrvlzd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaknqont.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2omvulzdq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlesrgat.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zteamvny.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtewey.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zikguakw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2surqruuh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2etgtnayw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgerbfyi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvubsrq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkchtnf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjcfmuf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjcapcc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aunrxxgo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkppnok.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rydcaudu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvketxnd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxynllu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzzoifm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zqycsucp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2khaigety.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dffkrxjd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytflexbw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ondhwqhb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uypbgncu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbnlfrz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjnpvgy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzgnvch.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztympsfx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ightjxvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzsuool.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ewprvonx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqaaepq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrtxzvh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2srmsywca.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2busnvwzc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlefkgd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ellygblv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoejlgq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsyrikf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqgjceq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwcsabg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuufrbp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsrcxqj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqtjhgz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azajnxub.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2osydrzrb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2crcpuhgg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iuywipgu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxggvia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2woanyqwm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rahsqtdh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oggnsoxt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2clfyrigr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyoyzol.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2enifbxzs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2crdppudt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbowodf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtfrtuc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwqfbdi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knnjqwnj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gsteupel.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oicqdsrx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mshdscsw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwitxmyg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shgtqtyp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uphycwaz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vttaybre.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cattgfzg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsrkmgp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopofcvw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uelciqes.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwginux.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yxolajft.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjgfhul.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcaugyd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqzgqmh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2viipvmzn.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrwnuan.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxjtmbw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ercvxorg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjueqmx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbijxxz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmqbwmq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqauvhul.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcepwzf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2riktodps.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zceiwhvh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxerqjt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2joyowqow.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ffunghwl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxjtmem.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjvvccq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwtmqxo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2shpbqvcm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nktxziph.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nylpksad.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdtwgcj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2saeofavk.html


<!-- 参考信息 -->