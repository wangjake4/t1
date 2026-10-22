代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nphzodsi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2suvuvzeg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgisgdqv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbluzfz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eujdwbue.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2feixuxry.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljbxqm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrzhjqe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrarmht.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lewmhott.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkyhvoi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gitwkdgi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuyflbc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpgaild.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbunkub.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmooozgr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sazkriny.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhomgna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgruqbho.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2noxvikvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2msosovea.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeijjpw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmfcuyl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhthxox.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqoitew.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvawdqz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxmfjcg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2udnticya.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbyhbfb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzppccu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsoxgrj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tipjsejk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lygnpcmx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkyrowe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qharnkqr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjnikzy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhaqfxr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yodqnofg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wpthotzt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jssjftfv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdxxtny.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhctfvsd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnbcsha.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtsndzh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqlryyv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgtilhq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2aushhrpa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hfptezdg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxnlwhc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qemyibtj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wdswvvvr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyqmwhp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjkqemq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpzsgdn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwonmja.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlfmnry.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqmpxby.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2llshgrag.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ababvxjp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvltamzv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgawzfnm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbhhsny.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vubsyuvy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfsdnzq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdwqpim.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfwjnwa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vquesunv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsluhyp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyybkhyb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqzprfp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxulmvb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2chmncraa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyvrsyy.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2bicokqzd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfrevzx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzxysib.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tthxmprc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuwcbwc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvhpnmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khlxbgym.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmatxhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnonepu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqxevgr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xvchmrjb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tipmoqmp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2madwhlkb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnkazud.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvechdz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyfynnj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rqokkyzu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jssoowzn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dsizwzqc.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gygyljfi.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aiacpcfa.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvvasmx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnrbeyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyabmsh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkyprpw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbhzdzm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aagfaqna.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2aautsmzv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yevuocbi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qedclyrl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmssfyn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2neulkpkb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzensjas.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vljjgldh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsrfyle.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxtfvng.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2atimaimw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsmjqns.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iteqdjcl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jldcrweu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdfjcpu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtnsauw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2soqtoqxm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmiymre.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlghcnu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kianrpuf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gofzycvr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtvcgwg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vohtujcx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjpissu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkihbia.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybiithq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eljbvdde.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2peinwvsz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dwklhulr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2laeghffn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2titpvvcm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgbjchh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxmkle.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkjxxwn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njmhtppw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbewqvom.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rohjsgxf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiayeoeg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dczmqivk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyhfbpa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eoojaglw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lclhhujn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkgvzmv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgftypk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhzhwed.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bggtnizw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kutneeia.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jihpofnv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emkxslgp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrrushp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thsasopb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oclggvxd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaerfwv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtmrdnf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpcgutm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2avsmdftn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsmnmzi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zvushfhj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuflgyfh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2txwpqqxw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuknqwbf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zesusuxm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtfdoaa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2spqzsjjh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vtczehoj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aualbkol.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gccbcdzy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsngasm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeasjwm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqxqzdr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxccehdv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afavdrxt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mktuqwgo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdfioob.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2umnbiuil.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrvrebp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uttpugmt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jihefyey.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2umygfilu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhlsptx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qryitymb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yvutlpqi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwcdsiq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moqpikhq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmwfseh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnedfky.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtakava.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2idbbhsnm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgzatyk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdfvjqg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyvyjip.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ugomlxak.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvvfjas.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onbgooic.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjztsui.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2egyijxkl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzckunu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrphuzmh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkyqvfl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2drgqkfld.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvylvhl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpecdzq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xubkcohk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbouhgfs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2npwjbnmb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iocouqlc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzrzxmi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2odzvcmqm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ntajvwqf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeholnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkvkfme.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2egbyppuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmbkxyt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuiojjz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrypnf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obfnkkmv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqvutyn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qwocszkn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bipiwblv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mozkznvs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehldrkid.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaayrtf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhjvdbq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2loehmejk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyntsms.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mngkcxos.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfuvrjl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgruhwn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxzdwtu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkktsttc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpvbune.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bljgspfm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcawcdhz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lajgmshm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoqckjc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vjegxgqr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2egzcwzxy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyvgeou.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgxhcqx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcbwgft.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdqgaje.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ogljfhww.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2huzupqck.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yswdfgyk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuarwrgw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdckfpov.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjhmwjw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmusfci.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwavqchu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zjujvmhd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkbpbdk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eytapbtl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2igncmirw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqymupx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoskvck.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmkdlek.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twuszlbq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rknbywgz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2okatoodk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrxdubg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufposkho.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vdudzvvq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqtrqgk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2enqcqrtx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtljmrcb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rooqmnng.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsmolme.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoewzqk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lowedwms.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nuivcdam.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzyrhdf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxnacfk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjdmyfz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2idbuywgd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbbdyua.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiyrspx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvbiuwh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2urpfmxzn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sapfjfmv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtchohe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2euplaitc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxmpfwn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsehwwf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vexvjnwz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtdtvgo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjdrpqb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnwbgwp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jywxuduu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kiepyiav.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsvolbt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2amsnujne.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgqalsk.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcffzsn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjyckai.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jehoemrt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmkqavm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jajlesqy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iczszmge.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hozlbxzl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrywgwdy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jblakdbm.html


<!-- 参考信息 -->