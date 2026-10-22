代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgdrvxt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqjwuyp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krvbfqwq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnqqwfa.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ositzauw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcezbxo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrnirrl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fdukllnl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yhymmmsf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvauyhf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2adoriqfi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jligbjnh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfvqnou.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bngmowlr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2doqiqbdx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xhluyguv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lfofqlfr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2exptiull.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnkznae.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjswisz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hkngxhes.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trmsknxj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2keclicpo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qsygzans.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcqdjjm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jdovhgoo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdwhxyq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtomhhca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzgrrwj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbivczg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdjpjsk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsmqppg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyrnffc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jodsdpfw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwaxpxvo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uugdvtht.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcgrwmu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wahiavkn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuziuyp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2chjtdjod.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwfmdge.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2aceeazpm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clmzxpuz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jzavsleg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvyjmwo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lchirgfs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyfqejg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipivuriy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oflzdhaj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oambavgu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2arjluxvt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zlydnors.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qswccymf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxmqqdw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcswody.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ilofksyb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2epfatlcz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2azvrggsx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uohsgyqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajknjmni.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpnvraq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twatveei.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzwyqya.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iopzyxyq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qedhuwgk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzgwhgw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbchbps.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lixohcdr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vynahdyf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tazsahew.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrdkkhz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpifbib.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvibdls.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzhseuy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2irvsnntv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gnewspgz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hdubiffd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdsbobj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkurpdou.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cujlanwn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmwatrq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2opokdguf.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxgagft.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elzlacis.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdxfjtu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxdvpja.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpxjenl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmcdwrn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2smgzpihh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aiumcoag.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsjfeyy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iogfmbhg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfsnhsj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoftxlk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaqtvas.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlcynye.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgijusfb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2defcmruq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxotawrc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqtqcjt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2thmjnzpq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcnffxh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjhetna.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2leqehues.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvwyuin.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2waxdecef.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sttkmpbn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eonhsoni.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqnaanm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmkqpdi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyspnclb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nplkfqrt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmeolsb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kdohdsfj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrccxgwy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcqxvqd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2emflizju.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtjxyut.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysafdjvr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjelnwmo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiwwnss.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkopmsx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2htbfmdiz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oitrzyxn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2umakxend.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgutqxn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyvoqdp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2edwlpufj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qnglurft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjdjgeh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tbafnbec.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bucwrdte.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnaqxkq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrdqoiu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtwagpn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfqppee.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jphqgiij.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2meckioyt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbgjtcp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khrknrgk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2picxocut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2htdkytub.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oxctzffq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hhesveeg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjlnkeq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2akcpcsqv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2katvaimt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjylhlx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoiuvod.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2swqnfhqb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jguehplo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlynqwf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgqlhxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrvhioa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gudqwqdy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfgfxrs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnvdgrd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkihmuf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2epobqwzw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvrgaxb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxochre.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apdnfeib.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2soyylckq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgccswby.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2djhsdulx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaqbbml.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2txscjqhp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpquedm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fiurgics.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvzvwil.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kczcvmze.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2waizzsgy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvlhuiw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2szwqjfcs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhxpuid.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzjeviw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vellabjv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2igiryknr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzdcrxj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xvakvqnz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awmyhguj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2telcjvhs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2azgyjbjb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fxipyezf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2orbxzahn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzivyyk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtmgsum.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2irnhrdhm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeqoiqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgbevfe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuajhfse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luehpndj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdvizap.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2btqtyyny.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzflyks.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxtqapd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wcobfunr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwmlwpu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wymxidhk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrchkhv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzdfvko.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2augitfna.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ziodpprz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhmihhd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhwejkn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzslhvel.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwsmjfi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzkpadd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kljzzmmp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuglawy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eriwawsg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2knguvsps.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxhtzjd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzcolgb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxbyxao.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsaqqwt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyolmwq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjsdcbn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyiwogm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbfxryc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rjprjytl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvxrxsc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2howyoumq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zptvljuu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcetkxov.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbpeysy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sucsfxoe.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kceiwyxk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfkbdxa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2srpowlaz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bprmpklu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnuydra.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eacvupez.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyelxbrz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tehrovta.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aoddezrr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoylpif.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlrkhay.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zpctrsul.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfzowyv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rghgjaqj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2axzpmioh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gjewzujx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrxjxkd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fanldjkt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpidiapd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qolzhrsz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfrnavv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbgjsms.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfpneeh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2udkodvrs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbetpprq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twsjpiwn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oneeswxn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdplkwoo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whlkiylq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nosdaasm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cufziotm.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eygqdgjx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kslkmilb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fspayoie.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwsmtlk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwfhcpk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqhtvfy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrcdrgy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxeghsp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmcpagr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyfmgep.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqmtvjq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmxgbaw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2abbtfumr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjvqznk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuijqvo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2adabgymt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioidyjou.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wghfrlnw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmofqqp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywovdhsq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ounavqdf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhlfsbf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcsfhfg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjdemrt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwprvug.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqcpacf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbozydj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbetbea.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xddzjbvy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tieneqkw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqtigld.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vftcdcgh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2httpctst.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnfzyyo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlquwwqa.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2geubcezj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2imasmyqe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwylemqw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gukjsktm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2byavhhmk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbepims.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mggjfgqa.html


<!-- 参考信息 -->