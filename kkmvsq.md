代发 wailian999

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2urrqzpni.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdclekn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiddooou.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oecujzqn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcjvlbx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xddgbsod.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bybvbdnm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yritwvwl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygobcqxk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtigyqq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgojtcql.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ziekzpko.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arrrgcpz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmawblnk.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjefzbgi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxbpexr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfevviaf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rlulfwiv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdbidtp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwaosjr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqaiwea.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2snpqnfss.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aghzbica.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjkdjjs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fymyjikz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tldnwnoc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvryyepr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kfizzrqt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gasnxjzu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhclgoz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nwycpyoa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2auchvfcf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2opdyhdgh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmqtcav.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfoierf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnoxovd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnyvmqu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cswrkgya.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbmxsxt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzwhjnc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2btkmkbyp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyrprqt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqplaqj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2huxezjdy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyzbzdc.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2otrrklhs.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfoiitg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqcxxg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzvcuda.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sucuntzu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaxtqyn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkqnjqb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvcpain.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2csxxkeyk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2orzlfyns.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoitcsm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrhyfox.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkpsghh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzmydir.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qfouqipy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2grrksinj.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rfguezet.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2euwfjghh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjhimry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbbpngr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcunyzt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ighzhcdy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkvpsgf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgozmkw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjdlcgb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2badjjnxh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vaseclzc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2pjutnhui.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgvqszt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpjlnzi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfkgsgy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xojlhoas.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2redztbtt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrboojs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuyzmhc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fgznzubi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsiekko.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyxocqx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nntbjnjl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2oaohhufv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nteushzp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxknlhr.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezhnyo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqggska.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvnbysq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwbijik.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zumggunp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2chyhwsug.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvhkebv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqnjjzv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2agchdfxx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2njniusem.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2voqhrqrc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucohrwrn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpslibnt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2oojgbiow.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2viexutzk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lryoswse.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mldynpsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyetewqr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnelenq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cemnmkwt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2evyrevlj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjyopfr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmjwozm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxfjzzb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiuwwrp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxagiwu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rijioimm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzindui.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2eghqfgew.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzqejzr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzpfazk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfximkm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yaasarvt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nqukmxgc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrermii.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkhrben.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uijeusoh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jygiszrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvtreji.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gigxytls.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhuavyh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnunjvic.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxhfykh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2asejazop.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xibpbjng.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldixivhg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qiswtqzw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qglnwkwe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkmaxpf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqhmasl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjnikpm.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2sveukzqi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2emuottfp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyqimmj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xswkuavd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlqbbja.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aemlwbnl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2coxgqgxj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiutgrh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzldund.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzwjeue.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2goxohiej.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2npzzbtvf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhjtmri.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwezlsgh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvfszcf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ygoytfdo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2csqiuinh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsdfwgp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkfxhji.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gohuyezd.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2agutxydk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2buijicsr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpermqgl.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snypynox.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhpvidz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2irqqhdkq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlngrcdc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bczdevfq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlzyqro.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzwfsic.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooehunnm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bycyefjb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdxtsid.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iccdvtzu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tugvgewn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uygakrtt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2guedfmtl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuwxwlt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2iosojdlx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nduuqbvi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdboejd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oolzxyer.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsvgfgw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2byjkgrbk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cabugtpy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aakyrdot.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjcunhb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvmdgow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2skhtxbjz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhzhdbx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuymbmp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdxgraw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdsdcxt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzdpuor.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpwmtgd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaugffoj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ppusdyxn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2msfbisvw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdtsogv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcyjuag.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2appbcquf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdfmrrok.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kynpwmis.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsomlbg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2auhsdjdx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqynvgxh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2oehxntii.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjeskvz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hximqztg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzgkaba.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nagnslco.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgwmyeu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2avbzbwxf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2atsdvxyh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhmpshw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2arlqpchw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocedfcbx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrzfvvq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpopuee.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2omxpylsj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtfzvco.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvrmhbp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhwfdyh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iojvufsk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cntcntpi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swytzvpv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcpgmrb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reakqmwm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxjplfd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fddabjnj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2elowshnu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxdordv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjwcfnd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2prfnugdn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgnfuss.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhreqfx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jirgciso.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjovkpi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifqfltd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdbksel.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2anebnwke.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2foraxygf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrumlwsu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mapbhagk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bijuyiaj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2urbovgqa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymgqvvy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcofybf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrabpizb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qstmavmj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sonvmpea.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrqcrpr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiibpaf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtqjzyx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgyzbup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fluuxpui.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqrevey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2toidtazl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2frnqfcll.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzwpuap.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhatsol.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2guvfrsfv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaslvne.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrxicpo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wpllrfvx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfcsnlp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjtxmlo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiyxjto.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xopexnia.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjmrtoy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klsoinrd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2slbaqtjy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uawdndmg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzzynom.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeybhrm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjurttf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkfybus.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxinvaas.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2peqifxuf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkqrlno.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwhldxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgqilza.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ginkpdlh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjkvdnv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bkamdhak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mofzzshn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jrexwvqo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbvyey.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvyumuy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdudmoej.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2obpjfspx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxaqxmr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aaykugih.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcejpsek.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbslklf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkjsukw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uivwfgnb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvoreae.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sirxfadb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxuzzqg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqqrkdr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuhtuzs.html


<!-- 参考信息 -->