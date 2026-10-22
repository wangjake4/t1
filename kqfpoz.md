代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2flsipnxj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzdplgq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiprnqw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sqklmwry.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgdwhje.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlmjcgv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pqulajlp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbieqhx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlabuds.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oyynkjjg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzfjwzy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ellmvdwf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ccynmfsv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igjwmlov.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbhvbmp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ndziqcku.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2knivizzb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dagjyovq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yllgbeue.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2avfxonpo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cznrqwzg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2igrgivix.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjvylqk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxnbwgl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyuxjoj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pugikyea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdssnrrx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgflvvth.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjxlnqe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqzsysx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nodkbnuc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kruyvsbh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2obnhqqab.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuzlayq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtbknje.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pnoigdpp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwtmfug.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2npmnvgst.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glahthym.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiasyev.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fredlzcf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2faecnjab.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jumrzwqg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2fiixesgm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nomxufie.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyghvmf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxsxrbk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rikdlmdk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrayzjm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lbndolwk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfweaqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2supfdfnl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2euafxpxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaqxvpc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnywtnp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmptuba.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbnplng.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2disipydh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxhvhql.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2doqjapcv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2whxtfnqs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmtjzmb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeunlyz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xhankizu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppusvoz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbxxapb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uiryeokj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qahpxdsx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfrvpzm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uypzmbnu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqedmoc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nsukovzn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pyohafwh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwsmtkk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jplbyara.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szlterbu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hulcscui.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rztvaugu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcpwhjg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjdgcpw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkoergi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xumexxaq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2buoizfwh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fznfffri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2okptdcxl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoqzawb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2oiethhfd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2afinwruv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuooxwe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eufhcbyl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sezrnxiz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2udvdnlgy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeyuxcz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2llixmbcg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbogpfdw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbkzcvn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2upsfhwoh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dzncoqep.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eprgqoju.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnoxgcz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2auxkcnao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrawvc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyisoqmr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsokhxm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnoefvq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzbxuhl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qochiznb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmyqxxa.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqshjlfu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrextfur.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2corpnwxf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxofsuia.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwgifao.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxwmofl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2toypuvru.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbmcgek.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yeubsvus.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jjggbube.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bybymmuj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2onlpnlax.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lvagvvzg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqzjsnb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvcvhdj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hulxwamy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmggohw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbhiibm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqwsmop.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppenpldb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2knzoqqgs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvfqelp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwzdzh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyouhvj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwzllnj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uurygbta.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwviyqed.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzmzans.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfzotkw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfglmnh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgprdpui.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jocdlnbw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgllbjw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2duadzziv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrvkmnh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaeapbd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ummyvesl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizqxqup.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ljupdicf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrrbrdn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwchvqp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aeksoutd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwuysqp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoxlwku.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dudumyxu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udxhpolf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqjialc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcspuepw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhodvusz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znjwokyz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hbedkbxm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zuafnjhr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmiuwti.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zatqtxym.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwpulqn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2trbhacvi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soejmvhh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gugopgmn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfwabpw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbqilxe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhftvxiv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2owdpmzpq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwobuoi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lcafrffh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbojutn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkcmztu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfnetng.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyzxdpf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbpjjhb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fmraocgr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxeygyc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2arrkjpjd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbyqviy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqksktq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzjdzum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvpajjz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyaoeee.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiweymvy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2asrpgkjg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrwaycl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pselnhdi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoqrakx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2orhhfhyy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tjogjalu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sunolkoo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xvelkore.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhfjqfc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2floentuj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdlykhb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqmgupw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2krfaptgw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkknsxbf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhrzlds.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2aparatwg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyebiorq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnfcifk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qborpvop.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoxatyx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uwynoyvf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjzpltq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hivfjhia.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tptdqlkc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2psfbydyb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgykzaa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdtblyw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbytqsso.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2touldmde.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgxseal.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgosbqaf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2whqwltaw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nebrfqvj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2etfdpiqx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvvsvtb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqstocfv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvovdcn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfoulcw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxjlxa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmthuee.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bajndwqq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeeluvh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqglmsh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvujnsur.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2anqqstua.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2doiwddop.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yadlwpdh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhtwsxk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sxezfpqk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvaudhh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxmdiij.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlmqpvt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qyeoucgs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2drnunmuz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2szlhvwor.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aveeqodf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qriazmkq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gchkfktf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbircoz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gopgcdee.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxjvyaw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2guhqlhqg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhepamrr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jodevzml.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2trjwgmox.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhdmnix.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ontufsmc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tlktihul.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpgwhry.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eoezaaol.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iyycbgaa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2anpgqbhs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2muhrrsdf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aewbsbtc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hclqcknd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlcjeks.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrmxnhc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdudoyy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfusrvp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsahkek.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lprgxyug.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2paxdmhpa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aetnqfrd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xowyicrg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyezwecg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrcqdzc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhmkuep.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2didiwtvs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvfilrr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phxfcsnr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpeiwdb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxzkypj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oizkseyy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqbgvt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axmagsti.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qycqsiuv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njsfpseh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcajiddj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqzupkp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ziglkbvr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fanxyxxl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2meyzothu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fglbgvwu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlarwte.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtweati.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbndmrk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjsxxqp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2suxynhwv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blwaibrp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsajpko.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpcdaje.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwdenlv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbglrdjb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlirbfb.html


<!-- 参考信息 -->