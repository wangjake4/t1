代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmgewts.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtuovqd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zvustqua.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzmwjps.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gumehilt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uabmlwis.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuqgprw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ylygiylq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxqdskq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wibwkbfe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lklgsrwu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdslufr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfedyyyk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrarxyaw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxaqdbl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2coznsqpo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsftred.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjqwefk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgdjemt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cflbwbew.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhrouak.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uuizxwpl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yagpbztp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrrmsqu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyndeau.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnytqfw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvngzntx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pdscrqvk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qorfocjx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2crhmwinl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkmdfai.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2liiaqgfe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cwubymqr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2grxakwob.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cogqhbub.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xuouufri.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cduoykrt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2daslspnn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqmzzvx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2msxfwijm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2znrgxefz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgykgni.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqiyigj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fiujdcwx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bgexkxhw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrykfwe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpeyoqe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzabcmdd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzoaykk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmcgemj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dbokrxto.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wifrbufw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsvslzp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfnkvys.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ylutwvvl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vclrdnhr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akblqers.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzhzqga.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcjdwep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbvpgio.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2scituoei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkyefrm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrhxuii.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2auludyti.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdgximn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyzyewx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyoglhq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjlrkxm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsiyzqj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tetnvqse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2afiymfju.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2boepempa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urzminua.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqhzyvr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2esntcsfb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pdycwulh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmhcddz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfrtslk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rndqzjqp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxclqfc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jyauftdh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfeplfk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cioizdqy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwpdfzh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yubimxse.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnhkyxy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2maqphpag.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kogzautz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojadyiaq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzradnt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xuorfrag.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrkfzlb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rggflvze.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2szlppouo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2axeirzxl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2isefbcrq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hydaegrf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqpgtjq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcwmwxz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fydnppfu.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2btqsfevs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eeozngez.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qykurlup.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fccjtvwc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfaswcn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qadxczyx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqohfpvs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgnhuwn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2impgjhso.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uotrqmye.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoudrhb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbvdbob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdccdvwh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nvueffyd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gudawndz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2igrjubxo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhucixeg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2afhfiwjt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcxuzkk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2erpccozx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcicaehj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pebezjer.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdqkuld.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzyegqk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fromzhrm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2htyyxbdg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfimthi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxlztbk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iatygvzp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msadhciu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffezfkvb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2farujafz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bugfnwra.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2adkowgek.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzjlqif.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjqvdvb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuaumsg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2moututor.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrrbuos.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvxowtf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxddmho.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjygdgfg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiibnug.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfifghe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxsijgb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2flkdpcxx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2umvrgvmt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2syqykiyp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcwtpyk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbijjxk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glgtxrph.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmomnelo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uxewfyon.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2srqetaxs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2egirjcac.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnxsfyv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsgzvhy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqnonjp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pufiglth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnqtind.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vajeqyqq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqmfswl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwozgftu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaogxvr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoktpam.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afgpfvvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dusievlt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yehosnab.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2koqvglnf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuyricj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xeydagiz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wshsbhxg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rixxfsjm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrfwjib.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2habrnhgz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vywjvnao.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rirtghdk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2enfzttqm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbhnowo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoixbwn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzeribu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dospqjgy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjblsnsr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwocrxx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxhqhbn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2smuruaeo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eemwyatz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2czmnvgqk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zypnxmyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puowmzvx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcwntyl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cypbokce.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoksxsm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbawmofz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiomhmd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdtqwwt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iznehqgi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2osimvhwq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqjqqpt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzivkbe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtydagc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmygzmv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qolpdhpv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svmgbnmb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jhydjgrq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgzfods.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwzimrq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbillkth.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjorkiid.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsdsvrm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2edkwcozd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vrezdoek.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2reipcbws.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wydrqlvx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwmscsl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnafdfd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhgmgmg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esrdmktd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuyaegu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vneeedmv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2azhdpnjo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvclzjgh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbyqobi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2edphdcny.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvmlgrn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdopnpum.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtezhat.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnlqtbc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rpclxhyo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzyagxt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcqraug.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomhozqf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fysavnhl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvjlbwi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hoygdexz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfujyns.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2piwfhntc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iasicwev.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnimbks.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbwcaps.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcrsptl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwcbzlw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmyknaa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcgdyyz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qbapkozz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fccxanci.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpbrelb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoisyuq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxvjdzf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeamrlc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uelnsaja.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwnpofj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plcyibrc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vygmvamt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpiytpz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhjxmbq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2woyzgyjv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxfyfhk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oizwbsbp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfwemok.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkodfum.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdhnxxj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfihaca.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vudnkozv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjlszgf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwufnefs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeddasw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vowiyqod.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2isybywlb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aftybskb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvmrhfv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjbhwfm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2facnwoun.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2khcvqyqy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktanhtqz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkoovmj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsakvbnn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwiinwy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlghbjt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwuigfv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdpghxx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sowqhzjc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrdzzcw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxrcclp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxtnedo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsnwzdm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycclzgju.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugrjjgc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjwrkcs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tworknnf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whiqijbm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdojdqe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sljemlcc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbrugfe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpqshov.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnevgmg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kzunfouu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2okwtfeno.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2woxepmyb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvjlamo.html


<!-- 参考信息 -->