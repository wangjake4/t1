代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrkqflcw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtcxjsibxt.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtzpsyuryz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtmpxjmkfu.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtijsyndqx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gtkgagzxxq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtplumrmun.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtyoziymht.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtkobezzff.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtlgeidaqx.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtlchhonhc.html

[Q17] 条件查询
来源：http://dali.mhx1999.top/Article/details/gttficxjnb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtzwmtvkqw.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtcmfofcfu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gtqiahyvri.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtpdbopzov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtcgyorkph.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtvbnbmfbh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtkopwiwyy.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtlaazctfm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtzobtrdcq.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gtkzbaonlf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtjbexwubl.html

[Q23] 分页
来源：http://dali.ydzc1.top/Article/details/gtfpnzmvft.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gtvpgjgspy.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpzkfpyo.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtbmpksanh.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gtwlqisvwd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtserimdop.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtthugtsia.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtnceflvpr.html

[Q27] 条件计数
来源：http://dali.zhixingplan.top/Article/details/gtpodfrmja.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtbndkptwj.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtyiriklwi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtbwdpyxks.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtfeoczseu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtnnfcnumi.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtkvankfag.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtqsndenbp.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghlfegvz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.birdmap.top/Article/details/gtmmmvclit.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gthrgeatub.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtfqfbmqhj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gthziydpeg.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtbkvpbgpt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzlkthsb.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtmmioveva.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtsbcltshe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtwazlgekq.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtrfjlmqsx.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtogszbwnj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtnnktbszn.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtqnuqehgc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzmgmaqb.html

[Q37] 右连接
来源：http://dali.nanxinkj.top/Article/details/gtkfrhqmic.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtunpnjbyh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtudpzqmga.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gtbfrelgjb.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtqgsrhkde.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtmwdsofik.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnikvadwu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtpmnqbdln.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtsoltuvmh.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtyfvkkjwb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtzkbahory.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtkigtmbce.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtipaajhot.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtaullaqkl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwddbmpb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gthttvqndc.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtxjnvuktz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhongyouzk.top/Article/details/gtmzdkeizc.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyszfssg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtkxpdizcj.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtrosjvphe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gtovkrzown.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtxlyumpjy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtbgtqstmt.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtzpkefwjt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtttcqrxzc.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtbmdnqjiq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdijeacft.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtkzsiddph.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtjmcqymji.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtvbbaouwt.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtsoshlwhn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtdhikbbyo.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtsvoystsl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtcpnngawz.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtafghhsrb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtwdewlwvp.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtdotnzhwj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtpizimamx.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtqedfuonw.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtitltyrjq.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtqjnxhyni.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtevgwqtsl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtdvwdpjsm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gthrfzzbji.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtzmdtvabu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtgwivsrva.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gtpxsgebbl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gttfucvhvs.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtlaghbles.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtntfzqfoe.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gtgevmrxmq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gtduylkgag.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvqplgmt.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtixrclxlj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtoswiyzzs.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzamxppp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtzblwkxub.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gthpzehnoy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoibnbems.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtzxtvcfih.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtinflvnfp.html

[Q65] 回滚事务
来源：http://dali.redwolf501.top/Article/details/gtssetggny.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gttozuuakj.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtfkztsfme.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtthmlvxdy.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtdlqybdjz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtlhrppyiq.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzqfbqul.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gthcrjkbgu.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gthykqdvwj.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtwyllklen.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtxqkzyiyh.html

[Q70] 更新统计信息
来源：http://dali.haohaochexian.top/Article/details/gtmmzhqbof.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gtoepecigc.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtkjoercgk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrideyzws.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtfqxatnou.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gthvchcsst.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtnqbccmlu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtqytmxcnn.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gtwouhlphn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtemzbryev.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtdrkefogj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlmmpcymd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtinthkqou.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtqiyngtrz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daxiang520.top/Article/details/gtjukaofef.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtcplqqoqt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gtscdxblxi.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtwenjzxku.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtgmokmjiw.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtugbkkzgk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtxzrhtiag.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtchxsdvwq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtkewgachk.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtyksdomrj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.wangdashe.top/Article/details/gtkoeoyddw.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtiglmtbco.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtiwatprap.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtavaqippe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnpqhywi.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtzsikvohf.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtlvbfbwzp.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gttupecftz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtljexgmwr.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gtcmpybpiu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszerivmu.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtdmtydmph.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.haohaochexian.top/Article/details/gtfrgoyeqa.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtkpuziwcx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtoksdvdqx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gteifmpoid.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gtojkriwwe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtnstqvwfh.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtwcxllmoy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtbflfphcr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtymmldlyz.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtqnbvydjl.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgjgujnkc.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gtkfkgkxmb.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtmghvvawh.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gtrkthffqs.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtyzwxenqs.html

name="Tom"; echo "$name"
来源：http://dali.yongpay.top/Article/details/gtljzrtokc.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtysovxiyb.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtzwnycmfq.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtfzevinca.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblezhfpz.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrigjthed.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gtyjxyrmub.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gtkxvroeux.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtciyyimdw.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gtqrdyekny.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gttinkuvkg.html

[R08] 数值比较
来源：http://dali.cdnleiting.top/Article/details/gtkdcbtchk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtxxcwhmod.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtvfmiggdh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtdqiqstxd.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gtlskjuuth.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtamyottgu.html

[R11] case 多分支
来源：http://dali.zhixingplan.top/Article/details/gtvfmvuahd.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gtkszpejqy.html

start) echo "启动" ;;
来源：http://dali.ybcxt.top/Article/details/gtdmdloisi.html

stop)  echo "停止" ;;
来源：http://dali.gotoacloud.top/Article/details/gtekejryim.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtnyeyqgtt.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtqpyuztke.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtcbtkfpwq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gttcmvffyu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtrnwaskwr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtyejrycyh.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gtgvlmuixz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtzzkdnruj.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtxpypwamq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gthyrxbefp.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gthowzxlep.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gttdlbohqp.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gtnogahwtw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtiwlloyst.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtmpsullix.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guannengcc.top/Article/details/gtvmrjzane.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gtnkbgjlia.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtatpegppz.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtyeamlfiy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtwpisiuop.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtyiwexzcg.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtxexwrfhf.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gthfgbdghy.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gtjajzhgfc.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtkqqymzbg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigufen.top/Article/details/gtvkqnxdpg.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtljxzagzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtlizmbfwm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtfukdznhw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gtmpuvzpwn.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtivehnkwn.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtxbfkoyji.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtgnpbdlpv.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtjmkciuvn.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtaibqbsxr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gteifdvpvt.html

[R29] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtgyaafvxq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtimwzbeci.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gtcmgpelwh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtjawsysca.html

[R31] 局部变量
来源：http://dali.yj20258888.top/Article/details/gtlvzxgrer.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtdhjqdsmk.html

[R32] 参数个数校验
来源：http://dali.zhengqikj.top/Article/details/gtyzugiewp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwexnqbbe.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtgohrekpi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtgwtheaxo.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtkgfmyzng.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfesyakoo.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtfagrretj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gtiwmlhkwr.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtotwhmqsi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtbvcnrrqj.html

[R37] 把输出赋给变量
来源：http://dali.9152youxi.cn/Article/details/gtzmxaivfc.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtcfcpjoje.html

[R38] 管道串联
来源：http://dali.yj20258.top/Article/details/gtfytaovcz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtqeqfpqty.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gtaunuqqkj.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtqvkioppo.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtnnctfwmn.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtqygdysip.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtermuhztx.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtsityesrl.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gtjieblxjr.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gtoaijguky.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gtyoqpitqw.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gtxtaznybv.html

[R44] 按修改时间查找
来源：http://dali.c1oappe.top/Article/details/gtgfpvozqm.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtrirovjua.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtlxngfdns.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtllnadghz.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gturplknfx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtuvtnkcub.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtzxyczxfy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gtdvgndctb.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gteungpccp.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtjbwxboia.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtcdonssqh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtmzzffuyv.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtqqcylevu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtrcjudfhc.html

[R51] 排序去重取前几
来源：http://dali.sufxvd.cn/Article/details/gtfhrdqplh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtzkilobcb.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gtjmvwcayo.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gthsdfyaby.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtrvqotstu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cdnleiting.top/Article/details/gtjsygtblh.html

[R54] 比较两个文件
来源：http://dali.zhongyouzk.top/Article/details/gtksjoxqyx.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtjlaodlhm.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtdrdnuvgg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gtygxyttcs.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtaobbwfpa.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gttkwgqxci.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtadmxaljm.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtrgtbpueg.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtassagzth.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gteoldarob.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtqhlslqqh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtpsmrzwqm.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtnuebtvgn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtjomagmyt.html

[R61] 磁盘占用
来源：http://dali.c1oappe.top/Article/details/gtwrnebycl.html


<!-- 参考信息 -->