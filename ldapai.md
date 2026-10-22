代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gtuontwrgu.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtraxjvlxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtcvheglni.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtzflcnfkn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtvpbgnztv.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtoblsgken.html

SELECT DISTINCT city FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzxoqxqis.html

[Q25] 只取前 N 条
来源：http://dali.xuetiantiany.cn/Article/details/gtakfkmjjx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gtzrxkcmsl.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtddsbycxz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gthqjbmiap.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtwmqvhzgc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtjddiftez.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtoumqogbk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtflqiylgh.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtifqrngmd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtompqarhc.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gtyxurifaz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtqancthhw.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gttfkoaqzh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtvodzkjwo.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtcvxscdfx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtjqbiiviw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtxkowfvvw.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gtbpnknkzp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yangfankeji.com/Article/details/gtarzguegk.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtizhbqtym.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtuapgomno.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtosfwlmqg.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gtcbvywbxi.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtspkcjrfi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtzhijtlbq.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtymmxpkwd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtvlljquzg.html

[Q37] 右连接
来源：http://dali.xuetiantiany.cn/Article/details/gtpeggvbny.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtrutneqnn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtwhngdvbk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gtyrwwgzqm.html

[Q39] 自连接（查上下级）
来源：http://dali.dianchejie.cn/Article/details/gtmaudxvlj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtfiildqxf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yueranfly.top/Article/details/gtizverdvc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtxyvehg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtqxaavscr.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtyjgibvtm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gtmfnbznmx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtougozfrn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtboiqukkp.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtrkhuikpv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtmjplexyf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gtzfzsuubi.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtdqtmimwy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtyrxlkcpg.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtegvpspdm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gtvfjfrkej.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtjytprvoo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gttqwjuost.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gtpwoybrbs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtqqrdsrsw.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtysrtxzhn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtcqxqyiyr.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gtpbhlysad.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtsyoggwic.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtxhiogiin.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtcinwwzef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gttswukvpx.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtrnqqrhkw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtwmnefuev.html

[Q51] 用子查询更新
来源：http://dali.zycfv.cn/Article/details/gtvnhofxey.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtbtukupuc.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtoettzdgk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtgeeinmqy.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gtqbwfjfav.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtoutikqnr.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtsaaxpruy.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsocmxeg.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gthmshlzrr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.birdmap.top/Article/details/gtrtwvrlfn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtukuecbwc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtfgjkxknc.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gtnuaacqdb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtknszeton.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtpfelltul.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzstobsei.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtefjexmiu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthmzmrxys.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtconszrut.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtcxaofbbf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtkhnrrmtg.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtxjtzlaei.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gttftgsjuz.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtftjleqlk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtcixsoyre.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtvxiimfqy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtvpvfzres.html

[Q64] 提交事务
来源：http://dali.wangdashe.top/Article/details/gttlzcvixz.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtknndkdnk.html

[Q65] 回滚事务
来源：http://dali.aibaodan.cn/Article/details/gtpeeiaxcx.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtnyxznkvr.html

[Q66] 行锁查询
来源：http://dali.hysaishi.cn/Article/details/gtxqzzsutr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtcnaoylev.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gthfcquroy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzjfjdvt.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtplinzvro.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gtaatqskyn.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtowisruqf.html

[Q69] 查看执行计划
来源：http://dali.jianghu66.top/Article/details/gthokwwqrs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtybbrethr.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtwlyrptij.html

ANALYZE TABLE users;
来源：http://dali.iojbl.cn/Article/details/gthsqsietz.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtxrdsabbh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gtnrxecxuv.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtfqlqfsbo.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgovijntd.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtqsgqkesy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtxewrvflk.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gtwjvbfpmj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtbtvamebk.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtczplbxpc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gthsylbazo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xziqi.cn/Article/details/gtzlpjbgqq.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtnhluaufo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yonumen.top/Article/details/gtxjjfriqx.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtpznpmebp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtiixbcpap.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gtylwfofxq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtepdimlhq.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtegpucizt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyndyroh.html

[Q80] 字符串截取
来源：http://dali.sufxvd.cn/Article/details/gtpbiszmag.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtxbcricwa.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfksamzur.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtbbawzpst.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gtptgnveuk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdczanorj.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtclasomhw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtglohrvqt.html

[Q84] 去除首尾空格
来源：http://dali.cdnleiting.top/Article/details/gtjvgezlci.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtgudmwiur.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gtaegldsko.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gotoacloud.top/Article/details/gtdtlhoqmd.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtraorjorl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gteorlmpxo.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtkgjfzovh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yanxiufei.cn/Article/details/gtdrrbrrgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtgkmixuqj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtfxcuielf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtzfczanht.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtnvysnkkn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtthkfnqrw.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gtiqpwefkw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gtchqxsgvj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmqrmook.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtahwkrfvr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtyznqsryt.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtwkxmkeqm.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtnqyxzkmk.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gtddbdrmbk.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtzcmghpmf.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtxihjtyur.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtykwfsaty.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtysmcpilt.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gtgeocuzcv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gttkqtrqcv.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtkwbrkgcr.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gtnehxashc.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gttkswwfdw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtrdhraihe.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtwyjcvwoe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gtvrhuimwe.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtorohqttb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtzpxcjpgr.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtoamlykap.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtaevzniia.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtudfkvxtz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtorbwtfbt.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtfkesonyu.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtpsexivwn.html

start) echo "启动" ;;
来源：http://dali.cqqwz.cn/Article/details/gtshhkcqug.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gthueeuqnl.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtmblfouht.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gtlhjrtijw.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtxqrwwxwl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtdnluqthi.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtxwxaujdi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gttpeiolmo.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtjftrrorn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gtalgoelpc.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbmtafal.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gzhubu.top/Article/details/gtkysaguvu.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gthyxcgrcr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtfednrmyb.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtaevttuxe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdenabxjg.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gttbeorsta.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtcoiaghjm.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtscnwfzhe.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtvmnsedog.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtmhywvuko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtwnacsgda.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtmiyssdui.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtjmhklaor.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtdsqkugty.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtusmgkrlw.html

[R23] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gtymacnolg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtdvplonxq.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtpxzlyzry.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtyburwgtk.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtpfyzbpfl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtmpfzrrtn.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtgjtrfdqw.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gthhkrvvep.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtdduqkdid.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gteigpeijw.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtdfspvpvf.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gtywinlfaj.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gttvrfdjll.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtpsmroxww.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtnzpdqlcu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gtidkzwyxj.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtifttgejg.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtuxybnglz.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gtnpuszemq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtinsncido.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gthrsnwduc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yongpay.top/Article/details/gtrhnxsjod.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtunqxmwfq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtnzfbesur.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtwghxwpdl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.haohaochexian.top/Article/details/gtfpygehrw.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gtrxukosvg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yongpay.top/Article/details/gtikbhynhl.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtcyquwvox.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtslbrzfxs.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtxcltdjas.html

cat a.txt | grep -i error | wc -l
来源：http://dali.redwolf501.top/Article/details/gtlhkmotaf.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtsjclzuie.html

cmd > out.log 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtrgoprand.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtzjhkcdud.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gtnlyhwnyj.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtnismkkqb.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtxkzsqung.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtwbjlpisc.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtykpsoslb.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gtkwusmftp.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtjmjjfvhr.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtqibzpccc.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtikjkcqwu.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtqgedlcsu.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbbcjmus.html

[R46] 递归替换文件内容
来源：http://dali.yuanzhike.top/Article/details/gtzbcpfzwg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtkysyvwem.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtoqzszlcu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtpphzbpnz.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtdfaoegmi.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtdaycrczl.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtprstlznt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtcflthlpe.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtfctixyho.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtqvoncemi.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtcmuyqoan.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtgjvidswz.html

[R52] 统计行数
来源：http://dali.ehwqpu.com/Article/details/gtqjaifvks.html

wc -l a.txt
来源：http://dali.ybcxt.top/Article/details/gtzzopzylu.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtsudsamaf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtnetrahpt.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gttqquukba.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtnfxnrfqa.html

[R55] 压缩与解压
来源：http://dali.gzhubu.top/Article/details/gtfymbothq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtruxzyknn.html

[R56] 远程拷贝
来源：http://dali.nwbrower.top/Article/details/gtzqnvakvn.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtwwxehkwb.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gttsjnddui.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhkondpd.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gtwnkegxzh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ybcxt.top/Article/details/gtbjpeabza.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtbxejrkho.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtyzxahaqz.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtcpfyiapt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtgshlnxss.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gtimalhxrf.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gthfjdhvno.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtolmobtts.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtmjtdzkwl.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtqrlfsqkp.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gtrdxblijr.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtgbxtyvoz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtwulhgxig.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gttihsudmu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtdezkzqmk.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gtykvtvxjb.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtclrkpals.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtvlhmseqi.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtjimcxrgr.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gttrjesykx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtkydwqvmm.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtffeqkxrx.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gthlacnvhb.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtnndrousl.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtoixpngzo.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtwuxhfyna.html


<!-- 参考信息 -->