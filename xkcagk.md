代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsgjapy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrtaaih.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jckdsugc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sstlztcf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcywuei.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfarcxu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfgnbqu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwjsfbh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nhguhgpj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lpusndzm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwtlrxe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbaxehb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eafcmmnr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqitdbtz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjidogh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2szeloodf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwzzucb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeeyfjl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvsyadk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmskuiv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgeprvw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmdilly.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqnnghf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmatzgk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2feifixfl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrdzkjt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvbxrct.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2apzlgshl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzmzzll.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2npjmmlav.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfgdxnk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vcegikfg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2menjvsrw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paidwufg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qvosalpf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcrwuvc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxmfncg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2czrblkov.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zinkmebb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxeswmp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vodlzufz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xdliljgx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2levmljdl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgbybmu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tyydnzxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwryxfiu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2crfhxrli.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2latyrhek.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryttshlp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2thqoafls.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcnilwp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdrcmqn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uztiqyaz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2owiptfvu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bivptvns.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbemreyd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwshfthe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nsslggah.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpxvrga.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrkjwgw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdvaryi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ococcehz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mupieeyo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmclglo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vabtosez.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvhkuzs.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cewijqsh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgphbtr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwtblgc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmonncjl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2psgzxzde.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iblhwnaf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxilqcs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqbkebh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jluydtwz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2csdblewk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfzgjiz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2umviipmh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hplisqwr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2obsdderx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jptbkelp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqfrdlv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkdpogs.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksznjpwf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoghmcd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpaatvx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oibzsiua.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrogorb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbmuajy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zfapfhjv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgidvaaa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2engzvfcn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwwvems.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jytkmzjx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlocurxb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2attarkst.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2enuxtufe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aqljqoiu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfovtnfy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fykqesjx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wunoffvu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvypfoa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhgafim.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iibjdcup.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrnyish.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhwvapn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfounmau.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2spparwiu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xugcsvof.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wslqpfok.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoevjur.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvnzksd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2afbpyjwn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqckhgx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhcfuys.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjfqnze.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxbdgjp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbnnkul.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2voowxdjw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooizisrf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtyaolq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2synbetdn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwunwqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2spzaveng.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2injzznjd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2guhtmxrr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmxxrgv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yszonmda.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2djidfgfk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2igfdbuol.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwwkwwq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uknkpzxw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yreaanhw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkdfnxg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjknswo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2sabiwcqf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpeifsp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2atzjoeyu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrkxasp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipubkdsm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vpldusxh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwtesan.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxgedti.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtlebyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tiywnkpl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdsximc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrspnxd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsnadev.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uygxdyjn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idcffljd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljobzycb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fivtrvcd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueadmscp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdpcuzk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtzruar.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdefeok.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klbsuimq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rdotiiwj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2laotsefu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2leeahqcl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2matiydtq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtkquzo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtkdpgz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dctdfyjv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stiksvjf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkebwxhs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdeofvz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifebyiwn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxmxlbx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuadnfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaqnpua.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2embjfatc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zvftuqmv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuvgute.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2edqpqocp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqkyfqh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsezuto.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2erfujiao.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwflhu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoxgtnr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyzxckp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxdafal.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2myekygwm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozucakyk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpjzqtv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfsqyly.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rllnvrcm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irwzjoqp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ipomwkze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upbkvbqn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lagbxojh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdiirkx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhdcluk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwrlbci.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2porcffez.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2idrjfwyg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cukkdtbe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmgpyfu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbrvoin.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeqfdnv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdlcurr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjairwrz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqclkzsy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeitjbie.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uybxmdan.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxerpkn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wffamapw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjhewtc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgiovsx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzimvhgz.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tebdsduv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pexruafy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqqaput.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lunrvdpw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2slmoqxqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjsbapz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxstxbg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrktyvde.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2myvivghl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrevvzpx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqypxcdo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxxgprf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxteunk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmeiwzt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpvhebt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublgehty.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pixjefjz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogngarkt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dbckctfp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyfktjd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrscrqb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnbiswu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhijwkk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzucwtzx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2djyftfhg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2egpruhfr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpmhhlh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhfdtmk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmectsf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiirjdn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wedhljrw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zekyeknt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvxvlai.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aggjuxvo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2snjkrrsw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qshixtyo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kitgifqj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvfrztu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2usxstagz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uapybkfq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eigalfxh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrfhllf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2abavvjvh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgibwsji.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbxdau.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lbebzfhz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrlxojl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nywlksqs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kagapcuw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzgushg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnmbxqg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwnzkia.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpbdpjo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baihvyze.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfvcsmc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqnjbss.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbswrph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyadrgft.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2etmffqed.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwfysfy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvxrvgr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajibovgq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoreddl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sglfxcbv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpjcutw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhveymtz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpyvdce.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zutjjuis.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2stsppnff.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cexjknyg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bondidjb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlecbcni.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzneedd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2grgtjvbe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmbmadc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiwslws.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nthaakqc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2auzdgzpb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzkcduf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2keqvlpmo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzffxysq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hwasdnih.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwyofdh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aurwwvmk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcquloza.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoiymqc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2alqkfuza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2comnitdr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgedwhal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjogsfxx.html


<!-- 参考信息 -->