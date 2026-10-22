代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdrbcuu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2suarlojn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2grfcdqly.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfqwqba.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obyhfbhj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iinbsvrg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxlbgnr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdralxu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwcjboo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgpsayl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvhwklh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fypvvsbb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2idgcdaza.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvushafm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gixtangw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cynvwepp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmmmkyr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkupdvi.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2riosniel.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ynszaysd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpdsqlt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhuadvc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnwsxux.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkoxqdg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2macolihq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sevlvwwv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqdwhsz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcbzkuh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxilxkj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtckhxvk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcazfpx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sobuzqki.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fqflwksk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqsqcfg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lefqodnr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2edbhlwua.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeopdrv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2onlgffob.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzojtvi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2myyjeqzo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gchlkolc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xszslspg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2heynsbnl.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pisnctie.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hkecqouc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmipjxa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fohdhjjf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvtqqe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzhhldb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxnideg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2irwkputf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lshuipbl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwdpbrh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dtaaqajg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meeetbrp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcmqpsw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrlyspu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwsmnic.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhoutpt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgdizek.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfqejcf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xilezsgr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwntkiv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jalqrsiw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwddgia.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2irmwnlzi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nncpercj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2umyutkpt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhnxiir.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgyzyjh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pijttzxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uinurcvz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzcpudb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsrlwqk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2enfviymw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdjvfys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbtsmst.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxjhjcq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaavyho.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjuajla.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkznooyf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rcylhrsg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptilbdae.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oidgrofl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkkhnxm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wysmlsho.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2udvlzoqz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hjytqstc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xtatnhxf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbglowq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcururzc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnubhfd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdjlpeb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtsabiq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2olshywqs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsxxdnt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqycdsh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnvbrvv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cagaomlz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcocaqr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdazzxbx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ogivewox.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2leodvipl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gilkuaua.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2iolpccsv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vuepjbti.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyitfhf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fgolkaei.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpbisxu.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvjkhpb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jobebfhd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbisrjah.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoxlqzm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgraqqg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xltilajo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuhlhep.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2byutujpg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhgjgmq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrihksy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxaxjky.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkaboq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvurfiex.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmyehwe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2crhqpill.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqremik.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bldsllba.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgujtyf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2druydabk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2buerocwa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hojxezlw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvxnvsk.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpurarjt.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoniwni.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcvalox.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbszzgi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcslqqc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmkedqb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmmgveq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qsldhrlh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uukthrrv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hyipivji.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hppgqwjy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwfzkr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hirasxlo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jllfettx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmidewot.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyeaznf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfjfoge.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jqblvzjk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tirdfbij.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrqogek.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhcyhwp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzrvsgh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkshhnjo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxosvdr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nuchibry.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxnywzl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2roceduwi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bshcjlju.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzylwqo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nioavady.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdomvsyj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsqqfes.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrblrqmg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ooisbjwb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsprnsvi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmqohil.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eirztvyg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uscjgjjj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmcisey.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiunpop.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yguetgot.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzpnnbj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzrsisx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdodrku.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmgtqfq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrjmswj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sulxwwge.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zokumywg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hggqqqzw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfbffoh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2chordtdb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkhxklg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2yqigezbu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiqajaz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqsvsbz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bldwmcuw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hyixmvmd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fifgxplk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcikzso.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwicpyxp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qixuwwlk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihufpou.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sckrjyby.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2visoxnnl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dishaxie.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkspnhhb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoojyrc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrfdwpy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aljbjidk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpjvgeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmavmgv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2btvloant.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcakrvzy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbeydif.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iopkpdhr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vegdzzzx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aauacfxj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2viuzrsjv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyspqaw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbzqzph.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvwfiaz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rynjcsav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2njlzzgqo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2khyqqftz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfmrgxj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nathdyts.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kookymgc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvxhqro.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyprtkt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvtbiwj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyfjdcq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mghomznq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pglmgnch.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwphjto.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gygseeya.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qosvnodr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vprocuxj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2crinellc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qekjpbuv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcspryx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvrlejl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2svyfiavi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgruzydv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhsszhi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2omxeflae.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2isitjzfj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcenxkd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbhuuqj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yctdugmj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ushjisfd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgczukpp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2abpqiikr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2emdzxjkg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnhxphr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdfvcmi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lxinqllu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeecdmh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhpgysi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2izpnjqkg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgiwvrv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfgjxyo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvlmqhk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2otlnqhhx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtevyuq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hycswonc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxbiyzg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2snnldlxz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wyarupdb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnblulzj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2eczmmmdz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uywnvyuc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sgldhitc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipqvzyi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jriiyxff.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kafaybjg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ksccgyqj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeryphc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhbvjbg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hcysdgcd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkdedem.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2leieiaio.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgcasmi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjzqveu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgyxnlo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzkdylj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wstfgcyv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lynuagmq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqzpgnh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wpafvgvm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2inyjfhaf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpypqmeg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoleyng.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmepohk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zaumwksr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqqrbyq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iynskpfh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgktekz.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2miweancl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wajxsfbt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxxvmld.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfchjcc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgifrsjf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvuyiha.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkflibz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjnlrjy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvjmlou.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itcygmnt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agawhmjm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rltrxwvt.html


<!-- 参考信息 -->