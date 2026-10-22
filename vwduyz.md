代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxahukp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfiyveg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvhuhxc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbfwauf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkkifgx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsutvres.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvkednu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjvoagm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdpcwbp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnjltvx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvexzcnc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmgvgkb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pffarolx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsagwhj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xredxfse.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfusamu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdcpgat.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urnhcexf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvizvex.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2douxnrxv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrbswfb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqogxnx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pecbtilw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gjheyxuq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjucyrz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mocwpeqn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pktwhhic.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yklwgmja.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejpuxa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgnxjyl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2axylslrb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvmapva.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hifegwla.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itmuvrux.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsgrqon.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcbljsb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2okwfnwgj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzushju.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtntjti.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wukchckq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwjaabk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2anectkch.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2skfoturo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqarpvo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zuagsgmt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2caoexypk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmrwzms.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kluivoao.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjlpqjk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqckkoe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnobalo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvimejq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxwpfuh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2letsvvef.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzakaxj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpbkwwi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wztkzqld.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2htluaprs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpejgscv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tnthfdzw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxcmsfh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avnaropn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fcafnqpd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cljwiefb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2krjcaaxo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaysyho.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeizqjd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjlgzyk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmewdnlz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jucswibk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2upglixfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snfflryh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmhdshs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwcekob.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfyiwhn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2krsczfyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2belrdcdt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbabtap.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqokborv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeddvqq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyprwqi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2emznyzxs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwubxsw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bkflnnni.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskelmvx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhkkpwv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bloieqcj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2spkiwhid.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrvydgo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxpbnyp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vottgunl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvtmfrl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gaefvtjb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ecezvcuz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxmrdpg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brccumjl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlccooy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2emzbrjzd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2louereru.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fldqhyiy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2irkpvphu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlkanve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gipmcolj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2phjgwzxf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxghqyi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxfrhio.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nleizqyn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhgeswu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qawyhowe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrkcqlt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmejpmua.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huoeilqe.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdajdze.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2huxbarvb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhasuvmt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jenkykxs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwvegfh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mifjofxd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2npwxbxqx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wiklsurx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxiuvmv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcgteex.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiftycw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2orfkjnzv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bycynsob.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqzhieh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2axjznrua.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzkptgz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxfsiaf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqrjsr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dykjvbuy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yktlsoak.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lybrwpcy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrypfbh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoawnxg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcprisj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkvrcry.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyrqznh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2upiyehww.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjhwydg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcqgufj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvohxyyt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdzhhyh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fccetpam.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhrrpjt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzmkhtj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyrshwd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwcnjfv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcttdwe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuklige.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrcyipv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2etqkdohf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qezpoyyw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjozphxs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjpdcvo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qccvvyhm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2szstdmdw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zabkdgix.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnbpdbk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbajwdja.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhjtrdg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gigtznsf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jljpqgal.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2klhhiudg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2catrytyu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2csoebmkv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xghehydk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyuqcyg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ckospbok.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtgdfgk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ludtetoy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlthgnbw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2worforks.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnefqrom.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdewkqg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbpalqx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqitdqqr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bthnqywc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyxocgh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zauasdvc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmdnxjo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hamwytyt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mnougvjn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpofans.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jigdvark.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkevroh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrdurmy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ngltkiof.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2krfbikid.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpvjifd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2emxccxve.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2duriuwfn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irwbbbqt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaznhvo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wztkukxa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxsnnqv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcqzynt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eurusgbs.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqdpabu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsfwnxi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbtvnlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrgbkxs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpnhsxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irijdibc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfespmd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyhulcy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kahyryta.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fruxpoec.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cubzsljf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgotuxg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fymkxbev.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2snllkdmy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdgchgz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mhodfppx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ydllwqjn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlblddme.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uummosvo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuhtlmh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcakird.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2azznfisw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hngnumjz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnadmkgq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uofadgtt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2texbhkae.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jgexmrln.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvatywr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgnwnsf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubflmnho.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2leitbgqd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjyfwal.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ijljdayf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwphkuuh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcertld.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjkyzlg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syiaoiok.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aualiggx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jzopyode.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eiizuqpa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2beysudiw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsckbzo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2crtngqon.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qywwdeoo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hucnfdnr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxctwbn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjgzhcr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcuyubs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvmfglh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqfcvcs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnplebt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyvvdte.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qxapauir.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2whjscypi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cpopfkjn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyzoncr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qtocwlhq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dehftxxy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2peqmbmaf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdxjchp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icypulgu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gictvbil.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hadmzwuj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepfyjax.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtjcllh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxcpfyx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tuukueav.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkepokmy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyyqpfx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2plhkcdyb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2poxvweaq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdiphvr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmhqvaf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2clweyafw.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaeibeb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxnrybo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vforbpzz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdafhfi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iadmrqxg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2opynobpp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fostdgnf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkpyxho.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pyamazaa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmgfmpr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2siuxfnuc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2axnvcwuj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhfspdt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhyrazo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2obsfvcka.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkwuamv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcrnfqy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rksbkcqd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlgpztb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbekvpix.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrqvocg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopairsx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2snzkawpq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpvtkft.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2djftcsvq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtnruhs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zafjbjla.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2odmftkpz.html


<!-- 参考信息 -->