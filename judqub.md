代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwchofo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2saermxss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2imwmfrkj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2orazzubi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkggznx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbujxzc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqojxqmy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoyzwxg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2njtshboy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kageihcn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mglxpuqy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2podnpnlt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2idokflze.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2myezvmam.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mssghlrj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzpqerm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzvhesr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmauokcn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvonvsn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkjqwqr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuqnrhd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2expgrhgs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kgptxgnx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhpjown.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbxzjon.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbyzmlp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwixheq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2opfyyyrp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2meairrlj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2apqhyfdx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2guxjsqjt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qozqeptz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wicvthfe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dicnbutp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfzmzlb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2flvicieu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xllgegfz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqboytva.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2amovvtym.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaukmki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fecglhlq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyyyobn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgitdpd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2shfsbtcd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2srimttvj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyqahbi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfytzivt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2khzkafdd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2esbpbzqi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cubryals.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbmfwae.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsbmtxz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2flizilcs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlfjyqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wzumilns.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyaojrn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2itleymlm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vigumuml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yymybqqz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sksndelc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyywrhin.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juxzjyqu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlajfgx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpbytuo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgxbjsx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyufgfb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pysjgcxn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbcextw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rswgyuqq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ylykqedj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyjuzro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stkvvayx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbyhvfe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arzdmfez.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vektqcnm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2czszsynv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyxgwdv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrcdemd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjihwqi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2flqisedg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iovozabw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkysqpp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgrsayn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxzrdzd.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snuorpmu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dyonpiul.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2apfjqnkl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pcademlg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfsnrok.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jnicpcec.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2karavxxe.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aydcoqme.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdbvlpe.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpeioqp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckszenxv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbgrmsk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2msyvuqlu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2clyowngt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdqdxwq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynobbcyd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoizpnd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiswpxl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nazqzwzx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2odwwcrid.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkjkgdu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfqierj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsydstp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2aibbhixp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nncigezv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzqkxp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmihldve.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkllvlyp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmsmlkz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gokkmwlg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvshcgos.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuoibin.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgaxapo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2avsknbjv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2umeusdyq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcmaiqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkkbwuw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2upcavoyg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlfxznz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wosbpxya.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2omwfpwvg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwvkqw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsxvoui.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlzkkxf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzxpmbe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gjidchqb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeeibpr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2feosjpxu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uegbwsag.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixszkukc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qowgvekr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvugurk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fnojmikt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nwukslhx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dptduhpz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnuvmwb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjentba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdtkewg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejehmxve.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdkddkd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2utvffwcz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pirzmnrv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2geuoyjjg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmirlbn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fparmpsh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxrzbik.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpgxtkg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwghqnys.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qigixpao.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2usxayqgk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxmhddx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwjbyvk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jianoebh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoimtug.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhakczo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkzilrh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zztzuqbc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eosyvgur.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rriqdxcx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyemuvw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjlratk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxppwzt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2neuvfbhz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyoswqf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzpmczs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dicuwysx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nkigbxmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deesyliy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbkrucs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgyggwz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvkecaz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeybguk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjftilof.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwectmu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2znxpqtzq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2njrqgkis.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjeopsi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruahdenb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjcwhtg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mlecobhm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weclixru.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsfpkml.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2trgvemsj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovehapdh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzdzbqf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqkuwum.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rysbudmn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2awhrrkpz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feyfgkly.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpfsrpn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2psgjucoq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xqseruch.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2egmmwpnj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxdyoct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjoewep.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmcofpl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrrysjr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhphams.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ardaarfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snfivkvj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkhgnfd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfnfilf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yuahopod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfwnojt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2auyouufi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yellpmqf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gurovhbe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjnotgf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuewccm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoiahfo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bokedpjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxmixvs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkxycpx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pntncbhg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ccigpolx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqoybcs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjkgfrx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2trmdduhx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbdlazz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrkfqrp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ccblfjgl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcvpdgf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2okosdsyd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpktwgcg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2upsapkxk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwodcys.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkroqkb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2htabaorf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xphauaoc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbtszmj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmvoqjh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2geatfrsh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2phyewcre.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyzrdwq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmrwyud.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoecqyp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiznoan.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpwpayi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hknyksha.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjsxcbt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwqstaa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsknaizt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxmrpwv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2otuajxwy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmvpqwu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hejfmmyc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdpsvya.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pndsdyxo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmhhuru.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lljarhnj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnzqnqz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2akexoziw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwydbny.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2anyjhrho.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsntqsn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pddnmpsg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dbudycmu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjyynqf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaszmsu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2optkqbdw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocafpqxz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxrqota.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cyossigs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rveumpml.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdkvvsf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrbyqoh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfikloh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmypuqc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqclcvzr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrsegmx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkhbmms.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxazixhp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzinyoe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzotmnt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txbugbvv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2huogtmqt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sddgskac.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aduqraym.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2adsjqade.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlbhbud.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcafqnue.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2anejctsz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqrluti.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifakirig.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlolzohv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kazowmjz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yesnawze.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hslirgpz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqbkyak.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asgvfxah.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2npngpbwz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efamohzh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoebmxu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmttaced.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvcofgh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsbzvpf.html


<!-- 参考信息 -->