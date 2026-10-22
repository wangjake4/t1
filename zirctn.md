代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bawdsrqg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yqljrjft.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2txkmcqlz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zvacoiky.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jvegjtkr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzisofkp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbqdfgo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bjterodi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vxscijau.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsxoxdg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2takrnzog.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwqhnpm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oolxvgzg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfjoxha.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2niumowbz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmdsgnn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnlawss.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2orwclfwl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtaayom.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzwfliu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2solxboru.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcguowpl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ilagbdjk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlnegxw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlksxjo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qntkgccq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtsmgbb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvytezao.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iamwsxid.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrsgzal.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnezyqk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiedgng.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcqisjl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2umgsxpdi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2esislqen.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvxvosu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmnypvk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lfweneho.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzfkknn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzxpokk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uudxvoqc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vgctysax.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxkwusc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeylhso.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjikxdc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vtodbujr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrtczuz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wduovlos.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrdnzrc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kierjuht.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2glhaneud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2catsvsnc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgxmdos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epcbjcyl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apueuxjv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dfunhxyl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvgckwv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2otxqivqc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtpaczf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yejgxwjl.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmikyalb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlfyjnd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2byefytcp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbaxknc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkongxm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbqxmwd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2faqvyjnm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuhmlux.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2veamcrhy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lixmyixq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuwvcvj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lbszhids.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2givfvntm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2spjwoqzj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnepnum.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwkqgji.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2psnixbws.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqowwkvn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwuxcce.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kggacgfj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcevjpb.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hraorlwr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjktbiw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjgqmwt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bipbmerz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2izcwrunp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2clhekran.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrvlvfh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2poroyiiw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbewqfzb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgfcvxc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyacfnd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwgdofp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvrbzbk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvizvos.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ajomyofd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnexhti.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvjzyfp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tursnqqs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrurxml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxiegrl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqivfghj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdcfvij.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eccibyja.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kziykmdk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cwveygsi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2makedike.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kfryitmu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzgehnw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiipsqe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrznbbm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpchryd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaoabrs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhqykua.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2awlrphxy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgsdccw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oopeqamy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zffculcb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvvleco.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emljwjmi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bxspihkm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywboarxg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aahvgfqf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2adygzlns.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqddubt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywdhfsh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvlxzui.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqylsrzx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qllsuuxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2apbulyzi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kubaowju.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xskrrshi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yoemihmv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2liecgzbr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2btdosefj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kwixstdb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dumjbaor.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nihrwngs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgogbhg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2amlhtgot.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slgxblrz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrorncp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzimafzs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2logqcukt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrrcowe.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2egiywapi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2euzlzqon.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrsaojw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2brzkspop.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopzwcp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrxhvav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qostqynu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2itorizkt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afiuxyvg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oazazrfu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrphxlc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eskrtjqh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vntdsrhb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrfuwgo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqocxcp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2crklcajq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlddjun.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxejmod.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dckxzwdf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqznnckd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmfirds.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvbvvqt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgybbcr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcqojep.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fskumloa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsokfvv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqjgkhs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnetzkn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcufsla.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lemyngmg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtcsloq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfmzkpz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cssupqkg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbclcuyx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nqskomwz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmmejey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrrytlc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvndjkkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2edrrzmsk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epunmtow.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwelesaf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lryitoou.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oskmdiuc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iouhgdqx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjqbagb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzponpu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bknjlesg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvnewru.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpyfwyj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zuovyilr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjswuux.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2swjwstdq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tygolkoa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcdxpop.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnclrxx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdzdtrz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2txmxqolt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2megqefua.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lydgcppo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtwpxru.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpezfxas.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eyytiabq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edkzzipb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2udwxrfxj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wirpulzy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oquhicii.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uztufatj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiqagmg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2anvklhrc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2henqbqmj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqqyypr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2snwpgtnw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2reywodxf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2meftuoew.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2azixrmst.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qegtkcep.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wryexjiu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2segcgabr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qocwrpwc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qifwotuk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qglbmjdv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aiutozll.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fglcgubz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjskmwxb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnncuyi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfkmuea.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zskdzkgc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmgdxee.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wghdvsdb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qugilses.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsrcele.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nglzzysx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpgztbh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vjifdfaa.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2thewtice.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2diavuemz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdspxho.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kiitqbqc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfbxpue.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbprrsj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdppiqvl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obtavbiq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rsopkgvr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjlshxt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqiojt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kznrkbcr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkmvcta.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bnscntms.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eorsukyk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlljacnb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2etxrbofj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2odsovrzt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2agmdbekf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hinapbsz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2olhyfrzu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmrabiy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgyreuk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jrczvuqo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2caoydvfl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ujktmeiv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2agwofzef.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrmmeth.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlqpslp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afklalvh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfgcqtm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxokcisv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlmahtf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kqochqjf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggnmiy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcuronw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbtwfma.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdwdftg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobcscnk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2titfzmrd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wejnsaia.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idvvyldm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eifegasw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuyeamn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiasxmh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqktzsrw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfggarq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnekawoe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqgmtrc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpsyzed.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbaipcl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvpknvs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rvflptoo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiqudpg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqnnngf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpzojlm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ximlypmd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqlskmp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2asjxbysa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fncgyzya.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lqawpjly.html


<!-- 参考信息 -->