代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gt2quedgrhe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zswkmmtv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2bvkefsnd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkykdqxm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2aadplsxr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gt2kfjyexzz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gt2nhnrtjck.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gt2aotrtnuv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gt2prspenna.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gt2wtgyymyk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gt2pfvmpkho.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gt2zyvbgrvh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2myfwtspd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgyolzaq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gt2lzuavkme.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gt2wnxmsliu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2zspsptaa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gt2apvzpgua.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ulugsylg.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezkehtxo.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gt2siiltcls.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2ejtahxoz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2rxweixek.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gt2pzprbiyn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gt2dltdxtnh.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2chzinviv.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gt2evuoondb.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2truuubjr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edaxmehv.html

user_id INT NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2eohdarln.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2ubjhzfap.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gt2zqxmgffz.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2fcceqtjn.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2xwptlirf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gt2awosclkv.html

[Q04] 修改列类型
来源：http://dali.yuxming.cn/Article/details/gt2rpgswtjz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2viinzgrp.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gt2cjotrdrq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gt2uaibanel.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2rnbthcjr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gt2qschybyz.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gt2xfnoczed.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2rfsvxves.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gt2xxzvqtsa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crjpakdy.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gt2aeknkwrw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2fgnilqpm.html

[Q10] 插入单行
来源：http://dali.yangfankeji.com/Article/details/gt2uxtryixp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuanzx.com/Article/details/gt2yokmvvxp.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gt2hzhjiqeb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gt2nzhfsver.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gt2rwaanehl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2vnyjgnba.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gt2khbblfoe.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gt2abmhgkdl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2espjdrcr.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gt2aawypeiw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2jheglpby.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gt2qhmochfo.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gt2mbecgjdg.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2fdlyjucm.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gt2bgqgdmeo.html

SELECT id, name FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2wnbnwxjq.html

[Q17] 条件查询
来源：http://dali.jinqigfzy.top/Article/details/gt2vktgclvn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2gvaeqgbz.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfjgqpei.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gt2hjxxdgjp.html

[Q19] 范围查询
来源：http://dali.shuidangran.top/Article/details/gt2ygrmcaom.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gt2pmyyaddf.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gt2bfyzbnhy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2swkhdgjx.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gt2cztowlis.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2owjfqtwt.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2sgzfzfiy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gt2uwyhuvms.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2tojbmykd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gt2zkrhihgr.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gt2gxozswmn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2jsoiults.html

[Q25] 只取前 N 条
来源：http://dali.aizwys.cn/Article/details/gt2pafazkct.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eyelwfjm.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gt2rjmbvrjk.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2tecjkomb.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gt2futtjlqv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2newwzcmz.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxhhuttn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2meuvxjhq.html

[Q29] 最大最小值
来源：http://dali.jinqigufen.top/Article/details/gt2mjvkprtd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2jsvyexzi.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rgxcjkae.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2nqnzrser.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2yaexohyq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cashguo.top/Article/details/gt2iosllktc.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2nhpqjwgj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2skdkyyvc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vobsehfv.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slugrmyq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gt2yzbcsmut.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gt2fxqokday.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gt2zvqjrvay.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gt2kuregxhk.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gt2pukbihni.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gt2khbvvqvp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2xtuiytbp.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gt2tsygsuui.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2vlqcxnqm.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gt2kbfhnghe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gt2unwtexnm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gt2meunhzya.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phgdidgz.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gt2mypnzntu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gt2reluptsa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gt2iwthvdwo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2qgfddwgo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gt2lxrfyhos.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2ecaqthde.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2gfccingn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gt2srtlerjs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gt2xlpyztdk.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2unhtvdbf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gt2lqvexlqk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gt2twwgidnt.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2xuiixklr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gt2ysncmdli.html

[Q44] IN 子查询
来源：http://dali.svipenyu.cn/Article/details/gt2nckrfswk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gt2bytwppyr.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gt2pbghxwhd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gt2cyzrmtqf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gt2atxdxfgu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgvfznxj.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2hdulklyc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gt2jrulilvo.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gt2nmifjoqk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gt2rjcxyqrq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gt2cxemjqbq.html

[Q49] 更新单行
来源：http://dali.hammf.cn/Article/details/gt2pkrscptn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2rjetksfa.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qeswoztp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gt2mdlkddeb.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2nemkxnpv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2jymtumvr.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gt2zjzhclzi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gt2djmtuimy.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gt2zjgbcyam.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gt2wlpgezcg.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gt2ymnoesji.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gt2lplqgrff.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gt2obwjjook.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2upkpntlx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gt2kjcemtma.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gt2bcrvhgbh.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gt2kcviidwr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyhrkgfp.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gt2ikjffkkz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2lnvhenzg.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gt2obxdtrke.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2iwtwycff.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gt2oppvsuce.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jianghu66.top/Article/details/gt2xaqgvhjm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2sortnbxf.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gt2hxqmwewt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2ernqkcbk.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gt2jhujjvoo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2mavazswx.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gt2skxomueu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2nbyxiuin.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2anuhaudv.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gt2ffjgdrmf.html

[Q65] 回滚事务
来源：http://dali.iojbl.cn/Article/details/gt2ejidyujo.html

ROLLBACK;
来源：http://dali.meibo888.top/Article/details/gt2dxkeripm.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gt2bugzvavz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gt2pzchvasc.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gt2bkebieeo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gt2xdvklbpn.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lslykjxj.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2cgldktbj.html

ROLLBACK TO sp1;
来源：http://dali.zhixingplan.top/Article/details/gt2zfbhahfh.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2osllemsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gt2wydkluvs.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gt2ahzrdjxx.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gt2rurnjebr.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gt2ctewkbmp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gt2vbyicnbx.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gt2cdkstrji.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2hzpihxue.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gt2opizlbdg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2rqmsajrz.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gt2zqmgyunz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ydzc1.top/Article/details/gt2ttwxjphg.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omlzoicj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2bwqmxjuh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2qtppwcnn.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gt2gtohdykv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gt2foonpttq.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gt2dtsambhw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gt2lspkrjrl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2reksczsr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2aldmerds.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2csoypadi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2vmlrdzpp.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gt2lnoazkgc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2reyjhxkn.html

[Q81] 字符串替换
来源：http://dali.svipenyu.cn/Article/details/gt2pllsypwp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awagvknu.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxinkj.top/Article/details/gt2gwhvouhb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2emrpbkuf.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2qwujbsjj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2qlmocxzr.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gt2eiufwfbv.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyodwgdl.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evknpnbv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gt2qnfgpuqu.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gt2tvkboczi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gt2mbucbfbr.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2tojgvvyl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gt2nyiopogv.html

[Q88] 行转列（条件聚合）
来源：http://dali.redwolf501.top/Article/details/gt2myolxcud.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqwdcgcg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nivdjles.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gt2gcbwoarw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2evchikva.html

[Q90] 生成序号列
来源：http://dali.zhixingplan.top/Article/details/gt2pvyvndie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gt2ikiksmff.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2hevcgptu.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gt2fvobyrnt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmegandc.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gt2clfxmeyf.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gt2ocuqgiyz.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2xuvgfktl.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gt2ilmvbbnr.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gt2keuelzbm.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2mbfyoghb.html

readonly PI=3.14
来源：http://dali.xziqi.cn/Article/details/gt2wayoemmc.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gt2ddqwjblt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gt2ldgydxza.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2joodhukz.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gt2uunatbxo.html

[R06] 判断命令是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyxlrfvu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2phugzoho.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gt2rizypxlr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcejzgue.html

[R08] 数值比较
来源：http://dali.vqdsnc.cn/Article/details/gt2lfafsqto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gt2luyghuwr.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2dyqrpoog.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gt2gcvjihju.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gt2ofkblsld.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gt2knruidxs.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2jsrpsobv.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gt2xjkxovix.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2ckxfefcq.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofjedyit.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2msmoahac.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2tcgyglwv.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2ygkoghyd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2omsbyxhe.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gt2spazzcle.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2oavzvqjn.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gt2fobkryww.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gt2mpnlgxun.html

[R15] while 逐行读文件
来源：http://dali.guannengcc.top/Article/details/gt2pzjzkbcx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gt2ihkukapd.html

[R16] until 等待条件
来源：http://dali.ehwqpu.com/Article/details/gt2miyfcekw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gt2rdraeoqi.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2xrtjioye.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gt2vlnugtyo.html

[R18] 遍历数组
来源：http://dali.yanxiufei.cn/Article/details/gt2bofzeorp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gt2hqeaokwc.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2qbtwtfeg.html

echo "${#arr[@]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2umoxmeow.html

[R20] 关联数组（字典）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eusptvrz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dashuyun.cn/Article/details/gt2iqhwntpp.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2obyyfobd.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gt2rzsbsaod.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2xindixes.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gt2audzjxfg.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gt2baltpmfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gt2oiidqpvg.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2oftgwoua.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gt2igdzefcn.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gt2ryrajjwy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2kmsmgcfq.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbxotfjd.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gt2bagpjyzb.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2hgnglolb.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gt2dgkadorz.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gt2hngubziu.html

echo "scale=2; 10/3" | bc
来源：http://dali.sweek.top/Article/details/gt2zqfffcop.html

[R29] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2azndrzbh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gt2ybkebnpj.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2efjzptag.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gt2jxdfpply.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gt2derfmujd.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bfdyhchm.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mommvigv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2kcuxcyvy.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gt2nuyhbrji.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gt2lfyhwcuq.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gt2yzpexqtc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2nrahtydq.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gt2snxnxxip.html


<!-- 参考信息 -->