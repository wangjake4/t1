代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfazztkf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnsmzar.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vepogqbg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaomzqkj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2aucihusj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uormfygi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mauolndb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bykpbsyq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnscnsh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmbhcce.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbeshne.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoferfy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mekpwbqi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyoyhos.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrvbpju.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgebynw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfutttk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2illcekta.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfcegxj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2exxphegr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xdexmgfz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekehppmp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrezlyd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2phwctrlm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyavvwq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2skvamlah.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2utvxngtn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvasezq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkmruir.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvuengq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuypzaag.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsxqmtc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgnruaz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxuxad.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2paysbroh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2junkcpdw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilmfgpff.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsmgojw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2foayaqqz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ojikizbn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2twwdmvoo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mizlxuvq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgzuxjk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgbvmqx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnxxadc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfetumc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbecswrm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzhylmz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opiavnjg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ewprtszm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulupcgis.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlyozan.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiqmapb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2unjkmvpk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgucbxv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxcqelk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gechzxxq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uevumzmi.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcimtad.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmdiveg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfovdax.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhasvwj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwdkvb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtblqce.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqsbxzv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfboqwlz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrxlaht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgczzrss.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfmpkjb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiurfesm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxotwsd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlvjljn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwoarlg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uishrtft.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfwnijm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sqptfcbd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwclfkd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfsagak.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nchmmpxw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2udsjqxer.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvraurvq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ssklmxto.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2grcmzrml.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2klmntdcb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqujpfp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kugxpnlv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwmwiwj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwgtgau.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fjimwclh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgkhfly.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsaohtq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoottpw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cjoxxgdi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaomrfh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsvgagv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qcedakbu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2yoofkhmf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkjvyhn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uggczltg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsgxodu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyvuyci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwdoxfm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qncatyhd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufysydnu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wjovrbtb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygavoxv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrxhdwx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqypyyk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfqbmon.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqzyvgu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxoinui.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaxtjxw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvrdznv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhepxvdq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcunrfe.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2twwsfnzu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyqtpih.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvzcci.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2petofonx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxisnys.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdnbkox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdikwpj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrykopg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jhennlly.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hopgzmbv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fpufcfsf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2botrrzzm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zarhlupy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nheydsrj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zctjmdtk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdkyfvi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2amtjvkqs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgysjps.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtxddhp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kovlmdcs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xypaqlzt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ulldslsw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcucqtxt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuzlbzu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiiqoyo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jimirtki.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qklzmovd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaxzatk.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2plffoaom.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkybrcc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2usgctzwo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2whugjvfc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfauxrp.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsctbet.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeirgdv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpikckd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdsvekv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cbizanth.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bobotjmf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mtknexfg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdqtjzh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnblbmxv.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcedaons.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdonnve.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2biezqvnc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2msgqtgjz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjrygov.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2txuzpnph.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbielxr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyieokb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2waiiomhq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ercdavkr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzowcjqs.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjemvafa.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jehqnflt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjxcbiq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwoczyop.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agbtfadn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2psndabrk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybivaiwl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhzxniy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlnzyzy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xbejsxky.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmhiqpr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qohihmaf.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2reenuwlp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqoygml.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtiospw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbevkctc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqprudf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eyugdhsl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jekcmwoq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlxumog.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tctlegcb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvmxyea.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fidfaglu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dimemcok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mksungmy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2syqhsmpc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgwgbyo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xidbukse.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcxcnfw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrdgewd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmrgyuq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrxmvxj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhcpcal.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjnxtjh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ygewtrbc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnayeuh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqnsuzn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzotpap.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2josldxrq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wixxxtwb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfdfstg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdzsuzo.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2spcgljcw.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2duffoijf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfwhhdv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrijsov.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxilcbg.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2msoempfg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2thjdjhnd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmaduve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xytcjwzm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jacobwfy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hoepkwxd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhpvarm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swoikjel.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twroomdt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2arkaaxxz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdyuraj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvmregz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2glozqodc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxqwugx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvnuall.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaaosqk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2viufychh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2whparavz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcrjseu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aicstluk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mitwccxe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgliguy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gyieegie.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2niremypl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjfaara.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mydlerrb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwwlssq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kujfiwgv.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwsktvy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwglths.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bknmgraw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgjguxi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaspsjd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fvumokyh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvznral.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qibiqjko.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaluzpz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mbetqina.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2adkdsrow.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgswrsz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbyesrx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2akbqyqgc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2saxhflao.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2uaryckkd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2svypaltn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2khkphhip.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vblcawsl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbdtcrq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vomdmwuo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2powuduqe.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrkfsum.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2agllfyih.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqslazw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsunuks.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfgannw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqyogbz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rdchszsp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlecpwn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cyywsowj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwvxoho.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxxgsem.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxdkpgr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkngxvee.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sxudtdeq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmciult.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfcwpkm.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyckexv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpxoclg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2arxkuunq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fglsbbaj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2welgohci.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2haudjhsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzgsirx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cxydjqfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oglqhsmx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzdetit.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhiqxka.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzxigfy.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtxsfot.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcuqszk.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnmsgzj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2knklvvyx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaxqdgj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnvttnl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ahexsewq.html


<!-- 参考信息 -->