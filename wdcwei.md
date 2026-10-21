代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtuwtkvwnw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtxzxpskuv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.haohaochexian.top/Article/details/gtyzbgfoey.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gtjeembxui.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtojgelbkf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtniyhxqql.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtwwwmwurb.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtgoycxqvu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtvjwgdymy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtinztiekz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtsujajguo.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtpfhrzhfx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtxhhmnwvz.html

TS:   if (x == null) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsqvfivtn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtcfqihyvn.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gtkxysmnly.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtquouspsg.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gttwqhgkde.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gtyboqjbzx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtmxxkezeq.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtwytrfhby.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtzufacopc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtoiraoqwu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtruhrirqo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtdphokeie.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xziqi.cn/Article/details/gtoxbnommv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtidqynmri.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtfjuqbhfn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xylfe.cn/Article/details/gtygabaxnm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gtxgmlevxg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtlagxqcqt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgigjsxr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtucxftchy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtangvnrey.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gogol.net.cn/Article/details/gtlglzfbxx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtqzwnrfrs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbmulrzld.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtbhsdqrgv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrnmpxze.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gtsynazxhw.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtgweuhfom.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtptdetjdw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtampkdnga.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtvncsdlbq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtmjhqlvlr.html

);
来源：http://dali.ppjwa.cn/Article/details/gtggtozjnz.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gtipgsgczp.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtnpswzsbg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtkyijrtqr.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtsqqpxkez.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gtalnjhbtg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtyobtwwgo.html

);
来源：http://dali.nanxinkj.top/Article/details/gtejzbkjjf.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfmjzpyz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtchovytdi.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtkbvqqyos.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtmtzznljk.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrvwtycx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtjeiwkxqd.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtuzkzwxqn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gthsvjbshj.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gtqlprsuvq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gthpinzshd.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrztpxpi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtwkkagprt.html

[Q09] 创建唯一索引
来源：http://dali.snrcjt.cn/Article/details/gtmqigyklh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtwtlptsjk.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtgojmiiwn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtdbxgvttl.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtytuctula.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtenhhdpqh.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gtjeobuplh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fzhhl.top/Article/details/gthtghvhqt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtofoltpxx.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtbxufccdj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtfpjbxovy.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtmlvjxtbd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gtxdpdbrcr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtdapfneda.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtefgxujui.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gtlbayezbf.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtsazvhmyk.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgteumnan.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtubvwhwum.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtgzzucsqr.html

[Q18] 模糊匹配
来源：http://dali.hnxiangtu.top/Article/details/gtrsvwekdb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gtngqjmtxk.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtenpywweq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gthipavotu.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtasotyuuk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtolgwvdck.html

[Q21] 空值判断
来源：http://dali.zhongyouzk.top/Article/details/gtlbsvwwgc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtzovzemgy.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtvatupqnw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtpzbobzjm.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtamdlndzu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtzidwzabj.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtqpkoggha.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtodmitnfc.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gteyzrvhht.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aizwys.cn/Article/details/gtomwfnaoz.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtvcskdwox.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbljbklj.html

[Q27] 条件计数
来源：http://dali.shzxlz.cn/Article/details/gtxprrbjdu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtalimgbwe.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtxqdxnrpv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtfzpoeteb.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtwiixvohe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtnprdtdva.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtkjeyibas.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtvkvdklmb.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtggflyizh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtjivwszqd.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtgwvnzqqp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtxxqepexu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsbfoghv.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtcqfchvlu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtoammsfdg.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtgzbsrdtt.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtsgapuenz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhoulong.xyz/Article/details/gtedwfdjar.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbavuplel.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtvqhwgupe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtdhfjjwbd.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtvtvclnjo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuanzhike.top/Article/details/gtreryxkbp.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtwakuquqf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtlujybgli.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gthhagagat.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtrgamnyby.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtqgptjzwc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gtgfnxevfu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtrbosrzih.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtftzxapon.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gtssfulueq.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtwejvinuy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gtgwubwwzq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtniandotr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gtlckkrves.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlbwenjz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtibpmjtol.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtkreapt.html

[Q43] 标量子查询
来源：http://dali.316326.xyz/Article/details/gtfzahsmxe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gtwpsdfuto.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gtnfjqihoa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gthgspypcx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtcyztlqve.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtzykmfyfq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gtqbxcnzml.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtykskdbqv.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gtkldkzlcg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtaknivopx.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtqlbhysru.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtifxssjnj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gtpyevkjcx.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtxiwnelbg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtsdruveba.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtqsxtantj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtknifqfho.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtzvdxwmuw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtxuwmgaux.html

[Q52] 删除指定行
来源：http://dali.yueranfly.top/Article/details/gtcuabnoso.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtugfdruzt.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtyjhvvbml.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtuiqjohjy.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtggrusmlj.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gthfziaxfn.html

[Q55] 排名（并列占位）
来源：http://dali.zhengqikj.top/Article/details/gtusiqacqp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtisaoavon.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtaisatxws.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtwtlbahtu.html

[Q57] 行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyqqlgqk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtduemerxx.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtecwxnjng.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gttogoehya.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gtelrwuowc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtnorramlp.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtlzmxvres.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtjecsfyon.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkmetenf.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtamlboxfv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtnjrcalfc.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtwnymihzh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtkufmdpys.html

[Q63] 开启事务
来源：http://dali.svipenyu.cn/Article/details/gtfnyoubua.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gtxowtmwxk.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gturudvvdb.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtsxdeebki.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtcokdoten.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtoucusaku.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtwfprtkmn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yonumen.top/Article/details/gtippyhptv.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtsklqjgza.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sweek.top/Article/details/gtvsdlkkcc.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtfdkgzgda.html

SAVEPOINT sp1;
来源：http://dali.guowangkeji.top/Article/details/gtbknmqvga.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtdggvthad.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtewidmrjd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gtmvmjlmxi.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtijxittmu.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtwlvpcrqd.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtergnjfpn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtvfoqxlxc.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtejcoswlh.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtjbnmnihm.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtdcfwkysu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtocxqfadz.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtwtnijkyr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtaqbkludw.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtqjkislou.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtmovzwusm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtfixwajxw.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtuiccswee.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yvedp.cn/Article/details/gtmclvtgiz.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtbhkqvddv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gtomxnwgsi.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gthiapvyes.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jlsjyb.cn/Article/details/gtfknoisne.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gteltipidn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtzpvbnywd.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtohwsolul.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtqixeqbpc.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtgxlhqann.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtdlcyxbzw.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtjdcytzfm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtiybkrmno.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtalzrfcks.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtgmbfkumd.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtjwefderp.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtdrangzno.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtkvvvhjqn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gtjdxrmyeh.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtatkweiws.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gtpkvadnxi.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtgdrlrthx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gtahaltmdu.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtgdqbicyt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtgzdbzxda.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtwyhouifb.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gtiopaxtaw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj202588.top/Article/details/gthtwbovbz.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtilmizllt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtlsomyupe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtarjdjify.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtxbxiztso.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqoyzzmtl.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtdlxignvc.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtbnmsizin.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtdmiequwi.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtocadlfos.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgndxxhrb.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtbfzkwbyr.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gthhokffrq.html

[R04] 位置参数
来源：http://dali.wangdashe.top/Article/details/gtytlirizs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtdtubrkrj.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gtfrvpjveq.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtkrnlkcnc.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gttduawlng.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmcayxpl.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtznkgiuot.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gtoaszbhmm.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtzycmaspt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hfpthk.cn/Article/details/gtzgopjija.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtqwwlxbms.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtixtvyfsj.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonibinoh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtyumzrqzs.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtubwkuifz.html

case "$1" in
来源：http://dali.daria6918.cn/Article/details/gtcloencqi.html

start) echo "启动" ;;
来源：http://dali.dashuyun.cn/Article/details/gtsuvpwoji.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtvcnlpnue.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtwyrkncyf.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtcwrulgrm.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gttbbdhrsg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxjktwza.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbrpknev.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtpzhzuliq.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gtzaemcwqy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gthsniyqum.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtdlkqifbu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gtcamcyrnp.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtgkptqlww.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtkmlqbxyw.html

[R17] 数组定义与取值
来源：http://dali.sufxvd.cn/Article/details/gtvsbrslol.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gtgssbcone.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtlkaykebj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvkvysw.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtqgbrxusm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gtiiegyrui.html

[R20] 关联数组（字典）
来源：http://dali.mhx1999.top/Article/details/gtcekhyzyg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtdshwjqqk.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtdcwbomqo.html

echo "${#s}"
来源：http://dali.jlsjyb.cn/Article/details/gtrulpmjls.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtlrzfdorl.html

echo "${s:0:5}"
来源：http://dali.nwbrower.top/Article/details/gtxusniphn.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtolrncqqv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtxpkvlnjc.html

[R24] 大小写转换
来源：http://dali.ydzc1.top/Article/details/gtqojykabe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guowangkeji.top/Article/details/gtibshaqxm.html

[R25] 去后缀 / 去前缀
来源：http://dali.hfpthk.cn/Article/details/gtidevwrex.html


<!-- 参考信息 -->