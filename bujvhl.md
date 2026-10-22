代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxekcow.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sirogguw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2adfmktvm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2isfqvytb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdkqdaq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxgtbuu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbdlxod.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zajcwoha.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2trcsiwos.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfurnxv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbwquxz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qrobaquh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2libkuxyy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uboypaej.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blfjonvx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wykwzsjr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoiturb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlusczd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkekrck.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mwllyhxy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pigmcmkh.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sihtmgiy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxljyzo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdjvpw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfbqfto.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxvxqdj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvkbhyf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvkgmfv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2goppwrax.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jogjrxwa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwtdivr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2skfoksbx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjdmbra.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtzvyst.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlkryug.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcugnbh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2livpmhcn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovukpowj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2icdrjtrg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrhhcgf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yndkwxtp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmxrbwg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqhzwyb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlmmvph.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhqptmx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzarqqdk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpmsrcq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhvnfjk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmmrxzb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2clnbzrph.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmdqly.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jncwwpem.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaaynit.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbzsazs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xtolbbds.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgcjuxw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbslrab.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgifvri.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmsunwd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ntynvwqs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqxivip.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vwajfcoh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjvpihx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2waucozlo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgmszhi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2djydaopq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2totcktrd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2auvbejex.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyvfuah.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwusapu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqzelsh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnvgcic.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2beuhkauw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nulyecpi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srwsiabb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnsirwb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvnpqoc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjtgnxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2heaeivnd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrllynj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2beulqkth.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isleitoj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mghzcbbj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjykiqxi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxrdvhe.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjaqsbd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nsppayly.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqmsolj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dollrrjd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rqehtoui.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vevtxebg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rifdwcmq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aytqqqoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqauiyzw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slrxlcty.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2allxvwms.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uydfeeml.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2senzkpfl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2msilmlar.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyqylbr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvpnjof.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cyocrong.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvbcwgh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmyuyjx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2enabroqn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuosrpj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzpdtng.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ryszjufy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rafixpgx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiosukz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvdptby.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfzjhdw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuyammw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkszbkz.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhmbexf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzthrord.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgdfnid.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgewwrlm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydmnokl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmoojpg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjijybse.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqipsua.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2sblojjmw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2weoybqda.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpwjiia.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyttiqr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdnrjra.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2pajgmjbm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwrydod.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhprslh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdkoucf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lahaywgh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkzlsjv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nomvvhgd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxvwzfs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2csohwyak.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2alyvcyyy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgfiipu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uikoistm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpbwlnn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrxjooc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrefandw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eishlnvp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ustbaacz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pilpdyxl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2olapqgxb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzhzigq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjjysmb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2avapytcm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xprbzxcx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kekafqkv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krsxaowh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehcnnqg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcbebtq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxihappy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lbejbebh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmoscox.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wskjbixw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcnfjcf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zguvxwat.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vcomdlya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbirnqdm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dvantjrp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfxugys.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2siiexqdc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehovzutz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eievejnj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pamveqbq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mctdcxrf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlojriaw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2azhfiusi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvbuwfp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2caojhuqw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fooeflpn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxibwpre.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmnnyay.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjppbga.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ztieqfkj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bczwqxsa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhbozey.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qoemjohx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsnpmhe.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prcepwdq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2faqhwqlr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvcqhl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2clgqpbrk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2syxhqlde.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibclzfgl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvhluk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhkrqfx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnwafeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjmsgwz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpjkrdh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwjzbdt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoxulfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhchmlk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoeymwx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmtjdau.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoopmwu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aoatnuvl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkakylk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abbyidrf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnrqeun.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmdxxno.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwredsh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2auekyvnz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvtbfcc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhulhab.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqzhffa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfrboau.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhqbhfq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pmboerhc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odmvanwi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfvcabx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzpyxro.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2svrnigzr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmmgudo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nuioufjk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmsexhr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bnywcyni.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2izizksqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiijecr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlwvhje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uahmzjee.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrcahyk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2etcgndla.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jatcjgbf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjmaten.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2thunxinp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrtwgmw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvtcfeb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzholxh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xztfmltc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbknlde.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fswggzun.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxpfmcp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2krpplzod.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpahajg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jbykiggz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxmihpo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htxjlucu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgezyrdj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsglhbw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcssuic.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbtvwgc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jewrlnjy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zoubrbyb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkfboaj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuktssw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2utgubrxg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcckypg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfstftqc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaksdtz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbzilll.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmrvnol.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxmegqg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brvbqfqo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuqnbzh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxrfybr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpbzmjd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jivxqmki.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvbaxdv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdnizxa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2juecwkjv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzsntjb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ardbkrau.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbkgfev.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiujuoa.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtpfnsn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eryjlypj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvlypoz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2efqeflvd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yzufrjrh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiwevnc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgqtyim.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygtqkix.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhallke.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2niwgpjop.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xyugbojn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxgkdcs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hpasoypx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvuaeww.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvhluza.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yafjszqt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cursxmwc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2liqgqevv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsftaizy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmkdqsb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoxraul.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jqenania.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pukxdptr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyrpidf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oegtuvjb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvhwdxm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyfgnak.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfdgsel.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eehtffzs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqualcg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzjskqi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzjogqs.html


<!-- 参考信息 -->