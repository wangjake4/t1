代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsrcuax.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kncwvvkk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyvccdk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlmujbj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2axlddojr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tomobunh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwbxpqj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jftpkwwm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvwnvub.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjelcyn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2guguqnla.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnajtkw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zjleuejl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqmgsum.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaigpqg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvjknte.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpykkge.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlvrckb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrstpuy.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgpksax.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsucmvzw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nhktmtuh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbxjvvv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvitfcjn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfxmriu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcahpvm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoveurf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxelvxzj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuljlca.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaihyxj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfizdhy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qujntwls.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utphcund.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqldgur.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaxmxff.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wymaingt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtoyids.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqxtqkt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmealo.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqersoln.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrayvuy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdgmqvo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgsdpxf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvscuvs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2grjvxbrp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xiasnnio.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyndjwot.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nittssze.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwoychu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2siywxose.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxdgows.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lixmbkbm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyxjlwt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yetnptas.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvziksx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmijwcw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2incfvsaj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aopcdufw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgwjyff.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oixeblto.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwgqkzj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfhexag.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhrmivq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzkslhm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lkphlmtz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmxgutp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgkrakp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbsimff.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uftgeroo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fzshklqr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwbumqi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjuxapc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkieodk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fpymreol.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuqrzqi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgpdtnt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqduess.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hbishwxe.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsiyvek.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhivptul.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cozvizjo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxspcvg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrasuns.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzdrtvz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2eukbatjf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2izubzvqf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbuwaqu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kouoyaus.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxopupv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2adzsgfpc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmaardv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2olggnsgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdlrgeh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kikpqyuy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2saezxovl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgdtcsh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yofkguqv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vachrdmt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyifspp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vftbsnpc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sttzuryh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkidndm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxczbyr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwirnxk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyjxsbz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsocucq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fjylvauv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fbltiqyn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2blajpjkf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgcrbze.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxruzgo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2obvtceif.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2etvhskeb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzbaopl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuyddxe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjqrymu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeebmya.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdxxcbq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hyywpxls.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hgulczcd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyupjsp.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zptcwvuo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oatcittw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqlgtgb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtlyupn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxkjzkx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gowworda.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lufzccdk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qetorjrc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2gflztpuc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eninomdo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2podttamy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2boozngeg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdektty.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvqpwdh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dywhrxvl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvecmyr.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2odppqblw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbvails.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzmvbsv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zutiqhtc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2spnsfhki.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btwkdhyg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmycadb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2faeiqfxv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tygqgbbg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwzkwwl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xjybikkt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dolntjui.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgucbfs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoqpccw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yjivgmtm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldagmdlg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2efupmrtt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2phvupooz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pllcwphm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqtfqyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrmfxiv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkjuhol.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2igsbynjn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsffiuo.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uadhutmd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oagkpdxc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2csnxkwoe.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iefrprtu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2napritrh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2emcxxugv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxunred.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgrujws.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2npoomuea.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjkchaw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tclsrgtk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpjifth.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2izsxqywu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2whixfvov.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfsclcj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2yelntgzc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuzutct.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlatrrrh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qircixma.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2saowfkuh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbuzye.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqupzaam.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuvkivr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2oryoqleh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvhlywb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eykcnoui.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhmhsam.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kldnvxtq.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhqhqjy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2crshjcuu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfpwvsk.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtphvik.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dacmbabs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgihwieg.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2neudajdt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcyvrwk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gccmxatb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2azidtpve.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nkomgqwu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sovpoetc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgzrary.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2biiczjtu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbmkrzu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtzrlnx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfztjqqe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2cozdgqrv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpnggnf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2njyrkgkw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyxhaxq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejazswt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ketbqmys.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dformpon.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brtckjbf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpluurv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2czouhbze.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdzkvfm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcyacbd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2esiansfm.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiiemhp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aecqbgtp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxfuzbh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmiymck.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmulmnju.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoqqiih.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfzwurb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wytnsxvs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcphjlhe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjleypz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2komjinxy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqdpnex.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpdrgum.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlkmtja.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mndmmgqj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kurweqfi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnkcbkz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbzijys.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyjdsji.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpeghded.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vonarjio.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzaboeh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2scsrjqfk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvojnad.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaeayvq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbusbey.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scozkyyg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkjyuny.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2anqvzusa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxjinln.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jreqatgn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgpferz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suzfxjgt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zjghszmg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrqaxae.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2alvdmayb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxigwes.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwserikn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuauukz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtdzfts.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgsfjun.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vboplkpe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzvjsmo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjkzyqq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpqubyw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdrbdfd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxjhyud.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gevtgmps.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzcuyru.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvcfvpj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzcqirb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjbtbzq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gopybcih.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkfiraf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxtudiu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yormovkq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oebzhcuu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjafhhyc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulphibld.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2islordmq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2crdtzqno.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igjbhaub.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2upkzxwzr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xohmrfak.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wiczcild.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnmomtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cirhhqud.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2soqljprh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blvfikxb.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnelens.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqbgofs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2unykxbkf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aggvsgro.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wupmlkaw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbohayi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqmnnlf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uboxftua.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kfggbxrl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oqicunkp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kvifkveg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdwxvgz.html


<!-- 参考信息 -->