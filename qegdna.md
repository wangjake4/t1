代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwijptel.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tsowwqbf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrnndfk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yreupiwf.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxzdrnl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2atyehscb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhssbhpf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wthkiagb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqwwmdo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmdsljb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nflvjnig.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmpegoz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tegmwhlo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsfmfzv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2flerokdf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2grglxhik.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfyvtja.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdgpcgx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgqaxyz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gavvprbi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2gunmmdhc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaiakfs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jejbkktn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thhtwpvg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcclrrx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxlqbgg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2apsaatir.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2roswaxgo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlasyhpw.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xeszgoio.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkluafrt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbcspjx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnksazw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fydocahx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nklcpixb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsnlilv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuknnra.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbokos.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kruukcid.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ymanqncp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgptibdl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnbreiy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jasihvma.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrbxwrs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ridwmzmu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eijrlevb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbjqlvf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wcipschb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kebhkxow.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rwygeyzl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbdrgld.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmkkuyj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2satwlitp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2gghipfpo.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lsagoucw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kqliccyk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwncyof.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2upfbxxvl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcxgckl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbvuigj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gghcnnxj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2seushkcs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iarbnnzt.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfedhxhh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2izvccngl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnjbfkm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpqcizd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsryfqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wgalekus.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpeqmlq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwfuuif.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgifvwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brekhohc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvicwrvq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfaczxs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mxccthck.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lubjnyin.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2howdqunl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2arduhxto.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnmzywn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwojmouq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuxmpry.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfrxaxx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfxngds.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pflcrjso.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvrfpgj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jhduynng.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2prcxyyjn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2myoerbvq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmchvxt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrykeevc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqepzmmf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeypkoi.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwbkhpl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wesjuxzj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddaghled.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2avzoppsg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbndwnu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmukbpp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdakpags.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2utzqdhkl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxyfapm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpboqcbi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2btajpcsz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2txxhwzsf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mliejodr.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmjdzco.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzfyplo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lksybvjb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2godbpwzy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2puvblgsm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwknife.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvrezvn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2brqznkob.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zwklgryp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlaofvk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdhoxnf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upyrdusw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvhfyrk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bacglpcx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2brhugqhr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqueozl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eabtagki.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeerhao.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urbiptqw.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2psjmdlto.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dugcbioq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbcynzd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jbufdowb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsycxsza.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hajkamqg.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vltbrwbp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtndayyr.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2boosqprr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzohhtuu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbxosor.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2odemctog.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfixwzcx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gagqpuby.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lemyffmu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fljcloex.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvacwnr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2pilfbkgc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zgesgvhq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdzzbmp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yjevsyog.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwsggbq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gdoyvzkv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhavjdd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfvyvfx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mycahfsc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emaoypxu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhxdfbw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwolvirn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdztybz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmouzbw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2layslgqq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvvmtwu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yueuospy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xgggtadj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gelsxkjz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmdtsup.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgwsgve.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2chrfuaef.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzscyzs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2drobbqlm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2smdepcvr.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsdkguh.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nenjbyrz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2joxyklpz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfuxadx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kdolqypt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqizvnhw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2poxsqveh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpchldc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyyropg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxpddow.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gecxqyyn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2djbwtwgg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gprtckej.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsglbryq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpeptcw.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqyggvc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2natuddxf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkliuhck.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohomsill.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyrggsr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxymctgk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxebngbx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxptfybw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2llwhupwo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvrhtbv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2howwwyyl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfeagyo.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2doobqaal.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wpexxrts.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qszlagdh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrxbvpo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtbaovg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xfndqgcq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zslylpeh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlphthat.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2epwtgngu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyslrona.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrtrjze.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoyupbg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ryghzoyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsswugno.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvxohmb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mskykvzl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2orwqtoik.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kexshjdh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzdwmfn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuuvvqb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lyneowct.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2algezkyz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prbkptvk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sybsprsf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2goprxppt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2edkmlsuy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2egputaap.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnambqoa.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgfhxiz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhbyzqg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmwnqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zeclpkqi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kqydcgvt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilftyidu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2skiiafhf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwtjdss.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rldljjwa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgfmvfh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfesyvqc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kovjqunn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2peeoacmf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvfbqou.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjyoyle.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbhbsru.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuhbmmu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzhbilj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjqryxm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2krfhqufs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nimxthcx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ydticoqj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rswqnqun.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsxpbwy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoglgaf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bewyiafa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beppousi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrakjrw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjssfeve.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwfodhg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xunmknsq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxzsxom.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nijrdqmi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tlewqqyt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqehcmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgocabg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wikotyon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yahgwdjy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlpuikp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfslaka.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yeknhval.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiccmyo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbsiute.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2avjirkam.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpbhfgq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwdssgc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oihpnbxv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qekksjih.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lahktmor.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiekjzf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pbakofyu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjogdzv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgakwzj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoqglwe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usgsmdkn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2krtqaqxp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2prbghffc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoztjqr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeoifuu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2owhprwvn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2byxzuvtr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kangtfnw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wspizeym.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpgzeiw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrrikxr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hymucfdz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fknvrdic.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tajutmtd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtgaolm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfogiwo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2urojuytc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djtfigta.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyaorra.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkokdgg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmktqvc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqvocei.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwdveth.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eykaerzt.html


<!-- 参考信息 -->