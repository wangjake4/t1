代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gtvkeidiuq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzyvchtun.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtaaaagvlp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtnqmdgmdx.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtsdarsluh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkyxrfq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeiqivha.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gtojzhgzfh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtavlzqoti.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtuojahsmn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtthwezbhn.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtesohlflv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqdhdfdb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtfboxuxul.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gtqsimmpdz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtbxrtamwf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtrngclmuc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtbzlfyest.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtslceeigl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtgfitshub.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjltoozuw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtsjtxarnl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnyrvvinc.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gthiowgdcr.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gttsaynqvv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtnnezsukm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtwycrbgkd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gthtlinjqq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtmcuhgttk.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtkrgbmiub.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtdebwhuth.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtplhgorsx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtirpbzagv.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gtlqiyckji.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtpeiwfyvf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtsliztzev.html

);
来源：http://dali.cdnleiting.top/Article/details/gtrxldmnvf.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtaeklcpub.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtavkfryxy.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtjdbzltma.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtskzpkfwi.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtilogsmrw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtmtzypbwo.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtyjyxzyqv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtfnpnksrq.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtjrkgokco.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtuctgsjpw.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtlqflfwmj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gtkqphukyp.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtbcldydxc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gtlsupqmnx.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gtevovphin.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtisktywkm.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtkfvnwqsz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtryswizhq.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtfdhvidpd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xinyue.icu/Article/details/gtygpivjmp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gttfmxeoin.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtbpmizagg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtocvhfcyf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoualmpxc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.smart0.xyz/Article/details/gttnoauhfj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtfmnudgyq.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtoywioprg.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtutqxtkwh.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gttfxxduad.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtauigclts.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtozvpktaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtzawyrxxv.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gtldxbzoet.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gtuoqoajpm.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gthpgdbxlr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gogol.net.cn/Article/details/gtpuskgnzo.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtxstgnbeb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtwqmmlxhl.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtpqgmqgfl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtsfjnbysj.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdoclxbmh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtpxdbvfdy.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtupskjrif.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtmgvyrowt.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gtvtikisrl.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtnbjbrdkk.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtfklxwjyp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gtqdmfwezg.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtczclzgvo.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrdqovnig.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gttjkknxig.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtgmrfixfx.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepfrypqo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtdfiermsr.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gttgocvuqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttcjlvgut.html

[Q30] 分组统计
来源：http://dali.chenjidiqi.icu/Article/details/gtkfeydwch.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtdpqvqmqh.html

[Q31] 分组后过滤
来源：http://dali.xuanzx.com/Article/details/gtaqywfscz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtjobiqibm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtqweffsra.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcmfljlc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtrcxpdlja.html

[Q33] 多列分组
来源：http://dali.zhoulong.xyz/Article/details/gtgtrehknf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtssvzxarl.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtscubuxcs.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtmqmwtgaw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtdbxqzqzn.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtmtdwhepf.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtxndptzan.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtmddmwpcg.html

[Q36] 左连接
来源：http://dali.c1oappe.top/Article/details/gtkcwurdha.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtkjfddhbq.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtnfjybpnl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gthrpbbrjf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtvshqmuez.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtepdztupm.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigfzy.top/Article/details/gtsbixjnyq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gtntjhosix.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtaprzflim.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gtpzwglsjs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtfnxpddwr.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtbsbwejbm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtxspkomye.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtfvspqvzc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtdpyfkhws.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxjitvou.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtvddxfvcl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtnezveupg.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtvtaxewkw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gtmyjtteyy.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gturhdetoj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtdlapcdlm.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsevlffg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiubzmbfz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtorrxdwzv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtzbzxipfq.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gtlydmeavq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gthnoxzivs.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gthlvexgrz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtagwqlpsm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gthgeoaqyq.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gtcyoenjfs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gteckjfhkt.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtmwsixcsw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.snrcjt.cn/Article/details/gtrsdrcyny.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtkcnfrpvr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtykpruoaa.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtwminltwx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gttmlrfqla.html

[Q53] 按条件删除
来源：http://dali.yonumen.top/Article/details/gtqunbmodq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtwuoprirn.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtzitahoij.html

TRUNCATE TABLE logs;
来源：http://dali.yvedp.cn/Article/details/gtapaeqnqw.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtsduxhrir.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtmecjjjxg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gzhubu.top/Article/details/gtjrypncjz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtjihbdfam.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtuvepopoa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtcsubxtpg.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtovrnptau.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtrqcmqlun.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtipdeipcg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtmajovckx.html

[Q60] 取上一行 / 下一行
来源：http://dali.birdmap.top/Article/details/gtinjlfolg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gtqxsvlvjn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkvzistn.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtvqkdctez.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtvsmumeyz.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtsonajxby.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtbaajcqkw.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gthljadlik.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtwlpeifkc.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtrrtzrmuq.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtdohnahuj.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gttqkwfbum.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtgnkqiaqq.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtvogbebes.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtmpinsphy.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gthrrksasp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtzppqqext.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gttoyfrwtm.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtjkgfqdhe.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtoiedonae.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gtvnfheiry.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtrlfvcpxz.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtygjvkiga.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtexwejotc.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtqtlikiuo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtgdaclptn.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtgilzwwxw.html

SHOW INDEX FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqimrswjf.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtgalgbuoh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtihgfgfgd.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtwtcxkgue.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtuqisjwks.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtjsrqsbzi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzdauagv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.feifeiyinyue.top/Article/details/gtioietddi.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gthkqnpsvu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthanawxbm.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtxpwqnfhx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtukvfjxba.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtzoeijxub.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtwymnicsg.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtcocesspo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jlsjyb.cn/Article/details/gtgmhxkuut.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gthunvtndo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtlcbfsphf.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtadezxeev.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtwpamulvk.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtktyrvwck.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtrozxznir.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtjnxewwuh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gthgmyejeb.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtyeqfkyua.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbosozuzy.html

[Q85] 数值取整
来源：http://dali.nanxinkj.top/Article/details/gtalmjjvup.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cucudq.cn/Article/details/gtruiocvhu.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtmrvqivkr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtxgarahgl.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtiyutonat.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfnxiooi.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtrxranwze.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtgvjjwdvt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtgedrvepc.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtqtkqreib.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtieijdgrt.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtapwszlea.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtbrpevooc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtatnultgl.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzaybwmj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqtlemyo.html

[R01] shebang 与严格模式
来源：http://dali.jqgufenzy.top/Article/details/gtdulllzit.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gtcjklxaze.html

set -euo pipefail
来源：http://dali.316326.xyz/Article/details/gtijfgnfzz.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gtfvhkvwvd.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gtqmsgocrq.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gtgrfddwub.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtqckpwybp.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtlmgkvnzf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtwxtqkrtl.html

[R05] 参数默认值
来源：http://dali.jinqigfzy.top/Article/details/gtsasmrqcy.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtrdtvukrt.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtyahfjrqg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtmujjwlkw.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtdmudxvxd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdsnequu.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtsqhqzwau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gzhubu.top/Article/details/gtghhxzdfc.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtntknqsfx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtsxvtfxvj.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtouytekis.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gthenzixyu.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtkvrrycki.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtixfjzits.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gttawkybmc.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtowshiedi.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtrcsivekn.html

esac
来源：http://dali.sxryk.cn/Article/details/gtjihjxoke.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtjtncleec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gtjsxchbfo.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtcwzwxshc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtgdiumyku.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtaefdsqji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtpoteuija.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioqxljpb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.redwolf501.top/Article/details/gtuvxgkdsy.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gttuvjftuk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtytaisjvp.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtsrcunqgt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.iojbl.cn/Article/details/gtythuqbzc.html

[R18] 遍历数组
来源：http://dali.nanxuanxn.top/Article/details/gtexnjsbqf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gteapsalbc.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtiyvqyeeq.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtjpgeawfh.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtqulnqgqp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtrmzzkyww.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtwufhxist.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtvgintgch.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtehrqzdom.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtoenkxxjp.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtkmvgcxxp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtnazcdjvk.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtguddxvbw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtliobroza.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtcloqrbwn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gtqopcwwmi.html

[R26] 命令替换
来源：http://dali.svipenyu.cn/Article/details/gtyuloojii.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgufenzy.top/Article/details/gturomkfhc.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtglkxckvl.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtasspopzg.html

[R28] 浮点运算
来源：http://dali.wangdashe.top/Article/details/gtouxzcvfr.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtuaiahgma.html

[R29] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtndgyaspr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtjhklbxir.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtztlcncdi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtzxnbndem.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtylydngfg.html

f() { local x=1; echo "$x"; }
来源：http://dali.jqgufenzy.top/Article/details/gtmhochtae.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtlxucovre.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtpcptxzzu.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtfletudfz.html


<!-- 参考信息 -->