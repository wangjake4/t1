代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyuevbr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntexkjcm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbjukgh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2upsuqyyb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgvajhz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ishicjoe.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsvdkgr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2atjjzifo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izhbhmim.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvrsdkr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2axatvegf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlkcbmd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxlflac.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpgrqpv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmvjxiq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkupnukp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhquictd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdyfcbg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxlzhac.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqjsmba.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuurvyy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nigzehva.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eoamipqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjpsvzi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yytqbwpp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvjmsnk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzgszbn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxhlbah.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcueasd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jesfuedb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfonayd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhtrbtt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsfixpn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryeenids.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjmqgbb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlnwofh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsdqcmo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krzkgfpc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwozrij.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkioisqj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2egbivrix.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2azfzaiwi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfalbno.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkwkzxu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvvxfnz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxkejlm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvddmklo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhxzjic.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcfwmyh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrzcakb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2olnkebhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utqqvxsq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbdbggr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pooilgjn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2idlstquy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2asrythrv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmckqby.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwwizfl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2inyybyra.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2muakasgx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nqetumho.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqcsvch.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfepdkv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzntyfo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjtwvqp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfhycwu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaaqljk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbacviug.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlbvzyu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2axpuncad.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjmpapf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2skswcinv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xogiykpk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qtojcxsk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2onbtjrck.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpdsrxn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qfukdmct.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2egncqvqw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2agppczqg.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcxyvxq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrjpvao.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppzxci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvlfyqx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rbazwcvz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oswtkcce.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjqswus.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjzgrbc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdstjixf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnzosoc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2offbvbpq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hznprzll.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ybexpchx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krxufehd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2elkpltzw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glbikqeg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zulwshaj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjewvqz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfiqjxe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvitilwj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxmewja.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cggcdvqb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2prfisecz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knjjfwtu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxmrhxz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkwabzk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tmruucba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wefepvkw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2hmokikfa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjaoywt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyuqtqp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eidunffp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyetngu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxqyhmh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jypemokv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiivvsw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbjuznn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tkziylgn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2srprvzbs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvezmyw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyqxyti.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjduhft.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2trzquegq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fojdndwy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqlhurv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsphnjg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmdtttf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfpjwkb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dccezjco.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2itrommew.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zgttldwh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yskwbuip.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqxkokg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeopxdt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ebayhvii.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlxxwkf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvoihhm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yiujevay.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bigquksg.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnewecc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zyebjebs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cytzoenf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfalxxi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgbfgvr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwqoyrr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2czabhycg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxrwnex.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxbejga.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpsdnxx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxzcled.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2czavxvgo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ontnusfo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbgincr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mezeynbr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyruceh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtfotlv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnyzows.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkfkzas.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvvhfjo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrxnqmr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2spsmojpl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jammyckx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nprtqfhj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzlwkcf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2iizmvkii.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkvwxsd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwltuwq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzdwasf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2buozdgtq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqhnxgl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oxictfzg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rzinhgbt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rljvbeqb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhxebxh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isztoyvk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2alhghews.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lisslvoe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhfjjdh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cavjcxfa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cllvtywe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2eouzeqja.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vjejmsne.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivjfap.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbzgaaj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvfsuou.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pauxgvbs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ftolefhq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pznxhdzl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zupzhceo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kawrcyky.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2alidssam.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvhgif.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgbiddn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzdjtyj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2smvluhxy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glmivqzo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfiqgzz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wofszxtt.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpeqjno.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbkehdh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2unltxigo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrlvmte.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbkwufk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgpydrl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvxczmh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bopormbq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2tydnmfqb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djvgamxq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfknzjjs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqkmwkf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvcolmt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvdiarv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2sqccuwjh.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2liupepeh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fraxomkq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlgtale.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvtbbjr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcetjmmu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcttdyj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fijofpdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kluqfovd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjhmqaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2louxnlzq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itayszbc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oljyjmzo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scezyoqy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2llnlrkrn.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhyckzb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpppkffu.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzzakjr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlpofpf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2teyisiux.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skvpwqmm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaquzoqx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdntvrx.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtigzoj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwfsibn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uegundej.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuahcvy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2musjnxyr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmzocfz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2asyhakzd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnrkysv.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqrdsuu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdvonuj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwoeyyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pluyvava.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnfislj.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmizvfi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfecrqvd.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xavpuvrw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2cogynexw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sykazhgo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rejdaayc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeoxugj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfvfnyq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkojawc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcdcdlf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wejdeqys.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqwljzu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvolmwl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzaoeev.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ijesceoj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzukeon.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwfsjdr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxtkvki.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaepigl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvsypks.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bflbmrge.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyectfwj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oymghujx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2txkzmctv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ilawsqob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fosvsxjw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gmslkmad.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkjzgvt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaxgnss.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpnusgp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvwwgzf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uidbvecs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hyalrjvh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2auqfhxkd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2llawhujt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bykjtplf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2njyhuwcw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkcbtnb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vtogqzsc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2efkyaycp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhvtmam.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vgskwfxv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjuplmw.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amshiakh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdnmesc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2offgzues.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2scwlvgsp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyuaism.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkpfokc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wehdnewn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nksjeunt.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ufybyomq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmzyusm.html


<!-- 参考信息 -->