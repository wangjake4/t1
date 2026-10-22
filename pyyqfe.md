代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gt2vdlxsznu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gt2yhmzhzux.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gobxbjos.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ztnbtbtz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gt2xwjveawb.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gt2oifjekrf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gt2fmvjhvor.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gt2dnudmewg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gt2rdudfqps.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gt2qteauaac.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gt2enpcgfwx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gt2xlbpbxuw.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gt2hievosaj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2ohejkjii.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2ggwennob.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2unuepaxk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2idrofbvn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gt2vshmmrvs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gt2ftuomleh.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gt2noghzqxb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2pxnubdnz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gt2ejkxmigi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gt2hjcoodxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2vjusgfow.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ppjwa.cn/Article/details/gt2wqhvxsry.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2dobszeen.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gt2prkgehxc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gt2uualkljr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ameygesj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gt2wsvcthkc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpahbtqu.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gt2yurrrnua.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2tqlxijcv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2pjffwpeu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2pvkhqqdi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gt2ufeoehfq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gt2ekgrxbam.html

);
来源：http://dali.tanke756.top/Article/details/gt2kjzmtbti.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gt2fmoksxav.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gt2xgwwqzfn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2vrajpjtu.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2iaptccwm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfwvcdx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cqqwz.cn/Article/details/gt2phawnmfu.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gt2jshogpnw.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gt2vkinouuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2rdhidgxu.html

[Q04] 修改列类型
来源：http://dali.cheryme.top/Article/details/gt2fckykfbc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gt2fdvffyqg.html

[Q05] 重命名列
来源：http://dali.cqqwz.cn/Article/details/gt2njqtfarr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gt2uekzkzia.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2fujzczkq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kbwvxzrg.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2ayeeytbe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gt2yhytmvsl.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2hchysrqr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gt2sejloqep.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gt2dladjozn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2xduvjsbn.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gt2qsusyveg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2vagsufeo.html

[Q11] 一次插入多行
来源：http://dali.hywenlv.cn/Article/details/gt2dnbqrnao.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2xfrhijuy.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2itlkvoid.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gt2zzgfqzdw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gt2rtvnwqjf.html

[Q13] 忽略重复插入
来源：http://dali.aibaodan.cn/Article/details/gt2wjrmmzwc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2slzlqplk.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gt2udslbwfq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ydzc1.top/Article/details/gt2nvajuiyg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2pbzhsqae.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gt2ntidzqih.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ekhiaiwn.html

[Q16] 查询指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2yvwdfbxq.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2aqtalvqh.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gt2uaytnrng.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jianghu66.top/Article/details/gt2jnbawaha.html

[Q18] 模糊匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxkbhgrm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bzchbxfa.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gt2rkcbwqyh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gt2qqpfhydv.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2hurejphx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gt2ahypxzpd.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gt2uvmdpsjl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gt2cwrtndxb.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gt2dydbazbj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gt2zfjraskt.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gt2dcxjpwiz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gt2ifjbqcwp.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gt2gwhruuav.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2groqdwll.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gt2goiesktr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2adxpptec.html

[Q26] 计数
来源：http://dali.hysaishi.cn/Article/details/gt2xjgdvcvl.html

SELECT COUNT(*) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2dpleoikq.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gt2vjogdnfs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2xneeihop.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2obsqcakt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2edqavvzt.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gt2kwdagogs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2donwpnmk.html

[Q30] 分组统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbtzjctd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lovdstzu.html

[Q31] 分组后过滤
来源：http://dali.jlsjyb.cn/Article/details/gt2hcimcoxk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2enobidbt.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gt2jjkihclx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brqhtyea.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gt2hlkcqzgq.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gt2lczwxywk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2wlwwaksc.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gt2crocnufz.html

SELECT * FROM (
来源：http://dali.andypj.xyz/Article/details/gt2effzubhz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gt2kfhjxcti.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2nmbcsphd.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gt2ukzfqbpg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2cmqqhtao.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gt2lhgxlith.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gt2vehfbhxu.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2jiqwlhol.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2aagtlvtu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gt2onwyyhiv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gt2vvvnvaqz.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2xewdsdni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gt2dhlqnaef.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hysaishi.cn/Article/details/gt2xqqbbwpz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2zjjnvkyc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2ufqhlcey.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gt2ltbqeqgu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gt2nuijjoxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gt2zrnqqdce.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zekgiiez.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gt2athrutui.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gt2veuuirrp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gt2tfasleym.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gt2qdjevjfd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gt2dvsqtaak.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gt2vktefkxv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gt2dtpowdxh.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2suqrccyc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2acjnilgl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gt2kzzuziuu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gt2iagdyyjy.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gt2llwxqqje.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvnmevls.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2rgqqcgzz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gt2kivwdbuv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gt2hpgkeiyq.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2bbdzutcz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gt2vuencnie.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gt2fzqaxcfo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ybcxt.top/Article/details/gt2lngimapn.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gt2dqzaohzk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gt2ocjxjamf.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2kotmsauu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2zmiiwxom.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gt2mulbkwur.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gt2ueuozyny.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gt2zzdoweub.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikzfybzm.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gt2tktwdpsw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gt2rzstypji.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzoqvkst.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gt2bogskgeh.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2cknqjkbt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gt2jgeqgcbl.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2cszkebht.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2nzpxdrnb.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybtyxyiv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2dxdeuayl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wshwpxhf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2pitygman.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2woocspis.html

[Q61] 移动平均
来源：http://dali.zhengqikj.top/Article/details/gt2cujmhzsr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2qjvfndkt.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gt2mbfdnyzy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gt2ejftmwqq.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2eapavslo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2ihcddzdl.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajmcvjnl.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2vzzugqky.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gt2qxorutua.html

ROLLBACK;
来源：http://dali.cheryme.top/Article/details/gt2abfnnwuo.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gt2stsbqhri.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gt2aaufnlby.html

[Q67] 设置隔离级别
来源：http://dali.tianlin.xyz/Article/details/gt2ffqvdrjl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gt2haqzekea.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gt2wjltisxm.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2odvmeneo.html

ROLLBACK TO sp1;
来源：http://dali.zycfv.cn/Article/details/gt2eercvxww.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gt2psmwpcyc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2ssisspfx.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gt2pnezuftq.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gt2xmcjyiid.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gt2uymiecrs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shangyingyoupin.top/Article/details/gt2suyurbxu.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gt2wvhynryk.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2vchzause.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gt2fzhgwdxz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2slpvhkbo.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gt2aobexijz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibrrftct.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2hraoucvs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2elcckyvo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gt2mllfofdw.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gt2spianmfa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gt2tgcehvsk.html

[Q77] 时间加减
来源：http://dali.mhx1999.top/Article/details/gt2yqknygth.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsccqcko.html

[Q78] 当前时间
来源：http://dali.zycfv.cn/Article/details/gt2ywjggbil.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gt2xluibbrb.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2wgymeqpf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gt2kqubdmno.html

[Q80] 字符串截取
来源：http://dali.hfpthk.cn/Article/details/gt2wwdvfkqw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2ywxtplhw.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gt2kvzwwdjf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2upuwzspe.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gt2zjqqpqxi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2tphkzebr.html

[Q83] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gt2pgeuegbg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2kvbsvsiv.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmzxxsds.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2qtagkmvv.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gt2zmzhyltp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gt2ziuajuzb.html

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gt2lfgvqczh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gt2sljoldzn.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gt2lwqfepwi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gt2vnpqogpb.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2bgxefvhe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.smart0.xyz/Article/details/gt2stlcrudk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2whojxzdx.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gt2ufakljyy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2wtqvupza.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gt2hanitiyi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gt2atbwooba.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2khygsxwp.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gt2oyuhiunr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2acdazmys.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gt2oaisybkd.html

#!/usr/bin/env bash
来源：http://dali.redwolf501.top/Article/details/gt2ulbiybxs.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gt2ssxnmaes.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gt2vvqrdtvn.html

name="Tom"; echo "$name"
来源：http://dali.gotoacloud.top/Article/details/gt2csyfgeyt.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gt2jxwimivv.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gt2lehktwwb.html

[R04] 位置参数
来源：http://dali.fzhhl.top/Article/details/gt2qxelptor.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gt2wvuqoicr.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gt2zyylqyma.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gt2gznymjua.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2gaeubviy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2jkikqqhw.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2qwabsptr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gt2xqlcegni.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gt2hxnnnooc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gt2zwvsgcml.html

[R09] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gt2alhyxope.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2iaodgcku.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gt2jfzqjqpf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gt2mlwxhxns.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gt2zcljaslk.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gt2szykkaoo.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2vezodmvj.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gt2ammlqbvl.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gt2vkbwbrlq.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2fupromjr.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gt2mnuwqbco.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2hyfdjrlc.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2tykguset.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gt2ctrpqomo.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gt2nndihapd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2hodylrcb.html

[R15] while 逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2jspjfkhl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddwtipml.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arenumkn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2hxqmsvai.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gt2izkmthlc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlwtitdg.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gt2mdgrtsdq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bszjsmyk.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2siynpfyf.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2yafkikbu.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gt2obvvgqkd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gt2oovcrsvz.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gt2lhsbnusb.html

echo "${#s}"
来源：http://dali.fzhhl.top/Article/details/gt2bcrfcyiu.html

[R22] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gt2fpdzjhtc.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gt2lzumfjeg.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2elomdwuj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gt2ljxqpwbh.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhqugkib.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2avyfvzoq.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2upukdzfc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gt2ykksldfj.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gt2frteuytf.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gt2claoufhd.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gt2xmwprgxu.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2nofmdeys.html

[R28] 浮点运算
来源：http://dali.ppjwa.cn/Article/details/gt2vscknaay.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gt2cxoduemf.html

[R29] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gt2nfoelzty.html


<!-- 参考信息 -->