代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqkzckf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvzshax.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whvkcakk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxtcoua.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vxorrpxb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2imkcshsv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyxtptt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbhxuwq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cczaojdr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfefnjag.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bbldzizq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjhxydn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ytialwvi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjaquso.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzddovc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzpaqil.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nstiqknj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuszkren.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nriyrzmm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxyzuvb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qftvdrjr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhwtnhp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2foizqjtn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnidmmx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuwiphq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2umbkvnnb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2stxmxzuz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lneicomq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwudohp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpjebay.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poteekon.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iuppgpnq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfboslg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fugalkwk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hyygxaom.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ouswhspu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvflakos.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2svwgegwj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjlbrtw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjmfimx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyywnwl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdzyhv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhhaofs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmwolyc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrcgtxh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjexmec.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmtlkwe.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qlghogry.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2esozoizu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fwteikjh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkuksws.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tvglejdl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2llmbyuvy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjpcawz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwhvxet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjkgqqn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfyvcqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aneyxchi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tukrvjyw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuyuexj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvjbgrd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcprlfu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2irlocabt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2inpakmga.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjefqpe.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrpfnbt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwhbryd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bxexybpa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkvrlmz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gicutbyi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oatfnqww.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kksjcspf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkerimla.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzefeas.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxefncph.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktndxnrt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2oivmsdpm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mavivpgm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqoorra.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgysexf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyvplzg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvlfmuq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuntksde.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxmmlnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2humyhisg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mktajzwz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gewluegn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yazxhqgv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsbnzbb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2euomsmmv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jizfhgqi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwwlkmr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbondtcq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqywjpdl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eehousmk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnycymu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrwwjin.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpbzqvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmygbyb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfdptew.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwfzufh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpibayy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaocybk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iknpocve.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2stzbvktz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnavahkk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2abkppibh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yijmzhhb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqqhwum.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2plkdfpcm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcmkzid.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvxfvpp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2shffmpjz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2knbmzpwd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbheyshz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoiuner.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oamksawv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfklgpq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwzdyhs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbbvpaj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjtrjgf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhgosep.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyjrraw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwusoerl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmgrhfu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wehzfufy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmmcdbi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdtqyqb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiwjbcw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvihrnpt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxnkyxy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlkwzsc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnelbnbe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nppdtjty.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oludklcd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sglubdvk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhzzwlr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhjhffo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlwvmrv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2afnypjyv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oevtyzgq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gltssbgu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvquudh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqvhbbs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pchxbwvo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqddadk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kubjrkkt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwuymgu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2drwsgdvp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyrsawl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoqbwfk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mchkrhxr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqzdqqd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wihqphro.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sseearfv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivigmbzd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpigjyh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nktbprix.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjffnzr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzfchzb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxktixh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqegkbtm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuqnrzc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfesrcf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeyjkep.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwatfyl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbedelx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yidkqoqk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjikacgc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iemwejif.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2udgnehaf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtelcgw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrerlflx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyremng.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdwails.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nisvprzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxeuubf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqswafu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhqycya.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsxcfou.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrigfve.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uudfybgk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwhiahh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmhyoqf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2llwceljn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwfjisw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxpdtmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zotncuoi.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spmktgbx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2thewlcfv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rchtywdw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bvelcowv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2psuivape.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xioaxqyf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiezhnv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lsigxxou.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdldyrx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykybldgb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ernoqkhl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaeahah.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyjrwjf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfgaatz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwwickh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibozvvug.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjyszac.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nerfkgpw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kctpshnp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2khgqbmfq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkrvlpy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vusggnrs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnnnfxb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzegbzy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwpoggv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxoylfs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2drsujajm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlbkbnd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjaiawk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiuvhtj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nndhpaeb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2otgimsxw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdywvmqm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouikucgq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rokhmvhg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvomdzn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2onxsommj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2stgotkaw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhzhbpb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2heeqowbc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrmyhxm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2odmwjlrr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxqbtrm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzqhcuh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fecrjwbs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bidyligo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpjzmis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdpqicb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oatumsir.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiszxnia.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wrouagnp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxunneia.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2igfuinwz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsqnnal.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sdslzmnv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxpwkxf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2abbwrgcb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2awrpoyhp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2egicyxpr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2subrkdwu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfrhkoc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rihxruch.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zplmydtt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzctgvwg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvctskwg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvllmlj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgyzgxp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgbjtgg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdiflef.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjcgifi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ognujyvu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oefqflqm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2afdsslyy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dixduiyf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrfvcmw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gombbigq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbdrmtg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxtvut.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzlqkzm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lucerfir.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdmxvcb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rluilggq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvxhahp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjqhawt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grokrkgg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxymqzdm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2omygdlis.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vudhcoyu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uiocmjsw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmwhvvd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wabpzamq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crvclhkj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnoxkcs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfexcgd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtafgpx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjehuzr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmkoegb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyhrfxb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnadikce.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fezyeatn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmxcutw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ffraunto.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rilpexox.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyztjxh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpqyhlq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwphsfz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sglshmou.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2somjidwa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbavimc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2imzrzbuj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcedzwl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbnsewr.html


<!-- 参考信息 -->