代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxevtlh.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gt2wnygichx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gt2bwesjvmr.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gt2qkhxnpae.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2tdymfwhm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gt2hrsytwsw.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gt2uizotlcn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gt2iaiykrjd.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gt2vwgrrhug.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2xepxewda.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gt2qppbuqvy.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gt2noseekjy.html

SELECT * FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2ioolmcnu.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gt2plmhawap.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2hsatczmu.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gt2eixdkdwx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gt2nxwqglce.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2lpcibwfn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gaupjppd.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2hrgogckb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2asilmkrm.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gt2ejzpujrk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gt2hnzysflk.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2wozliuvu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2mldiorct.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2oemapjpy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hszsmtfi.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmolliiw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gt2ukpdoixd.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gt2avzajihz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2kdaolrdj.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwnpcsuq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gt2dkcuexwr.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gt2fhoopkon.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2nktrstti.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gt2ajunswuk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2qlcynkol.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gt2eumpmhlu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2dudiblgt.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gt2cismboib.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2nsblgmov.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gt2kapoehjn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2nzaxysgq.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gt2meymtihk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gt2ulklxnme.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2fmnyoibz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gt2kdokibvi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gt2arscwlkf.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2xspgejbu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2vdjzsfdz.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gt2nnygjnrn.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gt2wugswnnf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gt2bxnrlodx.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2rfmswsjq.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gt2uncjjrmr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2sdpiniba.html

[Q36] 左连接
来源：http://dali.chenlongwang.top/Article/details/gt2ajmnhfee.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gt2cnkqatgg.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gt2tknafhlg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gt2rdbyoqsn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2ejrivxue.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gt2ztayfpiz.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2grljzzla.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2xttjioet.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gt2jisjexwo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gt2eflhwwae.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gt2ykgaxvae.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gt2xathtttg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gt2xkbjibrb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gt2zzrymrxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sckelixm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gt2ldwtnlng.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gt2lairqqvj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2azwlzgni.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gt2olfyaezh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gt2rolnvkrl.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2rsabrpae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gt2stdgliqz.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2hdmpquom.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ghhdujfd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gt2ntkvyjls.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2rjfhjmdu.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2qxongcog.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gt2xnhfpxtf.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gt2bbxpslam.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gt2pldydxgm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gt2fbpxctxm.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gt2wfflyqvo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2mbqlcvze.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gt2fyvlywli.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2nmonmsot.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gt2limkisja.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgpqkbsq.html

[Q52] 删除指定行
来源：http://dali.nanxuanxn.top/Article/details/gt2klszccsg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2yizdvxvj.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gt2pugwcldf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gt2jjnmtukt.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gt2vfljlmih.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gt2hrygejjw.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2gbjrbrww.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2durjimfr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2uqcnbanf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2mpmiuwfs.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gt2pgaywkas.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gt2ulmnzkby.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gt2uwttkkla.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2ghmxbxkz.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gt2tnjgubbe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2cvkocmje.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gt2laoogfwb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gt2txdgizvr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2hwfxlnvb.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2utmgxpvn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaqotunx.html

[Q62] 分组占比
来源：http://dali.ybcxt.top/Article/details/gt2tvlbyljv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mavmlafz.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2qvtkqbdx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2oqnibzhp.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evcemnoz.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gt2bjyegnss.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gt2gbmncbqx.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gt2rbnkbjej.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gt2ugduiklq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2cerohnpa.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztjwyofk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gt2uzhwgdav.html

[Q68] 保存点
来源：http://dali.mhx1999.top/Article/details/gt2lrscmqbf.html

SAVEPOINT sp1;
来源：http://dali.gzhubu.top/Article/details/gt2zswxhree.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kanyrwua.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gt2zibpafkb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gt2nsmbngvc.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gt2dadcgrno.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gt2qmgkbuyj.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvahzycg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gt2defufsif.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gt2ohfukaok.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2ctjqjisl.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2ckvqznty.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gt2azjhihlu.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gt2retiaiqf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2qynkrpkt.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2zfqsgfao.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2amyqogep.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gt2dtgcmump.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gt2qrprthjb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.smart0.xyz/Article/details/gt2waubjnfu.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gt2hcnyxdsq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yanxiufei.cn/Article/details/gt2zndsyjrs.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2oryyirpi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfpeptwa.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gt2eepeprfz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfyhymdr.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gt2kxtgsqdw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pojcgxal.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nvynvooe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poljpmir.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gt2vcwydzvx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2ibzxoljx.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2oizzydpp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2fyfxldue.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gt2zgumzngm.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilggdocc.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2encembso.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gt2tmmyukmt.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gt2xvmkhmgv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gt2wamsztsg.html

[Q87] JSON 字段做条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ervqccxr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xziqi.cn/Article/details/gt2iqotutfm.html

[Q88] 行转列（条件聚合）
来源：http://dali.cashguo.top/Article/details/gt2imrxypyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gt2yaufltcs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2aqgividr.html

[Q89] 判断表是否存在
来源：http://dali.ydzc1.top/Article/details/gt2xnbikmzc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xylfe.cn/Article/details/gt2wwbieerr.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gt2ucshzwmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gt2bdnmnhuh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkzcwufn.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gt2prkcrqmk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2cqyvoaml.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2dosnsbwv.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gt2bkidnzyu.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gt2ibsmiwlh.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2lwcjzdut.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2gdjsuxjj.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gt2kdbazokl.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2wjcngpji.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gt2ijnggbdj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsywxnpq.html

[R05] 参数默认值
来源：http://dali.hysaishi.cn/Article/details/gt2kfriczjj.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2amehgbsn.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gt2fwclxlpr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2jsjnmkja.html

[R07] if 判断文件
来源：http://dali.nwbrower.top/Article/details/gt2ayssbljy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqhxuwja.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2yenjvnvv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fzhhl.top/Article/details/gt2tfjzawwm.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2hceqykjd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2ewxatnhz.html

[R10] 正则匹配
来源：http://dali.guowangkeji.top/Article/details/gt2bdblowuz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2dgddhito.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2robgdimx.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2iuykezfp.html

start) echo "启动" ;;
来源：http://dali.ivvv.top/Article/details/gt2shjrygrw.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gt2ugyxoitp.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gt2locdoaat.html

esac
来源：http://dali.cqqwz.cn/Article/details/gt2zvtofxcm.html

[R12] for 遍历文件
来源：http://dali.yanxiufei.cn/Article/details/gt2alvrzyii.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gt2qqtrfavs.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2lbnvpxua.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2thgxrirc.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gt2crkerish.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2forwpwzu.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxbaofrs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2nozixmop.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gt2qbdszbhb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2dahicusl.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gt2aqycnibw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2bktjlahz.html

[R18] 遍历数组
来源：http://dali.haohaochexian.top/Article/details/gt2wcojmstx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cashguo.top/Article/details/gt2hhgrmjhc.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2ueghsixz.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gt2hctvcplr.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gt2hczokoqc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gt2mzmkrfsz.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gt2ozwkrnpk.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gt2akbivatj.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdudauoj.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gt2cctbptty.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2arlxvdhk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gt2oquvijnz.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2gtljkldy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2qwuzdtku.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gt2mjwrudvb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmbdppal.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gt2uyhonvom.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gt2ikoitmsl.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gt2cgjtqcuw.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2dfmoxwxh.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2ghuzyjwl.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gt2ixrgoxly.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipogqmje.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gt2cmlwopyk.html

[R30] 函数返回状态码
来源：http://dali.daria6918.cn/Article/details/gt2fajyknto.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2vvlqgxhe.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gt2dodpvlbd.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2rzldtkuu.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2pgegtuvi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gt2ecyrqqhw.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gt2rarychfn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gt2amhcvlbg.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gt2tuepjzsn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thlrxpba.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpiqrgr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gt2wbbmlkag.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwndcnni.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gt2lvyeammj.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gt2yfzxszen.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bexptktd.html

[R38] 管道串联
来源：http://dali.meibo888.top/Article/details/gt2fcleakem.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gt2quzunbsg.html

[R39] 重定向标准输出与错误
来源：http://dali.gogol.net.cn/Article/details/gt2qjgpgerz.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2utqyzkta.html

[R40] 追加写日志
来源：http://dali.jianghu66.top/Article/details/gt2hkqaybyl.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2tekqdkif.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gt2chjsqive.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2pkulvdai.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gt2bgpbmubo.html

wc -l < a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tltwzaff.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gt2lifrcbkv.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gt2mvmhczqc.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2eqqfwyrb.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gt2mwichzmv.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gt2lpcecblz.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gt2siopywpo.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gt2emcmpfrv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2duqtgzcb.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2mfvbuxgi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdnzjuoj.html

[R48] awk 取指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngfwgdem.html

awk '{print $1, $3}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2bhwsqupf.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gt2azyqjhvn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gt2bgtrwpqf.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gt2kbzndggk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sxryk.cn/Article/details/gt2zzmiwmlx.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2vooolxsf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pycfn.com/Article/details/gt2xcqfuwnx.html

[R52] 统计行数
来源：http://dali.svipenyu.cn/Article/details/gt2ovknzlyk.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2hziniiyd.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gt2gyknlght.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sweek.top/Article/details/gt2lkzwlyui.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gt2bzazgsaw.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gt2xwxtxrvz.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gt2vxorlddk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzeylwzb.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2inceqgjf.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gt2cwecpsdd.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gt2satlsyki.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gt2uppzkiqe.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2oaliwlzg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2xlcrpcle.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2ywjbrfjr.html


<!-- 参考信息 -->