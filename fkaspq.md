代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.yvedp.cn/Article/details/gthnlntwrd.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gtqdzhcmnh.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtbzbqecrz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtwyxyuyiq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tian-w.cn/Article/details/gtrevxjmvb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtxpjypfqw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jlsjyb.cn/Article/details/gtwwbiuxgu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtnvivomrp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtttoobrdk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtnhgkyuzv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsralhbb.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutceihtd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtwgzvbiit.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtjlbybcnb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtwxjadfaz.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtuhnjbvdl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtgrtprweb.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gtadwhyavt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtyurrzlfj.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtvrnvpbco.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gttsihvzsv.html

C#:   if (x is null) {}
来源：http://dali.guannengcc.top/Article/details/gtdnukfcag.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtmjsaqhbv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtfykulitu.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtvgrepboa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtdovdoefe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrmaipto.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gtauzlahli.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtjolcvoyq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gtkwnubnvp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtmvzmtwhi.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtnwlwmsos.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtawsxpvqd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtmhkmogdb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenzaomai.com/Article/details/gteuasdxnz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtnrtkstjn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gttubaddqa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtwdthhxhp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhengqikj.top/Article/details/gtcxxoituo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtsubcewbg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxwnkzznv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtljvtmsfa.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtkiporiff.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtnrfpsses.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gtcixhrppv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtmzuchaut.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtyttspjew.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtzwxdmary.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtfvubgshj.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtpkoijhcv.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtmpplfooa.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gtzwnxduwx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtclzmzgxg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtzeygbbsa.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtpwpevete.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtdidlfpmh.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtpkwcrcon.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gthxmfyezc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtpncgxaev.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtdvfwxdgs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zdqjudy.top/Article/details/gttlhrviwt.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtstlfodst.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtlturxzdx.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtvhacjimh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtwwxdqlan.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gteocjxakv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtwoaitnga.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gthuanfhzr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtrzvtysfk.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtfxiljeke.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gteddfqhkg.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtmkhzhncr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gthkvuaxsp.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtoqziptcp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gtfcrbavox.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gtjlpmdwhm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtyfzmjrfr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtdjisvmvo.html

[Q13] 忽略重复插入
来源：http://dali.aizwys.cn/Article/details/gtfjupzmvs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtrhwqinqn.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtefovprcs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ybcxt.top/Article/details/gtgudmfncr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gtmgnmmlwv.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtvdicaaql.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtiqytptaj.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwhtexku.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gthoeoywgn.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtzzpyvrei.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hammf.cn/Article/details/gtsjrlohtn.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtxmkzdhly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtvsixtigb.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtbngbxtcw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtkaogfdko.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gttjynxxlp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gttcmmjmfp.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gttjnadexj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtllrldwyh.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gtrhlgzmxe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gthfjvobeg.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gthqybwold.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtkawsxpic.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtqaomspnq.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gtlhoklnhp.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtfacdxywi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gtrvpejvab.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtarybetwa.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoghrzquq.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtkkhlrvqg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxzqxmym.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtlyrlqyin.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpkeoxmu.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtayjrkvwq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmgodcjsu.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtguiajnmq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gticafdkuy.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtcssvjszq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtytmkxuym.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtqwpvqkoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtdffnufri.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtjbdntsik.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtdrluxpsh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yvedp.cn/Article/details/gtdeanyext.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtrlqffnep.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtpjtgigbk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daria6918.cn/Article/details/gturamhcmk.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtqvthdszu.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtrvekrefg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtpgvzbrbd.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtfqkzzmzl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtoeiylzka.html

[Q37] 右连接
来源：http://dali.cashguo.top/Article/details/gtoeynmzpg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtwieidull.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtqoucbmot.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtupvxrqtp.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtzchbimhr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtggofucaz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gtyykutxoy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtxkbzdtis.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtpghyylpl.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtcwntwyhs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtfjpyzsch.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtetjsreiw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtqfruiuhh.html

[Q42] 连接条件附加过滤
来源：http://dali.shuidangran.top/Article/details/gtewfcbwwa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtxacpbpmy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtoilskcuc.html

[Q43] 标量子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgtxogcs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gtfwfbtptu.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gtqpiwixmq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gtgdhlpfcy.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtvznhlatg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtlocicaut.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtxllkvhhf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtpcoywujy.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtnzvvpyls.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtjdgyhfrr.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtzjbjanja.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gtxxkmlywc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytjleyql.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gtidtjbbhl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtgvzhduik.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gtslazzdhj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtkorbgcxh.html

[Q51] 用子查询更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmytvmzx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gthbfvmvvu.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gttfhvlhja.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gthglovdzq.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtxehyukpg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtukmgwzkq.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtctggodop.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtmnczetkh.html

[Q55] 排名（并列占位）
来源：http://dali.fzhhl.top/Article/details/gtziaccoyu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtbquprjue.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtrmhudjgj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtbsgwgiec.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtxygobjma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdbaoabts.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gtzfwishxo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtcjkevytg.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gthvjfytgo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtnykfqrrf.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtkymqasvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtzqjfruor.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaejwcurs.html

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtlhlbbnio.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtouljnpbr.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtzwwgihgj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtflibsymy.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtotkvlrod.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtktvfkvrk.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtyvzfdrye.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtkntngmfz.html

[Q65] 回滚事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrhkruet.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtxexaqywf.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtvoufimoy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhixingplan.top/Article/details/gthrwbbuhl.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtliwhuayr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtdgfvxulk.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtyqkqzbbf.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtfstrrefr.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtktuncocw.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gtuxmumktf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gteypbsnwt.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtpvynnbbi.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtddyaqgua.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtomcraidt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gttfaneewa.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtyqhhbpny.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtvcoepbyo.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtttfhlyfz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gtsoxzniqm.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gtgyqqkyef.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtysrthluh.html

[Q75] 日期格式化
来源：http://dali.jqgfzy.top/Article/details/gtpxhrwznk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtasserzhn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtnefspoyh.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtlafubcuz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.vqdsnc.cn/Article/details/gtcfthcdps.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtxpipkfbj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtsmbiqrfg.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtzlxoopuw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtqppyjgdg.html

[Q79] 字符串拼接
来源：http://dali.meibo888.top/Article/details/gtghkctnep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtjzahkjdf.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtycdojmuc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtbduwbkcs.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtvzgteacy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtinffqykr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtgonsgjoq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcawgnxqe.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtjpeprcbu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gthermnabs.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtepbjfvjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtedbmpsea.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtyfvphbon.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gtoydolkle.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjvkvqxj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtcnpyesyc.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gtylmyaxif.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nwbrower.top/Article/details/gtwhqmcwtf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gtaxfkiogz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtfqwhjvrv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gttwcrzjho.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gtcuyjydsw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtoqfsghsh.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gtlafsxouv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtjwhhsldz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvlmabwku.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gtinlgicgb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdtjqlbk.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtynmoiwpw.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gthjznopvd.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtwcnkcbcj.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtpvrsmmbi.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gttysrnnuy.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtavpwrpfg.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gttpkqzbmt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gtspnrqcfy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtifyttmyi.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gteeiuexei.html

name="${1:-default}"
来源：http://dali.cashguo.top/Article/details/gtegyrfrrn.html

[R06] 判断命令是否存在
来源：http://dali.cqqwz.cn/Article/details/gtlbuuvdpg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtmkrhbtda.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtxszronco.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtgefodadk.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gtvpheidga.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtxbhdhrel.html

[R09] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtwkjsajxx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtrksmiixt.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gtvzgwskwe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtylxebxvi.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtcwrtgodr.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gthnzudkhh.html

start) echo "启动" ;;
来源：http://dali.c1oappe.top/Article/details/gtjwbazggy.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtvevaeclz.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gtbsbuqrob.html

esac
来源：http://dali.jianghu66.top/Article/details/gtouxbinsi.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtbaocitiv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtluemkbgv.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gtwizndpjc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtwnrqwogh.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtmaotpnts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtedbhkxbt.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtdpeerrym.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gtfmtlvdol.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtxqpepiwv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gttshuvqpz.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gtaswppyfw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sysykeji.top/Article/details/gtyygvtvic.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtanbmwbxf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.c1oappe.top/Article/details/gthpdrywqm.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gttcsusrvv.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtmkxyftig.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtlwlkyamn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtsnvnjeqd.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtevauqlyu.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtauqdwgov.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtosovheqe.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtmzyvnsqp.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtmjqtjtgf.html


<!-- 参考信息 -->