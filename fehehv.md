代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoakwjt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jptoguav.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iszwxjkt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyarbgw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpearcje.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2paiqvxwg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vemtqgtq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlpnolx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akeebzwq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpjsech.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbolmkg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqsrtng.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyyzhwz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzqglok.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jlznwbul.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytspztxm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jggbsfcv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmrnogb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhhdrzf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cqijjgrw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejggrzac.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uzagpaoy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfrgzay.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ispsdcfy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2buukciqk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfryozv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyqzulb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bfziqqbc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxiemnq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yvflvzey.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2grbyhweb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yazzhwjj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnzmuoz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhqepqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeukppb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeasiue.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2spzmczfu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiivxdw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzmdhwl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mdydjeoo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpqfbez.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgqkjtm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqrbwef.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2deojvmlp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvvdwlx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnjzeef.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2otuswiim.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsxgagh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ruikjjec.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrnzlku.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2twcaxdhh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hffwqjqj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqgbinr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2utgagfwp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdkrgow.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yubmuejm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2esnsdoyl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgbkhgp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbngqajw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczlmwa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbnvzqy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsjrnah.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdywmwl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnhtkfc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2olcywrei.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqiqlqs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnfptdb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmfqpdt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeahbeb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzrnnmu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2moztuvsb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzabsst.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbsozpe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnchpgog.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpmaypt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ebezrvch.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgguvhi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsbitfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2spcvmfxe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdcxchr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2suvzbbja.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgoustey.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyyiyqu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlyvpwv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mazlssmz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhvpcpa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhmaegl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wntwbgag.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2huzztcww.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmknpwu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zprvfkli.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zngntzlq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2glhgmzdl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2igjxxxcz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gikgwegb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gohogndm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmaubxw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2euvslrmv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqonqje.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcigjbn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmbkphm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nwambasq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svpiscic.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrkilhr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtiqvhp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxcoclx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jekmfonp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjrexgg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2iosrhbvt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcprqsw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2exiaawpb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ddncwmtw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmdhljs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qowctvox.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exminbxc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2laincyeb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eazjhhti.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfntawf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2biosmvpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjueqms.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxbkiiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfinxqzq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbacunfh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxaqkph.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcowbppv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmgknyk.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oankpvwe.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvdgkmd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwjndnb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2javbgdcr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtrqhis.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xlezxcwa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxvuqdw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbbdhuj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hgilxowq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeihyzg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzqujma.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ffptpukk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnckipep.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyqbnox.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeykcxs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaypeyq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywebcs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2senromdq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjfehzz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dumbjivu.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2luoaindx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vquwxoga.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbzuxok.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfubjuwt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyqvzwi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jadqbvko.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2olmscmiy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2stbncmcx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsvmpuz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzwxmsu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2spsvlozn.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqfqlny.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvapcahl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpyoujt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbaryst.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwtwxit.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgggjkv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvilmkk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtafusy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqnwco.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gijqlfzn.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaeivfm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdrxmwu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqgmtpu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdutgnqx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2basubvft.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2juadrvow.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnripsg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uconsoag.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ssutsztx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvkkymy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuctaka.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kseuuuxt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aoezovks.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwialyud.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2scgfbuzu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkatrcx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2svmakgqf.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnethra.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgfsukr.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2klqlzppi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acopqjsh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2phcljbhg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vosciucq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjmtiny.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfbjzdb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jwskctne.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxentsir.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoqryxq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdigucx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlaidwu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhmatsy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoapmgu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lliieihs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2txurdush.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcedzodi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnaxtef.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2shzcsodh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsacaps.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpxdqbl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjpozzh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvfqecq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmokaysv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkugekag.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnfvxnb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bolpalie.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjzrdfp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqnagi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2oysuifga.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqqrspi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcyamtm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2miphlssd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgvpshk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgahoksu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmnfssy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prvmudje.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaaffrv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yftwpvxl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkbrmob.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iumiftye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxqlyay.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bvslhwao.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaomipkn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uozelekn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nktbuoxk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhauixi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcfrlmq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lypzkxjr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2egsvhzbi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqzxtfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhmicol.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqaoiio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnzoyio.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuellsb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvgwapq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2udsxolsx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgdurej.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tuipkjlj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2spqinwxq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjmqing.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2upfikrai.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2balnbxto.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zswkeusa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2poxtcsov.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdieodry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpxjjff.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzhvhgq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmewroj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprqair.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfgbzhm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmuhlpt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuweyzdw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xaijzyil.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgpaomx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiquueu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zrburozf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2olfrwbcb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiwlekz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwmxure.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyhqxht.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhyqthe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvikjql.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdimjnd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzyrdij.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iebeqzhz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeomlht.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qptjelrv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgwfxwn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wehujmdz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcgwsbe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqwbucs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhrioxl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2obnjqbru.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jveyqonp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfnpqpr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2biwyqzci.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqcehqp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2arehfqvg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yitjwbmq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxtltsi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxghixr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvjeeqe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ziktpneo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uroxrrgp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aryeopyu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2thwgelcd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vumdpftg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yypjosvj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsnhrxa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2naaxgsqx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awodljfa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvqgncq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iycgslul.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2adwggaqg.html


<!-- 参考信息 -->