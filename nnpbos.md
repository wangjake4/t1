代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bhboompx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfudrqao.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgrcdrv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qukjtfqx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhfqcib.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofedfwuk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cshvmgco.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbipssm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrntqla.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgfimsw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsbsacp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwmrtju.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdvhjwb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2omytpamq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pntwurjt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2drnzpmet.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtnfqyl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbelwdk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpwjoan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrmymw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2syzkbuau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvyoimi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwzjzxu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2aoivfaax.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjtfsiv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjhcurt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2witsforc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnggjwfv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnmdxoj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgrelsp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2itpruulq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dckbasir.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhpigtx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzhhopq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxtqqks.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eelornkm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnmjkcw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhjenho.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnhrghx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzjernk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ujauohzi.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vuspwpoe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lljaxcao.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gagmlgjj.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nerrfrwc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzncwdke.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxurdxgs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2igogywfz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjezmuu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrluzhqr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onrfoeme.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jipfpylc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjaultv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2skmxtidt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvugamf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctucrvbs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlnxntn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tooeslrd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqjqzwi.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvddamrq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaoqmwz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcvmkaw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ieifdiyf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aegmbmrl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvrjecm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsydsgyu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqbzoth.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbblzccm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxblfak.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwwzdpt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljergcmj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wksnwdmj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkjrhxu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gohqnwtz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfypubm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tldnhzcx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llwfimar.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2itdxotom.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2udcsqout.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cwutmguk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaazbrm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlfkwad.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjcgypn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzptwsz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqojgghd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwiajlv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxcouwb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvupkmeu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhjimug.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwffqkq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qskzcjbe.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpnhexf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtqksrj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eztpuwmn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpcdrss.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2omstanhm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxreohn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcteoev.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuaexah.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezacsizr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onyqlbxk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cjujcqkf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ixelchyr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dalpcdmm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sqexwhts.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxeuwgd.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zqawihdt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfgpajd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2aiawxgly.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsjrwkn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnboiuh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vowxfyci.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gubcciir.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuzuejs.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkcgyph.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsxeayk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2smhgsdfc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jbropqag.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkxfygh.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrglarq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnuznsi.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2glaqhjnr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfmfaef.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeppzvm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kddxbcue.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sznpwfve.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyswagn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jcckkphz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2aulzbzec.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaklpyj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ksozquef.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwzbqnm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zljikgdn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abeilaxh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnadrreo.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2sirkaqqd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtyjpmq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cliagxhe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjgocsh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyefmyx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqzhwyu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwicpyhk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqzozti.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2llnheirh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2acbhszej.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvrkspg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrklown.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxhqmtt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2npbblfmb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvsdljv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhjvyyy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2amxioggy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgnwjeq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnuaaxk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rteosoro.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrbzxdy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xlggplzz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2svfpswsd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2seyhppjk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsuzmci.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgfxqeq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkiodov.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glmrmboj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkahmkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkzmora.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzoxtdp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hthcgaij.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zaisfdqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwjukcf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvfnozt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idbsbvka.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwsedau.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dejxjpuw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoftxgp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2izijsilr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dumuynbm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2krpbraem.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjgfjcq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mshiknqv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2iutiyzcg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2fsblryfl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2obwoniyh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oqricmct.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhasgke.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgvucbc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxplzij.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjbhcvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgxwywm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2utypkpbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyybqkx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uecoxuqh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vemurnre.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rttmnfiy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvstiqg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgthcdjc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yslfqjoh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hevjwigt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2czrmduzf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vopadohd.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skpvhpmk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgubuvic.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2odkxtdiv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwmvfpt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nblnjdyt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2yttrdpqn.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdjehvl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcurpps.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmzbylg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2pohqaxex.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiquoxg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyhkdzd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkzqmsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnmmdol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2boeobjnz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwcnwrr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esnryfsa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbioorcv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdslbpa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkjjjes.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pczpelmm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mssgwpsc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdxihid.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsikijc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhlgxub.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozywcclj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2apehbwbm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2peaduhhe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjdddzs.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnofjcyc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cynkpdqj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgegajzu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtjykur.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtbannx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnpeeib.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gabumqki.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mygrqbvd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxceykyo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpewwxz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnvuswe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkuoduc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2alagowum.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pquenzhi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaxvtip.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfxuxzs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2thhpjpnu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2snyguxcw.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhzlmvt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2amhwslia.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mljxjlld.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnxavwn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfvjaip.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2utamgiqd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2blpedmsh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrveejv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbkzxhe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkvzduz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2heazdvij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zewgcggh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyrfohq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnwkjmw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaddnny.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqjgmov.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qbomnhbb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khowhoco.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2oznpsvjm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeoybuk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2olnbrklu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2inucbxgq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxxamzx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2scbeximn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fmziwlom.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdbuiov.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2januuusx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqovvdu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrtsdqx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wouoikdj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkauivx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ihylywbk.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sauqimox.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wopstucg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wevxycsx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjenkbsq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjasckk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnazoeic.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufsyvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipetuchu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpqwuos.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxmfquz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2azcvdtcv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjzntvn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2osfqsejg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktywpdkf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yogxaple.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epvitbhu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvknjxju.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pccrheqj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2knkfmcev.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzdffsn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gormilnt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzuraan.html


<!-- 参考信息 -->