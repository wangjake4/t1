代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2igiqzvux.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2pztxmzui.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdfdwsk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vonbpdpp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyfejcd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2opgxecvv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2slzayadp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjcypcn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqmquyi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fouerqts.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2moxluoab.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnepqlza.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abuoiknq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeammlk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2giwlgolv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuboxvr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2koclvgfs.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hrefpmkr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kulcmjez.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kpikftgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuknchy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbefzniq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzbxaun.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqqhszx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpkvcsi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlwheqv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnslaqzf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbjeoct.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rfinglpl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2saasukvn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpxcewz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2eoejyzid.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtudunb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxlmkia.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eibtlabq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yfraiirx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2druoxkmf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xseyxfwn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ldesxulf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gbauqjhj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfevozi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exlswtcm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqhxqwx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtwhhfu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgiocyb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaamese.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbysetbr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjbieim.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsklueo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyfcere.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2faufnbwl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mevbegtg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yszqtbgx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fftmoxel.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfokkzo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vqghieat.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hgldzoxb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvdtbqy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2odhgqptq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsddxak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouizvohz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yzurnufr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmhxnhd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2favuucij.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xubhalpw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcutprr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyweayh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xulhoijq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaheqja.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaomtnz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rudcebiy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qprhfnqf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wnextcmk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtwwhcd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfelqnqt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ttogfoie.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxrlcla.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2slzjumrp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iptdnkmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsjiycn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrwuguw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaditrc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmmiksz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtzfbxo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqylxpis.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaanohd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmggmow.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbwkrpc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrvaqwl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqvlcxi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rozromxh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhcugbz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbacits.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbstcwt.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpapgpm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2juhfugzh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uppsfdrv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfwnipg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2azixbrrp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxreojv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lqukktxd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmnoain.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2havzpbnb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzpfzyh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kynbqhet.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjqyyve.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfxjqnz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxurzsh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvfoydn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2loqoxhhb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxdwdur.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrdbvcx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yinqbamc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjosfby.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomzrnz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2oshgnvat.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfqwlgo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhakdaaw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfgpmnf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkafhuk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2efshdgpa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdfcukr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hligxblg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpxeumm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2smhitpen.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2alcsqigr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjjhwbd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmuuscl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2egjcqcvn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiymmvi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzkrded.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2igygyjzy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvelwumb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uczgicid.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdewkxqj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lfovtjgv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfnswxt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcpufbs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxeeclo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzjgofx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiixrvun.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzvegbe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2owowywco.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvcvxnb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnjkwoa.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyjwepm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2odomlsfx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trvlqrup.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxfihhx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frmjiweu.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwhocsi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvxldoz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xusrgljz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klpqorkq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqrmqeq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrtqhda.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hckfxudl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejssaqtt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2riousxlq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naftuwrw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxuiiqu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2robqokny.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxqtfqk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bupokzcr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xewvvgig.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2htkfvdmy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrdqtod.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sekktuni.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aufxomte.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ctroaayj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpodylhj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwebjrw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tnustksz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgywcrao.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdpqzqq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzibjxrk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsfpcuk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgsebqa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnsantb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mszddlzr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2racoffig.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yygksmtn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ohspexry.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfcjjfj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2laqjeorx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tudbvkzs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgeyqsd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdgzayv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icwtqbcg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2drskskpy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2svqvmvkh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvdobml.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkttnzcc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ususexxc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fktcyeab.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odyspkcf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lweewuws.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpgxqlh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrutnas.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwatgqw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgalsafs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sexttweu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2huzrujzr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2phohmflk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsqmqpu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vybbbzzo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fszrqlbk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2draehvai.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuvzdos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwktnlr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgvkehs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvuvbwc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvixadvg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2alibuycc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnyppso.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrwtscu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyjkljh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzaylo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xfurbchh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qowdthnu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yujntarc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtsnnag.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnoryxx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwoktiw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aadpgvzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnqrupy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gewkoggf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgnfqzr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqydlcwn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2trkigapb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idymbxgi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2daptkxip.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2escyxjnm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldoekcp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hivjaxic.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irsddtli.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jtorkgmj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrnzrsd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfzldtn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mavbfxhv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmsdyei.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxmpfcx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ieknrcop.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcsxtcq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgouqnat.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tukuawoq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2goxfjunx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gyucqshs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2orgudyej.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyobqwtc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwshurik.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2watcwgys.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzpinin.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xidvhbfx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sijlfupi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtrcqij.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhgsypt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqpipaj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhylskx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhlgsqw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfdbztj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyyrcku.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuidgkl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmgiero.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dlujiyuy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2isitnhxp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgsvxqo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmueugby.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sqechvuf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqlwqdy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpdqjqo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxgdhtd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaqqodr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvubaasy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2avymnvlx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mumadenz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgtsdbv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvjnxcu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjejwkb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrioqje.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvvyary.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aaruovsq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttusnzxm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrjgilk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdlqwbb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kscoapsm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thbegtyv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozavrtcx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyruoio.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rewqxrzf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcnkxbb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lgflkizl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxavuxx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcphuyd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stpqomoi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyodikl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnyxwkx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bopbvmnc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxhgnye.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxjolqu.html


<!-- 参考信息 -->