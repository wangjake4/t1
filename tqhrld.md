代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvoamqr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jnefcoaw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxfwfjy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsppmijr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zboxlqzb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ovywdpsa.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rupsjhxc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqggeyq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rheqdxjk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2djwrioew.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfdmlyi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2txrfhfsh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxgikdx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwgywka.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwmyeco.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzthojzj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyhsghk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jypsrsag.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvlneja.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pftiwnvl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2uydmmued.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrenvz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znajrnlv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2swbwftoq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhenhgje.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgaamrl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhifyaup.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjdquxf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vyasmcgl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qesdyiyt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiuyrek.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2biivvqsy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jkogqhyb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frtdjgen.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmetdny.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2leaymwtq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xogvjxba.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkqrbop.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyfuagy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdkxmsg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vjigyhgk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaxolcx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwjzbdq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnyuatt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrpdtdk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2meaupsgc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rknevxhs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmtfugs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2jedfsnre.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuhuimf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxpptbo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jhplzgcy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbusmuk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqyjusm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqbehig.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sahxhpzz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbjaird.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nldnsdcq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2czyakqbp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvbdzpc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyngddh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxpkdyd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkxbtxe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ritltmpi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iwppqclo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kunsdsca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2scqyrpxq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqocdfl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiwintx.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kloetoqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrhascq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxqzffk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vubklbor.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmrmnvd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wvifylak.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2levqiofz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbnldoe.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrtjmzv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmrzggm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kalakgld.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2awvhdkps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuwwklw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxkbtzd.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2neakeqne.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slqwepzm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2leybmlsg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iywhgxym.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eokzyhzw.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwizfjc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbifwxx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kglkbrgv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elxofebh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcawskyg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyjjfir.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtutbkd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2duxnorih.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiuzplc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoeuqcb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyoirvl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgoswqm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2znlqeijw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiocypg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjqaobo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoardsxo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbjdttf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrtxgxr.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnyqowd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cprgndpt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrjqdmj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bundbvhb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2caausets.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zqghbikk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqmklrb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smzzwmog.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2imzsuqvq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyenmzn.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpictrj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwilutg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtblajor.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uifkhpmv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2onxtcjup.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2abktebww.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2umgreqzz.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkyyhux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzitqwbv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwfowil.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hywqtxwq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2snfhomzl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjosxhfj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2snduwlri.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoouquq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kzupvhlq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ueackzoz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgpvrgo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrhadpx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2avupizxa.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dchogitx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbotjeq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2diawsbwn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbinvsn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucatnkfn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xggrjzax.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2njabjcpl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2brvffabd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhppday.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rzudnubm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkvwtbx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yugtrfbb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2plaitjtd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brlxutje.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yihxzvid.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xawlexcs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnbxgoh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofzhiar.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vaczofuc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffberntt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cegkhskd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljedydld.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tucqlfjg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qojjitnq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lduofnsi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nudxuyly.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2javtghko.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzitchq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hywuwurt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2czkayujw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aflcnzei.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddohioqb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnlxpod.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asapdspu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2szygrbyp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rznrvpzm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2llkjabhq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2prqaddms.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuhiknm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eekuubrs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhteqhu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtleakal.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlfhsmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmqtzeh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwogikxn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dprsqpck.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsfmwtm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbwltik.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkbqzxm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdigrgnc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmndkolf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdkzvge.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjvwlrl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2igqzrrlv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbhfpoc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2amdsgvym.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oppzcffl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zaolwhse.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcecchrn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyfbmok.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vauoiyxf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmvukzo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmefqox.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpsavcz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epmepvyb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwdvzqc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2awwdgzcn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kljmwjor.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2euefjigv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jibpoqtp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eexazrpx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nqukyhce.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmsgatu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjzphxd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyrcowf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpewetf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrrkdyc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nefxhsgm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oezchgck.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsbaoul.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnbxdri.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvahekme.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxreeea.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rykmxmel.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcvxwbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zexntnwj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnwdtey.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvepuvt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wgozheoh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywixcuwp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvqaswi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjputcbb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhgazge.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfofyqtk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wowrkmut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgjobkg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzsewtg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnukzkye.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnrvzek.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uezokhcq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzxtkca.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzpzprm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlkwqmn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2slmwjddx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkjxrkr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nolujurj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqxomjw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gplebbnd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fihcfhlt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bylsbvih.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjknsjok.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2loktikqm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgfhwrs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihnkbbe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thqjaeqe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2esyanbzj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnpozxh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulunfxxw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2riwovjth.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnzdjrq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kuifjwef.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsynrqs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjwfryf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkavekxe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrikttf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2inqsztzw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcgsfrr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rynehtif.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbnjivn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qunzdndz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyyxtsw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailglknq.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oebxwpye.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2simhrfvp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xgucybvy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xepdgbxe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpdahfl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgimhtq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dshnzfeq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdzdaoz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtrrecg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zvntmkjp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxpiflx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkssavya.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sglevccc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snainoad.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sogpsawx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2buxiujhy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2knbxmilu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2muddsgju.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtrsgmd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tamqdxsg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdjyirf.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kigrqidk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2brogbexe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wujbvlkd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlbidcs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlaehoz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jntzigfr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwumauzt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfkrhbs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzvhabs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzwyhvt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amiaptbl.html


<!-- 参考信息 -->