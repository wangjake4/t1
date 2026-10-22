代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hritofkd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnwfipk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bluqfcsm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2knecsnou.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tqienryk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rekjqdab.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mwngqbde.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyqvisf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxabtaq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gznhazuc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2idprhowx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwkqvov.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oytzmxzh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdrxmit.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2baqkblfr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvouxfm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pobruvcy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhfyymk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gerhmkxu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuowyic.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2frpqqcfd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2exzoeukd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfkiktl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xhapjibh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2etcrhwmz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2awfxtssi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2onxextfz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gscllonl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zwodvjwz.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlndenp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwugvnit.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvbvoto.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2djvctfyz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjnllpn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2towomltz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlobboo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lskrthoh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfqdgxt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqgojs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqihcpn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwiwxnf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdnmjsj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfegqhtq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfiflqk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mskrbake.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrphxxhk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vfphcsla.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdedypss.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2epdcdmem.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvhekuo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gliiwems.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpxbnad.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrnvqdi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfwidcf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwwverd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxgfrif.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2acitquun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjbsclb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swrlpjdw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2poebquet.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwrjwkq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2egkhyqlr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcfbhsn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuphgqo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhbfemt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wctpiddj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtkfzpv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkjfmpq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erkrnnby.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvjnaas.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlejwgr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ehidtusa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqpptei.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wurlrlix.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdwssjp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2etojdvnj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uuynlktf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsrxqlh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2afxivvoj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpprjcf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tknmhhko.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2olpafdud.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2actcequt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dftsdpdk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyzanvr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjjpwxu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvgmhni.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdrxnmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bghzeszy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjtxunc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qafimktb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxawnri.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsvdmdu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xytsjbze.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2afgdsnsb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnhhqir.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhbkggw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvnrzhk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epovwftw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2caffmsdu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2euxefawc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxlnwms.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rporpzjx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wigmzimm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvxqpgj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gewmbstf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2avrgmqgw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeufcxz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaazckl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pybfdior.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhhwoom.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqscizx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaeeloa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjjypml.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqsicrc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbomgqw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2puurhkmq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqpyojm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xplcvvoa.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyqldlz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyrnioz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiyivke.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xavmycjk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mevuaezi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pmawjggk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqrikxk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdapujoc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkykbpu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzbsega.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrtlbcf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqbyirw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xttemjgc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wobhitxc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvjoetf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxrcozu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvykdopd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpkzmll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2swabavfa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2osjaxfhv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuaoonz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfxrvdy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nntvahfl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqggpox.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2enitnytw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgalcnm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkkhxdg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqaqaop.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvxblkp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uvftpgfc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksustfel.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2woqnfaev.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxllnfxt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2geamvzxh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhbvhcf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvpgrek.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsndsjqa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoqobui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvvqwiq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzbhpau.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzzmieg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwpbofw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoorjxfq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaephcvq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtykscx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2njzcdplc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jntvexjs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vtajraxt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfcauqj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbyeoie.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sdncjqwh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmknzoea.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2otldykja.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsopymfz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmcjuba.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbovjou.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2grssrgdm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vatofqzu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2skcwjjii.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiigujs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqloqbm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhvtmcf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cshpjqam.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwaqwpw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiohdyk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvthuxn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azqnxvgk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajekgfcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvhegqy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vqypiiak.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbfzzoh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsgufic.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2taybxzcz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qknqhfla.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxmnekj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uipfjjlp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyehxbg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqokrwh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlocrvn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iyakengk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvvrbvvt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnpmdvi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npchvuob.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlipidd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2loutbzrc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxxgtff.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfqkqmb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwdjhjc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrirmiv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ylltemxb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oprafypy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlpvlic.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbapkige.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjadlnmn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfyabkt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ralyzmyq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeutrjh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjwlzcp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkldbssp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pazztplr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2orgmbqtb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2egbnpwpi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qahifwqi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqykuqxl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cswebbpu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cirxcjti.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpnvrzl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzsikhv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogavlsea.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlpauxt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2diqobjej.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zddrdhcj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yteosqak.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jksslins.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwengros.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqmlgyp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2snyfclla.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ktriefyi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnwmuna.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaxiava.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2amqzdwxq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2inumhcqe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkkxpnq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhmipek.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtldgug.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bibzcobt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeerurm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lttvmrej.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fshrhtgs.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hetkfayy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wszouoqs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqfvywi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wamksoos.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjknfgl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ppykdptz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsmkgoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgsjjoa.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydonntbi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftehrdzp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrkadmg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyzoaag.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2amohzakt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2imxzzpih.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjyxgpm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlqsefr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaaethp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpizvdn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hlufxzsf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmbvets.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emymfwir.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2efujnmce.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnahlng.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtomuqw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2awbfgjpd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2okgtvrpa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gecduezu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcabaekt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pndoxmaz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmgtwhr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sisrhuxe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbemryxn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2acdngrkm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymraadav.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2poanaatp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusajknn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwpbeqc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeycivum.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcuaney.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtveqhk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kueyjfnx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oydkkbef.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoitmip.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpdkcqd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lyblwwhq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2loijbshn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2louryiuf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmakphd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgetbrqb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmlmehs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psjnzmxh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeqtbna.html


<!-- 参考信息 -->