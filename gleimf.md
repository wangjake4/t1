代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xmagnevq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ponlyjna.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtwvnnj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2suwtiqsw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyhuheu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsarrxjg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxgbxpj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbtoqmi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2llpumxyl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbgjebe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcoaqxy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tnduymcg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2grpkvvxq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogprxdjd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbzfhju.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzpbhmj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pwznblbs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2znpjrgsw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlddkvd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zowkfrbt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kobthqis.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mngpbuii.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rutxnnkp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlrdwqq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwexalc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmaxlth.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqthelb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnlbatt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwsjufi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2knzukzzr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cgczsbbk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2krsrrcsn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rtodenfg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2icpxrjnz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ratpirhe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kprggwus.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhcglgl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xszaywhg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzeipzk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swtinxdv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrvuuvq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2otlwugqk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqtgjkl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoipomy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaaletg.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdcxrtx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdnwvik.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2haodfzek.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruirnfsj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmcwmbk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhloaga.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzsgpbq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2elqmjmzs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzzjznp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyygxmn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnmqulx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbeozow.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtexpbf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnmesra.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhmwzgl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2geluisje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxjijof.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yggnmozg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfkhktt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boezmick.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oedfgbog.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjldithx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjhmhlb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjgndin.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfzdttr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsexluoe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbpllgy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhvkxje.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxssfkc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhtxfco.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeblduo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2czzvhdzl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uycavicg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbpbqpf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvjrrpd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvobpxk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxqbksc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fihlbubj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glfnnsgp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfhnabi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfastazj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgsipxj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbwhthb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sctjczvz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwjxaau.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2okyhbgfo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qusuobkr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bksxfyjq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sshdegrs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrtjxsd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqdwsvy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdozhhgx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iknequik.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhokkypo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idammtte.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwerblh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkkdvgj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kronfbky.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmlcypo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqlckmg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bvabhmyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzsuvkb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjcywdd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cryihuzx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwrbots.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gylpwnwn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2usnpitpe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvsenbh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfcjtwx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxvqruz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tlveuuvl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vauacfqn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2udjmzswb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhcmngg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gschiwgu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgkmoam.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phxjnwzt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmexlsvu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uybghyqa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oemcakno.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdjsfne.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkkyguh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejluiznj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ysizsjxz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxzogjb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqejevlc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbkdcyz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zkynsgoh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgtrrwn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvycbwd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjfimwv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnfnsef.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfaodrwe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxmvuge.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljusoste.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2smqpwwfx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2akzvxwsa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiorxfc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcsaiya.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avjsmudw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lkszccqu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pzprunqu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqkegjs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cccetotm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ukesrubm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpwanvc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwctlzl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbfkalu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdundbgf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wvletoew.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aondxmwj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2otavilxr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlqedte.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjdselm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npckjaiv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2czkhjcpx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zncoqcio.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fggsicoy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwydnvm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsoykgh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjixsnn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2baobhlep.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2djkxaaue.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gohmbllu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiurgko.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqfivsd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjeysmz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peqnoinr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlvbkgc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rijbzyzc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdwjkgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2orqsibpk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2glhcuqcr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlvnynk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2myvxrfpz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbywvwab.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbewzit.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtxlxrh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fehfgzpa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2duwpnijs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzgkvdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nquubzdb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ustgypbd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvaywpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wushuxzx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvddhaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhegydhs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2idjdvkog.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aglxzhfo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjhdmsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjwmffw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsvhmsc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kphrvosw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsmyyiz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbdvrdo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqfimsu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2einuncge.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfpnhvk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfmnpb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xtshnykw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdatphyr.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vandbzeo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oepkpkhw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2covtbdlh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxpjwfy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxasxhpc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpjvcpd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yifyzknm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2odaacekm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rujpunot.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojbuaup.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkzftla.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfrldvd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjacncm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfybpqkl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yimuyoyr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdveysfy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psapbijz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhzcmun.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlsiluv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vongrgcw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qembmegj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqfizab.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2svzstegg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxljsoz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmakjyk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbahodb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alsynpcz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oalpqiuc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuwdptv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htmcgmie.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uothpbls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaiilhc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfjftko.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2efydxlfi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qaetphid.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgrljvl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxasxgd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzpyvcs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2umlbefbo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxpnlti.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrgkdl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbnsbzk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlytpwg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wazkgjqy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wkevrkzj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eooedfwq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2enwgriki.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhrqght.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpjugwv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nzulbcqd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbijilp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cohesnxf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlbbggw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxaeuqm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlvgdmf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyaqydh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2erjskgsc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvnhapu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxfbsba.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjiqwzy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dpktsukc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qobrokfw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhkhndj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vinylowx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2blphigdu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvrsoyh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsdiwnk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yumegpxz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ystazohe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfvwnlg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2marikacn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjybnfr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwtpry.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arwwgvsa.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rztkrniz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdszpvm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzefugl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lusscdgp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnxrjkb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwgohkg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2guanzjkl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2elbrmzdb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeeffkt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhuviuq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gspjwbfl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lknsewve.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzzftiu.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2egrtrcsw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qltnspzr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxjewkt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2woueebaa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnzzbmg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xipewrxo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cghyfyqd.html


<!-- 参考信息 -->