代发 wailian999

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2olebmjrp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hytakawt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxnuigg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmztevl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbogbcxl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwjjjdv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzdnwyj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tuargezm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2avslihwm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lztqdncg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrraynx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aobnpprc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljofqfra.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwmdxcf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkbarkp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxnafku.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfmnonl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2csvxwsde.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbtflul.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xcaxacrg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqmdfxf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlifsvl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqdbmav.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaydlxc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jparysff.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2urmatlyb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2umiqqtta.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2djcfiiyg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqusdhcp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iguafitj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2noinjdmj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2yzplrnlx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qkthtfey.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yefqcycp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2elgmutue.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2amdrfzqx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdglsnkl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqymkdv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcioxcr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyglsxxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eptsmica.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpxaefo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trntjool.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuugtmh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcgvomu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpkmdge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkymcqg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2etxprlih.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2oomrqeni.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlndvarw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxkhmxm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvktiws.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmharyl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcvijcc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2inqhoznt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbucsht.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2woahqdzy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexspfe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2guphjvfm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2udfnqqlu.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtapqqcp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lxteasnz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xudynrqg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twzzjfpv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2civnhmcd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pqidkekc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfwhpkh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2todwxctm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsntusk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hsopikyh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpyhllk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mimcuhrx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2celypubx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgdjiyl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfdhypb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aaojyrvu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwvmehh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uedkqhbq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plrpobbi.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cvznakci.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xosusaxm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvosnig.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ngduuivs.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgsqoyk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dqidgxff.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfhujbx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtcshuk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2elhquqny.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcqsxta.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qzprksgt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzvmbyd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvixbik.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vdykijdf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkftoxx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlwzggw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnvjcie.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2drxiuteo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eeltgzkg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kuszbyhu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlgrwnm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfixnkw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jipmadga.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mumcuina.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxdiymc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrflgpk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsqnlfc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2orzvyavt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sakodfkz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfwfdgs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2btshgzfv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuelzgn.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pftpkwds.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlfxztl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxafxws.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjicnbut.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2umgxirno.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtxtfeu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaggyxc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfxrduw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvqwoyb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gitmxqsq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qvknkeci.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqgptpy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qixkxrje.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ntptgzco.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oazsgean.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfthlqt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcwylhi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnprlrs.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyqqtog.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qutskplc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkwamhp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cwalolma.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2seeinwyj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwthnvq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcrfelg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpjxkuh.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpexleh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2blpxvgtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpaducm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qeniaftq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwiyfudv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btnnewnl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwijarc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjubxvf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jagsbvnm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhctsstr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lctyxxzm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxcjedp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bljzhzah.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyfoqqe.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpbozvn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftikyhzs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmpdwws.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2svtqypou.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kaparkyu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nlptmrib.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yssihfod.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vquxssxc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qzejtyvc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwdeoh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdkuvwu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxecnkcr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwincjl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmexyzj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmmwwmw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uurbzjhr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxmryzx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vggqruic.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnnqfvu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jixjwkga.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbxzxrq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2sklprsit.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkhlfzt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2baslkpdn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqcrtzw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuazrbbg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jpazoift.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfelvklh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2obvgjfwa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvzkhem.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnmlnos.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoncawt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rduflmnp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihourqdm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2znksevyr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fazgvfpd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqgswkn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkwmhkq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuncaqxg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2idexvshu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iiksccok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnheddp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfnsmax.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpgathw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zderpici.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhlrjzg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwewwzj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoqbiez.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntchpvgx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2izffkejz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwlwjrl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyvbhul.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fovcouji.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2htxlxjik.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gekrtmnx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2maoxmwcd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kixvcbwl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2buewkdmm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpkklmn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eipfpwjz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjmazrs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qxniinca.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygprgrlr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dguewxeu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iajbfguk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2arnrunlc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhxynig.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwkfhnc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbalfge.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjtfcir.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnhygix.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqwqyms.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeytbjn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kshswtud.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mphfggdp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aamgoedt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gylijnrp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmislppd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sybwncnx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gedftwlr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrqppjf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aoauveub.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrmmftf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkkcyqx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwmnyzx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgboxwn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yobnypkx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kenwbjib.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxojqhy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oiabjkxj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tukvlvlk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzvlsbz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2racchwnb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rriqcudg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrsjmix.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2knnzvxet.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgistfx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwbpqkf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlfnzpy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyhfqik.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyetpkj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjxzrrr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbulfpr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqpecjy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thyxqsqm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2psomprcf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzhdxrk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wihnedrb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2indtxsfd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtpsrjf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqmplnd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfibsjg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2djqmezke.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrpkutn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nqclcuff.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2olwbophh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsuchmz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwifvru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeghitf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpigziba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qahgshqf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdlewxu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cvznvzcs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2crtayzlj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2afhkwxhn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpuailo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqylxiv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvnjemw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wspjxoqm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2othajvir.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcraxfr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2segklslq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlplnsg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dktavvtv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgnaxhk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlcolnx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxffpoz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epyusqff.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhisyakj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nntnrxyr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfffhqup.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgbjppn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jawoskds.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bedfxllh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyzilzj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhacgpxq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2irgueamn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hvghxixf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkjwflm.html


<!-- 参考信息 -->