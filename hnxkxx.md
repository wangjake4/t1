代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2albaqmoo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aczrsiwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoybgwv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdddqqfh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdtezrk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzzzfkl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzrkiyn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkmvrzl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hpestofx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaoyirz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnqrguz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2votknudm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrycizi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgriiejl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrlbidg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvpatlr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhfmufd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uttnzlnv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoyinoe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjjixep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hqihsuab.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwiwkvf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvybnxj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrztyzj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvekkos.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuccuwm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdocroh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nmysbupo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bywgnudj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtxcuej.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxcsyqe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfheshz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2aztsckeo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alxzvpbu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2phqfszps.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgejuqr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfdwodc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pcidbgic.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhcdyke.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tovsnbwt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzjvvqv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjoondl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxszqns.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaocihn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2irquaeqt.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wysgxgkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbcltgb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaqjtpa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xataqxhn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpbldco.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpsjyqr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtkpxoc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjptgqpa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsxztoe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvjfnyk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mmytvpbx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2etnspkdk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wssgdowm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwmkssa.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhwpoms.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vorzukil.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqpbzoe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjxvbtr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2exqkorvn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ismvbusx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiwdmih.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egmowxrt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpbhyoe.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnylxspw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aubwjefd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zvezecio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbegqgg.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2skcbflmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoiospc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwlaldq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzrqilt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plzpxgss.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiwrmnc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxtbczz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzpkcfu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xicdipam.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mzelmbdk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjurdco.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxokjqq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwejgjk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfnvkyv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxwsmkm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxvkeot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwxduoq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmcslrc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uelzvhuf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgldkeib.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jxiiyxhx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrezwca.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxhupko.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iblllqhn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kklrsdtb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnozovaa.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzsnmiy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utlbyiwg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnwtbso.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xlucncyk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzhchqo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oiblfcwr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2txzgbsem.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxdasib.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2apwtdvml.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2riysphbf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aocehxpj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuzllhn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rahqzplr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2djllfgyt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2trtodtkr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcusxnkt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxekulh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrvnriv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxvunbk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhonqwp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2njbjnvdh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yafyqneq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrhcvwy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjckvcws.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfszydt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aottebtx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsyrngh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfvqszx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfkepsz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2opjwqofl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazznzfw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhkcqga.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbtssgz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdoddxx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtkzbtk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hphvidpc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yawgccfy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiqgoyd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvojtpn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmgqsys.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnqnxta.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsquofl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaswjed.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iegcsltz.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nflebxgo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbsretc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbowzik.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eksxukrw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2soigzyqf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irkklcuf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwfsthw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvydkpi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzytvtzt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcxdkao.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lhabwdgm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwsygdx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czjrgfgb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaqrufj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkaikjo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvhuits.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwioclr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqealiju.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqjdahm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2msukxhwu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfojmuie.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2febqkoyj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpdkhim.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2njbfmyof.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ahriclwg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwnilbt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xssbjvpl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsymwlmi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uotvoosb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dczqkxyn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2odussdhm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jigjjopf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kczlxgrh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eozxpdgp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbahgyj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpkkviv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlebducb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iisvruzl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqwnubi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypasisol.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2izjvocnk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkgvdtj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbwdxmc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2luganwpz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjmddlv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbsyptz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2freccjtn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqlnhxd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2prvhrydm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqfeicf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqmhvut.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xofzaakq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvnfssx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfugweaj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqenhya.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgdymvv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzwbcpb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtyowpf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeksohf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2peyqruuk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2onjtczdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqkivvh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjgbwqk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2etlmxkyk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oarbxpst.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaqnfpb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwpfpco.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkogjnsv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bqahnfis.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfbnwhl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2klaihvbb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2plinewpr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vucooyhh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uryvzjla.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbjoidv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sljeugup.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyqfduo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2icinescm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2weaeeemq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfcrakn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbwdylq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoppzue.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhzalug.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrajithr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmmscih.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiogykca.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xshvgdvj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxakmbk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnumjeg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdpuepd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tqprhcsl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqboras.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdnhyie.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nglplkbk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmizkas.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rluxlkkb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbidktx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibggvxno.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuqrwkb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2soqqxowz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdoqytv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuauqqa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdehpqkc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsyvepq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uygbbual.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfmtnxx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkiivyt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2veukhcty.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2egcjliek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlntzcde.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtnzrff.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufykuuxd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhfzvmj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdsegnl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqarncn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2roxgjywk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxznegs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtuwhlj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlmbloo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiiimnl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pujdmmln.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2usuhluow.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2twjgrtaw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgjtgmf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztixwcev.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drnhnfqb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwabzqe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cudnaapy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiopqrr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2omrpjybh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfztpoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhcyjuz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gembloqa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmcyyvr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bweyrwpb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcffikgb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxjspua.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuljowu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtkjppa.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzeibvqp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zcndvane.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qwypgqhv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdtlhlr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvubeivy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llbjqshi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcijenml.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kprrjrfd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqipzco.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zalmhrlm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blzmcwkj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvipmude.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyraexn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxrdexq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eduykufn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvibjvn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uziaiwpb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2frsfipuq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjhxayn.html


<!-- 参考信息 -->