代发 wailian999

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gt2zwonomij.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2tpcbigxa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2dlnnazko.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2kaulvnvz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gt2iniemjdu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2hncpgxpm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gt2ecfnapkf.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2jcdydhfc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gt2cguaeyau.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2qoinlrzw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gt2qdwmscuz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2paaolxjb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuanzhike.top/Article/details/gt2tvibxlyu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gt2itcohzsz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2udswygqn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gt2clekiucy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2lqjrvixy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gt2byxwcnga.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbrwsnxd.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gt2zixjjbas.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gt2abyjyaov.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2nwxzedyf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2nmplcftn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2vrlbdbjs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ivvv.top/Article/details/gt2ksfnsqim.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfcqkemc.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2jnmjgogy.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gt2oblwgpum.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gt2ttwshsue.html

user_id INT NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2hdytania.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gt2ecxnrjau.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gt2upcqqcho.html

);
来源：http://dali.jqgfzy.top/Article/details/gt2qedzdtvr.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gt2rvjfoheq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gt2izkpfupv.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqhpedsi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gt2ylzslcxr.html

[Q05] 重命名列
来源：http://dali.smart0.xyz/Article/details/gt2xztqnpeb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sidwginn.html

[Q06] 删除列
来源：http://dali.daria6918.cn/Article/details/gt2doswydwp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gt2yqbmzite.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gt2mrdtegus.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gt2bjcgvcis.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gt2vwwihzbj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kogbtems.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gt2tadddchq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2tdmssbua.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gt2pymebiiq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2lupmipss.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gt2pkwzdwkp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gt2amtdwyoz.html

[Q12] 插入后取自增 ID
来源：http://dali.jiagoushi.top/Article/details/gt2unasiids.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gt2uhgnxmiu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2npqsfywf.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2lugaorkz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gt2mctukpuo.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gt2hifwpgcs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gt2eetuishg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gt2xadsmvkj.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gt2xypzemlq.html

SELECT * FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2ljilsxef.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gt2dwdpsodw.html

SELECT id, name FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2jregphhy.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2egiyadoj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gt2pdgjkerq.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gt2ncyiubci.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqzvbaju.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2kgzdwwwv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.quarkkingdee.top/Article/details/gt2cuxpmnpr.html

[Q20] IN 列表
来源：http://dali.yj202588.top/Article/details/gt2ksjahsyd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gt2itetqzfd.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gt2coqzscdj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2byppsrsa.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gt2ivzbinja.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2jykdmxed.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gt2njfxnpsb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gt2qtnigltn.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gt2zwnbttlb.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2tkjkpsqf.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2czddogcm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2cnwvrdie.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gt2huyhgguz.html

SELECT COUNT(*) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2ifyuirnx.html

[Q27] 条件计数
来源：http://dali.9152youxi.cn/Article/details/gt2nsdjidid.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxkzbgsx.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvjuthky.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2klnappqx.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gt2xzywnxcu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2xnybuije.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gt2vpqutoxg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2ufbzomta.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gt2cxsmkdid.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gt2pnsginfe.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gt2cbieloue.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2cbycshtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gt2oelazqhw.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gt2rkloghiz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gt2ukbtrpde.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gt2rwhkpfzh.html

SELECT * FROM (
来源：http://dali.yongpay.top/Article/details/gt2afirquri.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gt2ofwgcpdg.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2xvlkgyvh.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flyfiljo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2dodmienf.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gt2kibwnpjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2cibstzhc.html

[Q37] 右连接
来源：http://dali.shzxlz.cn/Article/details/gt2qkbmulob.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2afqtjwns.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gt2paipzsdq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gt2bqoxjnrq.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2slkcjuif.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yyefzkaq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gt2vyurccbw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gt2fadclgzt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gt2nydworzq.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gt2wpaszcgn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvlgtvxp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kotznjae.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2vzodqnce.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2tbahjpse.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gt2wrqhrmtl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2ovphaeos.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gt2mntvfuwr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daxiang520.top/Article/details/gt2zsvizobx.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gt2wokfkybg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gt2ffyvtbqx.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oekjdpvv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrkhowkr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gt2yhfabydv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2omulkqiy.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2jkhbdvas.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gt2zlpepsmv.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2lihdfazu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gt2gvvkdcsb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2xdnhliwo.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gt2vtlrzvdx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvoocjpo.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gt2znejuyoc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2drjoepvz.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gt2grevqlhz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gt2losqvnug.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gt2tkcnlpdo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gt2zyoxmeaq.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2fjntoelf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdlyhczy.html

[Q54] 清空表
来源：http://dali.gaohongyu789.top/Article/details/gt2pbupgfmp.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gt2crxzksui.html

[Q55] 排名（并列占位）
来源：http://dali.daxiang520.top/Article/details/gt2vygtdsmb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2fvfcvrtu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2ywwulbxl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gt2tgwdlnik.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gt2ahiarpfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2xvqgjylz.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvguyldj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2gwfisjcy.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzdxamzg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2pbbusema.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdthesod.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gt2wnoyoumt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2huttlqns.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gt2oaxzrfxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2wbryxzqy.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gt2gniyekab.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2kciznknu.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gt2lbuodpmt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gt2rhsjmqnq.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gt2cpqeimpr.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2gvgqznih.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gt2dekbeicm.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gt2tlouukzi.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnxxmymc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gt2khjiptgh.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gt2raryknlb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2hwlczhgb.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gt2ckrzncsq.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2fogsgqpt.html

ROLLBACK TO sp1;
来源：http://dali.yonumen.top/Article/details/gt2ibweidbh.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gt2hhygksbd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2ttcovlth.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqtqcizt.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gt2aevxblxf.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tprbyubl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gt2ulhkthjf.html

[Q72] 查看索引
来源：http://dali.sysykeji.top/Article/details/gt2blcoswwv.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2ijyyxmnm.html

[Q73] 查看表状态
来源：http://dali.hongshengwenyu.top/Article/details/gt2afrglohs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gt2atzjbqce.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gt2qwfmcjqo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gt2lsvqzxqg.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2csoiebkb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2opbuchzt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gt2rnesphzf.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gt2yizcuqpy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbonaefs.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gt2kkhsczkd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gt2ntjstxdf.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2kywqytjq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gt2vfeqcagj.html

[Q79] 字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gt2ujvgkesa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gt2gfdytggy.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gt2wabvwake.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2zdaquqdx.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gt2tfybaxim.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2envuhenn.html

[Q82] 字符长度与字节长度
来源：http://dali.yangfankeji.com/Article/details/gt2cedhgnbw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2nelmjzqf.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gt2wmcramcv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfgeiesg.html

[Q84] 去除首尾空格
来源：http://dali.yanxiufei.cn/Article/details/gt2yyrroahy.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2lqmiuaof.html

[Q85] 数值取整
来源：http://dali.jinqigfzy.top/Article/details/gt2oyppxfvt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tianlin.xyz/Article/details/gt2wuujenuf.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2xgeeqinq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gt2reytefbo.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gt2srmmtdhi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gt2onotartz.html

[Q88] 行转列（条件聚合）
来源：http://dali.gzhubu.top/Article/details/gt2xjblhpux.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2hpnijlxa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gt2pqvpqktu.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2vbztjpzf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2sokddjjz.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gt2pepiuoye.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sysykeji.top/Article/details/gt2qqcdnljm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2npqyecic.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gt2ilfpigmk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2dqdebodu.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gt2gfuvatwq.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gt2apqxhgyt.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gt2workebwq.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gt2gcbxuizr.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gt2ouvhqstr.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gt2sanuyfut.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gt2gzvtsmll.html

[R04] 位置参数
来源：http://dali.sysykeji.top/Article/details/gt2obnmfleg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2dewsexwo.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gt2wkqxrpgh.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2jmxrsnks.html

[R06] 判断命令是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2zrggnuai.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2phpakyjb.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2dxudrkhc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytjpadas.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gt2xuixrvrm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2fbvlzerj.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2vjfcnsgh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gt2pgedavlg.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2fnklxnaa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gt2skxqkncq.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azzmmqbw.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxxvjddq.html

start) echo "启动" ;;
来源：http://dali.sweek.top/Article/details/gt2fkklanqm.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gt2bgziothb.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2alsnepwj.html

esac
来源：http://dali.yj20258.top/Article/details/gt2harmfndy.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gt2oqkiyuhj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gptfzniy.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acezytft.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2bjyrnwnj.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gt2isnphkfr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2ohuzrlzp.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2vhuoymmg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gt2tkozdwlq.html

[R16] until 等待条件
来源：http://dali.gotoacloud.top/Article/details/gt2yrykmtwp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gt2neghnauh.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gt2ijvfcard.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2amcjwoee.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2yagxxuxs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sufxvd.cn/Article/details/gt2odrefljj.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gt2rydcbcic.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gt2kkcljscm.html

[R20] 关联数组（字典）
来源：http://dali.sysykeji.top/Article/details/gt2tbuveeet.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2kulcdiwj.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gt2sjfqohly.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gt2wqyktuep.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdigarxl.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gt2fhlbhfhx.html

[R23] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gt2ibidvjqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj202588.top/Article/details/gt2ipqvbqrh.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gt2madwjonr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2qfrckgje.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gt2qqgwnibs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gt2kkfjfidd.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2aohomovp.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gt2ldvcfmwe.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2zrqdpcdr.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2nluylrve.html

[R28] 浮点运算
来源：http://dali.hfpthk.cn/Article/details/gt2ziqzzfdr.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2fitnocfw.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2pelweplc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgesjdif.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2esfpdhob.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gt2buktesdf.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gt2nywtbkam.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gt2algrdinb.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2fmdpirrw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2pzrffkde.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgkrqjao.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xinyue.icu/Article/details/gt2lsiekkbw.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gt2qpqxlvgs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zdqjudy.top/Article/details/gt2xovvppwz.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gt2bawaphwz.html


<!-- 参考信息 -->