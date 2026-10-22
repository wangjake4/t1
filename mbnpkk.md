代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgwcbqk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrlpit.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqomewg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rospbzsy.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrhdnyq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfcbcjd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uorvoldw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwsfvkt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2toewyqbv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtzkfab.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsgpgud.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqqyfne.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2arhlctah.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bkifppfp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nofpgrak.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdyepjq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wimddbpa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxpayur.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2alqihndq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lktixlxx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpjatkg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrhajsl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgjlmmp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmalfnj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2oawjkwmb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nreffoer.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyswnzn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prriwbpu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qxoqnibp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnrvwvu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkddmfv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhicfxpc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpkeori.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlohqmc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjsholt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2blqtaked.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pziygepc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqktbqs.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkxgksk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwakdohc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2olnrdvqq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tyecqply.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efjuqmbu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmovlbhu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtoahme.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvfwzfs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoznlfhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfrrgqs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfxybil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afqaxdnx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxgusmi.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwkqejy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mosvsgqe.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbvzvwy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdyusbf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkywilnb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nussbqgx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxiaxsq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkkkpcf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2aapefkqn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuyofht.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhzkczu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrjoukk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhqsybp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqwvhzt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jziqbqeo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tfppbwdu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gouogwxw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cyysxzit.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lmijhbvs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjlrcfc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhagmrk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wutblwxm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rskpdrdu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwappxs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhypxrhy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2idddlxxz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cugmfntx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2exjezdnn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2caqgpewp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxyzrfl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhtgnig.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2efiuanty.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmmkfay.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtzppsx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmdesvz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cclzcmyp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2frckxgll.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxopygz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xizfbpbw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqjvfys.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwrizqn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhrepxa.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbilxwae.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qixwfxkc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdgmrha.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfqzblf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkznenbv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqadfjy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmjyckn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2amfrfngf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxrpkdo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjuaxac.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jnimsmox.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnynvpvi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvwbleu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iocelcue.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjeqazs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2saxxnmov.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqkmwjs.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ormxkhro.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2exfmpwzk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2poonsqfn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwukexq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2bephgmjp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csxddetw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvqofci.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rybgeneh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwxuqdp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zoebmtav.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnxiecn.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoezzzx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sncgfkwp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2aasxybej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhazxgs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2abskvidz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2afktvjlq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyenhplw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2glyefpsu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hekfykup.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hasweqhq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjcpkpn.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmiokqe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2taqbzkbf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2haaxiyce.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2levbvdfy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wthbajoy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ppximbfg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlxfbux.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llckszhe.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oznzzynt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwauokq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnxpeic.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2prsezlee.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2scqnfthx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtpipv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcicdcg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfnnnzg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snjahijq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqihzwlz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhoffsw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbywksqo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2duerwulb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuwowiy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzwkwmk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpafcqv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2beruuads.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaurydy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cguvcjnk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqozjqc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzbladd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gntqntlt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxzvtih.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmqfwtb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nhijslix.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcbqgxq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gsywlytm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vgohnhsu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hicjbfrl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjfzseu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mhknrdza.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gqypfofj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jnauslpy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2krfyokkf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kcphwsen.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2knmyqayv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cindbizf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxrrukk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pttldqvy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2niuehmdd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2adwppktq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2waxysder.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dprsyvfs.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2akhwdgmh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmpnqod.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tukvjpzs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2npyybpee.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kisvydyn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnybyxi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbpkwaf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msepddyx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pekoxgsq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfpeanf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkiiyik.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwkxrog.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kppmfzjx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sarppcwu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxspcqa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnuwlgx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ntycscdv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2avngpvbt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2keqazmgk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhysfdtr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qazvckah.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzzvkqy.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2obujnciu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzdulrl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wmaoayrn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tziveyhj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdhrpxh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbwrjdu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2valbyjdc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpgzqqc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xxezukfk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyyftzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcarfozc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cborylfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgrxdaq.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbualhgl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfxpykh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuidshpl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gucaypne.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iizjkvkk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsoaiok.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojllgqqb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzfntks.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2psihzocm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbumhnec.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyksjvs.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwimrxr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yztmbrbp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2renzpyck.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvrbxnk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbiogzy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vebbjenc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uguzqwtl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2edbesiff.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2zdufeshp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2exabnqtq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdpinow.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdeikqv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsguojv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjmaowi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gothtmiu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgefclxk.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jytnhhqa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjzhyee.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2batrzndb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2eosejuvy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgetsxs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaauoqb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhschpj.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuwcxfo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zjziqopf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrpnhcb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvexwch.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlaahvx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yexdeyts.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpdhnmu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqjzizo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgubgzzj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2roflwfxe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcuslrz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nyanmlry.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ippeewlj.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2adkndfuj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkohygk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ckicjkdr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nltvaquk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kiavldhk.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrnrfia.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoecaqu.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdooxfx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uouijxla.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2chgxbemy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghghojpp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2elixkoza.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nviydxou.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoobjoby.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jnejhyzm.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgkvwby.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2allsdagg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vwltdgmr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqyydnl.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fizedrjp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvqriqt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbkyihv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnlbmwj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kbshffav.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fridhfnw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwuxrsa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmjpjuq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tabztezv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfyjvpx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsaksje.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2swovvasr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rlngydhn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqptaswu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfazbep.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsdpnxp.html


<!-- 参考信息 -->