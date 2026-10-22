代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjnkpds.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiivjql.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeieivq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtljrjz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlhujqi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvmhifr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2porpyrws.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2amzdjkaz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2grsbfbqe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2anlruhvk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpzhbbh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwycava.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoezmoi.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjrqbhq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfqfmqh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wczewldg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvykovq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2edvgrqxo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cidcjmvh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyzsrzy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2twigslcu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2roblbflh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aynbhegp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdnxvjd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ogazfoyr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmjmdzf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgbetjj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2likqwfiy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2twtxaxgx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jqznontz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoghyma.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwskvqf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpqagel.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oyabkaoa.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvoxkqh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiwfauw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fefjpsih.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wysknadd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cobyundr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uogmcdeo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rnauoqad.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olvpzchn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxnpunk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zipgzuwz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlmvqjk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ariuwwzw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkchqfp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgwmfro.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kgehmfmg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtngkoh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otxtpupb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2webzgkwb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpcbrmr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kctzfcrf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtlmhkq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gjufpwkz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqfnbii.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxmrxjn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmwvhzh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ittjtljl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bggptivu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmsktdk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fskooskb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2muopbbim.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbrqdif.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzaifry.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmawdsx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyxyzqn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnlijum.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzlkcuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvnxipo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pcekesxb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lpklnntt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kemocyzg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2inbygzjm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrmiktk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdxhpmk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2keudylld.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thrlubzz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdqsuny.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzhranz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cenjefuu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiaevnh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wgslaopy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjrrxvg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2akqonhxk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kboqhqtr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcdqjld.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpsojm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2asouvfzc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzgotco.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfhhrur.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2opztpgvz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouofzqwh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2allevgpt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnopxjh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iimkxinc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dukjmyxl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjuzvmn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qblmsirg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qsukrtdg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2plxnwwmk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhlunrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hygwfpgm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2acpugbrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfresqmo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpzcktt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yguolbsg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dapsfrsm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrtgugf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wguegcsg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiozlomz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnfssut.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2uylqhivg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnlbapx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhgzakh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxgbgpl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2conlqwny.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmisfra.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhhgwbo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdefxiy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2eamyjyqt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnkebmz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fygosdkc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpubytm.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqmpnhv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgygpbxb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoarlwv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tulxziwt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzruzpk.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwbxsgi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2famyhxlv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxwukis.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ovijogha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmibdu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xockctuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fwguonts.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kscsybis.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfudrspu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2duxsdmwc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbemmfh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfacardo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2reianues.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtptpvl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2btfohhge.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvphlxz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkywsdtq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2oppjvwlt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbksbxul.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2thorzeky.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoswvvv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fseimntr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdebykbf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2agvmekuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2avlcvfvk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lmapjdiv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2flatxstt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2emhycxzg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyilwch.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjylnct.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmmlrnr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiblorkg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlweahuc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fsupkmfo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwplulw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nejyools.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvpbccl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpajaxs.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlamswx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaaorgx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nehghbkg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aawkbzcy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zakhpxsj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hglvardo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxqsbjz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfqnvay.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgolwou.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bskjngnl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2edujtcjs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxucbahp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrvmgca.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmrvkdx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzdtbbk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzufnup.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aikemhjb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkwsnva.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aajafojs.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2irqwesmp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gowfryed.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlthgrh.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmriefc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhgyflo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoxqohh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2szxuyhaz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzipkzrn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmmiqvn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dbadisaq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kawarjri.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2osvemwsg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnmisbd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2peurbbnj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zevpqwhn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhxequl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoxpkpm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsxjwsw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyqjrgz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrjpuct.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfljsaz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2duqyfwpx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkarixd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuepxle.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hlitkzub.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrneqys.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsltyoco.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjddqlxo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsqjfpf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmftvqe.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cedtreow.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfaroau.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyjeqdg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnszdru.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjkoprn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbibdod.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ftudukgf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqkmivj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgjhxrb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2buctveje.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgwnwts.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfixbox.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzjbzar.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2alvmyodj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uiezyxkg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lvocmadi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xepxywee.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2muuraeqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbjlgbt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pksxkcha.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzlxlej.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crpqzmsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmomgij.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfutgnh.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dofqjgvq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcpgxla.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2npcuzqda.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsjmxdt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfvhqfb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fciowlgj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgciiyad.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsyriha.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slgxtxgi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaqmuul.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvzotyx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krozpmvm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qufohkbh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdebwaww.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyfdkfa.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjuelgy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiysmsmr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdqynwf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsywcxr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2slvojdks.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqxlfrv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2etxoakmj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwcsnls.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jwefoppr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vybcbpxe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2apkksoss.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfhmqod.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqveanuf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuhkyzk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdkbwxn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gypyxmkl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sicelein.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqujyebb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bssyyick.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxpibls.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxnlgvj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2naiijwoz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjabxlb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afsqmlrh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eapdwcum.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpxkbru.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkkkluk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvalgss.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfnfghr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhsraak.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnherbj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2asmtxqlk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rekdrcem.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiimtfwt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxnyrqb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuryxbr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vydkxori.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgywanzd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2artjwzff.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2naqlgphd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mblwavne.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpspcvi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkznpneb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eicakmln.html


<!-- 参考信息 -->