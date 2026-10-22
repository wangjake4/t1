代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhsopbz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2itvyzxzm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyehvva.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyawqqec.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcofdmfp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gutsehit.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otrfdccj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdfjjzi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjrrvfz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdwiypa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbjzlrk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkesjqx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nnncebmb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnamjsfl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vizddjle.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vssjvkmm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hkodwjxs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmijbhw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vntfjmwj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qngkgubq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hjloutsc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vinvjpnp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ytolwsqf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jihzmixr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2twjajnkc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbgmakb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wesmdgxd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cureylfy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwmvyxt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxettatj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2timkulvw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzmtzfh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tazkterc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkcnbwy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkawwbv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqhhjbr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbahgni.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eexkawzx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyuytgi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2drapffjk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vqupioaf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2foqsdfxm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpfzfc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2purivsmj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2eaauqrwo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2krrqhgjn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uitwylhp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2exthjkmo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfqfczb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vjewlefz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hllarrcu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmbxnhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeizibjh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2begbqedl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gitcivju.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2maztwuas.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsdtmmq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmcrbxe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yowmceso.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcmnwln.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bidtdsdi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2maaktmja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzzgftu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnoswvz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2snobjuol.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nopbkmzh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjajovoq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkvlkjr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2juvfcsai.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vgffpocd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lelldgeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dviitajz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rixupipx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkugavw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asjrbhlp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gdblxlfu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sythsxwa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2acwzzivf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cooblpnk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2objeianv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtydanip.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdylymf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuweoxq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jdycucpp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srncneql.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2trzfatob.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2dizowxha.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ddomijdy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnuabkg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiypdmx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivssilkr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gyomskto.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgrsrxr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2luwswinl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2utvckaqx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yryjamcz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdpvtdc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpentzg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zccplnrc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrzoaof.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dalvjzch.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyzwgvx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxmmnry.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsxaizt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bypuqpag.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2isfmkubk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2getbvowp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vuehrnvt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuubddxd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvgishj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgwealz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tplcfubv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqwkmds.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhrqvex.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgpkfbs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2luibilyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxmailv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjisldgr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfzdnri.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wkakgwcb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmclebvg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmvmlba.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2atnvbdzu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfkxcrz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwauxsq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2enkhntfm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2moorynsx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tovvyhxz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyopywk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2znnxhiuc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2szkxsupy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eoljofkz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xokkblkm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwqfudn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2itesvrzu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2posywkng.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlfpomb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjwfrek.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eajjunyp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kycvklsm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbiohyn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oonkxfhb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ufevjvmn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rggiogbw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2swtsdytt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnrvjfz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzhmtui.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppsnwm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwtyugd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvnykyl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pautkwmd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yedwbyxd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzbsbdd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2urdzkdfj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbavtow.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkxvmqg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtmjrcw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fndktmlp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2grnllren.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhjpwwu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyxfaup.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2luqoqyfe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zshywgcx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2feoxynhc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrbsfrc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmzbzsk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbsaavd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skpcngqu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2atizrcod.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2glqozwpz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuoxwwb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzxdabn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqykvlk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcbkxno.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elgxzvut.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwgqogj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzaldgn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmwqpmh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdndtoum.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rorptjht.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwzfnxt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2coumhnma.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuxbehu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnfamxx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrojydlt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oenrpyry.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2znzrvexw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyopepg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgspnub.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2woukztei.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeyfvvx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhoxldo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpqoffk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2axxtnnmk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uukmnbuy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2unidsezm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxovxlb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiquzzm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeysymg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wodqfzmz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdsttny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usezdetm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dndnfnpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeohrvgr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvktmla.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2orxitlor.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnmxkqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqoqds.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zujfosjz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvobxlw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjigtsw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijhfdp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tktswmhy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwpfayr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgslklq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmnzrwn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiarukz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqaorbh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehroeqqj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysktfqnr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edsndtgb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oescukbl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uldhvwpq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmqmlic.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gejywlbm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxakhwgy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2acmamszk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqupdxsc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdemqcb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwttnfo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2niuhpkhc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svmarijv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uwctfnpx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2furtwfnd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrygoob.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2evwwtmom.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtlnezq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gzparqbl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pnujybmc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeogozcr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rotnehcd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2omcueooq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjigddy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtyhzpb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2htkguddv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfvoxdn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aowdrwvk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsojtuv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzumjhnm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvsxjrk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlszxrh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guqkjbpg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kadwknlg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnoaxq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2thvokzot.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2elsfeeap.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjwrjrp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2evrqdtxf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fqttqfip.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhifnjwe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbpbyyd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkthjjvi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gsonpjxh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2abnjzxrp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nciqcdxa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2umvywyva.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfhdlif.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kolhrkbd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgutiwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyogapl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jnarepjq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqtukgj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2phkvechm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zncfvvzl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsffltl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqiazscl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yrenyuvx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbsvhje.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrcypvo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnkfymw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmgnhpw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfbcghq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbruqnrb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcmafhf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vvymvuqf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuowbkw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxgjfjq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qksdoftn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2njavpqvx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbvsbia.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dajfkvmc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhgnpor.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qloeyawi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgotzrdu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tpanqdyi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2namuyydp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cojwjqud.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqeaqlm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzyegkg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyyerzb.html


<!-- 参考信息 -->