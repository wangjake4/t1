代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtqoeixkuo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shuidangran.top/Article/details/gtcfzqyyds.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtsysepsmu.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtkllaylbd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yueranfly.top/Article/details/gtzxhmowkc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtnhrcakey.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtftmhibtw.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gtxsifjcuf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtbypkteeq.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtwxzlwnyt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gotoacloud.top/Article/details/gtiiosjxzn.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtuyxmkssb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gtwkpnrnvh.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gttglodsks.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtohipjonp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcqdmyhc.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtskusmhde.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtvykmyrjo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtprhrqiqd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtzukmvzdo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtzrkgcqul.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtrveknjqj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ppjwa.cn/Article/details/gtfdvdgbus.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtddatnvtd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gtpztokmiz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtaqyhplmh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtpzdxlmqi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtqejeihdr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtndkqywwq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtbbbqsmgn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gtmcsdwasu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gtwhcybxpj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpbryrqii.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtlevuligs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtubxpnfpj.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gtlfgqmgsr.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtkdneqszp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtlwdqmgwz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gthvwfvbfe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtuqkcoray.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtxjpdlkqf.html

);
来源：http://dali.svipenyu.cn/Article/details/gtezpnepvs.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtvsbdxfyb.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtzygnrvkq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtlpzemqcf.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtqlycazzb.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtqxieqvbw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gtkwtmulrr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtzdurwdat.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtdbjzsnxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdsprnqf.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtyoqkjqkg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gtcmeuctmg.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gthpnhfkro.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtcbbampai.html

[Q06] 删除列
来源：http://dali.ivvv.top/Article/details/gtmkenxvdj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gtbaywmkyk.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtmcrdgktz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtjktzpspo.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtfpbiqogq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtkojnvpgx.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtmlghebqp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtfnrzzths.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gtbxzmwpab.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykqdbhub.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gthidefdxp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtlabjipnb.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtfrjqtiez.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gtjrpsozub.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gtqasyaooq.html

[Q13] 忽略重复插入
来源：http://dali.tanke756.top/Article/details/gtraaqqxjo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjgdaqkx.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtwpkqcjta.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtigtmhhow.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtbozfoywk.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gtiekgiyee.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtgckvcdhy.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtfcgcelql.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvqxoxtzw.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtdbmcgtjo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gtgtmnamcr.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtqhbrxjpg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gtkwxhubjn.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtcwkbssjc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtgbhbpnvs.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtgaelbqgj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtdudahaib.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtxscukbhq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtpdbudlvc.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtkoanlmad.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gtwpzszknb.html

[Q23] 分页
来源：http://dali.jianghu66.top/Article/details/gtincatgfc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gthfujwzjw.html

[Q24] 去重
来源：http://dali.xuetiantiany.cn/Article/details/gtqxqrkbze.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqjxbopsc.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gthbrxyqsa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gthqpjevvr.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtwoaacpoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtmzoxlhgl.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtuxzuqxun.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtxakuffvp.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtxjtkkfqa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gttgtlvsgt.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtffjrypqa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtptkhblrq.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtfsissvxu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtlfxkudtp.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gtfwxpihyy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gtggnitlro.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtdwfbxdhr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtlhlajmaz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtdsnxyadm.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtszmhjvcq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtbkjvysms.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtuwocvvoi.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtpgxkoxia.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtsivxgqmx.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtbqvyllme.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtgvqajgwf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtkvlqzkbq.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gtprvwqhkv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtkwzzwtfi.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtsintbcqs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtujgdhcdz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtnjxmfhle.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtsrcljyca.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtcbbqmmqr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gtewaxhvyj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtcbdnxhjr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtfcvjkqnq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtkidgdvto.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtopsivzae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtqubvbqje.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daxiang520.top/Article/details/gtczhkrrqp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtkghesvou.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtmnucsasv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenzaomai.com/Article/details/gtymzkuxwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gtwuzkgdme.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtadsrqbtq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtdldxoqmj.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtswbugzoh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtxwgeybat.html

[Q45] EXISTS 判断存在
来源：http://dali.chenlongwang.top/Article/details/gtpwmxwqjt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqeocxgh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtkpvbuyxn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtbhtximma.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtidkxarcx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gtpabpxnff.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gtgmfpvtfh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtrzgtixbf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtxvrpvurp.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtflufgxgk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtvswsxuix.html

[Q50] 批量更新
来源：http://dali.jlsjyb.cn/Article/details/gtxoeiesak.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtawvsnvgi.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gthmezsdrj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtpncoiocb.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gthewunhgy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtaznohipo.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtlbjszlko.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtvwmfgeug.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtscncbsro.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtlbywvznv.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbvwncio.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtgzlaztnz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yonumen.top/Article/details/gtategtsnv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzienjvp.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtpkozgfot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtekjpaavk.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtyhftvzuz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtxmkpfdzt.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtdacirjuu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtlqlzkfgz.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtoyavcpxj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtybsxvrbj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gttinfzgrc.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtluukflzg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtabxxzwtw.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtrmoqjmdn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtxnjqocjn.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtvwpyzylv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtcyogtlhy.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gteyjkutks.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtkdfmwibu.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtwgjccniw.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtpaocfynr.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gthighajsu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtynsoujyt.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtdneenkuv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvaxnyif.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtdhbjcper.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtaxxlgdlu.html

ROLLBACK TO sp1;
来源：http://dali.ydzc1.top/Article/details/gtzvytmmjc.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtvydctrsw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gtkwpsszfr.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtvbrvcohs.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtiaszizzo.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gttjiyjqmd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtsywsxvrs.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtohvdbdcp.html

SHOW INDEX FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtfqspppxv.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtibsvjnic.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gtrctltzvd.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangtech.top/Article/details/gttyubivqk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gteqjfbvlq.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtstvqmoua.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.316326.xyz/Article/details/gtsgrxstbc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jlsjyb.cn/Article/details/gtkoykgxmn.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhblohgo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtqygsfzab.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtfxsylliu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtugpeonan.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtzqrpsyrc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtgwxmdzlq.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtqcxakhrl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gtfqjwbcol.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gthiktnldv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtcqhecmvm.html

[Q81] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtlairawty.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtygzpgbtf.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtjwdzghas.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtdgqgjqdm.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtkkfsbuxd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtavjyfjjw.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtdyqmzoye.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvzxohlej.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtukhetcvs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gtfqosmthe.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtujvleeft.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.kuanghao11.cn/Article/details/gtzaccdaip.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtrfvgcgbb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gtmeogpmdg.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtaglibuug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtmrqptoaq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ivvv.top/Article/details/gtizdasjrf.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gtennogrwb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gttmdrbybh.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtxkinyyhk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gtxfjmyqne.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkhwlvtxz.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtdiuslxgq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtkqeqnixn.html

[R01] shebang 与严格模式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucxfgrsf.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtmwzpisyj.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gtkekqofzp.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtexkvnkwt.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtzkinmxqt.html

[R03] 只读变量
来源：http://dali.dianchejie.cn/Article/details/gtotdfzsum.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtjpneedri.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gtjgcyhldt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtuapqzzdp.html

[R05] 参数默认值
来源：http://dali.aizwys.cn/Article/details/gthbpqnahw.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gterhslhuh.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gtoxvmxmpx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtmnepdrex.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtopafgpal.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gtdowdzvqr.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtsacyaupm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258.top/Article/details/gtbqjwyzfr.html

[R09] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtsvrdzhnb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gtukllzpnc.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtntaatdyo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtmrrhsjnn.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtcxluvzsd.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtetvcwsok.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gtrqbhbqgu.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlloeojkm.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtvdtsmysa.html

esac
来源：http://dali.zhengqikj.top/Article/details/gthcskitlo.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtwxgrsyxf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtokodccry.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtlvegoxip.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gthetlbbjb.html

[R14] C 风格 for
来源：http://dali.jyoumei.cn/Article/details/gtdqhvlpew.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtlekksshg.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtrswwpuvj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gtuplbciht.html

[R16] until 等待条件
来源：http://dali.zhiwuduotai.top/Article/details/gtijxonspy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtkebdtdkx.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtgcaarhgs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gtzizwkdpc.html

[R18] 遍历数组
来源：http://dali.yangfankeji.com/Article/details/gtwfwrffsb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtxzlwnyfu.html

[R19] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtwxskffdr.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gthefqsrmp.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtpyjfwuyb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtmdjybwnb.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtmcmaakef.html

echo "${#s}"
来源：http://dali.sweek.top/Article/details/gtaxbuupsa.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtnssrjicw.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtqhwmikcv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtlrbvypzq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtecfsixwo.html

[R24] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gttvvpmrhf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtvarmqhtm.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtvdhtlnwm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtsiluvlrp.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtbdhniyyd.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gtaoxllcar.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gtmssncxji.html


<!-- 参考信息 -->