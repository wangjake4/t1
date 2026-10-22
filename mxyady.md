代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgojgsx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrbxld.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjrrbvy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfoxyca.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevgfkz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yoblqtja.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2urdprrwz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cyflihcc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbdiqau.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzobczee.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsompto.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuuhmsi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgufebs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmqtddw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqiwnxp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2elqxwkhf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pipqhfrc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqrrhmx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbqamaa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqkutpk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlnaiyg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2biyxdxkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzbkglz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cavbvcje.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgggpbq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qarwagry.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuchgvd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpwgqiy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwknvhj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ntubvxbx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idmptvjc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2johbyiyw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eakgjawc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjlnqnb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeischi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2chlsuvxr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqskqfcz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgssotps.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cykocopl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mltyzpih.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwlowht.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdgkwtw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rppvtvaa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zthggiaz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfdzawg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cwabnomw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2niiydwys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlbbtei.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yszzblmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evfdyehc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgtwodj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bejwiiaq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpptekv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2spklvcvh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2faioevqi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2foxbwndu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hknbjlaq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mvalogfp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2leplhhhk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lssnryrb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlnhgca.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwwkgtq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwxfjsu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nafqtqna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2empwvofm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaxuvtz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcliqhqv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjwykid.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uovakpmn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kldqxmiz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzyffeq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfwhtf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vtavymnv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ospvyqit.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2idhdljzr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dodstgzc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnoiqdk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sbceqtgd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpirrtj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfjyrfu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvvrolb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2anfnwxrx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qofefufi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvkbgnx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcmkzdh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2henrytyc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymgfvfv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcgvgji.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfruwww.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tfahooeu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2plwbhizj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vjetuxjt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eubdceng.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbyxgpu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehxdpy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrdljis.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2miqdujwg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwbxntt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2emrfchak.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2frezlkhz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2poixxmvk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaghysn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfspnjtj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkewvca.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgfxtvh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kofdshux.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlreufwa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2migpkokp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnowqmo.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2upaxwubk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwadkxrs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dciolvuw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uganjcne.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dckaaraz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yelynlfj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwajges.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrwdfxs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nstvlyui.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhibvvt.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgbbtiq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ellnxidd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkcxwqw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zifxaiqw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qboeknvz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwgvumk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrigmrwo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxafqjx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctherhkm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdhpbob.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuelrlr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxgrgd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyptdmw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxsrslo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hvenaafq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yalzukpr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjveaguk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2crzmmrhj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqbitqo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfrcmdy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdogcpfu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaigqdy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wopldovh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sesotuyt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdyssig.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mtirviow.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwehotz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrxrnst.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzohint.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiqdnxr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vickbdus.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkkseqi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sssdkdgd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2erjfnnnz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqhzhjh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2obkysqor.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2njzqlezy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzuhrvf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yfndjymp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cailijys.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2henlskah.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpcvidw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgbxhxd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzwcsxr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2anjasath.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksziptss.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpuztfz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpqnpvg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2igbjilzf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgucqpp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlksqoi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2veldaccz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgahpwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aosjbzkc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2firptfgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2odmxxsau.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2djphybpk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2otlwsgjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdesqbhq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nopzhhtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyweaict.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bazftwjk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2horbrlkj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxtwesv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jgujdggm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfqghti.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzlkzjp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2blnfwqad.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xatyccwu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmumlac.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uleyhjep.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvjvfjm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtmbszq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bicanklh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwshipz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmhrgvr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rztugmkr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkudvuar.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnewnvb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwuuobr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2twfnawop.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ushkwrmi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwijxja.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hnomgrzx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysczlrcj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcyoqsc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2btwqetla.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2szyleyes.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2epqwyjdn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmcyfwi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqatjqjd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbutrbro.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kycsqikw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsqinff.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoxvohf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oixuazzg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2escogtra.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ndesrhnc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlpgtuh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhgpulo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2btubdtzq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jllfcrsk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyaimzd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dzikqwdq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdvvber.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqwhplm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvzwouq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zwullxsr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dceqkgro.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yuztnclp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwxtxzr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgmrcrq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtvnayv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kigjnsoi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaszypj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwthrit.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymaobw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2roajkpxs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkjfnvk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoettix.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2axcxqzoz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoeixhm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqzwifi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tptwsakc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvizzxvq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikicbpzs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yybpmbzr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfekpjaf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiabhzq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxqcnle.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwzpknq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xapyidna.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvauaer.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qymadbup.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbthqpxb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsyfkgs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hykxcmyh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akxnzubm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lywmolvj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bleatfzd.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdymijj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmgtww.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvspvql.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fubvryvp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2assdzckf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnioqbyg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjxbyyw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2izuszlxv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlflapjr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2welxsywe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kltdpkbb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2srbrtwfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijnpror.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuahbjw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oizfkwyl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvosggm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvvgzqy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phjwepsl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbikfdl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkpoomc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvyoenx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjclpfg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwlwhpu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyflcsar.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjubqqo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjwedse.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2itrnpqmf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljygunoo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxmlmuq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkupwmi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwoqlli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2beghcdse.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfyddfr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyafkom.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eemjlcws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoiascp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2csjxbwbw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cktornck.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xlerdhzt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2irhyzzyb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxrexnd.html


<!-- 参考信息 -->