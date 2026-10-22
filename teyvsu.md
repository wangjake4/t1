代发 wailian999

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xniyumrh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzoxkwe.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sumdcvgm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfuosbf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oibrnkde.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yketvbml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdlbugb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wabdzocf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gyuhvhnk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhbxzlx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wesarbxp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qmazegvh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kbruaajw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkltxheu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwqujzk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2afbqubts.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jomctrpr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtfphjt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ohablvtn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnuhdpj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqonads.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtjermm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ofawyuow.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdikyjm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpftjic.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqfrgab.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ceymaczf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuadkji.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykclkdvq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qslbecir.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uahvqbes.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2evuehllc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxcgkdn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrwgwt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqtgdxr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtzgxgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqtkhxi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgkgssm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fveqaqry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtrlqrl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tphdhdid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2riytxdxe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyyxila.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gchdgrlz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgtalyi.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dktlywsn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eupzwztp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2upowwalp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2miacptgs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeawrzg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iryddtlv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeaspth.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzxrxgo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjpvoce.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdtxabz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dpevfxdn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uohslwaf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsapjxh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdxsynn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2orcfeiyu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2odgknilb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dkykgrsk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsjvpid.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdgovym.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rilgmyhq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrcfzyw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlloiwe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsvtsis.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nutgqpnw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrtzmmg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2whxndepx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dgilnero.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdlbkhm.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkjsdpl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tecshnmc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxwkqji.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmqifng.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrqdjum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fohvfmsh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcguvbd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dldzkeuv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2thzaerdb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gujbrkkc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnwjslq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2obfoydtn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2crdoqzgl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2phjzlbox.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbscveh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbassub.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2awdrgibc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdztkkc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pozibqaq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qorcnblz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ykggpqqy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrbrtat.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xfemwvkp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbaxzmi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfehsxq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmcuegy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomhhvf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcucntsd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaiaptp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqelsan.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dvirqwcq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxyvrfa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxmmmsp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2klhxetuf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhseobr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2brlzlzji.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poifbvri.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfpmkqg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdhtesg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdhwmzu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbpzidz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ceveyrfq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpamahm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgxsjlz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjfsjdo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrncsgaq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfscyig.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvrzfbj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nptavijb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvekrlm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlljweg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oijtfvkq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdvffbu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtfpuvc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sklaspnj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awuxhmye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxmztip.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wynlqlol.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aguiofrx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jasgerce.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tltgkmrr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbfiopl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yujwlquy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yapcvehl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2giemadju.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpcbrov.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vscsnbxi.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrboatd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqaikic.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tarzteij.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkldcoek.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxcajmf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbxsyfy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuflwve.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hiscfbcp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xssnewlr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwnrtcz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zjitorjq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hwflaxby.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noznersa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oucijabp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqagwbsd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kytvbzfy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrgduyy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiryqch.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpzvaqn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2csogtyqj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbrxaho.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwossvkt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzquhqed.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtuticc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2asvrweyw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wljllcqh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2diknioov.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgxcdqc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fcerjnls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhnwqdm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqxvpfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swyojbiu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnejkuvt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqsalan.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdbplw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxlgtpg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qivtxgml.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtsxsly.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zfibyjtm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkytbpd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkrxsjb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hddxvttu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2txgbulpz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyjglfn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2abckhdzn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wquckxmj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2drvjapzb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnfnxdk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yielraph.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zttytyjn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zofkceof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgqgppg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxledozi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxoeprc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbanyrg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpegbce.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ygimutgr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wisnfepm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmufxuv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iawqtxmy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2cspglips.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2naafoeek.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnzfvbt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdxvitu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdesjgxs.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnkemnz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eekvfmgy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2frcpehkw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwkpeqv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cniimuvz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohachdel.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfycgikh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrqfciq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooavgmsw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaxnilf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxerrcib.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtiyydb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvyaltl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wllontjl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmafxplv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sozhuydc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvfqhio.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2txplxoof.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyizhdsq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jsktnjli.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwtuue.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uxacwgzf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nftapxlb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ydewixea.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uycrvypj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2urmanfuw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2faojciar.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzsddqa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiqeplu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsacfnd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdtnlyc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqybfnar.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yepulpqh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2htaudymd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfvznpy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hutsgmjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2srpdaigy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axzfzwbh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgeshii.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyhhuff.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpgswjo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvdctsd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zadxsivm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxwpvwc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuvlgqu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dnocnxhq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2elxcwdir.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vpybrzyg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2egubjzaw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eozgtrfr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mipgfdvz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmbibyy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhfzlca.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiqoabv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fctjtwoa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfwlxri.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imepsvjw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrrdobb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaqnpnf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmzwdyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prtvmghg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtphrnd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygovqfrm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuumvdk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hivneeyn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cidcoffg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqccxzgv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwprris.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2babrlnoc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxmnezj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gypdgvzz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tctohlwo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcxuoud.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2opccjzhh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljsxcw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcugydo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kexubtqx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pshhxgtl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpcchej.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2skptxmeu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtuifcr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2grxphhxz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqswcwms.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgybyxm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwhezei.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeeixms.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2augkuhtx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdewgeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itjwzzaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khfdjfci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nreojoly.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bavtqcbx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdlvrhn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzzjgof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrstrkk.html


<!-- 参考信息 -->