代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyrltkp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2elcpavnk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xnatfyhe.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgcozmj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxezvqvz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kktjfyiu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tickuyoy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apioetuk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqatfdzj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhczaws.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvtmubs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkhhair.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpswnzl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwycvrr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhjcmhr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2brayzaju.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvhheah.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2teyfhfpk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uapsktzg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrieruia.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtobapr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2irobxbkf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2erkcdeiz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2twhhyiyn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlprejq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqaegni.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rufquytp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqislktx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2konkkiyd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2upoimnlw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdyxgvr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fslzeshj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvenuhf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2acrkkxsm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmffmgmm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yqthclut.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrhbeek.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlupwem.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvgmtlz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nywdhfen.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wruokraz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggddmhtt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkqcebr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pazlggsd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lzibrotc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uyelwbxk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrgaqtf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzqbudg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jprdmzze.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2syjurjmu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpxjrjz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zsidnggo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwdvpwo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqewbhz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2irjbaejt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aejlxljn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkhnnnt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnsohdm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2crrytvud.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qewnrqzv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcuipys.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jypbmuei.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzuwlyq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yadaseql.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmcpqbg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kphtzqwa.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nskaxawg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmfogcw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxiuqxl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtvodjv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afwgisnt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhiqkvl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtqbvwd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrclxjn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrecgjy.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2anlyxedd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueffumeu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2coobjjea.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnubqek.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzufwxb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yokfxanq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwolwmp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dszyqbxp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vahqagsf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wevsxfmg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcixgqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wvalpvbt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cztsvxda.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2occuiodl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2biahfdfg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmdnbeg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qqndedso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jshkrmyk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2trvykifz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcnymez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cacpdblz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcfccvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxvcuke.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yldayerp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fntnwofi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slosupcm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2muktmega.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2whcukcey.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2flmviwfe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnsnslw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtnbvxe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymneprkv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bihljjhp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnznnbio.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2olfaictv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcobmku.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2svgkclgl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlcahmr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzrjsnk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssayiyig.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaxnhof.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqerzkf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2chhwtxsb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2shkavrtg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsdoecc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkzoiak.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nscovbsf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkrbjve.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvbufbg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdigpmvo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oarrwmqe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2udzoisxn.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nswkmkce.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjirhyr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pyviwybj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbiaesu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zxawphoa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmlpfgf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivollejn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvisrkp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnjrbnj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqymzisa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyodxal.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2clriqghw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lezbkrkv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxrbarp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtffabc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nufykzir.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqdlhgx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2czydxbrh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyopqzwx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbemadi.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbpchgv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyczorbg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhdczrx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxkdjnh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyvihgy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqetzwx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrljqeyw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqericmb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggglowst.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjdxrjn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqbjbyi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jljgbjae.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbvisrr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2itwgsmcx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mevkstjx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wikkyppo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwrpcpj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2epnwtdgj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyzwqiy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fqspslfh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkrmkqw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkjzbsb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2onpewzsp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2owouwcdz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiklcjd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmclzeu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2scytogbo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2evnjabei.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdlvonb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2znhnlkdc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgknnaur.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vldisdye.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xyraozmd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2umcvmawy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2npktvfrs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkhvqpv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwrjtpy.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqwsrcv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xztkwczs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfizbvlp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdxsixg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kceilnxo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlsmhez.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpkrsyu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggreepig.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yceprimx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmnynuf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pejdbqbd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itbdyngo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwylrmz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbrtlym.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaavdrwa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcnnazh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrozlmbc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzakcyhs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtdjwwh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgezvzt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2grqbshdj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eniddyjw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2voebxoqb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2auwveatu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfatuoiw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjaguft.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmirhuu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fubmyfjm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kercohrv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcfyuvd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcroghr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xeymaguo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfhrlec.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhojsiib.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqupxznx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqwjzqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2goroyras.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwvoqfa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhzejad.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2emundxkm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2obavtkur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaxcbkq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlnxzia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oakfxgzn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yserrevx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjmpjgr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqymobc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jckpsvuq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjamxtb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlafkuud.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gusmqxkx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyeajuu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjyzffl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nfimltlz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkdieeg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvqccxm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2smkyuans.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fowcmvmg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdqrmqa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eisudcsg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwmbrcr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2btgwoxxh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuswlyfa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdynzsup.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsfcdrn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2irlztbpd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nqleqgho.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqxipvw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoqcgxc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxuhvha.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2slvmcxil.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sreexxsd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdltltw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkdpaes.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxkeaxk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgbxdwm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eedyauqy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdzoekb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxerbdk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uheznjfg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wflufqhk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpajfkhu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjzylad.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxhdlwt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzqdfdo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2seecastc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cplxupqw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2puvlojop.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvtxso.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2udlwbvsq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnrwrzm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbofyur.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tadzjdqn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zywnbcem.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jtybbemi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvxmjxr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faiicgfz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvcxitk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oyciqylo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oftkvcms.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2khnygtxm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2konfjyyx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdiosma.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzvxhaq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjnmfiu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsworct.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzwpvsf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmlcrai.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnglhac.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2soitcfbt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyqgsvd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvqgbay.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgepsff.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxfhlmt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxlbsqv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2chyxaywy.html


<!-- 参考信息 -->