代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpweqzd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmtdvcd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsarjgi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wapygmni.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wggxgsmx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlxugup.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmmgcsa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oocneimq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oloetuey.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpfrnzq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nynlqayh.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iewxrtni.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcmzbvk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmnyzyg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpxfrfg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2eyybfyaj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pmihihhp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzuemjx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpzezpp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2koybbldu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2entbuovp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hivlfgod.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bpojagbj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlcliku.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdgackv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ucisdwxw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2iokfrgyx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfihflc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bowrhhfu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xcentgsr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oczceevy.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxqnzqg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltqxyx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjxfdqi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdgnkst.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvgkolg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oluzigny.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2suicdnns.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2chqjtoep.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzhgigd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwwtjtw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2wujgpicf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uczlvgiq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fydpzmgc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzckdur.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrniwgjk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frrcmomv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vasemdny.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgthafq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wepzyfev.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpfysvk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ncncjvzh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmpuwwj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcyokpd.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjcxeew.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhlwhfw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmtbbeb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsducitc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuclbbd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dluutmcj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqzfbrk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjttfiv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtyuawu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwixcus.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zopeiiup.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvriosu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2auwmszxj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxhaisf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxonzre.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iubyrjga.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaokqvb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdenpzqk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtttnxc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzvhgtb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpgwptq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtsqkfn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfgaeyj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmxmqap.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmbxgxe.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiybiqh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pohdiurh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhlcoku.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrclyns.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2whlpqadh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxmbdrk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxekqxzt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdhvgn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2stmqvkqv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdrasfn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyjhjxl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wojlvckg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmiinbn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwqvksv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkuyfua.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuwlvex.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxubyws.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nqiinzui.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnzggox.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwxaymo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhviqtlq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hspdgqdr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epgdwhdn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nifmfglz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2byxczbth.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgrlbni.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wrepqpoh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aemsohts.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcelejy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2phivuzae.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiyopiy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyevndw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdjffks.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckcvrb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkcmpcz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ninhhabs.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfezvjc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdiyzef.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubyepi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzjquqi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxkbded.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2elwhichn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qopqjexw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckypqity.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yrolijvu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwatdghd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ysewvxhq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcqkvqm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mwksxedm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2chypvteq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmhtwfg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuwmplt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuhvxck.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2etfvmxso.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmmqbsq.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2refkpiyc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqhylpf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuanjij.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hogojeda.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sziniqrh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzjwpid.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cajniusw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pepgsrak.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyniajd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvuntnm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pplohcvo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzogwbu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqlymno.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyynuxe.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxhgtwh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvifgit.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnsgfdz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxifght.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hczmpmtq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2emwhcgtb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqohsqub.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrgxtts.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hemwvdpc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qylpvqxi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hprzidrf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lunrihdz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwyntso.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxxqoih.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2amxivgld.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tsewrnka.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxxoutd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2backmydi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yknmwbwu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2tfalqrqg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aberbftn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dckjlrsx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlksxcq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgubcjo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdmpiso.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dryrsbdv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsregzz.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2islrobdh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoesert.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvztfjv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2exeoyxyo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ivydkcce.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2miwmskgw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbilgtd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dbasjrvr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeaxamw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cuckahlo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsqudyj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eylzpdya.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gstvieqi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2erymbnhf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfjhgxp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2holaetuy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sexkvwwg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxdxzpe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoonpuc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gleokaof.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oupaajxk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjglwvy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hedhonfu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbbiybl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyxmzkc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkwuzdt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbojtho.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkevxpma.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjagdpcw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qatwflfm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbogawyv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmvsquy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzvqtnt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cljgezxc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlncqth.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oluteebe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqshkjr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2unysffra.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwienugl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhkyvez.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzvqfkr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdcupxn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhorliu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyozwhhc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrarqei.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qerbjayw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdwvfja.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2juotjwxi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgyeipo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjvyirw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqagkslr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuievdx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jpweoeew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiysnpb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uqezarwj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjbbgjz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlpqmbj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpodowo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kivpasbg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkegmwvo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmtotac.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2leywkuav.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vqieieth.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyxnyfz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdxfbqd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uexvrnsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esrngvev.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmztjfes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oewgzyxp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iyerxjir.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvofnrw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2emiaolci.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2txmysuct.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lfslfckd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkufntu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tijfzfkc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoagcvj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2teymjsyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjnycsl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgxbucg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcgtozs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2swebcxhp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkithuoh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qhokgoma.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lubirclw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyjwbaq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxemkfod.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsslpdj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhzgzl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cylvkxam.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sougvhul.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nopwsfwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjrjeq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaexmzl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fopndnde.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2znftbqpp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjdqfjx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkelvl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeelgyh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxwveko.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knrwazdv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcetcouk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvbklim.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtxoyii.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gevfweul.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zoozuvpg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcaupfc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoarecz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszuyipa.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgxthyc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2flvvdifv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fvefmafh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjgsedm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pckhnpyu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkycsiz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qabatcru.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjdeoim.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhhwtom.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdgiokq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrowwcr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuvorue.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjqfjpi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jalcrgqh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lobwploi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2msioxufw.html


<!-- 参考信息 -->