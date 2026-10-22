代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tetqyuwz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcflmfs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkeoayc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpfaeuu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2miqmbvnh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwtfkum.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pispqdyg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2smypqyir.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eesbpwpt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfsegkr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hgviizlf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qkypcwdf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nntszrda.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2eiktsprp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrqufcg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjtdoqd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mgymoglx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqdrndd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yinxfdms.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2skqillki.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyewoqui.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgpsvek.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2whodvsfo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpfzybt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cticzvkk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaolpci.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgjpjfi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrqodfb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnezhlpq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxqhsnh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxcjyow.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxbwkpt.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jnalnrlv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2btvqerab.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lzguzjcw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bndihzhq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcrclar.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2yywahqgm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vngeuxxd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfixfhvl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqrwfcb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jajjavjl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2btyilvkz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbrqrzs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gbiqmols.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpjpxuu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wubxsghj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2blniqvyh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hicgfeva.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2upevfdgq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyzkxmo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrzqlfw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acsufnqt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gegnjooq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yjecadof.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2riourdeb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amojchoa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sixyhecj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsvoolp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjteiqp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2emicvvbt.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2picqnihs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbwgmze.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2buyhuikg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtmkodi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bafanjwe.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvrbbto.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iquphjfp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaqazfb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxnzmx.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2azzdgksa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2buvxlibz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfhcnmm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclcxrai.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2geutpmye.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pahkipqn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xckogcpo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2npqozhyv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpdldjp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spyxbdhz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bucbkjog.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udffdmxc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2poagekrv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2texobqcn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkrfszh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zdandmwu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ityfbavc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwpcbnn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2efjjscga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjfzmyb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svrbjwwt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgdxqxl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qahuuoao.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2muswzvxn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkppbcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cilwqwed.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvacqrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcpmbib.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ilviptqf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcbdics.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xvowqevy.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsiyeme.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeapton.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2terxupfa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kcotknfy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzygtaif.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfevzvbf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2irpvzfgx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdbidje.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmedlcq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwznzqr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfzsrlo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ourablqs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2adixfpzw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwvirbd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmhsank.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pvidpvym.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nttgzyyf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bheprvhw.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjinxlt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bizjyrju.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2unfpkszz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2byhgtmgt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uohogmlh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbtbtlv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqovxhkf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpwmsrc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zboxpoyf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lohxqddh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpwiqry.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tvneqfos.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhgzojv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ppymtvey.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfujdui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdtzmmo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vknwnoqx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzxgmoq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2knzroioo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snmiefat.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qaihqwyo.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlpfbhp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfokvgf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrseyja.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2booaegkp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvgykiu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvkwxob.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfofsduh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zchpgoth.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbfzvje.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vswisfst.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxgzxgf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2thsekeez.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqajgtir.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcmbltl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzaueqg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmmzlnx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtdmgne.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2obozyjly.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjjpoic.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzqzpcf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2doltweik.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfosyoh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2twjkwaxr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otawbtbg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofapesar.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrnoxxw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shmgshlv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxcnepl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlcrsbp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dyidbnyj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxphmwx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sosoexdj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2cncpndcj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lhahnszi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zouvdeol.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjumsts.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyepavvv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2niabwscy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuhfdoh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwtphws.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkfxfxx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzdyzmy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2usoykldi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqidbur.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2logdzabr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhiytyx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwuuvvj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzwonax.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2brrervlu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyriavn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqnjdin.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtjkjvj.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fahuohfz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fukdfdru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eztofifo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2txyduaek.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkydltt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxxsdtj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fozwesfm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hutzyvtw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hglqdnlu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2imlzsknk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rukxwjjo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgspygx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhfztmu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dughqvmo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhvyjwm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xqowbfsq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwqgyeh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wboxvyxb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmegsfm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mginlxyu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2igmtfdad.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgcjfwu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2npatmddz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jluzeiji.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2eidccwyw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsodfohq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgynemo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rniqsuua.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzokdtx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sliaqmlf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwoctsx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oldpjqqy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiayukx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwmvwdv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyoirkk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bamtkskq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdqjiup.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnasuka.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnismsm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhptzyv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcgmutr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkaugkf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxsgrih.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzfzhnk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbsujeo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2djmtuwir.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ciriwioz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2efjnnias.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2grehjrtz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpxavrq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyfsvmq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwogzvp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vggcwozz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxmfwoq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tugddtmd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpygzlx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2glikplhy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2akbvlkhx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucizoavn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vchwzmnr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaixhjpj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ersgnsei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyyicuk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2camvunsk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kzphlliw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjnrfqc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwliryu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zfupggfa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qepxwsza.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rrftrzby.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcdpsbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxzlpmd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rimgbwls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyazdgvv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aijezarw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kralcunn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrysbnl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kccvfpgb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcckqyx.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgfhrid.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2omyvzgow.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwtjqbx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkmjuwv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwlnueo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlnbhvz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2trccsguy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hnitiull.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfhldvc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmjjrqg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2yotazmtt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2frddtlza.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fpklivbg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2itmdofqk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyrisna.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjzdvgr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2werrqrht.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysseddst.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjapomkf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2immaucif.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbwyljv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wegqsgzw.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvndvcx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2undokcnw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwcxuju.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqsqwdh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzplsdn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpviftx.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gpflsret.html


<!-- 参考信息 -->