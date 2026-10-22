代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zsntexoh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuosnrd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bigtegkl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfzezpf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuatpmd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdmnjjr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqltydov.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mytsfujh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zyloheah.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ultjstdo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxtxzlu.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kziurqnj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2artiphqn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkrcsbl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pveggdnp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqijjocy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhenqdk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxktssw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mptltfka.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2orbobczd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vndnflqe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzctptp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncktlblb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2toyzguqu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrrhvsj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dydgsixw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbipcsy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtctquh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlscedm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyedizhb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2murnkzge.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtwrpat.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mklkeydu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zutztxal.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nulbuwkc.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wanbyfnx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hiydgdvm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiopwkc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcfpbms.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmbwsmn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtbmwdr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cearxwrd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qpktqsur.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtytoban.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2npndmvdm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xswxtjoo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2omcntfhd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hirndmpw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dktxwxza.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbugntt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2coeyaaeq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbtkvrk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lvapixuv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfotoxkl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2awerufzr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxsykzh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yjipidwv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgivbnhk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvdtcmb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rdscfzbk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwysrve.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmnzrnc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkxlxgp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsvxgdu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2torzosur.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2unzptlqm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqvqxnb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2btyuciak.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2szmaqypu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbcoikz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvgklcj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkjaaud.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdbuult.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnnbter.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxgchsv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jblynmuj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoufusu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlrhjme.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvhrnqa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbzlwcf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2floiqusn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzstiip.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrabelq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jziuohrv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcweutd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwwmxax.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwualybk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oojoriwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhejqamk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyngofn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uadyshta.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsuejrh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bosoblon.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wyinzelt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fufgduwb.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tebzkibi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfxddda.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfhhmxo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrpmdxx.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2htbfxaib.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzmvhap.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdcgurg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mztypgsk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hofluraz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kihwdxlb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tozvchxd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsthnqr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trhmuitv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2clxusdjc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ublxqjgx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvxicep.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrmgmxm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbvwizl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ztngomes.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjylzvn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eeckmold.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqeslh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xysfnciy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ereksghw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbrbrke.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhmrmpd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkblaxmf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdetipjj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssonxegk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsaoaxgk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fyadeyrh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgfecre.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uonzjiwm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhxmgan.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2arrgqjce.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxbnfky.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzqmxfb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjlbwsv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbvzplx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpuznzn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbrlojo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2eppscqmv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwbvwyp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfaazea.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2phesrlnp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2onrhapmx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhnzjdk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcuczdh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lefeykvv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdibzea.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrahya.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawvcric.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dukxnhwi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lgihjbxh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uhivbfcq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ctovkfpc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ecykzddx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrfrzhn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgerants.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jeemozhh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzoxrue.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mlepxeij.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2odsrfgcc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxgyiih.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhepzdc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpohdhh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjhlghn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gprcxecm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2arnlpksz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvdalhj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfizksts.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcotgpsr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2talinvtm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qicskpag.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhuzjro.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iedspdax.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eutypxzh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnkhctf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbvtlwg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjediyun.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hlztlcjj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2srmdiqis.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqmddtz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwuwpzj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhpycgs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eizqdyrn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phqukdjk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqsmver.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdscqkrk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flnugvqw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jptmmcfs.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkaobtb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwizlmbs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjazvwkd.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgopult.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xllowozf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcwdmgn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzqrmfg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ethycvjx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2csrnverj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcyjqak.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixjkczq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rweghwsy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkhoofx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2banucrmi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsgdnjq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2reesuucu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmhpnak.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rnukfszk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aphuljoc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnlplrh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgicfld.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkwsgiv.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2axwvuesh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsrlmcx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxgiyzy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfehoyd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2njverkvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kekfceng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcckloy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yimtrlhr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlafnvh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylktmetg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atxxkaby.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjcoqzm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmfeoda.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgdheyw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbnqbla.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2puvmjqza.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nbucxuwb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2asnxgefu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbikbzf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaxvwpx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2snwsxiqh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ookeyxuz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzdnvfd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukojuhwk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suvrjtke.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpvoutq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2etwimdcu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jounezck.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuliuyr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzsqvtz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qbktilof.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzenvsf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtlvwrr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iezgmqtg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yufaozcg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjagrst.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ektufdnp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieghhszf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdvqsvr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxgvcsi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2djahhywz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbcvpks.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oeibolnl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbbxkdl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjqeiih.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2imnsoadg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoroalc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrareaod.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkntcew.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfsdmau.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gnghhzqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rilcfmvd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oneircrm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjygexds.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjejyjm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2klakkpua.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbtwfzd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbvncjp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kysuxixz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcfvhv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdijamv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pizizcba.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbpuqnq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aomlbxbf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2blxfmlii.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxprssjg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aftjhwym.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmoobfl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqryvrk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aonvaiod.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kersrmka.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgqwnqh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2amwksnck.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ciejhted.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rubnpqhd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qinerqqt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjteyrx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyeethg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bselnzjc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaberjg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ceccrqje.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyjjdsj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwhfegr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vipwajwf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmluftc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeqflbi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkhfwvv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ranzbkcl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkmqgzx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2flbuvbfs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwsrscp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqhrhtt.html


<!-- 参考信息 -->