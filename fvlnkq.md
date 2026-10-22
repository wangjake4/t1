代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzqtnss.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bwixxhlo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2noyjymcp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvoeepj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjhqesk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2lyenognd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvhhhau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgpcyhl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2llbtlzie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbeqani.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzkdxvu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjfbrwy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuhyrfo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbrhjrw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqnixl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuluogv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jumwcvgn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbybsvhi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiacohn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmryqclu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfewboo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdstwij.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzroxies.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2quukmlij.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kahmevig.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoinxfv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qswrlkne.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdcmhodq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjohcjru.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2chlrnbnf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcymhgs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2shwtldmm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnersxu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsmjjew.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnouyvem.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sijtwmjo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2znxqunpn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tunocpsp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xsixpiwr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsgsevj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inksrvjz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtcmpkv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvakdim.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkftaigw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fquafedt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzspyyrp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsucoxq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrawigza.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsrshca.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xryrhttf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csljssqh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nwbqomsa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciykcgrg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wicgdkhe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkngztr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rspmpixt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2logbcxsp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwitxxio.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaarmdi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeoeveh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2emnhewri.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2trdqgrjj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwdrdls.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2sresudrp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ganeqlfo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rzutensf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpayvlw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwjsscp.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2minlqpbe.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckdhza.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlzddry.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvcgthe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxddcmng.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kyoxolxl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aovnrmdt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwghpuxm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqgnclj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcyulci.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpwtkmv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnotbqm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqsxxef.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqbyiad.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lxecgbpa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2awjpxbvs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lflgkfgp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzwmhxm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmjsgap.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2chdyhaqi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlsleew.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2duzfdysh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aglhtklb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuyawua.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2agwnxshh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxpxmeh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzvttsk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoyhixw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwbvqbx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fcovkxwh.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sldagech.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcdlung.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxfqvsm.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2evpviuta.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eaekqrlz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2omyeghyj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwxfrxa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sakqgemu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzayqkz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2midltpsy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiahufbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjpualh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wguumtem.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaowhac.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyrkmfe.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjynpee.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzezuos.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zvodhobe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yixhonlt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iozolpey.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqijzfye.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtrromp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zikhofhf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iogwkyjz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiqevia.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwjxoyx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2auxwdnxk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjqwmev.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbozosd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2egipiuck.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ngicmckk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cjscesag.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2arrjxohc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zveehzsw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqpbspb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoznzpp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwfeyaf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlpflhb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cakfilmf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpdowug.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkbfrvx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lyluiull.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zbyufblw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nghjfhus.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2evsneqtd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lxluexhd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2onspxqho.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cyewdida.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nykcdesc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2anbqqzzo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgdmcpn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qblyxnxx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuszqio.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuffmpp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hosxvkkf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wfplzcmm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rovmgcnj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2esziqmwx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbrnhtm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2opukttcg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azkrwahe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkdpqqa.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiwxmwh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbhhkod.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lpipdlmq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2htkgfzub.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtbakpd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skcomkfs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dznzafss.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2msiifevw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jiepuxnn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvawfzr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uobbnnrn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuprhcm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qugldmnv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oajownrp.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2benqkori.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2notpacjq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrbfezy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzjijal.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrudnrm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yahxmgrv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfxyqui.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmmjjev.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhogpfd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqgjknq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlwilsg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqtxvsn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjbaga.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bzazezfy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cibiqmjw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ukymrkxv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yflmxzjr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgwiysc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2fyupwded.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kotosvyk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmihuae.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2javqzqtl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xiimtfed.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vubdmjix.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2shswjuim.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mckmfrne.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2inpunisa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcmijhc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2okpnhpfy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzucnwmy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sceedono.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrxcuqp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2engiiuun.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyahoqf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgwanni.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdshfwv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmezekr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2givhkyde.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2giiwnxbb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvtgkip.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnqlrkv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlcztyq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnldtzd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pyecflhp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsescwt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pncdpsbf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpyyagz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oruahqmm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2clnldqvr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qiclkgzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2idplywyy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzdahbn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2espvvrmu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvivvih.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qseltett.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2acrxikqt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzrhwnp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2admpusrn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qahaktky.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoiuzsc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwnvnzy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnmsbdm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uumoamrm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmukwobo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hddnkauk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yimtbvou.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjsykxf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnytsep.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvdfgwb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swnzqcae.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwlydld.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqliobi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iafxofuc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qdygnldg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xihbfynp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhqjxcn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzmzgnv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzygdfwr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2efewlorv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqowyyk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjtucib.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfikszyp.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2hazzuaoa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfsoodd.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrqqvuh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuyfzfn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eyruzezy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vtahmbms.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2afhqkmqg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yozopmlv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cypudftm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lifqmwcx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jziffrhq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmejzdf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lnihzdzz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxiiusm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmaovzd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnarkwug.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyaegak.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjhdnrk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qpictnql.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaavzcbk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdcnlpy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxgofeo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2niszbwcv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmminwbn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cskhqned.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqbxcva.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tysqvrve.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kmeeqqtb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2osxehuwp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hongbygs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dbepyonk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgorfyl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqrywgr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvhlfbj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrbamvi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqcdnmg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhxvvjn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ragjpeyc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuezpuu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxcmtnr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqircxc.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hemxpaug.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2burqkzcf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwogydj.html


<!-- 参考信息 -->