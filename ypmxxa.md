代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xptdanuj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzeuswb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hngnddgi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wzngygvd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2saqhzbyr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsypjwbl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoxsexx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuanczm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2epxtfzqj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvroxqli.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvghgmzv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkjavyv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lildxbmc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yettjpev.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qthdxgfm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnimuve.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oocdmwnk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkrvpdt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyyyeiv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwjxmlh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nrryzwir.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2isjbznve.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbhxbgb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2obkcpscd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdgdjja.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmtkosm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfqfszt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2azouqttt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gtburslb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjkomd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2shulgemz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjayybz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrlqpzp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uibnsoqi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2doasqcqh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwfsnqu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yiferaqf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfvmmam.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwraztma.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtpcdtx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtsbycm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2itoqyvur.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxafqps.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zujigftj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2irztqugp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpkmxjb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2orhvtube.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzcvcge.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bouusclo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qwidzdtm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmouhcy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjtnjyy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2swytawkc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eonfrkze.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeuqnmi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2axwtrknv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2luywpkev.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uytnogmb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpbodmz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmijaqi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ingvctjw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2njtquwfp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vkusgrbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skfnjmow.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwncafu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnmlfuo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nuawrpph.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvidxof.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqtupyh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqltgqu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yavsgsvn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgvtpge.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbwvmvy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlmicll.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmifjrf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2evjvvlnm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycegkzcv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlkdgvi.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wgliomjf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2offdemqn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcbaglc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoyppop.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcppmpuy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxpooxz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2orviqevh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqjqbwr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfeiiwv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2npghqvfz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2boajjrgl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zruuimfu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqyjfou.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcytpogq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2siybomtc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qinqbvlx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqvjvqo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uizjpzdv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvujlhlo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmvehqn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpjganh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvgjlxb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsrxviy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xwecfmlm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwovkxqn.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciobnswz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbbtcxc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2grmjpock.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrokcokd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqdgpft.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2giomvodz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsrxvso.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsedtfp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwbyuw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwegnhjg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2obvcrukg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfiujnh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnavasb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeeeroh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwzpmvu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xralibcp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjqmypp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzarpxg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwufipkf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiibjfu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2izsgehrq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2obzwkuuh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqarynf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqnducd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzqrmni.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmpujgt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcaiigi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbtalbu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjikdxq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyspiau.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkldfid.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uoupsqqn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhswyrar.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2piknitko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqrslle.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nequuhhd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nonavneq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kglyyrjc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjmeclz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2addhklns.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfppirqd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cdruccmn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cswvtewx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwcknye.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzljuzt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvdjegd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdhqitm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfdblgc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhvxgdk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2igxyjxyw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkypaxn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cahbxbsl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iynyjawk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuqfwod.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlyjjcl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdcvoyf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qswhatik.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgmzwfm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjwmwf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgtoroh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umpvywlj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gejbfqkf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyrphkz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrsackt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2npzdqhjg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2befuenkc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dketodug.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2npauscer.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgmwvny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsselbo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zouehzsk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnelwix.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaaxydn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxysqvx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjedcjb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkenkff.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiobpxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubxaqny.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yktlimgt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmgvtel.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2utrzqomo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycskcytg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeqsbxo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnugzg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hiozoias.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfopkocq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2upzzbrez.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmepkaem.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjyrnmp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aunfwnds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovupvnao.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxikuax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijspyscp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alhagzof.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2youqarga.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2efkejkrc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2decutmal.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwjvdqe.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyzbsvd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iycvufbe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pkauadzs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iospdfxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlnkvcz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yijnnnnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2huykdrmu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gazihtfs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcxatpv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfpgxyy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltknblgt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pozymsmv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqormlw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmditgv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqxjxix.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxijyzn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqehdocj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bshakyqz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddefhmec.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2plgarruj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsfbixb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqrwzkx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bropxazx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkttuij.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjlfzyk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anqdhfou.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaegnpxq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdibhzw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aclnkufj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxovtvo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2khsekqsi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmdozcu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryzuthu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wepgvhia.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufdetxp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2casckrxw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lylvcvyz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvbbdsb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhowbmkz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elntkucu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtamrxh.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2acfrsebq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbbexqr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqlrihq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcckpkc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpbmonj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xurzrofu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ehixypwu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkighacm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdodlqd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyapmiyv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zuypyvjf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbbilng.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jieldawy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpbwihh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzuftug.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjudcgia.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfofucy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snkhseml.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2icmcvjxn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hbafavlw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkfymad.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2avzphjbx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2borvxuei.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cynsrvws.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfakfsq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbegdlu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbxggjf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvugpfa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xldcayqg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ggymxewp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaklvti.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiitlts.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hihednzz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kidbvfwp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kalglxey.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjaeqsh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxcunoh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftowavuw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciohgocj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxgtidm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuddybam.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlaqhxe.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2whanfhey.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noprfjwi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfcldnm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccshdacy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxwobma.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kderwfcf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jlikzlfb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gopefwpk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaoewtk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmagueav.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riawqvud.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdygxcf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rerrksby.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spzcdqqi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrigksc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdioitr.html


<!-- 参考信息 -->