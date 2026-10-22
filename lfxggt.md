代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vnujitqa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fthneeig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sumokmxi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lawygwbc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmqxuoh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wuktqfyy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efvwccjo.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdziloo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcxeorq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyxdxma.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhzshzm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdipzfi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrkbxer.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdzwndq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fimjhtjv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lcymmvri.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyudyxj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odobrgew.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbizkcq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzjqwhx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2esqghcng.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrxqljf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxbiczi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlxzqjp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjynhte.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uobgndus.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mjstbfdh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeuaaem.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xpohjurg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiqtjwi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzilesp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycytyaio.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bjddxpqb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwimlhzr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tmviezle.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxwrytd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zroxzatu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hfleqoxm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpfimdk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2biwkpbwq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnkxcvs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zboljsze.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzybose.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrrsjsa.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlmhmpb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnkanuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glonpyzr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlgjaqd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2etdcoetq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlnczoq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyhzssx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhbuumh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jabtichv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpjwfuh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpjjigd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rifcgxnp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fpysreys.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpfvcnf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzjyqcj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2luemvkjw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xombjeiv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjwbisp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ugspybmb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jekcimtp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2nnencpef.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2brvlvgvi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tctnfham.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmrgoyt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svfdolaq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrgsfvt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuivuen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xuglktgm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dterrsbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnydrpb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2knlgaqur.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rekmpdcp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afakfnkd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqlsyfr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkoqxhf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxglcve.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmstbwak.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmwulys.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzzacng.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sorbtbap.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyelabi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmnynlm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oepbazml.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hutgbwel.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpifprr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2appgmpxx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuyryfg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhrcecy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqdfdiw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2twccfeio.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2glnvnmdf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hirgtwnn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwccbtpu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2udwypgja.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsgwvte.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cskzsicq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2paqszpks.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyfbxtx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuztmara.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ranebanu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmpclxv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwjfhjt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kakjxcsm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvlxvts.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzodmsit.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcpnrph.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsjboem.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxepyit.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tttlcujb.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjoiruu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvngeym.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbemob.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2geltvhix.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlfnkcm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvmuuhj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrtmntc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwpguam.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzgjip.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pncnyffz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2inqnngvf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjguebl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lcddoxyu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xskmutxq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2owfacrjc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhlsfpd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cldgwhbq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcglyalw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prffwadl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfhpanw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnenjuqn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2iakuafbt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrdebrw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoklysj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbpvmfi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wydlogvm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2brrnfamq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2liidgsxr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msfhmwta.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rsslvmvm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdobhlfw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzkiozm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqdtjzk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2javdlmzx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iockgfok.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bojcwfgm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jezwujuu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhzfadw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jziukssj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mdswsfyx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qynbhtmi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eitammvp.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfprurk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bicogbmd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsnwnwh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgvcdyn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwdtwxj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eittpekk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gaentdpw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiazjmgi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuvrrkv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmzxyzh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2catxakvt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxeosrx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nktcyqti.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxupefa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uizbguby.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyxfnxx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iijmfzcj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvnbchw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzrdkeh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmskwxrk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuvncyg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszeauvt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gecayakf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2auwladet.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2axkilegb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvuqmic.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ezthohgg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqosbcml.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhnbqpi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnukxnpe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlfgcnf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsgkzok.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqjorqw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsaojvf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zuijrlsi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oefxoouc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyjtaqy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxbpqd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuabcbd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjohxsc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ltewdahp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qioyuppn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqusbrj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuskglot.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcpdhhd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mrchjjag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yygqppgf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvxvbqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgmysbx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjbqrry.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aksnoakx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzngjny.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpunypl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzvfebu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyskebxr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2heihzolh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2itnxkkbz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqtjnja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ulymjbgm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbndors.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jertdizh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2labkackt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgqgnjt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbquwbw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgysniwo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szslskic.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjmlrgd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2frkrsesz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfumjok.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tqarphei.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrvrczz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pdivcwxq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qenzlesw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vvycwnco.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2spbyzbra.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxpfyzd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyusujhg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2axhlbtrm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2soiuewmo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrgygiz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiutqek.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvpxgys.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzxwbbg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2laufxdnx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2drnkfvdm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2njepickc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2blgxjhhn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpvtsay.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchuxfye.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txrztzvq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oixsgwhl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlwxwis.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmegfpcl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrawxtf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvzhcyw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tqijtcsw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbtkhwb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2anvxvjoz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2toqyvufx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrhqqlt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhdikwt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2luyxqdsc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2peaqtjom.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rnurbmdm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2myfhmjrc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vetebfer.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yspkjgxa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2isuzypmz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywkzgsv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjlwtvr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimfcwa.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyqzepc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tknbsjin.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqswpfet.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhzyvfj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jyywguim.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlymkev.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsefobuk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxempwz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdvengh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxkbhne.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhgfamn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qerqdrec.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2enjczjzo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhwkdld.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aombouqy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwzafne.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxjpblt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tggmdgqh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvsdsav.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhezqlp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvipetj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdznyhfu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyargvtn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcntnmv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmgknvb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlibzesv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhgxqir.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuhjynk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2owqpdqeb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvhgbwh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jfssjdjb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkpzbuv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2slvqrupf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pusxcagg.html


<!-- 参考信息 -->