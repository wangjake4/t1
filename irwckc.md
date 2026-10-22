代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqzfphh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2opyxzxye.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqadercn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoophlu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcejlr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywtlhl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ersawpqg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkdgyce.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uyynbxxv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvibkut.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2finaqlvt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkedoubo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxnvwzs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjgiwoo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjandokw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2szaqleqp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eucvzafl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nymlqjgz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhbjfa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyfgmhw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrskihi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2acxrcnen.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyeckgz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2noqoglyc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cmduyjmw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ninyzxva.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fywusflz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gglwamqr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qumremhl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uciuhiay.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwpghie.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2llgvezve.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlwequx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbawdna.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrlwaly.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyukwkp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlcfxva.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkelcswd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxrvdzz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iofatckt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2huxbrype.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfyyjei.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2upanxcja.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmplrwki.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjloriy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2algzfrdj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyrhoek.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddotddvy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtyladi.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfbahez.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kcymeziw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiopukf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxblagh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hfegoscw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqnenql.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cchpvrfz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gqliprlb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vcndfobr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2llwrcspx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2flqryacp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaqpewn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wftauwco.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiwlvxx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2edlhlhht.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzmzddo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rngkpqzq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akdvqzcy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjkprvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnppeay.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqeeodf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dlokyztp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xklossmk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vhylveom.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzlasba.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azckdnsx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cnowibsu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtsynpj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2turxkgeb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2txaymxsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfxlvtz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhbphby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcxxybq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaaaatm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdhptlz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgevnioq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2riyqfxob.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nibbxkrr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdsflth.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzkvhkr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjyjbti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2owtqktnk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlmkmrs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wviyrfow.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ixomhdwe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xllfsica.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bcedcyyw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfoqbro.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jiufwvpd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkahhfmj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzxdtia.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zixpikvk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuxxbyd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhnormh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyijlvf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2toifwfmn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2umnnzypv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnacgtp.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afhkwmcl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2okbjkdsd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxbrfu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vfboxitn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2twakkzpn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdauwbw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrtxmmr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2svgtmpiq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchprmg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2haoifghh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kifqhuff.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqhsmrt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2upyruqiq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2whzafjye.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlhohug.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzetqqts.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnmoemj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mthwqppv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qqedfeit.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2akljlaft.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvgewqz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2udkwcusf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yelkbkmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgunwafe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyjxliu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyjzivy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xfugzqsa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwrpwfx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ypolncqu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcnnkxm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoqkint.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rclwcbsj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpjevhn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzksrxb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaybxak.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncylkntc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bevsssee.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2eawpviml.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yakmwrdg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2reifcegj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdlttbv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdbcbda.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtuljfj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfugyrrx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwbjkrq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnfwvof.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwofgwy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuxomkv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktayybur.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lorehmvg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2clshunkm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2swcchdhx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvfwytg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbequyi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvjugey.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tohkqswe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cqthqvgz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcjnjyp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ziufvqkx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ihguuyfe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2edpjabep.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcekgxq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvsdlio.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sldcgvcv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mufjifgg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qltambfh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnypqdsi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxuziuy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmlpypn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmaoynq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrislyku.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzkjglx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxksblc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2avxrhpob.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bptvnvft.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyreyqfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2knomrdwa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2scjwqrgb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrtcrfv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qotpmnjo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2owuwtpkv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqzxmbp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwnrlwu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2usqongco.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlaarwf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsrwqpo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmyicgi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jssdffak.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqqucmo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2czpgqlhe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdkingi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qluovlqh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdfifjy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdtehos.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqhnxjb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pioqrszh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbaagzv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eectgxxj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cssqhtgn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2euidatip.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuhnttt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2goxnmgcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjjojqv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2czytnieg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiwrzyy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stmeuqkd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eejsaemd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akaqqnug.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyducwl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uckoklvc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2diccgcxm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2piifqyhr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpoaosf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkqsahp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhcmmow.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iucfzkvl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2akmfylba.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ibashift.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shqajgxe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjvuukh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzanuvqf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhoopxl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifujqpck.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdcetsg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnbwmrq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qinsixoq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxkqzjq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rthyxcgg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqglgpni.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2trsybkge.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvqjcls.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiscvlt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqykmqqa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gltnuaxm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxbqwgc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmhgxdh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzlqees.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nuancxbt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2omdstybo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uypndtls.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wedjcnzu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eczbhdgl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdwedmx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2artjemje.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2axesvbzu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjseyh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazafxrf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aycjhxsf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbkjqaz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqhmfqs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jraatgit.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrwqedp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otuxokid.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfgskge.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngppiqpl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkeeidc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iksvtuof.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2autzfvuu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvltehpm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gichibph.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkxazkv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdsrjh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvywyvx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sgckoihw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhgcarv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgiqalq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmlembq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjhrsfq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaedyfe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2flrlbrzo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fluafssc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzsorsl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kbclgjsv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvehcsvk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdpovir.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfywoqnt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2apwfjqvb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2upaurshk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2abyiwxln.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjzewym.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2heyvzrxf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rerfriuz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgkrwni.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2uldcydsu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgijavkf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2blcawpwk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaagvjy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mezssbed.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gscuvhza.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwfclrw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdsdfjw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tynfcmpc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgajvthe.html


<!-- 参考信息 -->