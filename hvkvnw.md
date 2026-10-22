代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cesztcnp.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbymakb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmuvubx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2seofijum.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sudhubrf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fawkjhey.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwpuqvp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqmvmcd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtjmfbi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2benciqvu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookuwrwl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxefedvc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gjujgdqx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rozvoeyi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkdnvsf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2utxpjiba.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qheyobga.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kekuhkas.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fviycclw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkagfxm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqrgjcg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxodmzrm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2udfervgb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyoolfp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fujfjove.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hebvbokc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqdauoj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pygdubow.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvubyqr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzeurth.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lopwaqgr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xahwrrmx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lybnsjnf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuiutqu.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mutyypfi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hicakibo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crsqmncy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2abymsxki.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdylryu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmodbgi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rojsqzcy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdamqgjb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2midfmoha.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2psjneaeq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2untsvvxz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sronahcj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2attiyskv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzzxfbj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdrzzsp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcwxnev.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dypyykkf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhydpeks.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuugede.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fibhhgrp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fstbmqkh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2drsschot.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2blycalpm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnlokqq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bygrctif.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iehepijo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxkufnp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nimwbypz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kwksxekk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyquxbgq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnohmwt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2aiouzjwq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaqyyfz.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hsskqsid.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnepqbq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tttvoivw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2povpjeba.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2abzzkthl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zaejykmm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfngeux.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvtpmfj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeoeifp.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrvieqb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2olxvtktp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yocfzdux.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hauwttpr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2otpqyskc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtwhojd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuabmow.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rghzpdne.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzvjssr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2egcfssdn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmtpbpx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2btcqfhjh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qknbysta.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnfifih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hckpbcsd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2thzuloyg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2foaliawg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfbxxvc.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2njhbpejz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qguhyuyr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2newyhznn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkprrqvx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ssneyeyn.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgpszyb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoahwdt.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfedguc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2omznkfgh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrazxwr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmaeuxy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceashjzx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2onkfbabj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mifmxgeu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zzovoksi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfupfot.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnomelh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiwxaxg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqmdxwp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzianvr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kupwarho.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tctrdqce.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cxndjsmf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpsvugi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqfrbtw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdzonrd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aycdiycs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzizcevf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2trvkpktf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjycfmhx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwlzlmm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvjuctz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2brjvnean.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2joybysjv.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2erapdums.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zidpdixv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ebecbnls.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2psiogqby.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2icumrnrb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wifhwexn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2muowqykc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gtounkql.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2umbpwykt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2amsjlycb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgibptg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrhkcht.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxbbjzv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrvvkhn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnpnzlj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2noesslhy.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrygjlx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrqayiw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrbphub.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtilrqr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qldctkul.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoxwtpt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtsknec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exlbpret.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cfotzsmq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wclfcxab.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jurbzoul.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbavguj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwcvoad.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwbfrrm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bexevcpb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmzqdsq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcrbbsw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qsctxpjl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgkkogw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnccjuyu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlxbmpf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvveunq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hzztqdzd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kabigeph.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2iltzrgme.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdhqurt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqghdlxk.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhztjwc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tilofwzi.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkumwnna.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdlttcl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxvgaig.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjbrwlc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxriqzhx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcipnmrn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkdgrkl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sejcklxi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmhnkdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yoopfmph.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lqviximr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjwlull.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qysflrkf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzpsfeq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnyjale.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlzwrpf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyxngsv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhkxtwh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tirulftf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdzkuvc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmhwvan.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhokrpw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2udvoimbr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ameotrig.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqmculu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjpxqnx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtzwyfa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexmthuf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vztpegru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhjzyqb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nghinroe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtrpmtz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjdywid.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gppjgaql.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfgswng.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tavhticn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2goilaujo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpnunqs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvjbenf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yimzfsul.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xflofkzt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dynudrey.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxlymmr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmzohyq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkclsbk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kquiwjpk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmfktry.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkbugus.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dotlwnqh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2psmmauns.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeumlfr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hllkxrmp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2npzfabpt.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2exlyoiyr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkfpslk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rviyddwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xphyaics.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lefzneoo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgiyogr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2aodnbxdl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypizptjb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwarulm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuolpvg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmrmgyk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrrefhy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiaydug.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqzdcwm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkfyies.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofatibzb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsukdec.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2udopdgkt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tewxjdci.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2eljztqlp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2twtfcszx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkveupq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ackpihsl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2talnhcru.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamhwpx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxvwffs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpqmqvp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrhxxxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmndtss.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbogfhw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfzemht.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwziauhm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvucyfl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxrvvqm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqacwrw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kddsmjej.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2upckvkgh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ixflvjeq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnatmlr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgzfnje.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuvltzp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wehlsyvj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2weszbnqg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvixlzt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2fitvvvsq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2liwtdbjs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxhkwsf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnplkmpo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzthmwg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfbifbw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpwzxgr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxqrilq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjymnxpv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2banzsiec.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxddjpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmqmquj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkkubbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsywsqsz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2reudqrwp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2urugccfu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mchkzrcs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgiyrtk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmacqil.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxjaeut.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyvewfj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmkfvki.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2roewdywp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtncgvo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrnqtok.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxvutot.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhuejuf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxhqjhn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2acvaaczy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxwzrxg.html


<!-- 参考信息 -->