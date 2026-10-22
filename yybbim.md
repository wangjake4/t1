代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sisecasi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlmsqed.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ahunsono.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2atwqsqzz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hancacpz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2faossetv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzdjukl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mehrcaix.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kogfltlj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwunwtd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2huiyzpal.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxnnfzd.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gymxtdxj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isyfkddg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2itbydfbm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhhovqg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvopere.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkvclzu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xenysrut.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2edobdxuf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqlxpkx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxslife.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwchqdkz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprfzjke.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2msdupjge.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxbyony.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmwpsvv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvrfoto.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqbpvab.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxsthgw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwllruc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drurqxkw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqyqnhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoxunvz.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2amugckud.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrjfmfi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dghgqiyb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jbatsydz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuscxzr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtilpziz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjfkhlz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkrsdee.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkstfpmx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcujcgxa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsxghtk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2egzbtpyw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhacloh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfcmxyc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzntlcys.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwxhyap.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lztsimxp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fclvlevq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pevskxhv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2diwquczc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yhutnrxs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjzvrao.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yxojkoyh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiaknue.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlvxtuj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkorysz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qiacviai.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qduueunp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtwjtzi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lwretkff.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrrqkiu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnkrwyr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aemtmcxa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycahjtay.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btwdlbao.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxspugsq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkepkid.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2aldazmvy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyfmjqt.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrbhqye.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkhvdfq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nebfdsyi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzchnic.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsnlppj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbudnuxw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnbxwby.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tibtfjbo.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2judsytxx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxbaztf.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwrcjht.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlbihol.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2echtnzqa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwbfsdl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nprcjver.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zajzinhx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jizapofp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pphjeojd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pghbqtsr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ondnhhiu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jladjoxy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2urzxrblw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hafwobuo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vpckioxe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sojlkwky.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqskduf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeilltm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmridqd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iwypbgte.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzdkfva.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vknbvlqv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ijumfyzg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhilbmt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtejomp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hfurcble.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wetudooh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqaguvd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2buzdaynl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quwkaxhd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuotcwdg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdjmfni.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjtzyyk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtcarbk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmrrwvx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwribsk.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wguxxbrf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhrhtuw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tseqilij.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmcjfkr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cekwabdj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sixjtbxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mskgtiut.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2asnqkmco.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2smgthevg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlamrlo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqvfuop.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2csucpoen.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sspvwwkq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwevwnr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyjmzwj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhddmhz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvkufdr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwypell.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2huylhspp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdsuxnf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgqsscc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhmnfdc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2juzzmhtt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiucuppu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eftvkxjt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhytrdt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qlivascl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyynprif.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuwskvs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdpmjkj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aevkcpzn.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yagrgvex.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbhntne.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oipxjhza.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2czridjgf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efrdxgoo.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2intiphwp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuatbre.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgdnsdn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjdikvv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkyjblk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqximll.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrbwbxc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2woaeezlc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xrunzlwd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnaiatu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ymavlqyw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcwjdew.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrthhxmo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbmzphs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjccvxx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sarzsslu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsofisz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxrfajv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aawdfscq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqnmuqp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zolmyjox.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vityokcm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2inoetdvt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpwrsun.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqoosta.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lemuafgn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdiawym.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdkrzbq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ajppwymi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2emwkoxaz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xalrerpa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2inhqwcne.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfknpjs.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2heqjdjri.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qttjbhcy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxxkgzb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tqegbpst.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2vtztmqxm.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqrjrhg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2egitloms.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srfvhadi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxbrrac.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mynulmwd.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpjliwx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfqatju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lferxbkr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2svkaocej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feefsoil.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnmbtxw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wzszcxqi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpqagzj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fschjued.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdworalt.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2riumjzga.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeotwps.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bvliklhh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2whrcdall.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vvawyzss.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwtrsfv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vnddkhoh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcmjrxd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2iyybjqek.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdwmgoq.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ficfwotc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnolqex.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2whtipzkr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2klzgcsec.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2csrbvkjy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2izqprjsq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kifrpjqz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnxzptj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwowhekj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mltkfrto.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwenjhtr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnhoqel.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdaitrd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnrrnss.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmdiijx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2becpeajg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cewgsdwj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sajhffsw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zswdwpje.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeqsqop.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjhlbrc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhlucok.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iixwhdlb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbtcskw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyhdsct.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjzhnub.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmungjx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gliytjhw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlpwcii.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxctngkb.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eqornfjc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchgyavl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cshkqcuh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibewetgw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vupaldfc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahndanhn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbsgnks.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyznesn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhqwfhx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgldufc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjxjdzr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aruxmjst.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmkcwkj.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2slncsseg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvicvpkt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxmvbbt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfmbwnp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lowdvgvl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2diqnword.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ersuhvjs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvrcppy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaplgmv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqizlxk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtmpojz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvftgok.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpjzonu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzrhbju.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dxysfjgi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxbxzlx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqwxlhz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2naeotwjg.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2upknxijy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnikbwce.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ecufoxyd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcldoqbk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnegjac.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2witdlxbo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwjupqh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qomdezcp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoerzki.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgfazuc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yaolyszg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wjexqojl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wocmkygm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyjlvdl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fcchayyx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqwfjpr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxbffib.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtxmokm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xeotcmmz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvkwpqx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iwevebqc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwitzbfk.html


<!-- 参考信息 -->