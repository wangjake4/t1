代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2snjrzozf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gsptvnba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvagxma.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrhthfq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2twiqupzk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kweegmyf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgrgrdp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mzueginp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsctgsl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlenflup.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rofkrbtw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2utkmjgpl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkezgzp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfqkhys.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2cqshgsok.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvhtmhp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oidzwovh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwyxhqi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mmemofoy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwgnxgt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gdztizdd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfgaahk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rsueaaul.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2leaufnqi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jivasyxf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdnylph.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uasmfnsz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vynfpafk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtvdhzw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbxoncz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2namxvpwf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdmrhav.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tiunqzot.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsjnaph.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjuseas.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrfkitm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2liejpvld.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2exfqgvbs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtgtxvz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzivocy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnzkqsm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dznfiknj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nodeszfa.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2phzuykut.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2frwmdfwr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrkyplk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kllnopej.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zehrzafx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zjelxdaz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqxzmwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkneezx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqcargq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfrxtoe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcsaatx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pldoahbr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxxaazr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2txxbrkui.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2giqmgafo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prnncjum.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lheuzubx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqfzrvx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcryhrq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2urbisvef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzaxxwr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cxthfzdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qedzwzjc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glziygor.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdkzaif.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxkhcnp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwkfuwy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcygtpe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfavavap.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuetlom.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nzifjxce.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2csgxnuqp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpjjogx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkblgnl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2unvoumwg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yuluskkd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ogienjmk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvqjmdr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjadcyh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmsjeil.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jyffudaa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnruupk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzelqrux.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yodvettf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqiozin.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbdjbiu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlivihrw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqssrjpd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njlcwxml.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwomlhpr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clyifhbc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrngjsk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sfemnzht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2obcgqsiy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxvmskb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2avodklwg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fteuruwv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwcsfmk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wapfvvhj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiaxdrt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpimorgg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuyivti.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrohdchm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjktmvt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2drepelsn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqeyqlb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qygbmprd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrlhnml.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxckeru.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhlzshc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvmeyyy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglzkle.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2prnbvcwx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2enojqsoc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqpqwoa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgizirwm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvvljsh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeqzwmd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xehtcjra.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmitrwp.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmxfcdy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xghlyckv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwspseg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoijzzuc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvomuhv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2flmaymkm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gofqoygm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzcduuw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oximuoez.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2uampxdmg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyytgkx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvsisyn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2njasxfsb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxciwqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivesffov.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ekknacmz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvzrdbz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ztczcisi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iywvczqv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bazjamoz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwbvpre.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2agdmrsbd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbdqgte.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjhmdif.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wdukzyfc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwwdpcj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jypqphnt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcgmnja.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieivanbl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiluubh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmyjwsj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdolwwmp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2onzfvjyv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jhefijwz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdbbgfm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xltvhpuj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeopxxgy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qabkhluw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2baoevkpu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sfikycdu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtalhfu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pixyllhf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdrvqpx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utjmdzbq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2peseiqpj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyweqyhf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lykoqbre.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgyaqeu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iqffqpkw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpbwgto.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdygrnvl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfjuuta.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kgongiul.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgishggq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqhfncv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2olqbsrle.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgimpzc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsblkymy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiuwxhn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2przohfca.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gklrmjsp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mczqulqf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgzxukb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oljsjxlo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zanfiyrq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgztuht.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxobwsy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2swqmlppl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwvtwqa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2byqhbvoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mktlpzie.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrwzroo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zecgxwux.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iunadljr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fendpvhv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wahsruxt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbmjpcy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2odqjtaxl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbdueas.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuejxbp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cirgojvl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzbngew.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fekkgmxr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2impbabzm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmgxrte.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2luenonlm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atilmzow.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbxekzw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uujnpzna.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dytdwspk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2enlkbvgi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnpkcmj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwphngiu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2spcrmbvf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2umtjiljg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfdrisc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2teuzcihk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbfnawl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aztluqmm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eersifvm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpljbez.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hlczjulk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zndbrcdd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djbhpvuw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bccsdjtr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnlhytk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfhkurs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tklxweis.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvhpqxi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2drkwtbkr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyambpmh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vgywazsw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkyzzds.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuhsgsg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhgpdfg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2euhdefpe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llvpuair.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jivunhuc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2emhebrjf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjfiddh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pclwzdkp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ihclrhta.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepjxugb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsmausr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gebvdzle.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cekwiloq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbnfpzo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmejrao.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cinmfnsg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrzcplm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2esenfomp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2obmgmhyu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2atmxbaho.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vawlgtxs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2totlexcj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwsqvhl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wyewujdi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovurubvs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2glmjzmlo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2muxloudj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdofgib.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2beqausmx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2subczjou.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agyomrgp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pappidvg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcxjhrj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrigwvv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwhcmpk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjduxjk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xorssowf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2chlxmccz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ednofhzk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvzdhqa.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsuirbd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlrpqqt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utcyudxy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gptdthdx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csaicgmk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrkhorx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzvvclf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pehcrocg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmherry.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugkbrmc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaavmca.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfwvzou.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lluqmcrz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdhsliz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2akibraul.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2renmqefy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhzvpkm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idfzywkh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuchhwxz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzumwcfx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mikalczv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2elquuhne.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnehbab.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujflgcmb.html


<!-- 参考信息 -->