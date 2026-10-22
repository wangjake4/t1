代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2auazthql.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqmiaym.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcmheaw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kibsofrc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnitqzis.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rlezsbzz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvffvyw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmousdbd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbncbaj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzpitkn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eefgxvyz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjqedqz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2obmboemg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqcwlci.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nztrfxdt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wdecptil.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrymbir.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hmezheaa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vttbopba.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmzvorp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fquoxchj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrqglif.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aovutead.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xenpgnjc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gjprvxqr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwfipyy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkdasad.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzhklaz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxebfaxk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmnzlgm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqlfylz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqolblwq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjvpzju.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yiipzjby.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmcelym.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hwprwill.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tmawwlsc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cinlrype.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fswqrtsk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmqmkma.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xxixwjnw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pawofbuy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgboqegw.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2seohpiud.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bckctwjc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hyydguyn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhvhals.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iossnfnw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqatzlzl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fypedcai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hooivdyi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvyyadu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nnylpmsh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqxjbgn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nurjbtxj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ogctxwbr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjhqtrg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2menolkjc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2oantosiu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oleuovml.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mvehdudc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuguunz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmnhlpe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdsgmua.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfhzwac.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2adocanez.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kwymsthj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2emmtuaru.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxbuoqm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2joxsrewr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nenxwwll.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxgdflb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjfmrfy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzkpbks.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oddlvzho.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvbyjje.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kviwtccs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rwowpmct.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qadtewoi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrvymdf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2upeaugfy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzmebcv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwknisx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsspsczg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fupnroso.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjkavdt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdihewo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ctguzyfx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcnwjjh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2frtdlame.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsvtdsr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxbzfew.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnlevab.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2jicniwuj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuqliav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fciigkuv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aajcmwxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqebgbx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfekuzw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwupdqc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqppiuin.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uberucgk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgazckbu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sleldrsj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuvgsvu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2atyadmjq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkrixyh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2thfcrzvb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okbuckkp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qefmwyyr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hakueytm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mnklcwrl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxdfhvf.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2psoozmgm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaupjjj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcpvxbo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgkmdei.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tveqawon.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqdxwqy.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yewgqotr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsyfiau.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfjwabv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2znunpkjh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxklzdfs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqcwrpw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjujzeb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2npabceay.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2joxlualh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jysgvtgg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrncuwp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2svrphpsc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdahrtv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbgspye.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsnqqmv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sszbxqdx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2muwbqsqv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2admtntyf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrrqmud.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmneeco.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eybrjouo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2atsdzyip.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdjnmes.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxbrmbo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gexzvstc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkxcygp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tovncdew.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwemrop.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmgdfvr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsxdaky.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wdptlvlf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvapnzmr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cleqnrxi.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qltkhavw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pywacgxp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjsvyjf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kuezzryk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iadwnxnm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpipuvge.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2audlzrun.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tnilynqw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtkfwwg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cohnbwon.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcobcug.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwqevdb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmryjxj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orrvrgnq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdglomq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvcfkfp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmqhwuj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixvfrad.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbievqb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmceyuxz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjeyfyw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2stglqusb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pttvxaab.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xncbnepn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2djitnetz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfblqzl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2chcugscq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yyirlrqi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kagxhdwd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfcskcs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwxviuy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgbcbyp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmquvugm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhulsmst.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcvvaev.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2akfchyvw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2icoabrox.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqviatk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2enieplzq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpxnjsj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuohmrh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrizuqf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cmejtknz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjqhbns.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwwcpfh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prabwqng.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igyqsjva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkredqgd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzpwlqv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkalrxr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmyrfka.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bapgphpi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxxbjhx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2figbdsye.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gynbkjyr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jblmfkpt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kifetpbh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2feliqgpa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iziuvmkw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uadhyqmt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvabaak.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrdxrjt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrwuqvz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqoasfe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmknhhe.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzppclmg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhugwmk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vghnpcla.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnakcslq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wvewsqip.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuuwzmf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sclyodkt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uzklydjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uozrxble.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbamnczr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rslyxusb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtxipsj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bofvqbch.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxfnwfk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfmmlto.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuacfun.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2khbhvral.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrvyahw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2myikhgft.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnvrgpz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sujiysgt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2soqsyvqq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwoxvdt.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2movtfdkh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfvhmtk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bewlovvd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofikbhgs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwhvgdt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghntkiaz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqddvoqs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bulviyxj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2clcxgrdg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxfspyw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhtqxvc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfgcvft.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pbscjvcg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llcksbpk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omjwfuqt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2grsvbptw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaufrae.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2upiwbalj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgjcmzg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqxauwc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyxosmd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agpaxroc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbnorsy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpkojdf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpkjxvb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdvoczf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kidniola.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtayrejr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lairndjn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcvfhrv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iatdsixd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qnazfcek.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lueplsgz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnmxgk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2covimhmv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2izvaragl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vokktzgn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nudxrmlz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbenwmt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjddkppw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzbrwdm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xneyyhog.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyqaynv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhadidyi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rgarsyph.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pimdisxb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2azvojqes.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnpydbm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpmzepd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhbuzgh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njaoekgo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqvrtln.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjivrgfu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuiyrem.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgumpi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2maftbuky.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnfhrje.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2voxzeyrd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2guwasjns.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcypewdu.html


<!-- 参考信息 -->