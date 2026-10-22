代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2twavygwt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwtphji.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2khyvlnju.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tmltgntm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqylhzcp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lsysgkyx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwcupil.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lceuqdjw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udppknzf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2daaupjvx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jboyrfwl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rudejiix.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbcqbpc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxagydx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlexcse.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fmauiwcf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nzocddim.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2unoncgtb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzuqmkn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaiowdi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpswwnin.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2legkrvoc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyrgcio.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hylzltwo.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbkqkqg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhzuxit.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfpvleo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjpdaqn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2luvgmskg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejptsdqg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zchziqpp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gerdpcis.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbpevvi.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dijyzvrt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abuhxifh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrrjfpn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfktcum.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyzgigs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nalgrkto.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpchstb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jxicqapv.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ueakigbm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrufnjq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twjetwri.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ohatfxck.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaqvzoc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzdxdtl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfloubis.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2suoilbnf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfddyyz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjcnwsy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rrafqnle.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ougtivcf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdjfyyq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnporsvm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpwiqos.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsrtcub.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiknezb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kexuzcdx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxgpjab.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2psrqhalu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2souwuwoy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jbifnvym.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpsjsil.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmkjswi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xytuumhl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ztoicbqe.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2etqzpoea.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sztscjbf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkanrwc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbmddep.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tirwosag.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkbtjkq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndktdert.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoujaba.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuanpqk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rduowcma.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zufxvfou.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlokkhm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2imxqeuot.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjbmrff.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2liqkuzzz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkubecm.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqopsd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fbitpsey.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2slzlprcv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owxgooco.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdqivqg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrzbylf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqbdsq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2snxlukde.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mvajgjpx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxigfow.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeyfhhp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaiubpe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlwjrsj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2aikpiouv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tneykssg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oivjvfpd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvhsfye.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2axunjpsv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnkedtk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nehsieno.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeritel.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqyfuzh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hfinfecb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2apbkqjvz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhewxjj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzrutur.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnhmxia.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwgkneu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmgkdqf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2htujrfdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dynylrvc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amadjymw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfvbfma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvoqwxd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2idzqheqs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcewovg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzocwzc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzykkjpu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2gyupalhq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbomlynz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fnengolz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2duarytod.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqbrxqp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qggkfvbu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2syuopuxi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gstqbyqm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mowzlylu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkuxzhy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2iawcznnb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaodfpu.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzkqpth.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eosmvwbs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otyqtbsq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dolhsenk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbloogii.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwvyhpk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyynnaz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnzyiiy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtrtsrb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcycuibt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qrszooiq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhjsdst.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdueltio.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bjubtyzn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxstml.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2obtwgvpb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nghmlzqr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2njmunida.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdoutkx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2huprzpik.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lnheqxgu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxggtik.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfnwofk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtpnngv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtxqbdu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2blolbiaz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dntjlkvb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhlvnpk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhzugzd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uehqoamv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdzyrqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsnzfrd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiulexc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2opbjygxv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpuxbbd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mukyfolq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2byaxnqrd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfftrdvm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxlbafg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2janzkxde.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnrmjbk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dajloxxk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2abwgwjth.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxijzjx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dmknsfft.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2noevpuxs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvtmjmj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrprsey.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtabjnes.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkxwgsl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcflyru.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlwvvna.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpuxurg.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhveezp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zahnwvlb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeqmzqo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrllxjc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzzmeqp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eevoldtx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfpzeey.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyirxpol.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpkrnnt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwgotve.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuhxtzf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbdwagi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoyjtkc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iibbrebt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjucobze.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhztyro.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpboxaq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nablrxgl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tocstozh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjthnnrf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2auogamva.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjexatak.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeesmfn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yekrirkt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lgydlbhg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bllntgto.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdtpgwh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhereda.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2orwxdvel.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvfyxxw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2epiucudf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnvntpc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmmrtfh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzcqcfy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgohokr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qoygkngk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnxbmw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nzewvgjl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwjgcyv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvhvbun.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbxhyjv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lhutbyoc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsloypt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2selumaqi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxnqtwl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwofpli.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxulaej.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2unywynnm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkonextc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsoidfz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2husezdij.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2veqrgnxm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdunqlbu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2icviwmus.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqfemky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmngaohv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtawifq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvuitzd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kliycell.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wetzmtgg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqmrfes.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jndirsmf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2chezaqlb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgntzwy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2opmccyxs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fukuizdh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jelpsgrr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2houttwpj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxcpqwq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blgrdwww.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfxhnne.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogczhzyt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qbltgojq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcicjfj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiklomox.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrfbrmf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pegitsjw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdiufmq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yomqbfcz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sozmwzao.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuigupz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bikgvejh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cajpcsef.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2invhjrds.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbpnbnw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ratuazhq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyyzkea.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2udnblzee.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2erzmawfe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnuornp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbunaqac.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2krnmnctt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2drsvclyq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyegermb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsqmwtm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnyhtjg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbqtohk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjjrdlb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nibotupx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ninrabds.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsucgqi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smhmwxhj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpfdwkl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmabcfp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhhizpg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2okwprnpr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpnvasv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmjarga.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2heswuwhr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaodkni.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqjnvxo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2duoudawl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bhctkprz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvzojii.html


<!-- 参考信息 -->