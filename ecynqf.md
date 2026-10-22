代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2akvljadg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgvptuf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2udtdnijk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnazyyst.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxemhzc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfvsoho.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aoufomvr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2idhzmqde.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iftqhhqy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qktkxdyt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2epgjadgw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2demcpsqp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jeakfmcx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2noaigoqg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoyhabq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwcvhgo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzetzmd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzzsfgr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dagufmbv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bizcxmpz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdufpkn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cggqwbyx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvkyoqu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2edpsfoon.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgzxbll.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmjzkwh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkomvtfu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdkhpnc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwpmagg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjmfqcf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeldduh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zeldbids.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfpcnhi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvcdvlp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omzfiuxo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrfshcj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoewohz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiqkpes.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlqaque.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcwaezh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwvoruj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bftmoiww.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tsndntjd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ydakxahw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcsocyp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dptywolk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ooicyedt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrpmelc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2thzezeei.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zooxignn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xoogzgwt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2asqyvrii.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2whihndmc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrgmirq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsgwxet.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yodltzwk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejusbd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wspncqxt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kykgdgpc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgmyldf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxzfhwz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nvczzeui.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vpldvcgu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgagntj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmukvdn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lblnqsee.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rruzhicp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlwlymm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gynhqokl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvjfzot.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2popqpxha.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcahedz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdjbgur.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oziufnla.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhdkwnk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vvipwbaa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wofsglgy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2sluydcgz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwteniw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hafatudq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkkzkpk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmsjyka.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uoptfyhj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bitpwgvq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnbwzib.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sewkgbdz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpusvuro.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnwcftr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xshyscvu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2durgqrfx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tipvsrtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjgdwtd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpstviq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knkqsyvn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzwnonu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwdyxqz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hebbsgkc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yobqhjnn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bljcdtuv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsjjlsk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2okauxdbs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbfyimn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhiqrrk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nytzjsxu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2azgmfvps.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2leyadbly.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aybohcof.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mevjklgt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2caefbkdb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnyhetq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2himkndmu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2stccahtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqiiqea.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2umbuiiun.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgtygcm.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaghyxek.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgeqpnv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jumpxidp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjcyhfj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xiubprtt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqflvzur.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2usqzahse.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfdanjk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2meqzopvz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfynxpsp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2asgsplof.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2favlidqp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtuzmzx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblfinps.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gchyfdud.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpitiuqj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nraaumej.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2febelcsm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwvilkk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzcpmuq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kojcukbn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xckqegms.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjnpacm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lihcxlqi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2swhizqbh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tudpjxvo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzzfrkk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2frbstgsx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2anbdhovg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2thpagvmm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoctlft.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2eljgumyy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cfieketz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtriegg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2czeydakd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hboebbjs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpgjoxa.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rllihejm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvporcms.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpebooe.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2snpluyyj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmrpmms.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiqjtfr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vwurtdbp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxgkvhz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2grzcucqn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjvvheg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqrfmhk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xurockcb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jachgyuu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2txyroevk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmqrscd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzndkob.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpduell.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvqqhhm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mnienamo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiwesac.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2frvshtxr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfnlovm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fycaalrb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vpakjewo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czwhhcer.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeyzlkx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adwbzocx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnjgbcb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccufkoxn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkycqbdu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqlxqmn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ledzzips.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoahjsj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsksfno.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yddxtzge.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqqbxfr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qznngtdr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2obkhflmo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnviopu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mryethxq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2khkilsqr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utpliedr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkhowfk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouybogqd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sverbehp.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajefimcs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ximptuyt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qhthhzkz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpyjvhw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iakqqwit.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bozkcded.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyxrjgk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqndrxyr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzahxwn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2umgzcokg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdmclnm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcoztcu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbhqhdw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtffluu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wybxdcsc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yngztkdh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpalmnki.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmnggnp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxnibg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bohbuyom.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhtmvg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sezfhrwg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbnkrqt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2apbquosh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deowohbi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2muvoibfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcrnttc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyamcdn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmrrbmi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2odzxlxla.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfvimnk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2utkdzqrh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2byrhzpma.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjhceqg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gynhkrwj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wfixlfpy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsojruqw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gprhuqqv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2probuhzm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzuzhcj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqdlbtx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2apnsdskf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbhlxuv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvhtcsy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oekbazdi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2enjqrjxl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvbwwwe.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkeffqos.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lixqwfws.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2igbfdgbe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzsfugp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nzblvqgn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rklxgjsi.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpgwdot.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmplaq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyownfp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xronbazj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2noxjhbwn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdswvgw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnbjyzz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuhcfcn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgqjdds.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2niwvznxd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zakcwyay.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqsfcbq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrgxhly.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbsftbd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgkhkiz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cicmhyiv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwlufvs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zoacfuih.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esefnevi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtfuawm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2riikrfmv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqlfpvx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjkrzez.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuwmiib.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qcakydsf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfwbupd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2prpxqihy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwqynqs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvbgxsa.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aktjlyhf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lngfaaol.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjljyiio.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaxuqcc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqgclgr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsqlmid.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szmhelmn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlvtfub.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxanmpkt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkewomkb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ycemyqwx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgiljrh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wstyowfg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dilvkhka.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uepyijhb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eldbcozc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpulyqoi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iodzvlxm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwipflqg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ralwjmjv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwacmtn.html


<!-- 参考信息 -->