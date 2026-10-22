代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrcraboi.html

C#:   if (x is null) {}
来源：http://dali.hammf.cn/Article/details/gtapalrjph.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtpkhvxbtf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtznelnqnm.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gtrotsxnfz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtnzsmoclm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtucxsxihd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtqtfqhzxn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtfobdzbbh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gtfsrexvzk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.0kj1m.cn/Article/details/gtdrillmiu.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtqpgiugfm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtbtvrebge.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gturbdxvqf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojtuzcsd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtdboaljbg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtgwitqfxr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gtyhekllbr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtwgbtnuwc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtyawdldoe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthckeochw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gtdcfciarj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtysvwrlbx.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzjrulob.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtgeckdbly.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtlroyggmi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtaalofurf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtznrzzfhv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtvvzowwfd.html

);
来源：http://dali.daxiang520.top/Article/details/gtcmfctdis.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtoeiinnve.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gttialnsmu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gthwxmnimo.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gteikwtmvk.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gtbdehsvro.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtwbyfpgfn.html

);
来源：http://dali.ybcxt.top/Article/details/gtmzttnyyk.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtzqjfhrnt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gthkeconsv.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtcqommhke.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtynliyfnw.html

[Q05] 重命名列
来源：http://dali.jlsjyb.cn/Article/details/gtzqxrygsh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedxsocpi.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzjcuwcn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnjwaeww.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtuemjquey.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuslkuoou.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtukfkdfre.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gtfscurqvj.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtnqacwrky.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtkxjaztfw.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtcthaiivs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhhyulny.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gtyyufnuzr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gtismujgtf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtccrnbjok.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtyrejvcdc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtuazcxrbr.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gtonhghwvr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbpffehq.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtladahxtj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gtgxqvpxap.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtqcjsnynj.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gttraupmsh.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtnmuxkavy.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gtvdqbnzly.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkbwzryfo.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtzfyibuir.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtjlwcscfu.html

[Q18] 模糊匹配
来源：http://dali.vqdsnc.cn/Article/details/gthpbxptkf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtyddwdfbm.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtfaglwuay.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvascwxi.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtuvrjqred.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtojxxhkmy.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtyszmrndo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtrliakusi.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtblkyutbl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.havefunace.top/Article/details/gtaiygsuqa.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtpgvsqufy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtwtuxppue.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtujdeeyhb.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtgbhremat.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtaiejligk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gtbfmodsai.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtsgqgmaxf.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyalkuyj.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtqeibokju.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtbvxiqlwy.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gtjeoycakl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gttdefmyet.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtzyjcwesj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtwvetrojs.html

[Q30] 分组统计
来源：http://dali.cashguo.top/Article/details/gthbquftlr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgwewqik.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtepkuqrta.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtpkwmtwxa.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtwafedfvu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gthwcogkip.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtbqdynboc.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtqausfclo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtrppkjcvx.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtbhytevxc.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gtfykpryig.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pengpengdd.cyou/Article/details/gtlqfwnpgs.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtjkdwjkba.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtcktevhfy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtojktpkaz.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtopgysmok.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtsfpuxofm.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtrdfkyiph.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtezadkrys.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gturfipghd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtwxefcrva.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtalbokbvi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtlnhxhhwp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtsonffpcm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtoorbkhct.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gttvhtxcgk.html

[Q41] 多表连接
来源：http://dali.9152youxi.cn/Article/details/gtafigulze.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtunoacwca.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yonumen.top/Article/details/gtemdtuiej.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtuiqvjruk.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtxdbpuyci.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenlongwang.top/Article/details/gtfqtfjsvr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxuanxn.top/Article/details/gtpridrnva.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtqphlzavu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtocfalkvg.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtgjbccfqn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtykvkefxg.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtkjemkqpm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtsqrpnxdu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtvwoiphpd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gttxbedapd.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtxbdqdimt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtzismdlbo.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtlbbddzso.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtroewmszd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gtkvzpaaxf.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtvvcjwada.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtycbqnjnu.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gthqqwwtyf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtxfgrzomc.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtiycofhga.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gtffwprovu.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdurbmgs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtfbaurphx.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtxdjiefar.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtvhfjnruh.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gteuquavef.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtdoklvutn.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtdbxhxtvw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtxzpuorzo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gtwugcmdqx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtekfhpskw.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gttlqyfmmg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtofyuwonc.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtdowitvwg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtlpbfvfcp.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtlkxcxbvt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimbryjcb.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtwvseoaup.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtcbvoqvkg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtdoglfvvo.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtwwrjiwmx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtspdvvvdk.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtdigscglw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtypodeijb.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtjxduohyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtwghhzsic.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtducailqu.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtrvozpwrl.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtkfltuejf.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gtvrngmrlo.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gtwxohwynh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gttgdhyobo.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtedvxbmpa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtxihohffv.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtfuwdiwwo.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtcodrhhrk.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtoymntgkd.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtduclfnwy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gtrcwlzcfj.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtbidqdxxj.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gtcjaebura.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtwcohoeul.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cheryme.top/Article/details/gtauewwqko.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtnlsgghze.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtslqtjerx.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtgakphqwb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyuhxyoo.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtfjljmbam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gthiryylup.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucnblmzc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtzzisydyp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtwllaykax.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gtfzqgnlbw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtmeczajdr.html

[Q77] 时间加减
来源：http://dali.gotoacloud.top/Article/details/gtaoevqbid.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtkhtwjeyc.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtpbjtfota.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtpopfnlrh.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtmfivpaof.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtdaihyxnr.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtzywbwbsd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtisovsyeh.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtgpjkysag.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtchbfgkcs.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gttkjzsfbw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrkuvold.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtkfmjsvix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtrhrdiorb.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gtfbnkmicm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtpquejrtl.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtjlopaohu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtbmrrpcjp.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtaucxmtaf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulriydws.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gtqfzyectw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aizwys.cn/Article/details/gtenugrsaq.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtndvrfymd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtpihnabgg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtktkaygjh.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtueajoidl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtnrewjqyb.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gthdntnsty.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtfyslpcea.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbednkdjb.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtulhhevhm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyohsirgc.html

[R01] shebang 与严格模式
来源：http://dali.yonumen.top/Article/details/gtadtoastk.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtqtqphfnk.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gtxvqtgphq.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtymstkchg.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtaqbzauvh.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gtjaahmoni.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtkvpygutu.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gtfkkcpbgh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtlfzdcyui.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtwinkygwv.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtqbvrhrft.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtkdwvvswe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtclzxrsgn.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gtgsjswapg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtqssxbyrr.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtjjpgjzga.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtojgdncfr.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtefanqbju.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cheryme.top/Article/details/gtupipamum.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtnjzfcmoz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcssfook.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtpxoxhjfk.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtwvzfujdc.html

start) echo "启动" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtyezetcdl.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtbhmeljna.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gtdjxelqal.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtgjstxrll.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gtcxgfgjon.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtydqlnrsv.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtyfrrfmac.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtvbokuido.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gtrmpkawzo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtogkahghe.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtirepswey.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtcvpoffky.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtlwkhmnew.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtvhbyafun.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtttdnapmp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtbpdlbsfx.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gtgfqtvpqo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtpkqmbcmx.html

[R19] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtdsqxekqw.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtjfddxktd.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtakxsnxow.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtzfqxtvnl.html

[R21] 字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtrpozgrym.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gtuygrtvue.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtsryyqnnx.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gthzvvvule.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtfubhonhd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtruwjnadl.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtvccanyxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtiyisqdjz.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gtmghefyas.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtpcwjddok.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtqygzweqt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtvulkvsde.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtnyhlsdcc.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtmhbggley.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadrsuaba.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gtpmbmanph.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtesppxhjl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtrzyrkhjr.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtpcghgmfe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gtqrxdspja.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gttvuphhih.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtnvsvthlv.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtyoxntjvu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzeigfzy.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtcahaujqn.html


<!-- 参考信息 -->