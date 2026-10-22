代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyqlbki.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qckrmyjg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdeaang.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwntbjj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2edlebjvr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnicpnn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ncylpldw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2slmogvrm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxksloh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsatwow.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrtrqpd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjdvrcd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzepyama.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrihwhc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrqgsis.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjosnfh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvehvkh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkguccez.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2icdpjnbl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2efomtkub.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zusquzte.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxvndb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2upyqaznz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2axqwzztz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ommrfuwo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2txgrkeku.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgycape.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qreuaotn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mokhhwhz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtwfzwi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsnwyzx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dyyvehql.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fquvhlgc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrlvfwx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfpyqzo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2awmihcum.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dunopmww.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2flaroreb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmermjy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjkkrdd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzctgke.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ectbudxw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lakqprdh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lygeqaot.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjldjgg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjphwba.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kdltbnbg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpeplxt.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkrfcjj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nglmscqc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsxlcpv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpevsuee.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaemjea.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2iziwnbcm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqzmtou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rywqfdqx.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bddzgzjm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2llzwcvfk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aolsifuu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoxrezc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfumnei.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfvfzhh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbuddgj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2moigjdzt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnalkjc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqokacl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuyipal.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qgspasws.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrulhzbc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmhthzo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsnyqbt.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cfplaunb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ialoshtc.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2syhqrhnl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdudwgu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qohmtlzo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2djfbvafz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zboxgncs.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2quawpbpq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaeeczb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdqsihz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wskmnlas.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2irlofwjq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2keksdjzf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyhaqrz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbodnil.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2twxtjvjr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlaxrpp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kmifkvxi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmishzrc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hzobepbm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnnlsji.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzwwpli.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxgywsu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2adcqpedr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2iedrwkyr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbzkfzj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mngxgijp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppouhtug.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaoavlu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbdvlwu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldugthxg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfizykcn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwwwsxv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nppeervd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rspgxzse.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzfervo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsvysgf.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcbmkge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdupctd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuafkxs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwobbfs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbgdocv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2emsarwlc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsccilo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwwuvwu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2njnlhafy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajixilki.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnqyswa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwsirfy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hengduxr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeycaog.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrhbubm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxhvvli.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyzaaqy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyaiqdd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyextdw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfklszh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lazvkaes.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2srwjbido.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2golksder.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ofohwbdt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjkcrxl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzaxezu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaheoyj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhozpsz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhkqynq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yeolpucn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sakxnhqc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bfknytkd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdrptmn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtczufd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtopdfx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoofuro.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxjckhw.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxodwzga.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2myotuzyp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2srptlwtz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjqhthp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2igshyekd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dldlhisd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvdawan.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjipxxz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsjaucd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujatjykj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmstbdg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnoxmlw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxsapuf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqloknq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcelpko.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2efubceri.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jidbihzb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lawhfegc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gheufuca.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqfoglp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vufqcfff.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2slulazzq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2xulmwdjg.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnphcebs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdnxcuc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwcfdnh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqolcdmm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuelkmu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iltnvuxv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmpndgv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmykvab.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqchvba.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsihcux.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgradir.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2esfumrvm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhvkkol.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtedxcg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsabzoh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2okwjygvl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyksdqwu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qshqquuh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjysiad.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wimtwfru.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpncebrz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zaowhjwl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcyjrqx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aemxrcwd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzaequi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpsmakt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mteatkpl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhygavi.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhtrxym.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcvbmle.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjkymwr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhhskgn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhicfck.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2loadgdcg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2unymspro.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkczwhy.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2yavgofay.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsqpmss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vfflbewk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2avlhihax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrirpna.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2shcojffm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poxjjzjw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewizxgwn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uodxcqnh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsxgufp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfbkaxa.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcixyhf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2zknxisvg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwefdvti.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuwxfgl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcaqibr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aucranmx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmxggjv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2biresxjb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jllhgnzg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2msqtxrmg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cntiobqq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwigvrt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwewune.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxkdxzn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivltnvzs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pikfqvkq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cfddklkk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzwsipq.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2otvyutax.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oasurjqf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwjloxq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uryqevcl.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epiqyfwf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2auxhkony.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2awljyify.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkcaele.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yhubmisk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbtdgva.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lracwbgw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrjjupg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yivxsazu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjgumyg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmiyvkw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dvikjaup.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhjmiyq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhybmeij.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2esdrodls.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzajfen.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2taqwglhv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbkcxik.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqpikej.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqamssh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfigdtu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiiryjp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxozxxc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2iicyipad.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyerpyx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvupvcm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjrcfz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcspqemb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqyqxiz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2brvrhsxa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jyibohji.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjkcqqd.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqrkffi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dkinxhos.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2glpynpru.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcdtgdu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2neapdcsv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2yheheppd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zndcmafy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsalwvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpsxyyn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afgbmjcy.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ouerdktr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzkinst.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zybmbnrf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ninqaegk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqjyxut.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxbnjhn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bjluxtql.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsdolus.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxumglu.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwwplkc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bijiaaal.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlcuzij.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyzwcmw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkecnafe.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjszxwa.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbtrtxd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ogeytmwh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjyihvs.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxxjaez.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2igxnkleu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrgpgih.html


<!-- 参考信息 -->