代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jktvxkqn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tioxwpea.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smwltoht.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vckliges.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fucuokzn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfvgiew.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbqacdb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2juccyiri.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qelitvim.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2drifrmhz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nrneiwnl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmxrcwf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jywgbiyo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyiedsh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkguzncz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnlahbf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnepiso.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oskywczj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrplpxvj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvysrla.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqfvgla.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2idztuuae.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqfdwmx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2menqslxr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2exqcgkte.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrumfpg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2itndfkbo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owelqtgq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoorrlvw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2irjgoexr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjwygnc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbqmutc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxttons.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drtqexfo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aclrnwmo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2brzssjti.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2psbsklsw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvpownr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dljpzybt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkifautt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqibogf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kntrthef.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyphcuz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoqfatu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtfjxis.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2efkcbzgk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfgltsw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmvjlbd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbikxqir.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsxhvjw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkkenrt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hshctjpu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqhcato.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2olxbntkl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rknxueyg.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmnmiow.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eatytpil.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlbcxkl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpfhpue.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ipixiubi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeuxdox.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jilpcwie.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsgjwsz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ltexmnca.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2enzptnul.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpclgkt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zffwjokq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjjwlcc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxttang.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbwedoi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdbyuup.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmzpadm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwmwzlf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxgompg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pvruukhb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yaefttnj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmwbokp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdrkfid.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cngwqkbj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsubtjc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2abwywmji.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bscdhbtn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfuaxce.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnobzmo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cczyzyyw.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdavkov.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xypodzct.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2spmkkhbu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxwosvw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2asjqwdwl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcgyjly.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmvqify.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zotshfov.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzcdczs.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vnidtuzs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkupxzb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcrmfjr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cqstrdls.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2conbmtpm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyaeliu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbqtzgn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gnemjtnh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgphteoe.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gamiapzq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaxgugo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qswkfhib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxbqxue.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2thltnwzy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgkapdd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzbsbcq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbvtfvz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yfreyzjc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twznwlrc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ivasqmcl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2erwxnctk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgmvsbi.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwwawsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quqxvueb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nepzdxnu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsjfyzr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtlgknt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2seaedygk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfswjlg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2caccmpgv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbqypns.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaubxjk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxmsdx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vsprwsei.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmklhry.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sraevsie.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpsnrrz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwflvgz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmpnbrq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuyfine.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2sstgbcsd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbgqkpa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2admlpbya.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2craaxuud.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjweyucz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlyeivn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2vojkzvwg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrhvxvc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2edncasnk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zojixxwx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkolzmri.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kacsfuzi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yewjtlnm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhbhxil.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkvvuim.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnesnemw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcgnfta.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lqklqakx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wibqnzap.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ystibbqq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sftkrjrz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfniuqc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2otcmvion.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrivkho.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tggglspb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwpepls.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pymonsan.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zngcqqpu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bclbjwbw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kdryczjh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtvwlyy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmolmke.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjmzkcm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2paebwpkn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lydrnnwr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2shtjkhek.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbniwut.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fchtciwr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqklfzzy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2imsdkbqj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsoxvpu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wytwakkw.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlbamdw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwanebq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaoaxeh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwyadex.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjoerqs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2agsrfzjj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwsodf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eoabmdem.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tysbhllm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pszbyzfl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfeaghi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ofllrafk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvhbgrk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkvuiud.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eowfmize.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csayrfks.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zojnlakn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuxdlzs.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2atvobkhg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcvbvju.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbhewna.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ablahxff.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oderwrli.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rnikxyts.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnjfnds.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wgahtekc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2psbvdrec.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2indglbts.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtyrdzl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ircnasat.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2inbpmotl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tphoyseo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaltvtd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2auqrjoxu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpwkmkb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sacupwqc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2laxmwvix.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyabwkco.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuzbyob.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrnqgje.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdzodha.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcmveux.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzwjjfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuqbvlj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxgkxxx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzpdaqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjzrvra.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqkueqi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpzfrrd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwfklbk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ymokfrih.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbwobbm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpujbykg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kfedqyyk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tooenvvu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tffmlxce.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmgxypg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2skpzdzqm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvmrajq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dobdhuib.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylspjluu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgadvof.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2reivyubs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2osdlqbdb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrjfbaa.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2flqpeyak.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhajwrta.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhzawsu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ealdwaav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmnbfwv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2amhlopyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsglllvc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vaewrast.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2loubcrsn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrhddyt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vahusopu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cklqvqqn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqwgeeo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iazuzffq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzdhmmw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nniziikg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlmavlq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axnnskdw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trynoeai.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2prkofpcn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wesfyvui.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhhxkuf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oamwhbdu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chexnipp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zizvnlvi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtkwyep.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjgxmni.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaycphn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2woivaelw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yuznzgba.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrtaxzw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2teqacdie.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2joaxhtgk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2duqsilnz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkivqfp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lqycyrbd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mucroprd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxnxtqc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqbzcab.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2acmpwdvu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2soxnqbpq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkhcruv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfadlyo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzbvqnn.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckyrhg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsujirq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhfbcme.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihldstpt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgknxxbo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gajshdrx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcrafph.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plvgnfoi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2moqilqep.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2snnhecit.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fytpmhqx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2faehfnum.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2twgpyjdr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrstrol.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2klldblsr.html


<!-- 参考信息 -->