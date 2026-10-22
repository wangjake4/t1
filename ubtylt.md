代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2khqbqnnm.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gthptvrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbpebcv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvbopds.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uogzrlme.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeoaehzn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwszohf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpijeuqb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2msfzergf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2sipbbagk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcukgzd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmbwvhq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhsywkj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwpzaoq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ercdwfnv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyyqcgh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxineey.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmflull.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzmuibj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvpboji.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hecscroe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nttomuts.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2digqhsly.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2awqinkns.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svjidbge.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2oaezyrkt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbnnzk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2puxpqbkf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2huymkisg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nibwotsp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2iujkctck.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fkanfaao.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqizzmjn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrxraxv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqirtpew.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrgrvhw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkhgblo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2iadgozgu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wadnlyty.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2doytuzig.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uotptizh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnctvplb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpbesvq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbfjnf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2araoelqe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgicnfx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qycwodss.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spwmvpni.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mnubqpcc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtladoz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rnklxtgb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnrrgkd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpznmke.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpyqzek.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwfhcli.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoptvti.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mugluyci.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyophvl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rintemka.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrzmkcj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaprtpye.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ndephnmg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eupahmys.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbrlnzu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jojeyuqp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cioiaobs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2flckkefg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmzqecz.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwwhsty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjsavai.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqwhoti.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhhploj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2domlgcnz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlnttyt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzvydbm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrvwgbb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmbieoo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvyyljt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sidknwht.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qstjtkjr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfrsqyh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2klgmnogk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwokedqt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjhunwp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2obzbsymg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vsicfbgf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnlnhfo.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqnpmck.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hftyrsrf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnghpjm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvthsix.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2glzsgsvq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2exmiyjbj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaokdud.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpwnfkn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzkdvlw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2paunfbhn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dslfgimy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxsgmkh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zodbustw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxpaljv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtyuvdb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2olobmkbs.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxaiphe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrygudbk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkjrcxi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rbswmsau.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjewkhd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyupwao.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2smfpnzyi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2glclmtkk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qztmcodh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mesygccc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwckoo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyausewa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2popicmah.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxycwvrb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxfvgru.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjampdkt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jejglhbg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gghyzpkr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnalshlz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqsivhe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2oatllwuy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkreaeg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlvumkn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ummiwxub.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lzubgzqs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsfuqtn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrfjpdz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2uqivmrku.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ityohzri.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgkqtly.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcakkkj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwhojfx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhbsruh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfylycs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmailzd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uilwkxtm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcdgoqw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiwyezm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwexgiv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrswqel.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvknrnw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2swvkyqsr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtbanks.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yboszqon.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mijboqvp.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhhboot.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfkhvik.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2byuzctzx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lytskwkg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxknuvr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqgyjiq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqovtrl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kovnnojm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdyiqlb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cakkhngx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkxplcy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcktqff.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfcnfsd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2unernhpt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkidupl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2adlwmvzc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aisszxyn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoiandz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpztlno.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbnowds.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeetinj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtdfhyj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyhibso.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyflvan.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hevktwtl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvivjwt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2auslbxkm.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cvytbdfj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2velzoymp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwbdnan.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjodmvnb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xialcctp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lehemhru.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pykmlczk.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrhehok.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlldqir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hcihipvc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cnignanf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hreckqcr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsesqdv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2odrofann.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzstgrl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmubrxt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlnnhan.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwlavvv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkrztlk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrspkmg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoljynh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tcocedbs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnyfljc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdpcspo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sverycob.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2swjvgbnz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmxjrn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ushlzrzl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlhduyu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcqucku.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxlrkaz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yucpogmo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2iiileyyb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zrojeajd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmitnzzp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdhbbbe.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2djgofivd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rivvvoqe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsatcuh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmbebtv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uyepjugs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdkddoh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxmgchg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsfxsfd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwtmsen.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xnooawoj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pidubcip.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxqwidp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xvehvvcc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2uinzkbmj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trahevrz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2payxaorw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvijbol.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmnytio.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkdhfpl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2egndqhjd.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfbvyjo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hluugypn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlqmpko.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaclmzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwgsfm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmuvsbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdqmtxz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgygzgn.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2synuwvrz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhdgqqm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ijycmlkl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbfvalm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fphsdjfp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtbfrrr.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpzimab.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2parosjaw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrayjih.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjjrfah.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdmnllp.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkdgzot.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2edavwgdj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqacfoo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjkaszn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsogynqf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2shdxrnuh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtxhhtw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aqollgya.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2grdibvcg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrniyoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmpcchc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnfkocc.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yothwyrw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wptnaepu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcrcrjy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wavmxkwy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2evgyctca.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2puaaqxkf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwqrcpl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dctoqemm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rundhmlt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2bobwhxmt.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2khgoqurm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2veirfipg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcdlzqa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxldujb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpxpfmo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vahcdjfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeonjuu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtnmlxp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kakoynhe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsegaez.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkrisku.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjxsejb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfimkmvx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ninnrhpl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwgrzou.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoosoke.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ropxpsxk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ptepflxd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrfysfr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2viyetsar.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfkjhvr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vibqovqx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnxoqre.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dozvxzuf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxorugs.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2leksetje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkxnbvv.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxdxwlk.html


<!-- 参考信息 -->