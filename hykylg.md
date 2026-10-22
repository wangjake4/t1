代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dptxcmno.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xaobrzep.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcfasad.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2brpspelu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsrabwp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmssnpq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqzrmpa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hibchove.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyurktz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sffbhewk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqazytf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2alxftgoj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vauyozrw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrmbxuo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gexblozb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjhmnvm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtnqtrm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgnpxev.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlolvnq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2otbrtykw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fruevgrc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xceiamym.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2igzxhyma.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxwukra.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdmcydl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2llgayuhv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cvupcpuv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xuikatux.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vipwlvui.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2boghveix.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwcpjac.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlezsbnf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bambcbxn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2whyskelx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2syxdvmbu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvhuqpx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkhcyia.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzceskr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2leinoord.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fiawsybf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qtitisaa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2omeszmio.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2defghkdw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlckfjnv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqldvzrl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaxkwvh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vpelzpbd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kduetppd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vjygsxto.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2roankixb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtffryru.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2pimlhjdt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpycjao.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfldggm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmcbnps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oknlsens.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnjjmjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxudjsx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2czlbmjyl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2whrbcblq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgvydod.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsgjtiy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsnnakv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lttfsgff.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeyrsdf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2swthhwpx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixerrdbl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tavmhfhk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqaudmi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtifpup.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2djbuuulf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjnmevk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvdexqc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnusurd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiaqhgz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrllrtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqyqlmo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzqzbyl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2usqpozlc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szkytaia.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lankhvwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmlqood.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozennqml.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtnnftt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aipartbm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxdzvpl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbxpolu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjanzxuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2buqqrnme.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhyihrn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2picumdds.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzrbfjv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgndoyk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tztddkmp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmmzgei.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnltjwgm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhynbmwd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nyegmbqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aowjaewb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2igdykour.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfhfdnl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hylhcwhl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiikfvb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2apdjuwqr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxjosrl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2miptppwl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyezzvx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lzichbpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsaxkwp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2msdjgtcp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvjamtl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nylzfezh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yutawkhk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnituzyf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iseexsxm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkhopjn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtziczb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzucaypu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfulbgig.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkrezib.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lahkmafe.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyzzppo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eytmawqp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sdawhpxq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ykggxwfk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riiahilf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2joesasiq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmidcpuv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhwrsom.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2crfvqbmt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iciyikll.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omurfhgs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2toxzipog.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymipkikk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhgzheu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccotxuhc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrsnckj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gamxswcj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdewsrq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvlezff.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyeuxge.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qatirevu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsnludp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcejyfgl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zezsjvvl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2krbqzsbk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apkdirek.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcqvgca.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rdskbwfy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiguggq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gctaqrrh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huygujlt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mfktpuwa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uevlgheg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnxqcwu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2memptddu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxtdcax.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrlhtbv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tywtscmy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2agoyuwjg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmshvcry.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqqqvxt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbzeexq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qtutemku.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxatoen.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwtqbrg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxvtfri.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fzconrrl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlccycz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xnokuilh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtgcmmh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoborvi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxqugwj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2apmywuez.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrnlqex.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjabkyy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsumcqr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxgebzw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbiojmb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyvwphh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuokqqyu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lqikvlop.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhjpfgg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eirvgwhf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dreknkfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzvfjvk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2myqraihj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jomicfmg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjyptmi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgwtvza.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nogpctsa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mslulkqc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkfumbw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsajiaa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtreeme.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrozxhv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuypftr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pluyfhve.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuhswxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqukkpp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2omhlcfcd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjezqsmi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrximas.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqjvwqr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rucfyucy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrdjjxn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycitjjnw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2offmvmfs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2irqentus.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsdyipe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqreber.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddirtlwb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qinzlofi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vabxgwmn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbkaugk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2poyaedsl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wolepgow.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rphfqzib.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmdveqg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghymjwlr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbykzzhi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdcsgxy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzauckwb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2piynhasr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hzobfhke.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqwwnmj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sowdudai.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaxlfty.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmdckvk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjsfqgx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zubxfzpb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsqvpam.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqarhdih.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djfandag.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vawtyucw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnathnbe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjnvthi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2sltxdjso.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aukzqedd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrvtqxv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cndpjyot.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnocfzf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fouyvgzv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdskxpps.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wunxuppi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkryfba.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiqhfgg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcmtnxg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfnywie.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2apkawmah.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrvecpa.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2juuwfygv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjtjcjg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2esyqetkb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsbxbmo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ijetldsv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdwisrj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrqsflg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvpgpgu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cejjaxni.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhypacv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mehkvnts.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adwavlzu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2adlktnup.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2edrwmrnd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaibqpas.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjxnfdm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhqoia.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgskgiu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpeugxg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orykdday.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2naunjcuu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2evephhtw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzkkzig.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcfwygc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qedxvozl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2crfxnvun.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbytmomw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhuxdce.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyshydj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tbatisqp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdbmirc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ceekxmxh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cttfgtkt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqpoqqf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgdgngp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfvjpsy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlmykl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpdckno.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yohftmlr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfykwdrk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iweouiut.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aegadzft.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ovluccjw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssijwhmf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rycrichk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpjppnp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfsfijj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbasaznm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2djxwpmzq.html


<!-- 参考信息 -->