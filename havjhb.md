代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2enkxyndg.html

user_id INT NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2asuxxudi.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gt2flkwrund.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gt2jndfkrrf.html

);
来源：http://dali.yj20258.top/Article/details/gt2xtcbpsma.html

[Q03] 增加列
来源：http://dali.iojbl.cn/Article/details/gt2jtpazqaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gt2icyudsbj.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gt2cbyqnmck.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gt2xguatqgh.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gt2xbelqran.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqbcvhhq.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gt2icfqmpdk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gt2yerwqetx.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gt2pdkfskuz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2pzelette.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gt2esgtvvrl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2kdvobmkt.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2fqqxhkma.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2zjqzwicr.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gt2eniiiwdb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2ujittluc.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbdifjrw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cdnleiting.top/Article/details/gt2kegsvuqc.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2utrgyfvh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2nxvizrxd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gt2uykovkru.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2vtixbjkr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2rvgcsnzu.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gt2molcuqov.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2gqljetil.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2etevysbl.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gt2hzbgsfew.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2xhsqygya.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2pyvvxwsw.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2igwxcsrp.html

[Q17] 条件查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2grfjhrnz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gt2hmpayrfx.html

[Q18] 模糊匹配
来源：http://dali.yuanzhike.top/Article/details/gt2ksdabrue.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gt2hcquvsmd.html

[Q19] 范围查询
来源：http://dali.zycfv.cn/Article/details/gt2ulpermdo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.meibo888.top/Article/details/gt2mgrvxmtn.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gt2bqcwcaje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gt2txzdtazb.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gt2wouerswn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2mgqdauze.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2sodbfvon.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gt2ypcsormn.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuzceohu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gt2teuzwhkt.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2ogfksndy.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bglwmdzo.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nqiuylco.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gt2gqametkx.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gt2wnyajjrt.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovgxuegd.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2xuwydmsi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2klpgpgzm.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gt2uggqzygz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2diekfeid.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gt2kzjwvlob.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbboiyfb.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gt2uzqqokcw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgrahdal.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gt2tebgxzpg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2uxldzhpk.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2zslfgtyr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2ruyadihx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pzwgsbnc.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2pzohnyvc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gt2gwzejdgi.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gt2fidtjaai.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gt2xctvjnvu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2muyocumi.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2guqkmaro.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2npvjfvhk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2slcysipf.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gt2epdgvakm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2nmyzobeo.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gt2uzlhztvp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gt2avueexbl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoxxprww.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tetrthza.html

[Q39] 自连接（查上下级）
来源：http://dali.cashguo.top/Article/details/gt2apfzspjk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gt2gcvxvaej.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgmhrkgi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gt2visoupxm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gt2gsebdsfm.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2jgkwmtmn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gt2kpooxdzw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gt2crhimjbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2zhzautoy.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gt2ptbddemz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gt2keqkuxjx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gt2lzkkiwyf.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gt2zbtfcoie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxuanxn.top/Article/details/gt2wqpadyrt.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2zrgmcrzn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gt2wxxefivt.html

[Q45] EXISTS 判断存在
来源：http://dali.yongpay.top/Article/details/gt2bimqicyv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2lncogyoj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gt2raaugtof.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbahryab.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gt2wybhknxs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2xglhmbjj.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2vybpctdg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gt2hgduhjvi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gt2dcsnjaky.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2isyljyvh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2cdtrficn.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gt2jpxqpilu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gt2lsbltyxv.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gt2ixdhzdde.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2vzqswbjt.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gt2dluqpkvw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2knezbcno.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gt2yjxxwstq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gt2mablfarf.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gt2ufdfdboo.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gt2ieuoicbb.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gt2juinoqvh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2turhtiru.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gt2nwcvfayc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2byuwwqfx.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2llowyyzt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2dfcbribu.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gt2diszuudw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2vqvtmchy.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gt2ysusldbc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpmujxos.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2bunuymus.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gt2ccywswti.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2zgeihjlq.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gt2klxrumvg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2smvndogu.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gt2fufuggqe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2puizqwmt.html

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gt2entcgdjy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gt2sstuzykp.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gt2pbetbohi.html

COMMIT;
来源：http://dali.shzxlz.cn/Article/details/gt2mbaavaxg.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2wrcajumw.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gt2yygalfog.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gt2qgxrljht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gt2gvrupxmw.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gt2nlcwcgjw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2lzrcnhti.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gt2ukwjqasw.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ijmiluki.html

ROLLBACK TO sp1;
来源：http://dali.haohaochexian.top/Article/details/gt2hirgtuzt.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gt2agxxjnkm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2rutovnia.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gt2perwvndx.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cedbjond.html

[Q71] 查看建表语句
来源：http://dali.wangshuangyany.cn/Article/details/gt2chgjrsrw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gt2imdnjlph.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miakgrgp.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2tgzlulyv.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gt2ogflwtcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2kewvefsc.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gt2aefxvodo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2higakpwe.html

[Q75] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2rurvnhdr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gt2puvlhgmo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gt2arshwdpe.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gt2swzmstic.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gt2nmwukyvt.html

[Q77] 时间加减
来源：http://dali.jiagoushi.top/Article/details/gt2suuebvcc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gt2wxehbsqn.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gt2fhwwwwui.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gt2bazxojcb.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2tvbvriyc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gt2clfezver.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gt2fxbkaupv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2oxpgytwp.html

[Q81] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gt2ojnjcepl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2zqtahpmb.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2rcoiszjp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2cmkarplv.html

[Q83] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2fptrjplr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2wtecbsmq.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gt2hxjihjzc.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2atypggek.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gt2awoghbbn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gt2muaumdwp.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gt2mfttykax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gt2oslxeazq.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2mjfcuulx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gt2btnutvfx.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkaciobr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gt2fldmlfjf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdcmonx.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2ilswnbmt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2zmybwvst.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2kknwglbf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gt2ktkhguka.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xuwjbeiq.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gt2atnudjmr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rlbtetbv.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2ldjqjsdr.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2kvbociyk.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usukaurb.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqpelpiq.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gt2simbwvlj.html

[R03] 只读变量
来源：http://dali.xylfe.cn/Article/details/gt2xvrerzkk.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2pmhqvayh.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2ugefjwdb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gt2wnhxtzea.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2pslrecnw.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2hlqccguo.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2nfqlthvc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gt2mptottpk.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvrmsnjx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2ossykncd.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gt2nepgefnh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2mabzikhl.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gt2qpstjvjm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjmluqtn.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsjrlnte.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2fimyfifw.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gt2xgxvbfcy.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2tggyiukn.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2tkpyaabb.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2nafxlesj.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2lkuktdha.html

esac
来源：http://dali.yuxming.cn/Article/details/gt2vlayvncv.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gt2swqjdyby.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenzaomai.com/Article/details/gt2wubjgpte.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2fyvfiioa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2irsbdrja.html

[R14] C 风格 for
来源：http://dali.pycfn.com/Article/details/gt2exlrhiiw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2okczfnru.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2mtrqedqg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmzbukzh.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gt2psiadwqw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gt2vtectghw.html

[R17] 数组定义与取值
来源：http://dali.jlsjyb.cn/Article/details/gt2nqzdzjva.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyjzalhf.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gt2wicofwrs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2japvrklk.html

[R19] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2uoaddagr.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gt2nvdqawxm.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gt2stkwgcwt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gt2gumafnel.html

[R21] 字符串长度
来源：http://dali.yj202588.top/Article/details/gt2orusxfww.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2kvymppve.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vavwsdoc.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gt2gjyrpiqp.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gt2hnbxoawa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gt2ruccwtmf.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2tjknjisx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gt2erlxcrld.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyecnsa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yangfankeji.com/Article/details/gt2vbiakwyh.html

[R26] 命令替换
来源：http://dali.bjfxy.top/Article/details/gt2haegnikf.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gt2hmmwsfid.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2pbzvepyh.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigfzy.top/Article/details/gt2wurybdsz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyepoxn.html

echo "scale=2; 10/3" | bc
来源：http://dali.havefunace.top/Article/details/gt2aohvtggl.html

[R29] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2mhencnuk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gt2jmtmwvys.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xssfequa.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rctjepeb.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2iewvohir.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gt2lggvdeca.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gt2ryxaawhg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gt2bvtzgyfa.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gt2hjhzcjzf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gt2jngiuvsd.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2ovecrlle.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gt2gpwqqwne.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gt2tnngvxbh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gt2iumfnubp.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gt2eajrssoc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gt2hronvghi.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gt2zagkmvuq.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gt2wwtourjd.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2ugwrgbef.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2wnwtwmrc.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2xreacuky.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2iszfxrmv.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2btjujkxj.html

echo "log" >> out.log
来源：http://dali.ehwqpu.com/Article/details/gt2zyxmwfgm.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2elkuduwh.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gt2yntkurrd.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2wtiedvjd.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvuvmody.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gt2bujfpprk.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gt2uigyrwii.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2dgdaxjnr.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gt2qnartqil.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2vehlyzoq.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gt2fxzyjxdp.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gt2ksnzfbtj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2gssiqkia.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gt2thzeawka.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2rytzxoxd.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gt2rqylkyqy.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2rlpcanhc.html

[R49] awk 带条件
来源：http://dali.aibaodan.cn/Article/details/gt2lqcahqji.html


<!-- 参考信息 -->