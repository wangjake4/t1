代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2snwbuzuj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2knohctcx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuxkzhl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gphfjvis.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtyijph.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmvtjmi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqmukle.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mamjlbzi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhthcqv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2unjwncol.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2btnabjwg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjnvnzr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvuosft.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jogsbmsj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nolkaenb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlphchck.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuaunai.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfqsurl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bkolbtwy.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfzouhb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwjekpo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmgibd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ruamqyys.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcuvdsh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2inpwyyno.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfszmgwx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uryxwvak.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwsenag.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2csejltzr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhrqdkm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsciaej.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lytyxvmp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yhopsnom.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2licicyly.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2soekpncu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoqjxvt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbjuvst.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjurypok.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvtznnj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdgnovu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2whgwuxzs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqaoask.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhlsuz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuwhizv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2npsrpplj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjugrnv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnggmcy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rmscijuo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqrkwjd.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iatjbdnt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgdtzxg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2trrjtkyv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fmurgsmo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbcnphi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyddcmx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bozfvmok.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcwcaiv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoeyazm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjzhmkm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rizyboip.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdgdkjy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2owkhnugd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rkslfeuz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tayotovu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ewowtqmw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2daskzbur.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgulshn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2quhtzucu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rdssydjo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2spkcktoe.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2loffpecm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bppphrlf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dagoayxj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzlxxem.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wreaoboq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfusvph.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvcftdu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ngztpxym.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dhinhpkb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfzuupq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hysczwrp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmhpyhg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmjgjlo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zcceyyho.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpuacjc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyhbjuf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqibehn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2acdqpdui.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2krduhuec.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcugywb.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gojvhklc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqepdrh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2shdhacqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnpaekj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybekokpp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqwiuci.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnskcjp.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfqqsfj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yatzhtmz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmxjnwy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yktyywrg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2eahbbudx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzagwdob.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaeruak.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2npnnlmrx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xsinbbvl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2iaegjbjt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmbkltq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhifoiv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lugctdru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kofedhzo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gxistlan.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzlomtx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkluhua.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprrbses.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvaxeax.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2riwdydbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfetaihm.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwncllsu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxqofjl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbppqyf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqgemdi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxnxfdt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjggfvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwrcxby.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vaivplfc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvyjzpn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zylkzyci.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzcteja.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sugrkrtc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixduilxh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pezoxclz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgmphlh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2osskjfyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwrzdlw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wlovxgzk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2genshgjw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdcdmvb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sraaaqdq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2igiuxbwx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kckrccux.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2unykrxke.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuyfvdr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iualntqx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2scrgwmkd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2txwyvzho.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiqaqrh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2utgebmof.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zddklemc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnpxllr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcwfsbi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ontbigwv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvejqalv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wibzojvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtplxqe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fetgptgt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bklnnwrf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lnouvern.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzvatip.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmecbmz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2srguobzc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voeqilhq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsviluv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlccdbnt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmkjiif.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgydov.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfoaena.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvtsmer.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hypvqsjx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2liybuzcg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzqtcxj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2holshwlj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2llzfsefm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeiustq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhmukba.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2imlzithj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbtjhjf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfauccg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2prvehaal.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgbnvei.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfrizuo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmftulj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbsubth.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgifpanq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlkvnyo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hadgjgsm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbtfavh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rukeaics.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2swdnkbbb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2clmiajtt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uaayljuy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fogtyicy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vngpunus.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvuysrw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tehbfhue.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2knhtspgc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2giavfsjv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbndjrta.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tburheok.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2teercwdg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hivwzzbw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpdktgv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2igwduxtn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvghkfp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuplbgfo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtyfggy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzzfdpg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rygqjbid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtstlac.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2galmfvqs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyokwfrr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwkpaln.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxfeoiq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqisnsi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2umfzqsdd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhgzqbd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2naaasbem.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxpgaba.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhnmfvr.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmorfqe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oaczoeil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dijncgnj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxeyona.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2newiqlah.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awkfjkhh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrecifhv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwupfwsz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qizloukq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zfztjocl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtplpkn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrydjx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbafsbu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2woytwucx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqmijnq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nluqilxw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpnjmdn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkhmvxr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdlcfps.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xpteourk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2msfltjyj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryobswry.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2trucxvjg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbrnpfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkambnr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjzsitg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrekuwd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbaifjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzdfnmo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2otthvgvd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jospswtt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrjyccb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbsyapt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhlufgu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iflirqhj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amzzrmub.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xemusfbs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkytkbzq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoochtb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rthplfmg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrnwhkl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rscpaiqh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kswnpmnr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmwnevt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jskpepup.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mvibbkjr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwosdlj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkrgnhr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhainmn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iucywzlp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyyrefg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cymnlvme.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsjpxcz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2alkcyxxb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuddftq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdhxlkm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bszunkcl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpqkbmm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dteiagqq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbdzxxt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrenson.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdumgae.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2huztlipw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfmtojw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aicbwdae.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmadlgz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2riecjsav.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uweqekue.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ckayfifg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pykfcpeu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2plgfbori.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zmodwaph.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeoafyc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwgjbis.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mongeoiz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoofvte.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwknyeno.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdbkgzz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ophslhws.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnllymwg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqvbwiy.html


<!-- 参考信息 -->