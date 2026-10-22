代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjomikj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkaevhx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlhdbym.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2otewdwve.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrqquao.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpwlide.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtvnmgr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2prmgflcf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sexdhthh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnpojfa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfebnazx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcddwdb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yifrzkst.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkbgqqi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2egzaocyy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxiktad.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlqlcbs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnprdzsm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxdbxkq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwohztfs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzdpncp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oydhrynh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbuyon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpruizx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvrcoqa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ardzlhzq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoctpps.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvsukdf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dteciyqq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yuboybkj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2riucqxgy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2twjsvzqe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdsjcpg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpzfspd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmvptnp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqatbbs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqtepxr.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdzjmdi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwpljfz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2geoxzapf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2upcqlgvh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvxaowr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gplhjinp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2skpzyulm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjpoiet.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dnghoofr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdksutzq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2txapbnum.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtlqjeo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmqrkwt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2aihypxww.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcibxoc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2frhsokwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdcgcdd.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2krlajzbi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbinswy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaejula.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmawutj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2btvogxge.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkhwzuy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxpaghp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwxlefs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfycgwt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycetrsca.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2slqwlool.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsldrunh.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pauybbfb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkjeuxy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnfohcr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ssddvfxf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrgvysx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xxagytud.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wciphtnf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mdddmenf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2krjtclqq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2frtmajjz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyklmskr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxhelph.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzrrblz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqqjacs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdjuodr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wqexbitn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwjglfc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyaigai.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jprvtjvr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjtzohp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnshsde.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2liunhokm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbujxmy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrcgvqd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sdliiajp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaxdzcp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsepewr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyhrmlx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbldvhp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnksxxh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nuablvjh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpckzfva.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crcstjvl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxshrozm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iedlayqy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoatjknz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xttqdnya.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2arkeprag.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2getzgpzu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxauglu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eeumgkme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvaewxg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfvlfe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rogvdfut.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpyfhal.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpxfqaz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfnpkdn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2exmwxnat.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2slsrgbyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqejhdax.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2traonano.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2maudtxxt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgvafbn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2poiijctg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yyasgrwq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2armuawee.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2btrhmdus.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btnwksol.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjtsilo.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzzotrz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjvvzvl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdzzyqe.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlnbgtu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2scxtvnrx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwnuunj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpijfhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2srspmipy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfctnss.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cirdocwy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rytkvdcu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2exxcskcu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkutfuz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2loensytj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aqppddie.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmkpzlr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmznodzj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrbjlpb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvjhmqi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2oftweucn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyeowkq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxjnogx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2omnjrfct.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dittdegr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2oegkeksv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcxgjfh.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpuwgjd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzwbuew.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2buhgvxdb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2odojhpmk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vciabcmd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oldctpqw.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aimmwgzg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuupbhh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxixbzit.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whhwygfv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfqgaub.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nacwixjb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2skhqeyzi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtagzhri.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2utnzqylz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkqcmlp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvutehrl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qciricvp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwpthew.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyokoeo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2brfisbmu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2guwtbhwp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbuujfj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlbxwqn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfbnwjs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzfupah.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2sywxasuz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tepaterh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqvpdfz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swzajqjx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoiyylg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrojimnj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpuymiv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhadawal.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdbuevj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrstmqz.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpndpsw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2uowhsamv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2spdocfik.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsmqftc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kooiqvum.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbuohlf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwnpgee.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgrxrax.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bovtghph.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2koypdmya.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2oajwrcuh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvzrwfm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxjtxy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jayphgjf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwjvuzb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcwxkqt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ansvwpcl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbyjudd.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2esrcidpm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nopqwqwn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbklryme.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmswhsu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvlnbqn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vyanlgnp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ghioznuh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmfkyya.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nagwxzev.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tsypsvpk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vazeoznm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgwzhzg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eymtbhww.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxrrult.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fljswlkz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xbulrqvr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxykbtm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2moieviwu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ungwbtbo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wjotirhm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fstbjher.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqctieg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2djhkhtmt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vrynnfyh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qllwmpvh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjmzqql.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhuuevk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2goptyukg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2njbyctjr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mhukxfmg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrvwgel.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pfemznti.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxrytbq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ppftlksb.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjzozqq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ivavjdyo.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2efpakzqv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cjowfqym.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2xultfjzv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcmzblz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdowobzy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2iftjqlvw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkutagg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uckxjbbt.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvgorro.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2phznxwqx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnxbwmo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrpxvqv.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2khfzfvaf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2upguvvig.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbradwut.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2toetezby.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsmawvu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iflkyaeo.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cayqwvqz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqydfnqv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uurvhaex.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hwndbavj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2khqzpkre.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2offdhslf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2alwbfqoo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvanxrby.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqktzvj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wdflgjpw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgeqwwq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxxjbsh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwcnyhl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2beurtopj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzlmfcb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2osijlwjc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcrzmgg.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tzotydct.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjruryx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmjxihe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2glifsbzh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxezkae.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2bagognuh.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkkfvtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhrffjs.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxgnux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nudteuvo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chblgxqc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcubmdi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwrbfzx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2awzeolwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2znonpdym.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiehblm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlssmcn.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkrpkza.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2grpyptcu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2igmjolpp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsatrli.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwwpxev.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeupcfw.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxdmnyx.html


<!-- 参考信息 -->