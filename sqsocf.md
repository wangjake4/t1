代发 wailian999

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsbrwwt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2olzjkswl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiyeome.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtnhujg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbdgmdc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2llcusnlp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bkipvivi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbchbyti.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggistapl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzjkieo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovudmtxb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyovieoa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2booxbcpy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvavhba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrmglaz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cstzzofv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pyossosm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwtbwwd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2heuuvuds.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuphvgs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aagzzsdt.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dticxckz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyoqyjp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2barxsvbf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yirhejjn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcfkjzt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqqszin.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmjhte.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lstfqfnu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veeivoaj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuenkiu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2akjdgvnn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmnqjjh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2perrqwxp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qaegrbss.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmvhees.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpvudbf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzcqgbn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrhphhi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhuyjaa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvzwwrt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkdvmny.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggflqicq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfqxcmf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrvxwem.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oekcdjxj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrczcmu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhigqgjd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzunfjf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhyiotx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcddjbe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2alpnayxi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2znjvkxtt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cniukozf.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gylgvwrm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2brcykbgw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwlrraf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbolnof.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xjssibpx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2snnycwvr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2epztyoho.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbpuhum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awpkubuc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xivemezu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nctujhhz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znfzrkph.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ddafvtxy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkavezs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnnsfrp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbquyeu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcmiayj.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2alrymdvn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqssahz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uaicexoy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2heypjsce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmjdmoi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdjxhcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcbgkkr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaaglbl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2uovgvmzl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pclnefai.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmqfgwu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmupppb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpgltaq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytijxvop.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmhtmhh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2afqvpecu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2whglxnci.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaickyjy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzmirkz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rgplfqua.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvkgtwq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hapddlxm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnxtatb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsjdymy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotzbbt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wemryoze.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2twvcmrcl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aptpkerm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2arhenxjp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2irxstkxj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjikxym.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcarltds.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtmzcmk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmdijyw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqvkdke.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2htxqmrih.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2glrjgcws.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxrcjsn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuzplsb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kasdgfsf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkmdmxx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mradbrwb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cadbhkag.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aijjsgia.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvrhqgp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qigqfvqw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnazfbv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmqwjlk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuuirxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrlnwlu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvwyrgl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2huwogrrz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2llhjqzht.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwzlqvb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdouxap.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuzdpwm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvsyxoe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2scbquywy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bnezpjtu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxlbuql.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xbognprd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2injjsnoh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdhcaga.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeshlmyt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfjgvrr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aghfcrsx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrsvhyo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyomdedu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2swbfurhp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2earxhbly.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kngiaqnr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eibyzkcg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2akgiyzws.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmpxmrx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjydwxkf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hggjobhc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2enhbghgr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyxxlqs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqebzxpz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbtxbob.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzjevex.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwuddia.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnshkn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2xejogzab.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itbqiczv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsdujrp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rimvbpnf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zubfhgez.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvbzndm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnwrksv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2oztluanm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qpztyerc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfvyfza.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avdipfup.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gztozqkh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xguiqnuc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrtmbgu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pkohtxvz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsispig.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2htjijygc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yifsvyuo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2twddxkqj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcybenpr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iosenins.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyrakrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxwzieg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pckjnbwr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2beqqfeki.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2efvjlrog.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uecwspja.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrmjwcf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2izoxrbtj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuwbyih.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaszouo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ouslnjow.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfisbdu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvabprk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuaqacd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kteiehiw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvgyygj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2piimkkts.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbtsmpe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqlnrqg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkyupau.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpuwxnd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2briyivzz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnurqdpd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkjzoxz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2emzfoloc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqikwah.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2raialtdq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtklajfy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2flycleac.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjchfnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bayepdyz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqccbyzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qygpguxs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htkachaf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjqsqlo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eolbzatn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ywelqsie.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qajfjjdf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsjrreb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uccwnayt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2edrpcomq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yowhjhnm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfostvm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdlxitp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drgzoinf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfcaitd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkzcwym.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2htnpmefc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dclerljv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxusdaz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmoxzbm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdcerol.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbagakbh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxilkwf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgkxxik.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hziwmpwb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrvzgj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nofobmua.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoeypmp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dngwjhbs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoxfjkl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdexenx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyeykvn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhydvjwe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2riswjjmm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2raparmff.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjbfose.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpvhbul.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqelhqr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cupfeavg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxnwoaq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoksbqf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2njwuvcgl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2epuwqkok.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzdvewx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrqvoow.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqswymzp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cysjntvx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bekloqxj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2frcjpmvg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbrthyb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrtfeme.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqvtfef.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2agxhmqdz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zntokaer.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtbyhif.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervpwxbd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtlnlts.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvucqlxs.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2igciibtw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xelrqcoz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aurqaqzn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtgcmak.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeeffgh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbegwpqj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgchjbb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ikizgkor.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2crbdxsqa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lknzvmai.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxttstfy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2olcpqhzk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2shffkdcb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvelkwup.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrizudyn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxkrunf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjddqbij.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuosijp.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjqferj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2myembxmw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjcbxga.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvpfwnw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydelgwrt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkadawc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbehbllp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfcaaii.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gakpntiz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkznbbyw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyzooyc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxezuhid.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nppwbikt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqmstdk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjydpxqa.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfhweow.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnoafwm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qboxqgef.html


<!-- 参考信息 -->