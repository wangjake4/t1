代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yydjglec.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2khbcxhvr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lygmjgpn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbymbuc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snmvjsql.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzzbdbq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpsanjo.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2thdqbsxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xthqxksv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mmziqzgy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfkljck.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqixqxku.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdimolk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpwghem.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkaspna.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vttrusij.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxxmnzl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnmpidm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqfymme.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnvqwwq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgngftz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2eheqhmwd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfersse.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cutbcybj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuokfte.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbzvbok.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkkawar.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfswuee.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlfhwdt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoukahs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xptnuika.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmhfzvr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwatsxh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wkftecqb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbipbyl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmyqnuh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oelrizut.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2frjkhfkz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmnlqjy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfgkupt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2aldcbvuz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2snlbunru.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeimyxit.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2olgpptmd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ieysktgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmouust.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2imfyrbet.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpjvlsp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uabfdoeq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2aedrgjyl.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qlebktyz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2iphpkenl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwgalyp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqngsgc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvsztjl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbhafqp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbustqv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdhxvgb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2omkvoqqk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhorjpy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2polesrkk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ultlfxbs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dkriyyep.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxptsmc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qakhpryf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yydufotj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdfiddk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdrzxbo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fayiutwf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbmkadg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfwyjpt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xinsgxwg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpiqxhu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mynstzxr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2krzhnrfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iylpiiex.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cneeguda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spkxdmup.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaqpmki.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uphjsjqn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtnxpjh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwbmgsh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2udzxhnow.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jmerwvqn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxgjqtv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxxqxmk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ietdgumw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zragrcwi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ertktuds.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgcmoad.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crhgeild.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyxuclm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2txnoxubz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeezjqg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sytarkmz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sdntjqnd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxzcvqx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2younprmr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsfbgep.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvbeecr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkuvdxa.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsenmhi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxkvori.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwdmlmf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlpobdq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akwiotno.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnczflzq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2egmqoksh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmneklw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xuricmpm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtwahnv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdnmutx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsauqgc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjnoibj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cszsdmcx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iatczfyg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2blvxyngm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbshxoqn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocskjhbn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mojszmnx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cixxdede.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhgtbpo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crvodvsb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2alvujrak.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiohnoc.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnsouum.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpilfwg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iijzmubm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpcgppi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2loxaitio.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyksommk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kadvxmsn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqlexcy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdcvqmc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2avbbwzez.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqxdnjm.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzlgxmk.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbidmjg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tptsiphg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwadims.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqpwsoj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdejqac.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cljrvxbl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fduimkel.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihguaebz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qumsklvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gddrtjex.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaxyngu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gzffvfmy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xftxakoq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uajgusjr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2romlqdtj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwooecj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hikrlrsb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uevpsdem.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rueyiuej.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrshdzi.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgwxymp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2njtqcrba.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mousrfme.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2glleyuli.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwnhaeu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzmslyf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwybjtf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqbxgzk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfqkari.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smiposkk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsixtzud.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlywzrb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsekejn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ywakbpso.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tkseeumq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2osyvrwnw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zoenbomj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tyerakff.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaxzaso.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rksjcphk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wguwtpty.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlvmzsv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pexxekcv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nffqtlay.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnkrrme.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvktbfqo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdxqpnm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kmakjdqf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gownptsv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbcuthc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhudorw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cunsglde.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvijmlkg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqzvltt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2akvluhjq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jnztkldm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2htnnkolp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2abjfefab.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cwicwepl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcjcmox.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jznbsqgk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2noarsaiy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2boiuybjw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxfjtyk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtpwrfr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrcdrok.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2velmluiq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2icmuscyt.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swoopmsi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhklbfq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2baazhqwh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2nydkocwe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tehrppkk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2evcmfmxr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jngmxpfs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kuweojib.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjheiuev.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgmgvbe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwcyjiy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrjiqfi.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjuefww.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2knuogndc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkbdhqb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgelpaq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzhogee.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmpsmfg.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqtjryo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bieeyjcl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yjinyiys.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qhedklrw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfndmut.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkdunvi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rchjrrxy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuwnskp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfymxscr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsputhe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlkknuk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fpamnims.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwdozud.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbyqwdz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdhwtcu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rofepczo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2njrtrnhg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2emguqchj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqybagx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkzdego.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qclfwlyy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xofwjhjw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqksuhv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eplvmbga.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2egpgeybq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxamkxwa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjqwvwu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mohzeheq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqhuqog.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwymyqop.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2njcorzgn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zocxlfee.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2joanvkxo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhnielj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlgztet.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdvtnuw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnampox.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nawdxcqw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2rcngongt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2krofwylr.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjlhvrz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lwksjntv.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoihrpu.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqrnnss.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkgjkyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjfvtvp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvoveds.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgonxuls.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvcoenr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqobnjni.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tevjzlym.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyfsojw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lydykdiz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlvhjfo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfqeswu.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzslrug.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2scjlmtqc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2skhhfjsx.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqardlp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdnckyv.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqimxoj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2atzjgbwi.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdjmbkm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2akrqxgwp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lvilfrli.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmwwhdm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dipplfjp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2eklixqob.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfbvawo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2znkwpoou.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwkuiyk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbouhk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jqoosesf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqrypno.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdllsib.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2diqujnly.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvdyqta.html


<!-- 参考信息 -->