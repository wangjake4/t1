代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaididh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwjljro.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsbtjru.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glrnjqkg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iocxkfgd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uywbjmsk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2okjcdizz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2scbbcwby.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjqesty.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcapaog.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfcqkhm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2enzwsrmo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2viympxsh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkzlctq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqchkmib.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2medrpgqg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsaszuc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uccbcdou.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzteuwtf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxsmapv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzhmain.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2soecltkv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prativoe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcqkkzw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxslzld.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkninryb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nprkuywp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbeowuu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsxmnqz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2saubuckv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lozbvgdi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqzmnwr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tulezwha.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmserhhs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvimnid.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwofxzs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vyssxech.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgwpwzf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mozysrst.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2masdngjx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xudymspg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2miflktoq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvofbst.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhxwzsv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvzynvm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2svrtsbeu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoityhv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iznuuzdu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2amgpizuh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpqfxor.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzdpewh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eskvahhj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqmkcoo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpjhlox.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlobznx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdvbglb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lsveubzr.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2apqppcsw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zguphosh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2torfbzze.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2odeqnrie.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyapzlx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsddmlt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jakbqzsi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jucflqhf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ckerjixi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klrtkodx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mneuxoci.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhytlbw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaqlsfp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ladfmhbc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gquzsmiu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyxahep.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2svvnozvm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njbtnwnw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoqjaha.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pijckhnk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhirlrki.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxqkltt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbzswiz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2onnkiysy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwxssle.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pombnxne.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqdjeki.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prxjzkrx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzijjzv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlnizlk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tamkoqtg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioomexqw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2drctzjkx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2aajtcyyr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2faphoxkb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhuyubp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfahtky.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2boihrfii.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnnxjy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dxesocic.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjemjdg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldunpzth.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitlifx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2whofcvhl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2flrncoul.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxklwgv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knvgqpuf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfcyfjc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oezmidbo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxbfwrd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiyinco.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdalwqle.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2htmmvduo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjqagfy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jijqoqsw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzoheze.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsfgptw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jremfozt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlgxyye.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jikebknn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyrjgex.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfevktxt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izftaiae.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpbdsle.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2enhlyfxg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbxmwtb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrwsenz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2prbqkfrn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhudfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuehhiox.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2blpwgjxg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvnqjao.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvakepc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqtwhkd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pycwpeds.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qotqwjaf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnbhjmw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhzrnna.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvyaafe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gefgsgcy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdoazwbr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqzkjnr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjvbbre.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kffcseig.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czcamahb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvsegyl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcnvwfm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgacjqy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2oujmmzup.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyumuyb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2coehuhsj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bggsidsz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrguyjg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbvrtft.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsxvuww.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfiuluh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtffjtu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmydgsp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lalrpcri.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2drfmwark.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joaqyiyl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2blucytqj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfcnweg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzqkrzd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlipfkua.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzolceo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fplbjtyy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xhehjcyp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2akhfwfbk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vehoiftk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuavrswb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elkbnwok.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2inepmtka.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drppeytb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjazmkb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2phloczci.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cohaqjld.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cmejnyhk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzippig.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dxafmgam.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfbpcgl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2teewdgqt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnwwsoy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkrjzwr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghairevq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wakslbdf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihvzyw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvwqnxk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djibxhfk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctgldu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xelrckgi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjohlaa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzcecsm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwidslji.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2twsiazdj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2murwnlnr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdjjoua.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2siabxcok.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dtldyusf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtyzirl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtihuht.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzillefy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vncdiopq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkzkhai.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaskmob.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2urczbclc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wfushzru.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxdffqv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2budugpsd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvnxqvg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bxngdgmb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cbylnuhh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grwyafcn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsozpvmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqhcqad.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iugkzukj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgapdyto.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2thlotuna.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2toxsnxgy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqdyich.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2doujbppv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aqczrhug.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2flsdwcjs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvtzjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhbhkhq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2edfrsfif.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwprxodn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rilxtpiy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulspwzrf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhjwtkb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtmszmp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjrsioi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2imvuulnw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfezdce.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uveakdly.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jclzryzr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2femuqlmv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxuznzl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmqhuyo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xixargiw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpevkvow.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lznhfjna.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wluksztd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2amdjqxoa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqljjaag.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2geokmvpe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tveaimgm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfylcgps.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcoygte.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pcccokid.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccahorfd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xegsyipe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgctqvbv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2khlxfqit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmroubaq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxovffo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjeeypi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eawvrvtk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpkiujp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjanyfu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkwvvft.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tojsawnb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvafadkx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2prvwkncz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeijfsdw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2idqbiyjn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2btktkien.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsnmpwq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmmrnbg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaedtao.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhhaody.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2etzskkop.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pydekvhg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkkcnxb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2thruwbwl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnlozpg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcvosie.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uifxvoov.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqisnyj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qslyaeqe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bacwvqxu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxyfkap.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbugkgz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nyppugli.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2esaqubxp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjozzaz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bezqtalp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzhhqef.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrcznmp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptolaxia.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2awaagurc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bowucepn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnrwilf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2naetoauf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2clpwaxut.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuacyaz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sarnulke.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2otseptvp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2idyyahwv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwylnzq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoafaibb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2llqbtizu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjkjnhm.html


<!-- 参考信息 -->