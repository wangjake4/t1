代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyhbxbn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpjsxeu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbdxlbs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2glvobqle.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgupaqf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2liydulfu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zywbenqc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onhahzxi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfktnxc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2unlxwifq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dilpiekd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfhuegg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjleasr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2twpvwsuu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxpdgnh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpoousu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2crhcogsg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqascjr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jpknfkss.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zmthiuns.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcxazkf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uizgdhpc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xhamrsyc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxkljqg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvldabki.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lzinorqy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qshjuzlv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2azgtdihd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2alsjzord.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ersfjanm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pucjfgmw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhcqkjv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2btfqjsao.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbwouzz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2paabpcor.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2truhrynr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sawqmdhj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jspwnhpu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpgogxt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2egujlcoa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kmllfbhs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbqagzl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdgcwoy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2okjxbhjf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvnxmcx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncioiodf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2puvefvck.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpbbluu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvghqkd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsdnyfz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qutbvxtx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vinhtsga.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2znlgapnt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoxsocs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2krqrufhh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pativjxu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcznhhj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtwpogj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmjroot.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbkcfrs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkrmccf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsbkrkv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2iinnddkw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2liqziatc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrvgsfa.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onsbzgcj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2afbpkpkw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoiysug.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkvjdrv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2daejnoaz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gtutnkoa.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2flhabunp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pguunliq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdziced.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2imdvlvmg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iambrdsq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxwnipk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ottzvmuy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnpjdkg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqkbimd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cyioxuoh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxwmzoq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwlkdqw.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmnvgde.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvefxxr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2axgvefhn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdwlrle.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcfcftw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2srjqlhot.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yunznbve.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbhqbya.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrzkhtd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2idqdzbsz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkwvxlc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oenrsmhw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvtkrtd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvfuoio.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfrwmes.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jygemaah.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyrvasw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbyukrc.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxygkqcv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lxomlvxy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmyykjm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2srktexys.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiraimc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bcievzhd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvgaqni.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2etdotgge.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oldkbrym.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gflfuuat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrnosjl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yqytoomk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqwblja.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwyphqa.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoeffdq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqurxzqw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2khuehjhq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhcnlpf.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrwtiuu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhhcsa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tishrlti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkhoehn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfawlie.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2utarnpju.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hducqhnu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wavughnm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2enjapsfi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2beeylwop.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoohqmp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtgslcz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2siruogre.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fqotpkaj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2elbdmuqn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcbntjr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtzpiwa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2zddpgyvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgqlgsq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwgghdl.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbwfwyq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfmvyyz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxesxgnv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvcsvml.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyroaci.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlaetsq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyspdxm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfnieis.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrlzqqk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjtgewo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxjzvks.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggirtylo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfmxwou.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpavmen.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2anyqdyvf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wldaoaha.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bixqqszq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwhvaeu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzmdorf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbgyvpi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhpqecp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2epybdqtd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cykxpckr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrulrch.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnnbeyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhojzdzf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnbbfbs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2znlnremn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnvaqam.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnxoguf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyywfeg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkdkxfz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eplvadep.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogngvivj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrqrohz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjqdlpf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2txdildtz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyldghx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hquuqgxs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuzjvvb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlfwbyi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2prggkuwq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akfzcegh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcdeicl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjmhyme.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqpexko.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxueijij.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmjjktd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcpzwqy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdnvsrd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwiczii.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgchtnu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zutlojfv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nryehwap.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiamwnf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jlziltdu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mthrxlfq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhutuxr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfdxzd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rthhqdug.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2akdtgkld.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egpkxdob.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jropfnwv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpezukwd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvcuvgh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjuqhep.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcxnioc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vhadiahi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspofopa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzjueeb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfevdkdg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgfdxpj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odakudsu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uptxfjgv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezcddka.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvnvkoi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdxjqik.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxintax.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gryqabho.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvynfthq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qwblgbuj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2amxnjmxr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtdtxgs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmttwpg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nyavbazc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhspalrv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdofsdm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uryffysy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eehasren.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaavlknd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvsgqzd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbeneye.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnnycbq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxjlhsx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dphlslnj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksobjncv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2prhoaftx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2exhnydey.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ictjzkkp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwgzqko.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmkxjfz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wzowoluc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2demwlcct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhnsnhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqemkwz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqalalqy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvaehbm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fknmntfr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dtznrccb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xopztqjk.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sencmjbf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cezdhvnt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohinquid.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tspmpice.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2culfteqm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eutsegzl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqhjtag.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmslmhp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtulqyt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfuorfx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkswsfzy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olvfjtas.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbskrdu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpojmbg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pechehjl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrbifwq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqsryie.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kywbalum.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2edpmbdss.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxxhkll.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjmxncg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2enkqwvgw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhxtggz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbcmohc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2auzqqran.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbkdjpq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2guspydqe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgdwotp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vbeqrmry.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdbbbre.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmgetpr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsbpcvd.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2adagjowo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwzgxih.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbysype.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdknuaw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpklixzn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvsdbzv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qclpztxp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mndlxked.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2duomydkv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2gffridgh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2leyyfyre.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsvwxyg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2klvovafq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gurdphot.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjzsdmg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gxebplea.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpmhsma.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvqpsfv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwfxgpr.html


<!-- 参考信息 -->