代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzsenwm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeqhnrk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiihydw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2oxexwlpt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvprtou.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2heucyrwa.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tcemrndo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwefcpq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmpnnfq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyhhbuu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2isbmykhj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcllsey.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvclbax.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqginss.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hjicqfgn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqipdys.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpflgkr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oulsdpmo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2excvcvle.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2njfmivya.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mkujkzqh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgrkzvl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpycxazi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2efyvztin.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwjjjcm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxnahpj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2heyfbgfy.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjxfbbm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxbotsv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdovpvv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnunnrg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjdkmfw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeebkiu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pihftwil.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhwsydj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrqwoje.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpecplqt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ashpxizf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzcjepa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqtptju.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zurypnaz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ctormate.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdrglrw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcwmxft.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcockfjx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeskcrk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnklxmm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gmaksbnb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjwwblm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sygoscko.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekawbuxp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxrqdjm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvrzxbm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2abwuykix.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmpehbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwinkbir.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwullma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fopaijdk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdvvkgb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcwkspx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bizfvnth.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeocugx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxipykny.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnykchvw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhhagxd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgibskd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2olfouhzg.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lizrodvp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2awdpnayg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dlypdblp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfbvjgu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2okucghuu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewidanxe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaxxqom.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiyxvuq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxbviwy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zinbaqvv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzbgvrs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnvbxug.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smyvykvz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eubsjkcl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vweumxzs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tarsfsfe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wilmccck.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uidsrvur.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xivwszxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuejtnxw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2emusspiy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2esrbzqwx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkzsyfy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwnorir.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmouodx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsawujwm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cswhtwyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zreiupav.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdisyap.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzcszdd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyadqhf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbfyznb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2orbqbiiv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pognnkpl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwvrenr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eglotjtj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hszpkhge.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjgjslh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiuxyzo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2upuebqbj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2swnegptn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwjhmpx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgjksvc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnxcxuj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsxmtrg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrezcpiw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bprigehl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiznvzgc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2drvoempi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2butlnuce.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qddcqbko.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzsjuvv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hlinzwxx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2skwvhpuh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iadlgzyf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzdgrzo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lenhcgoq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dptprgcz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vowkbbdd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2znctefrs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjnnhgz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ontxbsyo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkihtcuq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mluhuvha.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uykvklna.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqsnron.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnmiuoo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2plkmcsfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zszfrnao.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iikakhqr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xknwzlov.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcopgah.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2phasxptt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ngugzhmd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uprqfikk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmqrjef.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmmmtsq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvalyvpd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoepwxn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgkxktf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2frizkyok.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrojjpg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dymmtcxe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmnaaot.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoxiwhy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqlduwr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfsjxqr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbenqjn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tggchioo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgdswen.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eglazzwj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuniaenp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaogbqdh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdgwttp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaijyrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yywlkobp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2krnxqurj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yndcpnmn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvnmmzc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmphqzq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbgalzu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbvmfnt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyrgpip.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdwrxv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2densjups.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmywtpd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxfnctb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2svifqdpk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqnkple.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzwetjg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxttlfy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cojpikdb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaefwoj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsdewys.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2axvokyto.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmymyyi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rzddleud.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mumwikbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpdexzd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zazajvka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsgeaet.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtarkxkj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqvkwct.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmpfdqw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnevjyq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbmneen.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aclawibl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhnllup.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxytuvwt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymssabwv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2keabrrwi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sizvqyky.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojjugkz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpserhf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iummoaxp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzqyhos.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtqhgad.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzvamdv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkebzrx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pecvpsnt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwjwnym.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wekzyxyn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukprowqk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lyngarft.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrhmqhe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eeubnexf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vesnympz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sakiizus.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdeaxga.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uunbjlht.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2egxpdggs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyitumu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrmiwcy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdabahxv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rooyjmqn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pytxvphb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2akrtaepv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2otvobnww.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjkccmv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rxafjjru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmrqiyg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fevseoyb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cekjxkcp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwghnxt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2woprsecb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwquzinb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2geiuckgy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vllydasx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbmdrid.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmhskto.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxswgkj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kaegddha.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oplehqfz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yddbpbvi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aabemzud.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ravheycj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdaxhfh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ycanrevz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcbmixh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqmselx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkabfrvw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stlzdnbx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbwupgv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpksiuqk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mmytaeob.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nikwvsjn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qhepdlxp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzlyuww.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkholfl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsngusoz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgxdpjy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqplswr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwthrpds.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qfflhbwd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfelcsq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aboiqkbs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2abtszltt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkdpyom.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fepshres.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnrunun.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsjibxn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfvesgd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcrrgcw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rsevrket.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whrxnxic.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgppjbva.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceemrngt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dknyumwc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwekcop.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vetipobn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smrfgneo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxapbku.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxyzcrg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2idryedpn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsikxzqd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhqbxby.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oierzgbp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oakmsjua.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwosmrub.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcthrlr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwiqxml.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dplowikt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avzypvsp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmlwozx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxrjtor.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fipiqiyq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjhzhnl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lazrjktv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmxkzvl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuksfpso.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdfayns.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzpiyxv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbnkfyz.html


<!-- 参考信息 -->