代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcchtbp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjzrvar.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkllnrr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2plecpzzy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2aymyultq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qemfuzax.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkvelmr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzbrtmo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmcidrl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkxmfbe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uakwjqil.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvwniud.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2athdbxyb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcjkecz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmngnir.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxmdswk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaoedbo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgnzpja.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2npiwrobv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2udabwjhl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2izblkyej.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2exxiront.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdyjigl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzwreep.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhebxdq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ciczwpeb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pejluged.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzuxuir.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsbsbda.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hokawite.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nkagaszr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wmukhqcz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyhdibw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2silgptum.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbcolwa.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tistlqpb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyzabxw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrnkxvz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbljtks.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlsfuwk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrromzr.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxrnrpv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcauipb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2baqepsky.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2silnovay.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbagape.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2embabpkl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aabvcfaa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyhwbyv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2snacaxyt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2guhqgadw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gnibflxl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xwccflrw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkwyxeu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fktevbcd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmyhabe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpvitkm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqnneap.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2verbxcxf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2kaohpvcu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnxpgvv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2huxipbdb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgjfjsd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjzjwoj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2fqudfyxn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrxtiyl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2egvvywnm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2quoiidnm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xovgkgno.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2okpedtaa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2utkrnqwf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnabqek.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nhofukwt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sczubgak.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnpfcec.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2seyusdlb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iymqyjpr.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2majdjevf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxumlrbc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuftjig.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ujulopsy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbeadrh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gkibrlny.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmflencc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2enmaxpvp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsznyzbe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxlprmc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdelvbnd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kddskiwk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vimikzfb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yvphanxl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuvquyz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgsbnsg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2laipasmt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbsigjb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzgyytx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2eeizldhl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2itrzgoaw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dipfvaki.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqrtlrk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsykacrm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoodoyu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2heicrtyo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gxscunqj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzjzpru.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyobrtk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqazbotv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ruieizkc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzrgsni.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhgmomu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mehbupyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sadbrdsv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qiefsutk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izlfyzfe.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nifkgyam.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2eywzvvdx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kickihng.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnuwjvn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaogrni.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wizilipo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsunhnx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpiimrw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvrcvux.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tauoqfnq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwrzilv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpkpuuk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2doposxdf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ykobdzka.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tayibada.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgmjqou.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxzzgzn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rpprizra.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nocduvwf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxiufvh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mibplifg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gftgicnq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbcxodh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbklwriv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpakfvqt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omrkossm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2csdgshju.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2feliiajp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2citroujo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2avxyeutx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zedwynka.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btpcjenk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbebmwj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwtlfuh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fummrjxy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgfebxw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdirtoai.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2esipvwwh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfveopxq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxirblk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvhgbvu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqmqdo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbbqfqz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhubuqdv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwugrtv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeylbtl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2teoxqmjy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2izourtle.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2twdnlrsa.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvinkob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2idipillt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwykuxy.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lprjxlvr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nepvdkoy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzshqnio.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjjclkk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnucyskj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxywvew.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfdyiro.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuaklni.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrfwumr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2trykextb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qpckibnp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkququz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwqhfox.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eckjobrf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvcmcka.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nznqgzfj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxchnhc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lavzzwbd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmdspsa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2okvilxle.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaxlqvm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxrbivf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcyyrmb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trgpfnye.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbyfvrz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtioqwz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdoavzo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2umgrnljt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxyxsyu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmphogv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjvlnb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnlbxax.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eikkzydf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzytvxf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyssyzyz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oldywfib.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gznpvrzi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkglvvwb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bikvpnjn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgbarop.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jnucoggv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snwesrfe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqrquee.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjshgn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dehuracf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkcdgdz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kygtvzma.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zobnwmdp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxirwrks.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeijtxt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrbhesr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpwroti.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsaatfq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2icuqgphq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fexirhxp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2slupumtt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgwmkkk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fiprlebj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqclpvg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2idlnlrkp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvqmgxh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yjywoquh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwkusa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdixvxi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebudhhis.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuhufta.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klhochii.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdmttwm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zggwpggy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdszijq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fryofbdi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyvebdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmdziye.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkzrvxx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2imdijzsu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mntckqli.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpzifqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pryybdip.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qsybqgln.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnczsdg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxtegmq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyezmai.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fyedttzl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2huoccjha.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zwopmves.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2diopsfpi.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kahofgtf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvkspwr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jqidahlt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kddwkwmi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2slzcliss.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddyraxp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nliyjpxe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgptjxl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2detndmlk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdpprkp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwjvqhj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vynxnehj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhertkc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvusxupy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwwpuwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjktvrvw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxwakdt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvnpfys.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tedgrvkt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zibevrsa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqdkgql.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrzftjs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuutmqu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxuotoy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzfhjqy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxfxnir.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wawhpydj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2acplficc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzyuqxe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfxzllt.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeafsyk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wttgvirh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kcckjmak.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmpijns.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxipkvy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2raabwlty.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdakhej.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvxyuwr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzyuqrs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qazcosqe.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fftnaxeh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2erxbkxgp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2isqkxnxt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2myaavoef.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqwahaa.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvgbfzc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zqluzfrv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2djeookxx.html


<!-- 参考信息 -->