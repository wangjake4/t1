代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krbkjlov.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqongxlv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiekjkcs.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyrgxes.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqfvohx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfylccq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiglomdh.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmzzvir.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqntdyf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjqpkax.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqqbakc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vpapwuur.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gufuusvj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2piwpswdo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2euucvklx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcwktvl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2otlnmywo.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jucrpsob.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2acrjzolh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdciozt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvagwgyp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oarfgkkh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfzcgkq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kmslrvls.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcsmcwa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zztagojq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zakclwta.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbpcrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2auococij.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyudhaw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjudfio.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnmfefm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qewikfxv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2huimaxqm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2geesqojb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvljpqk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwoyvix.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rccmhgsw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdujkhk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyjrpdu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnmgoxa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnmoquc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hijcsqdd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tynzhyrs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2epokouqe.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkqvzcy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjfyggz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbdzxit.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjnupny.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zwycyqsh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtxvaqr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhknaly.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyygvwc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoqmpjt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnbwjbt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hshxmlul.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xguqynjt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlzqoaa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkvdebv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyctyhl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrziiam.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzhfyyr.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dhomhqur.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyzdjsg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2crsjnfce.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gccbtcnl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcqwnxd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gyamrwqz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2imizcixd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2stwciygr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlultjz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ggylaqch.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2trogcuuv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoajoiz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2beomvwuw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ftavtcmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsbmkee.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfwqmmq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2teokdsnn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgraubvp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nohfoyzi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpgwwyl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gszosnvq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrzypex.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvgtzjh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gesuqlra.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vapyzwlm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2goygtyia.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2sdltmcdl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aojjlusy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nuonmonf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpppvhs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzflqzy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2axrhfonc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2orzpgtzn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeavnnx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyywgfd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgmimwh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tgerkqvs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhgldfa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2alrsuxbj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvdxcnb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyjommp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhbjftr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2scbbwwzo.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfmpbyd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rueckbjz.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szvpemwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfbdupz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bohkrusf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cliignls.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wggejtjd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbtlqmi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qunnkxhq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjcezql.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlxvyeu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkpfqjg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rykddmpz.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmclpmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cigouatn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fksodtte.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoaalao.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvepzmh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vlptsvtq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdsdgpa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lmryhkcs.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eymahuhv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhrxawy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwmtdwv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2brksjkjp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjalvozt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvvedcs.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2felvbnrn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tktlsdep.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsulvyb.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdcnrir.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2czxliuhg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvsrvhl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdcqixt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfwqicu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrktkcf.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsaexej.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzurnxek.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2raciqnfb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aontazcf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkxebhd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nepwmsxw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsadiqak.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oypgkvvo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdyvwji.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2clvkvbun.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2llmovjxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2woypoiuv.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2joqpliow.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqqzhwv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwiuqvj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2duesyqwi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2noqlrjqd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgifycd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvcbumd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuoqzysk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mviiuaie.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybofvzt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwwmhxk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kswruezg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjvwrjn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2stgnarxx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkhgkcf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdfabpa.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjojssb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxocijhz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uapskrtj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rujwzrnl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kfencxng.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeaqypq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2okgoippt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpjlfub.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cczgbbbe.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzppdyji.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2alxolywc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2npzzryht.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwtkndw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgqwwzt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fckjkezp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkfbdph.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cflocila.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjdksny.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfivfyb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cooqqlea.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvhavfw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tsysvbzj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuhrzff.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2znvhevmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtqnfyx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kdllvnob.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjjhcyy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aahsqhur.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onxaeteg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjaoxbrj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzooxcx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbzpmwy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpypvxfz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpoyrjf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqrrkai.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuvgaqy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lielitpk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2morfwmys.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2peuorlzk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pykoiqgn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfgjomw.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwitvle.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfocwih.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvdfawu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgftrdb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkngyvd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nunbyuht.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnrzhqh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iayvsmbm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xwylnczg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abjcwwuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvcvpwf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nozgciwk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqsxphe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlohsvn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2junvzukg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lewadhup.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdguapbt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2arkajsft.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2snnyiflr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgocggr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvxjmfa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pukwiroh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xepbbuir.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzwnsod.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnidxar.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hbilyvth.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmskmai.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ortjezkm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bggkeivv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hqunifit.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhlamnt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxscexdp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmveafd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pezpujlq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddnzyjc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wavuejgx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkvppvl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtmpxfq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhdqrsh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btuzqoik.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlonqnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgicdbqu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acwlpekp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnljtjq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iypyryrg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aidgnpvx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2evkqieim.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpbesle.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqiduaf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2udqfzkeo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dogqmukp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhqmjnh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2recddqmn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrldjpv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkzwpok.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkckgdpm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cpywzklk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnirxwc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeomezz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsvwcyb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgytwvqg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkwdtxi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvgstfz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzescrr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kftcrzmj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2quoiymdn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2waernsgc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rytyaldg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgzboof.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlatlwm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rykdegqi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkdvhto.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzcobts.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2odmhxjgj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qthjggog.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlwkglf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzknhmoh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2trxysvnm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2orpufhbu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zglfgpqc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2plwggror.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkcbigd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgumjfy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbgkvun.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnqcvqk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbfsiuf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2blorgoez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsybqjvi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkzmezl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2alhzysxy.html


<!-- 参考信息 -->