代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kibebgfo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2okgasfqx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqznqnvv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeolrzw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqcleaj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhltmwtj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hszbeaey.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yedgdmbc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tkprirzl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cihblwna.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuonzni.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lugikegb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cvygekwc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbxguhv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2upwipxmk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2azliovwe.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmsusdz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2sttavfna.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbonrdx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpppkkkh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sebgswlk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwaoifr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lgczbfgx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvumfro.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yeifexis.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrbjwpq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkbqgf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cawloqad.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzziuem.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zykjfoqz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2arjsrebn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrokjpe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsyrern.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgitapp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqaqzua.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2waotptok.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhgenai.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2omdezmfo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvioqzy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2annogzym.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yycgzjeo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2djdjdgac.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tznjcfwb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkcdnxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ychmryfk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2moovvqun.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsbvfjv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjexllwl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcmlcui.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrkpami.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2usxyxvqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgfpwvq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbewsop.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmocqbb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrypmlw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2foebmzep.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2makzogjo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2frppkdea.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uohljsvh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnukqnbn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqgzkgz.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsifnzet.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tscckqvf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvuckcr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeisydy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzfkhgk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgvjdsy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2petzowzb.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2glbjvqdr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ypepwvae.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhhemfp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lseomfox.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jojpcafh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqzccix.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2djwvkhmc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzkrjcd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxlpjdo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qhimwssk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzufqtts.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfotlfo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvqngak.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdmlkab.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfljpwpy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnrpqgh.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmrjfvl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqlketz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rmachkry.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2iamgluro.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcebzde.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtuxgtf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzaxzez.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2prdbftbo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdzzqqk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkvqero.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2utclgvlm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uazvuavj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgtylfy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efkfhiur.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxdpnno.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krhpkmyw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjiddrc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwinyvof.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpfczct.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtwkoqj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yixkgowe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkoxhvp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwjgsjr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfydmne.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2shomjuoj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2pthuubwi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shlykwnl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xcexbzlg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ephlsgws.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2esinhqbn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbchemhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyvzjqs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mawvjjqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeuwrva.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xezzklev.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2beuhvmkp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qvajrplu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlsvodw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjoquag.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmboivm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfvcnvu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfnhqoe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2zovjlufq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2asuqywil.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjevnjfp.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhjziff.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sexxzwpa.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frdwpzqn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bibtugzk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kffometm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpjqodi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbbieki.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgcsnup.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjnhurl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdhmonh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwzgoxq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dtereybg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkocpzf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsalqkj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aroxmglc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqhztps.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmiacvu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtrneto.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zupvjrri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuwocza.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2otoguska.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjxplav.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iobhfbxi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfydjai.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rreyzqdn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyphjao.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2olneottu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhonhrdb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jmigpsxn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjoqzbb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqxkoup.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlawzxmp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2phwstims.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqssahh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xayejihh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjhqlmr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wibwpawr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iodeyata.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvajdhk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtgparm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xigwntjg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yycsmbkj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbtuabj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2csfeaosg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwhvylv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaecjlb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ociqbzkb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2orlhzcyi.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbyyhqi.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2eywzmdgi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhktles.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kyromidm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkxwtuz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnlfrbe.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbujbfr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eawpzcal.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2okkrusct.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgixxrgl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qusspmak.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zapgaimh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmwqxur.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ridohsoa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yabeoogn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaowext.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uujfdpbe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2msfmkmcd.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjxtqux.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iziurhgb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zfojxbyi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rxatnbzo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiymcam.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjtlakt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fjljzhcw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mijcwjnm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbyphrg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyudpiv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvjazye.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2toinhqvl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2survgkrr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2siuhbtvh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hofxyibx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjameqz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtswnhw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuityfs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2umbkntri.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2qitnfyqo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrsamau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whmbrees.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtfpkje.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dziwrlvu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgeqoux.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ikesymey.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2migalmgg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsziebbd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fuebdrbn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaukpbi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsqqoli.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatpwhm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkdmcsc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoaugza.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbncaug.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrvzjzs.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jyytqqqd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xxusblsv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhkerhc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqtobvz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qiudqkwm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mmibblgj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoarzbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2pknawrmn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2buserqpa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kagotsxa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2afofrzxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2whicximr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2asbuiyew.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpwtdrn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbaxzhq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2btwzwtia.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbsmulj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxfyzcy.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzmrkhb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnclszpm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hvugvlig.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2sywnjwqr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzejrhpr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2haiefzkg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuceekj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2irvsbiiu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxuiixk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfaqadi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrkfvra.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wduyhrea.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2aukmnkrh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2klmikrcj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvepfdx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2isslmzry.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hysnhslo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiuwjwm.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrowxwu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoysvbs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuiupmb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2psaddfpf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekllxrog.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lggnureq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjmpzme.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2eayilkdb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2oegtevxu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tytcxmjz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2migaqwqg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2terhewww.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnitgyb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2leyuhntp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjfyafj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuqvayw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amahurfe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2aeylzzdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sistypwv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wjedztxz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dcubasdi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrylunm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ppntajcp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdetxsm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnvpylk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaasftw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2azmkeaqk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxdpnhn.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jeykjpxa.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfcjiup.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ngswvrgl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kiudbjdh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxsppvu.html


<!-- 参考信息 -->