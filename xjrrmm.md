代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhgzvipe.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2vzoxtnbl.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gt2lwtwkdje.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yueranfly.top/Article/details/gt2xrdbdnew.html

);
来源：http://dali.ivvv.top/Article/details/gt2pbchipmb.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gt2avbjqxna.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2itsavrat.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gt2qasxklvr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2fxzzmxal.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufrurczs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gt2nheeacev.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2rtcqfddw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gt2biairjtp.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gt2rqvogfxv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vawptqnh.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gt2zvxamnji.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2lvghytla.html

[Q09] 创建唯一索引
来源：http://dali.yuxming.cn/Article/details/gt2vjyglmrp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gt2nsnoewao.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gt2roiwbfrr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gt2mvfxpcoq.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gt2tqvsqecp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2prdrsiip.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gt2qowuiwwk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gt2talqtxwv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gt2qrtwildt.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gt2tjizzkpk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gt2siizzdtb.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gt2oanwrmhv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gt2kbpvcuvp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbdqwsgk.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gt2qkvpoaeg.html

SELECT * FROM users;
来源：http://dali.hammf.cn/Article/details/gt2llgtighm.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gt2ujehcngf.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2bpxzfvsv.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gt2emuvfchb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gt2kwmtnofh.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2adgzvvqk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gt2rymsznza.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gt2kezsshuk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gt2rgleiqun.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2gxcrkvlo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2rfizyvjm.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gt2pmsducxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gt2tcfbmjhc.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gt2wpmvfkzp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gt2hyuhcdbp.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gt2ckrwdbjx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gt2ynxhvpxe.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgukvjgi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2yodxweyz.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2xnmlyion.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxuanxn.top/Article/details/gt2jnvvlhas.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gt2xiqwunur.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ygapybcz.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fuhjjmsr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2mprqlryq.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gt2pyngivqt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2ljsmtzuu.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gt2zryufwyv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2leerbqnk.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gt2wgdmoefm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2tlowdeyi.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2wkpqltul.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2dypqhjyr.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gt2nvxrudaa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2oehvgwkt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ppjwa.cn/Article/details/gt2vfoooxlu.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gt2lattuqwj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.vqdsnc.cn/Article/details/gt2jdygyrrz.html

[Q34] 每组取第一条
来源：http://dali.jianghu66.top/Article/details/gt2aqrbsylm.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gt2heibmnwv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aokgjxyv.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gt2awuwpjmz.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gt2jlplffnv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2cnijiupg.html

[Q36] 左连接
来源：http://dali.ivvv.top/Article/details/gt2lkthebqy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2nynqciyq.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gt2izqdydis.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gt2wwkphwum.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2bfgpilqm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2vvwudpaq.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gt2rletvshy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhhcnbvm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gt2fcriaoua.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gt2mjavtvqv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gt2hghatmkf.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfzgoees.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gt2xmogvsqd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gt2yonsyvbe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.redwolf501.top/Article/details/gt2kmqdqxtq.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gt2ftuyctrk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2fdujnpzn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2otxaqzrg.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gt2skdudavh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2mnvfklyg.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gt2bksgalmu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gt2mnfstocd.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlnwzyqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gt2iieemjrn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gt2fralrvvb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gt2ubrhvolz.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gt2srthhqus.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gt2babvxaqv.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2ocoqoktk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gt2wgbwnsao.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2aglwdbdn.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gt2rkovnfro.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2etwlljtm.html

[Q50] 批量更新
来源：http://dali.zhongyouzk.top/Article/details/gt2sliywdch.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gt2vspruueb.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gt2yfytgzom.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2vvpawhvp.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gt2mcmgzhtl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhzmtvfc.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gt2mtssijwa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2bucrvebi.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gt2boidjkqx.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gt2dhaplgel.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gt2moaprnur.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2caiwpxsy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gt2kmpmvtig.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2qfgdcdbh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2czvxguvu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2cmzeiltg.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2xdwfsjwh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2ybcxecqc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxljtmq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2dbawcwwn.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gt2qnzopntv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yonumen.top/Article/details/gt2rjkadeqy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2jqsyubnv.html

[Q61] 移动平均
来源：http://dali.dashuyun.cn/Article/details/gt2gtxlvfxs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2kwrehjiz.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gt2uhjkobgn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2pvbzetfn.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2vpittulh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gt2wadwnwth.html

[Q64] 提交事务
来源：http://dali.yanxiufei.cn/Article/details/gt2fmygyrvp.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gt2lvspziic.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gt2zhsgtzod.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gt2geaprivw.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gt2hbqrhtfr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gt2evqglisz.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2qvwdkvmt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2aisttqub.html

[Q68] 保存点
来源：http://dali.sweek.top/Article/details/gt2gdezunwm.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gt2plfzfqwt.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2udrysgfm.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gt2yecoahip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gt2mvispqqb.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gt2caeriwfy.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gt2kpqgdtgm.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2aqbrfraq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blfqogjc.html

[Q72] 查看索引
来源：http://dali.havefunace.top/Article/details/gt2tkjqtkjk.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2kxfojhdr.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvdggswi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gt2hmkvwwip.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gt2zhhwhwdb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gt2xakdsnza.html

[Q75] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoyoadpp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2phqztaee.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258.top/Article/details/gt2iaxcbrzg.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gt2ncnypfnm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ybcxt.top/Article/details/gt2xdhjbgnk.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gt2pwvhqssx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2vhofntkj.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fooxukwh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gt2cyiqbccs.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwrfvwym.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gt2hupnvhub.html

[Q80] 字符串截取
来源：http://dali.feifeiyinyue.top/Article/details/gt2knmjfnwt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2rukmrals.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2cqdxjxlv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2rgccnrqa.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2ujmftvpw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2xdpxcbwk.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2gpwcwyog.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2flcciafr.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2cravbyzw.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2efnhjsbb.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gt2ebnhzici.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gt2frorlsud.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gt2cssdtymi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnkngzjj.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gt2usayzayf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gt2pojtcxrt.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gt2okbfzzvg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gt2zfgnooiq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2ynpgnroa.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gt2roaftdbq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gt2trdvghqa.html

[Q90] 生成序号列
来源：http://dali.sxryk.cn/Article/details/gt2zzbgmlot.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gt2wixsqups.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2tusvptxk.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gt2lqzkhbrj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wfgbmrxp.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2cohmmtle.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gt2glyqarvy.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gt2sbpysrra.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gt2qrmfhblo.html

name="Tom"; echo "$name"
来源：http://dali.kuanghao11.cn/Article/details/gt2yqwdladb.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gt2leaekwcr.html

readonly PI=3.14
来源：http://dali.ydzc1.top/Article/details/gt2htzclxog.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzdljmkj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urlbjysk.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gt2kldxyqlk.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gt2nyqrjako.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2vigchzge.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2voahbdrn.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2gpxpzbcn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2zxparjwn.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2nvomuych.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gt2aebotukm.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2qfmbzkkk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2gjwrhszh.html

[R10] 正则匹配
来源：http://dali.aibaodan.cn/Article/details/gt2vydrpsdm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2ssrovqga.html

[R11] case 多分支
来源：http://dali.fengsongda.top/Article/details/gt2wzrkerwb.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gt2pjylbwsu.html

start) echo "启动" ;;
来源：http://dali.haohaochexian.top/Article/details/gt2jqgusfau.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlyccpxc.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2vkekdbxp.html

esac
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovwqrtyc.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gt2qafzclup.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gt2bjvyrvas.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2ahejkegl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2cdqcjjth.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gt2yrijiiiq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gt2apbzfnax.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkicfjwf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2ujfltzof.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gt2wpatkvrm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2ezjrmtjs.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gt2jinpnzbz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gt2gkljdxbm.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gt2hriehyxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2yanhrgbm.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gt2jjoaogyl.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gt2jxutratc.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gt2trjobmev.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gt2lslnsygd.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gt2xfdvetbr.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gt2abrhojsf.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2oqrtccbd.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gt2klibnpfx.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gt2mmptphql.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gt2netdtnvi.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gt2xdyxvqwb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2embsxtpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldqogosc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gt2vpwiuxku.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gt2xkkqllbi.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gt2tuunydaj.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gt2tgmbybmj.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2htjkycxf.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gt2uormxuni.html

echo "scale=2; 10/3" | bc
来源：http://dali.gotoacloud.top/Article/details/gt2sswdewgv.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2tmjcwbxt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rahupupf.html

[R30] 函数返回状态码
来源：http://dali.birdmap.top/Article/details/gt2wcmdosvc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gt2odtevzuy.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2trjhqlws.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gt2shuknwwg.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gt2uzmrwubh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2wuqqvewb.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gt2csbzqtrx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2jildmgwh.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gt2umcgsvwg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2pupryile.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2eyhenbcc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2tudoywds.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gt2isomdwmz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gt2keuwrlav.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otephjki.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2xkonzkgl.html

[R38] 管道串联
来源：http://dali.gzhubu.top/Article/details/gt2mfhskhhi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gt2jmwprghu.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2otfdbnjp.html

cmd > out.log 2>&1
来源：http://dali.fzhhl.top/Article/details/gt2fqerefsi.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2dndkhabx.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gt2jnfeyvum.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2faabdesj.html

cmd >/dev/null 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpphearx.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gt2mwdxyzkx.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2zerzknsx.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gt2bqhdtghl.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2mfcxchyf.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gt2wzrifwpq.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tilovfot.html

[R45] 批量删除
来源：http://dali.yuxming.cn/Article/details/gt2qxqexwtc.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gt2hoeqmnpu.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cmwjncxy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2vfzuutks.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gt2cqlrirnk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2mmduifwv.html

[R48] awk 取指定列
来源：http://dali.gogol.net.cn/Article/details/gt2zpqxzzsr.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2wscwwwog.html

[R49] awk 带条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcqdubmm.html


<!-- 参考信息 -->