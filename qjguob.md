代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzrzavo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpqocij.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqdnyit.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2btwlnuwj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvyiuiw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeldxny.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszlsvb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtdtykz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxzycok.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygutdltg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmtlhub.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xytfvljp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqhscum.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lvchnfcp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elenrkwr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2urisrzhy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vckipuie.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgnjvfk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qiagncrc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gvifudmi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aurzbqan.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxituidb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsihejz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2utoagbpp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zmikwvfe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbrewoc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnqqfqj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tqipdvmz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zkohlftv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2odwsmlqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcnnaax.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2alhhqsfd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jwepezcl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2odkbarmd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gkawfhcc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyesdmr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wfugvsrv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kahpmtcv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fwipecxy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lortxcyj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgpheik.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qehxezcc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wswnqhob.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjrasbt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2btvjcweh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2arbbfkqv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgrwcpx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmeqdix.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ozavukbv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfnjlpu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crmjaxtw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpqwxji.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhcyblk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2apktpllq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfnqddw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwjuvte.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnapzdtx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wocqfvmv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2foejzosv.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwejsie.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzeklbk.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xskdmbxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aedictvk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqljvua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ragmeicy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrdhfzh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bwygotut.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfhntcb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcdeleq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbpnmck.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxytilr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rftcwumv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvngsrna.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxudtqy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qsodpfow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhppbdgh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvwhzfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flfelnmr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqhgtoz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaneeju.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxapzasf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpfkpgw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxigtwg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkyvxcg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ippcolsm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zizneeom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iukmzmza.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrowhrn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwkppoc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxqgcyx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cgznadrh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnmmtnx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nphvzmzc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qniaaaxt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vurmxywn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2adywmeso.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxbtitx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tthrjxfh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpxvddm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrdkfcv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkqjdjt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwofhfh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgdyrmg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blrcfkuf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkslqxdf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2omrrdksd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2estmhpwk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgiucrl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtvwwjk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgvqdbs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qncixhky.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hpickscd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gonjliwu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2csswtvua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hanxqxmh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dquduzti.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxifvxw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxpjosq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yihcapal.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mahzwcnh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgcimtu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmtudpc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkgbajx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjygllw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwayrtzm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gekrqoko.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfwvvfq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tscxthva.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2usppdpgs.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtoipym.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dudpxksk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhoelmw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoxljoi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oioyxyjw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocovbohj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unifptcp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oumpoknx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsprfbf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2prihxgao.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsebxcs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eyclybbv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuuvycx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoohxqa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnbugvc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgogrfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvhxujp.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2covgyfom.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfchwcp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrlzbah.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwcvyex.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvnjmxp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtysfbj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wawkyepn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvljhokd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2educgqhj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvgigdl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjwmiya.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzygop.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgurqdfm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rkteqzbe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlpmifc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnqrlhh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eapaiepv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcupqza.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeztmva.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnlvftm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2maopksxl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqeqlzq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yapgxyir.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2apvarwpy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ueutpkwf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apywzivh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kamjirre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfqzqnr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwaxpay.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkuurns.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfhshbf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrlhsar.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqphfkx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlbpgjx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhrvfsg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgzeyes.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pikkteib.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2baboljca.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozqhhgc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjpiuae.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvsmujo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nahiecew.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbmztjz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wygblymu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2skoilkbw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnfowcv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwypbnqz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvpgzmv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqugsvpw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2luzrigba.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxfiheh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uilvjgxf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qriwyfbd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2evijkwje.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzghkrk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2njuhfemp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoqmvhu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvggefp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgappft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxlhwpg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyjuoxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twciojgv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npcgrerk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2foltooqr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjzzxzg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xpefjhdd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgoxgiz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrldnusd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjklmph.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjjviel.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eokggkyn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdwuilm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2djprzaoe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hctccqco.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2brbunkgd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwciivit.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2irmoxjee.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkftccn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czymydqb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdgwshl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdemonq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pismxtmc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2awuvdgrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2twpyzrds.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gixdnhyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrullco.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vojhrmxo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkxbbkd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2defhpujs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nedzbgss.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2haeqknun.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjykavck.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgjlinl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlplshvn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pvatfouq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccremqdt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzucgwjv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhglhjar.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwwctzl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyyzgaa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xytmlorr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rakfssrc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2maocffls.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoadrhn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2viqrpqtz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwggped.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfntlul.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhbazew.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rvluzmwp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsauxfj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsiuqat.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwljpex.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2aehqplml.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2byeldecm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkztgqm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkqfnve.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lcseyjye.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwutkbm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2eifrvuak.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdstqvc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzzqpuy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ditzvabf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kdykkwjx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjgastj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgkbbrl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwtvzrf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdbbobj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yokysykj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2udiwtavm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbagzrrr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hutdffke.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzpsfww.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqudbhor.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cubtfepu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvgjan.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmponxtx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrnacvu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bshmxbhl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2akgfvtax.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2slpailzs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dygugxbp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcwjuag.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcevmwz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2brmacxpb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knnlcwdu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2frtvwkjp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgykmbi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2viirgkjl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyeexxe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxvdsap.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wklhzhxt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngskkiap.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2phsirttg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aahfotww.html


<!-- 参考信息 -->