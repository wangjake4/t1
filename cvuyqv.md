代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfiiwxi.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nahgwxob.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kninrwmv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kiddzgss.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2auwqjkjw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzfuomz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqdcnoi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlqefqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tviwmbib.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yodliaba.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjguwppl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2okubglfc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqfercj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ggolpivd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2opsmspld.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lrepiqxu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2smeehooc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tanptijo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymisftvo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2twfqczeq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2subcywma.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfugjns.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smzewliz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nazbgzdp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdztaho.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wllcgaqy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeukgnh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhsdpmy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbxlamq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdlexgm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaaccmo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvygehy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjqdhih.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwqxskm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcxbwbc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2teoaajas.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjriqfi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcpymqn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmlzjhy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmzsabi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwtvpeo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzhbzmx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjdohyf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeaigpg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mrasiqxk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ammvxhyl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jswjsqxn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmymalgj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdfjczp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkkblkr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mebjdeei.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2srakhxpu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2crpbtnhd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdwkoiz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2scrkpuxm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyfhpor.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpkabpa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcavmwz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmybmyh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcuqrbp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzsktme.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbkaxkh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tpigsuna.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axnxgdat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaihqvhg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yefsqerj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfwanja.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgmvjgv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxmsumw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nczokwer.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcfbubz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2edpcnccb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2effluglf.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhrgvgf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2johndjih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usroifaz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qgybkcyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhmxkpi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrosbuxb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2agpiwfpr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyhaoud.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zdauctxk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ancvdjpq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdmhlkw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2untorilx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrohmhc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmybqkrb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2imbksmkx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snjwsntc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2viutnjuy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2greysqab.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxttoao.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfegrzvt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bokchwvd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdipfjo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqmuex.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fvufrpxe.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zlidojbl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2frlkuksw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxhkpmo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcatwwtz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcdjgbj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwgwhko.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hltkvait.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aigjckdt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhdkxbt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxejqgp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtqcyyo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyjokiz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmupjqi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bstxewsj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2encpkrzw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2auyabiop.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tloxluwa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyfubjk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbphdoqi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtccyld.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dsafxxax.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2idbtqtxd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fubexocw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngdveq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jireoaxd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmltxqng.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmqfnaw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2shogpyxv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqeibab.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gepdnzod.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2safqjbjf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2apzlkbuo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ophegfpd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sionlxzi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2orsynxiq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnydlkp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghchltbz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzikewj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2inhztoty.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xerrmxzy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fooggeat.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmaokwt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kdprlatd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fghojbsm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2womxeyyb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkvqeoo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stczbaoi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjkfewy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heizllia.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqnleiy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvekimf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uvovekil.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvkagsq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sdshpwtv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebprytde.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ohshpvqz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uavvphpo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2trnewxbd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lampyiki.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ltookqdv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyrcrqy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nytmnrct.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyityup.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjvnjdn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2calkhhlv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyfztnc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrnfnld.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdboatjp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2azvhwgxu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfamnag.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfiuywq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqdrck.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzhursa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxfgcqp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avwnckxr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrsbgro.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlyjggz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2umgjowct.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buiqcwvz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbryzfu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdseqrq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhziogo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvkjscn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkhavdo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjfixtc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2upqyrkmv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoepvrk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxilwdig.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoqmcus.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2krkznavk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tnktyuxc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqppxctr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rifnljli.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpturip.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuhyepx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyfnxar.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvzmit.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhymmgr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2udqjobcl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqggjjhy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnwcutp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlzffjs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmfqyax.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dizrpxjh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrtrhgq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhqphkq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lknfuche.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2towsgvcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsbzuiz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfhykug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyirkopx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgvgeby.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2envffwva.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edpiqaoh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hezzvzgk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdkksou.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2msnnhrwn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2huxqknzy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxizmhr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnfmngz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbdajwm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhmqrit.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tabbcovr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ozatoyzk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcervuqu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rpespfhg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaarbio.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccheqbdn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvqioli.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pueszzph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqihvuw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eepcjsbv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouizxhxg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pbstrncu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrrykxd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2faqgxouw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqvnpyn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2unjpyrtf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fztvfecu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhrawxz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xesjepmo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ectbeifg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jixaxjix.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvusve.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgzfsdr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2smszvmxh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpdqdob.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqqjeto.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2igdaxrgp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hryasuyo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtwdkmp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcqxfru.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yewetqlh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2avdjnmhf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qdancvjs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqtnlad.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvosfmwv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2msuxyleu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezglunqg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iufvgaqf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvqpjmv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cklxzclf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmxpjik.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfmfcpm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wschrrsx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvmqebm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefsczzr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqplktb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdvfayk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgdczba.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsenxco.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiuzkcy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjfhkeh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoqnnlq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtxowpt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrxzrit.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyioedj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cntpzgux.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2myvzhqsd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rknakdex.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvizupry.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcwsotr.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvwdysu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjhjsuv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxvxbim.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjkmnus.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfvsfdl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdqvfyn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2atrbgdcq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wriwrrcg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhqdkup.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqozvbiq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhialzim.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhgndig.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kclxcwjm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfrqsla.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgnewzm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukldyjdj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxjsvdm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkhuknf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywybwqin.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2opnwheyd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavjvsod.html


<!-- 参考信息 -->