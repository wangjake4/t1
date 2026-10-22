代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kflypoou.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiuvfvo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sawgihxx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiwodvw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2hijumxcn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2twyqzysu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vohiudei.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hstvqfsj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dekhodyj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbkezgs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2crnyxylr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2leaycifi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbduixmf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xerkqxjv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrdktho.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnxkwtp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrbxfpy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoowcdx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvcmncg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaodbys.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdiqvvh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpizncga.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzursld.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbpcara.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwfmxla.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tsillfjr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqtalyv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nfylthkh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wggoltio.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xhydshqb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uqocpwrx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfeftfi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2psorkjep.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jodvlnvm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpssutz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tirnzgdu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eestcvoo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjbuqwo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfagzzw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2azkavxvs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tmucibqm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2butjdtpm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2trhqgzzs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yodjyqoa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnxoufb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbyqolt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jclgihzl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxwaoob.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xidcqild.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoevghq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udhmbpwl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljpcdt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2etwkdkyf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeubtlv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqdslsx.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sixiuvpw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bseptpue.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgloeis.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nntruhps.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qspmvztg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcdegqd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hurjxnyv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwnyfxy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtwggeg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmgpowy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2waksrsvp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrzwioi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiqqvwz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuyvgmn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtavnjp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxbizsg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rgilfuxf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2saxijvwu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zpubstrz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbwyszm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kypqwqrj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2urvhugmw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nduajdde.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuzvapy.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhbtqgh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dopiypxf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxfowhl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yeekzhqf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgvchus.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xwouaywf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2pznrjlsu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsspcwh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtcehpx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rakryyfv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2tinrllbo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2njjkddfn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wyscessb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnulenjo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwfezxl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2byybqixw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twbnwalv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjxagjq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxjnife.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyigbeg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zewpdikx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2nagpxurr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgzcign.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwhtagp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zvihbuzv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsdrnvt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2imwgiabq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2clpvwzbq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tihavidi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbggrgl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2vvebuprr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2flfjuvqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqujfbwp.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuoeemb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjsbgws.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yinlnsjp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oggcxaad.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqimvyx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlmgyih.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxujbsge.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rljqjmlb.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2puzncupz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqvorgr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyvsruj.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cueqckgs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnusawa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ichhjlrh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xizasrpp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lxibcsrs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbvsacz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhuyvry.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxkoilc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqodybnr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxbwmsp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxrtgtu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeepphs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdtihcd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ridcamti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvieaufc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mequcint.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaxdeun.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjmsuxs.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2grefsrml.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuijkoje.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2glsobusc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnsclvy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjokzyn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvmlevi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyrdhqr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kixkbnai.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhaebai.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjsdejd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdzlvok.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvzpzrj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oecamdlk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2egerhzfv.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfwmfzm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdnfpti.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxljmgz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoraqmx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2owaxzoex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvflzdhu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrgfsbn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqycsbv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2inpwlfel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmatgzp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjkyoog.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmfvehr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zkphcjeu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdmuupj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyrqfvw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxyuhjd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyulkvig.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vourpewv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejalssoh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvwfnsc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxwqfaa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqfffzu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgewlqo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2atlobgqz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nckjexjw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyupuim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvcgyvq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsizygr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqipmxyp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwzchxy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsevvtgw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkpxcfl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgfyetc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2frjcfreh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ystuzbit.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yynguwul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tohfyhko.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxsyjfw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnpooeg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqseeci.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2shaljpqv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2brcpcteu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2liknupmw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpknbmv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdybcpa.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qumnduuk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oycfumbt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nztcjnve.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwzqaaq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyskvxa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgjcrje.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdpwpdy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgakjkqe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzteewm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ubggcest.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbibrqx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzwqrbv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrovgnv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwivommu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrtzjqe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnjpzke.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wktwegpu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izubeatf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkbkcaa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hcitywnf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrobmfi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xspreuak.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiyjqtk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtpwmfu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prmgdkix.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdoyfjc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsqkltt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtafcpph.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmhuabk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2szalzamx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeufvkyn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jkglkfaj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwffmsjl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaccpgl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2riffanqp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2equoarou.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsclxuei.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnbqsey.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nywaryyn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqodvtg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kozejeve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tokbdbfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aujzqgeg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxegmnh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sroyzuvd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jytffpsf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgnpgud.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfxzbkj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxqymsx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjcfauo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2plamyqfd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlvgcxf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mgikgmds.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2umalwbeg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbwcixb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdqvnso.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvtritc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrstenby.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqutpqv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2edcyruto.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoaxrig.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2olpuakoy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2glgrzypu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfydiyu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kacpkfzf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvajtjul.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vbablkgp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdgrxev.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2quukgzjg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgtumbf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pugfvqmo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2spdixjkp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2smdkkvuj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxkghzw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkuugda.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gniyoooc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhmhfon.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvafhdj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyokbkhw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhjnszi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtrugqv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2peiojozn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrbjbho.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbioopln.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvyyfiu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2duzidfng.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoxndjx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnhnwlj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yceaihmt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfucpvv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuocapx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlhipsz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qksxxqxl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2miodfdum.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2usfqtcry.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqzatcf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhlgzdc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbbogtr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hyizwzjy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmopjqwe.html


<!-- 参考信息 -->