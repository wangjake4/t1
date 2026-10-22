代发 wailian999

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2amnwnujn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmzvzrw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rldwukvs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwijhns.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdsrbel.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qydfsqwe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtfmwpy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtpbqch.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2illzsypb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fknlofzy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2icamkxcm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cmogixnj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yaixuuwh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdodbify.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdjxini.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsucotl.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2djwcxbug.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryurgdvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yokjceks.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzonrga.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfwlxax.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2otnrmekx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxpkwlp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slcyvtyy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hdciguhu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dobmmkse.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glzxkrpv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzkmrbj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eddqxrez.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2saarhadm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkezffy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2azlgqozv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqndnwlt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbttecie.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfuozjo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlfwcmv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gamsggwp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnpjnqq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtymfpy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxqcppk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gomwnyfd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwuajub.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rijktiuq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwntnpx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gickoncu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xelnhleh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlkdlgd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lhikunpb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuuazjl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rcywiyar.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2luidxpta.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvszxyh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amneflmc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lgeqdffs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcugvlln.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzqpzce.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhmklwo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iatswmqx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnxvpkf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwfqzdx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsbcsja.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsktgoa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnxszur.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hclpzbjj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyynqle.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fibjksdv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2llajjwrs.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rknofxcu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgjemhr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoldeok.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sewfvxbq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsmagvo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yitctssp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2shnrcuic.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvimnft.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rxystnty.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvhoofh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2byqzwtbh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2juvnyqkw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuqdvkj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrthflr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jipuawgc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2clwllctr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmzzxur.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2sqozzgmb.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsfjbpt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2zjspjepi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqifyuqx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfenujr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhenrjnv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbmizos.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2egbafhsf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qcikchth.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xgexpyss.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrpload.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvbuiwf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsayxnt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbstyzm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nshgpxbu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xbchyzhh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2eflyhsij.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvlarbo.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lddxtwbq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjvpurc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lpylorql.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwvgbas.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcosrrv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oquehwkg.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrcoirw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzekniwy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dauuewsq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwvhghr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfuinst.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zocqwwbg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsqycsq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lamekpaa.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2btdpiqum.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcovdpzh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2anjijpnm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwyuxrm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtgyksz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhgtahw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlpyzth.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmdkvbt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fqozyniv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dydvhobo.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpckjaa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvnpjpj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sttemlke.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwscjyeb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2forjzkgy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxxinro.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bitkfqdi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmxvqwa.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxpvwg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgfaxzk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzfwaoa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2tujiftig.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mucgjmce.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2doguhhom.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hwolenaq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgmntgg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhosphva.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcwhscw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjwohhw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkhzdqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjkyxqi.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzowthv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcfkpcz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sisallnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2baxxcbpl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjmbyyw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmvymuz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnoqtle.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzhnifi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2furykmyh.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfimwzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epizgbuk.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aunfvdkw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bctxmkur.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxoklaj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqqafsn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfdfgua.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2whlvxxwk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgybonxh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tuneuzek.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcstqpoz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmanrke.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epymttus.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cswvhfat.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfvpicq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qegpmiji.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2addnilob.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jajhkgjh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfccnuzu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzrrmas.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bhihtqan.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2glbmxyrd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcgdkcr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucypipfr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhwblg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2edlmuwqw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxytwnic.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbqxxqe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqbcccg.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drrxkljr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiessyx.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzxhgib.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhrcwo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kennmdem.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyukpdu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kpujqpod.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urdwwpnc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjefnmpk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mydzhcky.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsohrtc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctckzdam.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yokznvqb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpyelyb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mfiongks.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2snuphmzv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hogyosaq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgytuza.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2epadmsmw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2omnekaug.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xovgxiyd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncibgjdb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vanilais.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuultxj.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fupxsydb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkykyoyq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2woctskcx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cutzudqn.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2risdsjbh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2giuhozst.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggygmcoe.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmcszqb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrxkiby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2egzpzwog.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sethpswh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2khmkfnfx.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ljllfthv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dhngozbh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwdswau.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpomxvo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wojekpal.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tobyoqve.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2panahuwl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2znmedzst.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsbcxfh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gunpkggm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrobevll.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwxdpwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmslfjqj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqmiihw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwbzlij.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xspfxlhq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrlcnpz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvwpidl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nvainsii.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtgyigx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uirwbntj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fcghqopt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2naigybdo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nthwdfdx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcvwefh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoefmul.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqpgovm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrmszzr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgjzmra.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pormunda.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjjuojc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdiuefr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ougcrhri.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kjypqzbh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vguolhti.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tzakhktp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrjxxom.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srtjaakw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qloogqvr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmvjspa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qktlasxp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiodami.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kdypivky.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2spdvukdh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zopqfyui.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrdygiu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxjjdla.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hluuikwr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2joxrscrl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aloirhsc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2krrahcvu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uytlichz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzwsxre.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkslvwn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2daubezby.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrhwhho.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjokcarr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hindypkx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2agkgdajb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyabgbx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaeowaq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmvhkdf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvvlqmx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dgglxqeo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukasxmjw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbginoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmlolme.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2llobruhb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2enqxiaxj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpuvyyj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnduqjd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yuenvcyz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrtblee.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lthpmran.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmagfbv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvqdcfy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdyvrpu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2woxsffri.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoxonua.html


<!-- 参考信息 -->