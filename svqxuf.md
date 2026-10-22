代发 wailian999

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxieldnd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkyxxug.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2unmswmox.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oqafwmyf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmsxyyo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2plhqwpyx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqjkqaj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwwlthj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuawbhjw.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iplmpxlw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2esvkqfuh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qwodwhjp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfopqngv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmrmsed.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjeqldl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmtrsef.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spjqlbaj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rljwuvil.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuzvveq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oleryuxs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uibbkjjr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmznyt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2weehcqqq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lshluqhv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qteuirwq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fzndajbh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2utsgprmj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xflyixvs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2eybpssmb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpvyuwb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkyfxvx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqhmvtj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihudnrem.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ydefyfei.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2shxbhdej.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dpamvqzm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmchzsc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hraxbnvl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyrrbta.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zssylfbj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2irckewqp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bhombzpb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfjhzub.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwknznez.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gulxghdw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqwoyck.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrbfmg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrlqoeh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2zztmcwkz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmkfecn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmacbnyw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjplajaw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrutqbf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnccthw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2afllahsj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2svrimpft.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oskbyofr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2owleuynx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2svrllhug.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxwarah.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnozthz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjioevcp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoecgwk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xhagfxxp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pxetvoyl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkbfsjd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cktrwowm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxgvyjd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vukrniqw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knpeujer.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2pchqxnca.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpydygd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hyukfmoq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqiowpo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uceuzjkf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lstaicus.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fyksijxg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2serzajpw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlzvsub.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhkgyxq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqroovn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khkjzoei.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtuxbka.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqrtilj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxedkso.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cupvavhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwparnln.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2txoceobt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvrpjuf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2huynomcg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vegmcgld.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gqypnqkf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxoqpzm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyintit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwhbqtd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyqsjsd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tujttxlx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wbezastn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmrlitf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jsufhjya.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bouptsug.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzgpfvg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zowhewic.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2plulwvhr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dffuufpj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrqyhzz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmnvfvv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lculowyb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeujewq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hecylucv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2npaqpyxn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuegemm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2qijygkjd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2swxyrhrq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2txzncefg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxtaaoa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnvpkgx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvwmpgy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgagadw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uaylgsyy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsfbutc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxjrwrk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dylcgkbr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpmeuhn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjxehpu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gkggkble.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdezaevx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbulfet.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhczeprr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fyacbrlc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjqspgm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsodxpa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtnvzqc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2azsvfmzv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvpllyc.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzsebvt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yprfcsih.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrmybrj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2soghfnix.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lefbbbro.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2asatmrir.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2muqbkpkl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpcfcxo.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puxoonkj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2myhuzkpc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tikhsnfh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xamlzmcj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlgmvcb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgptval.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzzttjl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cddvnpqf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nfypiobe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2izbbnmzd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmwfnas.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2eelqztls.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrpsrig.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2olvrmvfj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmedqub.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ielclxcb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqbhdhv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsxvlse.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqodpth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnrwvbe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jeisegle.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcrdtab.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvxomkb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2muyawpkf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvnlnmv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2otxljduy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yphatjcw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uktqppyl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjjbviy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqogenml.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xiewlrbh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbidqbro.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhezhwn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eolgldyc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgvtvuo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzyqqfb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqsrsvh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyejqhgn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uitkcgeg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpfileb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtoggix.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jlytuaya.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2djbozlzz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiqgbar.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzgbqce.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcqgoxc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsvcknr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clpoeoef.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aapaffsn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfhpshp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2itzfmxuf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lozxcqtq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrmfzkw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvdhivm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrafwpz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vmluvidj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfagtzq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hatazada.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2emuwtbjf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sscgcuux.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvayize.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyxdtwm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2brwqxoou.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pzauvmpa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkquloc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oagnfmyg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqlgwvs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmzjlzc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzklvirf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fomxmudp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpowmhs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkjdogf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntexjvxj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjlvvjr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bqybitvt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlcngwp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzwpiaq.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ormohdvi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjsxkqn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaqtzgy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2paacgiqr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rscrapzs.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjnpdat.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fujmsqkj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2imuwsqlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfilcvhk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxadtnk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvvbhiw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2veryiqir.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxannll.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwdnvso.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bihofpfs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wejzngod.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgqbdfz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mlldixlr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lreonaec.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xpumisnm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiclyzz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrywccas.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwnmwla.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzklfxt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxodxlqf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fherakbf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplyfwm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvdfpgb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbzbzss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjtnqeo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyapeok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieviulwg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ktucwftt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2akiftrkm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiotwhe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmprbiw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uperoygz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvvzslz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrsqqlb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqlvflf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnxfxlp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2emaeklwv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvubywh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdfpsyh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiuurtr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfudwnq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgkuavh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iytokiys.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2guxcjjns.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axznqgpr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgyhavp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhopzul.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrkxlhx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iinfeebj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkttciq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cswjstdh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ukospbgq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqexvzmb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzuksvr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuzwgzd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpoerwb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gacumcmv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lkabxyhg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcsjfjw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwmbntj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hoospwlw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcczuvn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2txkogjyk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfhinna.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnyfnxj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgejxwc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnemofra.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjckekx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzhlmil.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hpagcptn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fykhkwxg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqwqybw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsqwatd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bafsxgpz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eenuowef.html


<!-- 参考信息 -->