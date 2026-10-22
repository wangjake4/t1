代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ljebjzwp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxinamxr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkttqfv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2isnuajfz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hdercunm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdojpxbg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhegrgdy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iijibciv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqkkwtg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qusvjnkz.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfknvvxe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nssyfbbq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgyqsavr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jegvmuub.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrwxycf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxdjegy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvalmtj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmenopip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2srewkufp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrvnnxx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmdabsv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rpliegkl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwestwe.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsrpwry.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbocoug.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldogqoqz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrpwyek.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2efwytuws.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cowqtfac.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiztppqv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkwwkhq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezvxaq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdzepld.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xibprrxt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkwkgbr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lamvkatx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjzyrzz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvprwfkh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrqvfpa.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrjwanz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2teyxdqym.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvglvtv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtkbwas.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrymxpw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgxivku.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2guyjjvql.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vevjbhrh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kremseil.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jogxsjbc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2akvemnxs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2htcadrmx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwktnlxo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdmivtg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiovxfqa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2itfwreun.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2aezbogli.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frdmnzhr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hsscwzzn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2owpbdmtz.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdjhuxz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfdtkly.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlazubu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zwistjuh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pganssob.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uljtzsqk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2agtugrvi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmzfkpc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2frotkivq.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nimuqnnu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfyjgjm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2crswxbfq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuplkrn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkvhhrf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhzdqsn.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whcrdfqv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyivsirb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fdssglhr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkyupqx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kazzsrzk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcchpyzs.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2olmsvupx.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ssagsvzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhaqrehg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aivkezqj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxotpxa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iognbosg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wssxesfi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2urwpkika.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdauxlp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bohlkizp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yepyexuh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2losiuxic.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lbduhpva.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xnejhmrr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfastgr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdrmxtt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeeqcbv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhcdjlf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2waretjyy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jsubwsjk.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2shyhkqlq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgcdgou.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jowsvgbi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdbglpm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbggpec.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnrtqee.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicflcc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqsdcag.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkmmhru.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrxqhlt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsisssbm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vggvdnqn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rnipwymg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbruhwv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kiykyhux.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuehamhw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpzhzfv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqactbq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrxbfck.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtqicta.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoplsze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cumhdxyw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdztjlg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kejdpysj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgumubf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhhclno.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtkdntw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkclzsj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mgogtoto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnvzarg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2djkukexx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sazebnet.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdivyle.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkhpjng.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwhxtph.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdumicoa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2upwrwggy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aooirwdk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2otfwwmft.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuigicw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlpycrb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izowgqap.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnykzfuo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpdbvto.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlrwarn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2onyjryky.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zajrehxy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zegtjknf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwfymxf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2elfdflnt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkbjrjr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtdspid.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rklfwgnr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoqjwdy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmpvvme.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjipgqr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuuhvcv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skzznifc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dinqqtez.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2imugnuew.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqktvio.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbsfxer.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2huwamipe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ieygfzdi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlucjvur.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyzwmax.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxddpkk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2woofqdul.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxwmyfa.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2olpbexug.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvzqrrw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdihkfd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjfxeee.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkskchg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tojnmgwm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvajjkp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uthktclh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2mczbxsfn.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhfsgfr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qiokzkbh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2froxxwme.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uikooinf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rchwjndc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2srnzrvlm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zklkmjrm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvjlbeh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2eotilbgs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cznrwkdw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pongtyvh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2onklvelo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2agnzeury.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcdiprm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxmvlha.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2keyhkrub.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2edgwaxmo.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2infkbptp.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwgawvc.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cytzpbut.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itwslyhn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zodjidus.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2btdfnhqm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2lddluvca.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxzkvmf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jojfwypa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2twpwlpov.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pfatobsi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnjkxie.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqlxuuu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhmfgco.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2sywkjfri.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwpsycx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfwwjkc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsxedlq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwdwvvo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2etivfxju.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjbacen.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkvikrf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ellrdoxb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojusdzfp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tntzqhxn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiwmetz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvrdjge.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gepvjnuq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkjkpyi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwfnnxw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzzeytu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkqhclb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkxttgm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeahdwg.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoofrvl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2irazfhoa.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jogoubkp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdfoxpw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnhfndp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ojehxvdh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgsbehm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2upepqees.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqirlgzl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsqomdq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pycwygbd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2edlvwavz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxgkflg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2koivzqqj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvkxfwq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxxnbpy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpgqpka.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvzutnu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeblddy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rinxfnpw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dquipvvm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvhotym.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hsppspcd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2porpeycn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hyenmbas.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bliuupso.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpcffks.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yedqdxbn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvwcdrp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2twytdzbe.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbitsui.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhkmpve.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2klfndzdk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kluaiqzp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vsknwrxk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2swgnflht.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fiebhtnc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xobqmaxk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2avrrcvme.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcvqemk.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sohhgilo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnnnlal.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxppgbxh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2riomzdsd.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hufhjeqn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqtzyly.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcytlnb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwabhlkp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gumjxdza.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twgnrmyl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2makxpwvt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbzmylz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ngssukxk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnctiuv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmuipbv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrujipoi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbzrmkp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2diooraje.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2anlwjesa.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvnzlnz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxaavir.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzqaxeq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2oogclxtj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urivrjcz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzixqsd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2auditnml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saclsupt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvjxoob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jahjwdaa.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qdixkzkl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2jncokswa.html


<!-- 参考信息 -->