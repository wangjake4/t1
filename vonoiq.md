代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtwxcoc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cilezymv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2utwycgtk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzkhado.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2moeqdzkv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2csxttktw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxhxcuh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ouipnazp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfboksl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2naohixfr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrsxqez.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rclwsifz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqfpduy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abhtjhvb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsbwoti.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bskayjjg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2axokybna.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2benamfwo.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhaekeh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xnugwany.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbnovsp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sznznnhi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqvpswb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqhuwkq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqpmbgo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2alydwmvv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jehimfiw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmavtof.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqyzxlt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dldtyiow.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xktzxjel.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xawbkobb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxxgjen.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoamtvn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlpquqz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2osxflyuf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwxhaet.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmpaswo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2waodpwlr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxvcsmc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aylojqab.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2odgsjvim.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmxhebq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2guqhmmfu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbejivg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzzqiuo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpjwidv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2twlgmtgg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfavzqmp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jdueydkx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmpjejv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmanqvd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2doymxhai.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyxhahe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rzotdofo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpujsqy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzksjyc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdthplt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qbubkfup.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwetyaw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhpmyxa.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvuwgun.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbldpkja.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kekuvwow.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djwrnioq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uccljanx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtdcrbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuzetuy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxnivkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eigisjda.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2arhzdbpj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkeznim.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyfpgum.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaxsluo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxaovri.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuftpwp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2dspiyzsb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcwmtyw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2abxhvoah.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtuxda.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wklcckhs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwitjrjg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcmmhq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2obcygnib.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrbepso.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tapcxgpz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnthpptf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsfwdcb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbzaakv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajccrufp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvniiak.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqibbbmp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmtqgzf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2advoayiu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsssaco.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvnzpnp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsesabj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkrgzix.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqbcbxh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mtilnfhw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtjwbxn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrtfoxp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrefjcy.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ezndiius.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcivrdw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxosylru.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2btsinhyy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kthhgqoj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2phmfbsfr.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjkzroi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fomfysll.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbjcpeo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdzcaki.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyechqy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2anujptzt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzavphq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjyjsdu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2swqlbxoe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuoxrxr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pmumpzht.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2buqmutip.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oebfihkl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2stvzlqwz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfctsog.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kchxemkx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjnkysk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdegrvkz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlrqgvr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjphkwl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtyomhu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgijzfo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sauiubpn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2noneguau.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mmivshhc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgkaggw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2imsdbbui.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eovivhjc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbewyftb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pllxkhzc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxsrewn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2iekwwozg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2seudrxpj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zoujkwuk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmgbimm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sbljwkax.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqkogtb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzgcagb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2upughbzk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzukcni.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sceekitb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzvcyu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbmctxw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfpvuhr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lebpukrl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2obmatyob.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqmlibv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhunuyvy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xikexdoa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bevpghhq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrftdki.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2extyxxwq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmljtof.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nqefstmo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjokwqn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhyieqg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbvowcg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpydimg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxadtzs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaxnnfv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2essleayn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfsoxmz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfpzatg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkngbpib.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjahvjp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dneljyec.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fafcguav.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iukaucxu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxmmuqn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2akzcgcel.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwvpbpm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jipyuqir.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zmujpzwo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxeyxev.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2icqskusu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwswarpn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrrqasy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcztcknk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2suqlnylx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxspfie.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcwwqxt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvhirov.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwpafzf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkctbqrt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2shvevddn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkruzmcu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmcjuna.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2owgtyqof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2haoyzrwb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzmrmzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2welcyimk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcpgaja.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iglvahjz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srmjxjkw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kyotmddx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lylpebdm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqovpfl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qmekuczr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdrsqpe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjtdcok.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yilgiclp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2smlejvjh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itcolefa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2chkofsbk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbkhle.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2peuhkjns.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldhqzrp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecshqqjo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyxczcd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rexajaoa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fekbsmrz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qulyofhr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaeytss.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrfoald.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeenocp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nixlwhdy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpbvfpg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cufxxnie.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwbphnq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qvokeeco.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpssfknk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdwsgzm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmcfgyq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdqkzkt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxcuaga.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhusreys.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjtathn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgadacx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhlpkhg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aelummoz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvolrom.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsfjzeg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2srylxujd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tlulrtcg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuqwbhf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvxidfg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtplued.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmldune.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqiuarl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2srxvjesd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2igjcjuzb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgigysa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2atijghsk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqnqgao.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlwvkpm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dotnsirx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2symskfup.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhjhntq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmflmite.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmiyonc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wouesyps.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjymac.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kengskeu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkviulq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqiekbs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjqxqxl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdcnida.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfctfool.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvwqxrc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2akebaliz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbktxtcq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpxuipb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyuijpn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrpprbd.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzhiuqx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqhwayz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdsqzjn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enpxiucm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwppkeo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjtcjnj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nfopqjxk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2txftnhnw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvuaqjq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfuctzj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zadaqsey.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqzunlf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xirgroyz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bptmvtvr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqmarab.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqkymgp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbhxrws.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvcocji.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imqiyfiz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xyucuulu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxkzifd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pskvywhb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2isytdcjx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmzwqhd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjwitdk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjdxsoz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mljfnwmq.html


<!-- 参考信息 -->