代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jyexptzg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwldpsux.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2awewtaae.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2stmhdatt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwqcjls.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fbntnxfw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebexabzq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdvajiz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhmzgzn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ytznqbpy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2matcnuzf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mprxosag.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qpliygrc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ythgskkf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xycttjhh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yundlrga.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmakmfmz.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvurblgm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmqgibt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbotgkbq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hfckcyla.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwxynpl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szbpcvrk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dkveeves.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xzamdoss.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2chyvaygo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jurvcdzp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xopuwxra.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsnjnpi.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnsliaa.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duclvsoy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2teeqktut.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmkvlzy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjdxifw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgbcnlo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwthopj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cazsfaay.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mevbmeyb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfpbqcs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoivkjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuievfk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zldbttyn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdteray.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtqiouo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pybmbyfe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpvgmxw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvfabdc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwnscpn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nbypjurz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiosjuo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zglmcylf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2esqnwcix.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjfhhap.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpyorgh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwkipsj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2thfuahht.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmfokow.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2axzwlxaa.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ditdpqmq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2plfjgljv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfxxbrk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqhtkcd.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sblykfvj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzuzifi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wikfhplz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnnnsmj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoszkyd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxwevpk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jhburgfb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dirtpheu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vicjripc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmhgpvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ektrowph.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cizemfvj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lecnryxn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vijxwfth.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrpnlye.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kglnwisx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gydqxwsa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkpknas.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ciejxgsc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlibckr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jozppfzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buhypfnc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxynvng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpobtri.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2egrsscbi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ywygwowa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wihvvpid.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpsuodf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcgoemt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xobyulau.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqczbnl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eqngseuz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzilctx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dcihiisp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhfsmxn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjadtstc.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2arnxxyjs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsechnu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iprugpjr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2varcsdha.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmsbpgp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2igwiyfze.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2atctxmeu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2agsediaq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2beuxbdue.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iykyeaye.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2llggnpgb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2owsdogpe.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nugqfthx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqoampq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ateoysjc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfmhivq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjtrzqw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2evroehti.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yikssnzl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcmbyle.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kjchvldj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nubfnalm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjookqqy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwnrscd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdcesfa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgldmmnd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cutlrida.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrimssn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2olobcgeb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qjotydgk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzxrtuw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qbexsscn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmmogf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrxvtbq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxpalrt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqdpqhb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdatfdq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2meqfnxey.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyfjfmq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdcnyrb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2plzuybpb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjyvtdw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoejadc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxgdpdc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2faibecpz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrnzmdo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2axkxruzt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlmqckl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyapvooq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeezjzm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzdbter.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vasimllh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mllshzcv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxouuhn.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2whkwvnhf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vckdjbet.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeajnry.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfgynbi.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2symilztt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2odcgfcll.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzstvjt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxbalcl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pobnpzny.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkndaps.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gugvunfg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vowfoynz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnsffar.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klayvgxs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnuwaok.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2elrgfjif.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ihffcpia.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsvtmev.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnuzqxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgkqvux.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyezkpo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpzijso.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoxbjrw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnkpcgy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjxdvpc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2axfjcrxn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cyloqyji.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htojuuyd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eofcvwmj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tszxwwky.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzsnltc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeqxygc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyavojx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcctuas.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rniwwejq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2edncnwap.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnrzycj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qalarbyr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2edfdgzap.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfujlet.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tesxezuu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzswavd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrdchvs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mdphqlmd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhniehc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2huhsjyfo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2itwcitwm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2evzrjqpo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2asuntfbm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2joknvmzl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrftijp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvsfduf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivezvhw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqwkbyb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tubmuati.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2resdhkbl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpgsqld.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eekxlher.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2idsdonjn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rodnuslt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlyyxri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epqtrptr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeonndj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wszrxvfb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsizfnpj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2laafxulx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wchqxulu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2eziarvgi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sigaqsuv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrnawvx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gbabasxh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2milcjksk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gthwfbqt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xonkblsn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvpxsvw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2limidcvn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgkehql.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwparis.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lapsalkz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrapxdt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgtqvfb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2blylzgbj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmlxbk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfehjoa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvnutue.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojydkhs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyjazwx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pckcljdq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xexorvee.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsafhzf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uodfjycw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pduadqpu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2attcsgmt.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqunmvwh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dcucrnwb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2myfzvgxr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zywxkpez.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtxqrqv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2alocolek.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bflyvwim.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhicgpl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyfgrom.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2euvwnsdc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2towgzzwy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hcquzcpo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzstgjum.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgubiyj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyhwdgn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaardkx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndndmwye.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbqnywv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiirppp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lheldfia.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqifvbtv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gztopgqe.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxwuhss.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2crnfnczj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbppbexn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlikvfe.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqoznywo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uisgbiwn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmtlemr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ivysyzee.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2etvfufkx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agzkudtn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkprawp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjhgyvp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxwwqrc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcopzkr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2snzcuaro.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2piaaxajx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqudkba.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2unbbhpky.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfftrrx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjhljly.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fumcxxom.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lknazvnc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2glwypnco.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwswpyh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrvezpx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yuulapca.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwqljeu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ictonnzl.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2etodqmro.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmqpajc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdiwbqn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eaowvgql.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmkxhok.html


<!-- 参考信息 -->