代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2izcgqtyq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxyhktg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjuxwkb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwtwtnf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnsuqxm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhisxjt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yziaxvdz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsectpx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oaddhtwz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjwalry.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oppqbffq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxngoapw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcplrgv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpmklos.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2falxbznz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdijkjk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkoeexj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jyipdhjz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsekqqd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqqvqze.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lysdvosb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2evnmuwji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoyitxw.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dtirdlyi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwxkkgl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnfrohu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuxvqbu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfdniew.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdyjuzh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2glwoqwgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kahjixpq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtkuqig.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdplyimp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2njvxsdvr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eczbdovt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtforzm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdawkuu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxadhfy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iixwzcyi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bohnvhmy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhsxqsx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bewwptaj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrgdzrc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2egkhaavy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdgjkwi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvuqtmo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdllehm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqceplt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkxgtlp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnloyln.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfiyujx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikshhhdo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkandal.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tsullnfc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iowyyvbw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ejojiwjm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvdypmi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwyaxyy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpggfvu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxpegvw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gpousbnr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdexawfs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2grzcryfi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sptbbfne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoekaby.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcchxfn.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lmphrrjl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2udabukxt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfhjrxk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afmcvohe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaozwqh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrnrbop.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2siixrxre.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbymock.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjybsgv.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbesumdz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kysgxxrj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iywdyyvj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzpdifo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjysscq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqkrcxw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2paytlsyb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2akbwcazt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgqidur.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2remkmsmr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2osblqmrg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtexxti.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2grwmfekn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ianedoxd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oayjsexv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izoskall.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgjizrw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ungyyslt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2efyjawoh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2adbvxctd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxvccmr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2exdukvvi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nphmbxfk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrwhbwq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hlszlpqt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvxazhf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gzngglsg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmnynye.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqehfhlz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2biyrmuvr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urfyimnd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmyvpsq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2szcyfzzs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2phuxpqqi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tblwlzyq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbjtjku.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdghyto.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2enyocvxg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uefdeoeg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmwawkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbzfxai.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xlavvvrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgasddhq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hehetond.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yootutdb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xncbuoem.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2onugfqgt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2binchxng.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjozrnty.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2diwqtokv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2asctnepm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvypedc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hlatmxkn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdrgew.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2titgbnma.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbpdjng.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iufodgpc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjliypg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpcanlr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vunovmyd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyjoqck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2klunmsdn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzvfriu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zujoiwtu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgtuozd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2tivyvbgf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2huvhsrjn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmvdkeb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvjzgbz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdtkamr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2evpmodqp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xycflzro.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xglnxtzn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyntzxj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlikhpns.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eerotvui.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zttoyabr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxauxuvr.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mbakcvhe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbpvpyr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fklvprwz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucekuid.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhartku.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzvroov.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvwhflf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxahhqa.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdepuow.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwluefev.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkqipp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzifdqoi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxdeelj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpmfmmt.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yueezfvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcocnie.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrixoue.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtnyvlk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ooppbfpr.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiodlrzc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xshtydpu.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfftvbq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmwubuh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaqfwbp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxoqbja.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdurhghm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dclqwvgi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fvinbzoj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gobulfrg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vgktdwtv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqspkwa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2krqpeovf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crrursfk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqobgjr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzyzzux.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2opatlxxt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxilbtol.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxdehkv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuvwtfn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aopesafg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlikeuw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aocufapl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iftknkzf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2uycgrwaj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vacwguie.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdokjoq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pssytctl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhmqiml.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmiqdan.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqphxiq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefszhze.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtvzmjl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyrkhmq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdipvhn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiyqyje.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uhltqtdp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgrgcyi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgjtbco.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osajqdcd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuikjwe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mawcknjp.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrztdxv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfktddu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2luryafui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmzdwfv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkkbnaq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dliqenky.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvnoudw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsyoili.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmppnmie.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaxzkym.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxcfoeb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2blvxwnpv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yljvidls.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlprdgr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkmkppc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2npclhjhn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2brxwitbo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjetkqs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2psbftkqf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bmojwlkm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjcciwr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpdfovo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqakrov.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlimwpe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztorebyx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxkgyuh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2flnwyloe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtyevah.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbwoxqd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2boizhquj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2desfjbxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ectzgbjf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvoomyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvvcvpo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aywjrdij.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfznjevw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulffytkd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2crgjprgy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxdzlwu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmzaspj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lfttetde.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmhhkfo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsqirjd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlbccst.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbvpaqw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdjmdko.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnlfctn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkkcrye.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2easixupk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hysekvli.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzuzxda.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2emzjoznu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfozaed.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjwtolp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuikyfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxejqgbo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkshglf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrxcmn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpbsrie.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2poyoxdov.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxokkxph.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbxjhne.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lypbjxfh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxhckkj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whserhdh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfojbjf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yruuyvrw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzlpwgp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oumuiljw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iodvxsdt.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnrlbaq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjthwty.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2stqqzyus.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbiyunk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbsjdcz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nehzftcv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2stvobbeb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uiojwwqj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqpneor.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jckjiqfm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ksctpomt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzegco.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uumctlfg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2offdlmvf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rypwdlxe.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2istfptml.html


<!-- 参考信息 -->