代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnekpij.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgcueio.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2exitenrl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwpupqk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogujwazz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrvvzns.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqfotkp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwxvfrm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2voswcxqf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdhlvfz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pweararl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njclejob.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2farsvgse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jdczsuha.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uefcvjpa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpwcuvo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdbhnrx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2annnteio.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkitcwo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnybjxas.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qandviod.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmtnoya.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqitwkx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2adoptsvd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2areyrmsb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2emlsvers.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzctzrtc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpzatoz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmcwhz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkjrmbw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjaavqp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbarvnm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmmesai.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxrkdns.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkexagg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hexzscui.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2brxkmwts.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkpuimf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqasiswi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2atjqsvez.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwbhdag.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpzfsqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2blgvfdux.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hopigvpk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cpywxhmk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oecbgetg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfxdkmc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jarqwsai.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhabsxa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvwtbgq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfffjwy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2exjmzick.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mupxsdrn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfjiwma.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxermbwv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaikyta.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qchqnijx.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwtqxra.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bizuijvx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwtasns.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crvgnpys.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpohyno.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhzygmp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjmysrv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sakfkfpr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwtbazo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojklmzdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyourqr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnmrfss.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thurrill.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiejwoh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvhdljy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2csrzlkkt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaroyzk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2bvehganm.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzmmevq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgxlurb.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgpjvgl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvnxiqy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxbnzks.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiogaumu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eheceuuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfyywrb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdmrugu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnbhgqe.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkrqmik.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwvohzj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbsyghj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqaattv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2durynipl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ashsmgxg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpbzfgr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzazpkhq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2glwpqkrg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjbrdaj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpsnddh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hktccgkw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyaaphg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nxylmlpw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkskjof.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2obddpgmh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iztuqmra.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmakeuy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqmroci.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeavzkc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2crxyqhfh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpyficg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqywzml.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdtqcwi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsmyped.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdijkbt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuappgrz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkdjqbq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlhcxso.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esxgdgtj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcfgstq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2idewuoho.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxxfjiq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjnttzv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qedglmct.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hbswynom.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wzycxsnu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvzrars.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bldfflfh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2joczraeq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhstollv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmgdzrs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvkenrr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzbwkje.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrbacja.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qyefpqyi.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wjicpttx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eygxhvgq.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbfokhy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhmjyfc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwanwyq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zyepnexx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jrifnyxw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jwacozgp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdqcjtq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqrmcpt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcffzog.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkcnrcc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyhoxyi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xdysybvv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iurmovxf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukgxcet.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kusxgqpz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pskfllhk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rryltbwi.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeqyvda.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtxnopx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hqowwlgw.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrsjknt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcawrrrx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ladulfei.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwueove.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2soqwjckw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeaaqcr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qycjsnsn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2daaypniq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2orovvybt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qefbfnmz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oetkuinq.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtvhnrv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2omwdqmng.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjnqsjh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ognbarcy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbklnko.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiyxpbr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrkecek.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cenugefj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuliqiz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhpcoug.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdzuoto.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xmygbpdm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2britxqzu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nephiqyx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nnicgjbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxphbkx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gyffuzgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtqynvv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jpohuret.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiujynu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcorvev.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sczypgqd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlwdrbr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrryhaf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjadrb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tlowtfjo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkokkpvl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsywfkp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfeuazf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrqftxf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjsrdpi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2aoctusql.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfviehi.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaedqrt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuliyec.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sturqgpc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2erbmmfru.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmebwzw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtgusgl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2athsuyre.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aspwxkqw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvbmkhp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2umnifszo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itikuysf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgjhxoe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iatnjtdb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsxrusy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gdweajum.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxstffcw.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2idussklb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2evpjzqhu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxmfuit.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqgnpur.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2suqgnien.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdhgjhu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrclnxy.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwijont.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmgmhpb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiqativ.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvkzhyd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbhpgu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvkakra.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlteuux.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuobeht.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrdljfs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2omlwqbaq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeslnqvz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2funaungv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aauvpwpg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rqssiwdp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhrmuuc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kkspexce.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvsxldk.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcexovzr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcojxwm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcsrkzj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltipfg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxtjyru.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlhgtyd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rpndwasx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2unlrfenz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axzzjnlh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxxzytu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmhgauv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nljjaqir.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhbjzdr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srkjadxe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvagsnqr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bsprxyed.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ortowxcq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2exyornxm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rznzlghy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bmczatsp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iizsextc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2keavrinu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hauiqihf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2saghrcav.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjzbklv.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uceecvqb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mquaznth.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cehtiksu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lolakzbq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtatvst.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2otqlonun.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hloxjsws.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sndpkjdh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpmnljz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2czqsiggr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgkxwzh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcdognl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyvfisz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxpfjpb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2twzspuoq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsamqqsh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2leofnqcl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuyennd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iabcrgxx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lklupngj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esmgkhad.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2crofskzf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iukjqgoq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbugtvqm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrmzomm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcrdnjr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knbzrzii.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aaodlxcy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqtmyus.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nxihynrr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ensmkmlv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qjddgczg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2umgihpgw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tectydnw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsglldqm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2odfkeloi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuvivge.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jifvcyea.html


<!-- 参考信息 -->