代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhpldhr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqfaoud.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgccoumr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qeipapij.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awyrsncc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbniakd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpurlsc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyfrxvt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzvxoju.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2leswwdcz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lidtbkpu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuflzvgf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoczzob.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuclibm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2sussonqa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vajergtq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxynnium.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yunddjzv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwecgmfr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2umuudxsc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrijvys.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnofoxsj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvnufld.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vphjtfgl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnrmjuu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pctvvyfl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vyprqnom.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zumtepub.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrqhgjs.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lormzhmf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kkalkjub.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2keglzqrw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nijqoylt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2frujicac.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2miagbjrx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2izmrpjyx.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efgjwrmr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbluwpu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrwvmaf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qouzyvyt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfenaex.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vvktmdrx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmramxn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnzegth.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeyvkez.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2awwmmkxh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2upeyqqlf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqsukye.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bymmvjiy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmzhpwr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsjpqsd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2otsgzwyq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqthbxe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vnujhyyw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abeljvjx.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2phpknrvl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtnoxvq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oysyxxap.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btrjntzo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2urchfbwj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2prodigwj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ognzlahu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2naxuhpks.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfreoez.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gglmmhou.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nubyqime.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2babmtibf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2agbfezlv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoftwsu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtvckoz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2adfrltbn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cqanuevo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gumpyzjj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gciyashw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkxsdsp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kvygwmww.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvkormp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfsybne.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qearbnta.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2biedazxb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zvraxpiz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsoqayt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaoizko.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzsxdnn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xcerekwa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2upjhlbiv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqlzbhi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkxqpif.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsvjhyl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkexajb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrktgqw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2eygutcfv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tfacuvfl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjnjaxn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2owjxconh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uaroaawl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tctiyova.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2glopxbhq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbeonjz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ulejodff.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvwltki.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vmskystd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eseykvsl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmrmaka.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdabzvdp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbplywh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2upqyzzuw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2admpnefe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgarfnp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2liajhszh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fytlljlt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcfdcgq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sujxgcig.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqklplf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2njkxhfak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kweumdkz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hzycaljj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcqeabp.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2abapslor.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2juluafys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxtmxob.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2paccntck.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjhliix.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxeuidm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zskbobub.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zygzdvry.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2noeuvssm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qitrhkoy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaylypp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bddddnpe.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tckvvarl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lirilipp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzvrfbg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yweprelg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qixmemld.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gejnqmpj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhgqjly.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaoikrn.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tasmkznv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oowxkrmd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsbapzj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxhlmdw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xccglhss.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxohvlmi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2polamhlk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2waczdoof.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2phidqxhk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2azxqqqgl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2szpueudb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmezbgt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2imdnhdtm.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzeiryw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjthlum.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dabtjpew.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnhswzk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqliqxsq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jficvsjo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmztvfz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khaotqnv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fiemvjma.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhmttcs.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lvavrzut.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjftbqt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2myjrxtie.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixogpre.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbbpguv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xflkapvy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rqicfjzs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpivpph.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uehahndn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2enofiktg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2seemdnkg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhazhae.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjyihml.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eduqedqj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkhardo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnflnyp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzyfvzz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2cioerebq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2kuajoglp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcfhcuf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvhmqrm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yohripiw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaocbud.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eatwdkvr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnldmzd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jymrxlut.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtucoos.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbzkavc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhnpnue.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hdobziro.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npzmimfp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnsnspm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjtzgc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2afyisiwj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dduzcvpb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lafslrkm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlvtlic.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwkloxq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vyskxmqp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzpdzaa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsvzhvn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mirwlzkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvkkwxf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tykqmepj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrohrng.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcjqrgn.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdalcssj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dgejnybs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufttjlkz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsnscmj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuubaox.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aykuasbl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzovzhbh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ousnxdgk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chdchmtg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nracgicv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oafpdrwv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvabnsut.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gslguead.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2htkzzdjs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhxdlxf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnqaqsn.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqfykcs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hixegzfk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtbwncz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2proxcfev.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkvaraj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwroyztj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2olyjkgqz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbjfpft.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jokjuesk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbuyhty.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2allkeqqg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxbhdos.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2skptlzvo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ostvgwdt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2asqcqxxe.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsnxcjq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvcreps.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsggnpb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqtqnhc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzauyipj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odkjvevo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvydsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmmesdn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zirukmou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2scwrmoqa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxbylmn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2alvxqeiy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2forkxiod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yantoqoj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbjvtvm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2httyhctd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpcxkhx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvdwryh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjybnauy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2evtufyfd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2toathqsm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trszraqw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxqhfu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qovizzaw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pezcwoul.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrljppk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uednzqsa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgezsby.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmuxcgz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjghtubu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2phwqmewa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2atbmvyfi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqgelpn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oalqkcda.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fytuityu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stjjwkgv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gfstscqk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwhybxr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpfbhhq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikshyykk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vppgohyr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yygeeezb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2romdwadk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aghoujgw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlszzpny.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjoypvd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2phhtaugb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfidbid.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qluprnkj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzgejpy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zccyoeju.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzvktii.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpkqyna.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpskreut.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csibxfkf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbvepqm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpahzav.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bupipvzk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeqrmqi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnqabza.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fzohtyjv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2byagalpz.html


<!-- 参考信息 -->