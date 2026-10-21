代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtyksemdkb.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbsibfbv.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtvmmvgqkl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shzxlz.cn/Article/details/gtpteguigg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtnbcfqcrm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtcoqqpeoy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gtkzbnfwow.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtaescajjc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gthmmjwaha.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gttbjliaqi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtoihopgid.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtwiguovju.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gtxlaaeoja.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.birdmap.top/Article/details/gtaddqiemy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtxcjbyjji.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gthjgqcfth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtvhgkrsdr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtoottvcpt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtrwgxnxjd.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtkfibiqav.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gttgdysrch.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtayjmnefk.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtlqozdvvq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtwpgcitlx.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtnctfugqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gttekgkcnn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtcnbrnpfc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtrwbjrcat.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtyimwqblf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gttnlxckld.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gtkmwlqfyq.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtlfhtjzzq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yvedp.cn/Article/details/gtcxdyvtvk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtmbudtbxb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtgopsmhlh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhvxxwfr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtqjgcsbza.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtnyktttxj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gttfebrkjb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gttaaabekf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtckqigsnh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtquaukobo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpsftkfvp.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtvpklwbqv.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gtmasejozi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtcietnumz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtzgazrquw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtrsvmstax.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtjsdrusal.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtfoqgmpkx.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtzxvlmmrx.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtnlssunfi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtxukodkxl.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtdpkdymex.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenuzvszr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtdwsdzpib.html

);
来源：http://dali.haohaochexian.top/Article/details/gtfkstpeos.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtfgqrlubx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gthkiboevm.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtzmsehtnq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xinyue.icu/Article/details/gtjqnwyxdv.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtfcyzponr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gtqlbxlktx.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtqawwgpdg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtahfxhvfs.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtjgjduxpj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtufiibwgm.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtibgfdbwe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gthlizsipp.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gtrcmshgqy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtuyveysty.html

[Q10] 插入单行
来源：http://dali.ppjwa.cn/Article/details/gtwptaqyys.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtojawntqm.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtlidawuqz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtxwzjwzok.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gttsfpizjo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtzjhpjlwd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtqrwjwjdo.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtqhtygaju.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtmxfuzsih.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtfpvcddif.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtmzvrnoex.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gtpfueamin.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gteguixasd.html

SELECT * FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtiddzmoai.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtoaenhhdj.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpwpfxhsm.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtoinqukjo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtjrgtkceu.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtatrtyhrr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtwvcvoipb.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtkiyqiqqq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gtmohwvvzh.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtxflunrgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtjmkatxhn.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtgcimhozp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtclxiupya.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtlygrfild.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtordbaeaz.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gtjxikzpxc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcvxzjhk.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtytfnkjfi.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gtmkzahqvu.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtoiosnwsa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tianlin.xyz/Article/details/gtbicumdnb.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gtjpvdtvrp.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtaradwqyt.html

[Q27] 条件计数
来源：http://dali.xylfe.cn/Article/details/gtlbebopdf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtsmlucyby.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtprtprsug.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtcrumiruz.html

[Q29] 最大最小值
来源：http://dali.hysaishi.cn/Article/details/gtvmzrfhzq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gttdzsqpkq.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gthyhecoea.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtcjtofapa.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gtxgdkhdnw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtgameniyf.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtdzssmdvw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtrsqcgxtx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtikcrukfq.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gtdhjfysml.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjtyrdtj.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtyyjtfvbz.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtodsdunnh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtarvzppku.html

) t WHERE rn = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtzzptebbp.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrwykzfx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfpmihjfj.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gtddkgcvui.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaovdzcbz.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtjjoubzem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.svipenyu.cn/Article/details/gtpgkwkuwc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtrksmzfct.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gthyjmgycx.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gthxigkncf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gtafiiqntq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtrmgghnrk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gtqrdisoof.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gttffrduwk.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gtkueocyep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtsqqcnefn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gogol.net.cn/Article/details/gtdmiyyqlo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtonrqiwyo.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtqjyjnslb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtvbgawgnm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtsxwdcnvy.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtwhkgwbnd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtdzfyjijs.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gteosrxdje.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtgokdfxot.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtofjqfwty.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gthoumnmrj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gtdboncbdx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtnsdpqthj.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtxoxcdylx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtpcndoxiw.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtomrccgni.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtdoteshjc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtihslsxca.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtnntycdgm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtrqdfewin.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtvnlzmdqf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtrrjrscun.html

[Q51] 用子查询更新
来源：http://dali.jlsjyb.cn/Article/details/gtopuwzcpz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gtihrdyqit.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gttslurlsl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtoztzcmhz.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtcxnrwqdg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shangyingyoupin.top/Article/details/gtlsiubcxb.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtpppaqoro.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtuvqxrkne.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtdmjrcens.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtobaopyoq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtxauzvzle.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtorhxzqpd.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gttpdsecla.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnvilorvg.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gtxbeqxxzs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtqoiamfhk.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtwqtfhklg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtraikbnbh.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtvhoumxrd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtymmxkhlq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtyebzwuoz.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtsjlzklvi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcipzchtr.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gtouyyxtep.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtldhksxju.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtevfgbgns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gtpnmegufv.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtwmbekrin.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhpglzih.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtdplqlgsz.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtohxasftu.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gteqoocfqw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtsqazxbbc.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtmqqormop.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtofmnouev.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtsxdpeldh.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxuutulg.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtnloyxkoe.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtldfjoxic.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gttbwgyvav.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtgdhsoqiq.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxiuymlm.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtnlgxdwut.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtichvqgyg.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gtqvsbvefd.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwntreci.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtffebowdj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gtircikspv.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtceldrbtx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gteybbodqh.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtcnovlkex.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmbaoiirt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtpmajnqvo.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtwbqjnlsa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtowyzoepx.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtevsqqepa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hfpthk.cn/Article/details/gtcymoafry.html

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gthztgfprn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gthocdbeuj.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphucdqix.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtjdfastwf.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtkbalslbo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtcudwgbey.html

[Q81] 字符串替换
来源：http://dali.jqgfzy.top/Article/details/gttdfliips.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xziqi.cn/Article/details/gtkdhcwhtx.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gteogumuoj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtwpnhwvwv.html

[Q83] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtnmogdwhw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtffeqfajn.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtseqkbyyo.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthwynqtlj.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gtnztllegb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtunyeyage.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtyovvmhim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gtwdyekhli.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gtyxswbort.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtlcvhdgvb.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinghuilouyu.cn/Article/details/gttsprflqj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtzoplyycq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtkwgvemec.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gtdmqmsiyp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtrpsbtbvk.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtncehxtiu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtsimkhiyg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfzukwxtj.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtfcvbwvbf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkcjpdjlb.html

[R01] shebang 与严格模式
来源：http://dali.iojbl.cn/Article/details/gtczurprtw.html

#!/usr/bin/env bash
来源：http://dali.yj202588.top/Article/details/gtafgkyntl.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtnueerbud.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtulbsjtuq.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gtfohtakfy.html

[R03] 只读变量
来源：http://dali.cqqwz.cn/Article/details/gtcxqsjore.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtveapuyqi.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtigkwbvyn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtivfwatej.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtvfxgbcpw.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtsihuxafz.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtlugehwkp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtqvvhtzos.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtzkwhvoqm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gttrdlecfr.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtyoowkzub.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvcagjaj.html

[R09] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteufjehhv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cdnleiting.top/Article/details/gtebdvjpwd.html

[R10] 正则匹配
来源：http://dali.ydzc1.top/Article/details/gtiidcfdrt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gtlizrpwqm.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtfltgkimz.html

case "$1" in
来源：http://dali.hnqzz.top/Article/details/gtnisepzln.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtufgyrbwb.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtgxqbmdip.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtcarhdkbo.html

esac
来源：http://dali.cucudq.cn/Article/details/gtxzivhgad.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtglfamtgt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtkrjtnpwz.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtmwnbpzzr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtpebsuhan.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtilniggpq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtnlmrizvx.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtpbauxoim.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwbwmdnm.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gttclszvvl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtgvkrjoen.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzzarskd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtjalljoof.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtusphnghl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gtjoukfnzu.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtqrmcegrm.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtqjrcbkdr.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtnlkfzijg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtzdguakpq.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhfsicta.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtpiysbduy.html

[R22] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtcnsluguo.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtdeiaaidm.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gthtbvkcip.html


<!-- 参考信息 -->