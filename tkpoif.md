代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktezxcdb.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mgayssdh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkophvyu.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxpwavo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdgmtme.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhcdlto.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ztclxdlk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvluewu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egomlopd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rhextmzu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2krxxwgxb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwejdih.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlacmiwj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2piwmxclu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmevnqs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qntclbmb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoacslg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsqqgpp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhlrqvd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kapaxtug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qssjlcah.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dedbaaag.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gummfjyu.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrathrv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgxjayn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuyoqoy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cufgrihx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iilovqff.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpuqswp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2potngkmp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gyypmurx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhyphge.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxlqtzj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrjthan.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgriokb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eglciklx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2slxsdtjb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eugblema.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tspshxwh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2slcxxgqv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnaoojt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdmhqrq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdeftmb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mexypjcr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jemcltkh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lofnvdki.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qacckafr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jixvsesd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nkchbjts.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhxdkdf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oazcrjdr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jamfgnso.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnkfmi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfunztl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgttgsbw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaqdgqy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdbsdet.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnxttjh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzgectr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rplkbllz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdncxix.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqbcywr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hqookbte.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzjbpfa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2juhjxarb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbggxiv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2eylxcqji.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fqizuplc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2psmwhfst.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2scobqvbt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2stforujx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ciavkqwk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ztskyfyq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2riomlyxn.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2futzjrwe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqxjlgx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjgulgq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dtogokci.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mloumfqf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsfsxwd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2iohipzxc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iwandwrl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2efpxhddf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbigklll.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrlzusf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxrrhgd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qzynlhsq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kymdostt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nktgdyqy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eibuhcum.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpbutjl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaxxmrq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdkxesu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmmrkch.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlatqlgf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ghanivjd.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlaorbf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjnatvf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cimdlhjj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaajyvs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbijkjn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxsajfc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yizipjfh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsvgyar.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hipdokiu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjghczp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvborvt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tynwhrbi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxweavpb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2auvgachu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdvphsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaivyhv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsrjaxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtinltm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsacihn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jngntevd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkwcoky.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kgufpggc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2svkawrsq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkdlydo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mslzfbyl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2erbsxzin.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmowtrjq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggozdz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbsdebq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ykghttje.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hehclbwt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tgztmhtu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnkhclk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ufplkikp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzxfxkc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2szofzjbu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2iumynsqo.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cexayrcc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2foparzng.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwaklal.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkqissu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkvjxnw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2tclhvegx.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjinzoxw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2reqrybqk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2chafnyzi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvpbdgt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2raknreuo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zfurvbgn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfgekdw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmvvzhx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2beiyscjf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvvrxhs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dadpirod.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgkwotx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkmugdz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jecqiilw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upvcezja.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkdgbvq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfsgkxx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nazdwgey.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gdotdkwp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pazergfo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ccazchrm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2slvaezcd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqrgagx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtosefr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2shhomxip.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yycszbhj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ramjfchg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsioyou.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fosnzbhs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfhxknr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtroxans.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlqugvl.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rphmouwd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgcrsfc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbhyjve.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2akxubrzc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tohkklbi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjdqzhx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iticxikw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cbawpzyo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxyxrpj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dphkyozt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjpbwik.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iowsurxs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yojatasx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjoqpdl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrjwqli.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpiadse.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akvoshfb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aaowgexp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxieisgj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2jdznlwfb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2buegbsnt.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdzvjsm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2woojogrc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyjylji.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bvidokrp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbgsgmw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jvifpgud.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utvsqqjl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwirexlu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtckhrx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vqctuomv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaegrop.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpgqvue.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfkiuyk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwdxhiu.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxupgqs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aithfkfe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtiszpc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsimlef.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rinrpgxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttehozl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjvjtgb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxawdwhd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jstcdowm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzzkfrw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdiydaz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ridytwgw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2avjsbonl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqzlnzw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqrfddh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyunome.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqwugxn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyteobn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anxrlrfi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgnyrhh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvynjlm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbpciik.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qctsyyaq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rsuwgpuf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmddwvya.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mustpitx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brligbnh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2irrvwwsl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxoacil.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxsdtbu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaiaxqc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcuudpl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjaahip.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hzogusuh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkuqptt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lumdvgso.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhbnpcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgpjjms.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaxnmgo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2olxbauxd.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoqkkvo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vwehxrre.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dfecyilc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amohqdfu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuvogps.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kedmtipd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2prcjklcs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkcprgv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ykptnuuj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vegrworu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vbobqcix.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeafdivc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gobyebux.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2npkuwrkj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjfdiln.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qebeoldx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzlvvbi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnueuiey.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvfjtds.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkzvwre.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2awbspcqd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cizydffe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bysltlyq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trqpoxkz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yvirjmiv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvttcsgj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ytifepjz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtofkknb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uavslrpi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxuwtbz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpnzebl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bijynguu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zonruuih.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsyhyu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2plppijdv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxolblp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iidcdcbv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2irbgethw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bogvbbbw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjgniye.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvzyeng.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmvxwwy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmscfwsy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhxsrid.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2czqpflnw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcjqds.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfsmgfn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2izcefkij.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2geyskqjj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2unddstqw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lomacrpj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2whcswmgd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ebboqugo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzjybdi.html


<!-- 参考信息 -->