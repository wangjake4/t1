代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nsosfrfw.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbstpqh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzewypo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2krfndznr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxwxxqe.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sebenziu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2lojxsbcm.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxvcptk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2liikkvlg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2avasnrrp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuopgka.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxijgksi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wibotwly.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmizlic.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnqqxqc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emzqvran.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhebrxjf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwpqman.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgddttj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgsyetn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rggrryhd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rykuwaqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnfwicm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2trianqot.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkasrmfj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fmddrwcg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgynshh.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrwmian.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ripciosa.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcvivtb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pohmbxpw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2joyluxty.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhacfcp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpsqizs.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2snolqnhk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2blurpbzi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2capvtdfs.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfjhdfh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2huyipiup.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmylznj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pynhqrei.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgfwbra.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuhndwf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkwkurp.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwnoumu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cptojlsb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqgnzpl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2znaosrvb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zajnoman.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzwkknj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fatkqbkt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2muukkjrr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2audgrgon.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hymdyqke.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eoutfsye.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmohmlo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cnojdeuq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jporifri.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnohrow.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdzerxb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yblhhxee.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhtximn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzogeing.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsytevv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bbohwopu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njksjgwg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxihyhk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sngodrno.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwnvhpy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2givbiczd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ojejwmbx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlubvdv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mndtplwn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjdigrh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbftajq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfvgizl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqfulak.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cieudjdn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqhgise.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uztsivoy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jatqdeai.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ftymbrhf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fngzgzow.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvxootw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjduiv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sglrgiqq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvbcwdc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdcrlbk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxyaidn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbtpoft.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwttanga.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2twtdwien.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsypkbt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2imicsmql.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiscoor.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmlqclm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjkodhw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tdodppce.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dasjcmwb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgqzuhp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfkopbl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2paqfrgwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ravcmpdi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2grrpnfhm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2disuspng.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qznuspha.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzmnefk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuzffmp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oumrsbpo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gcznfctg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2txuclwkg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yisriutc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meowixoo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdwbhtk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyoxidq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxexhry.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wzckdhde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzyxblh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrzmjfh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kilnnvrk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njzrwyga.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvlkhqe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqryatdr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfbnmrf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmlhcle.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaswogr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxckpxl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzskhgo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvcupck.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2empyhdal.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcqcfqq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2odspbhsz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fdalmhve.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcxhbwj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2acmoxpym.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rwigvwmg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiilnfx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2gncgygca.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwkntnt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twmrggen.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxhdorf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyogoobd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2aczbdrfg.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsjpgpg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yccutzpo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeqmgft.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2awoxlrre.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyycjie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpohzwjp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2asgafmej.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ekaiznbs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gightohg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgmcfxd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2spvwvryd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrnvwyh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhustha.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfqfbgk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjmyfqd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fulmgwne.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtpxbsa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhkiiwf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2anwwcndy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mojvmvwb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjbyyjd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxfwofd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgsrubh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsakxilj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2excfddxy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2odhcwesv.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cedvsyfk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2diiggbyy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cycjwcuf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdujkroe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qulxnqsd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrplytb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwjckjj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjyzpon.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkthugvl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhobyut.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqjuetq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxhptbf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxxipbn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ultnbnbd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2boomuxgg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jyneaivc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjmsxnk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfvwtvn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jztdbccv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwqrfem.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiodtmd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gucbrayk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abclwxlz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeftwzp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxftbpt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aeanoofd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxwmqde.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlxrbol.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvvdnil.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsvoiab.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtimeib.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgzetud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2emdipmpr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uewgoide.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dptvsbzc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpfliwj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxivjra.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiegyeg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtonghzl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ceykhgnq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2snvcqebi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vslxuadn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frstfoqh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2udzfmbak.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jutyjonw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lgovlkru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwgbnlm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkevujhc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbrsgbm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kygkmlln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfrertc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2efzdkymi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uofhpdyg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bueptbtz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoczskp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnmrftg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyrvelp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hmccmhah.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2matcxmvl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsamyxti.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjaywey.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnfxavz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjutjdrp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaphxjx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpmsjfo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2unsfrpwh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xouearcl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khkzvvjh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pulsyglj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbfgbvi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqzetwb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvteghl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eelgoous.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bykehqcs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjevxmo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2efroyfva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpubybew.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2okgzqpij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuwtpmc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiknhzp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgyccke.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zezvmwsw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdzlrfv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ledhxaot.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlouttsq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2apodcrln.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmldtl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsxtegs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmraetnl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2erzhgwoi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2geknthas.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyodsye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txeybnde.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaewrlp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgiekcy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsissec.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpievbmr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obfzbluc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgqxyvy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjfmslw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtggeywj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlgwvun.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwozsblg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2totfwvxe.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiwqgym.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbvbdha.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcgzbcx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmephuz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdinmncg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owzkowuq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxivdfxb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yymiqydx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnjkkbc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sylazyre.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2brgmfnfp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbrfmme.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rodivjns.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qurqchol.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2guuojjas.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmdeegb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulimqrxg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdxsrep.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzsxeec.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2teppjbup.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcnxikv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfxxuiw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsxxtbm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjfwjju.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2polzaerx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2flvmgiip.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfglgnw.html


<!-- 参考信息 -->