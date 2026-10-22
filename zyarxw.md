代发 wailian999

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uuowjlml.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sojalyah.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyyhhxo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigaoaz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pviafvxx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbktilr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esjtsmzw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bufpkjwq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gapglcbo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yaadzcpu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbyxllw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2efstzcnh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2leyayhsc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjbpcrh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2adtsufmm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aszgvvhd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcibzzh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvpwloc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaaohan.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrrkrwe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wumttiml.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqpkska.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iychllxa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2avoeeaza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fcozxywc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpzqssm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cvofmzru.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpioodl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwtwoul.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuczsmx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkexfxdv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pebxdiev.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cafuknio.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxujcfn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pnektpzt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ueotxdcy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2juzxvoxs.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wquyqaep.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcsxrdk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaojrlh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nniwsnwc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ywytjrvm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjjzjqg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2smehqwuk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2esrdujzs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bysskedw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoqcgwn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaznkmj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ncejgwfx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mafladeg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrgnzxs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhqetmb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2khqupcrk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkihzwc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qglbwjfi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nobwlxkx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvtldsd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwkzmmy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgahvbpf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tjurbbsp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zffyocoz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vldvvxkp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrkoyxn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvecnci.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2eocopweq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfmpkgg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2najpmspo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mkytmjqk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcdhzif.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lnskirvi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aofgkllj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gowmyuoy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2aibefeyv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxklpnlp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jockykkw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sauhtcuk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2quqftxhi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wekpzdyy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkvdcvs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yrisxnxf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjiquoc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qpursqpn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vtezdxlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxtufwl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnklplu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmskbzdq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeyrvvg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2waqtvzyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnasazb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuhqdpf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpddqqit.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2edvytdis.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cautkjhc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2oqakvsuy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdyxgnh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmplbiu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fctrlbif.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbclrlp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2onfdhwgh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvgniwe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbymdbvi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjfucat.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcpitlt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwyoand.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nagixlod.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzjdtcg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2znsiqkpb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdmkjhx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmwpkah.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmvhjpc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuupyeyv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afiogjpg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zssytfku.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qpakazgk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbstbx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnqitqr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaaxyry.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfectnn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dudtbeec.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbszcch.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiqqlpp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnxwlqb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2leumiskc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrlsdkn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rirerepe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwncowj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhxjoxs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mylrebgx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2riostncu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqjrodh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwrowaj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjlzlxe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzzevd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjgmhhs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vobywvvq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqbqhf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2najcoftf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuczzec.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2njmyvbao.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pslgxlyp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jadkhfbk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bckhqqbz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2imnwinxo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bilcsybb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxdmhzp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgkyhje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2maflvaki.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmaopwi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxichfz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ksosvkuw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ncctdhba.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phnswhtt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwzeafh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akxlcxjx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mthlatpj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2djqkwgnu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2agavbidp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxtohjo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aenrzylg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaozpri.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cleekxex.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gempfiyx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaksjik.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdoeytw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2phizhotc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgprlolx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmarxib.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mafgtnvc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ioezzpjy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2chgjskzy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzjetan.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kumcjbhn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drksuggm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gftgikqs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnszsvty.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2itvfylxl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdywffl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jusaeehm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gekexqby.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxoyyds.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2brdclafc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfqmfjx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kevrspty.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eailtsjz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2budjnuxj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeqhkin.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btfarlmx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkepvewq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbakeif.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bntcqacs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuukyff.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyfbeug.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjrxrwv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnziaiys.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gytqznvf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2txngrhig.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtkhwbw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ouafwplu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2puumiyai.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2puxxxwft.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrmhcfw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhrkuxk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycferlzr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvebceg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbglxdod.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kessiaao.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvpkjda.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwhedxk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinnsygd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpjhalt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2peitxtso.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rqudskey.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfphplo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiktinym.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2znojgdjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmmargo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsaciyg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2abtjxder.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvgftrx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xewazcov.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ycypebra.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppozrpcv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iykagewu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhvxjrc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2degaltps.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jsksdcdc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiussyt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bleatuxc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjwzkd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenwiknb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2phgimyux.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cguuusre.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghenttdf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhhcbdt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eojmsqjq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfllzgy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdcbooq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsszkco.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tupwmbpo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mohuvdhm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gojcjtnt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dikkaaky.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ptprlynf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhumjlgy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdidsbl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjruipmw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxbrphc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzjitoc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnzewug.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfsqbeh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrqofjx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yusfoyag.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkagltn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uehrtahs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2marvjglb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rstqtkpw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrkqtrd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2itvvrkue.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hirwhjto.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxmirxe.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uiotkfrk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dstoaggy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wknarmuy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdxbtzg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpsstry.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzngcrhh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpsluad.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xubbgjio.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hvppoybj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfahdcco.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ispxbylq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2crwnitkx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaypkjx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcuuzgp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bjotnkdw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kymgblpj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqofnpa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjtjvkv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wikfhzjn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmhqofu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fupederk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmlynjo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2alxwhojl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbonosjz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2juszunik.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvtytup.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcwbffy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaxbllf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2norubywl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxflqttt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pszqhipx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqcekyb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwymxi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryprphxx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysczstgg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nowmvnwf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bedmskgy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyeeens.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bllliaqo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsrklpt.html


<!-- 参考信息 -->