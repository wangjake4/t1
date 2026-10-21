代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtkuasoums.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtmraopzjk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtjxlcvvwc.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gttbagecnb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtsimtpydi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtwfchpyow.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtdroqgpns.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtyqqmrmrw.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtdlkyhabk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtzrvugwxp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtrbhxnuxl.html

[Q15] 查询全部
来源：http://dali.cdnleiting.top/Article/details/gtsqnqigqc.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtxxmcuygc.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtbwzzhyuh.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtpwswgviu.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtishlxvne.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtebqefzwp.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtoanwtzri.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gttaypjory.html

[Q19] 范围查询
来源：http://dali.pycfn.com/Article/details/gtxktcxedh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xylfe.cn/Article/details/gtnlkfzsar.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtnyeeukyk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtnfmrbvgt.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gtstzgmnvy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gtnfutgobi.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gttupmtxci.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtzowrxdmk.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gtsbkzicim.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtwztbspzr.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtxxhqejdr.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtqnlazlzd.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtpaofupvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtfdkkccyv.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtfyxxyawk.html

SELECT COUNT(*) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtuyotlvmh.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gthidpazun.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtophnohpz.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtxhrzhlez.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtvvsjvnlx.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtemwdvqqb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcynkreff.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtcfnfxner.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdftcmkmu.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtvttwwcxi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkrcfips.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtwwhkccqv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtuodbsqbb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dashuyun.cn/Article/details/gtwwofyfqg.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnovfpfu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtfgooqqbo.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gthuyqtvim.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtgfzmrpok.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtlkzkayqx.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtkcyfdcah.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtowatzisi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtnoklocig.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtvdpjdxbt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtbeshwjdl.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gtlbkmsynp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtmctibdlt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtqqaoyogc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtdfvxyiqf.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtkvrijijn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtmphwpivm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gtjrrvsljs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtsoawszoh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtwlzyzsza.html

[Q41] 多表连接
来源：http://dali.guowangkeji.top/Article/details/gtlnnkolwl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtwqqbkjwj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtfxwkstkh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtdbclhxoz.html

[Q42] 连接条件附加过滤
来源：http://dali.chenzaomai.com/Article/details/gtxzcbexqg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtiwxckfvo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtvldciveg.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtvamjitup.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtttzfgtjo.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtazqgriqx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtauogupnv.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtwrwyzhbh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtogrwzlvd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtytduiqkc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gteoqsquls.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtrhufnxju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtyruaniep.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtvjibjhqe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtogvcxisb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtuzceglxk.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtbqblslyj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtlojeikux.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtgvpjuira.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtlgbyagya.html

[Q51] 用子查询更新
来源：http://dali.yj20258.top/Article/details/gtgdtpznro.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzrhdxuc.html

[Q52] 删除指定行
来源：http://dali.gzhubu.top/Article/details/gtjkmeeapl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtwvlowkpi.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gttlkusfay.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtampuksro.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtxwxshnfw.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtebtvpojk.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtdlswyhxt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtpseczvcn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtazqmkwus.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtvrhajhsi.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoslaihk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtwuwpgedi.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtthmjmpbj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtoppxderm.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtunppsufi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtlgofuimu.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtpksxftdv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtvldzjuzy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtbgscrqbs.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtvtijawjk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtumtvfuhc.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtgclnoraw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtmkmcuumo.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmtzfmzi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtaomhojsw.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtifypytqf.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gtrsrlormw.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gtmqdecptm.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtrtzaeblt.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtcjblmfgo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.quarkkingdee.top/Article/details/gtscczuotw.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtdndzhdec.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtnqiyxkoj.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtziwghwob.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gthynlhqmk.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtfqgovqto.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtrefzcsbc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtxgymdrdi.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gtpwjijinq.html

ANALYZE TABLE users;
来源：http://dali.havefunace.top/Article/details/gtsdevwuww.html

[Q71] 查看建表语句
来源：http://dali.chenlongwang.top/Article/details/gtwwmamdls.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtgzhebejn.html

[Q72] 查看索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpqatyyk.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gtsdnjdlsv.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtntbbgbzm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cheryme.top/Article/details/gtiunnpruk.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtwmfonvsc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtvnwqxyee.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtxmjioird.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtcamdupxt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtvqwlwlfa.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gtmiqkglpg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtqcmfbvqy.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtubgixmqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gteedprxyn.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtslclboiq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtaiulsjom.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gtkrjvbhjm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gtcclpccoj.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtfgbjddlw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtozjdleys.html

[Q81] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtcpbshbcb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtuvceytsq.html

[Q82] 字符长度与字节长度
来源：http://dali.meibo888.top/Article/details/gteadpalrq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gthtqpopoq.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtafcujgdw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvyhyjhot.html

[Q84] 去除首尾空格
来源：http://dali.yangfankeji.com/Article/details/gtolqmwbvt.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpqrkxxv.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtceaidfll.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtpvkclxss.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtdbokyjoy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtwttqnmpd.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtskfglqeg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gtawbhraug.html

[Q88] 行转列（条件聚合）
来源：http://dali.c1oappe.top/Article/details/gtjmhtnfpf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtmefmvzub.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtitafkjru.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtmpezeysq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtgecgczed.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gtodwrdphm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtbkuuvydm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmywxqfai.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtntemdluy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkcmokat.html

[R01] shebang 与严格模式
来源：http://dali.fengsongda.top/Article/details/gtukvqdghb.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gtkptuoxwd.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtytzygdip.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtmgvpvcdr.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtrxawhixa.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtqafnijrs.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtlabzukpc.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtncnrtqdi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtyprlttnt.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtwrlfoueg.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtjkouiyhx.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtiumlulqa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtfjrcjycf.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtsulkwhnn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guowangkeji.top/Article/details/gtmwydqzbz.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtkyigwfcz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtynxblnxj.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwwcrttz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gtxzrehelh.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gthbjkaizf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtgaeectur.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gteuqzvsfh.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtpqtlnxny.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtlyypbwnd.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtnktklwxo.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtfjwtxihl.html

esac
来源：http://dali.xziqi.cn/Article/details/gtasunyngg.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtijqajqzq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtunxdqnhr.html

[R13] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtxefzvcre.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtzvcgxcvg.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtznjqbpfs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtmjsukucx.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtoogoiatz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtwukgmzdc.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gtzruirtdl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtkofeecrt.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtopskuakj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtntsymazm.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gttdfakffv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gttzrqvguv.html

[R19] 数组长度
来源：http://dali.yuxming.cn/Article/details/gtzyrnnxax.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gtifiwuteb.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtsilwiyie.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtlldxacdc.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtevpzauxd.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtehdshrvr.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvdcntms.html

echo "${s:0:5}"
来源：http://dali.cqqwz.cn/Article/details/gthrszwvwk.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gttlmepbng.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gttniyylfy.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtmyhhwxve.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtgdcznkgm.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gtxefyskea.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtwsmcdehi.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gtgxpafxkt.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtcjltbntr.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtkffmahcx.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gtpiqwucsx.html

[R28] 浮点运算
来源：http://dali.cdnleiting.top/Article/details/gtlspnnhey.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdqwchkb.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtpqytbrsk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cheryme.top/Article/details/gtnivivmlv.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtajezxxsi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphyyxynt.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtmzgsehbq.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtwzovbnrm.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gtxjspcxqy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtjazgtjpa.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gteqknmgbq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtefyxhrxy.html

[R34] 退出时清理
来源：http://dali.quarkkingdee.top/Article/details/gtnjrppcyu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtfkyztazu.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gttmsdrdco.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gtrldxkslf.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnilzqse.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtkzihxykr.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtrcnbfiyq.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtszkrcqok.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtjexxfnrh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtheknlcrv.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtmsvtgfoa.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gtydrvrdls.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtzcagaoni.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtyfjhurus.html

[R41] 丢弃输出
来源：http://dali.pengpengdd.cyou/Article/details/gtgfbcdnej.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtpxhxulpo.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtziwcnlre.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtuhgcpngd.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtvipbioje.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gttbipbxpk.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtpoygtmnt.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtjpsuhfcl.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gthebtinfn.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtcnobvjni.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlksamyig.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtoyiolyft.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbstvbqas.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.redwolf501.top/Article/details/gtexltmwpw.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtyocdjmti.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtjbscqcdj.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtxxnzbqyo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtusmrdkii.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtjxiiizeo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtxtuvzsjg.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtqtjjmhvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gtjgmpiexx.html

[R52] 统计行数
来源：http://dali.cashguo.top/Article/details/gtzbftngyk.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuqakram.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtxsrxkofk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvrzbzrh.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtjxvgsoti.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtujhaadbb.html

[R55] 压缩与解压
来源：http://dali.yangfankeji.com/Article/details/gtsasjuadv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtunqjmmto.html

[R56] 远程拷贝
来源：http://dali.yongpay.top/Article/details/gtznmybfnm.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtutdomacj.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtjbvutnhi.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtutxokiny.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtagfukshc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtucsppjot.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtciicarxd.html


<!-- 参考信息 -->