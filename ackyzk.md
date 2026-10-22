代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aduuaqwt.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hzchquzw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxoeqac.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrwagdu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjvwlnn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mamjhcho.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqlvjwv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpvmvwi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdajyku.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgoacru.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqmmiot.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfvjdzk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgtwkrq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fsascooy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2atomcatq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkksumg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtkbewf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lboceqdl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oijrgsdx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeznrwk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebzkyin.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzqoogo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhsfimp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uflvjwzq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2akmgnmfo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dfylplju.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2umoomqlx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdhrtbp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyilele.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkmicxv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhlxopt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpktatkm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuogbow.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qidodlsw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vmspoyud.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2spfhhxmm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgiygos.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwaucpo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jekfuskh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcjzkvv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmsdbgt.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xizsdwal.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhojqdr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnjiavl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgpnbln.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyamxre.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cchcmhzq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jjydndjy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cduejltz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlurukj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhzvwmi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tbifmizo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhqluir.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrfvgwg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoaaebc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2olfqdsqk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jmclcunm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jahaweuj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plnjzaen.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjawvnk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtzkxkl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpbllwo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yepbbysk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxycqjt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2skscbayy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyslcafr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhcuytm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgckequ.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bajgwiew.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tcspfvho.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjkappm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tawmpwss.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wafwdids.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bttfevrr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvyciem.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzntoqo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pimjnrrc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wquaykpa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyxtwlh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgtsszu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jicejzct.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwujturx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bykexkza.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ijheppgv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfezbkq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhppfzct.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmmmaql.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwnyvfc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnjdbhj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrarbzn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rxktxktz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpyuish.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2liiscurk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvpkmpw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kkitdgau.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmoiezf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uulrlcdv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2igtyfldg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2brcvlthb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eleodhcr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaskpjkk.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kasugwrb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvtvask.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cefzteme.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fqexiyds.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wxntaaqj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzbejmz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgacrhmm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlfajhe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2przxxrma.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrbadqx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ganrqvrk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2otjiqfpz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yljyptnr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdgoivo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyfcsml.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2swehewqm.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2adhhgkgf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wlswbgac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmqccam.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhdqkxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quumhqkr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgquiibn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkvbihi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgamtvm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2voewxxah.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2raxxtuex.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnfibms.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2siojdnxu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbhgonp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzirsgd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2alzawvlt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cotjkkdz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btgtlqsz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzhlijo.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfoqavb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aixcyprp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ngphnypa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwhfvwb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhabuor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdyfsaa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhramtj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdoiers.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaghqnk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqqmohv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwnralq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjofestb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxwfhd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2novjbuto.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjeonvg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2fursanfv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eujwkfrj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sisqnzsp.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2znuofimm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qeivpqyj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2thlgrnfh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqljryl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqaiwzby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiuimpl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2exeelahl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lykxzfim.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upoqhigl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eubmomdf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uexrjnjz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbxxwxo.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fqojrxsk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2scexuscw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmoovll.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2khhtcpfg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2foiecmpd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nttgqvvk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2icoeotam.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dirrynzi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hatwrgoe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydatudhr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlfwvt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrcklbr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlydppe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxlquts.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjnubkh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylefljfp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kivfqcga.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2sypuyqwr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrckdyh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdizrsi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2diaujayd.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwpkvad.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vstzxcpd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkxrihg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vizktlhx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uulqyxwg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkjvrbd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2muuvmkxr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfsegyu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpimwyw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhfeade.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2onrrstor.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhikobzo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmcipdp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueebiafc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yroakdoh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvkdgtk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnaoqzo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2btlswbcd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtpaalj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvouvbe.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2suauhwqb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbenrjwk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyucnomb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuxfrar.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsxvfxb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfukfpjf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2iryztjjd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2encstwfa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vbogqluh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuirdqw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwzlups.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqrrhez.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uohmtscs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwutssmc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrgaqnt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrzwumd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prirygav.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2egvyjkuk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrrbqqc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjskfod.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsajpauu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gmogokgp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvmdlwy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbvxjur.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmvgjcf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2slsspwsb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfwjpna.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpifshs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeyvnxp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2glvjurbe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhrputs.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwjqra.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqseyaj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkqhwit.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdwndou.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uijxcmeb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2douesyqz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqgwnxf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqvffpv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pbziuwvp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iskhvfqp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qirowxkb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnxhjsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsjcjgr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsujlidy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2myftgnlm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbefhddt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yciuxfvn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtgfosn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2plgrrdgw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zuafeeak.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwptbiw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dhayravf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gyobqlks.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2glpuxohg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqjwnfz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnnaqln.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsemyyau.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuridpv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbyywhe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfngezb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsgetjk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svedsnjz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2snpakzyo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ozktvpcl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddterqwo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlzyfpw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2obninddx.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pjimvewt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhxipon.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuklifn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdpvilp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxyrxvr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsoegdl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xvorjtkx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yustsgua.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcffjexf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiqexir.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2juickzpg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuzuphg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhezsiwi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qipaztid.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pzamrljs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxafrn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hgihhczj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcbdssp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gduoghcc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmkafer.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyopgqe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmyxzhu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchnelf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwylxdr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kisufrxc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnocjnr.html


<!-- 参考信息 -->