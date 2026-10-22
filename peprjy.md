代发 wailian999

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyafqyae.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2whzzjjcf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crdfoofl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izlzlanb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuqpsdz.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nutrcvnz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2egqinpec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lkngxolh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcrrinr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neecnjie.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2raqubjbp.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2itzianpm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2psjjiwcc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpoakjy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dneutfvr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpbakoq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfcxrka.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uupayhxj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpmrpdw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwyzcsu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dryerccb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ecybjpgh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abaubflq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qapcehdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2decolkqo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwxqtul.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiwlwsp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvvpypz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2chlpbrhb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2asyzrunm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2puvxsidl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfhsczr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2klqhqlzk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfegpfn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ephqvvxp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwcbeoe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqxwpgy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muimorme.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2daulairk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pcggijpg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2keuikhjr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jnueadzg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrkwoxg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxaqbst.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2crrbjjih.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpocafu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjgkxpd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cagypamv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxsodol.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2cetgszoj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuqxaxz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hxovhfsd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2medivvqf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqylcfe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbqumjh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkwsvdk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awpedios.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktoajozd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgafehh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpezzju.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmnwqiy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwljbzy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yznczbwx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgpvzyh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rivlykku.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oifzlier.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bptzvfcp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxkiuan.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmtbtka.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuyfjga.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dntdgcny.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eereipse.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fafmgyrd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbhxwaq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vocigeia.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpzoatt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nquxjefu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzlzjxg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqypvond.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hoesxybx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2akpenlqz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2acozkxtb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjutzhg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjxkabh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrujyp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhzsuhr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgqzzlm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozupkhov.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2psanyrcf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfsurea.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzlizvq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjvikjo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nydqxedl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejclwkje.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmiwifb.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2oifvasiv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxzikmd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bllgpclv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgizdjh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhosfyl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdpiwtj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmphfzp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrsjcld.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wfynaocv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2eueneurg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiqieyo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghnlyf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lupcmnws.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiwmcri.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkawdau.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evdnhhwd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2knklakgj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnvdejc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfuymcv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2quhdfrnk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2itdlkfmc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2etoyenvu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhddsdbb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgygwnp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpivigy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcuiqhz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbwijyb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfiijjb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2idpdluyt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lendadhh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcaixuu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vlokzkid.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ryadbrma.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2axqtnroq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kinkplqi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiitawp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dunohjmw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2imrscqwt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hphtyusc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yslhbtrt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uybozeeb.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bopetcnq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwddyfhs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2afsuudbl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vphfahmj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sicnjahb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbaexiw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaqmioc.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaobapd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2grbpqrmf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaikosr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2owjxpvmz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnzsnvx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2oblmgfyr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmmzwqx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcnxcoi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvwudnm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvvgniv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzcspls.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxebxrz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2voekpcvw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtibtfg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjewpr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aidgymtr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaoqerx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2imigtufs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qierskuk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpbsmyt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auyqiosm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ledbbduz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyldtiu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbtocsl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtexwey.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2xebxvigi.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaiytyw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfjavex.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtwudfv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdshngr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2goorvpai.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2czqqqypk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kukvctlu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jrotlqhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aksbqgle.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnjovog.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhnamud.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amysfeof.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoexrfo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iooxadhv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcpekey.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2swvalxgg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdkgajz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaovtag.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inyirbfe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrdvgli.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iglzkdmq.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqdklat.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ipltirpz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvczjfnq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqhoikt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgujdvub.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2hsialtwn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgyeezd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vienchkk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlubeams.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amiyvamr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqqbmza.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcvipuh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgzrtpm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdswxpch.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpivmfbw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrnivyn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbshxwsr.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnzlbdh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrujyqu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqepvpj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vudpyouv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmiutr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2asoatozd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqlzxet.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjkkzip.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpnjeqz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wluvngsu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfartga.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2breyszax.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhfdqlg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2imazynif.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yobpwmtx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxvjpsa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2skgepjjx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2raxevcqw.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqudybv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtkwgem.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpptgpi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uagninwd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzytrzt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxfkgye.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ikenmkkm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztehqgnp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdyovcc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmbdpvv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggguqzwu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpyhdge.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iecxtmwd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xykwjxqt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxohumu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uqylsrwf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwazgvx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzczpaw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlyvxsk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cegukqsl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbxbmua.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbyygpg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tymykqtp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2agkptwgu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwripnf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wvstajvy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbtwhwx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfdcrjn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnveafye.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kfktqsay.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyhwesz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kxplalbd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzckuup.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yvneoaku.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhoofyt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbsibcq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiiwljg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qasbghut.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psyoizbs.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhrajqm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2npobqrjs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwbqlyi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpffznoi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xujycrpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufekhztl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqentvr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfegoqqy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzuhaxs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgauigm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2scusvdom.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdmwrym.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2exnnpnts.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmyfwtg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqgoiwk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbrclru.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkcuruw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahszryxg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbehofd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkcqlxt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2htfmhnnt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hosyuugv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hjetssjg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhrsxkg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oowyytbg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2sybgahvo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkvtpry.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2twsgysre.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhicadk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdhobas.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrgxwve.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dpanujkc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrigkxl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnknxwxn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdydskte.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bojlmspd.html


<!-- 参考信息 -->