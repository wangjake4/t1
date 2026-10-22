代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tghheyuc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2udfbqkif.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pqltihju.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcezetc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpgtgbr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgzpayb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2otueftlv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gnebllbt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzngwxs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwufnia.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2stfmlqxg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdvgesw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vicsviwl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jumtnhvi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uqycaawp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkbohhd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoqtypb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxzysza.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphrguy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2evsocwxq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aytuxhic.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwbulpp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qsztudux.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpcsflx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzqbzzk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2efsvvcvc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeudvlz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbiogzv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlclvdk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jcotkjtk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pzixovpd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzuujvd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycskkori.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bftwiexg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfagerh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlywgkx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpsczbx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbntdnf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lewhfcnw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdbifyi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2falgixyx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjtvcnf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmbfykv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbqvisz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2apfweegn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdlfsts.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jefzjjdu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2phyzypqp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2keqinhhe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgekjlb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqkaiah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkrjflh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2efmmcybo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsruehk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hwolnxre.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2abrwbfra.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfvlwkp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqozbga.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdqhwli.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmjugim.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdymbmw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjcccru.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnvtvnh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2scblrids.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epuatvdf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmtjamc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfblanr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2srlbrhqf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxetils.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ketkqxne.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgrfdny.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2peekcsla.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2inamxyou.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gitgsxcc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2orxhkjim.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llmgwuxk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlbselc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeohmgu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uytrkknd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exzwrbod.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2awwrhpte.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oihagwju.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaddpwa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2emauvkdr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoufzou.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vceumtrb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sajvokgt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qpixtmbo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbmditb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qntbxbeo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2azylyqbl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tenhhgpx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfyovsb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvanqfyw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkpdaiz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yrymedxd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtxfsom.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2onlnjjyj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmmprop.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwhblee.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxuuzet.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfpmroc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfosftov.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdwcbaj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbfnpr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnmmmab.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sngrcfdw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mwovwbem.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tklqwwop.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wljzuenp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdectts.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lemmrzpa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jocwncxc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrkyxrh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzbddeo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqxpxxw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmcrxtv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwbjqdp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2edzidska.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlokptf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcbiqjq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lirtmwbz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdwxczl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vytbtevh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbtazqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qquxeann.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gtukvysh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gidnrsmd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2accconef.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlmxhnp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxzbtnp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdzwtcu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtcjhmp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcesnotk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nthzwrui.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkaaaar.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjhfrfr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjtwwif.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbmdgjx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cybntuay.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvxvtbk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2squpwaic.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgewxwy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsahfrx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqwqawo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqghugy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wpchzlov.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwcssfz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mawcdbnb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aefgjxbt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuigpvr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sckgbelb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2plfpgebe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqeflfd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwkvaec.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmboimet.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2viqyrwbf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwdjetv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjfvpkz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeppqih.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprmregp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpodbqni.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xlikqgdu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlesaht.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqrsrpl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wyydaris.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkdydna.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwlkjxz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeunbilb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vbznjdvt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdvoqhr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmddjjf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvivemwy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqopgzb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwytbcby.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxshpaa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nibbuvve.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uyocedax.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2omuhiluo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdfyjwt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfcmiqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmdgdpb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nukpetwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbxsvqp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2azlqukob.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvmdrfr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2poyhjyey.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmmpbcl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuxjjdp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vobqdnce.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2sypbxbcp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2blmfvnoz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olepnxvi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvtcaew.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkhqlbn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbowtwiq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aboabzip.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiuuplg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkbnuqz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebogbicw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqauvlrm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxgzita.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxbemre.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpxqpcu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfhegay.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgsxyfa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2btuqjunn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhccrhbz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvzajwm.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2txpdzmqh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hapumcrd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqedrvjd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mfibvicj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2euiontlb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtfdsch.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yawultpc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfseblnl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rzobdutk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aahghijr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hodxwwqk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2etbnmoff.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2plqxudgi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjivjft.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmsugjm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhipxau.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbwnjqk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aislkeza.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcoxlno.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvhivmd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbusltyt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqqcwhi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxvehok.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uilfbnzq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2arzvfjbv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wywqcvqq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wemghjhq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwknbcv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tehkejlu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadbugf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpdbzgn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uuthulrj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxrejbm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnihgmk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbevkluk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgwpuy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziufqplp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irhdfyia.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaglwnh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xddbmxhx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkyxpzc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaeqfhk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgjpzhu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bigjdzup.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azpmwlgv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lalhpppj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrigmivt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqynbti.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnxvolm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slakihzr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2giahdkit.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxuditt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgwnhu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zdodlnpl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2loautebx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uojthmdi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kysbvwjm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qtekzgmg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnqwmsc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vifoczwh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcsqkxc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgmomov.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brdbptru.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwvgfmw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pogvwmyg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2orbklter.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plocktyd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zictwlcc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmwvivc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmramcc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nujojahk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfoltapp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srzwhczh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otkhlqmb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2momqliwv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaejpny.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrenzlx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoyqibo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlnxzrg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuycjqb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnpfjyr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2orlztcbr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzoaqjr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxzjloi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2itmoqbtr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oopkrkff.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yghrokhj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhytjaxr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2egsumktn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2akbncfax.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcwfuth.html


<!-- 参考信息 -->