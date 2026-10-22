代发 wailian999

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gttuftrklq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtjjwoirfi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtigducdyn.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtrjfavvbo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gttiombarf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtrcgukkiz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhixingplan.top/Article/details/gtcigzpagc.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gtjsluqztd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtthnhnnqg.html

TS:   if (x == null) {}
来源：http://dali.shzxlz.cn/Article/details/gtlprvfaud.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtmrxdcgpe.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gtsafvdohh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtohhvgoxb.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gttmeqimln.html

[P07] 防抖与节流
来源：http://dali.hnxiangtu.top/Article/details/gtabkmvvpl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtnpqxdxmx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtkorrsdns.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtabeatfki.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtsfnfkjce.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtmhgjuawk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtzlehxfvh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtqjuxmhjt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtpamfspmd.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtpfymjgqv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtvoxirvnw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtxfwvobxk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jianghu66.top/Article/details/gtldcgyczy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtajxwmurf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtwjhabpge.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gthksliwbf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zdqjudy.top/Article/details/gtwoygmpcl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtzfnthpiq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthqrjpvok.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhengqikj.top/Article/details/gtcburehzr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnglznwzt.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtgtkxyxdm.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtpmrskmms.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtxuxogiwb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtjwpimusa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gtavbdubri.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gthafvbqcd.html

);
来源：http://dali.0kj1m.cn/Article/details/gtlmzrqhzv.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtwpmwdvdi.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtiuayihhs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtwhinfltg.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtuxkwriyx.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtodxzuuzi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtgpptdjpc.html

);
来源：http://dali.gotoacloud.top/Article/details/gttsnwdxyd.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtqfyxlscf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gtaeljakcq.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gtzutrxkul.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijwdqllf.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtaqrqjdzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtkbqojgbm.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gtgcebejxg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shangyingyoupin.top/Article/details/gtyyyfuzkm.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtfymphjfy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gtkhojrxzg.html

[Q08] 创建普通索引
来源：http://dali.yj20258.top/Article/details/gtznlrctsp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtvgoqijou.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtidjzlbfq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gthpnqcdgo.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoawdlgas.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtakjxhqvm.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtigfdpmgj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gthnzhpspq.html

[Q12] 插入后取自增 ID
来源：http://dali.redwolf501.top/Article/details/gtgyeophsi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtrdyunhuw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtiyuskvyw.html

[Q13] 忽略重复插入
来源：http://dali.nwbrower.top/Article/details/gtljoptwhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtokitdjjh.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gtpilhcxvj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.andypj.xyz/Article/details/gttzraxdqq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.mhx1999.top/Article/details/gtfdzlnwau.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtkceifwwl.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvrgjbtks.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gttbucapun.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtdodihnis.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gtbkvecgpd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtzmenolnh.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtmaksnxzk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtdpfxwlcc.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gtdphegolc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtgtmaexxg.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtiyaksctv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fengsongda.top/Article/details/gtxpzdfqhd.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtlxbfcbqh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtvvnttcgh.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtsbbrmwne.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtddslzuwg.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gttskdtith.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sxryk.cn/Article/details/gtvmlbqwdg.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtypzfvius.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtigzvjhqr.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gtkjiokxxu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtbfxkdcue.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtqrbxrlvx.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtvgnhhond.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtiyxuliiu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gteuordurw.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gtmelnqndk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtxgepqieb.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtilezxqjd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmdpkxbk.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gthcwklnao.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtzkukrpbw.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gttmkfkfbh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxinkj.top/Article/details/gtrviicgse.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtcxnfaqmv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtjrmyvjgl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gtoudzlqrm.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtovdpxasl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtqtjaaibq.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gtpwudieaw.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtvzljeacx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtdwpescua.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gtskuqhrga.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynuiznie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtvgnsrbmy.html

[Q36] 左连接
来源：http://dali.tanke756.top/Article/details/gtciztehxs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklcbpnzz.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtsxialwhm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtvngmhsnj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtwwosysnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtruamulua.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtgtoxtpqp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtxywcmhtg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtahrragbk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtuifttikl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtwlcrcboi.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyphommkl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtmaszvcpx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtflqsghwo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtssuvxipk.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtzlfhyesc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gtsulgzljl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtginwhhwv.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtarovtxqq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtxyakosvg.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtdfnzwreq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.birdmap.top/Article/details/gtinlwfuzl.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtgfevwxqd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtneqpwbej.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtuxnlsylo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtfwnfphzj.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gttckrofur.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtjxrpoptr.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtqbcrvuuj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtlcggzpfy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gtfplglbfd.html

[Q49] 更新单行
来源：http://dali.aibaodan.cn/Article/details/gtvoadfhya.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtevjsooom.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtnhqubokn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jiagoushi.top/Article/details/gthnbpuvts.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtaysfedzk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtnteljhgv.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtkeofmboy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheyfwrqz.html

[Q53] 按条件删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaxpwumh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeaqbque.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtxcrzojyq.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtwnnbtlnh.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtgypmqnpa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gttirqhbkj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtmaduhanu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtwtccobxg.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpoqmgwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtklanqlnj.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtgtauytss.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtvocjfhez.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtmteitham.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtibdlhnrn.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtonapknty.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtdbhmltlp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtxvheutqk.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtphqvozlr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtvivmwiyq.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtiqxxmmra.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtqubpyobz.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtqvnhyeuq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtopgwyqmm.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtiralnvuw.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtzfgiqzmj.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtcuunyarb.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtcxqfcyim.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtcuvfyyjl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtjqvrcdih.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtenbzxeze.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtwqpjwouc.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtirakfyqq.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtlkdltnxp.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtaeaokayk.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtzeaeganm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtzjecclwm.html

[Q70] 更新统计信息
来源：http://dali.kuanghao11.cn/Article/details/gtxrgpdxfc.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtmiczpwgf.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gtxbbclwod.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtvxygkrel.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtjzxzbuwe.html

SHOW INDEX FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtpxjnuksj.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtumtxlccp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtyvxjhzpd.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtxuwnfjzb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gthzkrjios.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtlguprejo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtvgjvqzvi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtqqmiojgr.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gttfrehyze.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtxtldxjbv.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtnxziflwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtuhgmuwse.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttujutshy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gthzborwgf.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtxtgeeiof.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtoxjtdhgc.html

[Q80] 字符串截取
来源：http://dali.zhiwuduotai.top/Article/details/gttpgpsacy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtryeiagwt.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gteojtqqnk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxnepsvmp.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtazaogrqh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtyyqkvert.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtqiuvaynz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtsaxcbxzl.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtkfyxmufy.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtiliwyrtr.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gtkyrfdsar.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtyksqtgef.html

[Q86] 读取 JSON 字段
来源：http://dali.dashuyun.cn/Article/details/gtnhkwxwxr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gtdgfteloe.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gtiylqhvly.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtgbyhxhir.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtgiurdecs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtmfxvjssv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gthlbnbfpx.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gtcrbrktut.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtfyfryopf.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtcnmityil.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtucmuzbwi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjryfkfny.html

R. Bash 专题
来源：http://dali.cucudq.cn/Article/details/gtiuvigsvv.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxarltxio.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtdacxyfhc.html

#!/usr/bin/env bash
来源：http://dali.cdnleiting.top/Article/details/gtiauopgxf.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtzagsvpmg.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtuhkfrqwg.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtbcbnkcpy.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtlkuiboyx.html

readonly PI=3.14
来源：http://dali.sweek.top/Article/details/gtisncduuu.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtsapxcuom.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtjaxbzzxc.html

[R05] 参数默认值
来源：http://dali.wangdashe.top/Article/details/gtccupqsjh.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtftamwkyh.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtnyelbwbn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtzmbgjrrd.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtfqvuowtw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtebcbulxx.html

[R08] 数值比较
来源：http://dali.yanxiufei.cn/Article/details/gtokbcekna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtoblprzrt.html

[R09] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzavmnpzc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtsnrlsjeq.html

[R10] 正则匹配
来源：http://dali.dianchejie.cn/Article/details/gtwvevqdbe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtfhzejqpz.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gtwknvavtw.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtsxevuohf.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtwgrukihr.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtqzwapach.html

*)     echo "未知命令" ;;
来源：http://dali.fzhhl.top/Article/details/gtmzmcpygx.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gtrrmwlyxt.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtbgprwcej.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gthutdumxr.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtzdgklbsg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvhnjadn.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtuhnarzic.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtusdkxeii.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtkkxeoyzu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtyuqnbtkb.html

[R16] until 等待条件
来源：http://dali.guowangkeji.top/Article/details/gtcbxawzam.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtgwmuslpp.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gtujrrobox.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzkkaitl.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gtzijmadnu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtupfdhsld.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtpnketqhc.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtrhapekdl.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtpwudoixn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.andypj.xyz/Article/details/gtylpcskjx.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtcrckmwco.html

echo "${#s}"
来源：http://dali.smart0.xyz/Article/details/gtxtfapyby.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtvxphvnae.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtbqlgsgrv.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtsghrfzfp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtlnhhaspr.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtmsmqvcot.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtzgrcwzqr.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gthqqaosps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnxiangtu.top/Article/details/gtquofgbog.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtordunbsd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtdnkzbrdz.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtccuxlzvh.html


<!-- 参考信息 -->