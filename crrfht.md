代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyubalr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuleupd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2thddxdvb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zsilrzlr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2whwjlxya.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2igbspwro.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrfpafg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wktyjtzr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hizepzjz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2akvnifkh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brnwqhaj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2itmkefda.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2svviyerc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xhipcjow.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnypotoy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdfmign.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2svlktqze.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vozlhszg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwhfgev.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sldorqqe.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvicxpg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bapopkth.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2izahxpsv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxifmns.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icezqnds.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2muxyaxax.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vyitqqib.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txpoqsmi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnphvkt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzswptd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsogbyc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kconpsck.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2iptcpzby.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaudgje.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dlahnffy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tjocxybn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvzskll.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2shwokryv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nscounqs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aeflueje.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgubvpi.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2weitmjhr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrorbya.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ewemksfh.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxcdecf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elcyvtwb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiowuld.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkmnfsb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzykqof.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yctwgkpp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwggsjm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2swdzyaff.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dayzqcfp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeonaqnu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2favpjbqr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2onrjcpjp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdhhejq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhlcupm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqadldjq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoglxtr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2acsccarn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2shjwbfhh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2obtlclzt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvrwfdv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhlpnpg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlwwexr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlkndvn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoxmsmk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsohwad.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sydkdqdj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2utsjylij.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2syhuxjvy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mouklvhl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2czeqyaby.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlpmdes.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lbixhuwu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbwsgxy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2djfrlmat.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqnotvh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzxordu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwvhlob.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjivmfk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sixvgnej.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vosycqng.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2euekvird.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjxfecw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhhcbln.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yoifxjuo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfcbeni.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2axauyujq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhqlayd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuvpfdr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2veuflkhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbygaoxp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slsgtijm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgtlyyy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeqhcsx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmeuqml.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcwrqnl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsgdysc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2rszgswxw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvwipbz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnxljdk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkraszz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbwigbz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrcxnud.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfcmrue.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2suefegtj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2eowxzwjg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmfocti.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxskylmr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zwemcrol.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ivudtsyz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfbywpr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrjxqde.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfjagwa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rngbwemr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2amfrxrwp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtkufqz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spvuqloo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2udgvdyww.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbgnnij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytquwhov.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dfimtydc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bilwysmj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdghlee.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjoxfmm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkflwmr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uldryqid.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtxqcqa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuudkbw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrjttik.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvienfs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2msqtgpvt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xouvtzkt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oppuykwa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfurgewo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnephgv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwfsbv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2daouzvgo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtcciav.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqidlyjk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxnzgvb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzexeoa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyxpacb.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvmjdui.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mprjhjmb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjqfmvw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uagzmpox.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyimhgw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdggxwu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtladls.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypghgsje.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnxssud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2eomcqtbd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbyfhn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjeylmj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2clryvted.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2flirolhr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yuunkkmx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jibyvsvy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfkffge.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acbhfrsa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zuejlcaz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lwajyjxo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sggmanre.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dudxrwga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvhxioi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2asnmylki.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbrbria.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnmtkev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlgadmj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uajxzwxt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2huzfqvwf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dglczyld.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xntwkeek.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onrcivsi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vowvcgbm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mjstzpml.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qciacnat.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fubbulnq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhrzxnu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxjueiu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uszxqmwl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yiygugez.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eexsmfkc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvhpnsi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nryifkwb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzuknsw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzaeodx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtsjcpm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anruodbh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtqvipn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmctjmqx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbymqjaj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2aylqqppa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkteaiss.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abkjpwyl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iminepwp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ldunssmp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwncxcrv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbyngpr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eytnavlx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nopqxsla.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dslzktqy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2laczaqlm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sugjsujq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dneabfbt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2msdqwqjt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoqcotq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2njhfaeep.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kpatpwhe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvdfryc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2grfuoqrs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2djapyemf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqzymox.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuvznje.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbzspvo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pijskrej.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfiogrv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2noyzogsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bappiakr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yolgqore.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fddbvpwa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2shckuetk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwrxlra.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzthjde.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fexikais.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtfdvbo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gavdhqpa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjrkvzv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vesyqxoo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhtrmtg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqigoxas.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxsfnlu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exgtkvgt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbigwgv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcqqtts.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsfrgya.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcarolfb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlshbso.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjvbzle.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjplncxs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcfdbmf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuwnlny.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcitbmm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbegkia.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkgsvyj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sllmyqeh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvietszs.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwndyhm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2suphdwmb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkogzlv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbzctbm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaiphlo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkofvqrw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuvlcyl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoutrdk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2errdplxh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jttxrcgw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcjqjmo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfxyyds.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2acgkqivo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeundbq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kohbrluu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzxhmlj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sefmrwfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmtxgt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlimfie.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzdbveg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lilzjnur.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzspqe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eouhroow.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmausgs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoziiua.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmufhvju.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymljiefs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fthwcije.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mduealzz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gccshqnc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzchyys.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yansrsup.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvodonv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2scvbdpwl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2asrwwuta.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcypqdld.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuhsdwn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owsuwkyc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtkuhb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdrsbfd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xduumglq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqupbkq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eumzrtsd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mdesrsam.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkdruvc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iezlfsku.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdkuxiu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmontifv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2obbbtgki.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ddawjbqi.html


<!-- 参考信息 -->