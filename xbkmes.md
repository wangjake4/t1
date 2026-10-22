代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wimeqqpf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfgwvws.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvhkquy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kamohsjv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjffvqb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvexxut.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rlucithg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fgacosgh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxykeab.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxgvban.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdryxic.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jncbfnhs.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxhzwzj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcjxedx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgjnxjx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qrywkxou.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxyywve.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvlmkxm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eeusnjcf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjudmva.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wufliayg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yslxzjwi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okcltavw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsaejhj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2reodpyez.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2otbxquqz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpowmzb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsujxyyk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlogiaqz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qeikrkkn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcuhwrz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvqzmfl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfmgdpu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nobpuhux.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjcpoun.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrojlzob.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuawpmke.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnjwmfx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjwkwoa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbywdal.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gbazhcpj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwwmhoy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbvpqfq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tucclbcp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbtqdqb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xnczjlel.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgdlcgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyogsetz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtvwomk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbzmnnu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmprgni.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gisvostk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aeytltjr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvoqvua.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiehfkeu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yykzjcfe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyphuufx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hraeftmd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iitexqwz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgqaqns.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vysnstjl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pblyspjm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eytucytv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xkufzlon.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2itwwdawh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfuvryd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvvyjtt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2teolxcas.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xcozogku.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmlyrsd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeabbeoi.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxvmtep.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcitpyd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsgeorw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbljuhm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esbszrmx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aauzylxm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpycjmb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blotexdb.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uudjpils.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkbxwdy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nberwvhn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2svnursyp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtwivnn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2adiuxnxv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdjammk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiriijv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mikhpvkv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2juxipmah.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoljtfr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfryumhn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpnxhla.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2temejogb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2npqlanik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2aasazeuz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eztjufvj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdzknvt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnifwqxa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqmsmlo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiyfqzg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgauzwih.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzrnxpf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhluszz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxpxteg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgesqel.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2muwlyivp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgddycqn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkgalkt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdsnlra.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjogjvsz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqrlvib.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyqzyqk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfosklt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmttsfvp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrmhubv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2woylbphs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uaboruvm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khyyskpf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjekfzr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hklkrfvw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwlimhj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfygwuuv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnjlxng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyapwdvt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ndamkzsq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpkrmmh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2atifytbo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqakhux.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vphpqxll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljohhdna.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdywqmby.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zirkhxak.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkyylyz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hztxacfk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgwbyfu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2namenkhx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evapqpkk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yftufqth.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpjkutm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vomzefbq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnvpido.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fprcyusb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjiatjv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chtpdxfi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjfrjnb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pciuoomn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsxnjsu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfvvkpp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfxbjcb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gogckchr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdxgsci.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqliogpc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atjzqlrs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2draepkmx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ssosgfzb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwiuvny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjeiauu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tiebrabh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvtqikf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqemqmi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuibidl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eudlhduf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlrjqpk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rywptdel.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jueslzul.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzeowen.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbufyixj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2szlbohek.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfralrba.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2exzxjnex.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2reetcalk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbjfvtr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxnyvzd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2poslcbwk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wilwxyvz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vikvypli.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqgutpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgjfezy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2alyhxlcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfofiobb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uuollylo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2psprcadn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgbzkli.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrnmhts.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2agxeclkw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyqerra.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvhybpd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpwztxn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkxdwav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrwrara.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxnsxgb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wryuyijx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeohtoq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xierwhqt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrisbib.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2janjdowd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaokyoo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2onxwnbql.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjlzenf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnkjdmh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzfllcj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylepniyz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dxadnnmi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgptwfn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaqowdf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2agysbjqd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2obcbdafh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yztvfpoj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrvbhlx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2koqatebr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mojyspxe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaivwqz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnjsuoq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llmxwtbb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tftsfgfu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2taztevda.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sahnaspi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyoelbqv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtohril.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvbmtgk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2thgagetq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2deeosveo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoofmdx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtrcgux.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vupefqpa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tprndswl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kenetnws.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxdjtse.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsqvvga.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrhbfwt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lycqikbu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuydtnw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svcnypcu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzfspfw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2waetrzyb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ortcpnde.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wrafyxcs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2szumxuyp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwxvsvs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbqdgbe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aynafpws.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qclusxwj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaovsuta.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoiafyp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuosguf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pcptwygy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mywrgfzy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2clzyhttd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjwvosc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcvbfdg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoviwydn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2btowrglh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcrtfnb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtjmzcf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiiubkn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2forbdcox.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rykpunmc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqkgqum.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcswalio.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ecehtrda.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lvruripm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwbhhbt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwledwsx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihscekat.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2erxjlyrl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsloeksq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqftllli.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unjafkfk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhrjels.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kthjgjkz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lumdszhy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woixygwm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2thznuzqe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysheozgu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hazycuvm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2erwctlnh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhjzndw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uprysbpr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adallmcd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyffdagk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grfebyeo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcxekhb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbphcifn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vqifzayd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qkurgjic.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2losbumez.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2shctmuya.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tulbvgpr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czlmxadz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krwwlpkq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgyomqd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkdxjqi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqxuqwv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hthpphjh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2klqoveai.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyvnggb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxqntqu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2irmhvqam.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrtlduc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkhsngc.html


<!-- 参考信息 -->