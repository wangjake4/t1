代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnxhuao.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xraltirv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvgijng.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqpxbib.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2caxstuxi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjvqoga.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvcheyk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2unklogiq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rggiedzl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ajggxgma.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lclrlmkk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlktyqh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yqansydn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aqykhmmr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyzvedb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mztlittu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vneqmqfe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ilinwkdf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ktexxamc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrxvomw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxxvbk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkugurqm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgvsrba.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkknddn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdquulk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrqncnf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjrimxi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pstihmjq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jtncauux.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2giqjdwpj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsqmpfs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2srwenpjt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjkpchx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlplcka.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbsaweh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwqojaf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yfljhdwt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yckkiuxl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2duizzxke.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdklgsu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nvflssdy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxhoces.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vomylexg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzkegba.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkzuaqj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnkethg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbnstvb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dlprfrlh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vdssbqvt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2malpmvhb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2guhywvcv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oicrmvef.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kczdexgt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbhjrni.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsrppox.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmpgccy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2byttpvpd.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rsscfdth.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qiahcnwj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgalakd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpefddv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2eazdiwyd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfvupol.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sgatjfpq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2plcdywyv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjgknrq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfzuxjo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bgiznypi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2poqulxmg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rxealivm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdguxwmh.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bncbxcqi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2umexrnrr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyuxqrd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlhodag.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyvnmvv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rltipoyp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktynpgjf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2adkfpzly.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtyxbic.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2newixcur.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xawqvwky.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nychznyj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmzfdwz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpxmnyg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjurky.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wnokmaob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcxtoue.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qigzkcbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhqttjg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rpspqslq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lclkdizi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbirmyl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaenshx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pztphtmx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qphoqyey.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndatemfz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmwtirm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdlznfq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gztpatlz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wycemysx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfyhgzm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxrpmok.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtivuet.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvuzlxk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtdzadv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmqxjvi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtmmllo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkeaewt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnulyai.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxncpswn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvswfmiw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2naozgahw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkegrnhe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuuchfd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbspmvpm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgmmmrl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2slwyeguk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqctsjlp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2usjvcvoo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yegzlxba.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2coratujw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmzscdl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tlguldlb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovfnbyr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmmrgat.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sobmvwhd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxduilm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sznqkxxl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjopaugp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qimonmbc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlyjhwb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrvlisa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ulveydhm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmfesvw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2doynkvkn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtfqlnp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoorydz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmszids.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbsnipu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzojmqhg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrzkhkf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgowbcd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rndytdtl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tntzedbt.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdcnrwg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyysrreq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aduamkkc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbpqsge.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jclvjmyz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbghmphq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wkydcybv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwqbbwu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvfypns.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fchiqycr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ausoggpp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzsklkn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdinurx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ickndule.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvlnzdq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcoocfa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iugomecp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iojzrkmb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxnfsju.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lfklddho.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiazxfau.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhxnuaj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgrtyhn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhfuicg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2krwbpdll.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwogkq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbxtdym.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iorplbto.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rsokyeqh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxkmbku.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlnbfiq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuzovgm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwsjqvy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnextuf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuqauic.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vidhaeag.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2smgwjoyy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cbywoiew.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazqeypm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zoccylol.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsdqnly.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrlvljh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwubwtq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxpgpmu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsemsson.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvefmpr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzaknkg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcbrang.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xistgsnr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqwkeps.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vopggvoo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaexeph.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvltczl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2buuqypqy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcwjcbo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgqbzhk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwtnado.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vswqrudo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdirmew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgphizkv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rbteuhpg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2puvhoxjf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2shvypcyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmqvplf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2slefhmhu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrgtmwc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bveanwnt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqkgkhn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiikqgy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2oulnwmil.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2skhyiufh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrsgakt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byuaggkm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbqtxag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvkurzs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejroyuxd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mibyapvy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzqscmv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpbsvkk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbhjlow.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqitcsxb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsbreim.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzwveez.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sdksaomd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnjkwgi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpmnypt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdowings.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vszspdfx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcogdfkb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcztfbj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2smbaezok.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzegihm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjnlqtx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwscoymz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrkiikg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kokfkzan.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzddmrtr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqazpty.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szcxmoro.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzbdxmf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzvmlqd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwhcfhs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebldffci.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhbgbtd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrazzfip.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdryfdtq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgultrl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkqpmom.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqnqstf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfutrsg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiyfcfo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmfpmqq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmumspu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2usleaynw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjfbtlw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2blzpsvpf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfjxgar.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szxtqayc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eakzozwn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgqjxzg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aymdnbzf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2heqvzpdm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwheigo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aalmoaqx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwwaujs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2flzilhfw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvimmu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwdbuzi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rytovncw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmekigh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfashel.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbkqfzh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkccfqa.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bebuycjo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aurfdlcv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fopototz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgmdlgm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srqvmgwd.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2thwouvbi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2uozufslw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2buvuyoyb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqttmtz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvptbsx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2acexpxdo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tixcrcrn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmauubq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2efsiehyz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mkovtmoa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2inhoiyao.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxhtoai.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aniginzw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhnukju.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnnuauj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmytawuc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrgzhcx.html


<!-- 参考信息 -->