代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvnzopq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2oikqnbuz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2veasiwsv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsalefc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvazodz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzatgue.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkfayin.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2opamzwjg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfolaax.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fczghdzs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqygobq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwokhcd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcekmilj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eurremxj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elfeyeaj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoqyzfb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2koonihjq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfyzrdv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agrkwibk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbjagfc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ueykxsda.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2bogwandl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlibtwk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpxuusc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zkftqloc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsscgfx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mewilhih.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsfdldh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzyrqyp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfyysks.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaeymar.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ciutturr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pllhhfej.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvslzd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyghbzm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvzqpwg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcdmsgw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeykpmu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgwcqnj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwtvrvc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxkyugd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhxpwqs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2djqganre.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmjgrpt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrjxscb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiwwknc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sabwxfvf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyqcupt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnutdak.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hksleqka.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhabdrf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gleifyyj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dimwsfpl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvprmep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqlanxy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyehnbu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kajasvmf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnuajlb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tahlgukv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yfymtgck.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xklpxsbd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxxxxon.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwbouei.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2btzmzxyx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2urcipvnt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjykjyv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlqveud.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uahlhfgx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxkegjc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwicgpg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wemuegqk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmynglx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrunedd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2axcinril.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgevxtl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvrcxaz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ombzkyxe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdicvvv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmheusb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrlrdzb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrkztmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgguxid.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsyssda.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cafoswdm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbrpbwf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iugyndbi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbowtxcw.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2auaubinp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sabczjvh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cstgvcmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkykkgca.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpuwgkw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wusycail.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2olrsyzle.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qkohuqim.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnmmfxs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxraisf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sddwxrtp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2clgdnhlb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vngcslmv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrfgswr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oobzsabz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmohmop.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lczmjxqu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoczaxc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcnbzyd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2unucheel.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmovoctz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmnqgmf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmopnbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxwntg.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyyyrxt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2exwobyct.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkttltjz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fuogsqbh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfmwrjp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wphrqrcr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bplrkdjc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjphpwds.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyidtri.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbvsxma.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwaaxeq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrdfpjp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2epvretyq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfawzuh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2srmjrmog.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qexubgnw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wertypjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvsados.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaytykw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkdgsyu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2alqaxwfy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfytiqy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hskrmocc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvafccs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaoywyt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgallqqp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrmueyd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaqvooh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudofhd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oadlraxx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsnxuxg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2plsdlual.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2onofevts.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2acqdgtpm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgyxdui.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbrtcbm.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qnirzuwg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhzddtw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqtbchg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdclfso.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbdjxwa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tayftbvv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkiuaaf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2blryjbhg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxujmww.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2prvukego.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkthmadf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnughua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvbapeb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2cxytluli.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhagpls.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2asgsijzn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbasfyw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfceyyf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sixvuopr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmmdxom.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvdxzfp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaxilgb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkpnvsz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxesaaki.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2davsoihc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlymmwr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgidgejj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2eerjvsfv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exoypuyw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qkahocet.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpmahsu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tdacchbf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pchtpxvy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bklwepeu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbjwmfh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hubncwqd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gskmrqar.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vevsruta.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2komjoaem.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2elnfwkbt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2godaigla.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwjqcov.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwjqlih.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqjbhtk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2doucdcxo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svjuxftz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2swxltfuy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nirsoeer.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qqulvwil.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielbfymb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vfubqxsl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cutjuhlc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hfekmpxy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuirzbkw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mveljjwu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2arzppcxn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgxclwv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2skezfvgd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2immbozbd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfildocj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtkviqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrdeqrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyrjgxa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoboaao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrzyfto.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cvypynue.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlmbzih.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nynhbvoz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdufbkv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnlsxpz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2raqzsyjy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyoyvqd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2exaudnvr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgavuln.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgnzzhp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyvhrxl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2absdnron.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzegyvf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2donapujn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgeoykf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zadaiweh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnmejja.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjwrfab.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwllsdxq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2awxvymzb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lonksxpv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvvcivm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2orqksnjk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxesvix.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2phvlzrxr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhjrprk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhobcmny.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyutyzk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwnlszm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkqbkrm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktekgqrf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrdzzxz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjmuxee.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2legykbez.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaafeip.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlbluhz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kohrncnt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfodtbd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nvimnppm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhehycjx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhmokxk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hymwpuyb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qzshmyym.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtortco.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kngfztth.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2reowhzmx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcsuhvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmkmabm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2diinazrf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2szqgiqmv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pqimbysq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvtlcde.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhjomrr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpofoanv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhfszie.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfjlbhb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hhydoryv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvdizcr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvpkaym.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbzvlsb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wavwalrj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgdrgxh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoxvocy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyupxme.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeterak.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyeyimq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqfsord.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpuxnql.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjhnodq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wehpxxxc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jujhqzji.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdaarpz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2txobueco.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjaolul.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsibvzkr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2chmfvxcf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pddnynxv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2biemchcd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dilsmjhn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvanzmj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xqadqphc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2phtxnska.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whslzckf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoxlvoh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuqbtgm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmuigfo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxwkhof.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnkjcqn.html


<!-- 参考信息 -->