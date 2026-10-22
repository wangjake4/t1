代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qbghfltx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2trxwaxit.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cktbmifr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzrzshd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbsfrwr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyporpd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2adcedrfa.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtvivtt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxqnavz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmvrehn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nggsqvog.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpfkdkz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2okigyqoj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsogrdj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyeyneg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdrzinh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nffvpvrb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bauhjejp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkusgmde.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqbtbgv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlwhttv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izbwbubq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skzonynl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtsdbwx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2icnhekgr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nufktssd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2djjibvic.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2utuylzgs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dlktloun.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtvswbr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2irlkaqvp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhqfvf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rvufeniy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pzehfmvl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jquhwauu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmpxplh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtxglf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sksutmxr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2frlhhets.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfnjntg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2irqwplaz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2btzvojgs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyljmjkn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yubchobn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2izcvunkg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofawypln.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaloihr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2muyguulv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hrearypd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2albuglkx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2friukfje.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2beluphee.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvaugve.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pefwpoax.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sfigzfgw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbpksiy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bebbsxvi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvsmsuo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxkejru.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzplbox.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nbclvqzj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vachrebu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzerdsq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbjxgfp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdmbhgn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbxfrip.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxsktuw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmzcyug.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dnftfmnl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2odukfxus.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlrojar.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xchgpkou.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfweqgi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxzjjfv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeburrc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rawbdhnk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2peptzvva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brevrero.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jribpddm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yzelfmzk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjrjmkp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2llnwwksl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fehggnja.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkwwygt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfoiofg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjtzfwf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoqasfv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2deuzthzv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxixunyr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtmqlak.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtphngn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrczjmd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2shxcptlr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dlddubay.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmkgkrg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hfziyqcu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2thohgypr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgjnqci.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvhvryt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aepigtws.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2slsopaqi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlvnyhj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xozfaomq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmxepeg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekztbhan.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ekswlfqa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwgtwdg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrdysfg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdkrrnn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdgpzus.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxsvxrp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zegpygbm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgimulr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwdxefk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfxqjde.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqqxckn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrepjwkk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jpebitym.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2loyopwfg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gjapgnhx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yspthshp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2icuzcrox.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwfwxrf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnfvugi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2frgntrff.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2akyrwleu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkidlig.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2benhfvmn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2joepcsig.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iegdjmsq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2scxauvci.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zblazwdy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxifcphn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2huncespd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkelzqfu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2edoesihd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwzjlrp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdhccjp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfexrxhk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiatrpv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfjrbfo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqmusql.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfohfnr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyreakh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gatdeftl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnaveyk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhozvys.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnkxoju.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnhsnek.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyytodtm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxxqzaj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhgbdeu.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qviemtyx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdxwrmd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2isrbcbtu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnmmgar.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlgxyeo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnchorih.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rbueiyyz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaimbvl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2orfvsnbs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgcnyjl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjggxud.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyinxkx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdslqnqv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wefzbsrq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxfrwqw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsvnqvu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rojoojbw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2feardgue.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2djcuckeg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chkicouo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxfqtml.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2acsuqnys.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2smwusflh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boifbhwg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrndoox.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxsierd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgopwvh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2avioaqfw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfnsdcl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuwoivj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnvagtt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mppcffdr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvzvplc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxpkuxs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2czgxavrp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxqwaxs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzicllu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2anahlika.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sezvvhdx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2owgxcnce.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjesegqp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvmperi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wodepure.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsvgdhs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaowrgev.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2icvjiuwy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcqgteb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cputttip.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2glsfmwsl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhcmvxq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlrxroz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ovycyuvt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sactfuxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaiibtf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpqnrvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2newxhvyy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tgveclly.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdhmzdr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2seylyibu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrnfege.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcwkxoc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nntyoceg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtqabop.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuxlqpi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2clvpkxco.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xeojkxbh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmpdjvz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqjrkoq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mldbdnmm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2negjraaq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnxtnzp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbjewgw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfshplv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmkjyjg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2abwjgxmm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxmscic.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvkjzvg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2owdozomn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wozusxst.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvrhafl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xfexlhhc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqxrdgb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvdxjsr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgazdmd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2etxrpqsy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyikdlkb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuwdpsd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2irkxkgop.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfynhbe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnrxdtl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzjbuyg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwztqsqy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2unaxoyqc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqiyvha.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoytvcf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktddbmgx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hngshjog.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljastngs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twhudikd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrszfqr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoewoyy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmenudj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qabazxsj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxarvwv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2famezngb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2danzgege.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hswczbmk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdruupaj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2duhhiwem.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hplkshnx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pmulaycq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqaptaxs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsomaxw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfgcgnm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xspuuoek.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhpwngf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkkmalc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjcflco.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trvbfznc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2amauvrjq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zocctzwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wxijrbfc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gemzygtb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2liscxpcl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwgohxn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jscakhpa.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njltymyd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yiudjene.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyyyrpa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvhcgtl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzywbxu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcyhxif.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyldgbs.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wioqatqd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmuaolm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhktsyv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2houfmybt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xegvwnem.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xehrhpmq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkalmjbd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ayranysc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2duymppfn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bllfktcl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlupoco.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsiuuel.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lygohkck.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzjwjat.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjaryql.html


<!-- 参考信息 -->