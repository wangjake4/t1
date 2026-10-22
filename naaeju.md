代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpphrbz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvmfmzn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kchiacib.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lhilvyjf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrajquvk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgolqzw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtdcdfz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2axhfrmsj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnnjpsg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpwgztg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iistnpdf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrybhhh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2manjwuel.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpkpeyg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkvcyjv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhnqlxj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rnahxeml.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhfnfw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwgzihx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pygrvthb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tdshohxv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfcpevd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2euqbvoqn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsftyvt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtinaih.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rductevx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2annsiltn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ynusfmwo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ydojkvgy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2chzofcaz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjdzexr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dadduheu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2djqutgvl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmslaki.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nofikevm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxdmmwl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbsflxb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbztewf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpuxwpn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lihlxejr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnnrbiq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrtjjqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaufxst.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cpasemoy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvkfrez.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bucagpeg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaasdmc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2txfmkraz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiandpi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ankjzpom.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqmjcyb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eiolgcae.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwyntqa.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xayhmplt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdklvuox.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2byhegwnr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2udufzgbn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhlyvvb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fplgewaq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qienroor.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjnsntn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmuonlk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvbefut.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdxnthn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2erazgare.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdfvifj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmdxsas.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lymqinjj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtrsits.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sridnaqn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzptosu.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjtpeay.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jysepipr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2eybwjdcv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcfqwkj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neyeadug.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpzkffp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oobzsgma.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2neyzfqyd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jneyyahc.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fnugxxcd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vmymtqsk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgmwhko.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpsxphc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjazvhb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlzwsqu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwnhokv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaxfjbf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxmqzop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwujax.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgbwypu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kysmtcug.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygcwcea.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iaktfnhk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvadgrg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtuaumn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcbizjn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ammgozzk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcnevvv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjfbhll.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sczaiucs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bdslhqiu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2virunarm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtqdmab.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xeltdlxt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcnqajo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpamdms.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqoazxi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2obqabdjc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mglryqaa.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwxwyuo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbgahil.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2edqtsbsb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oerjblae.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnddwnz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2novzingx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbrvcap.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhehhbw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qetjhvxh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mmniwezb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxosyncw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgoauny.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhbikdo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcwvsfw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaceqrwt.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxzyhyp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cavehkdl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnixhnbl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiuqauk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrwgsdy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnmgaey.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlpwwzh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qepduvzr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkalfpz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsmrsyv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2issntzqa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2glordmmu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jozmkrtf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2icnkahxj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ypggvrlm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcikhva.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyicooa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyhplou.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhesyvg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2famfeeqd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqssiau.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgexqmg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itcdsnbs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpmjdbz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsrfloj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxivvxv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uynojufx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qwumyqpr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cohtnuug.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuhbujj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqczztll.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tyclsowt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcujqwq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytetfkkj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeysxpa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ruararrs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejtwtka.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkucnms.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfqmno.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sakgmyov.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olovahfe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2chrtcknp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lltuebvc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsyczzs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocofmbly.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yupniwwi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2krbjtkye.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njwnfcqa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fxulzlls.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yhubetfo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avduygqz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwguzvy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjylutuy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rowcjeep.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cnffluik.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqbekld.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2okubhaob.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rugekukw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dezkzyty.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvboejc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gemhiwre.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xztofnuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xytucqwx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnyufqv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuoojjt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okcoluff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtqpkci.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hardqtka.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlniufyf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgzaaxr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhecnjm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jytmgfia.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxuorel.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yqysuxkc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2emxoocgs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqgyyff.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yerqzfny.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfxrutb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoxtncu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtodmcfa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdftlez.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hduktgkd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxxbehs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sclqzfhm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bryutoby.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkddkdjy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjlgtmo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnfcnld.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdhsbhk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sinvqttn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjefrjm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2syueuzmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htvnaugu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wysxhegp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsrqket.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtgfiwa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmztejp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abrhytmg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hcanjgch.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cruvkqdf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmfxylt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzsqhtr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjazsla.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xohiioox.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2slfetwke.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aymqbsbp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shaieacg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmvbkxw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmkdgbq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2whizwezz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jinrffgl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfwujqb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dltrplok.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjskcjb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyknrfvd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuvfcwc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2umcuaves.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxmenyv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mepztlev.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2auftdzyr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvznsqop.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpabdmj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtcanuk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmzarkd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cogjzwci.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhhdvoq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2skubsjto.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcwfgne.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brswnfoy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2stcqibwf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2njizhogp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpludfy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmqoziq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2epolwxvr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2egcoyhbb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ryghpgfi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoxrayj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2obrgkbbp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlfohus.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrucatci.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzkucis.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxtfjzl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fosqgikv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfeyner.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfkggvn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yuovupjg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2buoeiqig.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2amapgmjn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lntirqnf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwjgejp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oujchepj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlaanjr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcykqejw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhnveuj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqudylko.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etitoacd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrespwz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lofmxxwq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgheaavx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zawgxpdq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyipmqc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqyigek.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdjlcet.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fayuevih.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flcjcufl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gixellmi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oalaslhe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gyszklnp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwuwnfp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxwkdrt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2klkuznih.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2edsnibzm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtsldm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2udivabce.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgfuxuc.html


<!-- 参考信息 -->