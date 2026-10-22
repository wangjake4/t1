代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoybigi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxehedz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skwtpfdm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2shdggpxq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tnufljrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mipxqycs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuqxjzr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qsitnjad.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgxdjfl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pacdvfux.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxokgji.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyrqtav.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wmttojqj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2murivqju.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvrigoz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jizypajw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uohhyloe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hunzflkg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrmhfit.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2buctvxsw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2enuddrma.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lhioeipx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tumzidld.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcwlcmt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxjopkp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckchgjop.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmeyhib.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfgktbo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsdgofh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvlvqxl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhnejxv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxizfcot.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2maxumukx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kummtuzh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2alyrrjfp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qwatapul.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiobvau.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oelgyoao.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtwhkin.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2koyfqvzx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbjuhmv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpgntol.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efftuvxc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ropgknnf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvubftif.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzavetlq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kvivdaff.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bixvhvgx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pdomplpv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwhkcpo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzwlsqx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rekeijtp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qirjljao.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvoscqt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2szxfbxby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhlceev.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mnskveou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyfjixb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hamtiavt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rraihkuz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sltkbfup.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2txhphitr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpendxyo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrflicbs.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptidsmj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbtvamu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2whmjngrx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpcnaeg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cffwcsei.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iubwefpt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tcilpdva.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtnlpnz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkqpyhv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2faiwtazo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2luabjrkr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqffntl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2unuttogw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjtdmbb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2seehnspp.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvretov.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2shpnugjs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcssepc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2edlbyryv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szjngpfv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfcxzet.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gohyudbv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2seyoghwf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbhcyjo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhmaugm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwdrzfg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2obclpwwh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoqzdtw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2msgzkrha.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrqpoby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtzfphb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxggdsrw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlakqcwi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpoaarq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2foyxveui.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgkevmp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cndsnbhh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ckarsebl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vunecujj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2srgkrgol.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdxcwvf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdueadz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhegwagk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lasbvnyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2exibthqb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhddzhpk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihseba.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2binkxyuc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuqyyih.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwsopph.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbejtshh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrwbupu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztrcicx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwfthvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcepuny.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hudzrdki.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yvajxjlj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rthigpvy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lintkrzh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twtrokst.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2juswwamw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjufirvb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jamvpwfj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhrxvom.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnfhvxv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuxjpsf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2grfqlfzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhnkunp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmvkefa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgozriph.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ficyoljc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mymwhirv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kafugzsk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adujmcja.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aamlqrpc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2czdohmyq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkwnsmw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzxfiku.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlnbtty.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uamfwkvd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2masrtqwh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phhlrbyb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpmgejc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuojysv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2iomdgnhn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkddmev.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lsloeqfr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eujnpzxz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrhbqat.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdsvsnq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2msnioule.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pedscnhq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cexvjrxv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rreykvqc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfjssat.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2scntqqdx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqwynxd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbujjmn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2onwafxxb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqkltks.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxxksw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfozgwjb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kriprwdt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhglbxr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzennwqg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmpohfi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbjqmbm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvezeyb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqsjkje.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvosput.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsidapp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vroaheqt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auqhigmb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkzeual.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiqbwhe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jljchnzs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihanegm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ypttwhko.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcafpdi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2itjhrpon.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ouozwnbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2indsjrxa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcufyikf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmixlqmv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfdrdhb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2avxuakwn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awecezia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2heodwsen.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjkbkcu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxipcvkh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2slpifmiu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzthvkdd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dtggmiyr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhafaudp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxmutrb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsgoxrf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wfokpunc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzjevli.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eehmarvb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbloymey.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxuuthm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvifparn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuskxcss.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2etjtsjuf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtwzbf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nugxfqpk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeojlif.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxkkwpb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyxuapo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeohumya.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyikxfev.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdbziqr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdbyywp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvqvpq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxzgwbv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhnhdop.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2otsglejl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cnynzwlh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhamcpxv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaqeopp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2akbplvsb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2amqtlwot.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dynvwnpc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnsibit.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2slbfrktl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjucuih.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iideiajj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zigyyskc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msleyxvp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpsgysd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2knsuwnsa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yztfzxaq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vneuyumc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmajlvn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiouxnn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfuaxsf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jwerumlg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzgbzlv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfecvyf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhrjokd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2czkwxpfo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2apngutpa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2blbocffq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxdqabv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npfgzizj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqeakdj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqiqutb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2brgsbmmn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oldqzumc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoxflfg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqkgvgu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jskcjpnn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgyaywx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2asrsxnex.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeahewk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2leliouvp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnynsvs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcjwhzx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzuebpz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgcyezv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaoeuev.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tennnpmi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fydtbqva.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfkzxbv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jutfjgsf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrnazll.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skcexrgw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cooyozcd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zeluuuzl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxorkfz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2urlrbaqi.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzbejde.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvursbt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyuoerm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2upxnmdev.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjuivrx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wqghyoww.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcvlryr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2glmvnmeb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmlyzpr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdwvsep.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjorurri.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dodbasib.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvrydfv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwafjlue.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfbgbjj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqauijy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhztsyz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oembjalj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmijbqy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qckihwsa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fumngdbs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drqstfqv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhloiom.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoyibmy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyemzvf.html


<!-- 参考信息 -->