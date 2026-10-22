代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcqbahn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiltbnm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfisxdim.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzvvugy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjjwlrc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxwzjbn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2micxiufj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mkigrxqx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2telmrwxw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlphjlqc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zbztuwjo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxfveqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vkujgmcb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nouvdwee.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqfmhbs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vmammhau.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2axmekukc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhiqhcl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2quvawtua.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gzryxfqc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jiogsboo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsvhktt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vphjvipm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2inwefsfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtlfgom.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmrfmsf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nldolcrz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bniswvgu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bswlmdbz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsykzuo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dddpmael.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kykcynse.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxxxcdw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2juiqmyaq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjusklts.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzfxbfw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyuembc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmxgdh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2avzhcmhv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fobqqopv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kcelxdjd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbzumym.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcnxfye.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2guckemjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjluragm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxirnio.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvbnwvm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tetgbbea.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cezdedna.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvsclkj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtanvq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfybkps.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2adjobjpf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxlfwlg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yiophirk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gafszunv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxijeuy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnphxj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vseldkgx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zemqhlwa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfntbip.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uqekqdkr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvwhaka.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzrzgwl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urdvxvsl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zjagjcof.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxhdhxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2essmxsvr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqxkavz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrjmvgf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2firvhopg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xayuchvb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iatfijez.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hioqxjqv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmstoks.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhowcdvx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqrrxpx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mwesdpnr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqyejkv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khecpose.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmajnekw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2equilpbb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kngzrkca.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyugwwp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2smkhnkfi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dtchkdzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsunous.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gwllfcsa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfxvktn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zuormmvy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgczgxki.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvbwoxn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhihgmzx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rijarami.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpsymyv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsywpgn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcumjuw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqhtikx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2egqcexjk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zylbppns.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnachxiv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbtdsqd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jupioaju.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqjcoek.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bswvlify.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsxenme.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbvmlbk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmyplbd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoqfofb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfwdciy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2egqyazpx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjtmnxy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnswpvs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnejdzi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmyjdry.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeivcaz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2taazcppb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmylrat.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2imcjbeyh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2poccqrqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtnduxb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zghaorqs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kakgwlrr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgvlbpf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgxuvwz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqxouwr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrddtuty.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyogpwde.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2krunaunt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2keqirifp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqocjfkt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgjlpsi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2roojuool.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbcbvxu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oydcphnz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kapnzlyt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jjusdrzw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbirniw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlxjqxa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dypqfoyg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ornwqlfz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wionnibf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2deziuopw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmevwynz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvgxook.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnikjndg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wgddjcde.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhcgmwf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaauemz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2picgsidk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewykkxdg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqxiczq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xlspdrjb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2erwxgmov.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uznvlvvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqtscxy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqilqvp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbijupzl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwzikmm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwosbos.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaxbpzp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cflwcjxm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvendcy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efwhzlsx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgqnhpt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nobpvcna.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2teyilcfz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofrmyza.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkneerw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcapckvp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkxrswc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfywnmi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rncxzrtg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzshkiml.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbqfvbb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbotesh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bicbwuiz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bplxfemv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrtzrfr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrdjsgo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kckiunlf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2utfwxhoa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sodiwvbg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxhfjzu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfogdglf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eyycikpu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbpapqi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxkirmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcshhng.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkedyav.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rguhxopg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhihgno.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2okngkrej.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gnszbsbw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlofrem.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgnokez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2frviwqcu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztejtbrg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkhbdbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exujmvtn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yghfnhsm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbrktby.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyrdwlc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrsavsv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wloxcxkq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdafilce.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdxaeae.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yppvjuwf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mpetsbyp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeychgd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2norjapvs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqmlngd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqazteve.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijewaheo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiuwzsd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyckzky.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyvbsjb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2boniekws.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjrusvi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaxepbr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvicneb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxymnhsm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jdinryhg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxftkhcb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpdypuc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyxonbb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2efbqrpyn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwhmtle.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpyepzh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxnweyl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qevrtcpx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rllfzeed.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlzsvxz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtdwocd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtrfqma.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqznhyz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qemmtzfx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2glvwcnaq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjdtvvb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvblpen.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwwodjn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hflbfnkb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwtagvq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbrnoyl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iutxpdzp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2onifzhfd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdaugcn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxkftym.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwkeorj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2woxrhdgt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wljmcrem.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gndezzcj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2arkdmxfl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbjxkig.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tabelomj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnpzfaq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkbnvpb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlppapdj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2peltjzgi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdixlsb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrqthbn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgrriao.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwewrgnf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2djgoimhg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpwjahe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bprnjyfc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2olszhfxa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2etpkbjko.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vycbxzbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbupsdc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oifywsos.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrehpjd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpqexbj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrpnbbm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pobhciyr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lctukvox.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nylzfkae.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghemmipi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2luszqrrl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnjpijn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfynok.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkjyqva.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjbhzuh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsjrrrv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2reupephh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mphpmowu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqejfir.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjlxbtj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoldzao.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvojtgd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxcnhxq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwcnjal.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjjhaja.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkejcbm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmswbhvy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuxbicv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeqrxfx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2givipfci.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoiiwvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsanwdxg.html


<!-- 参考信息 -->