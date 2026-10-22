代发 wailian999

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lykoyiqr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2einangbs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lsncbjnd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2olnkhuii.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2medkepod.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sutumuek.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zeksasmt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wgueslto.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqgxiat.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2israkfiu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aeydmrop.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eilindjz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhugcmx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoxrczz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kejmfpew.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fivqhcve.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbeybic.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2coieikxm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoahzwd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icriyvbc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxbzrju.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2djokjagj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjtshqu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nowkhrka.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yhezjlkw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tyblkfuf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgxjecj.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtceqaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zjltdoma.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oveauipb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebveroui.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tqixbanw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eotyhaeu.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbumdlx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqnctwy.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kegztjan.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aipgdbyk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwkmgmi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2odvjofqe.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoamxgr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tawfbbdd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyudplj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2efvutudk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmsigct.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgjxuhx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqxjrna.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2agdzzldb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjepbyco.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2txbtwtvg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whieiyat.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ffslnuwk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gxykrhmc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zbifuxta.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuajgbi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jevtsjkp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aauxodik.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaayhgr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2duhdamiz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzeqhmu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yaamrqvw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2tjstysbs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2keoedabw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jonrtare.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2utqtdins.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfmkomy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2slycskib.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdfkijf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eilrqrpr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmdovia.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfzjbjp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqfygpi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2khbnjpsy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ennixdvp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxmnxus.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzpyzhf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ectgllhd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgahsizm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yacvciup.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvnsrqm.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbaepqq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvnfnon.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zpammmfv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qobgakio.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2neuqlfju.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yspocshv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2svgespnv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2udfabzaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeiqofy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ekumxtjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frqbehty.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izsbmdma.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2szkiytot.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhortmzh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cokxjefy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzdgjhd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkqnmqx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2icjxbhid.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qhthjmdh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlxfelx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oztmuzxx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2inmutkal.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxypcizd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqnebpu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gvldehjb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnwdwfb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kjraqpnt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hasxuppr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkqtrim.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rufwearj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvpyowq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpohlmf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzyqzzk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpcruho.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2puqfgcum.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbekzfq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clvbkxff.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpdrytq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhkkmth.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfiobfk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtmsvoy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhjxyzy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvidkwz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdgiqfh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2drxcmpmp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akikqeya.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsdjsfa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2iflyvkze.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wutyfpvt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fapoagai.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aclhapgd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jevvayxd.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxpgiwr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtehmsi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tggtkyrf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxusgitb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyjuekd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhqyydh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bprttfmk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2biaidqop.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2irxkupwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkkdnub.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dblnaega.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfjzrhg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfywumd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmfocoa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyromfxd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrercgh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpcafnh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytvccvs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsndemh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mngcqhqg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2doitxnmy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjmbxca.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2chtblwza.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2iljnqllg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkmqufp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2duvhqpnd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoqrttd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wpalbywz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvspcuoe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuqjfya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdomzkru.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wujzjpin.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxgbpus.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2onwzbyyy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amxpmcjq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gszlpkui.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pitozzuq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ryetoiik.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuivmabe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2olnttgrs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nusrmzoo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvgptxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ifefbumx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmixvfw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeermyod.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cercpqgz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyyvsjv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atetrmtb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2flloaaoo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2odcxfhng.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2usljczoo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2clsqiifk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnhoqkv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgnnkej.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzzqiab.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmkbcpu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voppxvwe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uencuegh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyrbvtf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkpugmr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2viynqvco.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdcuzbt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khjjwesr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vftteoud.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmdsasf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuqfjta.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgatalt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gamenayc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqfqxri.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cosifwfm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ooegwrsk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvfrukt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxpkgwc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2snriqfgz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hcryvkyg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhvgxdb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ivddcygh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drbrbdhy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvykgdr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2porpuqmn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sktbdicj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cximcpwx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2abnskvbz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2efefgocq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dyorqlgw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtraxgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usrtkrsd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ranyatim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuzheys.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2osfgamre.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2altehkxy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itplktfa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxomuao.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsylmll.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwotmkpk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2utyezski.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lshtjxia.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxauqgl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ugelbpse.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wncsjqxt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsamejb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cthtmzez.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uajkjtla.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vmydxsqu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrvhhjs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfajcnhh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbzgqjh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvafpqtb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulykhpoy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vincvuze.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyknzssw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuqtumu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2thngtqca.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnfbmuz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcagspc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uflnfjoa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugjffgz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfjfhsw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmmyqcm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bxswzvex.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knwagjzo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2futqoeaj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzpowrm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kubofxgm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdsqowa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fzemthco.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwrasca.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dpddjpul.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zicqkfak.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzouxzq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkbzhtf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzowdis.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaxhnwc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asfhnskz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbgmvfi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxfmyga.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnzvggp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fmffyqnt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiuaonm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hshxiwun.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlnljcu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfngmau.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlhogjm.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ovblbnyx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvjomky.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2igmppzjy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2djfdihrn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqixqez.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2puaujdqq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lewszokx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuxuzui.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcyppyz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpfzwmb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekawfdke.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkxfzgl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sngelnxj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsyvfyf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnpnpnu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbppxamr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeioruq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2eebvuufq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2oagfpuxt.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcppenb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdksauj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmjumom.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqfxsjz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2barkhnvv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfhueyb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mikduwsz.html


<!-- 参考信息 -->