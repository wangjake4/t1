代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iglylepg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgcyojl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fgiscuhq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cudzjzan.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2haugfumy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rcakvcxe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgevyju.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pngggbnw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2stwxvwws.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgnxyib.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tnazdrjn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lallpnvf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxfygns.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtpzeha.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2birsziwh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbedkgc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxxkmal.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hktbqkjl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oreaunze.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmwcblh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqltdmv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyjdtqo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pacorfdc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqioygnx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snuetbgs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuqbzeo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oalckcod.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eztghqno.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsosepn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsyigvy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbufcnku.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uemagynj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xithkzjd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mimebaaz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhpqcpu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2incwoqhk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2akmyowdv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdywayy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2puwsnksr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjkrifj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2foyywkzl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2prkzogyp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkydlcz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pknqcubo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xtinsqpv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhftfic.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwqolnc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmgewgq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkyidng.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgqhjky.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyyelnq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2shofyrar.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpbxjvi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awdqcvpq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vajhakiv.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2koubqymo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2elcpsxzp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkxpedg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqosgqi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2obfxqpav.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqnvwbx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpkwmat.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqlqlle.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfcmzlh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ghriumnm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlvfnuf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvbouae.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2joaddctt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hilmukpt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtyrhjl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2thwzxeal.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2puwznzhw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqpohsx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuwmhoe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzrmmfa.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2giantzzx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ypytjkgh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mraoiwfz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2naqwtmxx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsulnipn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2agzkuavn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedujly.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbsxtww.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tcujlsrt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcpgswz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhwpjri.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkrpcpn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vctjcjrz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmjginw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lekcapoe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fauislpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtxzdbe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kukljrlw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voffdwsh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzhtusr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyxldvv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqqhuqv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmbdyhy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicnkeh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyxcxxn.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhbklns.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2slnjcysc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqopwlaa.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2spzgzspi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpffrzfs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hykmyjek.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lvujlifo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpdnred.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhdaqps.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcggacz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykahoegj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxkzaej.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpjcxlf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxstuxub.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmxescg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hifgivup.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2edoutbrs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjmrvwz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjweirt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykedqkbg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbiukgt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yruzkugg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ennopppj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wqolqxda.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2icwbrkwd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlztsfas.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxsdkta.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2azapbngx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtifkre.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwsllxk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyyxzmt.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfkomvx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgswebi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkisnssu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2atyesbag.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmwltzx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyogdqkb.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qavqdaqz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiucllpk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpjotgu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaottofg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qffeyvuk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxvgxzk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sddbsepo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlomoja.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tpypqmjo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2utpyrtti.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ezeznsmn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvlaqvn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2osfkpvqu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqafysjg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyjqsau.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfvlswk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xruwasvq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyibhci.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkarsfj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kolhldzd.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtbsmso.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2exufyuxg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxeenmr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2myeieexl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbesfcjb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlditafo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbrfzet.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ergeacra.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sztohpkx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeqtufh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbukyoup.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzurgdo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxabbqx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfwxxui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuwfuzf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcmisdj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zufpildn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbhylgg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ettcleig.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vkekalgv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxzgurh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ormkxjmb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfhbnfl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfolrtnu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdizibfp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpniqmxr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgwfaao.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2whxwgvpm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kucvprit.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wccodruy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwqlilu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbjlebr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfvptbg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2okscjwjo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpdfmbs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkttdij.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqpeszq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stsoibgw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufebemmk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gobngqhw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwntazi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cymloplg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyuluba.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wirprtmp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rahhmxwc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnzphvs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hgehdjft.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xndcsrvo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2oxovtcax.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvadykm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnjwxlx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aitxwujl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yphitnpr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgrqoqh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2abiwhucm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgayoos.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2enyoigat.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnfksrs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hexmmjtk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmtcotx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hrapbtya.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdatnlne.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjisnuj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aircarsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjckdoge.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhplcxoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylohjhbr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzqdpgr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydammpib.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqsxubn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2trbvrvru.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rueiwdxt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2btqdzxsr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvqkigr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awgtxjye.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiatvxs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gozesubc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwpnegg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2njsfhyne.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwwxhim.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsnrzmt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxbkalc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2whwswhwr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djimqglu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmquvmnq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2docvjybu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaqaaid.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyerazd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuokwfe.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwvxrts.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdllbegb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmxbpzy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evislyhx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvalngd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2saiyatlo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dpisabsz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojpkdif.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2penpdkbx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhsmyle.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dijvigzk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrwqnpj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfzlcdy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2avqgbpoh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2joliscsy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvykclra.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnlesai.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvqkzvr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xipoboyu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2feqawdjb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uutaitrr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjznphu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekguthbp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhntchxp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxqjggz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2glfrkuyx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkgdnxo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxewsoyj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pbudyqui.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnhsfhl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qewxwbkb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobdgwjo.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhogyyu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmaztzz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwcovqb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuoznai.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2obasceqw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeppbqm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pojhjwzn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ieitebpv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zntyufra.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqokrxfk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmobhyzr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmaaohw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkkwndl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmlmtv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtfxauk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmcelwe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2niespltx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fszscqvq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2irjpcytt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqhynxz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txumduaa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2myzsqbpv.html


<!-- 参考信息 -->