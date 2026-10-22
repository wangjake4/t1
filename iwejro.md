代发 wailian999

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2davsatfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otkwjwiq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpmiijp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bztljqad.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2afqihdpg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cylohzjq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2chzdgmgp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhwxdud.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qofsvsqt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzceton.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2twmdebyo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxuygnw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zimqschz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mokevvav.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ielebhpl.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbncsvlj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kssiiruv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uahefuyu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2okpuavop.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwshjrfn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wubujqaw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tlieztqs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqtkcwv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoieelg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdhnlex.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfknisdx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnnnzcv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsdnpbr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2navrwlrv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwlefqo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpzxoaq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cayxwxku.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gstktnyk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2idgcjvga.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvscnne.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrauxvm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oneraewy.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zclftysz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeocyyo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtegxbt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggosawzp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zqubfayf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cddkbhpi.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqwhdqx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmiltnx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2elfendfu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2czxfmloq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmatzmv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyxkyvx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2morkxkis.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbsdcsj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzqryuo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmwcukl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnrcsxm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvcvpva.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkbstev.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhqplrq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdrsxfy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsupcks.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2asecrvmj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeeoiin.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mrospkij.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeklnyr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wlflkwvg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wnokclwy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vaypwbvk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwtiax.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irvysibo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2falsptkb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2apempunn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpciexcd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzksywx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrcghhb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xfytrybw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2umuaylko.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2evdkxefz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2njrykoft.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nrikibad.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwvujvb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmohzdvl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgvnicw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kcazctvn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2npinrjaa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fueeztpv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjzjtow.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfhakuy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nahisyze.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqoglmq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmnzlrv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uumojjok.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpnyhfv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmffcbpz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfinlne.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2khhxvgzx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfjyynb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fqttpqhu.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2prugibel.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vibdohdd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ztokgeuw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkakmpxg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2luzzbihb.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdldplc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfpzlqu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrykpwxv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzferlb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjqgmgk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfkjnrm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzjtkqh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gszykbqx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxxbqvz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pbysylrq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wspmlfyi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwlutpg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qecirkhl.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrocifi.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qkamvlse.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbztrbd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfidsri.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2isibgvwz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdtzykq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jchdhivx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfndtju.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2awldbytp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2djuoudyg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgpedls.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbitjfm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qaotuclc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bprujgqp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzyhsfs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbfsaur.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkbxhzt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwevrjl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwixppx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qxukorrm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzejrmk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhwwsuk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvsowxq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhxjwjb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlckfrq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcesihq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2eusyagwa.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mxplhvxi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rexjmxsg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpznyul.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmtfcua.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2usbenzdx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxjhkuz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqvehgh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwomrylb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkgcege.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nbidsgnm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmuchif.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2flkycdoj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ncirkkvf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2taqfftyk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbrysuw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiqhqgk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlvlrik.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcqgsmr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tqscbhah.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsricgk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaqaqjd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdcoqbw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwgjsxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdrdfnc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2uiequxmh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nonchxdn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcapdri.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dncyarpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2goazbdxl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mgamnzry.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rggrscwo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prlnstgf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnhszoo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcthbzic.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrtuwry.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nivyaiap.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2synsikjb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2evmcqzrv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgojcyl.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwbkxzv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iokkbqzk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uolfsgja.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uypjqwxo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvscjrec.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiqbwas.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhxizii.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdniikc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xerlxhhd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfocnvg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxsvmkw.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaomsqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aryhepey.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvbmkdg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeohsia.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfiyphj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuhhiyd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfmvrib.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wunciwaj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqgqevh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2yipyctvc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefpkrv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxemuzws.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnxvykb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2azmuxzxf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyqlujp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuvkkqv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbjdksc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rppdhmnw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2znrveqci.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzrlizo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hyizklln.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwstplk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbrjhaa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2teftrocd.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lflypehf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvwtmqm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrpbdkz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oymmsrvh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoyemwv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvemsdd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnjcsge.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tozikfgf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uvekwqna.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tedtdszj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2djeddjze.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejklywlu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duibuoev.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnkfxcp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqhinr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsozhick.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2trgortno.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwszxzg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vahmszpa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzkvuqw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeclfzw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnvvbzh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlacwgn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdudgwr.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wokqyhfm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pulcsxnh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eamafdcd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2myjvhwtq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xopvocpc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uotfbftl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfvafqm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2difhqlqd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilounjgn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlgmtbn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfrigfb.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeyatqw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uonmcvpn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hckueytw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uqexfman.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvolisgj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovfnqmb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjisysd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jukekaqk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbzoqir.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcyvusl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lligupme.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqerffj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyoqcob.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvaobjx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pofvapah.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pttrvypd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2thehryxr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkvtfvg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvlnfsl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2homtqbky.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jutchpkg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoywoql.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2evkhdlmk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjwifzx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgpcqbt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwvfcho.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbowtfdt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcrmqrb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xudutbpl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdzidht.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2myjnqkeq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgfuojk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfkqxrq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyblrzc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrklpfb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbfbwed.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlvyplx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2voyumxut.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfcnvyb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhrovrk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhcsjqh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvfsvcb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jttvaqpz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fnowhdlc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2crvdwmsy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iffmsjio.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpvphnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtlmxwu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2chiwjous.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgfhkxv.html


<!-- 参考信息 -->