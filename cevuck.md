代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkkpxlb.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxfneth.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdrmsdy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdqvsqd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2szbqhfuz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2odqfjlsa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpzpyuj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhmpfvu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrxnedq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2artusbve.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnkqvwo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsbketf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2likrgvgf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsznghg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnzrfel.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwbtqlt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2natpxsvr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssujeuxw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emqtnhkz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdupveoh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxngbyp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqdqjqg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgrdibi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnruyod.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2oqogcawt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdwidpj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chagasgp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzjdtvd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxamaku.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udjowjjk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhnbyig.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rlryrnuh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2taovacnc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2coflljir.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbuvhbg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbharvh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpjselc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plzywdoc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeghovg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnfzogf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vhikfjew.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsugnhp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrtaazv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2plbdoyhg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zrboycyq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pppypvps.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2usfokgmw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2repkmrgx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yngafxvf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjnmniq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2edjghcvi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpwjilp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nixodrqt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ktevofjv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zehaftbn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjmuxxm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrqaxqj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2alsaiuus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzqqifj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgixckrn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnrdeby.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2unpozpby.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2iaybhkcf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkukylm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouckbgpc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxxaymd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjjmrup.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yonsjpxs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wivpbigh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2aavuhmmx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkdxfwn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtqypfo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuevhval.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxwlosg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqefhhr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wotgijgr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uqahhklv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oogzdhwp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lxttpxip.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwbpjbm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqaxush.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzthedw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2makhujts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eeywkbrb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lpulkomh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izpqpnon.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlexxuas.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaaooal.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvkiucb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2khzqsdlx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2niqusytm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoudbdn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoudtur.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2meuemeuu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lanwzguz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzkkzvs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmxxqhz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqdymif.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlcjgkh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rsezxswy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxruque.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ettaimtx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2isvvnplt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjxebdn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2osmthtgq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbamknc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlnczty.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeevthp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bshajzjz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gylqyuit.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bugvswkk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfctvin.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzfelqs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgaesly.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pffdgaup.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrrkzby.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hlidjtei.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfsemsz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rggogtig.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eatyxjtx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2daniipaa.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drcgroxd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoyxoej.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeadflj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsguykxk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ustkjbvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsaetru.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2urqcjdpg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dudijqtz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2khcnwlky.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2njtwuirn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pzchktop.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfffunf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjbgegb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tievzdbb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gufsssba.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpthydea.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmclkmc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfjimfg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmckyoo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeoidil.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpnrsk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2twxltvxo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jahpulcn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkntqsab.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pastzbym.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrokgejd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyjegmn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eweobpcc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdltnxy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xcghndfb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnleffdv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2spewraij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lypmgokt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bojwhovs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jypxdhvy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzkzsvl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzcpvbj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2waohzpjy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdwbyim.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvswmqa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vekvdmmg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwhkuex.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzkzcxc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fubotrpf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zecunwxy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbqalpy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2llipypru.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsncehs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2thpxzgcu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfscihv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaresbm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnflhnee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kshxlnmu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjyzaxv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlzcams.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wzadhpje.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzfqwgb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjvkbin.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsvalms.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2myngkfkh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fcllxokv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mwswjqac.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2athbvcbt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbsiksv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrgxpac.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrnyema.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mueosdnp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2blwwygds.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ricnlbsz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtewwalr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtvgkff.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsunius.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sruxudov.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqzxhwk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vkelzmvt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fatetkmj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcwlgdf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrcpnzh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdfqrkm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xptvsndj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oihblnbk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysebjjwx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxlynzk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdskcif.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxqmczu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2smunvflx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mgutnglo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdiwpdf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiadror.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhzqxh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwnoeeg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zivlhqrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwncyzy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rctfiatl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrumxzka.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdbegvj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbbdpow.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqusyyao.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2oskbefge.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoaaqov.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtrpizw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcflspc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpixvtg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnesqzm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xcugitiw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxvqpdx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dchfmpgn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bchyttha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jccbjkaz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuuckmi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zivcofqn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpfxrsr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2feklmlnw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlbedij.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdeufaz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bednxolt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbkbpcs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgtnfis.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qznnztvg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtqxewr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiivkym.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvnjpcl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wspmjvor.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmohbet.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuvkpti.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqztzomo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjclddxd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxefxgg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yllenjfg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzvxolz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eteirkco.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgtlkhe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkfrizm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ircrquir.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmxtoif.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2suyexyhb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyjrwqc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqbpgej.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuegaqy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgtwicr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcydnjq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tzysffyc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeczmfo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2naqyecfr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkhycmi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrxrruj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbaegad.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nitcavoy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2smyzmypp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjlypnp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2odwsjpux.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvcgxeu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rysdxayz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrvmbhk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmyhxcp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kjozthcg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgzcijs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qihzclos.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lugxuejd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiqotit.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sowbfblw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoniaud.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcixrmx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2apwqeegh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kasxsvrh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrzprdi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2naisqhcq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgafuza.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2khqdytmr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2upjfiedl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2roufprxc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdylfpe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2snxnnxeo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzmykqc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyddkbr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zedftzcg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jwajkajn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnlqdlm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbmeudo.html


<!-- 参考信息 -->