代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtsfbzziqq.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcfnalmxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsofegyec.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtyctnucfr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttotlhtuu.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtkjdeqzyh.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gtdjgykblw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtovrcdnte.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gthsabbbwf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqxpncce.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtnwcunimf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtkxyvsefg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gthflwczel.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gttjprefrj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtfhlchudx.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtoakapabe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gtkvaottpm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkacmfdnb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtchcmigdy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtaxjbyrps.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhengqikj.top/Article/details/gtymlgugxb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gtladgomrr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hysaishi.cn/Article/details/gtcxirfksm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gtvswrkfds.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrbtuafnl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtompiyvuc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlegwsyon.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtfzvigrkq.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtybxxcgpr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtbjsvjyjr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtprheuwdu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtxdzugeer.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtxpqbjnzk.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtwordvxlr.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gtzrllawpz.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gttryosrab.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtvqvyixnb.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtnhneluid.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtxcpcrlfu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtnblwdnru.html

);
来源：http://dali.zdqjudy.top/Article/details/gtosvsjrhq.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtgpiafftv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtlxbwtmnr.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxohpxyb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtnrpqgndj.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtiszufpgi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtoywottei.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtjlafyyrk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtzueqzdzn.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gtkjrfxqvf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtwohflymq.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtdslidmvs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtmidqiaxl.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtyjoofdcu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtlwrvwycs.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtzhhppcnu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtfhxutwkn.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtvtutuedi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtgzbyhfmu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtlfjknoyd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gthnstaaom.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.quarkkingdee.top/Article/details/gtjgcutvqm.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtsvlbuijg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtvisyjiub.html

[Q14] 存在则更新（upsert）
来源：http://dali.hywenlv.cn/Article/details/gtqegwcyuw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuanzx.com/Article/details/gtuvztnfcj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtglskbtff.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoeiddhh.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gtceqmynlu.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtgkltxrtk.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhuzvuaj.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gtaxcdzmcs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtjzajtaax.html

[Q18] 模糊匹配
来源：http://dali.hfpthk.cn/Article/details/gtayeimtsi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtcakhgyws.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtxxsnfsea.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtqhynmicr.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtkzhgmdei.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtlteclwlc.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtwclbnywi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.havefunace.top/Article/details/gtyfhujxva.html

[Q22] 排序
来源：http://dali.yongpay.top/Article/details/gtilfctfnh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtiwdvploh.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gttcipdkme.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtlukidekv.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gttpuhllnp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtpautdraw.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtdqyfitlw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.c1oappe.top/Article/details/gtunqkxbco.html

[Q26] 计数
来源：http://dali.zhengqikj.top/Article/details/gtilqrgvfe.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtbtcfkequ.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gtxdugkxnz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuanzx.com/Article/details/gtigdejdrs.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtkccdhslt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtbrcwdswn.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtebipbatt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtkawnjcee.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtchyfeiph.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvitpymoe.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtamszduku.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtqgggasoo.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtinkvmibc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gthrrzlxwl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtjbooteym.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gtyqsevssw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gtiuvokdto.html

[Q34] 每组取第一条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzofpkoiq.html

SELECT * FROM (
来源：http://dali.fengsongda.top/Article/details/gtfwllqava.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenlongwang.top/Article/details/gtqpyxoqfi.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtxbbvkvej.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtfrhgxczw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtpmbdigkw.html

[Q36] 左连接
来源：http://dali.aizwys.cn/Article/details/gtgyapfomt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqcvphaw.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtsvqtjarr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gtkehfgmyo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtmycjomok.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gtnvtwcmiz.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtqpysktdr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jyoumei.cn/Article/details/gtmxmwtlrg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtuvjtlbfc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gtgiipdqmx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yonumen.top/Article/details/gtbrqotufl.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gtnkbafmhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtpoazvvhp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtgidwkgzk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.birdmap.top/Article/details/gtylobgehi.html

[Q42] 连接条件附加过滤
来源：http://dali.bjfxy.top/Article/details/gtbpqndadh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtlsahihqh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtaxynbvev.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtcmsouqvh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzulshaf.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtmzazuswp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tanke756.top/Article/details/gturbgmdve.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtkdoktfru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtjdjdqgbi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtbpezktac.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtgnubuwfp.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtsqucecag.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtcadcmqmz.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtgssetleq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtngbuvyur.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gtofosowsm.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtfkdyrlfd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtwialqunf.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtbytxerku.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtxyxquzts.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gtqhkwnnvz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtcpidxwtg.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvocnoio.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtcrcbjwmi.html

[Q53] 按条件删除
来源：http://dali.0kj1m.cn/Article/details/gthgzymmnz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtqfgxxsio.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtibhjknoz.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gtfkklivus.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtndbtpnzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtcnstykcg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvhbojgr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtokvqgzwi.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtnkyndqww.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gttiihczby.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtesepcfid.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtytqcbedv.html

[Q59] 分组内累计
来源：http://dali.fengsongda.top/Article/details/gtzrsjkgpy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtmvwonjbr.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gthzqwqlfv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuanzx.com/Article/details/gtlcrwgysn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtynrjflcd.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjwsexsq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtpyxpmqma.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtlfhilqtj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtyuodgtwh.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtpnunvacy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtwoxrfbil.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtszqbimbs.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gtbbxxqjmr.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtxquddwsz.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtucasygkd.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtvrvhglju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtjirfjnav.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtillqtdpa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtnyudlwwz.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gteflrirtf.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtytjfwcle.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtcvttaylo.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtrgifbrxr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtsktyxefe.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqveuvuvy.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtgftjmdgh.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtjekdipqi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtwgtfvgyb.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtctgtxriv.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtxkzicuqk.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gttkwlhhkp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtwpwauayy.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtrwbvqybx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gtqguwxwkq.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtedxrrxwo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtmhmxwssl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtcunhxprr.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtotgdglmw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkryctoa.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtrayvkrkw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtkvqbnljz.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gtklbujuit.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtmngqtcgg.html

[Q79] 字符串拼接
来源：http://dali.316326.xyz/Article/details/gtqjapbycv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gtggbmyllq.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtxmwxldur.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtdhqlvoao.html

[Q81] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtojepyqou.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtbloepzut.html

[Q82] 字符长度与字节长度
来源：http://dali.zhongyouzk.top/Article/details/gtxloknhev.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtdtzonbkg.html

[Q83] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtmikeiioj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtyavkrwvk.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gterkzmwbz.html

SELECT TRIM(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtirvghqys.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyyaqejk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtvlvvtypc.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtzdflzliw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtruvufpvq.html

[Q87] JSON 字段做条件
来源：http://dali.sxryk.cn/Article/details/gtdsmxfqay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtnmjygyea.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtrgdgrzki.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gtssfkcspl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtfuyxpnco.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtfrlmbdtj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tanke756.top/Article/details/gtzhthwtbf.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtkdjzzfok.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtgkxinkte.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmgloqcps.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtiswwlmif.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmkwcwcnp.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtckwcyeai.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gtpyjpkufc.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gtaqjdwjke.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gtvxrihfld.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gtoaljvhtk.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtmgdutkei.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtxlnwmiqc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtrqpdcpaq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gtcnububkf.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtxzzxaaad.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtbiwjzpnf.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtolvuyxmg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtaifgphdf.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtlgxkprly.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sxryk.cn/Article/details/gtcvquhwbt.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gthjkxqtma.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtkoprvbpj.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtexugstxb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtwvmgpzmq.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtzmceiedj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtjhiljxfz.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtesbjqgwg.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtecmcoqvq.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtqeyqlvse.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtmzediruy.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtlycceulc.html

esac
来源：http://dali.hywenlv.cn/Article/details/gtiqlnukgv.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gthjoseenx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtlmmktyng.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtppdbiwoj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtrhwnhqsb.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtmfdilttc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258888.top/Article/details/gteueemmnt.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtwgfsiuub.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtmazzkpbw.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gtitrejcui.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gtopciwmjh.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtsygaorpv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gtqwlpyany.html

[R18] 遍历数组
来源：http://dali.quarkkingdee.top/Article/details/gtoilphyyp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtqmnltjty.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtdwxrxdbe.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtoawixotf.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gtggqtrdyk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gtwktgwmbp.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtgiyjirij.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtnnkxezth.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtktmzwcrr.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtbzvbwwst.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gthyltwbka.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gtfmkttfpa.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtwnibjeyi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtlsliobgw.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gtqqeemvra.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtwokmaojj.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gtdtzndlkd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlynvyqik.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtmrkksbwn.html

echo $((1 + 2 * 3))
来源：http://dali.sufxvd.cn/Article/details/gtxwrypvfb.html

[R28] 浮点运算
来源：http://dali.c1oappe.top/Article/details/gtrhevxqws.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtzbzrfytv.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtkeeelgty.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtfokvuyds.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtgjdmhogu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgufenzy.top/Article/details/gtftijgzjs.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtykrzdqjg.html


<!-- 参考信息 -->