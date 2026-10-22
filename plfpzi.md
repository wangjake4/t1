代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2fqsdpcqa.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2rexwqnxz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2bfumtbmk.html

[Q12] 插入后取自增 ID
来源：http://dali.guannengcc.top/Article/details/gt2ppgvhlzb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgloohii.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2zoffsvdp.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gt2iacedayk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cliayowq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zdqjudy.top/Article/details/gt2ukjjbxdd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnqzz.top/Article/details/gt2nskcnvqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gt2guagldda.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gt2sabgarpg.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2wzvnyqif.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gt2nyoeiwxh.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2ahdedonf.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gt2gdyoypfv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gt2zfjrgtys.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gt2leybwwkc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2zhzptsaw.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2vszgofps.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.smart0.xyz/Article/details/gt2qdpqtzuq.html

[Q20] IN 列表
来源：http://dali.hammf.cn/Article/details/gt2kiqsnqcl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbobrflj.html

[Q21] 空值判断
来源：http://dali.sufxvd.cn/Article/details/gt2wurqmtqp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daxiang520.top/Article/details/gt2sodgtamn.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2wgegdtza.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gt2ufibsewq.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dsjhuozd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2efwcneon.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gt2kgcvtyex.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2isyukffb.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2rqybfsla.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gt2eufssvqs.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gt2gvbjhhai.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2kcfkmvvq.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2wzfmrmnb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2nzpxxdbi.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gt2obscmukt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2tvqrwxfz.html

[Q29] 最大最小值
来源：http://dali.yuxming.cn/Article/details/gt2waxoqnbm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2yqlcgzat.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gt2isqapxbs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2qbtpcexr.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gt2bqcakeqg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2ctgfhswo.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gt2tvabdqeo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gt2lozfpuib.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gt2gbztuhen.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gt2gqyqiqzg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gt2pwrzzzjj.html

[Q34] 每组取第一条
来源：http://dali.hammf.cn/Article/details/gt2wywmczvi.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2wwslswhu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2rpxhmlai.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gt2tbfompvp.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gt2sbojpcec.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2mnjlinoi.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gt2xeqxrwes.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2zjyqrdhr.html

[Q37] 右连接
来源：http://dali.yj20258.top/Article/details/gt2qvyvylto.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssdfebhb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vunueutt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2jsuqtjmj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxakcgfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gt2cpyymtvb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gt2jlhgiikq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gt2zwavkfgo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gt2piuwthep.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2mzjkhzss.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gt2vhxrjcgo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2qbcjdeuf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigufen.top/Article/details/gt2xlehqrsa.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqwfdkhi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2wdvreujk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gt2juazpuum.html

[Q43] 标量子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2fyjjldzr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gt2vechabav.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2yvwhctqd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gt2elqbtqed.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2mhwhosbe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnzbizqt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdojzqqy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2bhnifivz.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2fejtklrc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsfwdpjv.html

[Q48] CTE 公用表表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbktwbrt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.smart0.xyz/Article/details/gt2cjsxbpza.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2othedfqw.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gt2qovszlrj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2qdrrblzc.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gt2tzpeivdx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2fsxhqdtz.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gt2shenqyeu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sxryk.cn/Article/details/gt2geybkjhl.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysfhmrdb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gt2huroxyvl.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gt2igdvinyf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vojugqsn.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gt2twfbvupl.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gt2cpqhmhfc.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gt2wacsacyn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2pufdjyyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptuxqowr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkhfdunc.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2utrylymg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gt2ibvytpgi.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmausfsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2ovhfgcqq.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csrotpry.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2bppjoprv.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2sqvbziet.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gt2ilxbacyl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2ypcwpbmj.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gt2jwutigzm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2kkihgbti.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbjembvh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2wuvdfzsp.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2sewdzczt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gt2qxhflbpg.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gt2ffgjoyli.html

COMMIT;
来源：http://dali.zycfv.cn/Article/details/gt2qfpxmdbu.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gt2tcluflrj.html

ROLLBACK;
来源：http://dali.wangdashe.top/Article/details/gt2xmdbtmxs.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2iqmuuloi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2wcuaaest.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gt2crnrmecb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pekpnpvq.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gt2voxqtwjn.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2lwgtmqrh.html

ROLLBACK TO sp1;
来源：http://dali.gzhubu.top/Article/details/gt2tlqsjzud.html

[Q69] 查看执行计划
来源：http://dali.fengsongda.top/Article/details/gt2epymkvzx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2ghtzpwjq.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gt2rttdjsbf.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvmblblu.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzuplrgl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gt2xqvprres.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2jkbgwche.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2suhgjvfk.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gt2hekoaxdy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2aoskqhmf.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gt2iguazaam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gt2sjmxnlvx.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gt2feyqfqbh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kwglrhva.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gt2xhpjoxpb.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gt2mxmainiv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gt2fepdcojj.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gt2yhpjnwmm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gt2joldljdd.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gt2godifgel.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gt2vfkegpqo.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gt2qlenjphn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gt2lewzmhzb.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gt2llhmbfav.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kaknqndd.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gt2qoqqxgmu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2etdqiztr.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gt2rannzcee.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2znyhwuwb.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2vwxkawix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2qzwklqcu.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gt2gjyvmxzu.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2kyqxcnzl.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2hefclhtr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2cpfqsguw.html

[Q86] 读取 JSON 字段
来源：http://dali.xziqi.cn/Article/details/gt2loxsutnz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2ejboyixb.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2gmzrphhl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gt2ghdtneaw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gt2bjdvvujs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.bjfxy.top/Article/details/gt2uawielvw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gt2qagfmlrd.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gt2hmthbqwd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gt2aclrcdrh.html

[Q90] 生成序号列
来源：http://dali.hnqzz.top/Article/details/gt2srgsflac.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gt2cttcsxpq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tncgltoy.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftdurbkc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ziwajmqi.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gt2cfibgocq.html

#!/usr/bin/env bash
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsmsfpmy.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2zcdhpemz.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gt2zjrqdnsq.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gt2barrscfh.html

[R03] 只读变量
来源：http://dali.yueranfly.top/Article/details/gt2oyorjumo.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2oseeckno.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gt2ahyaokrj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gt2xdcpjndr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqunegrg.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gt2zbndkusr.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ksnldtps.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2uhxovlrq.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xrdptpui.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gt2rprzsoqb.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gt2puztnxoh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gt2detshxvx.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2bxiutxox.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cucudq.cn/Article/details/gt2kjbqyvhe.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2rtbfyhji.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2kdinwpmr.html

[R11] case 多分支
来源：http://dali.feifeiyinyue.top/Article/details/gt2lguwbtlg.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gt2nciigxqn.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gt2tkcrnzlz.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gt2lpdlgzsc.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gt2nfxyoxjf.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plxbaijz.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghisaskp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2wkfwomvk.html

[R13] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gt2lojyrejk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2qphpbhzy.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gt2fepoefqh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gt2qoodjnhy.html

[R15] while 逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2vthnddwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gt2gynfopov.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gt2qhqhqhbs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2dwwngimg.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gt2mbbxceez.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gt2kxstguqr.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gt2pdjqlbmn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gt2vxpaxhwi.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2cykswhhn.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gt2fzqsqryw.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gt2byfmogjp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gt2iymawnra.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2ujrgindi.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gt2hrzruraf.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gt2uzxkvmbx.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2sugarhis.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2bupxcady.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2qtixiouy.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilqzaqhb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gt2oortsqhc.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gt2mieiylxr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2xoylasot.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2yyycgexy.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gt2jbupmhlk.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlsajdnl.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2nsdwqwft.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gt2sktzmfof.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loeetfvb.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2bdeulkxu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2byufthgm.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2anlxjekp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gt2thdlomjz.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gt2gblsbcbd.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gt2wnrqieew.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2vnnffwxg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2bflkdxfv.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqoljzzd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gt2kbidyubh.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gadjxgnw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2ngkkdsjn.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2qtwlyahc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjqybtpg.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gt2xwsjgwvd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gt2fazdxeks.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gt2jbhxmahz.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gxmkcvee.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gt2ruvwpkmv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghjciksv.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gt2sixusqja.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2laxnqnaj.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gt2dkoskjrj.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2nhgwibka.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gt2bcpaudja.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2mudtfgen.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2ssusegwq.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2ockrsgxp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igjwwuku.html

find . -name "*.log" -type f
来源：http://dali.tanke756.top/Article/details/gt2zemykngb.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gt2axxsgljv.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2bajsrtzl.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gt2jscgaftc.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2trxjhkpl.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2jkjxiagd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2xwcqqksw.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2meoqygkf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gt2kivfviun.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gt2emxkhjfh.html

awk '{print $1, $3}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2lwdgzihx.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gt2xcuebfma.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2fhhcymfv.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gt2xxrgobjs.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2jprgosdz.html

[R51] 排序去重取前几
来源：http://dali.yueranfly.top/Article/details/gt2vnahojwd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gt2tfdkjqfe.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gt2blkmjmcz.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gt2jmoezqxk.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gt2ueyqztkr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gt2uswbknor.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gt2bshnhwpl.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2wginkxni.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gt2qwpjkyrm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gt2iydehzgl.html

[R56] 远程拷贝
来源：http://dali.chenzaomai.com/Article/details/gt2ewkymavt.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2tbofnmth.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoictikg.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gt2tccqsxak.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gt2yahehnvy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2nxloezcf.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsgnnbpi.html


<!-- 参考信息 -->